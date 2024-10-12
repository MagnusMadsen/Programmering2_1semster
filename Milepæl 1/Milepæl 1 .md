## Vejledning til studerende

I dette dokument skal du i grove træk beskrive din løsning til milepælsopgaven.

I skal kunne beskrive hvilke komponenter der er i basen, hvilket går i sektionen komponentliste.

Derefter skal i beskrive basen. Dvs. besvar hvilke komponenter bliver brugt til hvad? 

Hvordan er det blevet brugt? F.eks. hvilke funktioner giver det,

Hvad var udfordringerne undervejs i at få komponenterne til at virke?

Hvad virker godt/er du stolt af at have bygget?

Det i skriver i journalmappen er jeres uge til uge reflektioner, så dette Milepælsdokument er en opsamling til det hele, en oversigt. Dette dokument skal ikke være mere end 1 side eller 2, mens journalen er mere detaljeret.

## Opgave 1 - Base - Milepælsopgave

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

    På det tidspunkt havde vi en funktionel base, der kunne køre. Da vi var foran tidsplanen og stadig motiverede, tilføjede vi tre sensorer, der via if-statements i koden kunne styre motorerne automatisk baseret på sensorinput. Vi blev også enige om, at en rover ikke ville være komplet uden lys, så vi monterede baglygter, som blinkede, når den bakkede, hvilket vi styrede via analogWrite i vores “Reverse”-funktion. Vi kodede også en knap til at tænde og slukke roveren med digitalRead, så den blev nemmere at styre.

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





    


   

   