# umscraper-data
This repository contains the data for [desmondyeoh/umscraper](https://github.com/desmondyeoh/umscraper)

## Dataset
The scraped data are in this repository [TODO: Insert reporsitory link].
- `ptjJabTable.csv` has the full list of (Ptj, Jab) pairs with columns {ptjCode, ptjText, jabCode, jabText}
- `staffTable.csv` has the full staff list with columns {ptjCode, ptjText, jabCode, jabText, name, nameQueryEsc, details...}
  - `img/<ptjCode>/<nameQueryEsc>.jpg` can be used to find the staff's respective image file.
- `img/` has all the staff images files, organised into ptjCode folders.

## Notes
- Every row in `staffTable.csv` may not have the same number of columns. Staffs can have different number of details, and hence different number of staffDetail columns.
