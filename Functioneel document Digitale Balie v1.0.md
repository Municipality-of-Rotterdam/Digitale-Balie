||![Kleine logo gemeente Rotterdam](Aspose.Words.1256f77a-ef20-4852-b692-f017dd858094.001.jpeg)|
| :- | -: |


||**Digitale Balie**|
| :- | :- |
||Functioneel ontwerp|
||<p>**Van**</p><p>R.K.J. Bruijnzeels</p><p></p>|
||<p>**Datum**</p><p>30 november 2021</p><p></p>|
||<p>**Cluster**</p><p>Bestuurs- en Concernondersteuning</p><p></p>|
||<p>**Afdeling**</p><p>IM&P Projecten</p><p></p>|

|<p>**Datum**</p><p>10 maart 2021</p>|<p>**Pagina**</p><p>PAGE  \\* Arabic  \\* MERGEFORMAT3 van NUMPAGES  \\* Arabic  \\* MERGEFORMAT3</p>|
| :- | -: |

![Kleine logo gemeente Rotterdam](Aspose.Words.1256f77a-ef20-4852-b692-f017dd858094.001.jpeg)

**Inhoudsopgave**





` `**TOC \o "1-4" \u \t "Kop 1;1" 1**	**Aanleiding	 PAGEREF \_Toc90552190 \h 3**

**2**	**Doel	 PAGEREF \_Toc90552191 \h 4**

**3**	**Voordelen	 PAGEREF \_Toc90552192 \h 5**

**4**	**Functioneel overzicht	 PAGEREF \_Toc90552193 \h 6**

**5**	**Opbouw van de applicatie architectuur (schematisch ontwerp)	 PAGEREF \_Toc90552194 \h 8**

**6**	**Componenten	 PAGEREF \_Toc90552195 \h 9**



1. # **Aanleiding**
De Digitale Balie applicatie, die voor de gemeente Rotterdam is gebouwd, wordt gebruikt om verbinding te maken met de burgers van Rotterdam. Het platform is ontstaan vanuit de COVID 19 pandemie waardoor burgers het gemeentehuis niet konden bezoeken en daardoor geen persoonlijke documenten konden opvragen, een geboorteaangifte konden doen, persoonlijke informatie op konden vragen om te kunnen trouwen, enzovoort. De gemeente was op zoek naar een manier zodat de burgers verzoeken konden doen en diensten konden afnemen zonder dat er reisbewegingen naar het gemeentehuis moesten plaatsvinden. Daarnaast moet de Digitale Balie applicatie ervoor zorgen dat er geen fysiek contact nodig is tussen de burger en de gemeente ambtenaren en er een volledige digitale afhandeling van de dienstverlening kan worden gedaan zonder concessies op vertrouwelijkheid, persoonlijkheid, gebruiksvriendelijkheid en snelheid.

De Digitale Balie applicatie is ontwikkeld door CLEVR in opdracht van de Gemeente Rotterdam. De applicatie is ontwikkeld op het low-code platform Mendix. 
1. # **Doel**
Het doel van de applicatie is om persoonlijke dienstverlening mogelijk te maken tussen de gemeente en zijn burgers/ ondernemers. De Digitale Balie applicatie dient als complementaire dienstverlening aan de baliedienst in het gemeentehuis en ondersteund vele functies die normaal fysiek afgehandeld worden in een digitale omgeving. Denk hierbij aan het uitvoeren van transacties of het overleggen van documenten.

Daarnaast is er een onderliggend doel wat wordt ingevuld door de Digitale Balie applicatie, te weten het voorzien in de groeiende vraag naar digitaal zakendoen met gemeenten en overheid.



De app is een communicatieplatform waarin twee partijen kunnen videobellen met de benodigde processen en dienstverlening eromheen. Documenten uploaden, inloggen met overheid specifieke login mechanismes, chatten, alle informatie toevoegen aan dossiers, is slechts een greep uit de functionaliteiten die met deze app kunnen worden afgehandeld. En alles is veilig terwijl de gebruiksvriendelijkheid (met name voor niet-technische gebruikers) de app zo gemakkelijk mogelijk kunnen gebruiken.


1. # **Voordelen**
De voordelen van de Digitale Balie zijn:

