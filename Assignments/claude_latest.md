# Box Plot Interpretation: Time-of-Day Distribution by Crime Type

## Overview

This box plot visualizes **when** eight different crime types tend to occur throughout the day, based on a combined dataset of nearly **1.75 million incidents**. The y-axis represents the time of day (midnight to midnight), and the dashed reference line marks **noon (12:00)**. Each box captures the middle 50% of incidents (IQR), with the horizontal line inside showing the **median** occurrence time.

---

## Key Observations by Crime Type

### 🔴 Arson *(n = 6,804)*
- **Median:** ~11:30 (late morning)
- **IQR:** ~04:30–19:00 — the widest spread of any crime type
- Arson is highly unpredictable in timing, occurring across virtually all hours. The low median and wide IQR suggest a notable share of incidents happen in the early morning hours, consistent with deliberate nighttime/early-morning fires.

### 🟠 Burglary *(n = 146,948)*
- **Median:** ~13:00 (early afternoon)
- **IQR:** ~07:00–18:00
- Burglary skews toward **daytime hours**, peaking while residents are away at work. The distribution is relatively tight around business hours.

### 🟢 Assault *(n = 231,591)*
- **Median:** ~14:00 (mid-afternoon)
- **IQR:** ~08:00–19:00
- Assault is broadly distributed across the day but weighted toward the **afternoon and early evening**, likely reflecting social and recreational contexts.

### 🟣 Drug Offense *(n = 148,763)*
- **Median:** ~15:00 (mid-afternoon)
- **IQR:** ~11:00–18:00 — the **narrowest IQR** of all crime types
- Drug offenses are the most **time-concentrated** crime, heavily clustered in the **afternoon window**. This likely reflects patrol patterns and enforcement activity during peak daytime policing hours.

### 🟤 Robbery *(n = 76,951)*
- **Median:** ~15:00 (mid-afternoon)
- **IQR:** ~08:00–19:30
- Robbery mirrors assault in timing, peaking in the **afternoon**. The wide lower whisker suggests some early-morning incidents as well.

### ⬜ Vandalism *(n = 185,350)*
- **Median:** ~15:00 (mid-afternoon)
- **IQR:** ~08:00–19:30
- Very similar distribution to robbery, spread broadly across the day with a slight **afternoon lean**.

### 🟡 Larceny Theft *(n = 771,237)* *(largest dataset)*
- **Median:** ~15:30 (mid-afternoon)
- **IQR:** ~11:00–18:30
- The most reported crime in the dataset. Larceny is highly concentrated in **business/retail hours**, consistent with shoplifting and opportunistic theft when commercial activity peaks.

### 🔵 Motor Vehicle Theft *(n = 181,131)*
- **Median:** ~16:30 (late afternoon)
- **IQR:** ~11:00–19:30
- Has the **latest median** of all crime types, suggesting thefts often occur when vehicles are parked after commuting or during evening hours.

---

## Summary Table

| Crime Type         | Median Time | IQR Spread | Key Pattern |
|--------------------|-------------|------------|-------------|
| Arson              | ~11:30      | Very wide  | Unpredictable; notable early-AM activity |
| Burglary           | ~13:00      | Moderate   | Daytime, while homes are empty |
| Assault            | ~14:00      | Wide       | Afternoon/evening social contexts |
| Drug Offense       | ~15:00      | **Narrow** | Enforcement-driven afternoon cluster |
| Robbery            | ~15:00      | Wide       | Afternoon peak, some AM activity |
| Vandalism          | ~15:00      | Wide       | Broad daytime distribution |
| Larceny Theft      | ~15:30      | Moderate   | Retail/business hours |
| Motor Vehicle Theft| ~16:30      | Moderate   | Latest median; post-commute peak |

---

## Takeaways

1. **Most crimes peak in the afternoon (12:00–18:00)**, suggesting a strong link to daytime human activity and policing presence.
2. **Arson is a clear outlier** — its wide IQR and lower median indicate a unique pattern with significant nighttime/early-morning activity.
3. **Drug offenses are the most time-concentrated**, likely shaped by law enforcement patrol schedules rather than solely by offender behavior.
4. **Motor vehicle theft skews latest**, consistent with vehicles being left unattended after work or during evening outings.
5. The **lower whiskers extend to midnight (00:00)** for all crimes, confirming that no crime type is entirely absent from overnight hours.