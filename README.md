> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je, zoals altijd, in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Titel

Rapportage webtoegankelijkheid-test voor Beyco Coffee Page

![Usabilitytestbeyco](https://github.com/aajubitana/chippr-beyco-a11y-audit-autonomous/blob/main/Schetsen%20Sprint%203/bijlage/usabilitytest.jpg)

## Beschrijving

Dit document is een template voor een webtoegankelijkheid-test volgens de Web Content Accessibility Guidelines (WCAG). Een consistente rapportage helpt bij het uitvoeren van een evaluatie en zorgt er voor dat verschillende tests kunnen worden vergeleken.

In deze rapportage wordt het detail pagina getest aan de hand van de checklist van het a11y project.

Datum webtoegankelijkheid-test: 29-10-2021

Webtoegankelijkheid-test uitgevoerd door: Armando Jubitana

## Inhoudsopgave

- [Titel](#titel)
  * [Samenvatting](#Samenvatting)
  * [Achtergrond bij de evaluatie](#Achtergrond bij de evaluatie)
  * [Afbakening](#Afbakening)
  * [Beoordelaars](#Beoordelaars)
  * [Beoordelingsproces](#Beoorderlingsproces)
  * [Testresultaten en aanbevelingen](#licentie)

## Samenvatting

Dit rapport beschrijft in hoeverre de website beyco.nl overeenstemt met de Web Content Accessibility Guidelines (WCAG) van het W3C.

Conslusie van deze test luidt dat de Beyco website voldoet de WCAG 2.1, op niveau AA. Gedetailleerde resultaten en aanbevelingen zijn verderop in dit document beschikbaar en in de referenties vindt u bronnen voor eventuele vervolgstudie. Wij stellen feedback op deze evaluatie zeer op prijs.

## Achtergrond bij de evaluatie

De webtoegankelijkheid-test vereist een combinatie van semi-geautomatiseerde en handmatig uitgevoerde evaluatie tools door een ervaren beoordelaar. De beoordelingsresultaten in dit rapport zijn gebaseerd op een beoordeling welke is uitgevoerd op 2-11-2021. De website kan ondertussen aangepast zijn.

## Afbakening

Beyco is een wereldwijde platform waarbij koper en verkopers met elkaar in contact kunnen komen en ook kunnen handelen in koffie.
doel is om te kijken of er verbeteringen zijn in het gebruik van de detailpagina en of het geschikt is voor de doelgroep die ze voor ogen hebben.

Dit is de link van de website die wordt getest: https://test.beyco.chippr.dev/trade/offers/bf829616-ec18-45be-b74d-d4769adc1beb


## Beoordelaars

Armando Jubitana
Student
armando.jubitana@hva.nl

Nederlands

## Beoordelingsproces

Deze beoordelings is uitgevoerd op WCAG 2.1 Niveau AA

De tools die zijn gebruikt voor deze beoordeling zijn de volgende:

[A11Y Checklist](https://www.a11yproject.com/checklist/)
[WCAG Guidelines Overview](https://www.w3.org/WAI/standards-guidelines/wcag/)
[Google Lighthouse](https://developers.google.com/web/tools/lighthouse)


## Testresultaten en aanbevelingen

De detail pagina van Beyco voldoet niet aan niveau AA van de WCAG 2.1.

Er zijn bepaalde verbeterpunten en dat is vooral mobiel gericht, de layout oogt wat netter als de kolommen met content in het midden gecentreerd is en wat breder waren zodat de kaart of iframe beter past.
Ook is het mogelijk om sommige apparaten zowel verticaal als horziontaal te 
scrollen wat voor veel mensen niet handig is en soms voor irritatie kan zorgen.

Ook contrast van kleine teksten in het grijs is slecht te zien voor mensen die al minder kunnen zien dan is een hoger contrast veel meer leesbaar.
Ook mensen met kleurenblindheid zien de groene kleuren tekst niet het wordt volgens hen grijs weergeven maar de linkjes en buttons zijn wel goed te zien.

Checklist

- Forms
n.v.t.

- Media
n.v.t.
- Video
n.v.t
- Audo
n.v.t.

Appearance

   Check your content in specialized browsing modes.
    - Alles is goed zichtbaar ook in hoogcontrast modes kun je nog links en blokjes van content zien.
      Increase text size to 200%.
    - Ook bij het zoomen van browser naar 200% is toch alles duidelijk te zien en is content netjes in het midden van de browser.
      er is geen overlapping van content.
   
    Double-check that good proximity between content is maintained.
    - Doormiddel van de strawtest kun je zien dat content goed gegroepeerd is en blokjes die bij elkaar horen toch duidelijk is en de samenhang van informatie.
 
    Make sure color isn't the only way information is conveyed.
    - Met Greyscale filter zijn de linkjes nog steeds te zien doormiddel van blokjes.
 
    Make sure instructions are not visual or audio-only.
     n.v.t.
 
    Use a simple, straightforward, and consistent layout.
    De pagina heeft een goede layout, goede en logische verhoudingen.
    
Animation 
     Ensure animations are subtle and do not flash too much.
     - Animaties zijn heel subtiel ze gaan niet snel en wekken geen irrities op.
     
     Provide a mechanism to pause background video.
     - n.v.t.
     
     Make sure all animation obeys the prefers-reduced-motion media query.
     - Animaties worden niet weergeven in een prefers-reduced-motion media query.
     
Color Contrast 

     Check the contrast for all normal-sized text.
     - Normal sized text bevat een contrast ratio van 2.55:1 dat is niet voldoende.
     
     Check the contrast for all large-sized text.
     - Dik gedrukte teksten bevat een contrast ratio van 21:1 en dat voldoet.
     
     
     
     Check the contrast for all icons.
     - Icoontjes op de detailpagina bevat een contrast ratio van 4:73:1 en dat voldoet.
     
     Check the contrast of borders for input elements (text input, radio buttons, checkboxes, etc.)
     - Ook voor de borders teksten en buttons is contrast ratio 4:73:1 en dat voldoet aan de eis van 3:0:1
     
     Check text that overlaps images or video.
     - n.v.t.
     
     Check custom ::selection colors.
     - n.v.t.
     
Mobile and Touch
 
     Check that the site can be rotated to any orientation.
     - De pagina kan goed geroteerd worden alhoewel het soms op sommige apparaten niet in alle hoeken geroteerd kan worden bijvoorbeeld 
     de Iphone 12 kan het niet op z'n kop weergeven worden.
     
     Remove horizontal scrolling
     - De pagina kan zowel verticaal als horizal gescrolled worden op sommige apparaten.
     Alhoewel het handig is dat horizontale scrol niet mogelijk moet zijn. Alleen verticaal.
     
     Ensure that button and link icons can be activated with ease. 
     - Buttons en link iconen zijn goed klikbaar alhoewel sommige icoontjes overlappen
    
     Ensure sufficient space between interactive items in order to provide a scroll area. 
     Er is voldoende ruimte om te scrollen voor op de mobiel.
    
 
 
 
 
 
 
## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
