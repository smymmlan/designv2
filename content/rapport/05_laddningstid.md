---
views:
    flash: false
---

Laddningstid
=======================


Urval
-----------------------
De tre webbplatser som valdes var desamma som i föregående kursmoment *[färgschema](rapport/fargschema)*, dvs webbplatser för de tre största matvarukedjorna i Sverige; ICA, Coop och Willys. Ambitionen var även i denna undersökning att möjliggöra jämförelse mellan webbplatserna utgörs därför av webbplatser för tre aktörer inom samma bransch. För att jämförelsen skulle vara relevant genomfördes en initial analys av de tre webplatserna för att identifiera specifika undersidor som förekom på samtliga webbplatser. Utöver webplatsernas startsidor valdes undersidor för frågor och svar samt undersidor för att lokalisera butik.

Länkar:

* [ica.se](https://www.ica.se/)
* [ica.se/butiker](https://www.ica.se/butiker/)
* [ica.se/kundtjanst/vanliga-fragor](https://www.ica.se/kundtjanst/vanliga-fragor/)
* [coop.se](https://www.coop.se)
* [coop.se/handla-online/vanliga-fragor](https://www.coop.se/handla-online/vanliga-fragor/)
* [coop.se/butiker-erbjudanden](https://www.coop.se/butiker-erbjudanden/)
* [willys.se](https://www.willys.se/)
* [willys.se/butik-sok](https://www.willys.se/butik-sok)
* [willys.se/artikel/kundservice/vanliga-fragor-och-svar](https://www.willys.se/artikel/kundservice/vanliga-fragor-och-svar)

Metod
-----------------------
Analysen genomfördes med PageSpeed Insights och nätverksverktyget i Inspektörsdelen i Firefox Developer Edition. De utvalda sidorna på respektive webbplats undersöktes först i PageSpeed Insights och Hsdtighetsresultatet noterades. Därefter laddades sidorna i tur och ordning i Firefox Developer
Edition. Denna procedur upprepades tre gånger. För varje laddning av en specifik sida noterades mätvärdet för de tre parametrarna laddningstid, resurser och total sidstorlek. Därefter beräknades ett genomsnitt för varje mättal utifrån de tre laddningstillfällena.

För varje webbplats beräknades en sammanvägd bedömning för varje undersökt sida. För att ta hänsyn till relativa skillnader i mättal räknades de värdena för laddningstid, resurser och sidstorlek för var och en av de tre undersökta sidorna om till ett relativt värde. Dessa värden multiplicerades sedan till en total score (som döptes till SC-score efter "upphovshennens" initialer). För varje webbplats erhölls således en relativ totalscore för var och en av de undersökta sidorna.

För att också göra det möjligt att bedöma de olika webbplatserna mot en gemensam standard användes Google Doubleclicks
slutsats att 53% av besök via mobil avslutades innan sidan laddat om sidan tog mer än tre sekunder att ladda färdigt.


Resultat
-----------------------
Rasultaten redovisas i diagramen (figur 1 - 3) samt i kalkylarket *[länk](http://www.student.bth.se/~samt18/dbwebb-kurser/design/me/kmom05BU.xlsx)*.
[FIGURE src="image/startsidor.png?h=150&convolve=sharpen" class="pics" alt="resultat" caption="Figur 1"]

[FIGURE src="image/hitta-butik.png?h=150&convolve=sharpen" class="pics" alt="resultat" caption="Figur 2"]

[FIGURE src="image/fragor_och_svar.png?h=150&convolve=sharpen" class="pics" alt="resultat" caption="Figur 3"]


Samtliga webbplatser erhöll en relativt hög score i PageSpeed Insights desktop-analys med relativt låg variation. Spridningen var dock betydligt högre vad det gäller undersökningen av mobilanpassning. Samtliga sidor bedömdes således vara mer anpassade för stationära enheter.

Analys
-----------------------
Analysen av de egna mätetalen gav vad det gäller ranking av sidorna i stort samma uftall som Google PageSpeed
Insights Mobile. ICAs starsida fick bäst totalscore men vad det gäller de undersökta undersidorna erhöll Coop
högst totalvärde. Utifrån antagandena att besökare har mer tålamod med laddning av undersidor än startsidan samt
att majoriteten av besökarna når undersidorna via startsidan bedöms startsidans laddningstid vara den viktigare
parametern. Samtliga startsidor visade i stort samma laddningstider och ingen av webbplatserna stack således ut i
detta avseende.

Även om samtliga sidor uppvisade en relativt lång laddningstid bör det understrykas att denna speglar den totala
laddningstiden och inte tiden fram till den första meningsfulla renderingen av sidinnehåll. I praktiken innebär detta
att besökarna upplever de olika webbsidorna som laddade betydligt tidigare än de faktiskt är färdigladdade.

Detta gör bedömningen av laddningstid mot en bestämd gräns aningen problematiskt. Så gott som samtliga laddningstider
översteg gränsen på 3 sekunder. Google PageSpeed indikerade dock att den första meningsfulla skärmuppritningen varierade
mellan de olika webbplatserna och att endast Coop uppvisade en tid för första meningsfulla skärmuppritning som kunde
betraktas som låg för laddning på mobil. Av denna anledning bedömdes Coops webbplats som den effektivaste utifrån ett
laddningstidsperspektiv.


Referenser
-----------------------
https://developers.google.com/web/fundamentals/performance/why-performance-matters/


Genomförd av
-----------------------

Sarah Mattsson och Christopher Svensson
