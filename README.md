# Hauen – mitt smarthus

Mobiltilpasset startside for Easee, My Porsche, Fortum, Sensio Smart, Hombli, Smart Life og Eopt Home.

## Nåværende status

Første versjon er en oversikt med kategorifilter og informasjon om oppkobling. Ingen kontoer er tilkoblet. Ingen kontrollknapper sender kommandoer, og siden viser ingen oppdiktede målinger.

## Vis siden

Åpne index.html i en nettleser, eller aktiver GitHub Pages under Settings → Pages → Deploy from a branch → main → / (root).

## Neste steg

1. Bekreft utstyrsmodeller, sentraler og ønskede funksjoner per tjeneste.
2. Avklar støttede API-er og autorisasjon med leverandørene.
3. Velg server for integrasjonene. Flint 2 må undersøkes før installasjon; en separat server kan bli nødvendig.
4. Koble til én tjeneste om gangen og bekreft ekte status før styringskommandoer aktiveres.

GitHub Pages er statisk hosting og kjører ikke integrasjonsserveren. En side på GitHub Pages har heller ikke automatisk tilgang til det lokale hjemmenettverket. Privat fjernstyring, nettleserens HTTPS-regler og servertilgang må løses ved oppkobling.

Passord, tokens, API-nøkler og personlige enhetsdata skal ikke legges i repoet eller klientkoden. Dette repoet ble registrert som offentlig ved opprettelsen av første versjon.

Bygget av Hansen IT Support
