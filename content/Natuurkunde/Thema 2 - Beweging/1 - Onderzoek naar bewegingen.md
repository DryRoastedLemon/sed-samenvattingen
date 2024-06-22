---
title: "1: Onderzoek naar bewegingen"
---
# (Plaats, tijd)-diagrammen / (x,t)-diagrammen
Beweging kan worden weergegeven in een (plaats, tijd)-diagram / (x,t)-diagram, waarbij de plaats op de y-as staat en de tijd op de x-as.

![[xt_diagram.png]]

1. **Horizontale lijn:** voorwerp staat stil
2. **Recht stijgende lijn:** constante snelheid voortbewegen. Elke seconde wordt er een even grote afstand afgelegd. Hoe steiler de grafiek, hoe groter de snelheid.
3. **Steeds vlakker wordende lijn:** een vertraging. De snelheid neemt af.
4. **Steeds steiler wordende lijn:** een versnelling. De snelheid neem toe.
# Verplaatsing

$$
\Delta x = x_{eind} - x_{begin}
$$
$\Delta x$: Verplaatsing (**afgelegde weg**) in m
$x_{eind}$: De plaats aan het eind in m
$x_{begin}$: De plaats aan het begin in m 

In plaats van $\Delta x$ wordt ook vaker het symbool $s$ gebruikt voor verplaatsing!

**Voorbeeld**
Jantje staat 10 m van een paal af, en beweegt daarna tot een punt waar hij 15 meter van de paal af staat. $x_{begin}$ is 10, $x_{eind}$ is 15, dus $\Delta x$ is $15 - 10 = 5 m$.

---
# Verschillende manieren om beweging te bestuderen
Het boek bespreekt meerdere methoen om beweging te bestuderen.
## Videometen
- Met videometen kan beweging bestudeerd worden aan de hand van een filmpje.
- In iedere frame van de video markeer je hetzelfde punt van een bewegend voorwerp (zoals het midden van een bal) en vergelijkt dat met een vast punt in het beeld. Met die informatie kun je vervolgens de verplaatsing $s$ van een object in beeld krijgen.
- Om de daadwerkelijke verplaatsing te kunnen verkrijgen moet je de **schaal** weten. In het onderstaande voorbeeld van de bus is bijvoorbeeld bekend dat de bus $10,0\,m$ lang is.
- Van een filmpje is bekend hoeveel beelden/frames het per seconde maakt, en zodoende weet je hoeveel tijd er is verstreken tussen elke frame.
	- **Voorbeeld:** Als een videometing een filmpje met 10 beelden per seconden gebruikt, weet je dat er tussen elk beeld $1 : 10 = 0,1 s$ zit.

![[busje.png]]![[busjediagram.png]]

## Stroboscopische foto
![[strobo.png]]
- Een **stroboscopische foto** is een foto gemaakt met een **stroboscoop**. In zo'n foto zijn meerdere beelden in één beeld zijn weergegeven. Zo kun je de beweging van een object zien in één beeld.
- Op dezelfde manier als bij videometen kun je de verplaatsing van een object bepalen. Ook hier wordt dan gegeven (of kun je berekenen) hoeveel beelden per seconde zijn gemaakt.
	- **Voorbeeld:** In dit voorbeeld staan 30 plaatjes van de bal. Als dit in twee seconden is opgenomen, geldt dat dit filmpje met $30 : 2 = 15$ beelden per seconde is opgenomen, en er dus tussen elk beeld $1 : 15 = 0,067$ seconden zit.

## Ultrasone plaatsensor
- Ultrasone plaatsensoren maken gebruik van echolocatie en een computer om de verplaatsing van een object te meten.
- Zo'n plaatsensor zendt pulsen (korte tonen) uit die worden weerkaatst door het object. De computer berekent op basis van hoe lang het duurde om de echo te ontvangen hoe ver het object is. Op basis daarvan kan een (x,t)-diagram gemaakt worden.

**Voorbeeld**
Een pulssensor zendt een puls uit en ontvangt de echo 2,5 ms later. Hoe groot is de afstand tussen de sensor en het object?

De snelheid van geluid in lucht is $0,343 \cdot 10^{3}$ m/s (BINAS 15A). De echo komt terug bij de sensor na 2,5 ms. Dat is heen én terug, dus om de afstand te bepalen nemen we de helft van die tijd: 1,25 ms. Daaruit volgt dat $0,343 \cdot 10^{3} \cdot 1,25 \cdot 10^{-3} = 0,428$ m.

## Lichtpoortje met timer
- Een lichtpoortje bestaat uit een lichtsensor en een lichtbron die op de lichtsensor schijnt. Als er iets tussen de twee komt wordt het licht onderbroken en geeft de sensor een signaaltje af.
- In het voorbeeld uit het boek kan met behulp van een timer daarmee de snelheid van een karretje op een helling worden bepaald. De sensor zet dan de timer uit.
- Als het karretje in 0,065 s een afstand van 0,1 m aflegt is de snelheid $0,1 : 0,065 = 1,54$ m/s.

![[karretje.png]]