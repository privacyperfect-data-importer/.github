# PrivacyPerfect Project Data Importer

Welcome to the GitHub repository for the **PrivacyPerfect Project Data Importer**, a data conversion and importer platform. This project integrates a React frontend and a NestJS backend, providing an efficient solution for transforming and importing data into your tenant.

## Project Overview

The primary goal of this project is to simplify the conversion of data from one format to another so that it can be imported into your tenant. This involves multiple steps to ensure accurate and consistent data transformation.

### Project Components

1. **Frontend:**

    - The React frontend provides a user-friendly interface for interacting with the system.
    - Users can upload data files, map columns, manage separators, and initiate data conversion.

2. **Backend:**

    - The NestJS backend handles data processing, mapping, conversion and importing.
    - It ensures the accuracy and consistency of data transformations.

## Getting Started

To clone and run this repository, follow these steps:

1. **Clone the Repository:**

    ```bash
    # Clone this repository
    git clone https://github.com/Dalikey/PrivacyPerfect-Stage-Project.git
    ```

2. **Start the Backend and Frontend:**

    ```bash
    # Navigate to the backend directory, install dependencies, and start the server
    cd privacyperfect-backend
    npm install
    npm start # or npm run start:dev for watch mode
    ```

    ```bash
    # Navigate to the frontend directory, install dependencies, and start the development server
    cd ../privacyperfect-frontend
    npm install
    npm start
    ```

3. **Run Unit Tests:**

    To ensure the stability of the backend, run the unit tests using the following command:

    ```bash
    npm run test
    ```

4. **Access the Application:**

    - The frontend should be accessible at `http://localhost:3000`.
    - The backend will run on the specified port 3001.

## Production Packaging

To package the application for the local platform:

```bash
npm run package
```

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
