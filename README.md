# Romeo and Juliet – Mathematical Modeling Project

This project was carried out as part of a university assignment in **Mathematics and Modeling**.  
It analyses the emotional dynamics between *Romeo and Juliet* using a system of differential equations, exploring several relational scenarios inspired by **Turnea et al. (2024)**.

The notebook [`mathmodelingproject.ipynb`](./mathmodelingproject.ipynb) contains the full implementation of the model, including:
- Analytical stability analysis  
- Symbolic and numerical solutions  
- Graphical visualisations (time evolution and phase-plane trajectories)

The theoretical reference for this work is provided in [`Turnea-et-al_2024.pdf`](./Turnea-et-al_2024.pdf).

---

## How to Run

1. Open the notebook **`mathmodelingproject.ipynb`**. 
2. Run all cells sequentially to reproduce the results and figures.  

All computations were performed in **Python** using:
- `NumPy` for algebraic and matrix operations  
- `SciPy` (`solve_ivp`) for differential equation integration  
- `SymPy` for symbolic analysis  
- `Matplotlib` for plotting  

---

## Description

The model describes the evolution of the emotional states of Romeo and Juliet:
\[
\begin{cases}
\dot{x} = a x + b y \\
\dot{y} = c x + d y
\end{cases}
\]

Each parameter \((a, b, c, d)\) defines a distinct **relational scenario**, determining whether the system is **stable**, **unstable**, or **oscillatory**.  
The project replicates and extends several cases described in *Turnea et al. (2024)*, including:
- *Mutual and increasing love*  
- *Rollercoaster relationship*  
- *Fading love*  
- *Unrequited love*

---

## Author

This notebook was developed as part of a university project on **Mathematical Modeling and Dynamical Systems**.
Léa Pons and Axelle Rabanis
