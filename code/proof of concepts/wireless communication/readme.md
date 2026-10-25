# draadloze communicatie proof of concept

Deze POC toont aan dat duplexcommunicatie mogelijk is tussen een Arduino Nano en een smartphone via een HC-08 Bluetooth-module.

### Configuratie

**Hardware:**
- Arduino Nano
- HC-08 Bluetooth-module
- USB-kabel

**Software:**
- Arduino IDE
- Serial Bluetooth Terminal-app
- Baudrate: 9600 bps

**Aansluitingen:**

| HC-08 | Arduino Nano |
|---|---|
| VCC | 5V |
| GND | GND |
| TXD | D0 / RX |
| RXD | D1 / TX |
| STATE | Niet aangesloten |
| KEY | Niet aangesloten |

### Opmerkingen

De HC-08 communiceert via UART met de Arduino Nano en via Bluetooth met de smartphone. De communicatie verloopt in beide richtingen.

De Arduino verzamelt de ontvangen tekens tot een regeleinde (`\n`) wordt ontvangen. Daarna stuurt hij het volledige bericht terug naar de smartphone. Daarnaast stuurt de Arduino automatisch elke seconde het bericht `Hallo vanaf Arduino`.

### Gebruiksaanwijzing

1. Sluit de HC-08 aan op de Arduino Nano.
2. Upload de code via de Arduino IDE.
3. Verbind de smartphone met de HC-08 via de Serial Bluetooth Terminal-app.
4. Controleer of het bericht `Hallo vanaf Arduino` ongeveer elke seconde verschijnt.
5. Verstuur een volledige zin vanuit de smartphone en zorg dat de app een regeleinde (`\n`) meestuurt.
6. Controleer of de Arduino de volledige zin terugstuurt met `Ontvangen:` ervoor.

Hiermee wordt aangetoond dat de Arduino Nano en smartphone gegevens in beide richtingen kunnen uitwisselen.
