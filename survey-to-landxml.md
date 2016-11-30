# Survey to LandXML

> Van bestaande gegevens naar een werkbaar formaat.

Note:
Ik probeer kort de stappen te beschrijven die nodig zijn om aan de hand van opgemeten gegevens, een landXML file te maken.

<!--s-->

## Gegevens
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

Een DWG werd aangeleverd door Lieve, in het formaat DXF, op basis hier van heb ik een proefproject opgemaakt.

-   Locatie: Brussel-Klein-Eiland <!-- .element: class="fragment" data-fragment-index="0" -->
-   Lengte: ongeveer 104m <!-- .element: class="fragment" data-fragment-index="1" -->
-   Intersante lagen: <!-- .element: class="fragment" data-fragment-index="2" -->
    -   LEFT RAIL LINE <!-- .element: class="fragment" data-fragment-index="2" -->
    -   LEFT RAIL POINTS <!-- .element: class="fragment" data-fragment-index="2" -->
    -   ODOMETER <!-- .element: class="fragment" data-fragment-index="2" -->
    -   RIGHT RAIL LINE <!-- .element: class="fragment" data-fragment-index="2" -->
    -   RIGHT RAIL POINTS <!-- .element: class="fragment" data-fragment-index="2" -->
    -   TRACK LINE <!-- .element: class="fragment" data-fragment-index="2" -->
    -   TRACK POINTS <!-- .element: class="fragment" data-fragment-index="2" -->

Note:

-   Een DWG kan aangeleverd worden als DXF, deze vorm is een **open formaat**, en wordt volledig ondersteunt door Autodesk CAD producten.
-   Met de aangeleverde opmeting hebben we voldoende informatie om een basis trace-studie uit te voeren.

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

-   Aanmaken novapoint project, en structuur <!-- .element: class="fragment" data-fragment-index="0" -->
-   Zoeken van de aansluiting met het bestaande tracé. <!-- .element: class="fragment" data-fragment-index="1" --> <small>Let op het zoeken naar de bestaande verkanting!</small> <!-- .element: class="fragment" data-fragment-index="1" -->
-   Ontwerpen van ons nieuwe spoor. <!-- .element: class="fragment" data-fragment-index="2" -->
-   Opmaken van een terrein a.d.h.v. parallellen aan de spooras. <!-- .element: class="fragment" data-fragment-index="3" -->
-   Opmaken van een nieuw lengteprofiel. <!-- .element: class="fragment" data-fragment-index="4" -->
-   Instellen van de gewenste snelheden en verkanting <!-- .element: class="fragment" data-fragment-index="5" -->
-   Berekenen het 3D-model <!-- .element: class="fragment" data-fragment-index="6" -->

<!--s-->

## Export
Na het maken van het ontwerp beschikken we over de mogelijkheid om het resultaat te exporteren.

### Formaten <!-- .element: class="fragment" data-fragment-index="0" -->

-   Excel rapport (4 verschillende stijlen beschikbaar) <!-- .element: class="fragment" data-fragment-index="0" -->
-   LANDXML <!-- .element: class="fragment" data-fragment-index="1" -->
-   Leica <!-- .element: class="fragment" data-fragment-index="2" -->
-   Vedgat <!-- .element: class="fragment" data-fragment-index="3" -->
-   Tremble <!-- .element: class="fragment" data-fragment-index="4" -->
-   Novapoint <!-- .element: class="fragment" data-fragment-index="5" -->

Note:
Van alle genoemd formaten worden verschillende types ondersteund, bv een volledig export van een model, gedeeltelijke export (horz./vert./...)

<!--v-->

#### Opslaan van het alignement

Export file... ![Export alignement as](https://goo.gl/HOYAei)

<!--v-->

#### Alignement reports

![Alignement reports](https://goo.gl/nmUNUc)

<!--v-->

#### From Ribbon in base export

![From base export](https://goo.gl/1UHh9a)

<!--v-->
#### Railwaymodel Dialog

![from railway model dialog](https://goo.gl/0Ru8lv)

![examples](https://goo.gl/75ur7b)
Er zijn er nog meer, maar er konden geen extra regels worden toegevoegd.

<!--s-->

### Opmerking

-   Novapoint is NIET perfect, verwacht dit dan ook niet ...
    -   controleren <!-- .element: class="fragment" data-fragment-index="0" -->
    -   raporteren <!-- .element: class="fragment" data-fragment-index="1" -->
-   feedback eindgebruiker <!-- .element: class="fragment" data-fragment-index="2" -->
    -   gewenste formaten <!-- .element: class="fragment" data-fragment-index="3" -->

Note:
Novapoint is een software die steunt op een samenhangsel van oude en nieuwe componenten, veel wat in de software is gestopt, is specifiek voor de gebruiker gemaakt, en dan nooit meer opgevolgt geweest. Dit kan leiden to ongewenste resultaten! (Bijvoorbeeld het opnieuw niet correct werken van een LANDXML export in versie 20.0x)

Er kan nog zéér veel worden gesleuteld aan de manier waarop eeen export wordt gemaakt binnen NovaPoint, het belangrijkste in dit verhaal is weten wat de wens is van de eindgebruiker, en een duidelijke feedback van wat kan worden verbeterd.

Kijk even binnen de eigen software welke formaten er ondrsteund worden, wie weet kan Novapoint het aan om ook hiernaar te exporteren.
