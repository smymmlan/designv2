---
views:
    flash: false
---

Uppdrag 2: Analys valfri - Mobila laddningstider på svenska lärosätens webbplatser.
=======================

De senaste decenniets utveckling av såväl mobila enheter som mobila uppkopplingshastigheter har sannolikt medfört att fler och fler webbplatsbesök kommer från mobiltelefoner och surfplattor. Enligt StatCounter Global Stats passerade mobil internetanvändning den traditionella som sker via datorer, redan under 2016 och statistiken över senaste året indikerar att trenden har hållit i.

Den ökande frekvensen av mobila webbanvändning aktualiserar behovet av att anpassa webbplatser och design av sådan för att stödja de begränsningar som mobil internetanvändning medför. Sådana begränsningar omfattar såväl begränsningar relaterade till mindre skärmar som anpassning till lägre överföringshastigheter. DoubleClick by Google drog i en studie slutsatsen att 53% av mobila webbplatsbesök avbröts om den sökta sidans laddningstid översteg 3 sekunder. Denna slutsats visar på vikten av att anpassa webbplatser på ett sådant vis att laddningstiden inte begränsas av att webbplatsen besöks via en mobil enhet.

Denna analys syftar till att undersöka webbplatserna för Sveriges universitet och högskolor avseende anpassning till avbrutna besök till följd av begränsade laddningstider. Frågeställningen som analysen avser att besvara är hur stor andel av lärosätenas webbplatser som hade en laddningstid som översteg 3 sekunder.

Urval
----------------

Webbplatser för Sveriges universitet och högskolor valdes då dessa kan antas ha en stor andel besökare som är benägna att besöka webbplatser via mobila enheter.


Metod
-----------------------

De olika webbplatserna undersöktes med PageSpeed Insights (SPI). SPI ger ett antal olika mått på sidans laddningstider så som den tid det tar till dess att första meningsfulla uppritningen av innehåll skett, hastighetsindex och tid till dess att användaren kan interagera med sidan. Som mått på hastighet valdes i denna analys Första uppritningen av innehåll baserat på Lighthouse-analys med 3G-emulering, då detta mätvärde enligt Tools for web developers indikerar en viktig aspekt av sidladdning då den ger besökaren en indikation på att sidan laddas vilket sannolikt motiverar besökaren att stanna kvar på sidan.

Mätvärdet för första uppritningen av innehåll noterades för respektive webbplats. Därefter undersöktes hur stor andel av dessa som uppvisade en laddningstid som var högre än tre sekunder. Tre sekunder användes som en absolut gräns för tillräcklig anpassning till de begränsningar som mobila enheter medför mot bakgrund av den studie som refereras i inledningen.


Resultat
-----------------------
En sammanställning av resultaten presenteras i diagram 1.

[FIGURE src="image/resultat.png?h=250" class="pics" alt="resultat" caption="Diagram 1"]

16 av de 31 undersökta webbplatsernas startsidor uppvisade en laddningstid som var högre än 3 sekunder. Det genomsnittliga värdet var 3,12 sekunder med en standardavvikelse på 1,8 sekunder och variationsvidden var 4,3 sekunder.



Analys
-----------------------

Givet att en absolut gräns på tre sekunder används som skiljelinje mellan tillräckligt och otillräckligt mobilanpassade webbsidor förefaller fler än hälften av de undersökta webbsidorna vara otillräckligt designade för att överbrygga de begränsningar som mobil webbanvändning medför. För webbplatserna innebär detta således risken att besöksantalet är betydligt lägre än antalet besöksförsök.

En möjlig metodologisk brist i denna analys är tillfället då den genomförs. Ett rimligt antagande är att trafiken mot ett lärosätes webbplats är tyngre än vanligt vid terminsstarter. Detta skulle möjligen kunna medföra att de uppmätta laddningstiderna egentligen begränsas av belastning på de servrar som webbplatserna huserar på snarare än av bristande design vilket denna analys inriktats på. Från en pragmatisk utgångspunkt spelar detta dock mindre roll givet den andel av de mobila webbplatsbesöken som avbryts vid laddningstider längre än 3 sekunder. Sammantaget kan således slutsatsen dras att flertalet lärosäten har skäl att se över dina webbplatser utifrån ett laddningstidsperspektiv.


Referenser
-----------------------
[http://gs.statcounter.com/press/mobile-and-tablet-internet-usage-exceeds-desktop-for-first-time-worldwide](http://gs.statcounter.com/press/mobile-and-tablet-internet-usage-exceeds-desktop-for-first-time-worldwide)

[http://gs.statcounter.com/platform-market-share/desktop-mobile-tablet](http://gs.statcounter.com/platform-market-share/desktop-mobile-tablet)


[https://developers.google.com/web/fundamentals/performance/why-performance-](https://developers.google.com/web/fundamentals/performance/why-performance-)

[https://developers.google.com/web/tools/lighthouse/audits/first-contentful-paint](https://developers.google.com/web/tools/lighthouse/audits/first-contentful-paint)


Genomförd av
-----------------------

Sarah Mattsson och Christopher Svensson
