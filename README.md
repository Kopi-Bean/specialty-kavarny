# Obrázky

Názvy souborů musí sedět přesně — malá písmena, bez diakritiky,
včetně přípony. HTML se na ně odkazuje jménem, ne obsahem.

| Soubor | Kde se zobrazí | Rozměr | Formát | Poznámka |
|---|---|---|---|---|
| `logo-kopibean.svg` | hlavička, vlevo | výška 42 px | SVG | Bez PNG varianty; SVG je ostré na všech displejích. Pokud SVG nemáš, dej `logo-kopibean.png` v 240 × 56 px a přepiš příponu v `index.html`. |
| `kava-ritual.webp` | karusel káv | 600 × 600 | WebP | Packshot balení na světlém pozadí. Obrázek se vkládá celý (`contain`), takže okraje neuřízne. |
| `kava-muse.webp` | karusel káv | 600 × 600 | WebP | |
| `kava-nectar.webp` | karusel káv | 600 × 600 | WebP | |
| `kava-exotic.webp` | karusel káv | 600 × 600 | WebP | |
| `kava-calm.webp` | karusel káv | 600 × 600 | WebP | |
| `provoz.webp` | sekce Naše provozy | 1200 × 900 | WebP | Ořízne se na výšku boxu (`cover`) — hlavní motiv drž ve středu. |
| `cupping-berkova.webp` | sekce Než zrno koupíme | 1200 × 750 | WebP | Poměr 16:10. |
| `plantaz-sumatra.webp` | sekce Pražíme od roku 2007 | 1200 × 750 | WebP | Poměr 16:10. |
| `prazicka-imf.webp` | sekce Na čem pražíme | 1000 × 1250 | WebP | Poměr 4:5 (na výšku). Fotka pražičky IMF RM15 na Berkově.
| `baleni-200g.webp` | sekce Prodej hostům | 1000 × 1000 | WebP | Ořízne se (`cover`). |
| `og-velkoobchod.jpg` | náhled při sdílení odkazu | 1200 × 630 | JPG | Musí být JPG nebo PNG — WebP některé sítě nepřečtou. |
| `apple-touch-icon.png` | ikona na ploše iPhonu | 180 × 180 | PNG | |
| `ref-bezcukru.png` | karta reference | výška 88 px | PNG s průhledností | Logo kavárny Bezcukru — nutný souhlas podniku. |
| `ref-vazkafe.png` | karta reference | výška 88 px | PNG s průhledností | Logo kavárny Vážkafé — nutný souhlas podniku. |

Favicon patří do kořene repozitáře, ne sem: `favicon.png` (64 × 64 px).

## Váha

Každý soubor pod 200 kB, ideálně pod 120 kB. WebP v kvalitě 80 je
vizuálně nerozeznatelné od originálu a je řádově menší než JPG.

## Loga referencí

Loga se vkládají celá (`contain`) na světlé pozadí, takže potřebuješ
PNG s průhledným pozadím — jinak bude kolem loga bílý obdélník.
Před nasazením potřebuješ souhlas obou podniků s použitím jejich loga.
