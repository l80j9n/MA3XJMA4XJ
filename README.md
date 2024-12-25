java c
MA3XJ/MA4XJ Integral Equations
Problem Sheet 4: 2023-2024
1. Let K denote the integral operator on C[a, b] which occurs in the integral equation on page 195 of the lecture notes, i.e.

where k0 > 0,

and the function k : [a, b] → R is positive and piecewise continuous.
(a) Show that

where   
(b) The solution to the 1D scattering problem discussed in the lectures satisfies the integral equation

where ui(x) := exp(ik0x), for a ≤ x ≤ b. The Born approximation ubto the scattering problem is given by the same formula, but with u replaced by ui on the right hand side, i.e. ubis given by

Write both these equations in operator form. using the notation from part (a).
(c) Following on from part (b), show that
u − ub = K2u
and that, if ∥K∥ < 1, it holds that
∥u∥∞ ≤ (1 − ∥K∥)−1
and that

(d) Combining the results of parts (a) and (c), work out a condition on L, k0 and ∥k2 − k20∥∞ which will ensure that ubis in error by no more than 0.01 on [a, b], i.e. which guarantees that
|ub(x) − u(x)| ≤ 0.01,
for a ≤ x ≤ b.
2. Suppose that k : R → (0,∞) is continuous and that, for some a < b and some k0 > 0,
k(x) = k0 for x ≥ b and x ≤ a.
Where BC(R) is the Banach space as defined in question 5 on Problem Sheet 3, define the integral operator K : BC(R) → BC(R) by

where the function Φ is as defined in question 1.
(a) Show that

where L = b − a. (This looks as if it is the same result as in question 1 (and it is almost the same!), but in this question K is defined so as to be an integral operator on BC(R), so that

with ∥ · ∥∞ as defined in question 5 on Problem Sheet 3.)
(b) Suppose that u ∈ C2(R) and that:
(i) u′′(x) + k2(x)u(x) = 0, for x ∈ R;
(ii) for some T ∈ C, u(x) = T exp(ik0x), for x ≥ b;
(iii) for some R ∈ C, u(x) = exp(ik0x) + R exp(−ik0x), for x ≤ a.
Show that u satisfies the integral equation
u = ui + Ku,                                                                                        (1)
where ui ∈ BC(R) is defined by ui(x) = exp(ik0x), for x ∈ R. (Hint: this is just the argu-ment that we went through in the lectures (and see slides 199-207). You basically just need to repeat this, but it all simplifies a little bit as we are assuming here that k is continuous – in the lectures and on the slides we did the slightly more complicated case where k is piecewise continuous.)
(c) Explicitly, the integral equation (1) is the equation

Show that if u ∈ BC(R) satisfies this equation then u satisfies conditions (ii) and (iii) in part (b), and get explicit formulae for R and T as integrals involving the values of k and u on [a, b]. (Hint: note that exp(ik0|x − y|) in the definition of Φ(x, y) can be written without the modulus signs if a ≤ y ≤ b and x ≥ b, or if a ≤ y ≤ b and x ≤ a.)
(d) Let ub ∈ BC(R) be the Born approximation to u, given by

(This is the same definition as in question 1, but now we are thinking of ub as defined on the whole real line, not just on [a, b].) Adapting the arguments from question 1, show that

if

3. Consider the following problems:
Problem 1 (Volterra inte代 写MA3XJ/MA4XJ Integral Equations Problem Sheet 4: 2023-2024C/C++
代做程序编程语言gral equation). Find y ∈ C[0, 1] such that

Problem 2 (IVP for an ODE). Find y ∈ C2[0, 1] such that
y'' (x) = (1 + x − x2)y' (x) + (2 − 2x)y(x), 0 ≤ x ≤ 1,
and y(0) = 1, y' (0) = 2.
Show that if y satisfies Problem 1, then it satisfies Problem 2.
4. Suppose that y ∈ C[0, π] and that

Show that y ∈ C2[0, π], that
y'' (x) = 0, for 0 ≤ x ≤ π,
and that y(0) = 1, y′(0) = 0. Hence deduce that y(x) = 1, for 0 ≤ x ≤ π.
5. Consider the following problems:
Problem 1 (Volterra integral equation). Find y ∈ C[0, 1] such that

Problem 2 (IVP for an ODE). Find y ∈ C1[0, 1] such that
y' (x) = 1 + (1 − x2)y(x), 0 ≤ x ≤ 1,
and y(0) = 1.
(a) Show that y satisfies Problem 1 if and only if it satisfies Problem 2.
(b) Do Problems 1 and 2 have solutions? If so how many?
(c) Applying the Gronwall inequality show that, if y satisfies Problem 1, then
|y(x)| ≤ 2ex,               0 ≤ x ≤ 1.
(d) Assuming that y satisfies Problem 1, compute approximations to y(0.5) and y(1) by applying the trapezium rule with step size h = 0.5.
(e) The integral equation in Problem 1 can be written in operator form. as y = g + Ky, where g(x) = 1 + x, for 0 ≤ x ≤ 1, and K : C[0, 1] → C[0, 1] is defined by

Compute the first three terms of the Neumann series, i.e. compute
y2 := g + Kg + K2g.
(f) Where K, g, and y2 are as defined in part (e), compute ∥K∥ and show that, if y ∈ C[0, 1] satisfies Problem 1, then

6. Let y ∈ C[0, 2] be the unique solution of the integral equation

(a) By applying the Gronwall inequality, show that |y(x)| ≤ exp(ex), for 0 ≤ x ≤ 2.
(b) Compute approximations to y(0.5) and y(1) using the trapezium rule with step size h = 0.5.
(c) Show that y ∈ C1[0, 2] and that y(0) = 1 and
2y' (x) = 3y(x) − 1, 0 ≤ x ≤ 2.
(d) Find the exact solution of the integral equation by solving the initial value problem in (c). In particular compute the exact values of y(0.5) and y(1).
7. Suppose that u ∈ C(R) and k ∈ C(R) and that, for some k0 > 0 and a < b, k(x) = k0 for x > b and for x < a. Suppose further that

where

and ui(x) = exp(ik0x), for x ∈ R. Show that u ∈ C2(R) and that
u'' (x) + k2(x)u(x) = 0
for x ∈ R.
Hint. First observe that we will have shown that u ∈ C2 (R) and that the above equa-tion holds for all x ∈ R if, for all sufficiently large A > 0, we show that u ∈ C2[−A, A] and that the above differential equation holds in [−A, A]. Then observe that, if A is large enough so that [a, b] ⊂ [−A, A], then, for −A ≤ x ≤ A,

Now proceed by applying the Leibniz rule to the integrals in the above expression to show that u ∈ C2[−A, A] and get an expression for u'' (x).
8. Show that the trapezium rule approximation with step-length h = 1/N applied to the equation

leads to the equations defining the approximation yn to y(tn) (where tn = hn):

Using h = 0.5 compute approximations to y(0), y(0.5) and y(1). Compare these approxi-mations to the exact solution to the integral equation obtained via converting the integral equation to an initial value problem.









         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
