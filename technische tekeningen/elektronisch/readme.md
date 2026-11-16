# Elektronica

## H-brug

Het gedeelte van de H-brug is aangepast omdat J2 aan de achterkant van de print is dichtgesoldeerd.

## EEPROM

Voor de Arduino Nano is geen externe EEPROM nodig voor de opgeslagen instellingen, zolang die binnen de beschikbare capaciteit passen. De Nano gebruikt een ATmega328P, die volgens de [datasheet van de ATmega328P](https://ww1.microchip.com/downloads/en/DeviceDoc/atmel-42735-8-bit-avr-microcontroller-atmega328-328p_datasheet.pdf) 1 KB interne EEPROM bevat. Deze EEPROM bewaart gegevens ook wanneer de voeding uitstaat.

De bestaande code gebruikt EEPROM-functies om gegevens in het geheugen van de microcontroller op te slaan. Een externe EEPROM is alleen nodig als er meer dan 1 KB opslagruimte nodig is of als er een andere specifieke toepassingseis is.
