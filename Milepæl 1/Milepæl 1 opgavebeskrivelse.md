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

    Det første vi gjorder som gruppe var at planlægge nogle mål, visioner og brainstorme på hvad vi gerne ville opnå på den tidsramme udannelsen og underviserne havde fremlagt. Det som er spændende og godt ved at planlægge er at man kan se hvor langt man er kommet og hvor meget man har udviklet sig. Vi brugte meget af denne motivation til at brainstorme mere og idegenerer hver gang vi havde løst et problem. 

    Basen som det første har en basis plade som alt skulle samles på. Hvilket blev gjort for at kunne visuellisere vores koncept, videreudvikle på den viden vi havde fået og få mere motivation ved hver ny funktion vi puttede på. Det næste vi puttede på var motorere og hjul som er stripset fast. Herefter forsatte med placering af H-broer for at kunne styre disse motorer. Da vi var sikre på at forbindelser fungerede som ønsket lodet vi ledningerne fast så vi var sikre på at der ikke var løse forbindelser som kunne skabe usikkerhed i vores kode eller funktionaliteten af komponenterne. Vi valgte at gå to veje med vores roverere for at sikre at vi havde et færdigprodukt til afleveringsdato af første milepæl. En rover som blev styret mekanisk via knapper og strømforsyning og en rover der blev styret via en ESP32. Roveren som var bygget med ESP32'eren var kodet via void loops med de individuelle analogWrite værdier og navngav dem frem, tilbage, til højre og venstre osv. Vi delte os op, hvor nogle arbejdede på fremtidige funktioner og den anden halvdel på finpusningen af basis funktionaliteten. Men som gruppe har vi været gode til at inkludere hinanden, spørge om hjælp og videreformidle information så der ikke var nogle der ikke var med.
    
    På daværende tidspunkt havde vi en funktionel base som kunne køre. Men da vi var i god tid og var motiveret til at lave mere fik vi sat 3 sensore på som via if statements i programmeringen kunne styre motorene automatisk afhængigt af hvilke input sensorne fik. Vi var også meget enige om at det ikke var en rover uden lys så vi fik sat lys på og kodet vores baglygter til kun at blinke når den bakkede via analogWrite og satte det ind i vores Reverse funktion så vi vidste at hver gang den bakkede så blinkede baglygterne. Hertil kodet vi også en knap som kunne tænde og slukke roveren så den var nemmere at styre. Dette blev gjort ved hjælp af funktionen digtialread til at læse hvornår vores ONOFF knap bliver trykket. 

    ### Hvilke udfordringer har jeg/vi haft

    Overordnet synes jeg det har været en meget stejl læringskurve de første 4 uger. Det er imponerende hvor meget man kan lærer på kort tid. Men det påviser også udfrodringen i at følge med. Der er rigtigt meget at lærer fra alle fagende og det har bestemt været udfordrende at nå alle lektier og alle opgaver da man ikke vil neglishere nogle fag frem for andre. I og med at vores undervisning afspeljer opgaverne som representere vores rover har det altså være nødvendigt at kunne alt hvad vi er blevet undervist i. 

    Generelt på disse videregående uddannelser, er gruppearbejde en stor del af uddannelsen. Det gør at der har ligget meget pres på at finde, motivere, kommunikere, og løfte gruppen for at sikre en godt resultat. Det betyder også at man som endivid skal kunne gøre plads til forskellige personligheder, kunne lytte til hvad andre i gruppen vil og ikke vil og kunne vide hvornår man skal tage en diskution og hvornår man ikke skal. Selvom vi i gruppen har været rigtigt gode til dette så synes jeg at dette er en løbende udfordring som vi som gruppe ikke må miste respekten for. 

    Jeg har haft mange udfordringer i alle fagende, lige fra at få programmer til at fungere, til forståelse af basic kode eller breadboard systemer. Men ved oplæsning, gruppe hjælp og rettelser fra underviseren synes jeg at mange af de problematikker og udfordringer jeg/vi er støt på undervejs i denne milepæl er blevet løst og forstået. F.eks. efter vi havde haft om h-broer kunne jeg slet ikke finde ud af h-broer, men i og med jeg satte mig ned og afprøvede hvordan capasitors fungerede har jeg fået en bedre forståelse for h-broer. Do-While loops i programmering er også en af de elementer i programmering som jeg ikke helt har fået på plads endnu. Elektromagnetisme og hvordan på et elektron niveau strøm kan blive overført fra den ene coil til den anden ved hjælp af stimulering og retningsbestemme elektronerne ved hjælp af tyngde kræften, er stadig en gåde for mig. 

    ### Hvad er jeg stolt af

    Jeg er utrolig stolt af at have fået et super godt forhold til min gruppe. Jeg er stolt af at vi som gruppe hele tiden presser grænserne for hvad vi har lært. Og jeg er super stolt over at vi faktisk har en funktionel rover er kan køre "automatisk" på baggrund af sensor informationer. Alt dette er jeg er stolt af at vi har gjort på baggrund af vi havde lyst til at blive lidt længere, at vi som gruppe prioiterede hinanden styrke og stolede på hinanden. Istedet for at gøre det til en konkurrence om hvem der er bedst eller kan mest.



    


   