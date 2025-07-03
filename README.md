# TaxTip

<div align="center">
  <h1>
    <img src="images/taxtip.png" width="80px"><br/>
    TaxTip
  </h1>
  <h3>Personal Tax Management & Filing App</h3>
</div>

<p align="center">
    <a href="https://github.com/" target="_blank">
        <img alt="GitHub" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
    </a>
    <a href="APK/app-release.apk" target="_blank">
        <img alt="Download APK" src="https://img.shields.io/badge/Download-APK-green?style=for-the-badge&logo=android" />
    </a>
</p>

---

## 📱 Official App Links

- **APK Download:** [app-release.apk](APK/app-release.apk)

---

## 📖 About TaxTip

TaxTip is a comprehensive tax management and filing app designed for individuals and small businesses. With an intuitive interface and robust features, TaxTip empowers users to manage their tax-related information, calculate liabilities, track assets, and file returns efficiently.

### Key Features

- **User Profile Management:** Update and manage your personal and business information securely.
- **Asset Tracking:** Add, edit, and view various asset types including property, business capital, foreign assets, mutual funds, and vehicles.
- **Income & Expense Management:** Record multiple income sources and expense categories for accurate tax calculations.
- **Tax Calculators:** Built-in calculators for business, salary, and other tax scenarios.
- **Liabilities Management:** Track and manage liabilities with detailed breakdowns.
- **Tax Saving & Deduction:** Explore and record eligible tax-saving investments and deductions.
- **Summary & Analytics:** Visual summaries and reports for assets, liabilities, income, and tax returns.
- **Secure Authentication:** Google Sign-In and Firebase Authentication support.
- **Cloud Sync:** All data is securely synced with Firebase Cloud Firestore.
- **PDF Export:** Export summaries and reports for your records.
- **Modern UI:** Clean, responsive, and user-friendly design.

> **References:**  [APK Download](APK/app-release.apk)

---

## 📌 Overview

**TaxTip** is a Flutter-based tax management app that helps users track assets, income, expenses, liabilities, and file tax returns with ease. It provides analytics, calculators, and secure cloud sync.

## 🚀 Tech Stack

- **Flutter** (Cross-platform UI Framework)
- **GetX** (State Management)
- **Firebase** (Authentication, Firestore, Storage)
- **Cloud Firestore** (Data Storage)
- **PDF Generation**
- **Image Picker** (Profile & Asset Images)
- **Local Storage** (Shared Preferences)

## 🔑 Key Features

- ✅ **User Profile**: Manage and update user info
- ✅ **Asset Management**: Add, edit, and view assets
- ✅ **Income & Expense Tracking**: Record and categorize transactions
- ✅ **Tax Calculators**: Salary, business, and more
- ✅ **Liabilities Tracking**: Manage debts and obligations
- ✅ **Tax Saving & Deduction**: Record eligible investments
- ✅ **Summary & Analytics**: Visual reports and summaries
- ✅ **PDF Export**: Export reports and summaries
- ✅ **Notifications**: Reminders for important actions
- ✅ **Cloud Sync**: Secure data backup with Firebase
- ✅ **Modern UI**: Light/Dark theme support

## 📸 App Screenshots

<div align="center">
  <h4>✨ <b>App Walkthrough</b> ✨</h4>
  <img src="screenshots/taxtip_banner.png" alt="Banner" width="600"/>
</div>

### 🏠 Home & Navigation
<div align="center">
  <img src="screenshots/dashboard.jpg" width="180"/>
  <img src="screenshots/dashboard1.jpg" width="180"/>
  <img src="screenshots/drawer.jpg" width="180"/>
  <img src="screenshots/profile.jpg" width="180"/>
  <img src="screenshots/profile1.jpg" width="180"/>
</div>

### 🔐 Authentication
<div align="center">
  <img src="screenshots/splash.jpg" width="180"/>
  <img src="screenshots/login.jpg" width="180"/>
  <img src="screenshots/signup.jpg" width="180"/>
  <img src="screenshots/forget_password.jpg" width="180"/>
</div>

### 👤 User & About
<div align="center">
  <img src="screenshots/about.jpg" width="180"/>
  <img src="screenshots/about1.jpg" width="180"/>
  <img src="screenshots/contact_us.jpg" width="180"/>
  <img src="screenshots/chat_page.jpg" width="180"/>
</div>

### 🏢 Asset Management
<div align="center">
  <img src="screenshots/assets.jpg" width="180"/>
  <img src="screenshots/assets1.jpg" width="180"/>
  <img src="screenshots/add_property.jpg" width="180"/>
  <img src="screenshots/partnership_add.jpg" width="180"/>
