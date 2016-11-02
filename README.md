_tl;dr_: [Gå rett til videoanbefalingene](http://open.bekk.no/strange-loop-2016#anbefalte-presentasjoner).

Sammenlignet med NDC og JavaZone er Strange Loop en mindre konferanse, med tanke på både varighet og antall deltakere. Konferansen varer i to dager og er hardcore teknologifokusert. Her finner du få talks om prosess og metodikk, men heller flere avanserte talks om litt sære temaer. Konferansen har rykte på seg for å ha mye fokus på funksjonell programmering, men den byr også på mye mer enn det. Vi så talks om alt fra modulsystemet i Java 9, til distribuerte byggesystemer hos Google, til mangfold i IT-bransjen.

Vår opplevelse er at dette ikke er en konferanse for en ny og uerfaren utvikler. Mange forholdsvis avanserte konsepter tas nemlig bare for gitt og får ingen ordentlig introduksjon.
Nivået på presentasjonene er generelt høyt, men som alle konferanser vi har vært på er det også noen presentasjoner som er dårlige, uforberedte og totalt bortkastet tid. Det var fem samtidige presentasjoner, og det bekrefter igjen hvor viktig det er å mestre kunsten å velge riktige talks på en konferanse.

Sammenlignet med norske konferanser var det mye oppmerksomhet rundt konferansens Code of Conduct, og generelt større bredde og mangfold blant deltakerne enn vi vanligvis ser i Norge. Strange Loop har også en ordning der deltakere fra underrepresenterte grupper får søke om å delta gratis. Det var mange kvinnelige speakers – hele tre av fire keynotes ble holdt av kvinnelige speakers – en annen positiv forskjell fra andre konferanser vi har vært på.

Hele konferansen er preget av vennlig, løssluppen og kul stemning. Det ble spesielt tydelig på konferansefesten, som foregikk på det fantastiske St. Louis City Museum. Museet er samlingen til en eksentrisk kunstner og består av veldig mye rart. Det er sklier mellom etasjene, falske huleganger, hemmelige passasjer, pariserhjul på taket av det tolv etasjer høye bygget og utrolig mye mer. Festen varte fra syv til halv ti, og inneholdt en betydelig mindre andel rølp enn tilsvarende arrangementer på norske konferanser. Deltakerne ble til og med oppfordret til å ta med seg familie og barn på festen – mon tro når man begynner med det på AweZone?

Sammenlignet med norske konferanser finner vi et betydelig større antall skikkelige sluggere blant bedriftene på Strange Loops program. Vi så talks fra ansatte i både Google, Facebook, Microsoft, Netflix, Thoughtworks, Fitbit, Riot Games og Slack. Det er utrolig inspirerende å høre om de utrolig massive tallene de kan skilte med, men det betyr også at de ofte har løst helt andre problemer enn de vi jobber med til daglig. De er derfor sjeldent direkte overførbare til vår hverdag. Blant de fascinerende temaene vi hørte om var distribuert caching i Netflix, distribuerte byggesystemer hos Google og monitorering av League of Legends. Det er likevel ikke gitt at disse presentasjonene i seg selv var de beste, og vi har ikke anbefalt noen talks kun på bakgrunn av imponerende størrelsesorden.

# Anbefalte presentasjoner
Vi har plukket ut en personlig favoritt hver, og til slutt noen bonusspor for de som virkelig ikke får nok. På denne turen har vi diskutert mye på kveldene og underveis på reisen, og på mange måter har det faktisk vært mer å hente av disse gode diskusjonene enn å kun se presentasjonene.
Personlige favoritter

## Peter - Systems programming as a swiss army knife ([video](https://youtu.be/HfD9IMZ9rKY))
<iframe width="560" height="315" src="https://www.youtube.com/embed/HfD9IMZ9rKY" frameborder="0" allowfullscreen></iframe>

Julia er en rå, morsom og entusiastisk dame som nå jobber i Stripe. Har en veldig uvanlig måte å presentere på, som er forfriskende og fungerer utrolig bra. Hun spretter rundt på scenen, ser ned i gulvet mens hun snakker og er generelt utrolig likandes. Hun skriver zines og har også gitt ut talken som en zine. Dette er åpenbart en kjenning i miljøet, for det var god kok i salen. Hun snakker om avanserte muligheter for å debugge programmer i Linux, og viser at man egentlig ikke trenger å kunne noe som helst om språkene de er skrevet i eller hva programmene er ment å gjøre for å kunne avdekke feil i dem. Alle programmer bruker jo det underliggende operativsystemet det kjører i, og hvis man greier å se hvordan programmet påvirker systemet, kan man finne ut veldig mye om hva det gjør uten å faktisk lese noe kode.

Hun tar for seg tre tenkte "problemer" og løser dem ved å bruke strace, perf top, ngrep og flere ting jeg aldri hadde hørt om live i terminalen. Hun avslutter med noen praktiske tips som ikke er knyttet til de konkrete debuggingsproblemene hun løste tidligere, men som også er nyttige. Anbefales både for de konkrete linux-tipsene, og for den gode og uvanlige presentasjonen.

## Peder - Exotic Functional Data Structures: Hitchhiker Trees ([video](https://youtu.be/jdn617M3-P4))

Det er ett foredrag hvor jeg tok meg selv i å tenke: “Nå koser jeg meg ordentlig her!”. Temaet appellerte både til den delen av meg som er nyfiken på funksjonell programmering, samt den delen av meg som vil vite hva som skjer under panseret på teknologier. Men kanskje aller mest appellerte det til informatikeren i meg. Foredraget er av David Greenberg og handler om “eksotiske” funksjonelle datastrukturer.

Fullt så eksotisk er heldigivis ikke. Greenberg starter relativ rolig og forsiktig med å først definere hva som kjennetegner en funksjonell datastruktur før han gradvis presenterer forskjellige trestrukturer i økende kompleksitet. Ja det er litt matematikk her i form av O-notasjon, men Greenberg gjør en relativt god jobb i å forklare intuisjonen som ligger bak matematikken i stedet for å henge seg opp i utregninger.

Alt i alt syns jeg dette var en god introduksjon til temaet, og kan anbefale en titt for de som synes algoritmer og datastrukturer er like kos som meg.

## Fredrik – Is it a bug or is it a story? ([video](http://youtu.be/sMy4L-J6fFs))

Nicola Hughes jobber som utvikler i Thoughtworks, men har tidligere erfaring som researcher og gravejournalist i CNN, BBC, The Times og The Guardian. Som journalist spesialiserte hun seg på å analysere store datasett på jakt etter korrupsjon og skjulte mønstre i samfunnet.

I presentasjonen gir hun flere eksempler på funn hun har gjort ved å analysere data, og stiller publikum spørsmålet “Is it a bug, or is it a story?”. Med andre ord: Er funnene i datasettet publiseringsverdige – har vi en nyhetssak? – eller er datasettet ufullstendig eller metoden feilaktig? Interessant og tankevekkende om at sammenhenger og konklusjoner som kan virke åpenbare, ofte ikke er det.

## Bendik - Point-Free or Die: Tacit Programming in Haskell and Beyond ([video](https://youtu.be/seVSlKazsNk))

“Tacit programming”, eller “point free style” er the shit. Det hjelper deg å se på funksjoner som komposisjoner ved å fjerne støyende elementer som funksjonsargumenter, og kan derfor hjelpe deg å krype enda lengre inn i den funksjonelle verden. Amar Shah viser hvordan man kan gå fram for å gjøre alle funksjoner point free, og innfører blant annet en ny operator for å gjøre point free style mer leselig i flere tilfeller.

Denne talken er verdt å se dersom du er nysgjerrig på konseptet point free, eller kanskje har prøvd å kode point free tidligere uten å ha følt at det har gitt deg
noe særlig.


# Bonusspor for dem som må ha mer

## GraphQL: Designing a Data Language ([video](https://youtu.be/Oh5oC98ztvI))

Lee Byron, som var med fra starten på React og har laget Immutable.js, er en rå fyr. Byron er god til å forklare hva GraphQL er for noe og hvilket problem det løser. Han snakker  også om hva GraphQL ikke er (en graf eller en database). GitHub annonserte nettopp at det nye API-et deres vil støtte GraphQL, og noen få dager før denne talken ble språket offisielt produksjonsklart. Dette er en god talk for deg som lurer på hva GraphQL er, og hvordan det er å lage et språk.

## Debugging diversity ([video](https://youtu.be/4KhXwl0L61g))
Tankevekkende om mangfold i teknologibransjen, et tema som kanskje burde stått høyere på agendaen her i Norge. Denne førte til mange lange og gode diskusjoner over øl og løkringer på kveldene i St. Louis.

## Lies, Damn Lies, and Metrics ([video](https://youtu.be/pYbgcDfM2Ts))
God presentasjon om måling av data, og hvorfor du alltid bør visualisere i stedet for å aggregere.

## Diocletian, Constantine, Bedouin Sayings, and Network Defense ([video](https://youtu.be/qCUI5ryyMSE))
Morsom presentasjon som tok utgangspunkt i interessant historiefortelling om romerriket og greide å knytte det veldig godt opp til hvorfor en brannmur på ingen måte er nok for å sikre dagens nettverk.

## Government Hacking and Human Rights: The Why and the How ([video](https://youtu.be/C4rT0lgJr6U))
Aktuell og god keynote fra en advokat om hacking utført av regjeringer.

## Humanities x Technology ([video](https://youtu.be/fNe1i7nVbXI))
Utrolig godt presentert og gjennomarbeidet keynote om at teknologi for teknologien skyld er meningsløst. Vi må aldri glemme menneskeligheten. Denne har vi diskutert mye!
