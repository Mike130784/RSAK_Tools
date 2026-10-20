# Warmteverlies Importer

**Warmteverliesgegevens beoordelen en gericht op Revit-RuimteMerken toepassen.**

[Alle tools](../../README.md) · [Downloadreleases](https://github.com/Mike130784/RSAK_Tools/releases)

## Wat doet de importer?

De importer leest voorbereide JSON-brongegevens, laat de koppeling met Revit zien en kan waarden op de bedoelde geplaatste RuimteMerken toepassen. De geteste productwerking is door de maker bevestigd; verdere verbetering van het gebruiksgemak staat nog op de wensenlijst.

## Downloadstatus

Een runtimepakket **0.3.0 voor Revit 2024 en 2025** is voorbereid met ongewijzigde DLLʼs uit het bestaande pakket. De maker heeft de productwerking bevestigd, maar weet de precieze eerder geteste jaargang niet meer. De nieuwe verpakking is afzonderlijk op registratie, herstel en data gecontroleerd. Een nieuwe Revit-modeltest per jaargang is NOT RUN. Er is nog geen openbare download.

**De standaardgegevens zijn vervangen door drie volledig fictieve oefenruimtes (DEMO001).** Er worden geen bestaande projectgegevens of modelkoppelingen meegeleverd. Beide product-DLLʼs hebben dit nieuwe voorbeeld via hun eigen parser gevalideerd. Gebruik de voorbeeldwaarden nooit op een echt project; laad eerst je eigen gecontroleerde JSON via de keuze voor andere brongegevens.

## Voorbereiden

Pak de ZIP volledig uit en sluit Revit. Voer INSTALLEREN.ps1 uit met -RevitVersion 2024 of 2025 en -Mode Portable; de volledige opdracht staat in de pakket-README. Laat de uitgepakte map op dezelfde plaats staan. Gebruik je eigen modelkopie en controleer de bron, eenheden en koppelingen voordat je schrijft. Deze versie verwerkt **JSON**; rechtstreeks een PDF of Excel-bestand inlezen hoort niet bij de beschreven functionaliteit.

Controleer bij Vabi-brongegevens de bedoelde warmteverlieswaarde, waaronder `PhiHL,i [W]`, en de betekenis van de gebruikte temperatuurvelden. Kies niet zomaar de grootste waarde uit een bronregel.

## Eerste gebruik

1. Open de juiste Revitjaargang en je testmodel.
2. Laad de juiste voorbereide brongegevens.
3. Controleer de getoonde ruimtes, koppelingen en waarden.
4. Pas eerst een kleine, herkenbare selectie toe.
5. Controleer nummer, temperatuur en vermogen op de bedoelde RuimteMerken.

## Grenzen

Een bronbestand en model moeten inhoudelijk bij elkaar horen. Een succesvolle eerdere koppeling mag niet automatisch worden hergebruikt voor een andere woning of een ander model. Nieuwe nummerings- en matchingmogelijkheden uit de roadmap zijn geen garantie dat die al in de publieke versie zitten.

Gebruik alleen een pakket dat jouw Revitjaar noemt. Zie ook de [installatiehulp](../../docs/INSTALLEREN.md).
