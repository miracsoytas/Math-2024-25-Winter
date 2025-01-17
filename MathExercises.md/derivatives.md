# Derivatives

## 1. Compute derivatives of functions

### **a) $y(x) = -3x + 3$**
- **Solution**: The derivative of a linear function $ax + b$ is $a$, as constants have a derivative of $0$.
- $y'(x) = -3$.

---

### **b) $y(x) = \pi x + \sin(1)$**
- **Solution**: $\pi x$ has a derivative $\pi$, and constants like $\sin(1)$ have a derivative of $0$.
- $y'(x) = \pi$.

---

### **c) $y(x) = 4 + \sin(2)$**
- **Solution**: Both $4$ and $\sin(2)$ are constants, so their derivative is $0$.
- $y'(x) = 0$.

---

### **d) $y(x) = 2x^3 - 3x^2 + 8x - 9$**
- **Solution**: Apply the power rule $\frac{d}{dx}x^n = n x^{n-1}$ to each term:
  - $\frac{d}{dx}(2x^3) = 6x^2$,
  - $\frac{d}{dx}(-3x^2) = -6x$,
  - $\frac{d}{dx}(8x) = 8$,
  - $\frac{d}{dx}(-9) = 0$.
- $y'(x) = 6x^2 - 6x + 8$.

---

### **e) $y(x) = 6x^{1/3}$**
- **Solution**: Apply the power rule $\frac{d}{dx}x^n = n x^{n-1}$:
  - $\frac{d}{dx}(x^{1/3}) = \frac{1}{3}x^{-2/3}$.
  - Multiply by $6$: $6 \cdot \frac{1}{3}x^{-2/3} = 2x^{-2/3}$.
- $y'(x) = 2x^{-2/3}$.

---

### **f) $y(x) = \sqrt{x}$**
- **Solution**: Recall that $\sqrt{x} = x^{1/2}$, and apply the power rule:
  - $\frac{d}{dx}x^{1/2} = \frac{1}{2}x^{-1/2} = \frac{1}{2\sqrt{x}}$.
- $y'(x) = \frac{1}{2\sqrt{x}}$.

---

### **g) $y(x) = \cos(x) + \sin(x)$**
- **Solution**: Differentiate each term:
  - $\frac{d}{dx}(\cos(x)) = -\sin(x)$,
  - $\frac{d}{dx}(\sin(x)) = \cos(x)$.
- $y'(x) = -\sin(x) + \cos(x)$.

---

### **h) $y(x) = 2\sin(x)\cos(x)$**
- **Solution**: Use the product rule $\frac{d}{dx}(uv) = u'v + uv'$:
  - $u = 2\sin(x)$, $v = \cos(x)$,
  - $u' = 2\cos(x)$, $v' = -\sin(x)$.
  - $y'(x) = 2\cos(x)\cos(x) + 2\sin(x)(-\sin(x)) = 2\cos^2(x) - 2\sin^2(x)$.
- $y'(x) = 2\cos^2(x) - 2\sin^2(x)$.

---

### **i) $y(x) = x\sin(x)$**
- **Solution**: Use the product rule:
  - $u = x$, $v = \sin(x)$,
  - $u' = 1$, $v' = \cos(x)$.
  - $y'(x) = 1 \cdot \sin(x) + x \cdot \cos(x) = \sin(x) + x\cos(x)$.
- $y'(x) = \sin(x) + x\cos(x)$.

---

### **j) $y(x) = (x + 1)(x + 1)$**
- **Solution**: Expand $y(x) = (x + 1)^2$, then apply the power rule:
  - $\frac{d}{dx}(x + 1)^2 = 2(x + 1)$.
- $y'(x) = 2(x + 1)$.

---

### **k) $y(x) = \frac{x}{x + 1}$**
- **Solution**: Use the quotient rule $\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{u'v - uv'}{v^2}$:
  - $u = x$, $v = x + 1$,
  - $u' = 1$, $v' = 1$.
  - $y'(x) = \frac{(1)(x + 1) - (x)(1)}{(x + 1)^2} = \frac{x + 1 - x}{(x + 1)^2} = \frac{1}{(x + 1)^2}$.
- $y'(x) = \frac{1}{(x + 1)^2}$.

---

## 2. Proofs

### **Prove $\frac{d}{dx}(\ln(\sin(x))) = \cot(x)$:**

- **Solution**: Use the chain rule $\frac{d}{dx}\ln(u) = \frac{1}{u}u'$:
  - $u = \sin(x)$, $u' = \cos(x)$,
  - $\frac{d}{dx}(\ln(\sin(x))) = \frac{1}{\sin(x)} \cdot \cos(x) = \cot(x)$.

---

## 3. Verification

### **For $f(x) = \cos(x)$, verify $f''(x) = -f(x)$:**

1. First derivative:
   - $f'(x) = -\sin(x)$.

2. Second derivative:
   - $f''(x) = -\cos(x)$.

3. Verification:
   - Since $f(x) = \cos(x)$,
   - $f''(x) = -f(x)$.

---
