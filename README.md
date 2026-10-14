# 🛡️ MoneyVaults: Finances & FIRE

[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter)](https://flutter.dev)
[![Platform](https://img.shields.io/badge/Platform-Android-green?logo=android)](https://play.google.com)
[![License](https://img.shields.io/badge/License-Proprietary-blue.svg)](LICENSE)
[![User Guide](https://img.shields.io/badge/Documentation-User%20Guide-teal)](USER_GUIDE.md)

**MoneyVaults: Finances & FIRE** is a modern, privacy-focused, offline-first personal wealth and financial freedom application. Designed to organize your capital into dedicated smart vaults, track cash flow with zero friction, automate recurring reminders, log stocks and dividends, and project exponential compound interest growth toward early retirement (FIRE).

---

## 🌟 Core Features

* **🗄️ Purpose-Built Financial Vaults:**  
  Segment capital into dedicated vaults: **Savings Goals (Piggy Banks)**, **Emergency Runway Funds**, **Investment Portfolios**, and **Operational Spending Accounts**. Customize initial balances, icons, and matching colored progress bars.
* **📈 Dedicated Stock & Asset Vaults:**  
  Track individual equity & ETF positions: enter ticker symbols (e.g. `AAPL`, `VWCE`), monitor unit counts, average acquisition cost (PRU), manual market price updates, total invested capital, current market valuation, and unrealized profit/loss (P&L absolute and percentage). Log dedicated Buy & Sell trades with optional cash flow deduction.
* **💰 Dividend Tracker & Calendar:**  
  Track one-time and recurring dividends linked directly to your stock vaults. Estimate gross and net payouts with configurable tax withholding percentages (e.g. 15%, 28%), and confirm receipts straight into your Cash Flow balance.
* **📅 Future Planned Transactions:**  
  Schedule upcoming commitments (insurance, flights, tax payments) without altering your current liquid balance until the due date arrives.
* **🔁 Recurring Rules & Smart Device Alerts:**  
  Set recurring reminders for rent, salaries, subscriptions, and investments with customizable recurrence intervals ($x$ Days, Weeks, Months, or Years), target days of month (1–31), and specific notification times. Receive local device push notifications with instant **"Confirm & Log"**, **"Modify & Log"**, or **"Skip"** options.
* **🏷️ Tag Manager & Instant Filtering:**  
  Create custom tags with color labels to categorize expenses across vaults. Filter cash flow seamlessly by category, vault, tag, or status.
* **📊 Vaults Monthly Evolution:**  
  Multi-month stacked bar charts comparing cumulative balances and monthly net cash flows across 3-month and 6-month horizons with full multilingual month formatting.
* **⚡ One-Tap Fastfill & Independent Cash Flow:**  
  Log recurring daily expenses in under two seconds. Use the "Deduct from Income" switch to record expenses for budgeting and analytics without subtracting money from your liquid checking balance.
* **🎓 Step-by-Step Interactive Tutorials:**  
  7 built-in modal guides walking through every core capability, completely non-intrusive and available in 6 languages (EN, PT, ES, FR, IT, DE).
* **🧮 Financial Calculators Suite:**  
  - Compound Interest & FIRE Retirement Countdown Planner  
  - Dividend Growth & Reinvestment (DRIP) Simulator  
  - Loan Amortization & Early Payoff Table  
  - Smart Discount & Promotional Comparison Tool
* **🔒 100% Offline-First Privacy & Data Center:**  
  Zero account registration required, zero third-party financial tracking. Export and restore your complete portfolio in encrypted JSON or backup directly to Google Drive, iCloud, or local storage.

---

## 📖 Comprehensive Documentation

For a complete walkthrough of all features, math formulas, and membership plan details, read the official guide:

👉 **[Read the MoneyVaults User Manual & Guide (USER_GUIDE.md)](USER_GUIDE.md)**

---

## 🚀 Building & Running from Source

### Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (3.13+)
- Dart SDK (3.13+)
- Android Studio / Android SDK (Platform 34 / Java 17)

### Quick Start
```bash
# Clone the repository
git clone https://github.com/compoundlysupport/MoneyVaults-Privacy.git
cd MoneyVaults-Privacy

# Install dependencies
flutter pub get

# Run static analysis
flutter analyze

# Run all unit and widget tests
flutter test

# Run app in debug mode
flutter run

# Build production Android App Bundle (AAB)
flutter build appbundle --release
```

---

## 📄 License & Privacy

* **Privacy Policy & Terms:** [MoneyVaults Privacy Notice](https://compoundlysupport.github.io/MoneyVaults-Privacy/)
* **Support Contact:** `compoundlysupport@gmail.com`
