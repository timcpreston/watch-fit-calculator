# Watch Fit Calculator 2.0

**A live geometric calculator based on the Watch Fit Geometry Framework.**

Enter your wrist measurements and watch specifications to instantly calculate ideal strap lengths, lateral overhang, and a real-time top-down visual of how your watch sits on your wrist.

→ **[Try the calculator](https://timcpreston.github.io/watch-fit-calculator/)**

---

## What it calculates

The calculator implements the **Watch Fit Vector** — a two-axis geometric expression of watch fit:

```
[ (C − L − ΣK) ÷ 2 , (D − W) ÷ 2 ]
```

| Output | Description |
|---|---|
| **6 o'clock strap length** | Ideal length for the buckle side |
| **12 o'clock strap length** | Ideal length for the fixed side |
| **Standard notation** | Combined strap spec (e.g. 83/68mm) |
| **Lateral overhang** | How far the case extends beyond the wrist edge |
| **Top-down view** | Real-time diagram showing wrist, case, and straps |

---

## Inputs

| Field | Variable | Notes |
|---|---|---|
| Wrist circumference | C | inches or mm |
| Wrist width | W | inches or mm |
| Lug-to-lug length | L | mm |
| Case diameter | D | mm |
| Lug width | LW | mm (for diagram) |
| Clasp footprint | K | mm (butterfly/deployment only) |
| Desired tail length | — | slider, 10–45mm |

---

## The Framework

This calculator is the interactive companion to the **Watch Fit Geometry Framework** — a series of published working papers formalizing the geometry of watch fit for the first time.

| Paper | DOI |
|---|---|
| Watch Dial Centering Formula | [10.5281/zenodo.20447375](https://doi.org/10.5281/zenodo.20447375) |
| Watch Case Overhang Formula | [10.5281/zenodo.20449108](https://doi.org/10.5281/zenodo.20449108) |
| Watch Fit Geometry Framework | [10.5281/zenodo.20496410](https://doi.org/10.5281/zenodo.20496410) |
| Watch Fit Vector | [10.5281/zenodo.20496426](https://doi.org/10.5281/zenodo.20496426) |
| Axis 3 — Strap Thickness (open) | [10.5281/zenodo.20514259](https://doi.org/10.5281/zenodo.20514259) |
| Watch Comfort Geometry Framework | [10.5281/zenodo.20514293](https://doi.org/10.5281/zenodo.20514293) |

All papers are open access under **CC BY 4.0**.

---

## Usage

No installation needed. The calculator is a single self-contained `index.html` file — open it in any browser or serve it from any static host.

---

## Author

**Tim Preston** — Watch Fit Geometry Framework  
*"The AI was the instrument. The curiosity was human."*

---

## License

CC BY 4.0 — free to use, share, and adapt with attribution.
