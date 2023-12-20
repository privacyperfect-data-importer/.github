# PrivacyPerfect Project Data Importer

GitHub repository for the **PrivacyPerfect Project Data Importer** – a platform with React frontend and NestJS backend for efficient data conversion and importing into your tenant.

## Overview

Simplify data conversion with:

-   **Frontend:** User-friendly interface for file upload, column mapping, and data conversion initiation.
-   **Backend:** Handles processing, mapping, conversion, and ensures accurate and consistent data transformations.

## Getting Started

### For First-Time Users

If this is your first time using PrivacyPerfect Data Importer:

1. Create a new folder on your computer.
2. Open the folder you created.
3. To open a command prompt or terminal window, press `Shift + Right-click` inside the folder.
4. Choose "Open command window here" or "Open PowerShell window here."

Now, you're ready to follow the steps in the readmes:

-   [Backend README](https://github.com/privacyperfect-data-importer/back-end/blob/main/README.md)
-   [Frontend README](https://github.com/privacyperfect-data-importer/front-end/blob/main/README.md)

## Usage

The PrivacyPerfect Project allows you to:

-   Upload data files for import.
-   Map columns in uploaded files to corresponding fields effortlessly.
-   Perform data cleanup and eliminate duplicates.
-   Convert data into the target format.

## Project Overview

The primary objective of this project is to facilitate the conversion of data from one format to another, involving multiple steps to ensure accurate and consistent data transformation.

### Project Detailed Steps

1. **Ingest:**

    - Users can upload Excel files or similar formats for importing into the system.
    - These files typically contain 20-30 data points per row.

2. **General Mapping:**

    - The application offers a user-friendly interface for mapping columns in the file to corresponding fields within the application.
    - The importer automatically identifies column headers, even if they are not in the first row.
    - The application suggests mappings based on column headers and supports multiple languages (English and Dutch).

3. **Separator Management:**

    - Many fields are multichoice and can have multiple values.
    - Users can select separators for these fields, and the system can intelligently suggest appropriate separators.

4. **Data Cleanup:**

    - The importer checks for duplicate or potentially duplicate data entries (e.g., "email" vs. "E-mail").
    - Users are presented with options to merge duplicates, promoting data consistency.

5. **Targeted Mapping:**

    - For text fields like legal grounds, the application provides suggestions for general text based on legal qualifications.
    - The system analyzes text and recommends the nearest matching legal article.

6. **Approval and Import:**
    - After completing the previous steps, the sheet is converted into JSON records.
    - New records are created in the target format.

## Contributing

Contributions to this project are welcome! If you have suggestions for improvements, bug fixes, or additional features, please open an issue on the [repository](https://github.com/Dalikey/PrivacyPerfect-Stage-Project) or submit a pull request.

## Contact

If you have any questions or need further clarification about the project, feel free to [contact the repository owner](mailto:junhao@hotmail.com).

We appreciate your interest and look forward to your contributions!

**Disclaimer:** This project is created for educational and practical purposes and may not cover all production-level scenarios. Use it at your own discretion.

_Last updated: 30 November, 2023_
