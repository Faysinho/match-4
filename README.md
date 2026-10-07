# Match 4

Een responsive one-page webapp voor begeleid, respectvol kennismaken. Gemaakt met HTML, CSS en vanilla JavaScript; er is geen buildstap of package-installatie nodig.

## Starten

Open `index.html` in een recente browser, of serveer de map met een eenvoudige lokale webserver. De vier portretten staan in `assets/` en volgen exact de PDF-volgorde: Vefa, Hussam, Pascal, Sukru.

## Wat werkt

- Responsieve profielkaarten met zachte hover- en tiltinteractie.
- Aanmeldmodal per kandidaat, met verplichte basisvelden en wali/begeleider-contact.
- Toetsenbordvriendelijk sluiten, focusbeheer en veldvalidatie.
- Lokale demo-bevestiging met confetti.
- De demo verzendt of bewaart geen formuliergegevens. Voor echte aanmeldingen zijn een beveiligde backend, privacybeleid en beheerproces nodig.

## Publiceren met GitHub Pages

In `.github/workflows/pages.yml` staat een workflow die de site na iedere push naar `main` publiceert. Maak een GitHub-repository met de naam `match-4`, zet bij **Settings → Pages → Build and deployment → Source** de bron op **GitHub Actions**, en push deze map naar de repository. Na de eerste geslaagde workflow staat de site op `https://<gebruikersnaam>.github.io/match-4/`.

## Profieltransparantie

De omschrijvingen volgen de bijgeleverde opdracht. De kaarten vermelden expliciet bestaande relatie- en werkstatussen, zodat bezoekers belangrijke context vooraf kunnen meewegen.

