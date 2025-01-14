
# OLA11 Tværfaglig - reflektioner

### Af Magnus Mathias Bøg Madsen

Studienr: OITD27954
Holdnr: ITOE24

UCL Seebladsgade 1, Odense, 5000


## Milepæls Opgave 1 - Base 

## Gruppe 4, Medlemmer: Daniel, Lexar, André, Sebastian & Magnus 


### Komponentliste

    8x Hjul
    8x Motor
    5x Sensor
    3x H-broer
    2x ESP32 Wroom 
    2x Hvide dioder
    2X Røde dioder
    2x Pleksi base
    4x Fumlebræt 
    Mange ledninger 


### Beskrivelse af basen

    Som det første planlagde vi som gruppe mål og visioner samt brainstormede på, hvad vi ønskede at opnå inden for uddannelsens tidsramme. Planlægningen var afgørende, da den gjorde det muligt for os at følge vores fremskridt og se, hvor meget vi udviklede os. Det gav os også motivation til at fortsætte med at idéudvikle, hver gang vi løste et problem.

    Vores base startede med en simpel plade, hvor alt blev samlet. Det hjalp os med at visualisere konceptet og videreudvikle det, vi havde lært, hvilket gav ny motivation for hver funktion, vi tilføjede. Dernæst monterede vi motorer og hjul, som vi fastgjorde med strips. Herefter placerede vi H-broerne, så vi kunne styre motorerne. Da vi var sikre på, at alle forbindelser fungerede korrekt, lodede vi ledningerne fast for at undgå løse forbindelser, der kunne skabe problemer i koden eller påvirke komponenternes funktion.

    For at sikre, at vi nåede afleveringsdatoen for milepælen, byggede vi to versioner af roveren. Den ene blev styret mekanisk via knapper og en strømforsyning, og den anden blev styret trådløst via en ESP32. Roveren med ESP32 blev kodet med en simpel loop-struktur (void loops), hvor vi definerede bevægelser som frem, tilbage, højre og venstre med de rette analogWrite-værdier. Vi delte os op i to teams, hvor nogle arbejdede på at tilføje nye funktioner, mens resten finpudsede de grundlæggende funktioner. Alligevel sikrede vi os, at alle i gruppen blev inddraget og holdt opdateret.

    På dette tidspunkt havde vi en funktionel base, der kunne køre. Men da vi var foran tidsplanen og stadig motiverede, tilføjede vi tre sensorer, der via if-statements i koden kunne styre motorerne automatisk baseret på sensorinput. Vi blev også enige om, at en rover ikke ville være komplet uden lys, så vi monterede baglygter, som blinkede, når den bakkede, hvilket vi styrede via analogWrite i vores “Reverse”-funktion. Vi kodede også en knap til at tænde og slukke roveren med digitalRead, så den blev nemmere at styre.

### Hvilke udfordringer har jeg/vi haft

    De første fire uger har været en stejl læringskurve. Det er imponerende, hvor meget man kan lære på kort tid, men det har også været udfordrende at følge med. Der har været mange lektier og opgaver, som alle har været vigtige, hvilket gjorde det svært at prioritere fagene.

    Gruppearbejde er en stor del af uddannelsen, hvilket betyder, at der har været meget pres på at finde fælles motivation, kommunikere godt og løfte gruppens indsats for at opnå et godt resultat. Det har også krævet, at vi skulle gøre plads til forskellige personligheder og vide, hvornår vi skulle tage diskussioner, og hvornår vi skulle lade dem ligge. Selvom vi som gruppe har fungeret godt, er det en løbende udfordring, vi skal være bevidste om.

    Jeg har haft udfordringer i alle fag, lige fra at få programmerne til at fungere til at forstå grundlæggende kode eller breadboard-opbygning. Gennem oplæsning, hjælp fra gruppen og feedback fra underviseren er mange af de udfordringer, vi har mødt, blevet løst. For eksempel havde jeg svært ved at forstå H-broer, men efter at have eksperimenteret med dem og sat mig ind i, hvordan kondensatorer fungerer, har jeg fået en bedre forståelse. Do-while loops er dog stadig noget, jeg skal arbejde videre med. Elektromagnetisme og strømoverførsel på elektronisk niveau er også områder, hvor jeg stadig er usikker.


