# Project Setup Guide

This document provides a step-by-step guide for setting up the PrivacyPerfect Data Importer project. The project consists of a frontend application built with React and an associated backend built with NestJS, which is Dockerized for easier deployment.

## Frontend (Executable React Application):

1. **Extract:**

    - Extract the contents of the provided project zip file.

2. **Run:**
    - Locate and run the executable file named "PrivacyPerfectDataImporter Setup 0.1.2.exe".

## Backend (NestJS with Docker):

1. **Extract Docker Image:**

    - In the folder where the `privacyperfect-data-importer-backend_2.zip` file is located, check if you have WinRAR or 7-Zip installed.

    - If you have WinRAR installed, right-click the file and choose "Extract Here."

    - If you have 7-Zip installed, right-click the file, hover over the 7-Zip option, and choose "Extract Here."

    - If you don't have WinRAR or 7-Zip, download and install either of them from the following links:

        - [WinRAR](https://www.win-rar.com/download.html?&L=0)
        - [7-Zip](https://www.7-zip.org/download.html)

2. **Install Docker:**

    - Ensure that Docker Desktop is installed on your machine before proceeding. If not, download and install it from [Docker's official website](https://www.docker.com/products/docker-desktop/).
    - After installing Docker Desktop, please note that a system restart may be required for the changes to take effect.

3. **Open the Docker Desktop:**

    - Launch Docker Desktop to ensure that Docker is running on your machine.

4. **Load Docker Image and Run Container:**

    - In the folder where the `privacyperfect-data-importer-backend.tar` file is now located, press `Shift + Right-click` on an empty space in the folder.

    - Choose "Open command window here" or "Open PowerShell window here" from the context menu.

    - Run the following commands:

        ```bash
        # Load the Docker image from the tar file
        docker load -i privacyperfect-data-importer-backend.tar

        # Run the Docker container
        docker run -p 3001:3001 -d privacyperfect-data-importer-backend:0.1.2
        ```

    - The server should be running at http://localhost:3001.

    - To view a nicely formatted version of the JSON responses, add the [JSON Formatter Chrome extension](https://chromewebstore.google.com/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?pli=1) to your Chrome browser.

    - To stop the server, go to Docker Desktop > Images > open the image under status "In use" > Stop the server by pressing the square under actions.

## Contact

For any questions or assistance, feel free to [contact the repository owner](mailto:junhao@hotmail.com).
