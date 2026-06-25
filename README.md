# Nutri-Tsek v1.0.0 Thesis Edition

![Platform](https://img.shields.io/badge/Platform-Android-green)
![Frontend](https://img.shields.io/badge/Frontend-Next.js-black)
![Backend](https://img.shields.io/badge/Backend-.NET%2010-purple)
![Database](https://img.shields.io/badge/Database-Supabase-blue)
![Status](https://img.shields.io/badge/Status-Thesis%20Edition-success)

<p align="center">
  <img src="screenshots/Home.png" width="280" alt="Nutri-Tsek Home Screen">
</p>

---

# About Nutri-Tsek

Nutri-Tsek is a mobile-based application developed as a Bachelor of Science in Computer Science thesis project. The application helps consumers evaluate the nutritional quality of packaged food products using barcode scanning and the Nutri-Score algorithm.

In addition to Nutri-Score, the application provides supplementary product quality indicators such as NOVA Classification, Nøglehullet Assessment, and Nutrient Traffic-Light Grading. Registered users can also monitor calorie intake, track food consumption, manage nutrition goals, compare products, and receive personalized nutrition recommendations.

---

# 🌐 Try Nutri-Tsek Online

The web version of Nutri-Tsek is available for demonstration and testing directly in your browser.

🌐 **Live Web Application**

https://nutritsek.vercel.app

Try Nutri-Tsek directly in your browser without installing anything.

> **Note:** Some mobile features, such as barcode scanning, may have limited functionality depending on the browser and device. For the best experience, install the Android APK.

---

# 📱 Download Android APK

Download the latest Android APK from the **GitHub Releases** section.

📦 **Nutri-Tsek-v1.0.0.apk**

The Android version provides the complete Nutri-Tsek experience, including native barcode scanning and optimized mobile performance.

---

# About Nutri-Tsek

Nutri-Tsek is a mobile-based application developed as a Bachelor of Science in Computer Science thesis project. The application helps consumers evaluate the nutritional quality of packaged food products using barcode scanning and the Nutri-Score algorithm.

In addition to Nutri-Score, the application provides supplementary product quality indicators such as NOVA Classification, Nøglehullet Assessment, and Nutrient Traffic-Light Grading. Registered users can also monitor calorie intake, track food consumption, manage nutrition goals, compare products, and receive personalized nutrition recommendations.

---


# Product Evaluation System

Nutri-Tsek evaluates food products using multiple complementary food quality assessment methods to provide users with an easy-to-understand nutritional overview.

### 🟢 Nutri-Score

Evaluates the overall nutritional quality of food products using the Nutri-Score algorithm, assigning grades from **A (healthier choice)** to **E (less healthy choice)**.

---

### 🟠 NOVA Classification

Classifies foods according to their degree of processing.

- Group 1 – Unprocessed or minimally processed foods
- Group 2 – Processed culinary ingredients
- Group 3 – Processed foods
- Group 4 – Ultra-processed foods

---

### 🔵 Nøglehullet Assessment

Determines whether a product meets the Nordic Keyhole nutritional criteria, helping users identify healthier food choices.

---

### 🟡 Nutrient Traffic-Light Grading

Evaluates important nutrients using color indicators:

- 🟢 Low
- 🟡 Medium
- 🔴 High

The grading is applied to:

- Fat
- Saturated Fat
- Sugar
- Salt

---

### 📊 Product Comparison

Users can compare two food products side by side, including:

- Nutritional values
- Nutri-Score
- NOVA Classification
- Nøglehullet Assessment
- Nutrient Traffic-Light Grading

The application highlights the healthier option to support informed purchasing decisions.

---

### 💡 Personalized Recommendations

Based on product evaluation and user preferences, Nutri-Tsek recommends healthier alternative products when available.

# Table of Contents

- About
- Try Nutri-Tsek Online
- Download Android APK
- Product Evaluation System
- Features
- Application Screenshots
- Demo Videos
- Help Evaluate Nutri-Tsek
- Technology Stack
- System Architecture
- Installation
- Data Sources
- Project Information
- Disclaimer
- License

---

# Features

## Product Evaluation

* Barcode scanning
* Product search
* Product nutrition information
* Nutri-Score evaluation
* NOVA food processing classification
* Nøglehullet assessment
* Nutrient Traffic-Light Grading
* Product comparison
* Alternative product recommendations

## Personalized User Features

* User registration and login
* Personalized nutrition goals
* Allergy management
* Purchase history
* Consumption tracking
* Daily, weekly, and monthly calorie summaries
* Nutrition trends
* Personalized recommendations
* User profile management

---

# Application Screenshots

## 🏠 Home

The application's main screen provides quick access to barcode scanning, product search, and other core functions.

<p align="center">
<img src="screenshots/Home.png" width="280">
</p>

---

## 📊 Dashboard

The dashboard provides a personalized nutrition overview for registered users.

**Features**

* Calorie tracking
* Consumption history
* Nutrition trends
* Personalized recommendations

<p align="center">
<img src="screenshots/Dashboard.png" width="280">
</p>

---

## 👤 Profile

Manage personal information and nutrition preferences.

**Features**

* Update profile information
* Manage nutrition goals
* Manage food allergies
* Change password
* Delete account
* Secure logout

<p align="center">
<img src="screenshots/Profile.png" width="280">
</p>

---

## 🛒 Purchase History

View previously saved products and monitor purchasing habits.

**Features**

* Saved history
* Product ratings
* Product reviews & ratings


<p align="center">
<img src="screenshots/Purchase.png" width="280">
</p>

---

## ⚙️ Settings

Customize the application according to user preferences.

**Features**

* English and Danish language selection
* Light and Dark themes
* Application preferences
* Privacy Policy
* Terms of Service
* Medical Disclaimer
* About the application

<p align="center">
<img src="screenshots/Setting.png" width="280">
</p>

---

## 🔐 Login

Secure authentication is required to access personalized features.

After logging in, users gain access to:

* Profile management
* Allergy settings
* Nutrition goals
* Personalized recommendations
* Account management

<p align="center">
<img src="screenshots/Login.png" width="280">
</p>

---

# Demo Videos

## 🎥 Product Scanning Demo

This demonstration showcases the complete product scanning workflow.

**Demonstrated Features**

* Barcode scanning
* Product lookup
* Nutrition facts
* Nutri-Score evaluation
* NOVA Classification
* Nøglehullet Assessment
* Nutrient Traffic-Light Grading
* Product recommendations

▶ **Video:** [Product Scanning Demo](demo/ScannerFeature.mp4)

---

## 🎥 Product Comparison Demo

This demonstration showcases the product comparison feature.

**Demonstrated Features**

* Compare two products
* Side-by-side nutritional comparison
* Nutri-Score comparison
* NOVA comparison
* Nøglehullet assessment
* Nutrient Traffic-Light comparison
* Identification of the healthier product

▶ **Video:** [Product Comparison Demo](demo/ComparisonFeature.mp4)


## 📝 Help Evaluate Nutri-Tsek

Nutri-Tsek includes a built-in evaluation module developed as part of my **Bachelor of Science in Computer Science** thesis. The evaluation feature helps assess the application's software quality, usability, functionality, and overall user experience. Feedback collected through the application contributes to improving Nutri-Tsek and supports the research conducted for this academic project.

### Evaluation Types

#### 👨‍💻 Technical Evaluator

Intended for software developers, IT professionals, instructors, and students with technical knowledge.

The technical evaluation measures:

* Functional Suitability
* Performance Efficiency
* Reliability
* Security
* Maintainability
* Portability

#### 👤 General User

Intended for anyone using the application.

The general user evaluation focuses on:

* Ease of Use
* User Interface
* Overall Satisfaction
* User Experience

### How to Participate

1. Open Nutri-Tsek using the Android application or the web version.
2. Create an account or sign in.
3. Navigate to the **Evaluation** page.
4. Select the appropriate evaluator type.
5. Complete the evaluation questionnaire.
6. Submit your responses.

Participation is completely voluntary and greatly appreciated. Every evaluation helps improve Nutri-Tsek and contributes to the successful completion of this Bachelor of Science in Computer Science thesis.

❤️ **Thank you for supporting the Nutri-Tsek project!**

---


# Technology Stack

## Frontend

* Next.js
* React
* TypeScript
* Tailwind CSS
* React Query
* Capacitor Android

## Backend

* ASP.NET Core Web API (.NET 10)
* PostgreSQL
* Supabase
* JWT Authentication
* BCrypt Password Hashing

## Product Evaluation

* Nutri-Score Algorithm
* NOVA Classification
* Nøglehullet Assessment
* Nutrient Traffic-Light Grading

---

# System Architecture

```text
                   Users
                     │
      ┌──────────────┴──────────────┐
      │                             │
      ▼                             ▼
 Web Browser                 Android APK
      │                             │
      └──────────────┬──────────────┘
                     ▼
     Next.js Frontend (Hosted on Vercel)
                     │
                     ▼
     ASP.NET Core Web API (.NET 10)
                     │
                     ▼
       PostgreSQL Database (Supabase)
```

---


## 📝 Help Evaluate Nutri-Tsek

As part of my Bachelor of Science in Computer Science thesis, I am collecting feedback to evaluate the usability, functionality, and overall quality of Nutri-Tsek.

If you have a few minutes, your evaluation would be greatly appreciated and will contribute to the research and improvement of the application.

### Evaluation Types

**👨‍💻 Technical Evaluator**

For software developers, IT professionals, instructors, and students with technical knowledge.

The technical evaluation focuses on:

* Functional Suitability
* Performance Efficiency
* Reliability
* Security
* Maintainability
* Portability

---

**👤 General User**

For anyone who uses the application.

The general user evaluation focuses on:

* Ease of use
* User interface
* Overall satisfaction
* User experience

---

### How to Participate

1. Open Nutri-Tsek.
2. Create an account or sign in.
3. Navigate to **Dashboard → Evaluation**.
4. Select the appropriate evaluator type.
5. Complete the evaluation form.
6. Submit your responses.

Your participation is completely voluntary and greatly appreciated. Every evaluation helps improve the application and supports the completion of this academic research.

Thank you for supporting the Nutri-Tsek project!

## Evaluation

<p align="center">
<img src="screenshots/Evaluation.png" width="280">
</p>
---


# Installation

1. Download the latest APK from the **Releases** section.
2. Transfer the APK to your Android device if necessary.
3. Install the APK.
4. Allow installation from unknown sources if prompted.
5. Launch Nutri-Tsek.
6. Register or log in to access personalized features.

---


# Try Nutri-Tsek Online

The web version of Nutri-Tsek is available for demonstration and testing directly in your browser.

🌐 **Web Application**

https://nutritsek.vercel.app

> **Note:** Some mobile features, such as the barcode scanner, may have limited functionality in web browsers depending on the browser and device. For the best experience, install the Android application.

---

# Download Android APK

The latest Android APK is available from the **Releases** section of this repository.

📦 **Nutri-Tsek-v1.0.0.apk**

For the best experience, install the Android APK on an Android device to access all mobile features, including barcode scanning and native camera support.

---

# Data Sources

Nutri-Tsek uses publicly available food datasets for educational and research purposes.

* Open Food Facts
* DTU Food FRIDA Food Database

---

# Project Information

**Project Title**

Nutri-Tsek: Mobile-Based Application for Evaluating Nutritional Values of Food Products Using the Nutri-Score Algorithm

**Program**

Bachelor of Science in Computer Science

**Purpose**

Academic thesis project, demonstration application, and software engineering portfolio project.

---

# Disclaimer

Nutri-Tsek is intended for educational, research, demonstration, and portfolio purposes only.

The application presents nutritional information and product evaluations based on available food product data and established food classification systems. It is not intended to provide medical advice, diagnosis, or treatment.

---

# License

Copyright © 2026 Grace Duquiza Olesen.

This repository is publicly available for academic review, demonstration, and portfolio purposes only.

No permission is granted to copy, modify, redistribute, or use this source code without prior written permission from the copyright holder.
