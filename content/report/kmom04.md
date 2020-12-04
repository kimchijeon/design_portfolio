---
Title: Kmom04
Description: Report for part 4
Template: kmom
---

Kursmoment 4
==================
<div class="sidebar">
    <p>
        <a href="%base_url%/report/kmom01">Kmom01</a></li><br>
        <a href="%base_url%/report/kmom02">Kmom02</a></li><br>
        <a href="%base_url%/report/kmom03">Kmom03</a></li><br>
        <a href="%base_url%/report/kmom04"><u>Kmom04</u></a></li><br>
        <a href="%base_url%/report/kmom05">Kmom05</a></li><br>
        <a href="%base_url%/report/kmom06">Kmom06</a></li><br>
        <a href="%base_url%/report/kmom10">Kmom10</a></li><br>
    </p>
</div>

<div class="content">
<h2>Kommentera skrivuppgiften.</h2>
    <p>Det var en rolig och lagom tidskrävande uppgift! Det var väldigt intressant att upptäcka nya saker om webbplatser som man är van vid att besöka, men som man aldrig har tänkt på förr. Genom att genomföra analysen har jag verkligen fått lära mig att färgval på webbplatser inte är slumpmässiga utan noggrant övervägda för att skapa en eftersträvad effekt. Det har också gett mig tips på hur jag kan tänka kring färgval när jag själv bygger en webbsida.</p>

<h2>Vilket färgschema valde du till ditt tema och hur?</h2>
    <p>Jag bestämde mig för att använda ett monokromatiskt färgschema med ljus bakgrund och (ljus)svart text inspirerad av de webbplatser som jag analyserade i skrivuppgiften. Den tilltalar också mig själv personligen då jag gillar att hålla det minimalistiskt.</p>
    <p>Den ljusgula grundfärgen är ganska stark och används bara i headern och footern för att rama in sidan. Den mellanmörka gula färgen föredrogs för resten av sidan. Men för att liva upp sidan lite valde jag att ha en "split" komplementär blå till det gula på mina länkar. Detta gör det också tydligare vad som är länkar.</p>
    <table style="border-spacing: 4px; border-collapse: separate">
        <tr>
            <td style="height: 50px; width: 50px; background-color: #fbc100">
            <td style="height: 50px; width: 50px; background-color: #c79800">
            <td style="height: 50px; width: 50px; background-color: #7a5e00">
            <td style="height: 50px; width: 50px; background-color: #3e3e3f">
            <td style="height: 50px; width: 50px; background-color: #1179ad">
        </tr>
    </table>
    <br>

<h2>Valde du att jobba med accentfärg och isåfall hur?</h2>
    <p> Den komplementära färgen blå som nämndes i förra frågan använder jag som accentfärg även om den återkommer väldigt sällan. Den ljussvarta färgen tar egentligen rollen som accentfärg då den syns i navbaren och i titeln, men samtidigt är den också färgen på texten i huvudinnehållet. Den har på så vis ingen utmärkande karaktär. Därför ville jag ha en extra accentfärg för att kunna lyfta fram vissa element. Men eftersom jag eftersträvar en minimalistisk stil drog jag mig för att använda den blå färgen för mycket. </p>

<h2>Hur valde du att lösa ditt dark theme?</h2>
    <p>Eftersom jag så långt jag kan vill undvika upprepande kod valde jag att lösa min dark theme med import. Jag uppdaterade min <code>base.scss</code> med en <code>shared-style.scss</code> som innehåller koden som tidigare fanns i <code>style.scss</code>. På så sätt undviker jag upprepning och behöver bara redigera på ett ställe för det som är gemensamt för både light och dark theme. Efter alla imports i <code>style-dark.scss</code> skrev jag dark theme-specifik kod så att det skriver över eventuell style i <code>base.scss</code> som inte passar för dark mode.</p>

<h2>Vilken är din TIL för detta kmom?</h2>
    <p>Det största TIL:et var att få lära mig färgscheman! Att se klart och tydligt varför vissa färger passar ihop, istället för att "känna" att de gör det (eller inte). Det har gett mig ordentliga verktyg för att välja färg i framtiden. Det var också spännande att upptäcka att dark mode inte bara är en invertering av ett ljust tema. <a href="https://css-tricks.com/a-complete-guide-to-dark-mode-on-the-web/#design">CSS-TRICKS</a> guide till dark mode var verkligen en ögonöppnare!</p>
</div>
<a class="arrow-up" href="?"><i class="fas fa-arrow-circle-up"></i></a>