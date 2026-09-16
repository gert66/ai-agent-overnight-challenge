# Exacte challenge-prompt

Bouw een interactieve 3D-browserapp waarin een virtuele robot of drone van een startpunt naar een doelpunt moet navigeren door een ruimte met obstakels.

De gebruiker moet een 3D-scène kunnen zien met een duidelijk startpunt, een duidelijk doelpunt, meerdere obstakels of volumes, het door het algoritme onderzochte zoekgebied en de uiteindelijke botsingsvrije route.

De applicatie moet meerdere voorbeeldscènes kunnen oplossen, route-lengte en rekentijd tonen en kunnen herkennen wanneer geen geldige route bestaat. Animeer vervolgens hoe de robot of drone langs het gevonden pad beweegt.

Maak de 3D-visualisatie aantrekkelijk en intuïtief. Het moet morgenochtend direct duidelijk zijn wat het probleem is, hoe het algoritme zoekt en welke route uiteindelijk gekozen is.

Werk volledig autonoom. Kies zelf geschikte path-planning algoritmen en visualisatietechnieken, test collision-freedom automatisch, review het resultaat en verbeter het totdat de applicatie betrouwbaar en demo-klaar is.

Werk na de start zonder menselijke interventie. Stel geen niet-essentiële vragen. Als een gekozen aanpak of dependency niet beschikbaar is, kies zelfstandig een veilige alternatieve route en ga door. Gebruik geen sudo/root en wijzig geen bestaande productieomgevingen. Lever volledige broncode, tests, documentatie en een kort eindrapport op.

# Acceptance criteria
- Minimaal drie voorbeeldscènes kunnen verwerken.
- Een botsingsvrije route vinden wanneer die bestaat.
- Een onoplosbare scène correct herkennen.
- Search/exploration en uiteindelijke route visualiseren.
- Route-lengte en rekentijd tonen.
- Robot of drone langs het gevonden pad animeren.