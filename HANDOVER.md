# Project Setup Guide

This document provides a step-by-step guide for setting up the PrivacyPerfect Data Importer project. The project consists of a frontend application built with React and an associated backend built with NestJS, which is Dockerized for easier deployment.

## Frontend (Executable React Application):

1. **Extract:**

    - Extract the contents of the provided project zip file.

2. **Run:**
    - Locate and run the executable file named "PrivacyPerfectDataImporter Setup 0.1.0.exe".

## Backend (NestJS with Docker):

1. **Extract:**

    - Extract the provided project file to access the backend components.

2. **Navigate to the 'backend' Folder:**

    - Find and navigate to the 'backend' folder containing the 'src' directory. For example: `<your_download_path>\back-end.`

3. **Install Docker:**

    - Ensure that Docker Desktop is installed on your machine before proceeding. If not, download and install it from [Docker's official website](https://www.docker.com/products/docker-desktop/).

4. **Open the Docker Desktop:**

    - Launch Docker Desktop so you can run the commands in step 5.

5. **Build and Run Docker Container:**

    - Open a command prompt or terminal window by pressing Shift + Right-click inside the backend folder. Choose "Open command window here" or "Open PowerShell window here," and run the following commands:

        ```bash
        # Build the Docker image
        docker build -t privacyperfect-data-importer-backend:0.1.0 .

        # Run the Docker container
        docker run -p 3001:3001 -d privacyperfect-data-importer-backend:0.1.0
        ```

## Contact

For any questions or assistance, feel free to [contact the repository owner](mailto:junhao@hotmail.com).
