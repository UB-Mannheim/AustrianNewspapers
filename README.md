# NewsEye / READ OCR training dataset from Austrian Newspapers (19th C.)

## About the original data set

Austrian Newspapers is a ground truth data set created with [Transkribus](https://transkribus.eu/)
from Austrian newspapers by the [Library Labs](https://labs.onb.ac.at/) of the
Austrian National Library ([Österreichische Nationalbibliothek](https://www.onb.ac.at/)).
See this publication for details:

Günter Mühlberger, & Günter Hackl. (2019).
NewsEye / READ OCR training dataset from Austrian Newspapers (19th C.) [Data set].
Zenodo. http://doi.org/10.5281/zenodo.3387369

The original data set was published under the Creative Commons Attribution 4.0 International license.

## ÖNB Fraktur data for model training

This repository started with the original data set and now tries to enhance it
in several aspects to make it more suitable for model training of OCR software.

The original transcription uses level 1 according to the
[OCR-D transcription guidelines](https://ocr-d.github.io/gt//trans_documentation/transkription.html) (German).

This is sufficient for many applications, but there is also a high need to
have more detailed transcriptions. Therefore the transcriptions were enhanced
with the long "s" and special unicodes for fractions,
and similar enhancements might be added in the future.
It is still possible to get level 1 transcriptions by simple search and replace operations.

The initial enhancements were added by [UB Mannheim](https://www.bib.uni-mannheim.de/) who
also fixed some transcription errors in the data.

## Overview of content

Unpacked original data (PAGE XML, TIFF) from ÖNB with some transcription texts enhanced and fixed

- [TrainingSet_ONB_Newseye_GT_M1+](https://github.com/UB-Mannheim/AustrianNewspapers/tree/master/TrainingSet_ONB_Newseye_GT_M1%2B)
- [ValidationSet_ONB_Newseye_GT_M1+](https://github.com/UB-Mannheim/AustrianNewspapers/tree/master/ValidationSet_ONB_Newseye_GT_M1%2B)

Extracted line pairs (image and ground truth text)

- [gt](https://github.com/UB-Mannheim/AustrianNewspapers/tree/master/gt)

Note: Many updates in _gt_ still have to be transferred to the PAGE XML files.
