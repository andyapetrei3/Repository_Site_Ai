# 🦅 Endpoint Eagles

Site web de prezentare (one-page) pentru echipa **Endpoint Eagles**, formată din 4 studenți în anul 3 la **FSEGA – Informatică Economică** (Universitatea Babeș-Bolyai, Cluj-Napoca).

Pagina prezintă membrii echipei, studiile și experiența lor, hobby-urile și oferă un formular de contact.

## Conținut

- **Despre noi** – câte un card pentru fiecare membru (poză, prezentare, „Fun fact"), plus două poze cu FSEGA suprapuse și link către site-ul facultății
- **Studii / Experiență** – casete separate pentru fiecare membru
- **Hobby-uri** – casete cu pasiunile fiecăruia
- **Tabel** – recapitulare cu membrii echipei, urmat de o bară de progres
- **Contact** – formular (nume, email, mesaj) și linkuri de social media
- **Footer** – butonul „Nu" care fuge de cursor și butonul „↑ Înapoi sus"

## Tehnologii

- HTML5 semantic
- CSS3 (variabile CSS, Flexbox, Grid, media queries pentru ecrane sub 650px și 480px)
- JavaScript simplu, doar pentru butonul „Nu" și derularea lină la „Înapoi sus"
- Fără framework-uri

## Structura proiectului

```
endpoint-eagles/
├── index.html   # structura paginii (JavaScript-ul este la finalul fișierului)
├── style.css    # stilurile și paleta de culori
└── README.md
```

## Rulare locală

Deschide `index.html` într-un browser. Nu este nevoie de instalare sau de server.

## Publicare pe GitHub Pages

1. Urcă fișierele într-un repository GitHub.
2. Mergi la **Settings → Pages**.
3. La **Source** alege ramura `main` și folderul `/ (root)`.
4. Site-ul va fi disponibil la `https://<utilizator>.github.io/<repository>/`.

## De completat înainte de publicare

- Lista chitarelor din secțiunea „Hobby-uri" (momentan: „de completat").
- Linkul de Instagram pentru Andrei (este identic cu cel al Biancăi).
- Endpoint-ul formularului: în `index.html`, atributul `action` conține un ID de exemplu pentru [Formspree](https://formspree.io). GitHub Pages nu poate procesa formulare, deci este nevoie de un serviciu extern.
- Pozele membrilor sunt încărcate de pe Facebook și LinkedIn, iar linkurile pot expira. Pentru stabilitate, salvează-le într-un folder `img/` și schimbă atributele `src`.

## Echipa

- Mariabela Bradea Pintiuța
- Medeea Cezara Chiuariu
- Apetrei Andrei
- Stein Bianca Maria

© 2026 Endpoint Eagles
