# View Template Manager

**View Templates beheren met zicht op de verschillen.**

[Alle tools](../../README.md) · [Downloadreleases](https://github.com/Mike130784/RSAK_Tools/releases)

## Vier onderdelen

- **Exporteren:** één of meer templates bewaren als `.rsakvt.json`.
- **Importeren:** opgeslagen templates gecontroleerd inlezen.
- **Vergelijken:** verschillen tussen twee templates bekijken.
- **Health Check:** templates naast een gekozen Golden Master leggen.

Vergelijken en Health Check zijn read-only. Importeren kan het model wel wijzigen.

## Downloadstatus

VTM is door de maker als werkend en verder ontwikkeld bevestigd. Een runtimepakket **1.2.1 voor Revit 2022** is voorbereid. De DLL is byte-identiek aan de aangetroffen actieve installatie en de lokale Release-build. Registratie, veilig verwijderen en pakketintegriteit zijn gecontroleerd. De download is beschikbaar via de release hieronder. Een nieuwe Revit-modeltest is tijdens deze verpakking NOT RUN; de precieze eerder geteste jaargang is niet meer bekend. Er is geen uitvoerbaar pakket voor andere jaargangen aangetroffen.

## Eerste gebruik

Open na installatie **RSAK Toolbox → VTM → VTM Manager**. Begin op een testmodel met een export en een vergelijking. Bekijk bij importeren eerst welke gegevens worden aangeboden en controleer het resultaat voordat je verder werkt.

Gebruik voor een Health Check een bewust gekozen Golden Master. Administratieve worksharingwaarden worden niet behandeld als een functioneel templateverschil.

## Revitversie en installatie

Pak het volledige pakket uit op een vaste plek en sluit Revit. Gebruik INSTALLEREN.cmd om te registreren en VERWIJDEREN.cmd om alleen de eigen registratie te verwijderen. Een bestaande VTM-registratie wordt geweigerd en blijft behouden. Gebruik uitsluitend het pakket voor jouw jaargang. De bronlijn kent projecten voor 2022–2026, maar iedere gepubliceerde release moet zijn eigen werkelijk ondersteunde doelen noemen. [Algemene installatiehulp](../../docs/INSTALLEREN.md).

## Grenzen

Een vergelijking of Health Check past niets automatisch aan. Een template uit een andere Revitjaargang kan instellingen bevatten die de doelversie niet kent; beoordeel de meldingen bij importeren.

## Download dit pakket

[Release en instructies](https://github.com/Mike130784/RSAK_Tools/releases/tag/vtm-1.2.1-revit2022)

- [VTM-1.2.1-Revit2022-portable.zip](https://github.com/Mike130784/RSAK_Tools/releases/download/vtm-1.2.1-revit2022/VTM-1.2.1-Revit2022-portable.zip) · [SHA-256](https://github.com/Mike130784/RSAK_Tools/releases/download/vtm-1.2.1-revit2022/VTM-1.2.1-Revit2022-portable.zip.sha256)
