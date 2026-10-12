# EUAA to EPS Paste-Table Converter

Version 1.1.0 includes M1-M6 and the fixes requested on 12 October 2026. Open `index.html` through a local/static web server, select the table, paste NASMS rows without headings, and convert.

## Included fixes
- Philippines -> PH
- M4 converter
- Awaiting Lodging -> AW_LOD
- APR-bound subsequent application -> SUBSEQ_APRMS
- M5 NASMS columns and corrected column order
- THP/THP PROCEDURE -> REG
- DATA_STATUS = EU in M1, M3, M4 and M5
- Warning when a minor status is paired with age 18+

No case data is uploaded. Processing occurs in the browser.

## Dictionary alignment
All generated categorical values use the exact EPS codes in `EPS Dictionaries.xlsx`. Dataset-specific dictionaries are applied where M1-M3 and M4-M6 use different code lists.
