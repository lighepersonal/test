# Calculus Formula Sheet (Unit 2: 2.1 to 2.10)

## Rates of change and the derivative
- Slope = Δy/Δx = (y₂ − y₁)/(x₂ − x₁)
- **AROC** on [a,b] = (f(b) − f(a))/(b − a) = (f(a+h) − f(a))/h = (f(x) − f(a))/(x − a). Slope of a **secant** line (2 points)
- **IROC** at x=a = lim_{h→0} (f(a+h) − f(a))/h = lim_{x→a} (f(x) − f(a))/(x − a). Slope of a **tangent** line (1 point)
- **Derivative:** f′(x) = lim_{h→0} (f(x+h) − f(x))/h
- Notation: f′(x) "f prime of x", y′ "y prime", dy/dx "dy dx", d/dx f(x)|ₓ₌ₐ (calculator: math → nDeriv)
- **f′(a) = m** (slope of the tangent at x=a)

## Lines
- Point-slope: y − y₁ = m(x − x₁)
- **Tangent line** at x=a: y − f(a) = f′(a)(x − a), where (x₁, y₁) = (a, f(a)) and m = f′(a)
- **Normal line:** perpendicular to the tangent at the point of tangency; slope = **negative reciprocal** = −1/f′(a)
- **Horizontal tangent:** f′(x) = 0 (slope 0)
- Estimating f′ from a table: f′(x) ≈ (f(b) − f(a))/(b − a) using points on either side of x (f must be continuous)

## Differentiability and continuity
- Not differentiable at: discontinuity (hole, jump), corner or cusp, vertical tangent
- Differentiable ⇒ continuous (TRUE). Continuous ⇒ differentiable (FALSE)
- Piecewise at x=c: (1) pieces equal at c (continuous), (2) derivatives of the pieces equal at c

## Roots, powers, exponent rules
- √x = x^(1/2); ∛x = x^(1/3); ⁿ√x = x^(1/n); ⁿ√(xᵐ) = x^(m/n)
- 1/xⁿ = x⁻ⁿ; 1/√x = x^(−1/2)
- xᵃ · xᵇ = xᵃ⁺ᵇ; xᵃ/xᵇ = xᵃ⁻ᵇ; (xᵃ)ᵇ = xᵃᵇ
- Rewrite roots and fractions as powers **before** differentiating

## Derivative rules
- Constant: d/dx c = 0
- Constant multiple: d/dx cx = c; d/dx (c·u) = c·du/dx
- Sum/Difference: d/dx (u ± v) = u′ ± v′
- **Power rule:** d/dx xⁿ = n·xⁿ⁻¹
  - d/dx √x = 1/(2√x)
  - d/dx (1/x) = −1/x²
- **Product rule:** d/dx (fg) = f·g′ + g·f′
- **Quotient rule:** d/dx (f/g) = (g·f′ − f·g′)/g² ("ho d hi minus hi d ho over ho ho")

## Exponentials and logs
- d/dx eˣ = eˣ
- d/dx aˣ = aˣ ln a
- d/dx ln x = 1/x
- d/dx logₐ x = 1/(x ln a)
- ln 1 = 0
- ln 0 = DNE
- ln e = 1
- e⁰ = 1
- e^(ln a) = a
- ln(eᵃ) = a

## Trig derivatives
- d/dx sin x = cos x
- d/dx cos x = −sin x
- d/dx tan x = sec²x
- d/dx cot x = −csc²x
- d/dx sec x = sec x tan x
- d/dx csc x = −csc x cot x
- csc x = 1/sin x; sec x = 1/cos x; tan x = sin x/cos x; cot x = cos x/sin x

## Trig values (exact)
Note 2π/4 = π/2, 2π/2 = π. DNE = undefined (division by 0).

| Angle | sin | cos | tan | csc | sec | cot |
|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 0 | DNE | 1 | DNE |
| π/6 | 1/2 | √3/2 | √3/3 | 2 | 2√3/3 | √3 |
| π/4 | √2/2 | √2/2 | 1 | √2 | √2 | 1 |
| π/3 | √3/2 | 1/2 | √3 | 2√3/3 | 2 | √3/3 |
| π/2 (2π/4) | 1 | 0 | DNE | 1 | DNE | 0 |
| 2π/3 | √3/2 | −1/2 | −√3 | 2√3/3 | −2 | −√3/3 |
| 3π/4 | √2/2 | −√2/2 | −1 | √2 | −√2 | −1 |
| 5π/6 | 1/2 | −√3/2 | −√3/3 | 2 | −2√3/3 | −√3 |
| π (2π/2) | 0 | −1 | 0 | DNE | −1 | DNE |
| 7π/6 | −1/2 | −√3/2 | √3/3 | −2 | −2√3/3 | √3 |
| 5π/4 | −√2/2 | −√2/2 | 1 | −√2 | −√2 | 1 |
| 4π/3 | −√3/2 | −1/2 | √3 | −2√3/3 | −2 | √3/3 |
| 3π/2 | −1 | 0 | DNE | −1 | DNE | 0 |
| 5π/3 | −√3/2 | 1/2 | −√3 | −2√3/3 | 2 | −√3/3 |
| 7π/4 | −√2/2 | √2/2 | −1 | −√2 | √2 | −1 |
| 11π/6 | −1/2 | √3/2 | −√3/3 | −2 | 2√3/3 | −√3 |
| 2π | 0 | 1 | 0 | DNE | 1 | DNE |
