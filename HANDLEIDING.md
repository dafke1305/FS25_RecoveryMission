# Recovery Missions — Handleiding

[Nederlands](HANDLEIDING.md) · [English](USER_GUIDE.md) · [Download / README](README.md)

Voor het pakket **1.0.0.2** uit [deze release](https://github.com/dafke1305/FS25_RecoveryMission/releases/tag/v1.0.0.2). Deze instructies horen bij die ZIP, niet bij een andere build met hetzelfde versienummer.

## Installatie

1. Download **FS25_RecoveryMission.zip** onder Assets van de release. Behoud de bestandsnaam en pak de ZIP niet uit. De automatische GitHub Source code-archieven zijn niet de mod.
2. Plaats de ZIP in de ingestelde FS25-modsmap (op Windows gewoonlijk `Documents\My Games\FarmingSimulator2025\mods`) en schakel de mod in vóór het laden van de savegame. Deze scriptmods zijn voor PC/Mac.
3. Server en alle multiplayerclients moeten **dezelfde ZIP** hebben, niet alleen hetzelfde versienummer. Sluit het spel/stop de server en maak vóór bijwerken een saveback-up.

## Een opdracht kiezen en voorbereiden

Open het gewone **Contracten**-menu voor bergings- en pechhulpopdrachten. Accepteer voor de boerderij die het werk gaat doen en lees voertuig, defect, ophaalplek en bestemming. Neem eigen geschikt bergings- of servicematerieel mee. Deze mod **bevat zelf geen lier**.

Standaardtoetsen in dit pakket:

| Actie | Standaard |
| --- | --- |
| Verborgen berging accepteren/ontdekken | **Numpad Divide** (`/` op het numerieke toetsenbord) |
| Pechhulp-/accu-interactie | De **gewone `/`-toets**, niet Numpad Divide |

F1 toont contextuele acties bij een geschikt doel. Beide acties kunnen onder **Besturing** worden toegewezen.

## Bergen en pechhulp

- Berg bij een sleepopdracht het toegewezen voertuig en breng het naar de opgegeven werkplaats/aflevermarkering. Volg de werkelijke contractbestemming en wacht op de afrondings-/incasseerstatus.
- Parkeer voor pechhulp een herkend servicevoertuig of mobiele werkplaats van **je eigen boerderij binnen 18 meter**. Benader het defecte voertuig en gebruik de gewone `/`-actie.
- Zijn fysieke RMS/ADS-gereedschappen ingeschakeld en beschikbaar, voer dan de aangegeven handeling uit: luchtsleutel voor een band, vetspuit voor een motoropdracht, of de aangegeven uitrusting voor een oude accuopdracht. Alleen `/` indrukken voert geen fysieke gereedschapsreparatie uit.
- Zonder geschikt RMS/ADS-gereedschap gebruiken ondersteunde opdrachten de ingebouwde reparatietijd. Blijf nabij tot de voortgang klaar is. Optioneel vertrekgedrag kan het gerepareerde voertuig eerst laten wegrijden voordat het contract voltooit.

## Een accu vervangen

1. Accepteer de accuvervangingsopdracht. Haal **de nieuwe accu van dat contract** op bij de voertuigwinkel/oranje ophaalmarkering en vervoer die naar het defecte voertuig.
2. Ga te voet **vóór het voertuig staan, binnen één meter van de voorrand**. Leg gedragen voorwerpen neer en kies lege handen. Gebruik de gewone `/` om de oude accu te verwijderen en blijf tijdens het werk op die plek.
3. Leg de oude accu neer. Draag de **nieuwe** contractaccu naar dezelfde plek vooraan en gebruik `/` om die te monteren.
4. Blijf nabij terwijl de montage wordt afgerond en volg de actuele F1-aanwijzing. Volg daarna de afrondings- en beloningsinstructies van de opdracht.

Wielvervangingsopdrachten op geschikte trekkers hebben eigen instructies voor ophalen en monteren van het reservewiel. Volg die aanwijzingen; een gebroken as/wiel in een sleepopdracht is niet automatisch een reservewielopdracht.

## Verborgen opdrachten, beheer en problemen

Verborgen bergingen zijn niet aangekondigde voertuigen die je onderweg ontdekt. Benader het voertuig en gebruik **Verborgen berging accepteren**, waarna je het naar de oranje bestemming brengt. De bonus wordt bij voltooien automatisch betaald. Annuleren kan **10%** van de toegewezen beloning kosten.

Onder **ESC > Spelinstellingen > Recovery Missions - admin** kan een aangemelde beheerder generatie, aantallen, service/verborgen opdrachten en beloningen instellen. Gebruik **Save settings** om meteen op te slaan. **Cancel all TFU jobs** verwijdert de opdrachtvoertuigen en kan bij geaccepteerde opdrachten, ook verborgen bergingen, de betreffende boerderijen 10% boete kosten.

Geen nieuwe opdracht: mogelijk zijn de plekken gevuld of ontbreekt een veilige spawn/geschikte werkplaats. Geen pechhulpactie: controleer de toegewezen boerderij, herkend servicevoertuig, afstand en juiste slash-toets. Controleer bij een accu ook de positie vooraan, lege handen en of je de nieuwe contractaccu draagt in plaats van de oude.

## Hulp vragen

Gebruik [het bug-/supportformulier van deze mod](https://github.com/dafke1305/FS25_RecoveryMission/issues/new/choose). Vermeld release/ZIP, FS25- en mapversie, singleplayer/host/client/dedicated, stappen, tijdstip en het volledige clientbestand `log.txt`; bij een dedicated-serverprobleem ook `server.log` van dezelfde sessie. Voeg relevante screenshots/video toe. De pakketcontrolecode staat in [PUBLICATION.json](PUBLICATION.json). Verwijder wachtwoorden, tokens en privéverbindingsgegevens vóór openbaar plaatsen. Gebruik voor privébewijs alleen een goedgekeurd privékanaal.

Standaardtoetsen zijn aanpasbaar. De actuele F1-hulp en je instellingen onder Besturing zijn leidend.
