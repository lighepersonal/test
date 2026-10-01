# Calculus Unit 2 Notes (2.1–2.5)

## 2.1 Average & Instantaneous Rate of Change
- Slope = Δy/Δx = (y₂−y₁)/(x₂−x₁)
- **AROC** on [a,b] = (f(b)−f(a))/(b−a); also (f(a+h)−f(a))/h or (f(x)−f(a))/(x−a). Slope of a **secant** line (2 points).
  - Ex: f(x)=ln 3x on [1,4]: (ln12 − ln1)/3 ≈ 0.4621
  - From a table: x=0,2,7,30 / f=3,−2,5,7; AROC on [2,30] = (7−(−2))/28 = 9/28
- **IROC** at x=a = lim_{h→0} (f(a+h)−f(a))/h = lim_{x→a} (f(x)−f(a))/(x−a). Slope of **tangent** line (1 point).
  - Ex: f(x)=x−x² at x=−1 → 3 (both forms)
  - Identify f and a from a limit: lim (5ln(2/(4+h)) − 5ln(1/2))/h → f=5ln(2/x), x=4. lim (sin x −1)/(x−π/2) → f=sin x, x=π/2.

## 2.2 Defining the Derivative
- f′(x): expression giving the IROC (slope) at any x. Notation: f′(x), y′, dy/dx.
- f′(x) = lim_{h→0} (f(x+h)−f(x))/h
- Meaning examples: f′(2)=1/2 → slope of tangent at x=2 is 1/2. f′(3)=160 (f = meters run, x = minutes) → at minute 3, running 160 m/min.
- Using the definition: f=2x²−7x+1 → f′=4x−7. y=1/x² → dy/dx = −2/x³.
- **Tangent line** at x=a: y − f(a) = f′(a)(x − a)
  - h(5)=−2, h′(x)=(x³−2)/x → h′(5)=123/5 → y+2 = (123/5)(x−5)
  - From graph of f′: f(2)=7, f′(2)=3 → y−7 = 3(x−2)

## 2.3 Estimating Derivatives (calculator)
- Calculator: math → nDeriv, i.e. d/dx f(x)|_{x=a}
  - f=sin√x, f′(2) ≈ 0.0551; f=ln(1/(5−x)), f′(1.3) ≈ 0.2703
  - Tangent to y=√(x/(x³+1)) at x=1: y(1)=√2/2≈0.7071, y′(1)≈−0.1768 → y−0.7071 = −0.1768(x−1)
- From a table (f must be continuous): use the points on either side of the x-value.
  - f′(3) ≈ (f(4)−f(2))/(4−2) = (10−3)/2 = 7/2 mi/hr
  - w′(100) ≈ (w(120)−w(80))/(120−80) = (500−700)/40 = −50 gal/sec²

## 2.4 Differentiability & Continuity
- Differentiable = derivative exists at every point in the domain (local linearity: zooms in to look like a line).
- NOT differentiable at: (i) discontinuity (hole, jump…), (ii) corner or cusp, (iii) vertical tangent (slope undefined).
- Differentiable ⇒ continuous (TRUE). Continuous ⇒ differentiable (FALSE).
- Graph ex: not continuous at x=0,6; not differentiable at x=0,2,4,6.

## 2.5 Power Rule
- If f(x)=xⁿ then f′(x)=n·xⁿ⁻¹. **Rewrite f(x) as a power before differentiating.**
- Exponent rules: xᵃ/xᵇ = xᵃ⁻ᵇ, xᵃ·xᵇ = xᵃ⁺ᵇ
- Ex: x³⁷ → 37x³⁶; 1/x = x⁻¹ → −1/x²; √x → 1/(2√x); ⁷√(x³)=x^(3/7) → (3/7)x^(−4/7) = 3/(7·⁷√(x⁴))
- f=x/√x = x^(1/2) → f′(7) = 1/(2√7)
- f=∛x·x³ = x^(10/3) → f′(x)=(10/3)x^(7/3), f′(8) = (10/3)(2)⁷ = 1280/3
- Parallel tangents of x⁴ and x³: 4x³=3x² → x²(4x−3)=0 → x=0, 3/4

## 2.6 Constant, Constant Multiple, Sum/Difference
- d/dx c = 0; d/dx cx = c; d/dx (c·u) = c·du/dx; d/dx (u ± v) = u′ ± v′
- Ex: y=2x²−5/x+6 → y′=4x+5/x². y=8√x − x⁶/3 + 2π⁵ → y′=4/√x − 2x⁵ (2π⁵ is a constant → 0)
- **Horizontal tangent**: slope 0 → solve f′(x)=0. f=4x²+7x−13 → f′=8x+7 → x=−7/8
- **Normal line**: perpendicular to the tangent at the point of tangency; slope = negative reciprocal of tangent slope.
  - f=x³−4x²+x+3 at x=3: f′(3)=4, f(3)=−3 → normal: y+3 = −(1/4)(x−3)
- **Piecewise differentiability at x=c**: (1) check continuity (pieces equal at c), (2) check derivatives of the pieces equal at c.
  - f = 5x²+3x+2 (x<−1), −7x−3 (x≥−1): both 4 at −1; derivatives 10x+3 → −7 and −7 → differentiable (Yes)
  - f = x²−ax+2 (x<3), x+b (x≥3): derivative 2x−a=1 at 3 → a=5; continuity 9−15+2=3+b → b=−7

## 2.7 Derivatives of sin x, cos x, eˣ, ln x
- Recall: ln1=0, ln0 = DNE, ln e=1, e⁰=1, e^(ln a)=a, ln(eᵃ)=a
- d/dx sin x = cos x; d/dx cos x = −sin x; d/dx aˣ = aˣ ln a; d/dx eˣ = eˣ
- d/dx logₐ x = 1/(x ln a); d/dx ln x = 1/x
- Ex: 2sin x+5eˣ → 2cos x+5eˣ; 3ˣ−4cos x → 3ˣ ln3 + 4 sin x; log₂x − sin x → 1/(x ln2) − cos x
- f=3cos x + (sin x)/2 → f′=−3sin x+(1/2)cos x → f′(π) = −1/2

## 2.8 Product Rule
- d/dx (fg) = f·g′ + g·f′ ("first times derivative of second plus second times derivative of first")
- Ex: 8x sin x → 8x cos x + 8 sin x; 2eˣ√x → eˣ/√x + 2eˣ√x; (1/x+1)(2x²−5) → 4x+2+5/x²
- Table ex: h=3f·g, h′(2)=3f(2)g′(2)+g(2)·3f′(2)=24+6=30; r=(f/2+2)(3−g), r′(−5) = −15/2

## 2.10 Trig Derivatives
- d/dx sin x = cos x; cos x → −sin x; tan x → sec²x; csc x → −csc x cot x; sec x → sec x tan x; cot x → −csc²x
- Recall: csc=1/sin, sec=1/cos, tan=sin/cos, cot=cos/sin
- Ex: y=sin x tan x → y′ = sin x sec²x + sin x. f=x/sec x → f′=(1−x tan x)/sec x (quotient rule used) → f′(π/6) = (6√3−π)/12
- Calculator: d/dx csc²(4x) at x=2 ≈ 1.2020 (enter as 1/(sin(4x))²)

(Note: there was no 2.9 in the uploaded set — the 2.10 example uses the quotient rule.)
