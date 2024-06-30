---
Title: Load
Description: This is the analysis of kmom05 page.
Template: analyserna
---

Loaaaadi...ng
=======================

<h2>Utvärdering av webbplatsers laddningstid och användbarhet</h2>

Uppgiften handlar om att testa olika webbplatsers laddningstid och analysera huruvida de kan förbättra sin prestenda.

<br>
<hr style="border: 1px solid black;">
<br>

Urval
-----------------------

Webbplatser som jag har valt att analysera i den här uppgiften är följande:

<br>

1. 1177
https://www.1177.se/Stockholm/

1177 är en sida för information och tjänster inom hälsa och vård för hela Sverige. Där kan man logga in för personliga e-tjänster för att ta del av sin journal eller ringa för sjukvårdsrådgivning. Den här webbplatsen valdes då den behöver ha lätt- och snabbtillgänglig information samt att man som individ kan logga in och komma åt sina personliga uppgiter.

<br>

2. Skistar
https://www.skistar.com/sv/

Skistar är ett företag inom fritid/turism som äger och driver skidanläggningar i Sverige och Norge. Kärnverksamheten är alpin skidåkning och det tillhörande logistik såsom uthyrning av boende, utrustning, skidskolor och liknande. Skistar webbplats besöks av de flesta skidåkarna i Sverige när de vill informera sig om den aktuella info på olika skidområden, vilka liftar och pister är öppna, väderinformation, snö och det är just därför Skistars webbplats har valts för analys.

<br>

3. N1
https://n1info.rs/

N1 är en multimedial informativ plattform, en tv-nyhetskanal och webb-tidning, en partner till CNN, som främst fokuserar på att distribuera sitt innehåll i Sydöstra Europa. N1 har sin produktionscenter i Serbien, Bosnien, Kroatien och Slovenien och täcker nyheter rörande dessa länder. Jag valde den här webbplatsen eftersom jag besöker den ofta när jag vill informera mig om nyheter i mitt hemland. 

<br>
<hr style="border: 1px solid black;">
<br>

Metod
-----------------------

För att mäta webbplatsers laddningstid används Google Pagespeed tool där tre sidor från samma webbplats analyseras för både Mobile och Desktop laddning. Browser's developer tools används för att notera webbplatserns laddningstid, antal resurser och webbplatsens totala storlek. Uppmätta värden presenteras i en tabell nedan.

<br>
<hr style="border: 1px solid black;">
<br>

Resultat
-----------------------

###N1

<img alt="img n1" src="%base_url%/image/n1_bild.png" style="height: 150px; width: 300px;"/>

Mätningar gjordes på N1-webbplatsens startsida, artikelsida som öppnades slumpmässigt, och webbplatsens sida på engelska.

<br>

###1177

<img alt="img 1177" src="%base_url%/image/1177_bild.png" style="height: 150px; width: 300px;"/>

Mätningar för 1177 webbplats gjordes på dess startsida, slumpmässigt valda artikelsida och hitta vård sida.

<br>

###Skistar

<img alt="img skistar" src="%base_url%/image/skistar_bild.png" style="height: 150px; width: 300px;"/>

På Skistar webbplats mätes dess startsida, sida om allmän info om skidortens väderprognos, snö och liknande, samt kontakt sida.

<br>

Resultat finns presenterade i tabellen nedan där rådata är i sheet 1. För lättare överblick har datan sammanfattats för samtliga webbsidor och visas separat i sheet 2, 3 respektive 4.

<br>

Laddningstider varierar betydligt mellan olika sidor. Till exempel har sidan "1177 - startsida" den snabbaste laddningstiden (0,09 s), medan "N1 - startsida" har den längsta laddningstiden (5,15 s) bland de alla analyserade sidorna.

Generellt sett tenderar sidor att ladda snabbare på desktop jämfört med mobila enheter.

Antalet resurser varierar också. Sidor som N1 kräver ett högre antal resurser (startsida 103) jämfört med andra som 1177 (startsida 26).

Storleken på resurserna bidrar till den totala sidstorleken, vilket påverkar laddningstiderna och användarupplevelsen. Till exempel har Skistar - start den största resurstorleken (4,49 mB) bland de analyserade sidorna, medan Skistar - kontakt har den minsta storleken (0,46 mB).

När det gäller Page Speed mätningar för desktop och mobil, har sidor med snabbare laddningstider fått vanligtvis högre poäng, vilket indikerar bättre prestanda.
T.ex. har sida som "1177 - startsida" en extremt snabb laddningstid fått högre Page Speed poäng jämfört med sida med långsammare laddningstiden som "N1 - startsida".

<br>

<div class="embed-container">
<iframe width="402" height="346" frameborder="0" scrolling="no" src="https://studentbth-my.sharepoint.com/personal/veda23_student_bth_se/_layouts/15/Doc.aspx?sourcedoc={2716374d-2d11-4423-98c1-6f08a49f44f8}&action=embedview&wdAllowInteractivity=False&wdHideHeaders=True&wdDownloadButton=True&wdInConfigurator=True&wdInConfigurator=True"  title="Raw data document"></iframe>
</div>

<br>
<hr style="border: 1px solid black;">
<br>

Analys
-----------------------

Erhållna resultat understryker vikten av att optimera webbsidor för snabbare laddningstider, särskilt på mobila enheter där användare kan ha långsammare internetanslutningar. Strategier såsom att minska antalet resurser och optimera deras storlekar kan väsentligt förbättra laddningsprestandan.
Sidor med snabbare laddningstider och färre resurser tenderar att erbjuda bättre användarupplevelser vilket positivt påverkar sökmotorrankningar och användarnöjdhet. 
Utifrån de undersökta sidor så laddas 1177 sidor snabbast och har fått bästa betyg från Page Speed. En av orsakerna kan vara att 1177 har allmän sett många färre bilder och använder mindre av JavaScript, till skillnad från N1 och Skistar som därav har långsammare laddningstider.

<br>

Ingen av de undersökta sidor har fått höga betyg för optimering för mobila enheter. 1177 har ändå betydligt högre än övriga men jämfört med sin desktop version ändå sämre betyg. Webbsidor använder resurser som är mer resurskrävande eller inte är kompatibla med mobila webbläsare och detta leder till att sidor laddas långsammare eller att vissa funktioner inte fungerar korrekt på mobila enheter. T.ex. så är bilder en stor del av innehållet och kan vara en källa till fördröjd laddningstid och därför kan websidor försöka komprimera bilder för att få snabbare laddningstiden eller så kan de minifiera HTML-, CSS- och JavaScript-filer genom att ta bort onödiga tecken, mellanslag och kommentarer för att på så sätt minska filstorleken och därmed förbättra laddningstiden. Ett annat sätt är att använda cachningstekniker. Genom att lagra resurser lokalt på enheten eller i webbläsarens cache minskar behovet av att hämta resurser från servern varje gång sidan laddas om.

<br>
<hr style="border: 1px solid black;">
<br>

Referenser
-----------------------

    https://pagespeed.web.dev/?utm_source=psi&utm_medium=redirect

    https://moz.com/learn/seo/page-speed

<br>
<hr style="border: 1px solid black;">
<br>

Övrigt
-----------------------

Denna rapport är skriven av Vedrana Dajic.