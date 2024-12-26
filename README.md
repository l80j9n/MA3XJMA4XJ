java c
MA3XJ/MA4XJ   Integral   Equations
Problem   Sheet   1:    2023-2024N.B. see section   1.1 of the handout labelled   “Introductory Notes”   for   how   to   classify   integral   equations   and   do   Q1!      Important   questions   in   this   classification   are:    Is   this    a    1D,   2D,   ...   integral   equation?    Is   this   a   linear   or   nonlinear   integral   equation?    If   it   is   linear,   is   it   first kind   or   second   kind,   homogeneous   or   inhomogeneous,   Fredholm   or   Volterra?
1.   Classify   the   following   integral   equations:
(a) (y(x) + 1)2 = ex +R 01(x − t)y(t)dt, for 0 ≤ x ≤ 1;
(b) y(x) = R 0xsin(x − t)y(t)dt, for 0 ≤ x ≤ 3;
(c) tan x =R1−1(x − t)2y(t)dt, for −1 ≤ x ≤ 1;
(d) ex = y(x) + R −ππln |x − t|y(t)dt, for −π ≤ x ≤ π;
(e) y(x) = cos(x) + R π0cos(x − t) cos(y(t))dt, for 0 ≤ x ≤ π;
(f) cos(x) = R 0xxty(t)dt, for 0 ≤ x ≤ π;
(g) 0 = y(x) + R −ππln |x − t|y(t)dt, for −π ≤ x ≤ π.
2.   Find   the   solutions   y   ∈ C[0, 1],   if   any,   of the   integral   equations   with   separable   kernels:
(a) y(x) = 1 + R 01x2t2y(t)dt, 0 ≤ x ≤ 1;
(b) y(x) = sin x +R 01xty(t)dt, 0 ≤ x ≤ 1.
3.   Generalising   1(a),   given   λ   ∈ C   with   λ   ≠   0,   consider   the   integral   equation

(a)   Show   that   there   is   exactly   one   solution   y   ∈ C[0, 1]   to   this   equation   if   λ   ≠   1/5,   and   find   a   formula   for   this   solution;
(b)   Show   that   there   is   no   solution   y   ∈ C[0, 1]   if   λ   =   1/5;
(c)   Does   the   above   integral   equation   have   any   solutions   if   λ   = 0?
4.   Define   the   integral   operator   K   : C[−2,   2]   →   C[−2,   2]   by

Define   ψ(x) = x + 3i,   for   −2   ≤ x   ≤   2.
(a)   Obtain   an   explicit   formula   for   the   function   Kψ   .
(b)   Obtain   an   explicit   formula   for   the   function   K2   ψ   := K(Kψ).(c)   Generalising   (a)   and   (b),   show   that   if,   for   some   constants   a,b   ∈   C,   ϕ(x)   =   a + bx,   for
−2   ≤ x   ≤   2,   then

5.   Show   that   if y   ∈   C[0, 1]   satisfies

then

6.    [This   is   a variant   on the   previous   question, with   almost   the   same   solution,   but   showing   a   slightly   stronger   result.]   Show   that   y   ∈ C[0, 1]   satisfies

if   and   only   if

7.   Given   λ   ∈ C   with   λ   ≠   0,   show   that   y   ∈ C[0, 1]   satisfies
if   and   only   if
λy(x) =   1 +px   + q,          0   ≤ x   ≤   1,
and

Hence show that, if λ2      ≠      −1/12, then the   integral   equation   (1)   has   exactly   one   solution,   and   obtain   a   formula   for   that   solution.   What   happens   if   λ2    =   −1/12?
8.   Write   the   following   kernels   k   in   degenerate   form,   i.e.   in   the   form   N



for   some   N   ∈ N   and   some   functions   ℓn    that   are   integrable   and   functions   kn    that   are   contin-   uous.   In   each   case   say   what   N   is   and   what   the   functions   kn    and   ℓn    are:
(a)   k(x,t)   := sin(x)cos(t) + x2   + t−1/2, for   x,t   ∈   [0, 1];
(b)   k(x,t) = exp(x + t),   for   x,t   ∈   [−1, 1];
(c)   k(x,t) = sin(x −   t),   for   x,t   ∈   [0,π];
(d)   k(x,t) = ln(x/t),   for   x,t   ∈   [1,   2].
9.   Find   the   solutions   y   ∈ C[−1, 1],   if   any,   of the   integral   equation

10.       Generalising   the   previous   question,   given   λ    ∈   C   with    λ   ≠   0,   find   the   solutions   y    ∈   C[−1, 1],   if any,   of the   integral   equation

   
11.   Find   the   solutions   y   ∈ C[0,π],   if any,   of the   integral   equation
12.   Which   of the   following   integral   equations   have   continuous   kernels?    Which   have   weakly   singular   kernels?       [Note   that   any   continuous   kernel   is   automatically   also   weakly   singular,   according   to   the   specific   definition   of weakly   singular   that   we   are   using.]

