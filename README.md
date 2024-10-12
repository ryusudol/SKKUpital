# SKKUpital 🏥

This project is a 'Diagnosis Results Sharing System' designed to improve healthcare accessibility and continuity for patients who seek services at new hospitals. It addresses issues like distrust of unfamiliar facilities, inconvenience, and the absence of continuous medical records.

To address this issue, the system offers three primary features:
1. Doctors: Input and Access Diagnosis Results 📝 - Allows physicians to enter and retrieve patient diagnosis information seamlessly.
2. Patients: View Personal Diagnosis History 📋 - Enables patients to easily access their past medical records.
3. AI-Generated Health Insights: Analyze Diagnosis Data 🤖✨ - Utilizes artificial intelligence to provide valuable health insights based on historical data.

![Patient's Homepage](./UI/Homepage%20-%20Patient%20Logged%20in.jpg)

## Introduction 🚀

People often need to seek medical services at alternative hospitals for congenital or situational reasons. In these situations, patients may hesitate to visit new healthcare facilities due to distrust of unfamiliar institutions, inconvenience, and the lack of continuity in care caused by the absence of previous medical records. To overcome these challenges and improve healthcare accessibility, we have developed this project. The initiative aims to enhance the convenience of healthcare utilization for patients and ensure continuity of medical services by enabling swift and efficient access to medical records from their existing hospitals at new healthcare providers.

By enabling efficient sharing of medical information and leveraging AI for health insights, the system enhances the convenience and continuity of medical services, ultimately increasing patient satisfaction and improving healthcare outcomes. 😊

## Features 🔍

### 1. Doctors: Input and Access Diagnosis Results 🩺
* Functionality: Doctors can enter new diagnosis results for patients and retrieve existing diagnosis records from the system.
* Benefit: Streamlines the process of updating and accessing patient information, enhancing efficiency and accuracy in medical record-keeping.

### 2. Patients: View Personal Diagnosis History 👥
* Functionality: Patients have the ability to log into the system and view their own past diagnosis results.
* Benefit: Empowers patients with easy access to their medical history, fostering better understanding and management of their health conditions.

### 3. AI-Generated Health Insights 🤖🧠
* Functionality: The system leverages artificial intelligence to aggregate and analyze patients' historical diagnosis data, producing insightful health reports.
* Benefit: Provides both patients and healthcare providers with actionable insights, aiding in proactive healthcare management and personalized treatment plans.

## Screenshots 📸
### Doctor's Homepage
![Doctor's Homepage](./UI/Homepage%20-%20Doctor%20Logged%20in.jpg)
### Diagnosis Information
![Patient's History](./UI/History%20-%20Patient.png)
### Getting Health Insights from AI
![Health Insights](./UI/Health%20Advice%20-%20Patient.png)

* More detailed images are in the UI folder

## Installation 💻
1. **Clone the repository**

    ```bash
    git clone https://github.com/ryusudol/SKKUpital.git
    ```

2. **Navigate to the project directory**

    ```bash
    cd SKKUpital
    ```
---
### Frontend
3. **Install the dependencies**

    ```bash
    cd frontend && npm install
    ```
4. **Create .env file**

    ```bash
    OPENAI_API_KEY="Your OpenAI API Key"
    ```

### Backend
3. **Install the dependencies**

    ```bash
    cd backend && npm install
    ```
4. **Create .env file**

    ```bash
    SECRET_KEY="Your Access Token Secret Key"
    ```
---
5. **Start the project**

    ```bash
    npm run dev
    ```
    or
    ```bash
    npm start
    ```
