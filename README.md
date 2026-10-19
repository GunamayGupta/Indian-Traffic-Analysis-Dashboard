# Indian Traffic Analysis Dashboard

A Tableau dashboard exploring road accidents in India and MoRTH driver-response data. The workbook and supporting files were recovered from the Desktop and Downloads folders.

## Project contents

- `workbook/Rd_Dashboard.twb` — Tableau workbook with the dashboard and its original workbook references.
- `workbook/Rd_Dashboard_No_Reference.twb` — alternate workbook copy saved later.
- `exports/Rd_Dashboard.pdf` — PDF export for quick review.
- `data/processed/clean_india_accidents.xlsx` — cleaned accident records used by the workbook.
- `data/processed/driverresponse.xlsx` — state-level driver-response workbook referenced by the Tableau connection.
- `data/processed/model_feature_importance.csv` — model feature importance data referenced by the workbook.
- `data/source/accident_prediction_india.csv` — accident dataset source file found in Downloads.
- `data/source/MoRTH_data.xlsx` and `data/source/morth_driver_response_long.csv` — supporting MoRTH source data.

## Open the dashboard

Open either `.twb` file in Tableau Desktop. The original workbooks point to Excel and CSV files at absolute paths on the source computer. If Tableau reports missing data after cloning this repository, edit the data source connections and select the matching files under `data/processed/` and `data/source/`, then save a local copy of the workbook.

The workbook uses Tableau features and requires Tableau Desktop or a compatible Tableau application to edit. The PDF is available as a static preview.

## Repository notes

The collected files are copies; the originals were left in place. Check source dataset terms and attribution before publishing the data publicly.
