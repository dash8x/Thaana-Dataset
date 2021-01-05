# Thaana Dataset
A dataset of handwritten and computer generated Thaana glyphs

![Samples Preview](img/preview.jpg?raw=true "Example")

## Samples
There are total 25,133 samples in this dataset. Each sample is a 40 x 40 pixel grayscale image of a consonant-vowel pair or a consonant alone with 456 different possibilities for these combinations.
9,120 of the samples were computer generated using 20 different popular Thaana fonts.
16,013 of the samples were handwritten by 35 different individuals from Maldivian students at University of Nottingham Malaysia and residents of Ha. Uligan, Maldives.

## Sample Collection Form Layout

![Form](img/form.jpg?raw=true "Form")

## Extraction Process

![Extraction](img/extraction.jpg?raw=true "Extraction")

## Dataset Versions

![Version Comparisons](img/versions.jpg?raw=true "Versions")

From top to bottom:
- **glyphs_40.csv**: No extra processing applied
- **glyphs_40_thresh.csv**: Thresholded
- **glyphs_40_crop.csv**: Cropped to glyph bounding box
- **glyphs_40_thresh_crop.csv**: Cropped to glyph bounding box and thresholded

## Dataset CSV Format

| Col 0     | Col 1 - 1600          | Col 1601        | Col 1602    |
|-----------|-----------------------|-----------------|-------------|
| Sample ID | Pixel grayscale value | Consonant Index | Vowel Index |

## Consonant Indexes
| Index | Consonant |
|-------|-----------|
| 0     | ހ         |
| 1     | ށ         |
| 2     | ނ         |
| 3     | ރ         |
| 4     | ބ         |
| 5     | ޅ         |
| 6     | ކ         |
| 7     | އ         |
| 8     | ވ         |
| 9     | މ         |
| 10    | ފ         |
| 11    | ދ         |
| 12    | ތ         |
| 13    | ލ         |
| 14    | ގ         |
| 15    | ޏ         |
| 16    | ސ         |
| 17    | ޑ         |
| 18    | ޒ         |
| 19    | ޓ         |
| 20    | ޔ         |
| 21    | ޕ         |
| 22    | ޖ         |
| 23    | ޗ         |
| 24    | ޘ         |
| 25    | ޙ         |
| 26    | ޚ         |
| 27    | ޛ         |
| 28    | ޜ         |
| 29    | ޝ         |
| 30    | ޞ         |
| 31    | ޟ         |
| 32    | ޠ         |
| 33    | ޡ         |
| 34    | ޢ         |
| 35    | ޣ         |
| 36    | ޤ         |
| 37    | ޥ         |

## Vowel Indexes

Index 11 is for when a vowel is absent

| Index | Consonant |
|-------|-----------|
| 0     | ަ         |
| 1     | ާ         |
| 2     | ި         |
| 3     | ީ         |
| 4     | ު         |
| 5     | ޫ         |
| 6     | ެ         |
| 7     | ޭ         |
| 8     | ޮ         |
| 9     | ޯ         |
| 10    | ް         |
| 11    |          |

## Credits

- [Arushad Ahmed (@dash8x)](http://arushad.org) 