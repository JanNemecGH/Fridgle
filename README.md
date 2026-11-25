# Fridgle

Domácí zásoby (spíž, lednice, mrazák), trvanlivost, otevřená balení, recepty, jídelníček a nákupní seznam.
Data se synchronizují přes soukromý GitHub Gist (token a ID gistu se zadávají v aplikaci, v repozitáři nejsou).

## Soubory
- `index.html` – celá aplikace
- `manifest.webmanifest` – název a ikona pro instalaci na plochu
- `icons/` – logo Fridgle

## Zveřejnění přes GitHub Pages
1. Nahraj obsah této složky do kořene repozitáře (ne složku samotnou).
2. Settings → Pages → Source: **Deploy from a branch**, Branch: **main**, složka **/ (root)** → Save.
3. Za 1–2 minuty běží na `https://<uživatel>.github.io/<repozitář>/`.

## Aktualizace
Nahraj nový `index.html` přes Add file → Upload files (přepíše starý) a dej Commit changes. Data zůstanou – jsou v gistu a v prohlížeči.
