# Elektronica

## DRV8833 H-brug

Het gedeelte rond de DRV8833 is aangepast omdat jumper J2 aan de achterkant van de print is dichtgesoldeerd.

De datasheet noemt de betreffende pinnen **nSLEEP** en **nFAULT** (niet “EEP” en “ULT”):

- **nSLEEP** is een ingang, geen uitgang. Deze moet hoog zijn om de driver normaal te laten werken. Als de driver altijd actief moet zijn, kan nSLEEP volgens het ontwerp aan de logische voedingsspanning worden gelegd. Houd deze pin laag om de driver in slaapstand te zetten.
- **nFAULT** is een foutstatus-uitgang (open-drain). Deze is optioneel voor de besturing: je kunt hem aansluiten op een microcontroller-ingang als je foutmeldingen wilt uitlezen. Als je hem gebruikt, is een pull-up nodig. Als foutstatus niet nodig is, kan nFAULT ongebruikt blijven.

Controleer bij het aanpassen van J2 dat nSLEEP daadwerkelijk hoog wordt gemaakt; alleen nFAULT kan zonder verlies van de normale motorbesturing ongebruikt blijven.

Bron: [DRV8833-datasheet van Texas Instruments](https://www.ti.com/lit/ds/symlink/drv8833.pdf).
