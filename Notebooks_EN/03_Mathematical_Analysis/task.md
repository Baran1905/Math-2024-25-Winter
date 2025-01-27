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
# Solving First-Order ODEs Using the Method of Separation of Variables

---

## Problem 1: $$\frac{dy}{dx} = \frac{x}{y}$$

1. Rewrite the equation:  
   $$y \, dy = x \, dx.$$

2. Integrate both sides:  
   $$\int y \, dy = \int x \, dx.$$

   The integrals give:  
   $$\frac{y^2}{2} = \frac{x^2}{2} + C.$$

3. Simplify:  
   $$y^2 = x^2 + 2C.$$

   Let $$2C = k$$:  
   $$y^2 = x^2 + k.$$

4. Solve for $$y$$:  
   $$y = \pm \sqrt{x^2 + k}.$$

**Solution:**  
$$y = \pm \sqrt{x^2 + k}.$$

---

## Problem 2: $$\frac{dy}{dx} = \frac{y}{x}$$

1. Rewrite the equation:  
   $$\frac{dy}{y} = \frac{dx}{x}.$$

2. Integrate both sides:  
   $$\int \frac{1}{y} \, dy = \int \frac{1}{x} \, dx.$$

   The integrals give:  
   $$\ln|y| = \ln|x| + C.$$

3. Exponentiate both sides:  
   $$|y| = e^C |x|.$$

   Let $$e^C = k$$:  
   $$y = kx \quad \text{or} \quad y = -kx.$$

**Solution:**  
$$y = Cx, \quad \text{where } C \text{ is a constant.}$$

---

## Problem 3: $$\frac{dy}{dx} = xy$$

1. Rewrite the equation:  
   $$\frac{dy}{y} = x \, dx.$$

2. Integrate both sides:  
   $$\int \frac{1}{y} \, dy = \int x \, dx.$$

   The integrals give:  
   $$\ln|y| = \frac{x^2}{2} + C.$$

3. Exponentiate both sides:  
   $$|y| = e^C e^{\frac{x^2}{2}}.$$

   Let $$e^C = k$$:  
   $$y = k e^{\frac{x^2}{2}} \quad \text{or} \quad y = -k e^{\frac{x^2}{2}}.$$

**Solution:**  
$$y = Ce^{\frac{x^2}{2}}, \quad \text{where } C \text{ is a constant.}$$

---

## Summary of Solutions

1. $$\frac{dy}{dx} = \frac{x}{y}$$:  
   $$y = \pm \sqrt{x^2 + k}.$$

2. $$\frac{dy}{dx} = \frac{y}{x}$$:  
   $$y = Cx.$$

3. $$\frac{dy}{dx} = xy$$:  
   $$y = Ce^{\frac{x^2}{2}}.$$

---
