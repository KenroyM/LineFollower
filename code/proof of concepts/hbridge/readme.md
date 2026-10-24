# H-Bridge proof of concept

Deze POC test de aansturing van twee DC-motoren met een Arduino Nano en een DRV8833 H-brug.

De Arduino stuurt beide motoren gelijktijdig aan. Met PWM wordt de motorsnelheid geleidelijk verhoogd en verlaagd. Daarnaast wordt de draairichting aangepast, zodat we kunnen testen of de motoren zowel vooruit als achteruit kunnen draaien.

Het doel is om de werking van de motorsturing te testen voordat deze wordt geïntegreerd in de line follower-robot.
