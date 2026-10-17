# Imposter som app på iPhone

Mappen indeholder spillet som en selvstændig web-app. Når den ligger på en webadresse, kan den lægges på hjemmeskærmen og åbner så i fuld skærm med sit eget ikon. Den virker også uden internet, når den har været åbnet én gang.

## Læg den online med GitHub Pages (gratis)

1. Gå til github.com, og log ind.
2. Tryk på **+** øverst til højre og vælg **New repository**. Kald det `imposter`, vælg **Public**, og tryk **Create repository**.
3. Tryk på linket **uploading an existing file**. Træk alle filerne fra `imposter-app.zip` derind (selve filerne, ikke mappen), og tryk **Commit changes**.
4. Gå til **Settings → Pages**. Under **Branch** vælger du `main` og `/ (root)` og trykker **Save**.
5. Efter et minut eller to ligger spillet på `https://glente.github.io/imposter/`.

## Læg den på hjemmeskærmen

1. Åbn adressen i **Safari** på iPhonen.
2. Tryk på **Del-ikonet** og vælg **Føj til hjemmeskærm**.
3. Spillet åbner nu som en app i fuld skærm.

Vennerne kan bruge samme adresse uden login.

## Opdateringer

Når du vil lægge en ny version op, uploader du `index.html` igen i samme repository. Appen henter den nye version næste gang, den åbnes med internet.

## Filer

- `index.html`: Selve spillet.
- `manifest.webmanifest`: Navn, farver og ikoner til appen.
- `sw.js`: Gør at spillet virker offline.
- `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`: Appikoner.
