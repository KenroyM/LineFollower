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

### Opmerkingen
De HC-08 communiceert via UART met de Arduino Nano en via Bluetooth met de smartphone. De communicatie verloopt in beide richtingen.

### Gebruiksaanwijzing
1. Sluit de HC-08 aan op de Arduino Nano.
2. Upload de code naar de Arduino Nano.
3. Verbind de smartphone met de HC-08 via de Bluetooth-app.
4. Controleer of berichten van de Arduino op de smartphone verschijnen.
5. Verstuur een bericht vanaf de smartphone en controleer of de Arduino dit terugstuurt.


