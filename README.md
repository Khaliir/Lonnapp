# Min lønnsoversikt – installérbar PWA

## Publiser på GitHub Pages
1. Logg inn på github.com og opprett et nytt **privat eller offentlig** repository. Merk: GitHub Pages på gratis konto krever normalt offentlig repository. Ikke legg inn faktiske lønnsregistreringer i kildekoden.
2. Last opp **filene i denne mappen direkte til roten** i repositoryet (ikke selve ZIP-filen eller en ekstra undermappe).
3. Åpne **Settings → Pages → Build and deployment**, velg **Deploy from a branch**, **main**, **/(root)** og **Save**.
4. Når siden er publisert, åpne adressen GitHub oppgir. Den vil typisk ligne `https://BRUKERNAVN.github.io/REPOSITORY/`.
5. På Android: Åpne adressen i Chrome → meny (⋮) → **Installer app** eller **Legg til på startskjermen**. På PC: Åpne i Chrome/Edge og velg **Installer** fra adresselinjen eller nettlesermenyen.

## Data og sikkerhet
- Appen lagrer registreringer lokalt i nettleseren (localStorage). Ingen konto eller synkronisering.
- Eksporter en JSON-sikkerhetskopi regelmessig, spesielt før du sletter nettleserdata eller bytter mobil.
- Beregningene er anslag og må kontrolleres mot lønnsslipp.
- Koden er klargjort for statisk publisering. Full testing på en faktisk GitHub Pages-adresse er ikke utført.
