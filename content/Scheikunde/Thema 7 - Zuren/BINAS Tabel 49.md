---
title: BINAS Tabel 49 en rekenvoorbeelden
---
# Hoe lees je BINAS tabel 49 af?
![[BINAS Tabel 49.png]]
- In BINAS tabel 49 staan zuren en base en hun evenwichtsconstanten K<sub>z</sub> en de pK<sub>z</sub>. Die laatste wordt bijna niet gebruikt maar geeft wel een indicatie voor de zuurgraad.
- Aan de linkerzijde staan zuren op volgorde van sterke zuren naar zwakke zuren. Dat is te zien aan de K<sub>z</sub> waarden maar nog duidelijker aan de pK<sub>z</sub>, die enorm laag is (dus erg zuur!) aan de bovenkant van de lijst.
- Voor de basen aan de rechterzijde is het net andersom: de zwakke basen staan bovenaan en de sterke basen staan onderaan de lijst. Dat is op dezelfde manier te zien aan de K<sub>b</sub> en pK<sub>b</sub>, al is het duidelijker te zien aan de laatste.
- Het gaat hier om niet-geioniseerde moleculen, dus de zuur- of basemoleculen voordat ze zijn opgelost in water.

# Twee rekenvoorbeelden
## Sterk zuur
- Vraag: Wat is de pH van 0,1 M HCl?
- HCl is een sterk zuur. Dat is te zien omdat het heel hoog in de lijst van zuren staat. De Kz is ook 1, wat betekent dat het een aflopende reactie is (zie [[5 - Zwakke zuren]]) en dus alles reageert.
- Reactievergelijking:

 $$HCl \rightarrow H^{+} + Cl^{-}$$
- Alles reageert naar H<sup>+</sup>, en omdat het een sterk zuur is kun je stellen dat er ook 0,1 M H<sup>+</sup> ontstaat.
- Zodoende is de pH:

$$ pH = -log^{0,1} = 1$$
## Zwak zuur
- Vraag: Wat is de pH van 2 M CH<sub>3</sub>COOH?
- CH<sub>3</sub>COOH is een zwak zuur. Het staat wat lager in de lijst van zuren, en heeft een K<sub>z</sub> van 1,4 x 10<sup>-5</sup>. Dat geeft aan dat het een zwak zuur is en dat het om een evenwichtsreactie gaat (zie [[5 - Zwakke zuren]]) en dus *niet* alles reageert naar H<sup>+</sup>.
- Reactievergelijking:
 
$$CH_{3}COOH \rightleftharpoons H^{+} + CH_{3}COO^{-}$$
- Niet alles reageert, dus we moeten bepalen hoeveel dat is. Er reageert *x* M CH<sub>3</sub>COOH, en er ontstaat *x* M H<sup>+</sup>.
- Laten we eerst de evenwichtsvoorwaarde opstellen:

$$K_{z} = \frac{[H^{+}]\times[CH_{3}COO^{-}]}{[CH_{3}COOH]}$$
- Optioneel: je kunt in een tabelletje overzichtelijk maken hoeveel er van iets reageert, maar dat hoeft niet. Als je het snapt kun je het ook gelijk in de eventwichtsvoorwaarde doen.

|                | CH<sub>3</sub>COOH | H<sup>+</sup> | CH3COO<sup>-</sup> |
| -------------- | ------------------ | ------------- | ------------------ |
| <sub>t</sub>0  | 2 M                | 0 M           | 0 M                |
| Omgezet        | - x                | + x           | + x                |
| <sub>t</sub>ev | 2 - x M            | x M           | x M                |
- Verwerk dit samen met het gegeven uit BINAS in de evenwichtsvoorwaarde:

$$K_{z} = \frac{[H^{+}]\times[CH_{3}COO^{-}]}{[CH_{3}COOH]}$$

$$1,4 \times 10^{-5} = \frac{x\times x}{2 - x} = \frac{x^{2}}{2 - x}$$
- De *x* in de noemer wordt verwaarloosd omdat dit vaak heel erg weinig is. Dus dit wordt de vergelijking:

$$1,4 \times 10^{-5} = \frac{x^{2}}{2}$$

$$x = \sqrt{1,4\times10^{-5}\times2} = 5,3 \times 10^{-3}$$
- Nu weet je hoe groot \[H<sup>+</sup>\] is, en kun je daarmee de pH van de oplossing berekenen:

$$pH = -log^{5,3\times10^{-3}} = 2,28$$
- Best een gedoetje, maar als je het truukje kent lukt het al heel snel! Dus samengevat:
	- Reactievergelijking en evenwichtsvoorwaarde opstellen
	- K<sub>z</sub> invullen en berekenen hoeveel \[H<sup>+</sup>\] er ontstaat.
	- De pH berekenen.

## Maar wat als ik de molariteit niet heb?
- Voorbeeld: je lost 10 gram CH<sub>3</sub>COOH op in 500 mL water.
- De molmassa van CH<sub>3</sub>COOH is 60,052 g/mol:

| Element | Massa element | Aantal | Totale massa |
| ------- | ------------- | ------ | ------------ |
| C       | 12,01         | 2      | 24,02        |
| H       | 1,008         | 4      | 4,032        |
| O       | 16,00         | 2      | 32           |
| Totaal  |               |        | 60,052       |
- Bereken hoeveel mol 10 gram CH<sub>3</sub>COOH is. 1 mol CH<sub>3</sub>COOH is 60,052 gram, dus:

$$10 \div 60,052 = 1,7 \times 10^{-1} mol$$
- Deze hoeveelheid stof wordt opgelost in 500 mL water, oftewel 0,5 L water. De molariteit wordt dan:

$$1,7\times10^{-1} \div 0,5 = 3,33 \times 10^{-1} M$$
- Nu is de molariteit van de oplossing bekend en kun je verder met dezelfde stappen als hierboven zijn beschreven bij zwakke zuren.