# 8x IR-lijnvolgmodule

**Uitvoering volgens de stuklijst:** 8-kanaals IR-lijnvolgmodule. Een modelnummer of revisie staat niet in de stuklijst; de HY-S301 is een mogelijke overeenkomst, maar dit is niet bevestigd. Daarom zijn de pinfuncties hieronder niet als gegarandeerde fysieke connectorvolgorde te beschouwen.

## Specificaties

| Eigenschap | Gegeven | Opmerking |
|---|---:|---|
| Voedingsspanning | 3,3–5 V | Zoals vermeld in de bestaande projectnotitie/productbron. Controleer de markering op de eigen module. |
| Stroomverbruik | Niet betrouwbaar gevonden voor de exacte module | Verschilt met IR-leds en module-uitvoering; meet dit of raadpleeg de exacte productpagina. |
| Sensoruitgangen | 8 kanaaluitgangen | De uitgang kan analoog of digitaal zijn afhankelijk van de module; controleer de print/documentatie. |

## Aansluitingen en pinvolgorde

De gebruikelijke aansluitfuncties zijn **VCC**, **GND** en de acht kanaaluitgangen (**OUT1–OUT8**, soms **D1–D8**); sommige varianten hebben ook een **LED/IR-enable**-aansluiting. De exacte fysieke volgorde op de connector is niet vastgesteld voor de module in dit project. Volg de labels op de print en de specifieke productdocumentatie, en sluit niet aan op basis van een veronderstelde links-naar-rechts volgorde.

## Bronnen

- [TinyTronics — 8x IR Line Tracking Module (HY-S301)](https://www.tinytronics.nl/en/sensors/optical/infrared/8x-ir-line-tracking-module) — waarschijnlijke productfamilie; bevestig dat dit dezelfde uitvoering is.
- [Einstronic — HY-S301 8-Channel Line Tracking Sensor Module](https://einstronic.com/product/hy-s301-8-channel-line-tracking-sensor-module/) — productinformatie.

**Nog te controleren aan het eigen onderdeel:** model/revisie, connectorlabels en -volgorde, uitgangstype en stroomverbruik.