- Een gezicht bij de gemeente – De burger blijft altijd centraal staan (ook de minder digitaal onderlegde burger) en heeft behoefte aan een “gezicht” bij de gemeente. De baliemedewerker kan dat gezicht zijn in de digitale omgeving en daarmee wordt het videogesprek als persoonlijk ervaren.
- Efficiënt en kostenbesparend – Er kan locatie onafhankelijk worden ontmoet tussen de baliemedewerker en de burger. Hierdoor zullen ook minder mobiele burgers de gemeente makkelijker kunnen bereiken. Daarbij zijn ondernemers (met tijdgebrek) makkelijker in staat om gesprekken te plannen in hun drukke agenda.
- Kwaliteit en veiligheid – De burger ontvangt alleen een link en kan de Digitale Balie gebruiken zonder enige installatie van software. Daarnaast zorgt de beveiligde omgeving ervoor dat een burger en medewerker altijd in een veilige omgeving zitten en daarmee de applicatie voldoet aan de gestelde compliance en security eisen.


1. # **Functioneel overzicht**
Hieronder is een overzicht te zien van alle functionaliteiten die onderdeel zijn van de Digitale Balie oplossing.


|**FUNCTIE** |**WERKING** |**DOEL** |
| :- | :- | :- |
|<p>**Single Sign On (SSO)**</p><p></p>|<p>De Digitale Balie beschikt over Single Sign On functionaliteit waardoor accounts gekoppeld aan een apparaat maar eenmalig in hoeven te loggen. </p><p></p>|Makkelijk inloggen in de applicatie voor gebruiksvriendelijkheid. |
|<p>**Gespreksessies aanmaken** </p><p></p>|<p>De applicatie kan naam gebonden gespreksessies aan maken op basis van contactgegevens en koppelen aan geconfigureerde teams, werknemers en zaaktypes. </p><p></p>|Een gesprek(reeks) opzetten tussen medewerker(s) en deelnemer |
|<p>**Afspraken aanmaken en inplannen**</p><p></p>|<p>De applicatie biedt de mogelijkheid om gespreksessies om te zetten in afspraken. Hierbij kunnen datum, afspraakduur, en locatie worden bepaald. De ontvanger krijgt een uitnodiging via de mail</p><p></p>|Een tijdstip en duur plannen aan de gespreksinteractie |
|<p>**Afspraken beheren**</p><p></p>|<p>De applicatie heeft een agenda interface met een overzicht van afspraken per gebruiker. Er kan worden gewisseld tussen het dag overzicht, later geplande afspraken en verlopen afspraken. </p><p></p>|Overzicht in de planning en gesprekken|
|<p>**Email uitnodiging/ integratie**</p><p></p>|<p>De applicatie beschikt over functionaliteit die bij het inplannen van afspraken een uitnodigingsmail stuurt naar de burger/onderneming. Via de link kan veilig worden deelgenomen aan het gesprek. Hierbij kunnen additionele verzoeken worden gedaan zoals het insturen van bestanden voorafgaand aan de afspraak. </p><p></p>|Gemakkelijke en veilige deelname aan het videogesprek voor burgers|
|<p>**Beveiligd videobellen** </p><p></p>|<p>De applicatie beschikt over functioneel videobellen via een peer-to-peer beveiliging</p><p></p>|Een veilige verbinding|
|<p>**DigiD-identificatie** </p><p></p>|<p>De applicatie heeft de mogelijkheid om identificatie mogelijk te maken via DigiD door een SAML/API verbinding. </p><p></p>|<p>Identificatie/ authenticatie van personen en achterhalen van persoonsgegevens </p><p></p>|
|<p>**Live uploaden van documenten** </p><p></p>|<p>De applicatie is instaat om tijdens live videoverbinding documenten en afbeeldingen te uploaden en op te slaan in de applicatie. </p><p></p>|Digitaal documenten overhandigen |
|<p>**Live bestanden tonen**</p><p></p>|<p>De applicatie beschikt over een mediaviewer voor documenten en afbeeldingen die tijdens de live videoverbinding kunnen worden getoond. </p><p></p>|Digitaal documenten overleggen|
|<p>**FAQ raadplegen**</p><p></p>|<p>De applicatie beschikt over functionaliteit om per zaaktype een sectie veel gestelde vragen, beter bekend als frequently asked questions (FAQ) te benaderen die snel antwoord kunnen geven op veel voorkomende vragen tijdens de dienstverlening. </p><p></p>|Tijdbesparing door te informeren over antwoorden op terugkerende vragen |
|<p>**Producten configureren**  </p><p></p>|<p>De applicatie beschikt over de functionaliteit om producten en prijzen te koppelen aan verschillende zaaktypen (soorten dienstverlening) </p><p></p>|Een referentie en prijs koppelen aan verschillende producten van de gemeente zoals een rijbewijs|
|<p>**Betalingen uitsturen en incasseren** </p><p></p>|<p>De applicatie kan live betalingsverzoeken uitsturen van verschillende banken/betaaloplossingen en incasseren door integratie met een betalingsaanbieder*.* </p><p></p>|Girale transactie mogelijk maken|
|<p>**Email en SMS-notificaties** </p><p></p>|<p>De applicatie kan geautomatiseerde SMS en email notificaties uitsturen door integratie met gateway APIs (communicatieoplossingen) </p><p></p>|Trigger afgeven en herinneren aan afspraken |
|<p>**Opslaan en raadplegen van gegevens gesprekssessie** </p><p></p>|<p>De Digitale balie applicatie kan gegevens uit een unieke gespreksessie opslaan en archiveren om gegevens en documenten te kunnen raadplegen en toepassen op een later tijdstip. </p><p></p>|Gegevens inzichtelijk en beschikbaar maken |
|<p>**Documenten printen en exporteren**</p><p></p>|<p>De applicatie heeft de functionaliteit documenten te printen of te exporteren naar een bestandslocatie lokaal of op een gekoppeld netwerk. </p><p></p>|Documenten fysiek kunnen dupliceren en archiveren|


