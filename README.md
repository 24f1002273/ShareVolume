# ShareVolume - SEC Company Shares Outstanding Viewer

## Project Summary

ShareVolume is a single-page web application (SPA) designed to fetch and display the maximum and minimum common stock shares outstanding for a given company directly from the U.S. Securities and Exchange Commission (SEC) API. The application focuses on data for fiscal years greater than 2020. It demonstrates dynamic data fetching, client-side data processing, and real-time UI updates without page reloads.

The application defaults to displaying data for AES Corporation (CIK 0000874761) but can be easily switched to any other publicly traded company by appending its CIK to the URL as a query parameter.

## Setup Instructions

This project consists of several files: `index.html`, `README.md`, `data.json`, `uid.txt`, and `LICENSE`.

1.  **Clone or Download:** Obtain the project files (e.g., clone the GitHub repository or download the ZIP archive).
2.  **File Placement:** Ensure all files (`index.html`, `README.md`, `data.json`, `uid.txt`, `LICENSE`) are in the same directory.
3.  **Local Server (Recommended):** For security reasons and to avoid potential issues with local file access, it's recommended to serve `index.html` via a simple local HTTP server.
    *   **Python:** If you have Python installed, navigate to the project directory in your terminal and run: