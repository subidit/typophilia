## Fonts with variation commands

- Fira Sans
- Inter
- Nunito
- Overlock
- Raleway
- Roboto
- SourceSerifPro & SourceSansPro
- Montserrat `{\montserratalt ...}`
- Merriweather and MerriweatherSans


## Commands
- To select oldstyle or lining figures locally, use `\oldstylenums{...}` or `\liningnums{...}`, respectively.
- Options `scaled=<number>` or `scale=<number>` may be used to scale the fonts.


## Figure versions
- Lining figures, designed to match the uppercase letters in size and color
- Old style figures (also known as text figures), designed to match lowercase letters

### Two figure widths are also available:
• Tabular figures, which each have the same width
• Proportional figures, which vary in width according to their shape

## Superfamily

+ Alegreya - Alegreya, AlegreyaSans
+ Bera - Serif bera, berasans, beramono
+ DejaVu Serif, Sans, Mono, Condensed
+ Droid Serif, Sans, Mono
+ IBM Plex Serif, Sans and Mono
+ Inria Sans, Serif in Light, Regular 
+ KP Sans-Serif, Serif, Mono - sc
+ Libertinus Serif bfsc, bfit, Libertinus Sans, Mono
+ Merriweather, Merriweather Sans Light, bfit
+ Montserrat Regular, Montserrat Alternates Extra Light bfsl
+ Noto Serif, Sans, Mono sc
+ Paratype Serif Caption, Paratype Sans Narrow sl only
+ Quattrocento, Quattrocento Sans bf only
+ Roboto, Slab, Light, Condensed
+ Source Serif Pro, Source Sans Pro, Source Code Pro


## Good

* Coelacanth (Centaur) Regular, Light, Extra Light no sc not great
* ETbb
* Cormorant Garamond - meh
* Gentium
* Ibarra Real Nova - bfit, bfsc
* Romande ADF (bit goofy)
* TEX Gyre Schola
* Alegreya
* Baskervald ADF baskervald - bfit, ebsl
* Charter
* Clara
* Cochineal is a fork of the crimson font. bfit
* Crimson Pro Regular, Medium, Light, Extra Light
* Atkinson Hyperlegible - it, bfit
* Berenis ADF berenis - (Didot) sc, bfit
* Biolinum - sc, bfsc, bfit 2021-03-13
* Cabin, Cabin Condensed - bfsl
* Caladea - bfit (tall x height)
* Chivo Light, Chivo Regular - bf
* Clara - it, sc
* ClearSans, clearlight
* Eczar Regular, Medium - no it
* Erewhon - it, sl, sc, bfsc, scit 
* GFS Artemisia - it, sc
* GFS Bodoni - it, sc, bf 2020-01-06
* Inter
* Josefin Sans Geometric
* Libre Baskerville - bf, it (2020-07)
* Lato - eb, l, ul
* Linux Libertine - sc, bfsc, bfit
* Literaturnaya - it, sl, sc, bfsc, bfit
* Magra - bf only. Humanist sans 2021-01-11
* Overlock - bf, it, sc
* Raleway - bfit
* Rosario - bf, it omnibus-type.com
* ScholaX - it,sc, bf
* Shobhika - bf only, Devanāgarī, Cyrillic.
* Spectral - el, l, m, sb, eb, sc, scit
* Sticks Too - A reworking of Stix 2. it, sc, bf.
* Universalis ADF Standard - Futura univrscondensed



### Display fonts
1. Alfa Slab One
2. Cinzel Trajan
3. Cyklop
4. Fetamont - ffmwfamily, ffmfamily (Logo/Metafont)
5. Lobster Two
6. Oswald
7. Playfair Display - black, sc, bfit, blackit
8. Trajan


## Similar fonts

### HELVETICA
1. tgheros TEX Gyre Heros URW Nimbus Sans L qhv
2. helvet phv
3. uarial URW A030
4. Archivo
5. arimo Arimo

### ITC Avant Garde Gothic
1. tgadventor TEX Gyre Adventor URW Gothic L qag
2. QT Avanti

### OPTIMA
1. Biolinum 
2. URW Classico
3. Epigrafica
4. Libertinus Sans
5. Marcellus
6. QT Optimum fontspec

