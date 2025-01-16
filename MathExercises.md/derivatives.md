# Derivatives

## 1. Compute derivatives of functions:

```math
y(x) = -3x + 3 \implies y'(x) = -3
```

```math
y(x) = \pi x + \sin(1) \implies y'(x) = \pi
```

```math
y(x) = 4 + \sin(2) \implies y'(x) = 0
```

```math
y(x) = 2x^3 - 3x^2 + 8x - 9 \implies y'(x) = 6x^2 - 6x + 8
```

```math
y(x) = 6x^{1/3} \implies y'(x) = 2x^{-2/3}
```

```math
y(x) = \sqrt{x} \implies y'(x) = \frac{1}{2\sqrt{x}}
```

```math
y(x) = \cos(x) + \sin(x) \implies y'(x) = -\sin(x) + \cos(x)
```

```math
y(x) = 2\sin(x)\cos(x) \implies y'(x) = 2\cos^2(x) - 2\sin^2(x)
```

```math
y(x) = x\sin(x) \implies y'(x) = \sin(x) + x\cos(x)
```

```math
y(x) = (x + 1)(x + 1) \implies y'(x) = 2(x + 1)
```

```math
y(x) = \frac{x}{x + 1} \implies y'(x) = \frac{1}{(x + 1)^2}
```

```math
y(x) = (x + 1)\exp(x) \implies y'(x) = \exp(x)(x + 2)
```

```math
y(x) = \sin(x^2) \implies y'(x) = 2x\cos(x^2)
```

```math
y(x) = \exp(-2x) \implies y'(x) = -2\exp(-2x)
```

```math
y(x) = \frac{1}{\sin(x + 1)} \implies y'(x) = -\frac{\cos(x + 1)}{\sin^2(x + 1)}
```

```math
y(x) = \sqrt{2x + 1} \implies y'(x) = \frac{1}{\sqrt{2x + 1}}
```

## 2. Prove:

```math
\frac{d}{dx}(\ln(\sin(x))) = \cot(x)
```

### Proof:

Using the chain rule:

```math
\frac{d}{dx}(\ln(\sin(x))) = \frac{1}{\sin(x)} \cdot \cos(x) = \cot(x)
```

## 3. For \(f(x) = \cos(x)\), verify that \(f''(x) = -f(x)\).

### Verification:

First derivative:

```math
f'(x) = -\sin(x)
```

Second derivative:

```math
f''(x) = -\cos(x)
```

Since \(f(x) = \cos(x)\), it follows that:

```math
f''(x) = -f(x)
