# Udari politika! - Volilna igra 2026

Satirična browser igra v stilu "Whac-A-Mole" s slovenskimi politiki.

## Kako igrati

1. Klikni **"Začni igro"**
2. Ko se politik prikaže, ga **klikni/tapni** čim hitreje
3. Naberi čim več točk v 60 sekundah
4. **Deli svoj rezultat** s prijatelji!

## Točkovanje

| Akcija | Točke |
|--------|-------|
| Zadetek | 100 |
| Hiter zadetek (<0.5s) | 150 |
| Combo (3+ zaporedni zadetki) | 1.5x množitelj |

## Lokalni zagon

Igro je potrebno servirati preko HTTP strežnika (ne odpirati direktno kot datoteko).

```bash
# Python 3
python3 -m http.server 8000

# Node.js (če imaš npx)
npx serve .

# PHP
php -S localhost:8000
```

Nato odpri [http://localhost:8000](http://localhost:8000) v brskalniku.

## Tehnologije

- **Three.js** - 3D grafika
- **Vanilla JavaScript** - Logika igre
- **Web Share API** - Deljenje rezultatov

## Struktura projekta

```
volitve-igra/
├── index.html              # Glavna datoteka igre
├── assets/
│   └── politicians/        # Slike politikov (PNG s prosojnostjo)
├── docs/                   # Dokumentacija
└── README.md
```

## GitHub Pages

Igra je pripravljena za hosting na GitHub Pages:

1. Pojdi v **Settings > Pages**
2. Izberi **Source: Deploy from a branch**
3. Izberi **Branch: main** in **/ (root)**
4. Klikni **Save**

Igra bo dostopna na: `https://<username>.github.io/<repo-name>/`

## Pravno obvestilo

Satirična igra za politični komentar. Vsi liki so karikirani za humoristične namene.

## Licenca

MIT License
