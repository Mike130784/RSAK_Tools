# Installeren zonder ontwikkelomgeving

[Terug naar het overzicht](../README.md)

## Eerst het juiste pakket kiezen

Controleer productnaam, pakketversie en Revitjaargang op de releasepagina. Download het benoemde portable-/installatiepakket, niet het automatisch gegenereerde archief Source code.

Pak de volledige ZIP uit. Start een programma of script niet vanuit de ZIP-weergave van Verkenner. Laat de mappen en bestanden van het pakket bij elkaar staan.

## Revit-gereedschap

Sluit de bedoelde Revitversie voordat je installeert of bijwerkt. Gebruik vervolgens de installer die in de producthandleiding staat. Die registreert de add-in voor de bedoelde jaargang. Start Revit daarna opnieuw en volg de eerste-gebruikstappen van het gereedschap.

Alleen een DLL kopiëren is meestal niet voldoende: het pakket kan ook configuratie, iconen, startscripts of een manifest nodig hebben. Behoud de uitgepakte map wanneer het pakket rechtstreeks vanuit die map wordt geregistreerd.

Een reeds draaiende Revit-sessie kan een DLL vergrendelen. Sluit de sessie in dat geval; ga bestanden niet geforceerd vervangen.

## Zelfstandig Windows-programma

Pak de ZIP uit naar een nieuwe eigen map en start het aangegeven EXE-bestand. Installeer de vereiste runtime alleen als die ontbreekt. Git Desktop vereist naast .NET 8 Desktop Runtime x64 ook Git for Windows met Git Credential Manager voor GitHub-aanmelding.

## Bijwerken en teruggaan

Bewaar de vorige werkende pakketmap totdat de nieuwe versie is getest. Volg de update-/herstelinstructies van de betreffende tool. Een andere programmaversie starten draait wijzigingen aan een Revitmodel of Git-commits niet terug.

Gebruik de meegeleverde verwijderroute waar die aanwezig is. Verwijder geen volledige gedeelde Revit Addins-map en wis geen werkgegevens of herstelbestanden van andere tools.

## Bestand controleren

Bij een gepubliceerde release hoort een SHA-256-bestand. Op Windows kun je het gedownloade pakket controleren met:

```powershell
Get-FileHash -LiteralPath '.\naam-van-het-pakket.zip' -Algorithm SHA256
```

Vergelijk de volledige uitkomst met de waarde bij diezelfde release. Een overeenkomende hash bevestigt de bestandsinhoud; het is geen vervanging voor een digitale handtekening. De signingstatus staat in de release notes.
