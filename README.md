# YouTube Family Plan Policy Chang: Impact Analysis
This project analyzes the gap between social media sentiment and actual user behavior following YouTube's 2025 family plan residency policy update.

<p align="center">
  <img src="./main/images/Excel_Dashboard.png" width="90%" title="Dashboard Overview">
</p>

## 1. Motivation
**The project started with a simple observation:** while online communities were filled with complaints and threats to cancel subscriptions following **YouTube's 2025 family plan residency policy update**, I wanted to verify whether this noise actually translated into business impact. (I was also personally affected—a family member with a different address lost access!)
My initial hypothesis was that strict residency verification would lead to significant churn.
**Spoiler:** The data told a completely different story.

## 2. Data & Methodology
** Data Generation: Created a synthetic business dataset using Python in Google Colab with AI assistance to simulate various user response scenarios (churn, retention, plan switching).
graph TD
    A[Google Colab: Data Generation] --> B[Python: Data Cleaning & Transformation]
    B --> C[Google Drive: Store Cleaned Data]
    C --> D[Excel: Data Import & Verification]
    D --> E[Excel: Pivot Tables & Dashboard Visualization]

    subgraph "Data Processing (Python/Colab)"
    A
    B
    end

    subgraph "Visualization (Excel)"
    D
    E
    end

### Data Pipeline Flow
Step 1: Data Generation (Python/Colab) – Generated synthetic business datasets using Python and AI to simulate user response scenarios
Step 2: Data Cleaning (Python/Pandas) – Performed all data transformations, including timestamp normalization and churn flag creation, entirely in Python to ensure data integrity
Step 3: Storage (Google Drive) – Saved the fully cleaned datasets to Google Drive for secure and organized data management
Step 4: Visualization (Excel) – Imported the pre-cleaned data into Excel to build an interactive dashboard using Pivot Tables and Charts

<p align="center">
  <img src="./main/images/cleaned_data" width="90%" title="Cleaned Data">
</p>





























