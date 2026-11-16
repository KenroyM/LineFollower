# Elektronica

## DRV8833 H-brug

Het H-bruggedeelte is aangepast omdat jumper J2 aan de achterkant van de print is dichtgesoldeerd. J2 verbindt de SLEEP-aansluiting met de hoge logische spanning, zodat de DRV8833 uit de slaapstand komt en kan werken.

Op de print zijn de labels deels afgekort/afgesneden: **EEP** hoort bij **SLEEP** en **ULT** bij **FAULT**. Volgens de DRV8833-datasheet is SLEEP een ingang; deze moet hoog zijn om de driver normaal te laten werken. FAULT (nFAULT) is een open-drain foutstatus-uitgang. Die is niet nodig voor de normale motorbesturing en mag ongebruikt blijven als foutmeldingen niet worden uitgelezen.

Bron: [DRV8833-datasheet van Texas Instruments](https://www.ti.com/lit/ds/symlink/drv8833.pdf).