</div>

### 💸 Income & Expense
<div align="center">
  <img src="screenshots/income_inflow.jpg" width="180"/>
  <img src="screenshots/income_inflow1.jpg" width="180"/>
  <img src="screenshots/income_inflow2.jpg" width="180"/>
  <img src="screenshots/income_inflow3.jpg" width="180"/>
  <img src="screenshots/business_income.jpg" width="180"/>
  <img src="screenshots/business_income1.jpg" width="180"/>
  <img src="screenshots/expense_outflows1.jpg" width="180"/>
  <img src="screenshots/expanse_outflows(advance).jpg" width="180"/>
  <img src="screenshots/expanse_outflows(advance)1.jpg" width="180"/>
</div>

### 🏦 Liabilities & Payments
<div align="center">
  <img src="screenshots/liabilities.jpg" width="180"/>
  <img src="screenshots/liabilities_add_edit_delete.jpg" width="180"/>
  <img src="screenshots/payment.jpg" width="180"/>
  <img src="screenshots/payment_detail.jpg" width="180"/>
</div>

### 📊 Tax, Returns & Summary
<div align="center">
  <img src="screenshots/tax_retun(dashboard).jpg" width="180"/>
  <img src="screenshots/tax_retun(complete).jpg" width="180"/>
  <img src="screenshots/tax_retun(pending).jpg" width="180"/>
  <img src="screenshots/tax_retun(submitted).jpg" width="180"/>
  <img src="screenshots/summary.jpg" width="180"/>
  <img src="screenshots/submit.jpg" width="180"/>
  <img src="screenshots/submit1.jpg" width="180"/>
  <img src="screenshots/tax_save.jpg" width="180"/>
  <img src="screenshots/tax_deduction.jpg" width="180"/>
  <img src="screenshots/tax_deduction1.jpg" width="180"/>
</div>

### 🧮 Calculators & Advanced
<div align="center">
  <img src="screenshots/calculator.jpg" width="180"/>
  <img src="screenshots/capital_gain.jpg" width="180"/>
  <img src="screenshots/dividend_income.jpg" width="180"/>
  <img src="screenshots/foreign_income.jpg" width="180"/>
  <img src="screenshots/new_retun_panel.jpg" width="180"/>
  <img src="screenshots/fuilter_apply.jpg" width="180"/>
</div>

## 📁 Project Structure

```
lib/
├── controllers/           # State management controllers
├── models/                # Data models
├── utils/                 # Utility widgets and helpers
├── views/                 # UI screens (Home, Login, Assets, etc.)
├── main.dart              # App entry point
```

## 📱 Download APK

You can download the latest APK from the [APK folder](APK/) or directly:
- [app-release.apk](APK/app-release.apk)

## 🔧 Configuration

### Firebase Setup
1. Create a new Firebase project
2. Enable Authentication and Firestore
3. Download `google-services.json` and place it in `android/app/`

### Environment Variables
If needed, create a `.env` file in the root directory with your Firebase configuration:
```
FIREBASE_API_KEY=your_api_key
FIREBASE_PROJECT_ID=your_project_id
FIREBASE_MESSAGING_SENDER_ID=your_sender_id
FIREBASE_APP_ID=your_app_id
```

## 🚀 Features Overview

- **Asset, Income, and Expense Management**
- **Tax Calculators & Analytics**
- **Liabilities & Deductions**
- **PDF Export**
- **Notifications**
- **User Profiles**
- **Cloud Sync**
- **Modern UI**

## 👥 Contributors

<div align="center">
  <h3>Project Contributors</h3>
</div>

<table align="center">
  <tr>
    <td align="center">
      <img src="contributor/jamalihassan0307.jpeg" width="100px;" alt="jamalihassan0307"/>
      <br />
      <sub><b>ALI HASSAN</b></sub>
    </td>
    <td align="center">
      <img src="contributor/MohsinIsmail28.jpeg" width="100px;" alt="MohsinIsmail28"/>
      <br />
      <sub><b>Mohsin Ismail</b></sub>
    </td>
  </tr>
</table>

<div align="center">
  <h4>🌟 Special Thanks to All Contributors 🌟</h4>
  <p>This project wouldn't be possible without the dedication and expertise of our amazing team.</p>
</div>

---

<p align="center">
   Made with ❤️ by the 7 Skies Solution Team using Flutter and Firebase
</p>
