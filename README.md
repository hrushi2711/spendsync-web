### SpendSync – Credit Card Expense Tracker

<img width="1456" height="1247" alt="Image" src="https://github.com/user-attachments/assets/deda76fa-7321-4b44-80ec-31a653df7898" />

📱  SpendSync is a lightweight credit card expense tracker built with Flutter & Dart. It helps you log expenses, view a dashboard of spending habits, and track progress toward annual fee waivers. Designed as a modern replacement for Excel-based trackers, SpendSync automates calculations and provides a clean, mobile-friendly interface.

🔎 What the App Does Dashboard Provides an overview of your spending across categories and cards. Expense Logging

Manually enter transactions: date, description, category, amount, payment mode, notes.
Categories include: Food & Dining, Shopping, Travel, Fuel, Entertainment, Utilities, Health & Medical, Subscriptions, Education, and Others.
Transactions automatically update summaries. Fee Waiver Tracking
Set card details: annual fee, waiver threshold, cycle start/end.
Tracks cumulative spend against waiver targets.
Shows whether you’ve achieved the waiver and how much more you need to spend.

📊 Key Features

Spending Habits Overview – See where your money goes each month.
Category Breakdown – Identify high-spend areas (e.g., shopping vs. groceries).
Waiver Progress – Visual progress bar showing % of threshold achieved.
Tips Section – Suggestions like using cards for recurring bills to maximize waiver chances.

⚙️ Technical Context (Flutter + Dart) SpendSync is built as a Flutter app with a responsive UI and local database support.

Framework: Flutter (Dart)
Local Database: sqflite (SQLite wrapper for Flutter)
Navigation: Sidebar-style navigation with three main sections:
Dashboard
Expense Logging
Fee Waivers
Architecture: MVVM-style separation using Provider or Riverpod for state management.
Cross-Platform: Runs on Android (APK/AAB) and Web (PWA) from a single codebase.
Design Goal: Replicates and improves Excel trackers by automating calculations and offering a cleaner, installable interface.

🚀 Deployment Guide (Android & Web) This guide walks you through building release-ready packages for SpendSync. Android Deployment

Build APK (for direct install) flutter build apk --release
Build AAB (for Play Store) flutter build appbundle --release
Signing: Configure keystore in android/app/build.gradle.
Testing: Install APK via adb install app-release.apk. Web Deployment
Build Web Release flutter build web --release
Hosting Options: Replit, GitHub Pages, Firebase Hosting, Netlify, or Vercel.
PWA Support: Add manifest.json and service worker for offline caching and installability.

✅ Why It’s Useful For credit card users in India (Axis Rewards, HDFC, ICICI, etc.), fee waivers are common if you meet annual spend thresholds. SpendSync ensures you don’t miss out on savings by tracking progress in real time. It replaces manual Excel tracking with a mobile-first, browser-accessible solution that’s easier to update and more visually engaging.

👉 In short: SpendSync is a personal finance tool to log credit card expenses, analyze monthly spending, and track fee waiver eligibility — built with Flutter & Dart for Android and Web.
