# Kopi Bean — velkoobchod pro kavárny

Statická landing page pro B2B poptávky. Hostováno na GitHub Pages,
doména `coffee.kopibean.cz`.

## Struktura

```
/
├─ index.html          celá stránka (HTML + CSS + JS v jednom souboru)
├─ robots.txt
├─ favicon.svg         ← doplnit
├─ img/
│  ├─ logo-kopibean.svg      ← doplnit (výška ~28 px, SVG)
│  ├─ og-velkoobchod.jpg     ← doplnit (1200 × 630 px, náhled do sociálních sítí)
│  ├─ apple-touch-icon.png   ← doplnit (180 × 180 px)
│  ├─ kava-ritual.webp
│  ├─ kava-muse.webp
│  ├─ kava-nectar.webp
│  ├─ kava-exotic.webp
│  └─ kava-calm.webp
└─ CNAME               vytvoří GitHub sám při nastavení domény
```

## Co je potřeba dodělat

1. **Obrázky** — doplnit soubory v `img/` podle seznamu výše.
2. **Formulář** — endpoint je nastavený, ale míří na *testovací* Apps Script
   pod účtem michaelbedna13@gmail.com. Před spuštěním naostro založit tabulku
   i skript pod firemním účtem a novou `/exec` URL vložit do `index.html`.
3. **Fotky v zástupných blocích** — v sekcích `#provozy`, `#puvod`
   a `#branding` jsou zatím šedé placeholdery.

## Spuštění na GitHub Pages

1. Repozitář → `Settings` → `Pages`
2. *Source*: `Deploy from a branch`, větev `main`, složka `/ (root)`
3. *Custom domain*: `coffee.kopibean.cz`
4. U registrátora domény kopibean.cz přidat DNS záznam:
   `CNAME  coffee  <organizace>.github.io.`
5. Po propsání DNS zaškrtnout **Enforce HTTPS**

## Úprava textů

Stránka je jeden soubor. Text se dá měnit přímo na GitHubu
(tužka v pravém horním rohu souboru → Commit changes) —
změna je online do minuty.
