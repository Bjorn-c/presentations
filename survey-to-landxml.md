# Survey to LandXML

> Van bestaande gegevens naar een werkbaar formaat.

Note:
Ik probeer kort de stappen te beschrijven die nodig zijn om aan de hand van opgemeten gegevens, een landXML file te maken.

<!--s-->

We vertrekken steeds van **gegevens** in de volgende formaten:

<ol>
    <li>
        <b>DWG</b>
        <span style="color:green; font-size: 175%;">*</span> <!-- .element: class="fragment" data-fragment-index="5" -->
    </li>
    <li>STAR APIC (uitzonderlijk)</li> <!-- .element: class="fragment" data-fragment-index="1" -->
    <li>LANDXML</li> <!-- .element: class="fragment" data-fragment-index="2" -->
    <li>FOTOGRAMMETRIE</li> <!-- .element: class="fragment" data-fragment-index="3" -->
    <li>SCAN of FOTOS</li> <!-- .element: class="fragment" data-fragment-index="4" -->
</ol>

Note:
Het **meest wenselijke formaat** is een complete **DWG** die op een **logische wijze** is opgebouwd, en dit het liefst volgens een standaard structuur.

<!--v-->

> Wij gaan hier verder met het formaat DWG.

<!--s-->

## DWG

Een DWG werd aangeleverd door Lieve, in het formaat DXF

-   Locatie: Brussel-Klein-Eiland
-   Lengte: ongeveer 104m
-   Intersante lagen:
    -   LEFT RAIL LINE
    -   LEFT RAIL POINTS
    -   ODOMETER
    -   RIGHT RAIL LINE
    -   RIGHT RAIL POINTS
    -   TRACK LINE
    -   TRACK POINTS

Note:

-   Een DWG kan aangeleverd worden als DXF, deze vorm is een **open formaat**, en wordt volledig ondersteunt door Autodesk CAD producten.
-   Met de aangeleverde opmeting hebben we voldoende informatie op een basis trace-studie uit te voeren.

<!--v-->

> Wat kunnen we nu afleiden uit deze aangeleverde gegevens?

### Gegevens <!-- .element: class="fragment" data-fragment-index="0" -->
<ol> <!-- .element: class="fragment" data-fragment-index="0" -->
    <li>spoorbreedte</li> <!-- .element: class="fragment" data-fragment-index="0" -->
    <li>opgemeten punten op beide rails, en in de as van het spoor (X;Y;Z)</li> <!-- .element: class="fragment" data-fragment-index="1" -->
    <li>relatie tussen de opgemeten punten (polylijn)</li> <!-- .element: class="fragment" data-fragment-index="2" -->
    <li>verkanting</li> <!-- .element: class="fragment" data-fragment-index="3" -->
    <li>In de laag _comments_ kunnen we speciale punten en opmerkingen terug vinden.</li> <!-- .element: class="fragment" data-fragment-index="4" -->
    <li>Kilometrering</li> <!-- .element: class="fragment" data-fragment-index="5" -->
</ol>

Note:
In een normare opmeting zal er veel meer informatie zitten, katena-palen, hectometer-palen, kilometer-palen, ... maar voor een voorbeeld van een tracestudie is dit niet nodig.

<!--s-->

## Ontwerp
Nu we de bestaande gegevens hebben geanalyseerd, kunnen we starten met het spoorontwerp.

-   Aanmaken novapoint project, en structuur
-   Zoeken van de aansluiting met het bestaande tracé. (<small>Let op het zoeken naar de bestaande verkanting!</small>)
-   Ontwerpen van ons nieuwe spoor.
-   Opmaken van een terrein a.d.h.v. parallellen aan de spooras.
-   Opmaken van een nieuw lengteprofiel.
-   Instellen van de gewenste snelheden en verkanting
-   Berekenen het 3D-model
