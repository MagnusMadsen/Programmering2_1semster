# Milepæl Opgave 3 - Joystick og Fjernstyring

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

