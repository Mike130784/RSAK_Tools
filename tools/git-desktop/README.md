# RSAK Git Desktop

**Git en GitHub in een rustige Nederlandstalige Windows-interface.**

[Alle tools](../../README.md) · [Downloadreleases](https://github.com/Mike130784/RSAK_Tools/releases)

## Wat kun je ermee?

Bekijk je wijzigingen en staged inhoud, lees de commitgeschiedenis, beheer branches en maak commits. Fetch, Pull en Push tonen de lokale en externe status. Guided Mode helpt bij uiteenlopende geschiedenis en conflicten. GitHub-aanmelding, PR's lezen en PR's in de browser openen zijn aanwezig.

## Downloadstatus

De huidige herstelkandidaat is **1.0 RC2**. Browseraanmelding, afmelden, opnieuw aanmelden, PR's laden/openen en Fetch/analyseren zijn door de gebruiker praktisch bevestigd. De tweede-pc- en definitieve releasecontrole staan nog apart. Volgens het beleid van deze catalogus wordt de kandidaat nog niet als definitieve publieke download aangeboden.

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