### Hvad er jeg stolt af

    Jeg er meget stolt af det gode samarbejde, vi har haft i gruppen. Vi har konstant presset grænserne for, hvad vi kunne opnå med vores læring, og det har resulteret i en funktionel rover, der kan køre “automatisk” baseret på sensorinformationer. Jeg er også stolt af, at vi som gruppe har prioriteret hinandens styrker og arbejdet som et team i stedet for at konkurrere internt om, hvem der kunne mest.

### Selvreflektion 

    Teknisk set har jeg lært en del om både hardware og programmering, specielt i forhold til integrationen af forskellige komponenter som motorer, sensorer og H-broer. Før dette projekt havde jeg meget lidt til ingen erfaring med H-broer og programmering som helhed, men nu har jeg opnået en dybere forståelse af, hvordan man kan styre indlejrede systemer, både gennem kode og hardware. Det var utrolig spændende at se, hvordan små justeringer i koden kunne påvirke roveren og dens bevægelser.

    Dette projekt har indtil videre givet mig mulighed for at identificere flere forskellige svagheder, og jeg ved nu, hvilke områder jeg skal arbejde videre med for at styrke mine kompetencer.

    På et personligt plan har jeg lært meget om samarbejde i grupper. Jeg har oplevet, hvor vigtigt det er at kunne lytte til andres idéer og indgå kompromisser, især når forskellige personligheder skal arbejde sammen. Jeg er blevet bedre til at kommunikere klart og konstruktivt med mine medstuderende, hvilket jeg føler har gjort vores gruppe mere effektiv.

    En vigtig læring for mig har været at give plads til andres input, samtidig med at jeg har været bevidst om, hvornår det var nødvendigt at tage en beslutning eller handle hurtigt. Dette har lært mig en balance mellem at tage ansvar og inddrage mine gruppekammerater i beslutningsprocessen.

    Jeg er stolt af, hvordan jeg har håndteret de mange tekniske udfordringer undervejs. Jeg startede ud med begrænset viden om visse emner, men i stedet for at give op har jeg arbejdet målrettet på at lære mere. Når jeg har stået over for problemer, som f.eks. at få H-broer til at fungere, har jeg brugt tid på at eksperimentere og søge hjælp, hvilket har været en lærerig proces. Jeg har også indset, hvor vigtigt og værdifuldt det er at kunne spørge om hjælp fra mine gruppekammerater og undervisere, når jeg støder på noget, jeg ikke forstår fuldt ud.



## Milepælsopgave 2 - Robotstyret arm 

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


## Milepæl Opgave 3 - Joystick og Fjernstyring

## Gruppe 4, Medlemmer: Daniel, Lexar, André, Sebastian & Magnus 

## Komponentliste 

2x joystick
1x pcb board
2x SMD capacitor
2x SMD resistor
1x liligo T-display
6x jumper wires
2x Knapper 


## Beskrivelse af joystick samt hvordan i har fået fjernstyring til at virke

Som en del af vores arbejde indenfor Embedded-Systems, Programmering, Netværk og projektledelse har vi udviklet kompetencer i trådløs kommunikation ved brug af ESP-NOW. Der har været en del fejl på Joystikkets PCB som har gjort det nødvendigt at omlodde flere af forbindelserne til nye pins så vi har kunne sende de rette data fra de rette pins. Foruden dette har vi skulle samle og skrue joystikket sammen, samt sammensætte de sidste dele af roveren og implementere dette i koden. 

## Projekt
I projekt har fokuserede været på udviklingen af vores Rover. Interne gruppemøder blev brugt til at prioritere opgaver og fastlægge en strategi for projektet. Vi designede et standardiseret layout til ESP32, så de samme pins blev anvendt uanset Rover-base. Dette gjorde det muligt at skifte base uden at ændre koden, hvilket effektiviserede Roverudviklings processen.

Der er blevet arbejdedet ud fra kravspecifikationerne, for at sikre fokus og effektivitet. Samt for at minimere potentielle fejl og undgå unødvendige problemer. Denne strukturerede tilgang sikrede både fleksibilitet og robusthed i vores løsning.

## Embedded systems 
Embedded systems har omfattet en række tekniske emner med fokus på kredsløb og komponenter, robotarmen, joystick, ESP32-kommunikationsprotokoller og binære koder. 

