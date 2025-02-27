---
title: "5: Weerstanden in een schakeling"
---
- Elektrische componenten kun je [[In serie en parallel schakelen|in serie en parallel]] schakelen.
- Of componenten in serie staan of parallel zijn geschakeld kan invloed hebben op de spanning, stroomsterkte en de weerstand over de verschillende componenten.
- Meerdere weerstanden in een schakeling kunnen vaak worden samengevoegd tot één weerstand.
	- Dit is belangrijk om te kunnen omdat alle weerstanden bij elkaar bepalen hoe groot de uiteindelijke stroomsterkte is.
- Deze kenmerken en formules staan in BINAS tabel 35D.
- De kenmerken die hieronder staan voor de totale spanning U<sub>tot</sub> en totale stroomsterke I<sub>tot</sub> gelden altijd voor serie- en parallelschakelingen. Dus niet per se alleen voor weerstanden, maar ook bijvoorbeeld voor lampjes!
	- Als lampjes in serie staan gaat bijvoorbeeld dezelfde hoeveelheid stroom door alle lampjes, maar;
	- Als lampjes parallel geschakeld zijn wordt de stroom verdeeld over alle lampjes.

---
# Kenmerken van een serieschakeling

$$ 
U_{tot} = U_{1} + U_{2}+ ...
$$
- De totale spanning is gelijk aan de som van deelspanningen over alle componenten.

$$
I_{tot} = I_{1} = I_{2} = ...
$$
- De stroomsterkte is op elke plaats in een serieschakeling even groot.

$$
R_{tot} = R_{1} + R_{2} + ...
$$
- De totale weerstand is gelijk aan de som van afzonderlijke weerstanden
## Voorbeeld
In het onderstaande plaatje staan drie weerstanden in serie geschakeld. De totale weerstand is:

$$
R_{tot} = 10 + 20 + 35 = 65\ohm
$$
Deze schakeling kun je dus ook tekenen met één weerstand van 65 Ohm.

Met die informatie kun je dan berekenen hoeveel de totale stroom I<sub>tot</sub> is. Als de voeding een spanning heeft van 9,0 V zou het bijvoorbeeld zijn:

$$
I_{tot} = U / R = 9,0 / 65 = 0,138 A
$$

![[weerstanden_in_serie.png]]

---
# Kenmerken van een parallelschakeling

$$
U_{tot}=U_{1} = U_{2} = ...
$$
- De spanning is over alle componenten de parallel geschakeld zijn hetzelfde.
$$
I_{tot}=I_{1} + I_{2} + ...
$$
- De totale stroomsterkte is gelijk aan de som van de deelstromen / takstromen. De grootste stroomsterkte gaat door de kleinste weerstand.
$$
\frac{1}{R_{tot}} = \frac{1}{R_{1}} + \frac{1}{R_{2}} + ...  
$$
- De totale weerstand volgt uit die van de losse weerstanden. De totale weerstand is kleiner dan de kleinste weerstand.
## Voorbeeld
In het onderstaande plaatje staan drie weerstanden parallel geschakeld. De totale weerstand is:

$$
\frac{1}{R_{tot}} = \frac{1}{10} + \frac{1}{20} + \frac{1}{35} = 0,101...\ohm
$$

$$
R_{tot} = 1 / 0,101... = 9,86 \ohm
$$
Deze schakeling kun je dus ook tekenen met één weerstand van 9,86 Ohm.

![[weerstanden_parallel.png]]
Met die informatie kun je dan berekenen hoeveel de totale stroom I<sub>tot</sub> is:

$$
I = U / R = 9,0 / 9,86 = 1,0158 A
$$