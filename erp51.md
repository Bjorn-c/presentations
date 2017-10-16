# ERP 51
Een eerste kennismaking.
<!--s-->

## Onderwerpen

- Geschiedenis 
    - Wie <!-- .element: class="fragment" data-fragment-index="1" -->
    - Wat <!-- .element: class="fragment" data-fragment-index="2" -->
    - Waar <!-- .element: class="fragment" data-fragment-index="3" -->

<!--v-->

- Dossierstudies
    - Beschikbaarheid <!-- .element: class="fragment" data-fragment-index="1" -->
    - Doel <!-- .element: class="fragment" data-fragment-index="2" -->
    - Startscherm <!-- .element: class="fragment" data-fragment-index="3" -->

<!--v-->

- Werkfiches
    - Beschikbaarheid <!-- .element: class="fragment" data-fragment-index="1" -->
    - Doel <!-- .element: class="fragment" data-fragment-index="2" -->
    - Startscherm <!-- .element: class="fragment" data-fragment-index="3" -->

<!--v-->

- Installatie
    - Hoe het nu werkt <!-- .element: class="fragment" data-fragment-index="1" -->
    - Hoe het zou moeten werken <!-- .element: class="fragment" data-fragment-index="2" -->

<!--s-->

## Geschiedenis

De eerste opdracht dateert van 29 september 2009.

