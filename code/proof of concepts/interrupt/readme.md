# start/stop interrupt proof of concept

Deze POC test de werking van een start-stopdrukknop met een Arduino Nano en een LED.

Wanneer de drukknop wordt ingedrukt, wordt een hardware-interrupt geactiveerd. De interrupt schakelt de systeemstatus om tussen aan en uit. De LED geeft deze status weer: wanneer het systeem aan staat, brandt de LED; wanneer het uit staat, is de LED uit.

Het doel is om te testen hoe een hardware-interrupt kan worden gebruikt om onmiddellijk op een drukknop te reageren, zonder de knop voortdurend in de hoofdloop te controleren.
