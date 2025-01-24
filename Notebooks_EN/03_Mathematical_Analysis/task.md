# Solutions to the Problems

## 1. \( y'(x) = y \)

This differential equation is a **separable differential equation**. Let’s solve it step by step:

---

### Step 1: Rewrite the equation
The equation can be written as:
$$
\frac{dy}{dx} = y
$$

---

### Step 2: Separate the variables
Separate terms involving \( y \) and \( x \):
$$
\frac{1}{y} \, dy = dx
$$

---

### Step 3: Integrate both sides
Integrate both sides:
$$
\int \frac{1}{y} \, dy = \int dx
$$

- Left-hand side:
$$
\int \frac{1}{y} \, dy = \ln|y|
$$

- Right-hand side:
$$
\int dx = x + C
$$

This gives:
$$
\ln|y| = x + C
$$

---

### Step 4: Solve for \( y \)
Exponentiate both sides to isolate \( y \):
$$
|y| = e^{x + C} = e^C e^x
$$

Here, we substitute \( e^C \) with \( C_1 \) (a positive constant):
$$
|y| = C_1 e^x
$$

Finally, remove the absolute value:
$$
y = Ce^x
$$
where \( C \) is any real constant.

---

### Solution:
$$
y = Ce^x
$$

---

## 2. \( y'(x) = \frac{1}{2y(x)} \)

This is also a **separable differential equation**. Let’s solve it step by step:

---

### Step 1: Rewrite the equation
The equation can be written as:
$$
\frac{dy}{dx} = \frac{1}{2y}
$$

---

### Step 2: Separate the variables
Separate terms involving \( y \) and \( x \):
$$
2y \, dy = dx
$$

---

### Step 3: Integrate both sides
Integrate both sides:
$$
\int 2y \, dy = \int dx
$$

- Left-hand side:
$$
\int 2y \, dy = y^2
$$

- Right-hand side:
$$
\int dx = x + C
$$

This gives:
$$
y^2 = x + C
$$

---

### Step 4: Solve for \( y \)
Take the square root of both sides to isolate \( y \):
$$
y = \pm \sqrt{x + C}
$$

---

### Solution:
$$
y = \pm \sqrt{x + C}
$$

---

## Final Results:
1. For \( y'(x) = y \):
$$
y = Ce^x
$$

2. For \( y'(x) = \frac{1}{2y(x)} \):
$$
y = \pm \sqrt{x + C}
$$
