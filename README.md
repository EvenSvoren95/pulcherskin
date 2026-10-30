# Pulchér Skin – nettside og separat bookingdemo

Nettsiden ligger i roten. Bookingdemoen ligger i booking-demo/ og er et separat prosjekt.
Ingen installasjon eller bygging er nødvendig. Ren HTML, CSS og JavaScript.

## Publiser nettsiden på GitHub Pages
1. Pakk ut ZIP-filen.
2. Opprett et repository på GitHub.
3. Last opp innholdet, slik at index.html ligger i roten av repositoryet.
4. Åpne Settings > Pages. Velg Deploy from a branch, main og / (root). Lagre.
5. Åpne adressen GitHub viser når publiseringen er ferdig.

## Separat bookingdemo
Opprett et annet repository og last opp innholdet INNE I booking-demo/ i roten der.
Aktiver Pages på samme måte. Du kan utelate booking-demo/ fra nettsidens repository.
Demoen lagrer kun testbestillinger i nettleseren. Den har ingen felles database,
innlogging eller e-post/SMS og skal ikke brukes til reelle kundebestillinger.

## Lokal testing
Kjør python3 -m http.server 8000 fra mappen, og åpne http://localhost:8000.

## Redigering
- index.html: innhold, priser, kontaktinformasjon og bookinglenker.
- style.css: farger, typografi og mobiltilpasning.
- app.js: karusell og behandlingsdialoger.
- assets/: KI-genererte behandlingsillustrasjoner, ikke bilder fra salongen.

Nettsiden lenker fortsatt til Hano. Prisene er et utvalg og oppdateres manuelt.
Komplett kategorisert prisliste og automatisk synkronisering er ikke implementert.
Ingen hostingnøkler, Git-historikk eller interne konfigurasjonsfiler er inkludert.