### TIMES
1. tgtermes TEX Gyre Termes	URW Nimbus Roman No9 L qtm
2. mathptmx Times ptm
3. Linux Libertine
4. TX Fonts
5. New TX (enhanced versions of the TX Fonts)
6. Stix
7. Tinos
8. XITS based on [STIX fonts]
9. Romande ADF (substitute for Times, Tiffany or Caslon.)

### PALATINO
1. tgpagella TEX Gyre Pagella URW Palladio L qpl
2. palatino Palatino ppl
3. Domitian
4. KP Serif
5. New PX
6. PX Fonts
7. QT Palatine

### BOOKMAN
1. tgbonum TEX Gyre Bonum URW Bookman L qbk
2. bookman Bookman pbk
3. Kerkis

### Century Schoolbook
1. tgschola TEX Gyre Schola	URW Century Schoolbook L qcs
2. ScholaX
3. QT School Century

### CHARTER
1. charter Charter bch
2. Charter BT
3. Charis SIL
4. Bera Serif
5. Bitter
6. DejaVu Serif 

### ADOBE UTOPIA (Baskerville and Walbaum as influences)
1. utopia Utopia put
2. fourier Fourier put
3. Heuristica
4. Erewhon
5. Venturis ADF No2

### Bitstream Vera Sans
1. Bera and Bera Sans
2. Arev

### BEMBO
1. ETbb
2. fbb

## Notes
* TeX Gyre enhanced version of URW 
* QT needs fontspec
* Libre is large
* Bookman: Consider to use the Kerkis font, which is an extension of Bookman with math support and support for greek characters or the enhanced version available with the TEX Gyre Bonum font.
* The DejaVu fonts are derived from the Vera fonts and contain more characters and styles. Other implementations of the Vera fonts are the Bera Fonts.
* Eczar The fonts support over 45+3 languages in Latin and Devanagari scripts in 5 weights. However, there are no italics available.
* Erewhon is a font package based largely on Andrey V. Panov’s Heuristica, but with so many changes that it is no longer strictly compatible with that package, and is offered instead as an enhanced alternative.
* Andrey V. Panov’s Heuristica font family extends the Utopia font family, adding many accented glyphs, Cyrillic glyphs, ligatures, superior and oldstyle fixed-width figures in all styles, and Small Caps in Regular style only.
* This package supports only XELATEX or LuaLateX, for pdfLATEX use the package plex-mono, plex-sans and/or plex-serif. Serif, Sans and Mono families are available in eight weights: Regular, Light, ExtraLight, Thin, Bold, Text, Medium and SemiBold (with corresponding italics).
* Linux Libertine is a digital typeface created by the Libertine Open Fonts Project, which aims to create free and open alternatives to proprietary typefaces such as Times New Roman. A side project of Linux Libertine is Linux Biolinum: it is a sans serif font based on Optima. 
* The Libertinus font family, including: Libertinus Serif, a serif font based on Linux Libertine. Libertinus Sans, a sans serif font based on Linux Biolinum and Optima.
* New PX The text font provided is a Palladio clone. The fonts are enhanced versions of the PX Fonts. Other implementations of the Palladio font is mathpazo and TEX Gyre Pagella.
* Archivo and Chivo (‘goat’ in Spanish) https://www.omnibus-type.com/fonts/ 
* Theano Didot, Theano Modern, Theano OldStyle
* The Venturis Collection consists of fonts made by Arkandis Digital Foundry (ADF), venturis, venturis2 and venturisold, Venturis ADF Sans
* The Domitian fonts are a free and open-source OpenType font family, based on the Palatino design by Hermann Zapf (1918-2015), as implemented in Palladio, the version distributed as part of URW's free Core 35 PostScript fonts (2.0). Domitian is meant as a drop-in replacement for Adobe's version of Palatino. It extends Palladio with small capitals, old-style figures and scientific inferiors. The metrics have been adjusted to more closely match Adobe Palatino, and hinting has been improved.
* PDF [A story of kpfonts](https://www.tug.org/TUGboat/tb31-3/tb99caignaert.pdf) frenchstyle option
* https://scripts.sil.org/default
