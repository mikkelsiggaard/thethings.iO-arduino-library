# 📜 Project template

## 📧Welcome mail

Use the mail template below, to send the initial mail to the customer:

Hej XXX.

Det er mig der kommer til at være projektleder på jeres nye Salecto shop.

Iflg. aftale med min kollega XX, vil jeg gerne have en indledende snak med dig, feks. XXX?

Så vil jeg også lige få mulighed for at introducere dig til hvordan jeres onboarding-forløb kommer til at være.

Desuden er der generelt en hel masse udveksling af data og informationer her i opstartsfasen.

Så velkommen til Salecto, jeg ser frem til at tale med dig :\)

## 📞 Onboarding call

1. Present yourself and what your role in the project is going to be
2. Explain the process for the whole project
   1. Information mail with all the relevant info for the project
   2. Graphic Design + Approval
   3. Possible Data Migration start
   4. Design implementation
   5. Shop configuration, module installation and other integrations
   6. Go for launch
3. If the sales person has specified anything out of the ordinary have a discussion with the customer about this
4. If we are responsible for making a Data Migration, ask them if we should start this immediately or at a planned point in time
5. Schedule a time for when the walk-through of the backend system will take place
6. Ask the customer when they will be ready to have a talk with our Graphic Designer

## ℹ Information mail

Hej **xxxxx**,

Tak for snakken tidligere – jeg glæder mig til at komme i gang med den nye webshop :-\)

Vil du sende nedenstående retur til mig?

**Nuværende shopsystem**

Backend-link:

Brugernavn:

Adgangskode:

**DK Hostmaster**

Dette skal vi bruge for at kunne sætte shoppen live, da vi skal pege domænet over på vores servere.

Brugernavn:

Adgangskode:

**DNS-administration**

For at kunne sikre at alle DNS-records som er opsat på dit domæne også bliver opsat hos os når vi flytter domænet over til os, vil vi gerne bede om enten at få adgang til kontoen hvor I administrere jeres DNS, eller få en eksport af indstillingerne. Er I i tvivl om hvor jeres DNS-records kan findes, så kan I slå jeres domæne op på denne service og derigennem få et hint om hvor jeres domæne administration kan findes.

