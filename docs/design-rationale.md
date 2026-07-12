# Design Rationale: PocketPace

## 1. The Anti-Accounting Manifesto
PocketPace operates on a **Behavioral Design Framework**. The engineering priority is to keep complex mathematics completely hidden behind the backend code, providing the user with empathetic, intuitive interface gauges rather than cold, corporate analytical spreadsheets.

## 2. Evolution of the Architecture: The 3-Tier Safety Net Engine
To protect the integrity of the weekly sprint from irregular transaction leakage, the system evolved from a simple one-tier tracker into an integrated, automated **3-Tier Behavioral Engine**:

* **Tier 1: The Weekly Sprint (The Primary Interface):** Based directly on the successful Cashew sandbox experiment. It isolates the "Variable Big Three" high-frequency spending categories: *Office/Essential Meals, Fun/Treats, and Groceries*. The UI remains focused 90% on this daily pace.
* **Tier 2: The Monthly Buffer (The Shock Absorber - Hidden):** A dedicated safeguard hidden behind a simple interface toggle. Unexpected, non-weekly variable anomalies are automatically deducted from this buffer rather than polluting the active weekly gauge, preventing the user from feeling like they "failed" their weekly budget.
* **Tier 3: Long-Term Vacation & Shopping Fund (The Reward - Hidden):** A motivational bucket designed to capture positive reinforcement from leftover funds.

### Hidden Backend Automation & Leftover Overflow Logic
To keep cognitive load low, all balancing math is handled completely behind the scenes via an automated flow:
* **One-Time Setup Confirmation:** The application prompts the user for *Net Pay* and *Fixed Monthly Obligations* (Rent, Bills, Insurance). The backend handles the subtraction to isolate the overall Discretionary Pot, showing a single confirmation page before hiding the math forever.
* **The 4.5-Week Safety Slider:** The app avoids complex "4.33 weeks per month" division. The backend automatically divides the discretionary pot by a conservative **4.5 weeks**. This nudges the user into a slightly tighter, safer weekly budget, creating a natural financial surplus/reward at the end of standard 4-week months.
* **The Automated Surplus Split:** At the Sunday midnight reset, the backend automatically takes any remaining weekly leftover and splits it 50/50, routing half to long-term savings and half to replenish the Tier 2 Monthly Buffer shock absorber.
