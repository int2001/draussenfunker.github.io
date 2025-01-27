---
sidebarDepth: 2
description: Eine Portable Viertelwellen Vertikalantenne für 10 - 20 Meter und kleines Geld - selbstgebaut
head:
  - - meta
    - property: og:image
      content: https://draussenfunker.github.io/images/diy/teleskop-viertelwellen-vertical/action-shot-stadpark.jpeg
---

# Teleskop 1/4 Lambda Vertikal

![In Aktion im Stadtpark](/images/diy/teleskop-viertelwellen-vertical/action-shot-stadpark.jpeg)
Eine Portable Viertelwellen Vertikalantenne für 10 - 20 Meter und kleines Geld - selbstgebaut.

## Bauteile / Bezugsquellen

Die Antenne besteht im Wesentlichen aus einer 5,6 m langen Teleskop Antenne, welche mit einer Halterung und einem Dorn im Erdboden befestigt wird.

Problematisch an günstigen Teleskopantennen aus Fernost ist, dass diese, im Gegensatz zu z.B. den Produkten von MFJ, ein M10 Gewinde haben und nicht das gängigere 3/8".
::: tip
Wer schon eine HF-P1 oder eine PAC-12 Antenne besitzt, kann diese prima mit dem unten angegeben langen Teleskop kombinieren. 
:::
Daher hier eine kleine Liste mit Bezugsquellen und Bauteilen.

| Bauteil       | ca. Preis Stand 08/2022     |
| ------------- | -----:|
| [5,6m Teleskopantenne mit M10 Gewinde - BD7IBI](https://de.aliexpress.com/item/1005004139955542.html)   | 25,00 Euro |
| [Halterung](https://smile.amazon.de/Albrecht-Antennenhalterung-3-8-6197-Silber/dp/B002VASO5U/)     |    10,00 Euro |
| [Einbauchfuß M10 auf PL](https://difona.de/amateurfunk/geraetezubehoer/ersatzteile/1880/einschraub-pl-auf-m-10-fuer-hfp-1) | 8,50 Euro |
| [Litze für Radiale - Fahrzeugleitung FLRY 0,75mm² o.ä](https://www.ebay.de/itm/403789483361)| 20,00 Euro |
| 12mm durchmessender Aluminium Rundstab (Baumarkt, Amazon, ebay, Bastelkiste)| 5,00 Euro |
| Schrauben, Stecker ggf. Kabelschuhe  (Baumarkt, Amazon, ebay, Bastelkiste)| 10,00 Euro|
|**Summe**| **78,50 Euro**

::: warning Hinweis 
Die Teileauswahl ist nur ein Vorschlag und nicht notwendigerweise immer verfügbar. 
Wichtig ist es, das Prinzip der Bauweise zu verstehen und für die Bauteile ggf. das zu benutzen, was man schon hat oder leicht bekommen/bauen kann.
Wir freuen uns über Eure Abwandlungen. 
:::


## Zusammenbau

Halterung und Einbaubuchse bedürfen im Aufbau keiner weiteren Erklärung.

### Erddorn     

Von dem Aluminium Rundstab längt man ca. 30 cm ab. 

Das Anspitzen erfolgt durch etwas manuelle Vorarbeit mit einer groben Pfeile und anschließender Feinarbeit eingespannt in einer Bohrmaschine oder einen Akkuschrauber.

::: danger Vorsicht
Schutzbrille aufsetzen und Handschuhe an! Metallspäne im Auge oder sonst wo im Körper sind nicht cool :) 
:::

### Radials

Da es sich bei den Radials nicht um "Elevated Radials", sondern "Ground Radials" handelt, müssen diese nicht abgestimmt sein.
16 bis 32 Radials in 2 - 3 m Länge sind ein guter Kompromiss in Hinblick auf Portabilität und Antennen Fußabdruck.

In diesem Beispiel sind es 32 Stück a 2,5 m Länge

![Radilas](/images/diy/teleskop-viertelwellen-vertical/radials.jpg)

Um die Radials an der Halterung zu befestigen, wurde ein weiteres Loch in die Halterung gebohrt und ein Gewinde geschnitten.

Natürlich kann man die Radials auch direkt an den Schrauben der Halterung befestigen.

![Radial Befestigung](/images/diy/teleskop-viertelwellen-vertical/radial-mount-closeup.jpg)

### Fertig

![Alles Fertig](/images/diy/teleskop-viertelwellen-vertical/collapsed.jpg)

## Abstimmung / Aufbau

Der Aufbau und die Abstimmung sind denkbar einfach:

- Alu Dorn in den Boden stecken
- Radials Auslegen
- Teleskopantenne aufschrauben
- Mit VNA (z.B. Nano VNA) auf das gewünschte Band abstimmen.

Noch schneller geht es, wenn man sich mit einem wasserfesten Stift kleine Markierungen an dem Teleskop macht, damit man die Bänder schneller grob wiederfindet.
Feinabgestimmt werden muss natürlich trotzdem.

Die Antenne lässt sich durch Ausziehen des Teleskops problemlos für 10 - 20 Meter abstimmen.

Hier ein paar Screenshots von den Abstimmwerten für das 15 Meter Band , beim Aufbau im Stadtpark Hamburg.

Auf anderen Bändern sind die Ergebnisse ähnlich.

**VSWR**:

![VSWR auf 15m](/images/diy/teleskop-viertelwellen-vertical/swr-15m-band-cropped.jpg)

**Smith Diagram**:

![Smith auf 15m](/images/diy/teleskop-viertelwellen-vertical/smith-15m-band-cropped.jpg)

## Feedback?

Du kannst mit uns auf [Discord](https://discord.gg/B6BkdcTQ87) in Kontakt treten und uns mit Fragen bombardieren oder Feedback geben. Wie freuen uns.
