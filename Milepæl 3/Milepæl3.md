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

En kort gennemgang af hvad denne nye controller kan og hvordan den kommunikerer med roveren.

Som en del af vores arbejde inden for Embedded-Systems, Programmering, Netværk og projektledelse har vi udviklet kompetencer i trådløs kommunikation ved brug af ESP-NOW. Der har været en del fejl på Joystikkets PCB som har gjort det nødvendigt at omlodde flere af forbindelserne til nye pins så vi har kunne sende de rette data fra de rette pins. 

## Projekt
I projekt har fokuserede været på udviklingen af vores Rover. Interne gruppemøder blev brugt til at prioritere opgaver og fastlægge en strategi for projektet. Vi designede et standardiseret layout til ESP32, så de samme pins blev anvendt uanset Rover-base. Dette gjorde det muligt at skifte base uden at ændre koden, hvilket effektiviserede Roverudviklings processen.

Der er blevet arbejdedet ud fra kravspecifikationerne, for at sikre fokus og effektivitet. Samt for at minimere potentielle fejl og undgå unødvendige problemer. Denne strukturerede tilgang sikrede både fleksibilitet og robusthed i vores løsning.

## Embedded systems 
Embedded systems har omfattet en række tekniske emner med fokus på kredsløb og komponenter, robotarmen, joystick, ESP32-kommunikationsprotokoller og binære koder. 

Desuden lærte vi at lodde SMD-komponenter på vores controller-PCB, hvilket involverede præcisionsarbejde med ultra små modstande under brug af et præcistions-mikroskop. 

## Programmering
I programmering har forløbet taget meget fokus i ESP-NOW som bruges til kommunikation mellem ESP-LillyGo og ESP-32. ESP-NOW er en 2,4 GHz frekvens kommunikationsprotokol, som giver mulighed for at kommunikere selvstændigt via egen trådløs netværk. ESP1 Sender, kender ESP2 modtager's MAC-adresse og kommunikerer herigennem med hinanden. 

I koden imellem de 


#### Er der blevet brugt structs, funktioner, classes, og til hvad?

En struct kan defineres som en datastruktur, hvor i praksis bruger man structs til at organisere data på en mere overskuelig måde. Det er især nyttigt, når vi har flere attributter, der logisk hænger sammen. For eksempel, gør vi brug af struct til at sende data imellem joystik og rover fordi det gør det muligt at samle flere forskellige datatyper under ét tag. 

Klasser er et kraftfuldt værktøj i objektorienteret programmering, der gør det muligt at modellere komplekse systemer. F.eks. har vi gjort brug af classes i de fleste dele af vores kode for at gøre det mere overskueligt at kalde forskellige funktioner og voids i vores main kode. Derudover bliver src koden nemmere læselig og skaber et bedre overblik. 



#### Hvilke libraries er blevet brugt og til hvad? (#include statements)

#### Hvordan har i anvendt metoder i har lært i undervisningen?


## Udfordringer undervejs:

### Hvilke udfordringer mødte i undervejs?

### Hvordan løste/har i tænkt jer at løse det?

### Hvorfor tror i de opstod?

