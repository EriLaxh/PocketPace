# Concept Origin: PocketPace

## 1. The Core Problem: The "Human-Budgeting Gap"
Traditional personal finance tools are fundamentally broken for the everyday user. Applications like YNAB, Monarch, and Simplifi are built entirely on "Accounting Logic"—treating an individual's daily life like a corporate business ledger. They demand meticulous tracking of every single cent, flood the screen with overwhelming charts, and enforce hyper-rigid categories. 

This corporate-centric UX fails because it creates immense cognitive load and financial anxiety. PocketPace identifies this market blindspot as a **UX failure in the financial tech industry**, rather than a user discipline failure.

## 2. Low-Fidelity Sandbox Experimentation (The True Starting Line)
The empirical spark for PocketPace came from a real-world constraint while navigating a career transition from Penang to Kuala Lumpur, dealing with highly volatile daily variable spending.

To test if a radical UX simplification could fix financial tracking anxiety, an existing accounting application (**Cashew**) was weaponized as a sandboxed testing framework. 

* **The Methodology:** I consciously ignored 99% of Cashew's "accounting-first" features. Instead of tracking long-term assets, I forced the container to display an isolated **"Weekly TNG (Touch 'n Go) Balance"** (e.g., RM65.76 left of RM215).
* **The Core UI Test:** I focused entirely on a single behavioral metric: a horizontal progress bar showing the elapsed week alongside a dynamically calculated real-time indicator: *"You can spend RM XX/day for X more days"*
* **The Behavioral Result:** By focusing entirely on this hyper-focused weekly slice, the mental barrier to tracking evaporated. It transformed budgeting from an institutional chore into a low-stress, sustainable lifestyle game.

## 3. The Shift to Product Architecture
The sandbox test proved that the **Weekly Sprint** works brilliantly as a behavioral interface. However, real-world usage quickly exposed a critical mechanical limitation: **Leakage**. 

While the weekly tracking managed high-frequency food and grocery spending perfectly, unexpected, irregular monthly anomalies (like an urgent trip to hardware stores like Mr. DIY) would completely blow the weekly gauge. This forced the realization that a pure weekly tracker requires a hidden structural architecture underneath it to safeguard the user's psychological momentum.
