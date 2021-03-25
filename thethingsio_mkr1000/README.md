# thethings.iO-Arduino-MKR1000-library

Arduino libraries and examples to connect to [http://thethings.iO](http://thethings.iO)

If you want to use the WiFi client you should `#include <SPI.h>` `#include <WiFi101.h>` before including this library.Then include this library with `#include <thethingsiO_mkr1000.h>`. Before using any client from this library, the WiFI connection should be initialized. Check the examples for mor details

```text

  Serial.println("Connecting MKR1000 One to network...");
   // attempt to connect to Wifi network:
  while ( status != WL_CONNECTED ) {
    Serial.print("Attempting to connect to WPA SSID: ");
    Serial.println(WIFI_AP);
    WiFi.begin(WIFI_AP, WIFI_PWD);
    // wait 10 seconds for connection:
    delay(5000);
    status = WiFi.status();
    status = LWiFi.status();
```

```text
thethingsiOWiFi();
thethingsiOWiFi (String token);
```

Create a new client. The first form is used to activate new things with the `activate(String)` method. The second form sets the token for an already activated thing.

```text
String activate(String activationCode);
```

Activates a thing with the given activation code. The token for the Thing is automatically set and returned. In the case of failure an empty string is returned.

```text
String getToken();
```

Returns the token associated with this thing.

```text
void addValue(String key, String value);
void addValue(String key, double value);
```

Adds the key/value pair in the buffer of data to be sent. Since those pairs are stored in memory until the data is sent the user should be aware of the memory.

```text
String send();
```

Send and flush the data stored in the data buffer \(added with the `addValue` functions\).

```text
String read(String key);
String read(String key, int limit);
```

Get the last `limit` key/value pairs sent to this thing with the given key. In the first form , the last 10 items are returned.

```text
void subscribe();
int available();
String read();
```

Subscribe, check for data to be read and actually read the data from the thing. This is used to listen and get the data sent to this thing. &lt;/article&gt; &lt;/div&gt;

&lt;/div&gt;

&lt;/article&gt; &lt;/div&gt;

&lt;/div&gt;

&lt;/body&gt; &lt;/html&gt;

