# modellsegelflyg.se – arkiv

Arkiv av modellsegelflyg.se (2005–2026), publicerat med GitHub Pages och Jekyll.

## Struktur

| Mapp / fil | Innehåll |
|---|---|
| `_posts/` | Nyheter (en Markdown-fil per nyhet, `ÅÅÅÅ-MM-DD-rubrik.md`) |
| `_artiklar/` | Artiklar |
| `_album/` | Bildalbum (bildlistan ligger i filens huvud) |
| `_sidor/` | Klassidor och undersidor (F3B, F3F, F3J, F5J, F3K, Tävlingsregler) |
| `_data/navigation.yml` | Menyn högst upp |
| `_data/redirects.json` | Gamla adresser (`Articles.aspx?pageid=…`) → nya |
| `filer/` | Bilder och dokument |
| `_layouts/`, `_includes/`, `assets/` | Utseende |

## Redigera

1. Öppna filen på github.com och klicka på pennan.
2. Ändra texten (Markdown) och klicka **Commit changes**.
3. Sajten uppdateras automatiskt efter någon minut.

### Ny nyhet

Skapa en fil i `_posts/` med namnet `2027-05-01-rubrik.md`:

```markdown
---
title: "Rubrik"
date: 2027-05-01 12:00:00 +0200
author: "Förnamn Efternamn"
klasser: ["F3K"]
---
Text här. Bilder: ![](/filer/uppladdat/bild.jpg)
```

`klasser` gör att nyheten även listas på respektive klassida.

## Förhandsgranska lokalt (valfritt)

Kräver Ruby. Kör `bundle install` och sedan `bundle exec jekyll serve`, öppna http://localhost:4000.
