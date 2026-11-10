# Excel Data Cleaning & Preparation Project

A practical data-cleaning project completed during the Decodelabs Data Analytics Internship using Microsoft Excel 2021. The workbook documents the raw data, cleaned data, validation checks, and cleaning log for a dataset of 1,200 records and 14 columns.

> **Privacy note:** Only publish a workbook or screenshots after checking that they contain no personal, confidential, or otherwise sensitive customer information. If the original data contains sensitive details, do not upload the raw-data worksheet or workbook. Share an anonymised copy instead.

## Project overview

The goal of this project was to prepare the dataset for reliable analysis by addressing missing values, checking for duplicate Order IDs, standardising date and currency formatting, and validating the resulting data. The work is organised in four worksheets:

- **Original Raw Data** — the source worksheet. Keep this private if it contains sensitive information.
- **Cleaned_Data** — the prepared dataset.
- **Data Quality Check** — validation results.
- **Cleaning Log** — a record of cleaning actions.

## Objectives

- Inspect and prepare a 1,200-record, 14-column dataset in Excel.
- Handle missing Coupon Code values consistently.
- Check Order IDs for duplicates.
- Standardise date and currency formatting.
- Validate the cleaned data and document the work.

## Tools

- Microsoft Excel 2021
- GitHub for project documentation and portfolio presentation

## Cleaning process

1. Reviewed the raw data and identified missing Coupon Code entries.
2. Replaced **309** missing Coupon Code entries with **`No Coupon`**.
3. Checked Order IDs for duplicates.
4. Standardised date and currency formatting.
5. Ran data quality checks and recorded the results in the workbook.
6. Documented the cleaning work in the Cleaning Log.

## Data quality results

| Check | Result |
|---|---:|
| Records | 1,200 |
| Columns | 14 |
| Missing Coupon Code entries replaced with `No Coupon` | 309 |
| Duplicate Order IDs | 0 |
| Numeric date entries | 1,200 |
| Remaining blank cells | 0 |

## Repository contents

Add the approved, privacy-checked project files here. A suggested layout is:

```text
.
├── README.md
├── workbook/
│   └── data_cleaning_preparation_anonymized.xlsx
└── screenshots/
    ├── cleaned-data-anonymized.png
    ├── data-quality-checks.png
    └── cleaning-log.png
```

The filenames above are suggestions. Upload only files that are safe to share. Do not include an unredacted raw-data file if it contains sensitive information.

## Excel screenshots to include

Capture screenshots from the anonymised workbook that demonstrate the work without exposing real customer information:

1. **Cleaned data sample:** the `Cleaned_Data` worksheet showing column headers and a few representative rows. Replace or obscure customer-identifying values; retain only what is needed to demonstrate the cleaned structure.
2. **Data quality checks:** the `Data Quality Check` worksheet showing the checks and results: 0 duplicate Order IDs, 1,200 numeric date entries, and 0 remaining blank cells. Ensure no sensitive values are visible.
3. **Cleaning log:** the `Cleaning Log` worksheet showing the documented action for the 309 missing Coupon Code entries replaced with `No Coupon`, plus any other actions actually recorded in the workbook.
4. **Workbook structure (optional):** a screenshot showing the worksheet tabs, with the workbook zoomed or window arranged so that no sensitive cell values are visible.

Do not present a screenshot of the raw-data sheet unless it has been anonymised and reviewed. Avoid screenshots that show customer names, email addresses, phone numbers, addresses, payment details, order-level identifiers, or other sensitive values. Crop the image to the relevant worksheet area and check the final image at full size before uploading.

When the screenshots have been uploaded to `screenshots/`, embed them in this section by adding Markdown image links, for example:

```markdown
![Data quality checks](screenshots/data-quality-checks.png)
```

## How to view the project

1. Download the anonymised Excel workbook from the `workbook/` folder.
2. Open it in Microsoft Excel 2021 or a compatible spreadsheet application.
3. Review `Cleaned_Data`, `Data Quality Check`, and `Cleaning Log`.

## Privacy and responsible sharing

Before publishing, inspect the workbook itself—not just the visible worksheet—to check for sensitive data in hidden rows or columns, hidden worksheets, comments, notes, formulas, named ranges, document properties, and pivot caches or other embedded data. Remove sensitive content from the copy you intend to publish and reopen that copy to verify it. Keep the original workbook private if anonymisation cannot be confirmed.

## Project summary

This project demonstrates a documented Excel data preparation workflow: handling missing categorical values, checking identifier uniqueness, standardising date and currency presentation, and validating the cleaned dataset. All reported results above are based on the project information provided.
