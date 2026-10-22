# RSAK Git Desktop

**Git en GitHub in een rustige Nederlandstalige Windows-interface.**

[Alle tools](../../README.md) · [Downloadreleases](https://github.com/Mike130784/RSAK_Tools/releases)

## Wat kun je ermee?

Bekijk je wijzigingen en staged inhoud, lees de commitgeschiedenis, beheer branches en maak commits. Fetch, Pull en Push tonen de lokale en externe status. Guided Mode helpt bij uiteenlopende geschiedenis en conflicten. GitHub-aanmelding, PR's lezen en PR's in de browser openen zijn aanwezig.

## Downloadstatus

**V1.0.0 RC2 (1.0.0-rc.2)** is beschikbaar als openbare portable voor Windows x64. De bestaande productbinaries zijn ongewijzigd. Browseraanmelding, afmelden, opnieuw aanmelden, PR's laden/openen en Fetch/analyseren zijn door de gebruiker praktisch bevestigd. Workstation/tweede-pc-validatie blijft NOT RUN; de download is als Release Candidate gemarkeerd.

[Release en instructies](https://github.com/Mike130784/RSAK_Tools/releases/tag/rsak-git-desktop-v1.0.0-rc.2) · [Portable ZIP](https://github.com/Mike130784/RSAK_Tools/releases/download/rsak-git-desktop-v1.0.0-rc.2/RSAK-Git-Desktop-V1.0.0-rc.2-win-x64-portable.zip) · [SHA-256](https://github.com/Mike130784/RSAK_Tools/releases/download/rsak-git-desktop-v1.0.0-rc.2/RSAK-Git-Desktop-V1.0.0-rc.2-win-x64-portable.zip.sha256)

Het pakket is **ongetekend (NotSigned)** en bevat runtimebestanden, README en privacy-informatie. Geen broncode, debug-symbolen of interne checkpoints.

## Vereisten

- Windows x64.
- .NET 8 Desktop Runtime x64.
- Git for Windows; Git Credential Manager voor GitHub-aanmelding.

Een .NET-runtime is iets anders dan een ontwikkel-SDK; om de portable te gebruiken hoef je geen broncode te compileren.

## Beginnen

Pak het volledige pakket uit en start RSAK.GitDesktop.exe. Open een vertrouwde repository en controleer de actieve branch en remote. Werk nieuwe functies eerst op een eigen testbranch door.

Bij GitHub opent Aanmelden je browser via Git Credential Manager. Voltooi daar de toestemming en wacht op de gecontroleerde accountstatus. Git-commitnaam/e-mail en een eventuele SSH-aanmelding blijven aparte instellingen.

## Bewust bewaren en versturen

Stage kiest wat in je commit komt. Commit bewaart die selectie lokaal. Push verstuurt de bereikbare commits naar de gekozen externe branch. Fetch haalt alleen externe informatie op en voegt je werk niet samen.

De app voert geen force push, reset-hard, clean of stille merge uit. Bij divergentie kies je na analyse zelf een bewaakte rebase- of mergeflow. Stoppen is geen automatische rollback.

## Updatecontrole van deze RC2

De ingebouwde updatecontrole gebruikt nog de oorspronkelijke private bronrepository en negeert prereleases. Gebruik voor deze ongewijzigde RC2 de openbare downloadlink hierboven. Er is geen automatische installatie.

## Validatie

LOCAL PASS volgens het bestaande RC2-checkpoint: build zonder fouten/waarschuwingen, 78 gerichte controles, 11 echte WPF/Git-controles en 29 tooltips. De ongewijzigde suite is niet opnieuw uitgevoerd. Voor de openbare verpakking zijn manifesthashes, product-/bestandsversie, x64-architectuur, runtimeconfiguratie en ZIP-integriteit opnieuw gecontroleerd. USER PASS en de nog niet uitgevoerde Workstation-test blijven afzonderlijk vermeld.
