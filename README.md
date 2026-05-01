# PZH Provinciaal Gegevensmodel
🚧 Dit project is in ontwikkeling (work in progress)

## 📌 Over dit project
Het **Provinciaal Gegevensmodel** van Provincie Zuid-Holland (PZH) is een gemeenschappelijke structuur en taal voor provinciale gegevens. Het PGM draagt bij aan een samenhangende, gestandaardiseerde en toekomstbestendige informatievoorziening. 
Het model ondersteunt de provincie in het realiseren van: 
- Eenduidige definities van gegevens en begrippen
- Samenhang tussen domeinen
- Hergebruik van data en modellen
- Betrouwbare informatievoorziening en rapportages

Het model volgt de Metamodel Enterprise Datamodel standaard van PETRA en Metamodel Informatie Modellering (MIM).

### 🎯 Doel
Het PGM heeft als doel om:
- Gegevens op elkaar te laten aansluiten.
- Een gemeenschappelijke basis te bieden voor datamodellering
- Consistente en herbruikbare definities vast te leggen
- De basis te vormen voor datagedreven werken en samenwerking
De ontwikkeling van het PGM wordt gestuurd door een **doelarchitectuur**, waarin afspraken zijn vastgelegd over modellering, standaardisatie en governance.

### 🧱 Architectuur en modellering

Het PGM wordt opgebouwd volgens vaste abstractieniveaus:

Begrippen – definities en betekenis
Bedrijfsobjectmodel (BOM) – domeinobjecten en relaties
Conceptueel informatiemodel (CIM) – gegevensstructuren en attributen

Bij het gebruik van externe modellen en standaarden worden bewuste keuzes gemaakt, zoals:

- adoptie (overnemen)
- adaptatie (aanpassen)
- refereren (koppelen)
- niet toepassen

Deze keuzes worden vastgelegd in het modellenregister PGM (Nog in ontwikkeling).

---

## 📂 Inhoud van de repository
- **Enterprise Architect (.xea) bestanden** met het gegevensmodel.
- Aanvullende documentatie en scripts (*Later toe te voegen)

---

## ⚙️ Installatie & Gebruik
1. Download of clone deze repository.
2. **Enterprise Architect versie 17**: Importeer het `.xea` bestand in een bestaand model
3. **Enterprise Architect Viewer/Lite**: Open het `.qea` bestand ([download de viewer hier](https://sparxsystems.com/bin/ealite_x64.msi))
4. Verken het gegevensmodel en pas het toe in jouw data-omgeving.

---

## 🔍 Voorbeeld
![PGM voorbeeld](/assets/PGM-voorbeeld.png)

---

## 📜 Licentie
Het werk in deze repo valt onder de EUPL-1.2 licentie. Zie [Licentie](/LICENSE.md)

---

## 🔄 Ontwikkeling en governance

Het PGM is een doorlopend ontwikkeltraject. Modellen worden iteratief verbeterd en afgestemd met domeinen.

Belangrijke uitgangspunten:

modellen worden beheerd per domein
generieke objecten worden domeinoverstijgend afgestemd
wijzigingen worden gevalideerd via data governance
keuzes worden expliciet vastgelegd

De governance sluit aan op de bredere data governance binnen de provincie.

---

## 🤝 Samenwerking
Het Provinciaal Gegevensmodel wordt ontwikkeld in samenwerking met:
- Provincie Zuid-Holland
- Interprovinciale organisaties (IPO)
- IBDS

Wil je bijdragen? Houd deze repository in de gaten voor richtlijnen en updates.

---

## 📬 Contact
**Diana Vermeeren**  
Regisseur Datamodelleren  
📧 ac.vermeeren@pzh.nl

---

## 🔗 Meer informatie
- [Metamodel Enterprise Datamodel](https://petra.wikixl.nl/index.php/Metamodel_enterprise_datamodel)
