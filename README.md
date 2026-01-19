\# CI/CD Demo Application using Azure DevOps



\## 📌 Project Overview

This project demonstrates a complete CI pipeline using Azure DevOps for a simple Python Flask web application.  

Whenever code is pushed to the GitHub repository, the Azure DevOps pipeline is automatically triggered to build, test, and lint the application.



---



\## 🛠️ Tech Stack



\- Python

\- Flask

\- Git \& GitHub

\- Azure DevOps Pipelines

\- YAML-based pipeline



---



\## 📂 Project Structure



cicd-demo-app/

│

├── app.py

├── requirements.txt

├── azure-pipelines.yml

└── README.md



---



\## ⚙️ CI Pipeline Workflow



The pipeline performs the following steps:



1\. Trigger pipeline when code is pushed to `main` branch

2\. Setup Python environment

3\. Install dependencies from `requirements.txt`

4\. Run unit tests (if present)

5\. Run flake8 lint checks

6\. Complete build validation



---



\## 🚀 How Pipeline is Triggered



\- Developer pushes code to GitHub repository

\- Azure DevOps is connected to GitHub

\- Pipeline automatically starts using webhook trigger



---



\## ▶️ Run Application Locally



\### Step 1: Install dependencies

```bash

pip install -r requirements.txt



