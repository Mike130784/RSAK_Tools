# RSAK IFC Exporter

**IFC exporteren via een afzonderlijke Revit-worker.**

[Alle tools](../../README.md) · [Downloadreleases](https://github.com/Mike130784/RSAK_Tools/releases)

## Wat doet deze tool?

De exporter bereidt een modelsnapshot voor en gebruikt een afzonderlijke Revit-worker voor de IFC-export. Status, voortgangsfasen, workerlevenscyclus en herstel zijn zichtbaar. De hoofd-Revit-sessie blijft beschikbaar voor het normale werk, met de gebruikelijke beperking dat Revit tijdelijk bezig kan zijn tijdens het voorbereiden van een opdracht.

## Downloadstatus

Voor Revit 2025 is de exact praktisch goedgekeurde build **D10G-C P3 HOME PROVEN, 1 oktober 2026** teruggevonden. De DLL is geverifieerd tegen de vastgelegde SHA-256. Een schoon runtimepakket zonder ontwikkelbron is samengesteld en de pakketbestanden zijn gecontroleerd; er is nog geen publieke download.

Die goedkeuring betreft de vastgelegde Revit 2025-route. Ze is geen algemene vrijgave van nieuwe native-cloudkandidaten of een andere Revitjaargang.

## Eerst installeren

Sluit Revit 2025 en pak het volledige pakket uit. De bewezen pakketlijn gebruikt **INSTALLEER_RSAK_IFC_2025.bat** voor installeren of bijwerken en **VERWIJDER_RSAK_IFC_2025.bat** voor de verwijderroute. Volg altijd de README van de daadwerkelijk gepubliceerde ZIP.

Er mag maar één actieve registratie van deze IFC-tool voor dezelfde jaargang zijn. Zet geen development- en portable-registratie naast elkaar.

## Eerste export

Open een geschikt testmodel en kies de bedoelde exportview. Controleer uitvoermap, exportinstellingen en geselecteerd model voordat je de export start. Volg daarna de workerstatus en controleer de resulterende IFC ook inhoudelijk.

Een bestaande uitvoerfile kan een gecontroleerde blokkade veroorzaken. Kies dan bewust een andere uitvoerlocatie of naam; forceer geen overschrijving via losse bestandsacties.

## Stoppen en herstel

Gebruik de eigen status- en herstelbediening. Een stop is geen bewijs dat al het werk ongedaan is gemaakt. Wis geen queue-, ownership-, lease- of herstelbestanden en beëindig geen willekeurige Revit-processen om een melding te omzeilen.

## Grenzen van de vrijgave

De exacte 2025-build is praktisch getest op de vastgelegde HOME-routes. De nieuwe openbare verpakking krijgt afzonderlijke pakketcontroles; dat is geen extra Revit-praktijktest. Een losse IFC-conversie zonder Revit is geen functie van deze tool.
