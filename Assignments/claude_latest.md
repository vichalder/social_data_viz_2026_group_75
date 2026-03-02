# Time-of-Day Distribution by Crime Type — Analysis

## Overview

The visualization presents **box plots** (top) and **violin plots** (bottom) showing when eight types of crimes occur throughout the day, drawn from a combined dataset of nearly **1.75 million incidents**. The dashed reference line marks **noon (12:00)**.

---

## Key Findings by Crime Type

| Crime Type | n | Median Time | Notable Pattern |
|---|---|---|---|
| Arson | 6,804 | ~11:30 | Earlier/daytime skew |
| Burglary | 146,948 | ~13:00 | Moderate spread |
| Assault | 231,591 | ~14:30 | Afternoon–evening peak |
| Drug Offense | 148,763 | ~15:00 | Broad afternoon spread |
| Robbery | 76,951 | ~15:00 | Evening-heavy |
| Vandalism | 185,350 | ~15:30 | Wide spread, slight evening lean |
| Larceny Theft | 771,237 | ~15:30 | Afternoon concentration |
| Motor Vehicle Theft | 181,131 | ~16:30 | Latest median; evening peak |

---

## Observations

### 1. Arson Is an Outlier — Earlier in the Day
Arson has the **lowest median** (~11:30) and the **widest IQR** among all crime types. The violin plot reveals a relatively uniform spread across all hours, suggesting arson incidents are not tightly clustered around any particular time window.

### 2. Theft-Related Crimes Peak in the Afternoon–Evening
**Larceny Theft** (the largest category at 771K incidents), **Motor Vehicle Theft**, and **Robbery** all have medians in the **15:00–16:30** range. Their violin plots show pronounced bulges in the late afternoon and evening, consistent with higher foot traffic and opportunity windows after business hours.

### 3. Drug Offenses Have a Distinctive Bimodal Shape
The violin plot for **Drug Offenses** shows a notable **hourglass/narrow-waist shape** around midday, with denser clusters in the late morning and late afternoon. This suggests two activity windows, possibly tied to enforcement patterns or behavioral cycles.

### 4. Assault and Robbery Extend into Late Night
Both **Assault** and **Robbery** show wide upper tails in the violin plots, extending heavily toward **21:00–24:00**, reflecting well-established research linking violent crime to nighttime hours.

### 5. Vandalism Is Broadly Distributed
**Vandalism** has one of the widest spreads with a relatively flat violin shape, indicating it occurs throughout the entire day with no sharply dominant peak — though there is a slight evening lean.

---

## Summary

> Most crimes in this dataset are skewed toward the **afternoon and evening hours**, with medians ranging from ~11:30 (Arson) to ~16:30 (Motor Vehicle Theft). Violent crimes (Assault, Robbery) extend more heavily into **late-night hours**, while property crimes (Larceny, Motor Vehicle Theft) concentrate around the **afternoon–early evening** window. Arson is the notable exception, occurring more uniformly across all hours of the day.