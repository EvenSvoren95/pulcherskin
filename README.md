# Pulchér Skin – GitHub Pages

Komplett statisk nettside med HTML, CSS, JavaScript og lokale bilder. Ingen installasjon, API-nøkler eller bygging er nødvendig.

## Publiser via GitHub

1. Opprett et offentlig repository, for eksempel `pulcher-skin`.
2. Pakk ut ZIP-filen. Last opp **innholdet** slik at `index.html`, `style.css`, `app.js` og `assets/` ligger direkte i roten av repositoryet. Ikke last opp selve ZIP-filen.
3. Lagre filene på `main` (Commit changes).
4. Åpne **Settings → Pages**.
5. Velg **Deploy from a branch**, deretter **main** og **/(root)**. Trykk **Save**.
6. Åpne adressen som vises i Pages når publiseringen er ferdig.

Den inkluderte `.nojekyll`-filen lar GitHub publisere filene uten Jekyll-behandling. Dersom filen er skjult i filutforskeren og ikke følger opplastingen, kan den opprettes som en tom fil i GitHub.

Offisiell veiledning: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Test lokalt

Åpne `index.html` i nettleseren. Alternativt, fra denne mappen:

```bash
python -m http.server 8000
```

Åpne deretter http://localhost:8000.

## Rediger

- `index.html`: struktur, tekst, behandlingsmeny og bookinglenker.
- `style.css`: farger, skrifter og responsivt oppsett.
- `app.js`: karusell, behandlingsbeskrivelser og dialoger.
- `assets/`: lokale bilder.

Alle ressursstier er relative og fungerer også når siden ligger under et repository-navn på GitHub Pages.

Booking går til https://hudpleiesvoren.bestille.no/OnCust2/#!/ og håndteres av Bestille.no. Ingen bestillinger lagres på nettsiden. Priser, kontaktinformasjon og egne salongbilder kan legges til senere. Bildene som følger med er stemningsbilder, ikke dokumentasjon av behandlingsresultater.

Denne eksporten inneholder siste versjon med navyblå logo, SVG-ikoner, fem behandlingskategorier i karusellen og uten negledesigner.