(a)   tanx   =              (x   −   t)y(t)dt,代 写MA3XJ/MA4XJ Integral Equations Problem Sheet 1: 2023-2024SQL
代做程序编程语言   for -1 ≤ x   ≤   1;
(b)   y(x) =    sin(x   −   t)y(t)dt,   for   0   ≤ x   ≤   1;
(c)   y(x) =    cos(x −   t)|x −   t|   −1/2y(t)dt,   for   0   ≤   x   ≤   1;
(d) y(x) =      sin(x −   t)y(t)dt,   for   0   ≤ x   ≤   1
[Hint:   first   rewrite   this   as   y(x)   =      k(x,t)y(t)dt,   for   0   ≤ x   ≤   1,   with   the   kernel   k   defined by   k(x,t)   := sin(x −   t),   for   0   ≤ t   ≤   x   ≤ 1,   and   by   k(x,t) = 0,   if   0   ≤   x   <   t   ≤   1.];   
(f) y(x) =      sin(x −   t)|x −   t|   −3/2y(t)dt,   for   0   ≤ x   ≤   1.
[Hints:   remember   that   |cos(s)|   ≤   1,   |sin(s)|   ≤   1,   and   also   |sin(s)|   ≤   |s|,   for   all   s   ∈ R.]13.   Recall   that   if S   and   T   are   sets   and   f   :   S   →   T   is   a   mapping   (in   which   case   we   call   S   the   domain   and   T   the   codomain   of   the   mapping),   the   range   of   f,   often   denoted   by   f(S),   is   the subset   of T   defined   by
f(S)   := {f(s)   :   s   ∈ S}.
Define   the   integral   operator   K   : C[0,   3]   → C[0,   3]   by

Let   R   denote   the   range   of   K,   i.e.
R = K(C[0,   3])   :=   {Kϕ   :   ϕ   ∈ C[0,   3]},
and   let   L   denote   the   set   of linear   polynomials   defined   on   [0,   3],   i.e.    L   is   the   set   of functions   ϕ   :   [0, 1]   → C   such   that,   for   some   constants   a,b   ∈ C,
ϕ(x) =   a + bx,            0   ≤ x   ≤ 3.
(a)   Suppose that g   ∈ L,   i.e.,   for some constants   a,b   ∈ C,   g(x)   =   a+bx,   for   0   ≤ x   ≤ 3.    Show   that   the   integral   equationKy   = g                                                                                                                                                                                          (2)
has   exactly   one   solution   y   ∈ L,   and   find   that   solution   explicitly.   (b)   Noting   the   result   from   part   (a),   show   that   R   = L.
(c)   Does   the   equation   (2)   have   a   solution   y    ∈   C[0,   3]   in   the   case   that   g(x)   =   cos(x),   for   0   ≤ x   ≤   3?
14.   Define   the   integral   operator   K   :   [0,   2]   → C[0,   2]   by
(a)   Applying   the   fundamental   theorem   of   calculus   (look   this   up   in   your   calculus   book   or   on
Wikipedia!),   deduce   that   if   ϕ   ∈ C[0,   2]   then   Kϕ   is   continuously   differentiable   on   [0,   2]   with
(Kϕ)′   (x) =   (1 + x)ϕ(x),          for   0   ≤ x   ≤ 2.(b)   Let   C1 [0, 2]   denote   the   set   of   those   ϕ   ∈   C[0,   2]   that   are   continuously   differentiable   on
[0,   2].   Using   the   result   from   (a),   deduce   that   the   range   of   K   satisfies   K(C[0,   2])   ⊂ {ϕ   ∈ C1 [0,   2]   : ϕ(0) =   0}.
(c)   Using   the   result   from   (a),   show   that   if   y   ∈ C[0, 2],   g   ∈ C1 [0, 2],   and   Ky   = g,
then
In   the   case   that   g(x)   =   sin(x),   for   0   ≤   x   ≤   2,   show   (just   by   substituting   in)   that   y   given by   this   formula   is   indeed   a   solution   of   Ky   = g.    Show   that   y   given   by   this   formula   is   not   a   solution   to   Ky   =   g   in   the   case   that   g(x)   =   cos(x),   for   0   ≤   x   ≤   2,   and   explain   why   this   is unsurprising   given   the   result   from   (b).
15.   For   any   continuous   function   ϕ,   let   Kϕ   denote   the   continuous   function   defined   by
Show   that   if   ϕ   is   defined   byϕ(s)   =   1,          0   ≤ s   ≤   1,                                                                                                                                                                      (4)
and   if   K2   ϕ   denotes   the   function   K(Kϕ),   then
Kϕ(x) =   (e -   1)ex   ,          0   ≤ x   ≤ 1,   and

For    n    =       1,   2, . . .,    generalise    the    above    notation    and    let    Kn+1ϕ    denote    the    function   K(Kn   ϕ).   If   ϕ   is   defined   by   (4),   prove   by   induction   that
   

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
