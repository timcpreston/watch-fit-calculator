[README.md](https://github.com/user-attachments/files/28285864/README.md)
# ⊕ Watch Dial Centering Formula

**A geometric formula for perfectly centered watch dial placement on the wrist.**

---

## The Formula

```
(C − L) ÷ 2 = ideal functional strap length
```

| Variable | Definition |
|---|---|
| **C** | Wrist circumference in mm (measured with a soft tape) |
| **L** | Lug-to-lug distance in mm (springbar to springbar) |

Apply the result equally to both the **6 o'clock strap** (long blade, hole side) and the **12 o'clock strap** (short blade, buckle side). When both functional lengths are equal, the dial centers itself.

> **Note:** The 6 o'clock strap's total physical length = `(C − L) ÷ 2 + desired tail length`. The tail is personal preference only — it does not affect centering.

---

## Bonus Insight: The Sweet Spot Ratio

```
C × 0.10 to 0.15 = ideal lug-to-lug range
```

When the lug-to-lug distance is 10–15% of wrist circumference, the watch has ideal visual proportion and enough strap on each side to feel secure and balanced.

---

## The Calculator

**Live version:** https://timcpreston.github.io/watch-dial-centering-formula/

**Inputs:**
- Wrist circumference (mm or inches)
- Lug-to-lug distance (mm)
- Desired tail length (10–60mm slider)

**Outputs:**
- 6 o'clock strap length in mm
- 12 o'clock strap length in mm
- Standard industry notation (e.g. 115/75)
- Lug-to-lug arc coverage with sweet spot indicator

---

## Full Article

- **Medium:** (https://medium.com/@timcpreston/the-watch-dial-centering-formula-f33063ae027f)
- **Citable DOI (Zenodo):** [10.5281/zenodo.20389138](https://doi.org/10.5281/zenodo.20389138)

---

## Why This Formula Exists

Watch dials slide off-center because stock straps ship with unequal functional lengths — the 6 o'clock strap is longer than it needs to be, pushing the case to the side. The fix isn't removing links from both sides equally (that preserves the incorrect ratio). The fix is equalizing the functional length of both straps using the geometry of the wrist itself.

This formula was derived from first principles. A thorough search found no prior published documentation of this relationship in English or otherwise.

---

## Standard Strap Notation

Watch straps are listed as **long/short** (e.g., `115/75mm`) where:
- The **first number** = 6 o'clock strap (long blade, hole side)
- The **second number** = 12 o'clock strap (short blade, buckle side)

The 6 o'clock strap is always longer in practice only because of tail length — not because of any intentional ratio. The conventional 55/45 split has no geometric basis and actually assigns the longer length to the wrong side.

---

## Integration

The calculator is self-contained HTML/CSS/JavaScript and embeddable anywhere. Watch retailers and database operators are welcome to integrate it. The formula itself is free for any use with attribution.

---

## Author

**Timothy C. Preston** — 2026

Derived in conversation with Claude (Anthropic), which also assisted with diagrams, structure, and the calculator build. The question, the curiosity, and the principal investigation were entirely human.

Inspired by *The Watch Bros*, whose asymmetric sizing video first pointed toward the right question.

---

## License

Creative Commons Attribution 4.0 International (CC BY 4.0)

You are free to use, share, adapt, and build on this work for any purpose — including commercial — as long as you give appropriate credit.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20389138.svg)](https://doi.org/10.5281/zenodo.20389138)
