---
Title: Kmom02
Description: Report for part 2
---

Kursmoment 2
==================

## Vad tycker du om SASS än så länge?
SASS är verkligen ett fantastiskt verktyg! Som jag upptäckte under projektet för htmlphp-kursen så kunde CSS-filen bli väldigt lång och innehålla mycket upprepningar. Med variabler och nesting känns filen mycket mer effektiv. Och att sedan kunna dela upp stylen i olika moduler och bara importera dem känns också bra rent organisatoriskt.

Jag är glad att jag blev introducerad till SASS!

## Är du bekant med Node, npm eller npm scripts sedan tidigare?
Jag hade aldrig hört talas om Node och npm förr, men upplevelsen med dessa verktyg så här långt har varit bra! Det var enkelt och smidigt att installera och även att använda. Det är exempelvis enkelt att lägga till egna script så att det passar en själv. Det är också skönt att kunna använda `npm run lint` för att snabbt validera sin style.

## Hur kändes det att kompilera SASS till CSS?
Tanken att kompilera `scss`-filen till `css` kändes först lite skrämmande. Men så fort jag kom underfund med SASS så känns det som ett smidigt sätt att skapa sin style. 

Det enda som var lite jobbigt var att ständigt behöva köra `npm run style-min` för varje liten ändring man ville kolla. Jag valde att inte köra `watch`-scriptet som automatiserar detta eftersom jag inte kände mig bekväm med det när jag skulle lära mig hur SASS och npm fungerar. Men det är nog något att använda framöver!

## Kommentera ditt tema.
Jag ville skapa ett tema med en kreativ och lekfull känsla. Detta skapas främst med hjälp av min flash-bild och header-typsnittet Permanent Marker. Även accent-färgen (orange-gul) bidrar till en glad känsla. Samtidigt blir sidan inte för oseriös och plottrig tack vare mycket whitespace och en sans-serif som kontrasterar header-typsnittet. Jag hade inte riktigt någon plan med mitt tema när jag började, men tyckte att Niklas exempel fungerade bra som grund. 

I kursboken "The Principles of Beautiful Web Design" ges exempel på "populära favoriter" eller trender och där kan jag se att jag definitivt lutar mig åt t.ex. [TheDesignBlogs](https://thedsgnblog.com/) håll. 

## Valde du att dela upp din kod?
Den största delen av koden finns i `style.scss`. Där finns utseendet för element under header, main och footer. I `style.scss` importerar jag `layout.scss` som kontrollerar det övergripande utseendet för hela webbplatsen. Därutöver har jag `typography.scss` som kontrollerar övergripande typsnitt, textstorlek och radavstånd. Jag gjorde dessa uppdelningar för att det skulle bli lättare att hitta och därmed att redigera.

## Vilken är din TIL för detta kursmoment?
Mitt TIL är helt enkelt att lära mig förstå SASS. Allt från själva syntax till kompileringen av SASS till CSS, inklusive npm. Jag känner att jag har kläm på det här nu, men vet att det jag har fler SASS verktyg att testa på! Det var också inspirerande att läsa i kursboken och lära mig mycket teori om layout och typografi som jag aldrig tänkt på förr.

[Tillbaka](%base_url%/report)