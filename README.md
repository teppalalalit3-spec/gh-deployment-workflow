# GitHub Deployment Workflow

This project demonstrates Continuous Integration and Continuous Deployment (CI/CD) using **GitHub Actions** and **GitHub Pages**.

## Project Goal
To automatically deploy static web content to GitHub Pages whenever changes are pushed to the main repository. 

## Features
* **Automated Deployment**: Uses GitHub Actions workflows to handle build and hosting steps securely.
* **Path Filtering**: The workflow is optimized to trigger **only** when changes are made specifically to the `index.html` file, saving execution minutes.

## How to Test
1. Make a small text change inside the `index.html` file.
2. Commit and push the change to your `main` branch.
3. Check the **Actions** tab in your GitHub repository to watch the deployment run.
