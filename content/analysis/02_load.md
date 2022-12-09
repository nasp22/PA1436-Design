---
Title: KMOM05
Description: Analysis - kmom05
Template: report
---

<nav class="nav">
    <a href="%base_url%?analysis/01_colors">KMOM04</a>
    <a href="%base_url%?analysis/02_load">KMOM05</a>
    <a href="%base_url%?analysis/03_designprincip">KMOM06</a>
</nav>

KMOM05
==========================

Rapporten presenterar hastighet, föreslagna förbättringar och analyserade jämförelser hos 3 olika webbplatsers laddningstid och användbarhet.

Urval
-----------------------

Första urval av webbplats är den egna portfolio-sidan under menyval Gallery, vilket också var den andra uppgiften i detta kmom. Uppgiften "Gallery" är redan genomförd vid skrivande av denna rapport. Val av denna sida gjorde det möjligt att direkt i denna rapport kunna påverka och föra anteckning om faktiskt skillnad i prestanda.
Andra urvalet i denna rapport gjordes på den störtsta sökmotorn som existerar, Google.se. Val har gjorts att undersöka bild-resultatsidan av en bestämd sökning, "hund". Analys görs på bild-sökning för att ta reda på vilka optimeringar Google sjävla gör vid presentation av sökresultat konta orginalbild.
Tredje urvalet för denna rapport är webbsidan Coop.se. Valet gjordes då det privat väcktes en nyfikenhet om att det måste vara en extremt ansträngd sida rent prestandamässigt då stora bilder och rörliga animatoioner är det första som syns på startsidan. 


Metod
-----------------------

Prestanda kommer jämföras mellan dom tre webbplatsern med hjälp av pagespeed.web. Respektive webbplats tilldelas en procentsats och kan lätt då jämföras med varandra. Analys och data kommer hämtas från Devtools  och respektive relevant undermeny. Utvärdering och förbättringsförslag sker ur personlig åsikt och redovisas under Analys. 

Resultat
-----------------------

Sammanställning visar att google toppar listan för bästa prestanda för både mobila och fasta enheter. Maximal poäng är 100 och Googles bildsökning visar ett resultat på 46 för mobila enheter respektive 95 för fasta. Coop visar en ansträngd webbplats med resultat om endast 54 poäng för den fasta enheten. Google har på denna sida 203 resurser fördelat på sidans totala stolek 2,03MB i jämförelse med Coop med en total storlek på nästan det dubbla 4,35MB, dock ej det dubbla resurer, vilka var 291 st. Gallery visar ett bättre resultat än Coop med en poäng om 86 för datorer och 37 för mobila enheter. Sidans totala storlek är 1,49MB med resurser om 48 st. 


<iframe class="text" width="700" height="280" frameborder="0" scrolling="no" src="https://studentbth-my.sharepoint.com/personal/nasp22_student_bth_se/_layouts/15/Doc.aspx?sourcedoc={86860b3b-c902-474b-91a3-b962079da32e}&action=embedview&wdAllowInteractivity=False&wdHideGridlines=True&wdHideHeaders=True&wdDownloadButton=True&wdInConfigurator=True&wdInConfigurator=True&edesNext=true&edrtees6=false&resen=false"></iframe>


<h2> GOOGLE BILD-SÖK --> "Hund" </h2>

<p> Här visas det tydligt att google själva optimerar förhandsvisningen av sina bilder. Bästa resultat av samtliga tre webbplatser trots att webbplatsen visar extremt stort antal bilder och länkar. Ett stickprov gjordes på en av bilderna vars orginalstorlek var 54,9kB. Samma bild som förhandsvisas i googles resultat är då endast 6,84 kB. Det är svårt att föreslå förbättringsförslag åt en så pass stor och bra hemsida rent prestandamässigt. Självklart kan alla förbättra sig och en förbättring hade kanske varit att inte ha styling som rundade kanter på bilderna. Men i det stora hela känns det inte relevant utan resultatet är nästan felfritt. </p>

<br>

<figure class="print-screen">
<figcaption>Print-screen:</figcaption>
<img src="%base_url%/image/googl-hund.jpg?" class="pic" alt="print-screen-google-hund">
</figure>

<figure class="pagespeed">
<figcaption> Resultat pagespeed (Desktop): </figcaption>
<br>
<img src="%base_url%/image/google-prestanda.jpg" class="pic" alt="print-screen-ikea">
</figure>


<br>

<h2> COOP </h2>

<p> Som misstänkt gav det inga höga poäng för denna webbplats med stora bilder och rörliga animationer. Anmärkningsvärt var att bilder på startsidan har samtliga orginalstorlek 200 x 200 px och är ca 20-25 kB stora. Detta visar på att coop använder extremt högkvalitativa bilder,trots att majoriteten av bilderna visas endast i mindre format. Tydligt förbättringsförslag för detta hemsida att diskutera är storleken på bilderna som används. Alternativ som cimage eller olika bilder för olika platser skulle minska deras storlek avsevärt. 

</p>

<br>

<figure class="print-screen">
<figcaption>Print-screen:</figcaption>
<img src="%base_url%/image/coop.jpg" class="pic" alt="print-screen-ikea">
</figure>

<figure class="pagespeed">
<figcaption> Resultat pagespeed: </figcaption>
<br>
<img src="%base_url%/image/coop-prestanda.jpg" class="pic" alt="print-screen-ikea">
</figure>


<br>

<h2> Me-page - Gallery </h2>

<p> Här tar bilderna uppp den största delen av sidans storlek. Samtliga bilder ligger mellan 20-28 kB. Bilderna är relativt optimerade då de har olika källor för olika storlekar av fönstret. På så sätt har vi redan påverkat bildernas storlek och använder endast det som behövs för att önskat resultat.
Ytterligare förbättringsförslag att analysera kan vara att optimera även "bth-bladet" som i nuläget är hela 33,29kB i storlek.


</p>

<br>
<figure class="print-screen">
<figcaption>Print-screen:</figcaption>
<img src="%base_url%/image/gallery.jpg" class="pic" alt="print-screen-nivide">
</figure>

<figure class="pagespeed">
<figcaption> Resultat pagespeed: </figcaption>
<br>
<img src="%base_url%/image/gallery-prestanda.jpg" class="pic" alt="print-screen-ikea">
</figure>

<h1>Analys</h1> 

Google är dom stora vinnarna i denna rapport vilka fick bäst score både för desktop och mobila enheter. Google visar genom tt bilderna på sin egen sida är mindre än orginalen att dom själva optimerar för bästa resultat. Skillnad var det med coop.se. Deras bilder tog upp samma storlek oavsett om dom visades i litet eller stort exemplar. Det betyder att bilderna som används är extrem höguplösta för att kunnas användas som stora, men också överkvalificerade när de ska visas som små. Detta är deras främsta förbättringsåtgärd. Denna rapport fokuserade lite extra på just hur bilder påverkar prestandan och samtliga resultat hos pagespeed visade en gemensam förbättringsåtgärd för google och coop, att bilderna saknade width, och higth. I min egen gallery-sidan är dessa valda och dessutom förändras eftersom fönstret ändrar storlek. Me-page "Gallery" visade ett bra resultat under första undersökningen med 2,9 sekunder. Detta resultat redovisades inte utan åtgärder vidtogts direkt efter första testen. Vid start av denna rapport var det endast kodat så att bilderna skulle ändras beroende på fönsterstorleken. Varje bild i galleriet hade 4 olika bilder som visas beroende på skärm.
Efter första prövningen minskades även kvaliteten av bilderna i takt med att bilden minskade enligt nedan:
    
    <picture class="gallerybox">
        <source media="(min-width: 1700px)" srcset="image/skargard.jpg?w=350&h=350&crop-to-fit&q=80">
        <source media="(min-width: 1361px)" srcset="image/skargard.jpg?w=300&h=300&crop-to-fit&q=70">
        <source media="(min-width: 760px)" srcset="image/skargard.jpg?w=200&h=200&crop-to-fit&q=60">
        <source media="(min-width: 374px)" srcset="image/skargard.jpg?w=300&h=300&crop-to-fit&q=50">
        <img src="image/skargard.jpg?w=150&h=150&crop-to-fit&q=40" alt="skargard">
    </picture>

Denna åtgärd ledde till det redovisade resultatet på 2,2 sekunder. 

Enligt speedInsight anses det att ett laddningstid på mindre än 5 sekunder ändå är ett godkänt resultat. Personligen känns det svårt att direkt jämföra olika webbplatsers laddningstid rakt av och anse att en viss laddningstid är mer ok än någon annan. Jag anser att beroende på vad hemsidans syfte är förväntas sedan olika resultat. Coop som visar en hastighet på 4,8 sek anser jag inte alls är ett godkänt resultat. Företagets syfte och mål är att sälja mat. Det ska inte behövas så mycket upptagen storlek av media och bilder som det på denna sida är.
Denna webbsida borde utan problem kunna uppnå runt 2 sekunder där googles bildsökning ligger i denna rapport. Därför anser jag att Coop ej är godkända med sina 4,6 sekunder. Skulle google-bildsökning uppvisa ett resultat på 4,6 sekunder skulle jag däremot anse det som mer okej och ett godkänt resultat. Det är extremt många mängder sökningar och resultat som i form av media ska visas. Jag tycker därför inte att jag på rak arm kan meddela en gräns, utan jag anser att gränsen borde sättas efter webbplatsens sytfte. Är hastigheten snabb i jämförelse med vad hemsidan "måste" innehålla för att företaget ska fungera eller är mycket av innehållet lyx och onödig data? 


<h1> Referenser</h1> 

Urval webbsidor:
- https://www.coop.se/
- https://www.google.se/search?q=hund&sxsrf=ALiCzsZhmWnNpWr5_VcwMNARu1DjeJB5dw:1670062112924&source=lnms&tbm=isch&sa=X&ved=2ahUKEwj3j_mXmt37AhXqR_EDHfDFC9YQ_AUoAXoECAEQAw&biw=1873&bih=961&dpr=1
- http://www.student.bth.se/~nasp22/dbwebb-kurser/design/me/portfolio/gallery

- https://pagespeed.web

<h1> Övrigt </h1> 
Rapport skriven av Nadja Spångberg
