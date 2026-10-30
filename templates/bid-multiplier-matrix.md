# Ramadan Bid Multiplier Matrix by Hour (Dayparting)
| Time Window (KSA Time) | Activity Level | Bid Multiplier | Strategy |
| :--- | :--- | :--- | :--- |
| **04:00 - 08:00 (Fajr to Morning)** | Low | 0.70x | Throttle bids |
| **12:00 - 16:00 (Mid-day)** | Moderate | 1.00x | Standard baseline |
| **17:00 - 19:30 (Iftar Window)** | Dead Zone | 0.40x | Minimum bids (zero conversion) |
| **21:30 - 03:30 (Post-Tarawih to Suhoor)** | PEAK RUSH | 1.45x | Aggressive scaling & uncapped bids |
