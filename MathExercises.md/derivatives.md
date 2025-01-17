# Derivatives

## 1. Compute derivatives of functions

### **a) $y(x) = -3x + 3$**
- **Solution**: The derivative of a linear function $ax + b$ is $a$, as constants have a derivative of $0$.
- $y'(x) = -3$.
<img width="668" alt="Ekran Resmi 2025-01-17 11 26 19" src="https://github.com/user-attachments/assets/6f5312ab-5c83-4890-9cd9-0ce63cdb50b4" />

---

### **b) $y(x) = \pi x + \sin(1)$**
- **Solution**: $\pi x$ has a derivative $\pi$, and constants like $\sin(1)$ have a derivative of $0$.
- $y'(x) = \pi$.
<img width="670" alt="Ekran Resmi 2025-01-17 11 26 44" src="https://github.com/user-attachments/assets/d6b767bd-294c-46cd-a215-72bb30d2b2ce" />

---

### **c) $y(x) = 4 + \sin(2)$**
- **Solution**: Both $4$ and $\sin(2)$ are constants, so their derivative is $0$.
- $y'(x) = 0$.
<img width="659" alt="Ekran Resmi 2025-01-17 11 27 15" src="https://github.com/user-attachments/assets/e4d3bcca-a6de-425e-8b9f-cadb0c31200d" />

---

### **d) $y(x) = 2x^3 - 3x^2 + 8x - 9$**
- **Solution**: Apply the power rule $\frac{d}{dx}x^n = n x^{n-1}$ to each term:
  - $\frac{d}{dx}(2x^3) = 6x^2$,
  - $\frac{d}{dx}(-3x^2) = -6x$,
  - $\frac{d}{dx}(8x) = 8$,
  - $\frac{d}{dx}(-9) = 0$.
- $y'(x) = 6x^2 - 6x + 8$.
<img width="664" alt="Ekran Resmi 2025-01-17 11 27 43" src="https://github.com/user-attachments/assets/54042a84-870c-4753-bac9-54e87279a414" />

---

### **e) $y(x) = 6x^{1/3}$**
- **Solution**: Apply the power rule $\frac{d}{dx}x^n = n x^{n-1}$:
  - $\frac{d}{dx}(x^{1/3}) = \frac{1}{3}x^{-2/3}$.
  - Multiply by $6$: $6 \cdot \frac{1}{3}x^{-2/3} = 2x^{-2/3}$.
- $y'(x) = 2x^{-2/3}$.
<img width="662" alt="Ekran Resmi 2025-01-17 11 28 09" src="https://github.com/user-attachments/assets/7c121ac1-6a00-4e09-8a5f-6f44d09d1f06" />

---

### **f) $y(x) = \sqrt{x}$**
- **Solution**: Recall that $\sqrt{x} = x^{1/2}$, and apply the power rule:
  - $\frac{d}{dx}x^{1/2} = \frac{1}{2}x^{-1/2} = \frac{1}{2\sqrt{x}}$.
- $y'(x) = \frac{1}{2\sqrt{x}}$.
<img width="667" alt="Ekran Resmi 2025-01-17 11 28 31" src="https://github.com/user-attachments/assets/07e2bd05-b0a8-447a-8d84-f48b17ba4bc2" />

---

### **g) $y(x) = \cos(x) + \sin(x)$**
- **Solution**: Differentiate each term:
  - $\frac{d}{dx}(\cos(x)) = -\sin(x)$,
  - $\frac{d}{dx}(\sin(x)) = \cos(x)$.
- $y'(x) = -\sin(x) + \cos(x)$.
<img width="663" alt="Ekran Resmi 2025-01-17 11 28 54" src="https://github.com/user-attachments/assets/34f86548-6aa1-4e81-8706-6365081067c4" />


---

### **h) $y(x) = 2\sin(x)\cos(x)$**
- **Solution**: Use the product rule $\frac{d}{dx}(uv) = u'v + uv'$:
  - $u = 2\sin(x)$, $v = \cos(x)$,
  - $u' = 2\cos(x)$, $v' = -\sin(x)$.
  - $y'(x) = 2\cos(x)\cos(x) + 2\sin(x)(-\sin(x)) = 2\cos^2(x) - 2\sin^2(x)$.
- $y'(x) = 2\cos^2(x) - 2\sin^2(x)$.

<img width="667" alt="Ekran Resmi 2025-01-17 11 29 28" src="https://github.com/user-attachments/assets/f656f7f4-4665-4f0e-9bf4-42a22123bf6f" />

---

### **i) $y(x) = x\sin(x)$**
- **Solution**: Use the product rule:
  - $u = x$, $v = \sin(x)$,
  - $u' = 1$, $v' = \cos(x)$.
  - $y'(x) = 1 \cdot \sin(x) + x \cdot \cos(x) = \sin(x) + x\cos(x)$.
- $y'(x) = \sin(x) + x\cos(x)$.

<img width="667" alt="Ekran Resmi 2025-01-17 11 30 02" src="https://github.com/user-attachments/assets/129dbb8e-8d29-40f3-847b-f2cfacdfa77d" />

---

### **j) $y(x) = (x + 1)(x + 1)$**
- **Solution**: Expand $y(x) = (x + 1)^2$, then apply the power rule:
  - $\frac{d}{dx}(x + 1)^2 = 2(x + 1)$.
- $y'(x) = 2(x + 1)$.

<img width="665" alt="Ekran Resmi 2025-01-17 11 30 23" src="https://github.com/user-attachments/assets/83b4b179-8cab-424f-bf67-47541ea1a3c0" />

---

### **k) $y(x) = \frac{x}{x + 1}$**
- **Solution**: Use the quotient rule $\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{u'v - uv'}{v^2}$:
  - $u = x$, $v = x + 1$,
  - $u' = 1$, $v' = 1$.
  - $y'(x) = \frac{(1)(x + 1) - (x)(1)}{(x + 1)^2} = \frac{x + 1 - x}{(x + 1)^2} = \frac{1}{(x + 1)^2}$.
- $y'(x) = \frac{1}{(x + 1)^2}$.

<img width="660" alt="Ekran Resmi 2025-01-17 11 30 50" src="https://github.com/user-attachments/assets/443f4fc8-d9b2-46f6-ac9b-389ea9600138" />

---

## 2. Proofs

### **Prove $\frac{d}{dx}(\ln(\sin(x))) = \cot(x)$:**

- **Solution**: Use the chain rule $\frac{d}{dx}\ln(u) = \frac{1}{u}u'$:
  - $u = \sin(x)$, $u' = \cos(x)$,
  - $\frac{d}{dx}(\<img width="639" alt="Ekran Resmi 2025-01-17 11 31 27" src="https://github.com/user-attachments/assets/e626c12b-7449-4643-b923-88e692ac9bc6" />
ln(\sin(x))) = \frac{1}{\sin(x)} \cdot \cos(x) = \cot(x)$.

---

## 3. Verification

### **For $f(x) = \cos(x)$, verify $f''(x) = -f(x)$:**
<img width="655" alt="Ekran Resmi 2025-01-17 11 32 01" src="https://github.com/user-attachments/assets/e9f85971-93f6-4e12-9f1b-a500f7bc3529" />



1. First derivative:
   - $f'(x) = -\sin(x)$.

2. Second derivative:
   - $f''(x) = -\cos(x)$.

3. Verification:
   - Since $f(x) = \cos(x)$,
   - $f''(x) = -f(x)$.

---
