# 2D FitzHugh-Nagumo Equation: Spirals and Turing Patterns

This notebook solves the 2D FitzHugh-Nagumo model, a system of reaction-diffusion equations describing neuronal excitation, using the Finite Difference Method (FDM).

$$ 
\begin{aligned}
\frac{\partial u}{\partial t} &= D_u \Delta u + \lambda u - u^3 - \kappa - \sigma v \\
\frac{\partial v}{\partial t} &= \frac{1}{\tau} (D_v \Delta v + u - v)
\end{aligned}
$$

**Domain:** $(x,y) \in [-2, 2] \times [-2, 2]$, $t \in [0, T]$

**Boundary Conditions:** Periodic/Neumann on the spatial domain.

By adjusting the parameters and initial conditions, the model generates the following striking patterns.

<img width="971" height="425" alt="fn_turing" src="https://github.com/user-attachments/assets/8ddcd294-b83d-4ba4-8fe2-069416948994" />


https://github.com/user-attachments/assets/b496c861-f0b9-4e9d-b309-1702b5836b47

<img width="971" height="425" alt="fn_spiral" src="https://github.com/user-attachments/assets/74e28687-5a71-474b-8485-085003e1d41d" />


https://github.com/user-attachments/assets/6bf6f940-c45d-43b5-98aa-fcefab1f853e

<img width="971" height="425" alt="fn_steady_spiral" src="https://github.com/user-attachments/assets/cd1eb4b9-9658-41b4-a1c5-04d5af4fffc2" />


https://github.com/user-attachments/assets/15bd662f-5b22-4322-8027-00b97c311da0

