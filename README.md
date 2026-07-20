# Ordinacija Osmeh — sajt

Jednostavan, jednostraničan (single-page) sajt za stomatološku ordinaciju. Napravljen u čistom HTML/CSS/JS-u — nema potrebe za instalacijom ili build procesom.

## Kako da postaviš sajt na GitHub

1. Napravi novi repozitorijum na GitHub-u (npr. `ordinacija-osmeh`).
2. U taj repozitorijum ubaci fajl `index.html` iz ovog foldera (drag & drop na GitHub-u ili preko git-a, vidi ispod).
3. Idi na **Settings → Pages** u repozitorijumu.
4. Pod "Branch" izaberi `main` i folder `/ (root)`, pa klikni **Save**.
5. Za par minuta sajt će biti dostupan na adresi:
   `https://tvoje-korisnicko-ime.github.io/ordinacija-osmeh/`

### Ako koristiš git iz terminala

```bash
git init
git add index.html
git commit -m "Prva verzija sajta"
git branch -M main
git remote add origin https://github.com/TVOJE-KORISNICKO-IME/ordinacija-osmeh.git
git push -u origin main
```

Zatim ponovi korake 3–5 iznad da uključiš GitHub Pages.

## Šta treba izmeniti pre objavljivanja

Otvori `index.html` i zameni sledeće:

- Naziv ordinacije, adresu, telefon i email (sekcija "Kontakt" i footer)
- Imena doktora i njihove specijalizacije (sekcija "Naš tim")
- Radno vreme
- Formular trenutno samo prikazuje potvrdu na ekranu — ne šalje pravi email. Za pravo slanje poruka, poveži ga sa servisom kao što je [Formspree](https://formspree.io) ili [EmailJS](https://www.emailjs.com/), ili sa svojim backend-om.

## Struktura

```
index.html   → ceo sajt (HTML, CSS i JS su u jednom fajlu)
README.md    → ovo uputstvo
```
