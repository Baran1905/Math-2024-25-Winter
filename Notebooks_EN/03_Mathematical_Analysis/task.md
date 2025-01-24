# Solutions to First-Order Ordinary Differential Equations

---

## 1. $y'(x) = y$

This is a **separable differential equation**.

### Steps:

1. Rewrite the equation:  
   $$\frac{dy}{dx} = y$$

2. Separate the variables $y$ and $x$:  
   $$\frac{1}{y} \, dy = dx$$

3. Integrate both sides:  
   $$\int \frac{1}{y} \, dy = \int 1 \, dx$$

4. Solve the integrals:  
   $$\ln|y| = x + C$$  
   where $C$ is the constant of integration.

5. Exponentiate to eliminate the logarithm:  
   $$|y| = e^{x+C} = e^C \cdot e^x$$

6. Simplify, letting $C_1 = \pm e^C$:  
   $$y = C_1 e^x$$

**Solution:**  
$$y(x) = C_1 e^x$$  
where $C_1$ is an arbitrary constant.

---

## 2. $y'(x) = \frac{1}{2y(x)}$

This is also a **separable differential equation**.

### Steps:

1. Rewrite the equation:  
   $$\frac{dy}{dx} = \frac{1}{2y}$$

2. Separate the variables $y$ and $x$:  
   $$2y \, dy = dx$$

3. Integrate both sides:  
   $$\int 2y \, dy = \int 1 \, dx$$

4. Solve the integrals:  
   $$y^2 = x + C$$

5. Solve for $y$:  
   $$y = \pm\sqrt{x + C}$$

**Solution:**  
$$y(x) = \pm\sqrt{x + C}$$  
where $C$ is an arbitrary constant.