# Sensoren proof of concept

Deze POC toont de werking van een 8-kanaals IR-lijnsensor met een Arduino Nano.

De acht sensoren (D1–D8) worden afzonderlijk uitgelezen via de analoge pinnen A7–A0 van de Arduino Nano. Deze pinnen worden in de code als digitale ingangen gebruikt.

De sensoren geven een digitaal signaal van `0` of `1`. De waarden worden via de Serial Monitor weergegeven, zodat kan worden aangetoond dat de acht sensoren onafhankelijk van elkaar kunnen worden uitgelezen.

Voorbeeld:

```text
S1: 1  S2: 1  S3: 0  S4: 0  S5: 1  S6: 1  S7: 0  S8: 1
```
