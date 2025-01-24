# Solutions

## 1. $$ y'(x) = y $$
This is a **separable differential equation**. Let's solve it step by step:

### Step 1: Rewrite the equation
$$ \frac{dy}{dx} = y $$
Separate the variables:
$$ \frac{1}{y} \, dy = dx $$

### Step 2: Integrate both sides
$$ \int \frac{1}{y} \, dy = \int 1 \, dx $$
$$ \ln|y| = x + C $$
Here, $C$ is the constant of integration.

### Step 3: Solve for $y$
Exponentiate both sides to remove the logarithm:
$$ |y| = e^{x+C} $$
$$ y = Ce^x $$
Here, $C = e^C$ absorbs the constant.

**Solution**:
$$ y(x) = Ce^x $$

---

## 2. $$ y'(x) = \frac{1}{2y(x)} $$
This is also a **separable differential equation**. Let's solve it step by step:

### Step 1: Rewrite the equation
$$ \frac{dy}{dx} = \frac{1}{2y} $$
Separate the variables:
$$ 2y \, dy = dx $$

### Step 2: Integrate both sides
$$ \int 2y \, dy = \int 1 \, dx $$
$$ y^2 = x + C $$
Here, $C$ is the constant of integration.

### Step 3: Solve for $y$
Take the square root of both sides:
$$ y = \pm \sqrt{x + C} $$

**Solution**:
$$ y(x) = \pm \sqrt{x + C} $$

---

## Summary of Solutions

1. For $$ y'(x) = y $$:
   $$ y(x) = Ce^x $$

2. For $$ y'(x) = \frac{1}{2y(x)} $$:
   $$ y(x) = \pm \sqrt{x + C} $$
