# Aslong JGA12-N20-30 DC-transmissiemotor

**Uitvoering volgens de stuklijst:** 6 V, 500 RPM, overbrenging 30:1, N20-formaat. Er is geen datablad gevonden dat gegarandeerd bij exact deze Aslong-uitvoering hoort. De waarden hieronder zijn daarom gemarkeerd naar betrouwbaarheid; controleer de productpagina en motor zelf.

## Specificaties

| Eigenschap | Gegeven | Opmerking |
|---|---:|---|
| Nominale spanning | 6 V DC | Volgens de gekozen productomschrijving. |
| Onbelast toerental | 500 RPM | Volgens de gekozen productomschrijving; belasting verlaagt het toerental. |
| Onbelaste stroom | circa 40 mA | Vermeld bij de productvermelding van TinyTronics; afhankelijk van uitvoering en spanning. |
| Stroom onder belasting | Niet betrouwbaar vastgesteld | Afhankelijk van belasting. Dimensioneer de driver niet op een schatting. |
| Blokkeerstroom | Niet bevestigd voor exact dit model | Een generieke N20-bron vermeldt waarden rond 0,67 A, maar dat is geen gegarandeerde waarde voor deze motor. Voorkom langdurig blokkeren. |
| Aansluiting | 2 motordraden | Sluit aan op de motoruitgangen van de H-brug; polariteit bepaalt de draairichting. Kleurcodering is niet gegarandeerd. |

## Aansluitvolgorde

Dit is een eenvoudige tweedraads DC-motor, geen encoderuitvoering: de twee motorleidingen zijn de twee aansluitingen. Er is geen vaste polariteit voor vooruit; verwissel de draden of keer de H-brug-aansturing om de draairichting te veranderen. Controleer bij de eigen motor of er daadwerkelijk twee draden zijn.

## Bronnen

- [TinyTronics — Aslong JGA12-N20-30, 6 V, 500 RPM](https://www.tinytronics.nl/en/mechanics-and-actuators/motors/dc-motors/aslong-jga12-n20-30-dc-transmission-motor-6v-500rpm) — productgegevens.
- [HandsOn Tech — G12-N20 geared mini DC motor (PDF)](https://www.handsontec.com/dataspecs/motor_fan/GA12-N20.pdf) — algemene N20-familiegegevens; niet noodzakelijk exact dezelfde motor/overbrenging.

**Let op:** de stroom en het toerental van een DC-motor hangen af van de belasting. Gebruik geen generieke stall-/blokkeerstroom alsof die gegarandeerd is voor dit exemplaar.
