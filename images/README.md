Mandatory assignment before taking the exam in "Introduction to programming" at Høyskolen Kristiania autumn 2023. Below you will find the task:

# Task: AdventureLand – Final Boss Battle

## Del 1: Beskrivelse av hvordan spillet skal fungere

- Man kan klikke på Nameless knight, The Cat og Julia the archer for å angripe monstrene.
- Man gjør 1 angrep ved å klikke på Nameless knight, The Cat eller Julia, og Big Boss gjør umiddelbart et angrep tilbake på en av de 3 heltene; det skal være tilfeldig hvem av dem Big Boss angriper.
- Noen ganger (med sannsynlighet på 25%) etter at man har gjort et angrep vil en Slime eller Bat dukke opp (ref. img med id appearing-monster).
- Alle angrep skal ta en tilfeldig mengde hp; bruk Math random-teknikken.
- Når Slime eller Bat har dukket opp kan de 3 heltene kun angripe Slime eller Bat. De angriper ikke tilbake, men de forhindrer heltene fra å kunne angripe Big Boss. Big Boss fortsetter å angripe som vanlig mens Slime eller Bat er der.
- Nameless knight greier kun å ta liv av Big Boss
- Julia the archer greier kun å ta liv av Bat
- The Cat greier kun å ta liv av Slime
- Alle angrep må skrives ut. Alle utskrifter må inkludere hvor mye hp som er tatt, eksempelvis «Big boss angriper Julia, og Julia mister 20hp ».

## Del 2: Utvide med mer funksjonalitet

Hvis man er 1 på gruppen skal minst 2 av funksjonene nedenfor gjøres
Hvis man er 2 på gruppen skal minst 3 av funksjonene gjøres.
Hvis man er 3 på gruppen skal minst 4 av funksjonene gjøres.

- Man kan klikke på William the healer for å hele en eller flere av heltene
- Bruk element.style-teknikken for å stilsette meldingene som skrives ut. For eksempel når Julia angriper er bakgrunnen til meldingen grønn.
- Man må klikke på Jack the lumberjack for å lage piler til Julia; dvs. Julia har begrenset antall piler.
- Hvis Big Boss har mindre enn 20% liv så blir han større og tar 10% mindre skade.
- Det skal dukke opp «Du vant!» hvis man vinner over Big Boss
- Det skal dukke opp «Du tapte!»-melding hvis man taper
- Gjør bruk av setTimeout (se kodeeksempel nedenfor) for å utsette angrepet fra Big boss og de andre slemme vesenene med 1-3 sekunder.
- Egendefinert funksjonalitet: legg til noe du selv ønsker å ha med som du tenker er kult å ha med!
