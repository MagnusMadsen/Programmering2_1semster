# Milepælsopgave 2 - Robotstyret arm 

## Gruppe 4, Medlemmer: Daniel, Lexar, André, Sebastian & Magnus 

### Komponentliste

4x Servomotor
3D-printet arm
3D-printet base
3D-printet Spacers
MDF-skåret base


## Læringsudbytte i de individuelle fag 
### Projektarbejde
Dette projekt har givet os mulighed for at anvende og integrere avancerede teknologier som lasercutting og 3D-printning i udviklingen af en modulær og funktionel roverplatform. Lasercutting gav os præcisionsværktøjer til hurtigt at fremstille og iterativt tilpasse basens design, mens 3D-printning tillod os at skabe komplekse, skræddersyede komponenter. Denne iterative proces fremhævede vigtigheden af hurtig prototyping og designoptimering. Vi udviklede adskillige versioner af Roveren, hvilket ikke blot forbedrede den fysiske struktur, men også gav os dybere indsigt i, hvordan forskellige materialer og konfigurationer påvirker den samlede systemydelse. Den iterative fremgangsmåde har skærpet vores evne til kritisk at evaluere og forbedre teknologiske løsninger.

### Programmering
Softwareudviklingen fulgte en streng objektorienteret tilgang for at maksimere modularitet og genanvendelighed. Overgangen fra structs til klasser var en bevidst designbeslutning, der afspejlede vores intention om at skabe en skalerbar kodebase. I første fase implementerede vi strukturer for at etablere en grundlæggende datastruktur til mindre projekter, såsom vores bankapplikation. Derefter migrerede vi til klasser og objekter, hvilket gjorde det muligt at definere og manipulere komplekse datastrukturer på en mere organiseret måde. I Rover-projektet blev denne tilgang anvendt til motor- og sensorkontrol, hvilket ikke blot forenklede koden, men også reducerede risikoen for fejl og gjorde fremtidige udvidelser nemmere. Vores fokus på softwarearkitektur har givet en robust platform for yderligere systemintegration og optimering.

### Indlejrede systemer og elektronik
I arbejdet med indlejrede systemer har vi fokuseret på effektiv spændingsregulering og præcis motorstyring. Anvendelsen af buck-converters muliggjorde en præcis justering af strømforsyningen, hvilket var afgørende for stabil drift af de individuelle dele på roveren. For at sikre en dybere forståelse af kredsløbsdynamik implementerede vi Kirchhoffs lov til analyse af forskellige fiktive kredsløb. PWM-styring blev undersøgt som en central metode til styring af både vores DC- og servomotorer, hvor vi analyserede respons og effektivitet under forskellige belastninger. Vi anvendte avancerede måleinstrumenter, herunder oscilloskop og triple channel power supply, hvilket gav os et Frekvens og Hz datasæt til optimering af det elektroniske kredsløb. Denne proces understregede nødvendigheden af præcise målinger og analytiske værktøjer i systemudvikling, da det påvirkede vores duty circle og den pulseregulering der styrede vores komponenter. 

### Trådløs forbindelse
Ved at konfigurere ESP32 som et access point skabte vi en trådløs grænseflade til styring af eksterne enheder såsom LED’er. Denne øvelse demonstrerede potentialet for trådløs kontrol i fremtidige iterationer af Roveren, hvor fjernstyring og realtidsdataoverførsel vil være afgørende for at udvide systemets automatikation og fjernstyrelses funktionalitet.

## Rover optimering

### Basens udvikling
I forsøget på at finde det optimale materialevalg og design til Roverens base eksperimenterede vi med MDF, plexiglas og 3D-print. MDF og plexiglas viste sig at være strukturelt robuste, men deres vægt havde en negativ indvirkning på systemets energieffektivitet og sensornavigation. Den 3D-printede base, omend let og kompakt, introducerede nye udfordringer med hensyn til stabilitet under dynamiske belastninger, især når den mekaniske arm var i brug. Vi udviklede også en specialdesignet batteriboks med integreret buck converter for at sikre præcis og stabil strømfordeling til systemets forskellige moduler. 

### Udfordringer
Projektet afslørede flere tekniske og metodologiske udfordringer. Integration af klasser og structs i koden medførte kompleksitet og fejlsøgning, hvilket krævede en refaktorisering af hele kodebasen. Vi erfarede, at en konsistent objektorienteret tilgang var mere hensigtsmæssig for at sikre en skalerbar og vedligeholdelsesvenlig struktur. Hardwareudfordringer opstod også som følge af ændringer i basens fysiske dimensioner og vægt, hvilket påvirkede sensorernes effektivitet. Sensorernes blinde zoner og nedsat præcision i navigationen krævede gentagne justeringer og designiterationer. Energiforsyningen viste sig at være en kritisk faktor. Med forskellige spændingskrav fra ESP32, H-broer og servomotorer var det nødvendigt at implementere et mere avancerede strømstyringssystem. En kombination af buck converter og en serieforbundet batteripakke blev anvendt for at opnå optimal strømforsyning. 

Desuden stødte vi på et mindre problemer med kodningen af den mekaniske arm. Selvom vi kunne få armen til at udføre de ønskede bevægelser ved brug af vores controller, opstod der et uventet fænomen: efter at have frigivet controlleren, vendte armen konsekvent tilbage til sin nulposition. Denne adfærd indikerer en ukorrekt specificering i positioneringskoden. 

### Styrker ved Roveren
På trods af de mange udfordringer er de nuværende iterationer af Roverne kendetegnet ved en høj grad af modularitet og fleksibilitet. Den objektorienterede softwarestruktur muliggør nem tilføjelse af nye funktionaliteter, mens den iterative udviklingsproces har sikret en velafbalanceret hardwareplatform. Kombinationen af letvægtsmaterialer og avancerede strømstyringsløsninger gør Roveren til en fremtidssikret platform, der kan skaleres og tilpasses til en bred vifte af applikationer. Denne proces har styrket vores forståelse af komplekse systemintegrationer og givet os en solid basis for videreudvikling og forskning inden for robotteknologi.







