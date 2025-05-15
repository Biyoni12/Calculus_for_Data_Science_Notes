# 📘 Functions – Calculus Foundations for Data Science

This section covers essential concepts related to functions, a foundation for learning calculus. Topics include the definition of a function, different types of functions (polynomial, rational, trigonometric, etc.), and special classes such as exponential and logarithmic functions.

---

## 1. What is Calculus?

- **Calculus** is the mathematical study of continuous change.
- It focuses on two main areas:
  - **Differential Calculus** – concerned with the rate of change (slopes, derivatives).
  - **Integral Calculus** – concerned with accumulation (areas under curves).
- Widely used in data science for:
  - Understanding trends in data
  - Optimization problems
  - Modeling continuous processes

---

## 2. What is a Function?

- A **function** is a relation where each input has exactly one output.
- Notation:  
  - \( f(x) = x^2 \), where:
    - \( f \): function name
    - \( x \): input (independent variable)
    - \( f(x) \): output (dependent variable)
- Domain: all possible inputs  
- Range: all possible outputs
- Used in data science to model relationships between variables.

---

## 3. Types of Functions

- **Linear Functions**: \( f(x) = mx + b \)
  - Graph is a straight line.
- **Quadratic Functions**: \( f(x) = ax^2 + bx + c \)
  - Graph is a parabola.
- **Cubic Functions**: \( f(x) = ax^3 + bx^2 + cx + d \)
- **Rational Functions**: Ratio of two polynomials.
  - Example: \( f(x) = \frac{1}{x} \)
- **Piecewise Functions**: Defined by different expressions based on input intervals.

---

## 4. Polynomial and Rational Functions

### Polynomial Functions:
- Composed of terms with non-negative integer powers.
- General form:  
  \( f(x) = a_nx^n + a_{n-1}x^{n-1} + \dots + a_0 \)
- Smooth and continuous curves.
- Degree determines the shape and number of turning points.

### Rational Functions:
- Ratio of two polynomials.
- Can have **asymptotes**:
  - Vertical asymptotes: where the denominator = 0.
  - Horizontal/oblique asymptotes: behavior as \( x \to \infty \)

---

## 5. Inverse Functions

- The **inverse** of a function “undoes” the original.
- Notation:  
  \( f^{-1}(x) \) is the inverse of \( f(x) \)
- A function has an inverse **only if it is one-to-one** (passes the horizontal line test).
- To find an inverse:
  1. Replace \( f(x) \) with \( y \)
  2. Swap \( x \) and \( y \)
  3. Solve for \( y \)

---

## 6. Trigonometric Functions

- Models periodic behavior (e.g., sound waves, seasons).
- Basic functions:
  - \( \sin(x) \), \( \cos(x) \), \( \tan(x) \)
- Key properties:
  - **Periodicity**: Repeats every \( 2\pi \) for sine/cosine.
  - **Amplitude**: Height of the wave.
  - **Phase shift**: Horizontal shift of the graph.
- Applications in signal processing, oscillations, etc.

---

## 7. Exponential and Logarithmic Functions

### Exponential Functions:
- Form: \( f(x) = a^x \), where \( a > 0 \) and \( a \ne 1 \)
- Rapid growth or decay.
  - Example: population growth, radioactive decay
- \( e^x \) is a special exponential function used frequently in calculus.

### Logarithmic Functions:
- Inverse of exponential functions.
- Form: \( f(x) = \log_a(x) \)
- \( \log_b(x) = y \) means \( b^y = x \)
- Properties:
  - \( \log(ab) = \log a + \log b \)
  - \( \log\left(\frac{a}{b}\right) = \log a - \log b \)
  - \( \log(a^n) = n \log a \)

---

> ✅ These function types form the groundwork for understanding limits, derivatives, and integrals in future calculus topics.

