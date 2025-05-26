# φ vs η₀ Dataset for Open Channel Flow Design

## Description

This dataset captures the variation of the dimensionless function:

\[
\phi = f(\eta_0, m)
\]

where:

- **ϕ** is a dimensionless parameter defined as:  
  \[
  \phi = \frac{nQ}{\sqrt{S} \, B^{8/3}}
  \]

- **η₀ = y/B** is the ratio of the normal depth (*y*) to the bottom width (*B*).

- **m** represents the side slope factor (horizontal : vertical) of the channel.

---

This dataset is useful while designing **channels for irrigation in open channel flow**. It provides a **convenient aid to determine the normal depth** in both **rectangular (m=0)** and **trapezoidal (m>0)** channels.

---

## How This Dataset Was Created

The values were generated using Finite Element Method (FEM) techniques.

##  Dataset Format

The Excel file contains:

- A column for *η₀ (y/B)*.
- Multiple columns for *ϕ values*, each corresponding to a different side slope:
  - `m = 0` → Rectangular channel  
  - `m > 0` → Trapezoidal channels (e.g., m = 1, 1.5, 2, 2.5)

---

##  Source & Attribution

This dataset was inspired by concepts presented in the book:

> *K. Subramanya – Flow in Open Channels*


## License

This dataset is made available under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to:
- Share — copy and redistribute the material in any medium or format  
- Adapt — remix, transform, and build upon the material for any purpose, even commercially

*As long as you give appropriate credit.*

---

## 📬 Contact

For questions or collaborations, feel free to reach out via GitHub or open an issue in this repository.
