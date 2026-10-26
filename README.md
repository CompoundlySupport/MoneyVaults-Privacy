# 🛡️ MoneyVaults: Finances & FIRE

[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter)](https://flutter.dev)
[![Platform](https://img.shields.io/badge/Platform-Android-green?logo=android)](https://play.google.com)
[![License](https://img.shields.io/badge/License-Proprietary-blue.svg)](LICENSE)
[![User Guide](https://img.shields.io/badge/Documentation-User%20Guide-teal)](USER_GUIDE.md)

**MoneyVaults: Finances & FIRE** is a modern, privacy-focused, offline-first personal wealth and financial freedom application. Designed to organize your capital into dedicated smart vaults, track cash flow with zero friction through list and interactive calendar views, visualize multi-horizon **Evolution & Trend Curves**, automate recurring reminders, log stocks and dividends, and project exponential compound interest growth toward early retirement (FIRE).

---

## 🌟 Core Features

* **🗄️ Purpose-Built Financial Vaults & Smart Sorting:**  
  Segment capital into dedicated vaults: **Savings Goals (Piggy Banks)**, **Emergency Runway Funds**, **Investment Portfolios**, **Stock / Equity Vaults**, and **Operational Spending Accounts**. Sort vaults by Default order, Balance, Name, or Vault Type, and update balances, P&L, or share prices instantaneously with auto-selected quick inputs.
* **📈 Evolution & Trend Curves (1M, 3M, YTD, 1Y, ALL):**  
  Track individual vaults or your entire portfolio with interactive **Evolution & Trend Curves** across 5 timeframes (**1M** Daily, **3M** Daily, **YTD** Weekly, **1Y** Weekly, and **ALL** Monthly). Compare **Current Balance** and **Profit & Loss (P&L)** simultaneously on a natural monetary scale with a dashed `0` baseline, powered by automated `00:00` local snapshots and ultra-compact **FIFO** retention pruning.
* **📊 Dedicated Stock & Asset Vaults:**  
  Track individual equity & ETF positions: enter ticker symbols, monitor unit counts, average acquisition cost (PRU), manual market price updates, total invested capital, current market valuation, and unrealized profit/loss (P&L absolute and percentage). Log dedicated Buy & Sell trades with optional cash flow inclusion.
* **🗓️ Interactive Monthly Calendar View & Cash Flow Hub:**  
  Switch between List View and a rich **Monthly Calendar View** on the Cash Flow screen. Filter calendar days by **All**, **Completed**, **Planned**, or **Recurring** status, inspect daily inflows/outflows, log due items in 1 tap, or edit future one-time planned transactions and future recurring rules directly from the calendar.
* **⚡ Unified "Include in the Cash Flow" Control & Advanced Filtering:**  
  Toggle **"Include in the cash flow"** on any expense, vault transfer, stock trade, planned transaction, or recurring rule to record entries for analytics without altering your liquid cash balance. Use the dedicated **Exclude in Cash Flow Filter** on the Cash Flow bar alongside Title Search, Vault, Tag, Category, and Time Range filters (`This Month`, `Last Month`, `Last 3M`, `Last 6M`, `YTD`, `Last Year`, `Custom Range`).
* **💰 Dividend Tracker, Projections & Calendar:**  
  Track one-time and recurring dividends linked directly to your stock vaults. Estimate gross and net payouts with configurable tax withholding percentages (e.g. 15%, 28%), explore **Dividend Projections** across 1M, 3M, 6M, End of Year, and 1Y horizons with an edge-to-edge monthly average reference line and floating badge, manage holdings with batch select/delete actions, and confirm receipts straight into your Cash Flow balance.
* **📅 Future Planned Transactions:**  
  Schedule upcoming commitments (insurance, flights, tax payments) without altering your current liquid balance until the due date arrives, and edit them anytime from the List or Calendar view.
* **🔁 Recurring Rules & Smart Device Alerts:**  
  Set recurring reminders for rent, salaries, subscriptions, and investments with customizable recurrence intervals ($x$ Days, Weeks, Months, or Years), target days of month (1–31), and specific notification times. Receive local device push notifications with instant **"Confirm & Log"**, **"Modify & Log"**, or **"Skip"** options.
* **🏷️ Tag Manager & Custom Labels:**  
  Create custom tags with color labels to categorize expenses across vaults and filter transaction history instantaneously.
* **📊 Vaults Monthly Stacked Evolution:**  
  Multi-month stacked bar charts comparing cumulative balances and monthly net cash flows across 3-month and 6-month horizons with full multilingual month formatting.
* **🎓 Step-by-Step Interactive Tutorials & Fictional Demo Showcase:**  
  7 built-in modal guides walking through every core capability in 6 languages (EN, PT, ES, FR, IT, DE), plus an instant **Demo Mode** featuring realistic daily, weekly, and monthly market fluctuations using strictly fictional sample tickers (`NVTX`, `APXS`, `PRMT`, `OMBV`).
* **🧮 Financial Calculators Suite:**  
  - Compound Interest & FIRE Retirement Countdown Planner (with maximized full-width trajectory charts)  
  - Dividend Growth & Reinvestment (DRIP) Simulator  
  - Loan Amortization & Early Payoff Table (with maximized remaining principal balance chart)  
  - Smart Discount & Promotional Comparison Tool (100% Free)
* **👑 Transparent Membership & 14-Day Free Trial:**  
  Explore MoneyVaults Premium completely risk-free with a **14-day free trial** on all subscription plans (Monthly, 3-Month, 6-Month, Annual), automated Day 10 cancellation reminders, Lifetime Access, or unlock temporary 1-minute passes via rewarded video.
* **🔒 100% Offline-First Privacy & Data Center:**  
  Zero account registration required, zero third-party financial tracking. Export and restore your complete portfolio—including historical evolution snapshots—in JSON or backup directly to Google Drive, iCloud, or local storage.

---

## 📖 Comprehensive Documentation

For a complete walkthrough of all features, math formulas, and membership plan details, read the official guide:

👉 **[Read the MoneyVaults User Manual & Guide (USER_GUIDE.md)](USER_GUIDE.md)**

---

## 🚀 Building & Running from Source

### Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (3.13+)
- Dart SDK (3.13+)
- Android Studio / Android SDK (Platform 35 / Java 17)

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

* **Privacy Policy, Terms & User Guide:** [MoneyVaults Legal & Privacy Center](https://compoundlysupport.github.io/MoneyVaults-Privacy/)
* **Support Contact:** `compoundlysupport@gmail.com`
