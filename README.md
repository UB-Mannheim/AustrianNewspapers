# NewsEye / READ OCR training dataset from Austrian Newspapers (19th C.)

## About the original data set

Austrian Newspapers is a ground truth data set created with [Transkribus](https://transkribus.eu/)
from Austrian newspapers by the [Library Labs](https://labs.onb.ac.at/) of the
Austrian National Library ([Österreichische Nationalbibliothek](https://www.onb.ac.at/)).
See this publication for details:

Günter Mühlberger, & Günter Hackl. (2019).
NewsEye / READ OCR training dataset from Austrian Newspapers (19th C.) [Data set].
Zenodo. http://doi.org/10.5281/zenodo.3387369

The original data set was published under the [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/).

## Austrian Newspapers 2.0.0 (April 2023)

A revision of the data set was carried out by [Mannheim University Library](https://www.bib.uni-mannheim.de/en/)
from November 2022 to April 2023 using [Transkribus](https://readcoop.eu/transkribus/?sc=Transkribus).
All transcriptions are provided as `PAGE XML` in the `data` folder.
The original separation of the data set into `TrainingSet_ONB_Newseye_GT_M1+` and `ValidationSet_ONB_Newseye_GT_M1+` was kept.

The revision includes: 
1. Layout correction of text regions, text lines and baselines.
2. Region labeling ("header", "headings", "paragraphs", "reference", "footer"). 
3. Correction and enhancement of transcriptions according to [OCR-D Ground Truth Guidelines Level 2](https://ocr-d.de/en/gt-guidelines/trans/level_2_2.html).

### Statistics

Find more information about the revised dataset in our [wiki](https://github.com/UB-Mannheim/AustrianNewspapers/wiki#information-and-statistics).

### Transcription guidelines:
The transcription rules are based on the [OCR-D Ground Truth Guidelines Level 2](https://ocr-d.de/en/gt-guidelines/trans/level_2_2.html) with some exceptions (see below):

1) **Special characters**:
    - Long s (ſ)
    - Fractions (¼ ½ ¾ ⅐ ⅑ ⅒ ⅓ ⅔ ⅕ ⅖ ⅗ ⅘ ⅙ ⅚ ⅛ ⅜ ⅝ ⅞)
    - Fraction slash (⁄) (U+2044), if
        - can't be transcribed by a unicode fraction representation
        - numerator and denominator are not on the same baseline height
    - R rotunda (ꝛ)
    - Dagger (†)
    - Black Right Pointing Index (☛)
    - Black Left Pointing Index (☚)
    - Superscript Numbers 0-9 (⁰ ¹ ² ³ ⁴ ⁵ ⁶ ⁷ ⁸ ⁹)
    - Subscript Numbers 0-9 (₀ ₁ ₂ ₃ ₄ ₅ ₆ ₇ ₈ ₉)
    - White square (□)
    - White medium square (◻)
    - Black square (■)
    - White up-pointing triangle (△)
    - Black up-pointing triangle (▲)
    - Bullet (•)
    - Black circle (●)
    - Black large circle (⬤)
    - Heavy four balloon-spoked asterisk (✤)

2) **Additional characters** transcribed true to original (contrary to OCR-D Level 2):
    - Double oblique hyphen (⸗)
    - Em dash (—) instead of En dash (–)

### Funding
This revision is part of the [OCR-D project](https://ocr-d.de/en/) and predominantly funded by the [German Research Foundation (DFG)](https://www.dfg.de/foerderung/info_wissenschaft/2020/info_wissenschaft_20_15/index.html).

# Links
- [[Original data set] NewsEye / READ OCR training dataset from Austrian Newspapers (19th C.)](http://doi.org/10.5281/zenodo.3387369) 
- [Library Labs @ Austrian Nation Library](https://labs.onb.ac.at/)
- [University Library Mannheim](https://www.bib.uni-mannheim.de/en/)
