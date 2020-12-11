---
Title: Kmom02
Description: Report for part 2
Template: kmom
---

Kursmoment 2
==================
<div class="sidebar">
    <p>
        <a href="%base_url%/report/kmom01">Kmom01</a><br>
        <a href="%base_url%/report/kmom02"><u>Kmom02</u></a><br>
        <a href="%base_url%/report/kmom03">Kmom03</a><br>
        <a href="%base_url%/report/kmom04">Kmom04</a><br>
        <a href="%base_url%/report/kmom05">Kmom05</a><br>
        <a href="%base_url%/report/kmom06">Kmom06</a><br>
        <a href="%base_url%/report/kmom10">Kmom10</a><br>
    </p>
</div>

<div class="content">
<h2>Vad tycker du om SASS än så länge?</h2>
    <p>SASS är verkligen ett fantastiskt verktyg! Som jag upptäckte under projektet för htmlphp-kursen så kunde CSS-filen bli väldigt lång och innehålla mycket upprepningar. Med variabler och nesting känns filen mycket mer effektiv. Och att sedan kunna dela upp stylen i olika moduler och bara importera dem känns också bra rent organisatoriskt.</p>
    <p>Jag är glad att jag blev introducerad till SASS!</p>

<h2>Är du bekant med Node, npm eller npm scripts sedan tidigare?</h2>
    <p>Jag hade aldrig hört talas om Node och npm förr, men upplevelsen med dessa verktyg så här långt har varit bra! Det var enkelt och smidigt att installera och även att använda. Det är exempelvis enkelt att lägga till egna script så att det passar en själv. Det är också skönt att kunna använda <code>npm run lint</code> för att snabbt validera sin style.</p>

<h2>Hur kändes det att kompilera SASS till CSS?</h2>
    <p>Tanken att kompilera <code>scss</code>-filen till <code>css</code> kändes först lite skrämmande. Men så fort jag kom underfund med SASS så känns det som ett smidigt sätt att skapa sin style.</p>
    <p>Det enda som var lite jobbigt var att ständigt behöva köra <code>npm run style-min</code> för varje liten ändring man ville kolla. Jag valde att inte köra <code>watch</code>-scriptet som automatiserar detta eftersom jag inte kände mig bekväm med det när jag skulle lära mig hur SASS och npm fungerar. Men det är nog något att använda framöver!</p>

<h2>Kommentera ditt tema.</h2>
    <p>Jag ville skapa ett tema med en kreativ och lekfull känsla. Detta skapas främst med hjälp av min flash-bild och header-typsnittet Permanent Marker. Även accent-färgen (orange-gul) bidrar till en glad känsla. Samtidigt blir sidan inte för oseriös och plottrig tack vare mycket whitespace och en sans-serif som kontrasterar header-typsnittet. Jag hade inte riktigt någon plan med mitt tema när jag började, men tyckte att Niklas exempel fungerade bra som grund.</p>
    <p>I kursboken "The Principles of Beautiful Web Design" ges exempel på "populära favoriter" eller trender och där kan jag se att jag definitivt lutar mig åt t.ex. <a href="https://thedsgnblog.com/">TheDesignBlogs</a> håll.</p>

<h2>Valde du att dela upp din kod?</h2>
    <p>Den största delen av koden finns i <code>style.scss</code>. Där finns utseendet för element under header, main och footer. I <code>style.scss</code> importerar jag <code>layout.scss</code> som kontrollerar det övergripande utseendet för hela webbplatsen. Därutöver har jag <code>typography.scss</code> som kontrollerar övergripande typsnitt, textstorlek och radavstånd. Jag gjorde dessa uppdelningar för att det skulle bli lättare att hitta och därmed att redigera.</p>

<h2>Vilken är din TIL för detta kursmoment?</h2>
    <p>Mitt TIL är helt enkelt att lära mig förstå SASS. Allt från själva syntax till kompileringen av SASS till CSS, inklusive npm. Jag känner att jag har kläm på det här nu, men vet att det jag har fler SASS verktyg att testa på! Det var också inspirerande att läsa i kursboken och lära mig mycket teori om layout och typografi som jag aldrig tänkt på förr.</p>
</div>

<a class="arrow-up" href="?" aria-label="Go to top of page"><i class="fas fa-arrow-circle-up"></i></a>