1. # **Opbouw van de applicatie architectuur (schematisch ontwerp)**
De applicatie is opgebouwd uit de volgende modules: 

![Diagram, timeline

Description automatically generated](Aspose.Words.1256f77a-ef20-4852-b692-f017dd858094.002.png)

***Figuur 1:** High level architectuur Digitale Balie applicatie.*

1. De Digitale Balie applicatie is gebouwd in het Mendix low code platform. Binnen de applicatie worden er verschillende losse componenten gebruikt om virussen te scannen, te notificeren en PDF’s te genereren. Er zijn verschillende API’s (integraties) om verder functionaliteit te waarborgen.
1. Het video platform wordt gebruikt om veilig te kunnen videobellen. De oplossing wordt aangesproken via een API en het videobel scherm wordt door middel van een iFrame in de applicatie getoond
1. Er zijn een aantal integraties die niet in de applicatie zijn opgenomen, maar wel degelijk van belang zijn voor de werking van de Digitale Balie. Integraties die binnen het gemeente domein liggen zijn:
   1. Er is een email integratie om berichtenverkeer met burgers beschikbaar te maken
   1. Er is een single sign on module om inloggen op een makkelijkere manier te verwezenlijken
   1. Er is een betaal API waarmee het mogelijk is om dienstverlening digitaal te kunnen afrekenen
1. Daarnaast zijn er ook een aantal integraties die buiten het gemeente domein worden aangeboden. Dit zijn:
   1. Er is een koppeling met DigiD zodat burgers kunnen authentiseren
   1. Er is een integratie met een SMS-gateway zodat burgers een bericht kunnen ontvangen als de afspraak begint


1. # **Componenten**


|` `**​**|**​**|
| :- | :- |
|**Mendix​**|Platform waarmee de Digitale Balie is ontwikkeld en ook het platform waarop de applicatie wordt gehost|
|**Video platform​**|Videocall platform waarbij een API wordt gebruikt om gesprekken te plannen en een iFrame om het gespreksvenster op te nemen in de Digitale Balie|
|**Digid​**|Digid is het NL-inlogmechanisme voor veilig inloggen op publieke diensten. DigiD is onderdeel van de Digitale Balie oplossing en wordt gebruikt om de burger te authentiseren |
|**SMS​**|De sms-gateway wordt gebruikt voor het versturen van sms-berichten naar de burger wanneer een afspraak bijna begint|
|**Email​**|Dit is een module om e-mails te kunnen versturen en ontvangen in de Digitale Balie.|
|**Payment​**|De Digitale Balie is aangesloten op het betalingsproces van de Gemeente Rotterdam.|
|**PDF​**|Dit is een module om PDF documenten te kunnen genereren.|
|**Notificaties**|Dit is een module die onderdeel is van de Mendix omgeving en kan notificaties versturen naar verschillende apparaten en omgevingen|
|**Virusscanner​**|Er is een module toegevoegd aan de Digitale Balie om ervoor te kunnen zorgen dat documenten worden gescand op virussen.|
|**Single Sign On​**|Er is een module toegevoegd aan de Digitale Balie om gebruik te maken van Single Sign On functionaliteit (inlog gegevens van een eerdere inlog actie gebruiken)|



|**Datum**|**Pagina**|
| :- | :- |
|30 november 2021|PAGE  \\* Arabic  \\* MERGEFORMAT3 van NUMPAGES  \\* Arabic  \\* MERGEFORMAT3|

