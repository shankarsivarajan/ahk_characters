# AHK characters

 [AutoHotKey](https://www.autohotkey.com/) scripts for typing special characters.

- The diacritics follow LaTeX's notation closely: `\"a` → ä, `\'e` → é,  `\\i` → ı, `\ho` → ő, `\^u` → û.

- Capital Greek letters work automatically: `\delta` → δ, `\Delta` → Δ, `\DELTA` → Δ.

- The astronomy and zodiac symbols are prefixed by "astro" and "zod" respectively to remain consistent as well as compatible with the other scripts: `\astrosun` → ☉, `\zodaries` → ♈.

- Miscellaneous symbols include `\infty` → ∞, `\partial` → ∂, and `\times` → ×.  
The Hebrew letters here, used in math, `\aleph` → ℵ, `\beth` → ℶ, type left-to-right.

- Tengwar, mapped to Unicode according to [this](https://freetengwar.sourceforge.net/mapping.html) proposal, may be typed following the same syntax as Greek letters: `\tinco` → , `\ungwe` → ; and tehtar: `\tehta` → , `\tehti` → .  
Tengwar fonts that support this mapping include *[Telcontar](https://freetengwar.sourceforge.net/tengtelc.html),* *[Alcarin](https://github.com/Tosche/Alcarin-Tengwar/),* and *[Artano](https://github.com/shankarsivarajan/TengwarArtano).*

- Hebrew letters: `\aleph` → א, `\beth` → ב, `\gimel` → ג.  
**WARNING:** These type right-to-left. This bug is unlikely to be fixed for historical reasons.

- Unicode Basic Multilingual Plane: `\uni0123` → ģ, `\uni4567` → 䕧, `\uniba98` → 몘. Note that capitalization might produce unexpected results: `\uni0041` → A, `\uni0061` → a, `\Uni0061` → A.
