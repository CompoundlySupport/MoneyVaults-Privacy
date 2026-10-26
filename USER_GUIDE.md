# 📘 MoneyVaults: Finances & FIRE — Official User Guide & Manual

Welcome to **MoneyVaults: Finances & FIRE**, the modern, offline-first personal wealth management and financial freedom operating system.

---

## 📑 Table of Contents

1. [Philosophy & Architecture](#-philosophy--architecture)
2. [Quick Start Guide](#-quick-start-guide)
3. [Understanding Vault Types & Sorting](#-understanding-vault-types--sorting)
   - [Savings Goals & Emergency Funds](#savings-goals--emergency-funds)
   - [Dedicated Stock & Asset Vaults (PRU, Units & P&L)](#dedicated-stock--asset-vaults)
   - [Vault Sorting & Instant Value Replacement](#vault-sorting--instant-value-replacement)
4. [Cash Flow, Calendar View & Transactions](#-cash-flow-calendar-view--transactions)
   - [Interactive Monthly Calendar View](#interactive-monthly-calendar-view)
   - [Fastfill One-Tap Logging](#fastfill-one-tap-logging)
   - [Cash Flow Independence ("Include in the cash flow" Switch & Filter)](#cash-flow-independence)
   - [Tag Manager & Multi-Criteria Filtering](#tag-manager--custom-filtering)
5. [Future Planned Transactions](#-future-planned-transactions)
6. [Recurring Transactions & Smart Alerts](#-recurring-transactions--smart-alerts)
7. [Dividend Tracker, Projections & Stock Vault Sync](#-dividend-tracker--stock-vault-sync)
8. [Vaults Evolution & Trend Curves (1M, 3M, YTD, 1Y, ALL)](#-vaults-evolution--trend-curves)
9. [Portfolio Allocation & Weights](#-portfolio-allocation--weights)
10. [Financial Calculators Suite](#-financial-calculators-suite)
    - [Compound Growth & FIRE Calculator](#1-compound-growth--fire-calculator)
    - [Dividend Growth & Yield Calculator](#2-dividend-growth--yield-calculator)
    - [Loan Amortization & Early Payoff](#3-loan-amortization--early-payoff)
    - [Smart Discount Calculator](#4-smart-discount-calculator)
11. [Interactive Tutorials & Demo Mode](#-interactive-tutorials--demo-mode)
12. [Smart Reminders & Notifications](#-smart-reminders--notifications)
13. [Data Center, Cloud Backup & Privacy](#-data-center-cloud-backup--privacy)
14. [Membership Plans (Standard vs Premium)](#-membership-plans-standard-vs-premium)
15. [Frequently Asked Questions (FAQ)](#-frequently-asked-questions-faq)
16. [Support & Contact](#-support--contact)

---

## 🏛️ Philosophy & Architecture

MoneyVaults is built upon three non-negotiable principles:

* **100% Offline-First Privacy:** Your finances are your business. MoneyVaults does not require an account, does not connect to external financial servers, and never sells or uploads your data. All records remain stored locally on your device.
* **Mathematical Precision:** No ambiguous projections. Every compound growth curve, loan amortization schedule, historical evolution curve, and portfolio weighting formula is built on transparent financial math.
* **Frictionless Daily Tracking:** With customizable **Fastfill** buttons, auto-selected quick update inputs, and an interactive **Calendar View**, logging a daily transaction or portfolio update takes less than two seconds.

---

## 🚀 Quick Start Guide

1. **Set Your Base Currency:**  
   Open settings or tap the currency indicator to choose your preferred currency symbol (`€`, `$`, `£`, `¥`, `CHF`, `R$`, etc.).
2. **Review or Sort Your Vaults:**  
   Head to the **Vaults** tab to see your foundational accounts (General Account, Emergency Fund, Investment Vault) and sort them by Default, Balance, Name, or Type.
3. **Log Your First Cash Flow:**  
   Tap the central **`+`** button in the bottom navigation (or the leftmost **`+`** button in any Vault Details header) to add an Income, Expense, or Vault transfer.
4. **Explore Tutorials or Demo Mode:**  
   Open the top menu and tap **Tutorials** for step-by-step walkthroughs, or switch on **Demo Mode** to explore a rich pre-populated portfolio with fictional assets.

---

## 🗄️ Understanding Vault Types & Sorting

<a id="savings-goals--emergency-funds"></a>
MoneyVaults organizes your wealth into dedicated, purpose-built vaults:

| Vault Category | Purpose | Key Features |
| :--- | :--- | :--- |
| **💰 Piggy Bank (Savings Goal)** | Short-to-medium term savings goals (Vacation, Car, Tech). | Target amount, percentage progress bar, milestone tracking. |
| **🛡️ Emergency Fund** | Runway reserve for peace of mind. | Monthly burn rate calculator, months of runway covered. |
| **📈 Investment & Wealth** | Compounding assets (ETFs, Funds, Real Estate, Crypto). | Compound growth engine, P&L tracking, auto-reinvestment simulation, capital target. |
| **📊 Stock / Equity Vault** | Individual stocks & ETF portfolio positions. | Ticker symbol, unit tracking, average acquisition cost (PRU), live P&L. |
| **💳 Expense & Budget** | Daily operational spending (Groceries, Dining, Utilities). | Fastfill one-tap logging, categorized expenditure summaries. |

<a id="dedicated-stock--asset-vaults"></a>
### Dedicated Stock & Asset Vaults
* **Ticker Symbol:** Assign market tickers (e.g., `VWCE`, `IWDA`, or fictional demo tickers like `NVTX`, `APXS`).
* **Live Position Metrics:** Automatically tracks net units owned, average acquisition price (PRU), total invested capital, current market valuation, and unrealized profit/loss (both in currency and percentage).
* **Buy & Sell Trades:** Dedicated "Buy" and "Sell" buttons record order quantity, unit price, and broker commission fees.
* **Cash Flow Option:** Choose whether each trade is included in your Cash Flow balance or operates as an independent portfolio adjustment.

<a id="vault-sorting--instant-value-replacement"></a>
### Vault Sorting & Instant Value Replacement
* **Custom Vault Sorting:** Sort your vaults list by **Default**, **Balance (High to Low)**, **Name (A–Z)**, or **Vault Type**.
* **Instant Value Replacement:** When you tap **Update P&L**, **Update Price**, or **Update Base**, the input field opens immediately focused and pre-selected so typing a new number replaces the previous value right away without needing to backspace.
* **Quick Add Transaction:** Inside any Vault Details screen, the **`+`** button to log a new transaction is positioned as the leftmost action in the header bar for rapid access.

---

## 💸 Cash Flow, Calendar View & Transactions

The **Cash Flow** tab provides real-time control over liquidity, historical transactions, and future commitments:

* **Net Cash Flow Card:** Real-time breakdown of total Income, total Outflow, and Net Savings.
* **Transaction Logging:** Select date, amount, description, tags, category, and target vault.

<a id="interactive-monthly-calendar-view"></a>
### Interactive Monthly Calendar View
Toggle the **Calendar icon** on the Cash Flow screen to switch from the standard list to the **Interactive Monthly Calendar View**:
* **Daily Activity Dots & Totals:** Instantly spot which days have completed transactions, planned future commitments, or recurring rules.
* **Status Filter Pills:** Filter the calendar grid by **All**, **Completed**, **Planned**, or **Recurring**.
* **Inspect, Confirm & Edit Future Items:** Tap any date on the calendar to inspect its scheduled or completed transactions below the grid:
  * **Confirm & Log** due recurring or planned items in one tap.
  * **Edit Future One-Time Planned Transactions** directly from the selected calendar day and save your updated amount, title, or date seamlessly.
  * **Edit Future Recurring Transactions** from the selected calendar day—modifying a future recurring occurrence updates the rule for that selected date and future occurrences without erroneously creating a completed transaction prematurely.

<a id="fastfill-one-tap-logging"></a>
### Fastfill One-Tap Logging
* Configure a fastfill step increment on expense vaults (e.g. `€5`, `€10`, `€25`) to log frequent routine items with a single tap.

<a id="cash-flow-independence"></a>
### Cash Flow Independence ("Include in the cash flow" Switch & Filter)
* **Unified "Include in the cash flow" Switch:** Every transaction form—including Expenses, Investments, Piggy Banks, Emergency Funds, Stock Buy/Sell trades, Planned transactions, and Recurring rules—features an **"Include in the cash flow"** toggle:
  * When enabled, the transaction impacts your Cash Flow summary and liquid balance.
  * When disabled, the transaction updates the specific vault or budget analytics without altering your Cash Flow balance (ideal for reimbursed expenses, prepaid cards, or internal capital movements).
* **Dedicated Cash Flow Exclude Filter:** On the Cash Flow screen, the leftmost filter button lets you **hide transactions marked as "Exclude in Cash Flow"** (disabled by default so all transactions remain visible until you toggle the filter on).

<a id="tag-manager--custom-filtering"></a>
### Tag Manager & Multi-Criteria Filtering
* Open the **Tag Manager** from the top bar to create custom tags with dedicated color labels.
* Combine filters on the Cash Flow bar: **Exclude in Cash Flow Toggle**, **Title Search**, **Vault Filter**, **Tag Filter**, **Category Filter**, and **Time Range Filter** (`This Month`, `Last Month`, `Last 3M`, `Last 6M`, `YTD`, `Last Year`, or `Custom Date Range`).

---

## 📅 Future Planned Transactions

Plan future commitments and avoid surprises:
* **Future Dating:** In any transaction form, pick a future date to record an upcoming planned expense or expected income (e.g. quarterly insurance, travel bookings, tax bills).
* **Cash Flow Shielding:** Planned transactions do not alter your current liquid balance until their due date arrives.
* **Calendar & Scheduled View:** View and edit planned commitments directly in the **Monthly Calendar View** (filtering by *Planned*) or via the Scheduled section.
* **Settlement Day Confirmation:** When the scheduled date arrives, the app prompts you to confirm, modify, or reschedule the final settlement into your permanent history.

---

## 🔁 Recurring Transactions & Smart Alerts

Automate routine obligations:
* **Calendar Recurrence Rules:** Set rules for rent, salaries, gym memberships, or ETF savings plans with customized recurrence intervals ($x$ Days, Weeks, Months, or Years), specific monthly due days (1–31), and notification times.
* **Device Notifications:** Receive local push notifications when a payment is due.
* **Pending Confirmations & Calendar Editing:** Review due items with full control (**"Confirm & Log"**, **"Modify & Log"**, or **"Skip"**), or select any future occurrence in the **Calendar View** to adjust future recurring parameters cleanly.

---

## 💰 Dividend Tracker, Projections & Stock Vault Sync

<a id="-dividend-tracker--stock-vault-sync"></a>
Track and project passive income from equity holdings:
* **Log Dividends:** Record one-time special dividends or scheduled recurring dividends (monthly, quarterly, semi-annually, annually).
* **Stock Vault Integration:** Select your stock vault to automatically fetch current shares owned and calculate projected gross and net payouts.
* **Tax Withholding:** Specify tax withholding percentages (e.g. 15% or 28%) to forecast true take-home passive cash.
* **Payout Calendar:** View upcoming dividend dates and confirm received dividends directly into your Cash Flow balance.
* **Dividend Projections Dashboard:**
  * Tap the chart icon in the Dividend Tracker top bar to open the **Projections** screen.
  * Switch between 5 horizons: **1M**, **3M**, **6M**, **End of Year (YTD)**, and **1Y**.
  * **Monthly Average Reference Line:** An edge-to-edge dashed reference line with a floating pill badge highlights your average monthly dividend income across the selected period.
  * **Auto-Scaling Headers:** Screen and section headers dynamically adapt using `FittedBox` scaling to prevent text clipping across all supported languages.
* **Detailed Card Breakdown & Batch Actions:**
  * Tap any card to expand its breakdown, including owned shares, tax withholding rates, and payment frequencies with fully localized unit labels.
  * Use **Select All**, **Deselect All**, and **Delete Selected** to batch manage or prune multiple dividend records at once.

---

## 📈 Vaults Evolution & Trend Curves

<a id="vaults-evolution--trend-curves"></a>
Analyze both short-term and multi-year wealth trajectories from the **Vaults Evolution & Trends** screen:

### 1. Evolution & Trend Curves (1M, 3M, YTD, 1Y, ALL)
* **5 Timeframe Horizons:**
  * **1M (1 Month):** Daily resolution (up to 31 daily points).
  * **3M (3 Months):** Daily resolution (up to 92 daily points).
  * **YTD (Year-to-Date):** Weekly resolution from January 1st.
  * **1Y (1 Year):** Weekly resolution (up to 53 weekly points).
  * **ALL (All-Time):** Monthly resolution across your entire history.
* **Natural Dual-Curve Comparison (Current Balance & P&L):**
  * View **Current Balance** and **Profit & Loss (P&L)** plotted on a unified, natural monetary scale with a dashed `0` baseline and clear Y-axis value labels so the curves never artificially converge or distort.
  * Scrub across the chart to inspect exact dates, balances, P&L figures, and period variations.
* **Automated `00:00` Snapshots & FIFO Pruning:**
  * MoneyVaults automatically captures local snapshots at `00:00` and applies **First-In-First-Out (FIFO)** retention pruning to keep storage fast and lightweight.
  * Any period prior to a vault's creation date is automatically anchored at `0`.

### 2. Monthly Stacked Bar Evolution (3M & 6M)
* **Interactive Multi-Month Chart:** View stacked bar charts comparing vault performance over **3-Month** and **6-Month** horizons.
* **Dual View Modes:** Switch between **Cumulative Balance** and **Monthly Net Flow**, with localized month formatting and tap-to-inspect breakdowns.

---

## 📊 Portfolio Allocation & Weights

* **Visual Asset Distribution:** Real-time percentage weighting of every vault against total net worth.
* **Liquid vs Invested Ratios:** Monitor the balance between immediate emergency reserves and compounding growth assets.
* **Rebalancing Insight:** Keep your portfolio aligned with your target allocations.

---

## 🧮 Financial Calculators Suite

Access the suite from the **Tools** tab. All trajectory charts feature maximized, borderless plotting areas for maximum readability:

### 1. Compound Growth & FIRE Calculator
* **Inputs:** Principal, monthly deposits, expected annual return, time horizon.
* **FIRE Projection:** Computes your Financial Independence target number (based on the 4% safe withdrawal rule) and calculates your retirement countdown.
* **Maximized Trajectory Chart:** Full-width **Growth Trajectory Over Time** chart with a clean legend displaying the accumulated compound reinvestment advantage, plus year-by-year and month-by-month tables.

### 2. Dividend Growth & Yield Calculator
* **DRIP Simulation:** Model dividend reinvestment compounding over multi-year horizons.
* **Gross vs Net:** Calculates dividend yield on cost and after-tax annual income.

### 3. Loan Amortization & Early Payoff
* **Maximized Balance Trajectory:** Full-width **Remaining Principal Balance Trajectory** chart comparing standard payoff vs accelerated payoff with interest saved and time ahead directly in the chart legend.
* **Accelerated Payoff Schedule:** Detailed regular principal, extra amortization, interest, and remaining balance columns.

### 4. Smart Discount Calculator (100% Free)
* **Direct Discount & Sales Tax:** Instant calculation of discounted price and savings.
* **Side-by-Side Comparison:** Compare two promotional offers side by side to pick the better deal.

---

## 🎓 Interactive Tutorials & Demo Mode

<a id="interactive-tutorials--demo-mode"></a>
* **7 Guided Modal Walkthroughs** accessible from the top bar menu:
  1. **General Account & Cash Flow**
  2. **Investment Vaults & Allocations**
  3. **Recurring Rules & Confirmations**
  4. **Future Planned Transactions**
  5. **Stocks Vault & Buy/Sell Trades**
  6. **Dividend Tracker & Stock Vault Sync**
  7. **Cash Flow Independence (Non-Deducted Expenses)**
* **Realistic Fictional Demo Mode:** Activate Demo Mode from the top bar to test all charts, Evolution Curves, Calendar views, and Stock/Dividend trackers with realistic daily, weekly, and monthly positive/negative fluctuations and an upward long-term trend—using strictly fictional sample companies and tickers (`NovaTech Corp. (NVTX)`, `Apex Systems (APXS)`, `Prime Realty Trust (PRMT)`, `OmniBev Corp. (OMBV)`, `Global Core Equity ETF`).
* Fully localized in 6 languages: English, Portuguese, Spanish, French, Italian, and German.

---

## 🔔 Smart Reminders & Notifications

* **Daily Check-Ins:** Optional evening reminder to review and log daily expenses.
* **Due Alerts:** Timely alerts for recurring subscriptions and dividend pay dates.
* **Day 10 Trial End Reminder:** Automated local notification scheduled 4 days before your 14-day free trial concludes (on Day 10), ensuring complete peace of mind to evaluate your subscription or cancel risk-free.
* **Custom Days & Times:** Choose which days of the week and exact hour/minute alerts are triggered.

---

## ☁️ Data Center, Cloud Backup & Privacy

* **1-Tap Cloud Backup:** Save complete portfolio backups (including historical vault snapshots) directly to **Google Drive, iCloud Drive, Nextcloud, Dropbox**, or local device storage.
* **JSON Portability:** Export and restore your complete portfolio with zero data loss.
* **Clean Slate Reset:** Switch between Demo Mode and your real portfolio or reset to a clean blank slate at any time.

---

## 👑 Membership Plans (Standard vs Premium)

MoneyVaults offers transparent, flexible pricing with an upfront **14-day risk-free free trial** on all subscription plans:

### 1. Subscription Tiers & Pricing
* **Monthly:** €5.00 / month (with 14-Day Free Trial)
* **3 Months:** €12.50 / quarter (Save 17%, with 14-Day Free Trial)
* **6 Months:** €20.00 / half-year (Save 33%, with 14-Day Free Trial)
* **Annual:** €35.00 / year (Save 42%, with 14-Day Free Trial)
* **Lifetime Access:** €60.00 one-time purchase (Pay once, enjoy permanent unlimited access forever)

### 2. Risk-Free Guarantee & Trial Reminders
* **14-Day Free Trial:** Start any subscription without paying upfront. If you cancel before the 14 days end via your Google Play Store account settings, you will never be charged.
* **Day 10 Local Reminder Alert:** The app automatically schedules a local reminder notification on Day 10 (4 days before renewal) so you never miss a billing decision.
* **Rewarded Video Passes (100% Free):** Placed prominently directly under the primary trial button on the Plan & Subscription screen, you can watch a short rewarded video to unlock a 1-minute full Premium pass (up to 5 passes per 24 hours) whenever you need quick access to an advanced calculator or projection chart.

### 3. Feature Comparison

| Feature | Standard Plan (Free) | MoneyVaults Premium |
| :--- | :---: | :---: |
| **Vault Creation** | Up to 5 Vaults | **Unlimited Vaults** |
| **Stock & Asset Vaults** | Included (within limit) | **Unlimited Asset Vaults** |
| **Dividend Tracker & Projections** | Included | **Unlimited Dividends & Projections** |
| **Recurring Rules & Alerts** | Up to 3 Active Rules | **Unlimited Active Rules** |
| **Interactive Calendar View** | ✅ Included | ✅ Included |
| **Compact & Expanded View Modes** | Expanded View | **Full Compact & Expanded Views** |
| **Discount Calculator** | ✅ Full Access | ✅ Full Access |
| **Financial Calculators Suite** | Read-Only Preview | **Full Interactive Access** |
| **Portfolio Allocation & Weights** | Basic Summary | **Full Visual Analytics** |
| **Evolution & Trend Curves** | Current Horizon Preview | **All Horizons (1M, 3M, YTD, 1Y, ALL)** |
| **Cloud & JSON Backup** | ✅ Included | ✅ Included |
| **Ad-Free Experience** | 5 Video Passes (1m each) / 24h | **Permanent Unrestricted Access** |

---

## ❓ Frequently Asked Questions (FAQ)

#### How do I transfer my data to a new phone?
1. On your old phone, open **Data Center** (cloud icon at top).
2. Tap **Backup to Cloud** or **Copy Backup to Clipboard**.
3. On your new phone, open MoneyVaults, open the **Data Center**, and tap **Restore from JSON**.

#### Does MoneyVaults connect to my bank account?
**No.** MoneyVaults is strictly offline-first. It never asks for banking credentials or online access tokens. You retain 100% control over all logged data.

---

## 📬 Support & Contact

* **Privacy & Legal Center:** [MoneyVaults Privacy Notice](https://compoundlysupport.github.io/MoneyVaults-Privacy/)
* **Support Email:** `compoundlysupport@gmail.com`
* **GitHub Repository:** [compoundlysupport/MoneyVaults-Privacy](https://github.com/compoundlysupport/MoneyVaults-Privacy)

---

*MoneyVaults: Smart Vaults • Compound Growth • Financial Freedom*
