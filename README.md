# Auto škola Dule — veb-sajt

Statični sajt (HTML/CSS/JS, bez frejmvorka). Spreman za GitHub Pages.

## Sadržaj
- `index.html` — ceo sajt u jednom fajlu (stilovi, skripte i fontovi ugrađeni).
- `assets/` — fotografije i logo koje sajt učitava.

## Postavljanje na GitHub Pages
1. Napravi novi repozitorijum i dodaj **`index.html`** i ceo folder **`assets/`** u koren.
2. Repo → **Settings → Pages**.
3. **Source:** Deploy from a branch → **main** / **/(root)** → Save.
4. Za par minuta sajt je dostupan na `https://<korisnik>.github.io/<repo>/`.

## Sopstveni domen (opciono)
U Settings → Pages → Custom domain upiši domen (npr. `autoskoladule.rs`) i podesi DNS kod registra.

## Napomene
- Stranice (Početna, Kategorije, Cenovnik, Vozila, Naš tim, O nama, Kontakt) rade kroz internu navigaciju — jedan fajl, bez ponovnog učitavanja.
- Kontakt forma je vizuelno kompletna, ali još ne šalje poruke. Za slanje je poveži sa servisom kao što je Formspree ili sa mejlom škole.
- Fotografije vozila i tima su privremene (generisane) — zameni ih pravim fotografijama u `assets/` folderu, uz iste nazive fajlova.
- Cene su unete prema dostavljenom cenovniku; proveri iznose pre objave.