[https://mxtoolbox.com/DnsLookup.aspx](https://mxtoolbox.com/DnsLookup.aspx)

**Google Analytics**

Vi vil rigtigt gerne kunne følge med i shoppens performance. Til det vil vi meget gerne kobles op på Google Analytics via vores bruger: [online@salecto.dk](mailto:online@salecto.dk)

Du kan finde en guide til hvordan man gør det her: [https://support.google.com/analytics/answer/1009702\#Add](https://support.google.com/analytics/answer/1009702#Add)

**E-conomic**

Det skal vi bruge for at kunne lave integrationen så al bogføring kan ske \(semi\)automatisk. Bemærk venligst at vi er nød til at have administrator-adgang for at kunne oprette forbindelsen til shoppen. Det kan enten være du opretter en ny administrator, som du kan slette igen efter vores arbejde er færdigt, men du kan også bare give mig oplysninger på din nuværende administrator-bruger.

Vi gør brug af følgende modul: [https://www.tric.dk/guides/magento-economic/](https://www.tric.dk/guides/magento-economic/) Her kan i læse nærmere hvilke indstillingsmuligheder der er.

Aftalenummer:

Brugernavn:

Adgangskode:

Såfremt du bruger VISMA Connect, skal jeg bede om følgende:

Email-adresse:

Adgangskode:

**Storebuddy**

For at kunne integrere shoppen med Dinero, skal vi bruge den service der hedder Storebuddy. Så der bedes du oprette en konto, og sende login-detaljerne retur.

Brugernavn:

Adgangskode:

**Facebook Pixel**

Der er også bestilt at der skal indsættes en Facebook Pixel.

Det er bedst at undgå at oprette en Facebook Pixel på ens egen personlige annonce-konto/private profil.

I stedet skal man oprette en Business Manager-konto, hvilket du kan gøre her: [business.facebook.com/create](https://business.facebook.com/create)

Derefter kan du følge denne guide til at få oprettet en Facebook Pixel: [https://www.facebook.com/business/help/952192354843755?id=1205376682832142](https://www.facebook.com/business/help/952192354843755?id=1205376682832142)

Facebook Pixel ID:

**Mailchimp**

Vi skal også have lavet en integration til Mailchimp.

Hvad der er opsat i Mailchimp af segmenteringer, kampagner med videre er ikke noget Salecto supportere i. Vi skaber ”blot” connection fra shop til Mailchimp.

Da Mailchimp har fået lavet 2-faktor-godkendelse, så vil vi meget gerne oprettes som bruger med administratorrettigheder.

Det er der en guide til her: [https://mailchimp.com/help/manage-user-levels-in-your-account/](https://mailchimp.com/help/manage-user-levels-in-your-account/)

Vi vil gerne inviteres på email-adressen: [support@salecto.com](mailto:support@salecto.com) \(alternativt med brugernavnet ”salectoaps”\).

**Shipmondo \(Tidl. Pakkelabels\)**

Jeg vil rigtigt gerne lave en fragtopsætning til dig via den service der hedder Shipmondo. Det er et system vi generelt har rigtigt gode erfaringer med og hvor det er nemt at skifte eller tilføje nye fragtleverandører.

Det kræver dog at man har en konto ved Shipmondo. Man kan oprette en ny konto her: [https://shipmondo.com/dk/](https://shipmondo.com/dk/)

Brugernavn:  
Adgangskode:

Udfyld venligst nedenstående tabel med jeres data om hvilken fragt-opsætning der konkret skal laves.

| **Leverandør** | **Service** | **Vægtinterval** | **Pris for kunden** |
| :--- | :--- | :--- | :--- |
| PostNord | Med omdeling | 0-5 Kg. | 49 Kr. inkl. moms |
| PostNord | Med omdeling | 5-10 Kg. | 69 Kr. inkl. moms |
| GLS | Til Pakkeshop | 0-10 Kg. | 45 Kr. inkl. moms |
| GLS | Til Erhverv | 0-5 Kg. | 39 Kr. inkl. moms |
| GLS | Til Erhverv | 5-10 Kg. | 49 Kr. inkl. moms |

## 🍥Design Approval Process

Describing the basic procedures that needs to be done for a webshop design to be approved.

![](.gitbook/assets/design-approval-proces.png)

### Design Start

Onboarder creates a Wrike tasks using the request [\#171 Salecto Designs](https://www.wrike.com/workspace.htm?acc=506669#/forms?formid=329746).

The graphic designer has the initial conversation with the customer, starts creating the necessary design files, uploads them to InVision and informs the CTO and Head of Production that an internal acceptance review can start.

### Acceptance Review

#### Internal

The CTO and Head of Production will go over the design files in InVision and verify that every single design element can be implemented with our current technology stack.

They may also inform the Graphic Designer about other possible design elements, that is easier to produce and maintain.

The CTO and Head of Production will inform the Graphic Designer whether or not the design has been accepted.

#### External

The Graphic Designer will now send the links to the design files in InVision to the customer.

There can be multiple iterations at this point in time. If there are important changes in these iterations, it is up to the Graphic Designer to get acceptance again from the CTO and the Head of Production.

If the customer accepts all design files the Graphic Designer will inform the Onboarder.

### Implementation Meeting

The Onboarder will create an invite to a meeting with the primary Front-end Developer along with the InVision-links to the design files.

This meeting is the Onboarders chance to proactively inform about details not included in the design files, and it is the Front-end Developers chance to ask question about how specific elements should be implemented.

The goal is to prevent re-work from happening, have a stable result and for the customer to be able to maintain it themselves.