Desuden lærte vi at lodde SMD-komponenter på vores controller-PCB, hvilket involverede præcisionsarbejde med ultra små modstande under brug af et præcistions-mikroskop. 

## Programmering
I programmering har forløbet taget meget fokus i ESP-NOW som bruges til kommunikation mellem ESP-LillyGo og ESP-32. ESP-NOW er en 2,4 GHz frekvens kommunikationsprotokol, som giver mulighed for at kommunikere selvstændigt via egen trådløs netværk. ESP1 Sender, kender ESP2 modtager's MAC-adresse og kommunikerer herigennem med hinanden. 


#### Er der blevet brugt structs, funktioner, classes, og til hvad?

En struct kan defineres som en datastruktur, hvor i praksis bruger man structs til at organisere data på en mere overskuelig måde. Det er især nyttigt, når vi har flere attributter, der logisk hænger sammen. For eksempel, gør vi brug af struct til at sende data imellem joystik og rover fordi det gør det muligt at samle flere forskellige datatyper under ét tag. 

Klasser er et kraftfuldt værktøj i objektorienteret programmering, der gør det muligt at modellere komplekse systemer. F.eks. har vi gjort brug af classes i de fleste dele af vores kode for at gøre det mere overskueligt at kalde forskellige funktioner og voids i vores main kode. Derudover bliver src koden nemmere læselig og skaber et bedre overblik. 

Funktioner tager ofte input, udfører en behandling eller operation og kan returnere et resultat. Men funktioner kan også være “void” (dvs. ikke returnere noget), som det ofte ses i indlejrede systemer som vores. Størstedelen af koden er derfor bygget op af void funktioner som skaber udførslen af de indlejerede komponenter på roveren og joystikket. Et par få eksempler kunne være vores rover og arm styrings-funktioner som nok er de vigtigste funktioner i hele koden. 


#### Hvilke libraries er blevet brugt og til hvad? (#include statements)

Igennem projektet er der blevet tilføjet mange forskellige biblioteker som på hver sin måde påvirker individuelle dele af koden. ESP-now som er med til at sende koden frem og tilbage. Der er VL53L0X som er vores sensor bibliotek. Alle biblioteker har tilfælles at gøre koden nemmere og derved kalde på funktioner som allerede ligger i disse biblioteker. 


## Udfordringer undervejs:

### Hvilke udfordringer mødte i undervejs?

I vores arbejde med roveren har vi stødt på flere udfordringer, som har påvirket både præcisionen og funktionaliteten af roveren. En af de primære udfordringer under denne milepæl har været at opnå en glidende bevægelse af armen, således at den ikke udfører hakken eller ryk i de positioner. Denne mangel på smidighed har været et centralt fokus. 

Desuden har vi haft vanskeligheder med at integrere knapperne korrekt i koden. Vores oprindelige implementering af knapstyring resulterede i knapværdierne ikke skiftede fra true til false som ønskede. Dette skete fordi at knappen kun fungere som strømledene når den var holdt inde. Denne fejl har krævet yderligere debugging og tilpasninger for at sikre korrekt og pålidelig interaktion med knapperne. 

Den hidtil største udfordring har været multi-threading og dertil core/task modulering. Hver gang vi har tilføjet en ny task har der været problemer med sensor, motor og andre funktioner i koden. Dette har medført restruktureing af flere omgange over hele koden. 

### Hvordan løste/har i tænkt jer at løse det?

Vores fejl med arm-præcision og funktionalitet blev løst ved at ændre vtask delay'en og tilpasse vores increment ændringer. 

vores knap-problem blev løst ved omstruktureing af vores knapfunktion så den fungerede med en knapstate som skiftede hver gang knappen så en ændring og derved ikke var afhængig af direkte respons fra knappen. 

Vores multi-threading problem har ikke rigtig nogen specifik løsning. Det har været små ændringer rundt omkring for at få de enkelte dele til at virke. Dog har det været nødvendigt at implementere statiske voids og omdanne funktioners resultater til et objekteret datastruktur som vores main multi-thread kode kunne forstå og håndtere. 

### Hvorfor tror i de opstod?

Problemerne er opstået på baggrund af uvidenhed overfor funktionallitetten af de individuelle funktionstrukturer og komponenter.








    


   

   