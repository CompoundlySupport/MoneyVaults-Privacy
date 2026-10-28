# 📘 MoneyVaults: Finances & FIRE — Official User Guide & Manual

Welcome to **MoneyVaults: Finances & FIRE**, the modern, offline-first personal wealth management and financial freedom operating system.

---

## 📑 Table of Contents

1. [Philosophy & Architecture](#-philosophy--architecture)
2. [The Vaults Interaction Philosophy & Capital Flow Dynamics](#-the-vaults-interaction-philosophy--capital-flow-dynamics)
   - [The Philosophy of Mental Accounting & Purpose-Built Vaults](#the-philosophy-of-mental-accounting--purpose-built-vaults)
   - [Central Clearinghouse: The Single General Account Architecture](#central-clearinghouse-the-single-general-account-architecture)
   - [Capital Flow Architecture Diagram](#capital-flow-architecture-diagram)
   - [Comprehensive Capital Flow Interaction Matrix](#comprehensive-capital-flow-interaction-matrix)
   - [The Budget Surplus / Deficit Equation](#the-budget-surplus--deficit-equation)
3. [Quick Start Guide](#-quick-start-guide)
4. [Understanding Vault Types & Sorting](#-understanding-vault-types--sorting)
   - [Savings Goals & Emergency Funds](#savings-goals--emergency-funds)
   - [Dedicated Stock & Asset Vaults (PRU, Units & P&L)](#dedicated-stock--asset-vaults)
   - [Single General Account Architecture](#single-general-account-architecture)
   - [Vault Sorting & Instant Value Replacement](#vault-sorting--instant-value-replacement)
5. [Smart Budget & Two-Level Drilldown](#-smart-budget--two-level-drilldown)
   - [Budget Overview & Time Horizon Tabs](#budget-overview--time-horizon-tabs)
   - [Hierarchical Two-Level Drilldown (Direct Expenses vs Vault Transfers)](#hierarchical-two-level-drilldown)
   - [Future Forecast & Projected Dividend Inflows](#future-forecast--projected-dividend-inflows)
6. [Cash Flow, Calendar View & Transactions](#-cash-flow-calendar-view--transactions)
   - [Interactive Monthly Calendar View](#interactive-monthly-calendar-view)
   - [Fastfill One-Tap Logging](#fastfill-one-tap-logging)
   - [Cash Flow Independence ("Include in the cash flow" Switch & Filter)](#cash-flow-independence)
   - [Tag Manager & Multi-Criteria Filtering](#tag-manager--custom-filtering)
7. [Future Planned Transactions](#-future-planned-transactions)
8. [Recurring Transactions & Smart Alerts](#-recurring-transactions--smart-alerts)
9. [Dividend Tracker, Projections & Multi-Vault Sync](#-dividend-tracker--stock-vault-sync)
10. [Vaults Evolution & Trend Curves (1M, 3M, YTD, 1Y, ALL)](#-vaults-evolution--trend-curves)
    - [Evolution & Trend Curves](#1-evolution--trend-curves-1m-3m-ytd-1y-all)
    - [Monthly Inflow / Outflow & Cumulative Balance Modes](#2-monthly-inflow--outflow--cumulative-balance-modes)
11. [Portfolio Allocation & Weights](#-portfolio-allocation--weights)
12. [Financial Calculators Suite](#-financial-calculators-suite)
    - [Compound Growth & FIRE Calculator](#1-compound-growth--fire-calculator)
    - [Dividend Growth & Yield Calculator](#2-dividend-growth--yield-calculator)
    - [Loan Amortization & Early Payoff](#3-loan-amortization--early-payoff)
    - [Smart Discount Calculator](#4-smart-discount-calculator)
13. [Interactive Tutorials & Demo Mode](#-interactive-tutorials--demo-mode)
14. [Smart Reminders & Notifications](#-smart-reminders--notifications)
15. [Data Center, Cloud Backup & Privacy](#-data-center-cloud-backup--privacy)
16. [Membership Plans (Standard vs Premium)](#-membership-plans-standard-vs-premium)
17. [Frequently Asked Questions (FAQ)](#-frequently-asked-questions-faq)
18. [Support & Contact](#-support--contact)

---

## 🏛️ Philosophy & Architecture

MoneyVaults is built upon three non-negotiable principles:

* **100% Offline-First Privacy:** Your finances are your business. MoneyVaults does not require an account, does not connect to external financial servers, and never sells or uploads your data. All records remain stored locally on your device.
* **Mathematical Precision:** No ambiguous projections. Every compound growth curve, loan amortization schedule, historical evolution curve, and portfolio weighting formula is built on transparent financial math.
* **Frictionless Daily Tracking:** With customizable **Fastfill** buttons, auto-selected quick update inputs, and an interactive **Calendar View**, logging a daily transaction or portfolio update takes less than two seconds.

---

## 🔄 The Vaults Interaction Philosophy & Capital Flow Dynamics

MoneyVaults avoids the pitfall of traditional budgeting apps that lump all liquid capital into a single unorganized bucket. Instead, it utilizes an advanced **multi-vault mental accounting framework** designed to balance immediate lifestyle needs against long-term compounding growth.

<a id="the-philosophy-of-mental-accounting--purpose-built-vaults"></a>
### 1. The Philosophy of Mental Accounting & Purpose-Built Vaults
Traditional financial tracking often causes anxiety because money meant for living expenses is mixed with emergency reserves or stock purchases. MoneyVaults solves this by compartmentalizing money into dedicated vaults:
* **Operational Liquidity (General Account):** Covers daily life (groceries, dining, rent, bills).
* **Guaranteed Peace of Mind (Emergency Fund):** Preserves a designated runway (3–12 months of living expenses) shielded from daily spending.
* **Goal-Directed Capital (Piggy Banks):** Ring-fenced savings for targeted milestones (vehicles, holidays, home down payment).
* **Wealth Engines (Investments & Stocks):** Compounding vehicles (ETFs, index funds, dividend stocks, crypto) that generate capital gains and passive income.

<a id="central-clearinghouse-the-single-general-account-architecture"></a>
### 2. Central Clearinghouse: The Single General Account Architecture
The **General Account** operates as the central clearinghouse of your entire financial life:
* All external income (such as monthly salaries, bonuses, or freelance income) flows into the General Account.
* All routine living expenses exit directly from the General Account.
* When you save money or invest, capital moves **out** of the General Account and **into** the respective target vault.
* When you withdraw money from savings or reserves to cover an unexpected expense, capital moves **out** of the reserve vault and **back into** the General Account.

> [!IMPORTANT]
> **Single General Account Rule:** To maintain unambiguous mathematical integrity in budget calculations, cash flow surplus tracking, and inter-vault transfers, MoneyVaults features **strictly one General Account**. Additional vaults can be created without limit for Emergency Reserves, Piggy Banks, Investments, and Stock Assets, but all operational living cash flows through the single clearinghouse.

<a id="capital-flow-architecture-diagram"></a>
### 3. Capital Flow Architecture Diagram

The flow of funds between the external world, your General Account, and your specialized wealth vaults follows a clear, predictable circuit:

```mermaid
flowchart TD
    ExternalIncome["💰 External Income<br/>(Salary, Freelance, Business)"] -->|Inflow (+)| GA["💳 General Account<br/>(Operational Living Budget)"]
    GA -->|Outflow (-)| LivingExpenses["🛒 Living Expenses<br/>(Rent, Groceries, Dining, Bills)"]

    GA -->|Capital Allocation (Outflow)| Reserves["🛡️ Savings & Reserves<br/>(Emergency Fund, Piggy Banks)"]
    Reserves -->|Capital Drawdown (Inflow)| GA

    GA -->|Buy Trades: deductFromIncome| Assets["📈 Asset & Equity Vaults<br/>(Stocks, ETFs, Crypto, Real Estate)"]
    Assets -->|Sell Proceeds: deductFromIncome| GA

    Dividends["💵 Dividend Payouts<br/>(Received & Projected)"] -->|Vault Inflow (+)| Assets
    Dividends -.->|Optional Cash Flow (+)| GA

    style GA fill:#0f172a,stroke:#0d9488,stroke-width:3px,color:#f8fafc
    style ExternalIncome fill:#064e3b,stroke:#10b981,stroke-width:2px,color:#f8fafc
    style LivingExpenses fill:#7f1d1d,stroke:#ef4444,stroke-width:2px,color:#f8fafc
    style Reserves fill:#1e3a8a,stroke:#3b82f6,stroke-width:2px,color:#f8fafc
    style Assets fill:#312e81,stroke:#6366f1,stroke-width:2px,color:#f8fafc
    style Dividends fill:#581c87,stroke:#a855f7,stroke-width:2px,color:#f8fafc
```

<a id="comprehensive-capital-flow-interaction-matrix"></a>
### 4. Comprehensive Capital Flow Interaction Matrix

Every event in MoneyVaults updates the corresponding vaults with strict mathematical consistency:

| Event / Operation | General Account (Operational) | Destination / Origin Vault | Budget Surplus / Deficit Impact | Vaults Monthly Evolution Mode |
| :--- | :--- | :--- | :--- | :--- |
| **Salary / External Income** | **+ Inflow** (Direct Income) | *None* | Increases Monthly Surplus | General Account: Inflow |
| **Everyday Living Expense** | **- Outflow** (Direct Expense) | *None* | Decreases Monthly Surplus | General Account: Outflow |
| **Deposit / Transfer to Vault** *(Piggy, Emergency, Investment)* | **- Outflow** (Capital Allocation) | **+ Inflow** (Capital Received) | Decreases General Cash | Destination Vault: Inflow |
| **Withdrawal / Return from Vault** *(e.g. from Emergency)* | **+ Inflow** (Capital Drawdown) | **- Outflow** (Capital Withdrawn) | Increases General Cash | Origin Vault: Outflow |
| **Asset / Stock Buy** *(`deductFromIncome = true`)* | **- Outflow** (Transfer to Asset) | **+ Inflow** (Units & Invested Capital) | Decreases General Cash | Asset Vault: Inflow |
| **Asset / Stock Sell** *(`deductFromIncome = true`)* | **+ Inflow** (Liquidation Proceeds) | **- Outflow** (Units Disposed) | Increases General Cash | Asset Vault: Outflow |
| **Asset / Stock Buy** *(`deductFromIncome = false`)* | *No Impact* (Pre-existing cash) | **+ Inflow** (Units & Invested Capital) | *Neutral* | Asset Vault: Inflow |
| **Received Dividend** *(Assigned to Asset Vault)* | *No Impact* (unless cash flow) | **+ Inflow** (Dividend Yield Earned) | *Neutral* (unless cash flow) | Asset Vault: Inflow |
| **Projected Dividend** *(Scheduled / Upcoming)* | *No Impact* | **Future Inflow Forecast** | Positive Future Inflow | Budget: Upcoming Inflow |

<a id="the-budget-surplus--deficit-equation"></a>
### 5. The Budget Surplus / Deficit Equation

In the **Budget** tab, the real operational performance of your month is measured specifically through the **General Account**:

$$\text{Budget Surplus / Deficit} = \text{Income} - \text{Direct Expenses} + (\text{Withdrawals from Vaults} - \text{Capital Allocated to Vaults})$$

This formulation guarantees that:
1. Moving money to your Emergency Fund or buying an ETF correctly reflects as capital leaving your everyday checking account.
2. Reimbursing yourself from savings correctly restores operational liquidity without distorting your regular employment income.
3. You know at any given moment whether your operational lifestyle generated excess cash or required dipping into reserves.

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

<a id="single-general-account-architecture"></a>
### Single General Account Architecture
* The **General Account** is created automatically as your operational default vault.
* To prevent accounting discrepancies in monthly budget surplus and inter-vault capital routing, creating additional General/Expense accounts is intentionally restricted. All operational living expenses and transfers flow through this unified account, while any number of additional Piggy Banks, Emergency Funds, Investment Vaults, and Asset Vaults can be created freely.

---

## 🧭 Smart Budget & Two-Level Drilldown

<a id="smart-budget--two-level-drilldown"></a>
The **Budget** screen provides complete forward-looking and historical transparency over where your money came from and where it went.

<a id="budget-overview--time-horizon-tabs"></a>
### 1. Budget Overview & Time Horizon Tabs
* **Monthly Horizon Selector:** Navigate effortlessly between **Past Months**, the **Current Month**, and the **Next Month / Future Forecast**.
* **Inflows vs Outflows Header:** View real-time visual progress bars showing your budgeted income vs actual received inflows, as well as budgeted expenses vs actual outflows.
* **Operational Surplus / Deficit Gauge:** Instantly spot whether your General Account closed (or is projected to close) with a positive cash surplus or a deficit based on living expenses and inter-vault allocations.

<a id="hierarchical-two-level-drilldown"></a>
### 2. Hierarchical Two-Level Drilldown (Direct Expenses vs Vault Transfers)
When inspecting the **General Account Outflows**, MoneyVaults separates operational lifestyle spending from wealth accumulation:

1. **Level 1 — High-Level Differentiation:**
   * **Direct Expenses:** All routine expenditures (Groceries, Dining, Utilities, Subscriptions, Housing).
   * **Vault Transfers (Grouped by Target Vault):** Distinct clusters for capital allocated to other vaults (e.g., "Emergency Fund", "Tech Stocks", "Vacation Piggy").
2. **Level 2 — Transaction & Tag Inspection:**
   * Tapping into **Direct Expenses** reveals the tag breakdown (e.g., `#groceries`, `#transport`, `#health`) with aggregated totals.
   * Tapping into a specific **Vault Transfer** (e.g. `Tech Stocks`) lists all individual purchase transfers made toward that holding.
   * **Protected Header Layout:** The drilldown header features a dedicated breadcrumb trail (`General Account › Outflows`) above the active category title and isolates the total amount badge on the right, completely eliminating text truncation and overlap across all screen densities.

<a id="future-forecast--projected-dividend-inflows"></a>
### 3. Future Forecast & Projected Dividend Inflows
When viewing **Next Month** or upcoming budget horizons:
* Upcoming planned transactions and recurring rules are automatically plotted.
* **Scheduled Dividend Inflows:** Recurring and scheduled dividends are calculated based on pay frequency and credited as forecasted inflows into their respective holding vaults, giving you a full, reliable projection of passive income and operational cash.

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

## 💰 Dividend Tracker, Projections & Multi-Vault Sync

<a id="-dividend-tracker--stock-vault-sync"></a>
Track and project passive income from equity holdings:
* **Log Dividends:** Record one-time special dividends or scheduled recurring dividends (monthly, quarterly, semi-annually, annually).
* **Stock Vault Integration:** Select your stock vault to automatically fetch current shares owned and calculate projected gross and net payouts.
* **Tax Withholding:** Specify tax withholding percentages (e.g. 15% or 28%) to forecast true take-home passive cash.
* **Payout Calendar:** View upcoming dividend dates and confirm received dividends directly into your Cash Flow balance.
* **Multi-Vault Inflow Integration:** Dividends confirmed into the portfolio are recognized as capital inflows in their respective vaults (Asset, Investment, or General Account). In the Smart Budget, upcoming scheduled dividends automatically feed the projected inflow forecast for their assigned vaults.
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

<a id="monthly-inflow--outflow--cumulative-balance-modes"></a>
### 2. Monthly Inflow / Outflow & Cumulative Balance Modes
* **Interactive Multi-Month Chart:** View stacked bar charts comparing vault performance over **3-Month** and **6-Month** horizons.
* **Three View Modes with Fluid Scrollable Pills:** Switch seamlessly between:
  * **Cumulative Balance:** Total wealth accumulated across all vaults.
  * **Monthly Inflows:** New capital deposited, shares bought, and dividends earned per vault.
  * **Monthly Outflows:** Capital withdrawn or liquidated per vault.
* **Responsive Pill Navigation:** Designed with modern, horizontally scrollable chips ensuring full, clear labels without text clipping in all languages.

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
