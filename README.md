# Oblig-TMA4106
Forsøk på å lage regulert svingarm

I fjor valgte jeg å gjøre standardprosjektet, noe som jeg synes var litt kjedelig. Som Kyb student tenkte jeg det ville være interessant å lage et lite reguleringssystem, så jeg prøvde meg på å regulere en svingarm. Systemet er som følger: En arm er festet til kanten av et bord med en eller annen form for hengsel, slik at den kan svinge opp og ned. På enden av armen festes en motor med propell (jeg hadde en push-propell, så den ble festet på nedsiden av armen). Deretter kobles en avstandssensor på oversiden.

Ideen var at jeg skulle sette en referanseavstand, for eksempel 20 cm, og armen skulle fly opp til den avstanden. Endret jeg på hvor jeg hadde hånden, slik at avstanden økte eller minket skulle systemet følge etter. Dette ble gjort ved hjelp av å koble alt på en arduino nano og ved bruk av en PID-regulator. 

Oppkoblling og kodeskriving gikk ikke uten problemer, men jeg kom til noe fornuftig etter hvert, men så skjer det uheldige: motorkontrolleren stokket seg og jeg får ikke lenger styrt motoren systematisk. Jeg så etter mange løsninger på internett, blant annet reseting av motoren, men ingen ting fungerer for å få den tilbake til slik den var. Derfor har jeg nå bestilt en ny motor, men den kommer ikke i tide før påske, så prosjektet skal fortsettes til neste år, og mulig med noen oppgraderinger. 