![werkfiche](https://goo.gl/s2K9L7)

<!--v-->

### Wie
- Sponsor van het project was Ben Ferdinande. <!-- .element: class="fragment" data-fragment-index="1" -->
- In 2011 werd het opgeleverd, en in gebruik gesteld. <!-- .element: class="fragment" data-fragment-index="2" -->
- On 2013 werd het onderhoud van de applicatie doorgegeven aan Cattoor Bjorn <!-- .element: class="fragment" data-fragment-index="3" -->

<!--v-->

### Wat

- De applicatie is geschreven in C# gebruikmaken van het .NET framework. <!-- .element: class="fragment" data-fragment-index="1" -->
- Voor de ontwikkeling werd er gebruik gemaakt van VS. <!-- .element: class="fragment" data-fragment-index="2" -->
- Een acces database wordt gebruikt voor het opslaan van de gegevens. <!-- .element: class="fragment" data-fragment-index="3" -->
- Dossiers worden opgeslagen in het Word-document formaat. <!-- .element: class="fragment" data-fragment-index="4" -->
- Werkfiches worden niet opgeslagen in een bestandsformaat, ze worden adhv de gegevens in de databank opgebouwd als FlowDocument. <!-- .element: class="fragment" data-fragment-index="5" -->

<!--v-->

### Waar
- In het windows register worden de instellingen bewaard.<!-- .element: class="fragment" data-fragment-index="1" --> `HKEY_CURRENT_USER\Software\ERP51` <!-- .element: class="fragment" data-fragment-index="1" -->
- Alle gecompileerde code, en digitale documenten worden bewaard op een fileserver. <!-- .element: class="fragment" data-fragment-index="2" -->
    - I-AM.3 database + digitale documenten: `\\msnet.railb.be\ifs1\IAM\I-AM.3.Shared\ERP51\` <!-- .element: class="fragment" data-fragment-index="3" -->
    - I-AM.2 database: `\\msnet.railb.be\ifs1\IAM\I-AM.2\I-AM.23\I-AM.231\STUDIES MDB\Studies.mdb` <!-- .element: class="fragment" data-fragment-index="4" -->
- De broncode is beschikbaar op BitBucket, en kan op deze manier eenvoudig worden doorgegeven. <!-- .element: class="fragment" data-fragment-index="5" -->

<!--v-->

#### Overzicht register

![register voorbeeld](https://goo.gl/ozJ6bM)

<!--s-->

## Dossierstudies

![dossierstudies](https://goo.gl/vz192e)

<!--v-->

### Beschikbaarheid
Dossierstudies kunnen alleen maar worden aangemaakt door ingenieurs, en bureauverantwoordelijken.

<!--v-->

### Doel

- Het beheren van dossierstudies binnen de afdeling <!-- .element: class="fragment" data-fragment-index="1" -->
- Het toevoegen van extra informatie mbt de dossierstudie <!-- .element: class="fragment" data-fragment-index="2" -->
- Het toekennen van werkopdrachten uitgevoerd op een dossierstudie <!-- .element: class="fragment" data-fragment-index="3" -->
- Het toevoegen van extra informatie in verband met de werkopdracht <!-- .element: class="fragment" data-fragment-index="4" -->
    - Deze extra informatie wordt opgeslagen als word document. <!-- .element: class="fragment" data-fragment-index="5" -->
- Het opzoeken van dossierstudies. <!-- .element: class="fragment" data-fragment-index="6" -->

<!--v-->

### Startscherm

Het startscherm is het eerste scherm wat de gebruiker ziet, de volgende zaken worden weergegeven:

- relevante dossierstudies (eigenaar, en niet afgesloten) <!-- .element: class="fragment" data-fragment-index="1" -->
- werkopdrachet die aan de gebruiker zijn toegewezen (eigenaar, en niet afgesloten) <!-- .element: class="fragment" data-fragment-index="1" -->
- de actiebalk voor het uitvoeren van bewerkingen op een dossierstudie <!-- .element: class="fragment" data-fragment-index="2" -->
- aan de linkerzijde de zoek-balk <!-- .element: class="fragment" data-fragment-index="3" -->
- en de rechterzijde de documenten-balk <!-- .element: class="fragment" data-fragment-index="4" -->
- onderaan de werkfiches die aan een dossierstudie zijn toegewezen <!-- .element: class="fragment" data-fragment-index="5" -->

<!--v-->

![dossierstudies](https://goo.gl/EXDbDX)

<!--v-->

![details](https://goo.gl/2fEcCQ)

<!--s-->

## Werkfiches (WFT)

![wfts](https://goo.gl/dHUkyG)

<!--v-->

### Beschikbaarheid
Tekenpersoneel, ingenieurs, en bureauverantwoordelijken.

<!--v-->

### Doel

- Het raadplegen van werkopdrachten <!-- .element: class="fragment" data-fragment-index="1" -->
- Het raadplegen van extra informatie gelinked aan de werkopdracht <!-- .element: class="fragment" data-fragment-index="2" -->
- Het toevoegen van informatie ter opvolging van de werkopdracht <!-- .element: class="fragment" data-fragment-index="3" -->
- Het bewaren van een overzicht van de uit te voeren werkopdrachten eigen aan de gebruiker <!-- .element: class="fragment" data-fragment-index="4" -->
- Het opzoeken van werkopdrachten. <!-- .element: class="fragment" data-fragment-index="6" -->

<!--v-->

### Startscherm

Het startscherm is het eerste scherm wat de gebruiker ziet, de volgende zaken worden weergegeven:

- relevante werkfiches (uitvoerder, en niet afgesloten) <!-- .element: class="fragment" data-fragment-index="1" -->
- de actiebalk voor het uitvoeren van bewerkingen op een werkfiche <!-- .element: class="fragment" data-fragment-index="2" -->
- aan de linkerzijde de zoek-balk <!-- .element: class="fragment" data-fragment-index="3" -->
- en de rechterzijde de documenten-balk <!-- .element: class="fragment" data-fragment-index="4" -->

<!--v-->

![wfts](https://goo.gl/zma5Kj)

<!--v-->

![detail-wft](https://goo.gl/6stBnu)


<!--s-->
## Gebruikers
- toegang tot de applicatie wordt gegeven op basis van de ingelogde gebruikersnaam <!-- .element: class="fragment" data-fragment-index="1" -->
- rechten (tekenaar/ing./admin) worden gegeven op basis van de tabel gebruikers in de databank <!-- .element: class="fragment" data-fragment-index="2" -->
- toegang tot de fileserver wordt verkregen dmv een groepsbeleid <!-- .element: class="fragment" data-fragment-index="3" -->
    - momenteel I-AM.2 en I-AM.3 gebruikers hebben toegang <!-- .element: class="fragment" data-fragment-index="3" -->


<!--s-->
## Installatie

### Hoe het nu werkt:

De installatie van de software gebeurt aan de hand van een uitvoerbaar bestand: 
1. zorg voor het kopiëren van nodige bestanden <!-- .element: class="fragment" data-fragment-index="1" -->
2. maakt snelkoppelingen aan <!-- .element: class="fragment" data-fragment-index="1" -->
3. zorgt voor het invullen van de warden in het register <!-- .element: class="fragment" data-fragment-index="1" -->
4. start het update programma <!-- .element: class="fragment" data-fragment-index="2" -->
    - kopiëren van de nieuwste bestanden vanaf de server <!-- .element: class="fragment" data-fragment-index="2" -->
    - het update programma start de applicatie op <!-- .element: class="fragment" data-fragment-index="2" -->

<!--v-->

### Hoe het zou moeten zijn...

De eevoudigste manier om dit te doen is dmv een "click-once" instalatie programma. En niet een zelfgemaakte routine.

<!--s-->

# Vragen?