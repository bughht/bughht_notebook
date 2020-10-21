+ $ f'(z_0)=\lim_{\Delta z\to 0}\cfrac{\Delta w}{\Delta z}$
+ $\cfrac{\Delta w}{\Delta z}=f'(z_0)+\eta(\Delta z)\Delta z$
+ $Prove  f(z)=z^2 \text{is derivatable and } (z^2)'=2z$
    $\cfrac{\Delta w}{\Delta z}=\cfrac{(z+\Delta z)^2-z^2}{\Delta z}=\cfrac{2z\Delta z+\Delta z^2}{\Delta z}$
    add lim
    $=2z$

+ $f(z)=\overline{z}, Re z, Im z, |z| \text{ continuous on }z$
+ $ u(x,y) \text{is derivatable at }(x,y)\Leftrightarrow \Delta u=A\Delta x+B\Delta y+o(\sqrt{(\Delta x)^2+(\Delta y)^2})$ 
+ $f(z)=u(x,y)+iv$
    + $u(x,y),v(x,y) \text{is differentiable at }(x,y)$
    + $u(x,y), v(x,y) \text{ supports } u_x=v_y, u_y=-v_x\textbf{  C-R Euqation}$
+ $\text{if f(z) is derivatable at z, }f'(x)=u_x+iv_x=v_y+iv_x=u_x+iu_y=v_y-iu_y$
+ if $u=u(x,y)$ is partial derivative at $(x,y)$, $u_x$,$u_y$ are continuous at $(x,y)$, and $u(z)$ is differentiable at $(x,y)$.
    + Example 1 $f(z)=|z|^2$.
        1. $f(z)=|z|^2=x^2+y^2$
        2. $u(x,y)=x^2+y^2, v(x,y)=0$
        3. $u_x=2x,u_y=2y,v_x=v_y=0$ 
        4. $u_x=v_y,u_y=-v_x$ (C-R Equation) get $z=0$
        5. $f(z)|_{z=0}=u_x|_{z=0}+iv_x|_{z=0}=2x|_{z=0}=0$
    + Example 2 $f(z)=x^2+2y^2$
        1. $u(x,y)=x^2, v(x,y)-y^2$
        2. $u_x=2x,u_y=0,v_x=0,v_y=2y$
        3. $y=x$
        4. $f'(z)|_{y=x}=2x$
+ analytic function
    + Example $f(z)=\overline{z}$
        1. $f(z)=x-iy$
        2. not analytic
+ $f(z)=\overline{z},Imz,Rez,|z|$ are not analytic
+ ### The relationship between Analytic Function and Harmonic Function 
+ Construct: Given a differentiable function u,(v), if exsist a v,(u) make $u+iv$ analytical
    + **C-R**   
        + $u_x=v_y, u_y=-v_x$
        + $u_{xx}+u_{yy}=v_{yx}-v_{xy}!=0$
    + **C-R**
        + $u_{xx}+u_{yy}=0$
+ Harmonic Function : $u: u_{xx}+u_{yy}=0$ ($u\in C^2(D)$) $u_x$, $u_{xx}$ continuous
    + Example: $u(x,y)=x^3-3xy^2$
        +  $u_{xx}=6x, u_{xy}=-6y, u_{yx}=-6y, u_{yy}=-6x$
        + $u\in C^2(C)$
        + Harmonic
+ $f(z)=u+iv$ analytic $\Leftrightarrow$ u,v harmonic in D and support **C-R** Equation.
+ If $u(x,y)$ and  $v(x,y)$ harmonic in D and satisfying **C-R** equation $u_x=v_y$, $u_y=-v_x$, then v is the convergent harmonic function of u.
+ Partial Integrate Method
    + $u_x=v_y (1)$
    + $\int v_y(x,y)dy=\int u_x(x,y)dy$
    + $\Rightarrow v(x,y)+\psi (x)=\int u_x dy$
    + $v(x,y)=\int u_x dy+\psi (x)$
    + $v_x=-u_y (2)$
    + $(\int u_x(x,y) dy)_x+\phi '(x)=-u_y$
+ Example $u(x,y)=x^3-3xy^2$
    + $u_x=3x^2-3y^2, u_y=-6xy$
    + $v_y=u_x=3x^2-3y^2$
    + $v(x,y)=3x^2y-y^3+\phi (x)$
    + $v_x=-u_y=6xy$
    + $6xy+\phi'(x)=6xy$
    + $\Rightarrow \phi(x)=C$
    + $f(z)=(3x^2y-y^3+C)i+(x^3-3xy^2)$
    + $f(0)=i$
    + $Ci=i$
    + $C=1$
+ Primary Analytic Function
    + $w=e^z=e^x(cos y+i sin(y))$
        + $z=|z|=(cos \theta +i\sin\theta)=|z|e^{i\theta}$
        + $(e^z)'=e^z$
        + $|e^z|=e^x>0$
        + $e^{z_1}\cdot e^{z_2}=e^{z_1+z_2}$
        + $e^{z+2k\pi i}=e^z\qquad (k\in Z)$
        + example $e^z=1-\sqrt{3}i$
            + $e^z=e^{i(-\frac{\pi}{3}+ln2)}$ 
    + $e^w=z\Leftrightarrow w=Ln(z)$
        + $z=re^{i\theta}, w=u+iv,e^{u+iv}=re^{i\theta}$
        + $\Rightarrow u=\ln r, v=\theta+2k\pi =Arg z$
        + $w=Ln(z)=\ln |z|+i Arg z(z\not = 0)=\ln|z|+i argz+2k\pi i (k\in Z)$
        + Example $Ln(-1-i)$
            + $Ln(-1-i)=ln(\sqrt{2})+i(-\cfrac{3\pi}{4})+2k\pi i, k\in Z$
        + Example $Ln(-1)$
            + $Ln(-1)=i\pi+2k\pi i, k\in Z$
        + Example $Ln(2)$
            + $Ln(2)=ln2+2k\pi i, k\in Z$+ 
        + $Ln(z_1z_2)=Lnz_1+Lnz_2$
        + $Ln(\cfrac{z_1}{z_2})=Ln z_1-Ln z_2$, ($z_1\not ={0}, z_2\not ={0}$)
        + $Ln z^n\not ={nLnz}, Lnz-Lnz\not ={0}$
        + $2Ln z= ln r^2+i (2\theta +4k\pi), k\in Z$ 
        + *$e^{Lnz}=e^{lnz}=z$
        + Example: solve $lnz=1+\pi i$
            + $z=e^{1+\pi i}$
            + $z=e\cdot(cos \pi + isin \pi)=-e$
    + $e^{iy}=cosy+isiny$ and $e^{-iy}=cosy-isiny$
        + $sin z=\cfrac{1}{2i}(e^{iz}-e^{-iz})$
        + $cos z=\cfrac{1}{2}(e^{iz}+e^{-iz})$
        + zero point of $sin z$ is $z=k\pi, k\in Z$
        + zero point of $cos z$ is $z=(k+1/2)\pi, k\in Z$
        + Example $sinz=0$
            + $\Rightarrow e^{ir}-e^{-ir}=0$
            + $\Rightarrow e^{2iz}=1$
    + $w=z^\alpha, \alpha \in C$
        + $z^\alpha=e^{\alpha Lnz}=e^{\alpha (ln|z|+iargz+2k\pi i)}$
        + Example $i^i$
            + $i^i=e^{iLni}=e^{i(i(\pi/2+2k\pi ))}=e^{-(\pi /2+2k\pi)}$
+ **Homework 2.9(1)(4), 2.13(1)(2)(4), 2.14**

+ ## Integration of Complex Function
    + Complex Integral
        + $\oint_Cf(z)dz=-\oint_{C^{-}}f(z)dz$
        + If $f(z)=u(x,y)+iv(x,y)$ continuous on smooth curve $C$ from $a$ to $b$ ($u$,$v$ are continuous), $\int_C f(z)dz=\int_C udx-vdy+i(\int_C vdx+udy)$  
            + If $f(z)$ is continuous function and $C$ is a smooth curve, integral $\int_Cf(z)dz$ exist.
            + $\int_Cf(z)dz$ can be simplified into real variable function.
        + Parametric Equation
            + $z(t)=x(t)+iy(t)\qquad t: a\rightarrow b$ 
        + **(Important!)**Parametric Equation method: *$\int_Cf(z)dz=\int_a^bf(z(t))z'(t)dt$
        + Example:
            + Prove: $I_n=\oint_C\cfrac{dz}{(z-z_0)^n}=2\pi i,\quad(n=1)\text{ or }0,\quad(n\in Z^+,n\not ={1})$ where $C:|z-z_0=r(>0)$
                + $z(\theta)=z_0+re^{i\theta}$
                + $\oint_C\cfrac{1}{(z-z_0)^n}dz=\int_0^{2\pi}ir^{1-n}e^{i(1-n)\theta}d\theta$
                + $=ir^{1-n}\int_0^{2\pi}e^{i(1-n)\theta}d\theta=$ then split it into sin and cos.
        + $|\int_Cf(z)dz|\leqslant\int_C|f(z)|ds$
+ Cauchy Integral Theorm
    + $f(z)$ integral in D is unrelated to path$\Leftrightarrow$ $\oint_lf(z)dz=0$
    + If $F(z)$ is analytic in single connected region $D$, $\oint_Cf(z)dz=0$ for any contour $C$ in $D$.
        + Example1:
            + $f(z)=e^z,z^n,\sin z,\cos z$ analytic on $z$ area, $\oint_Cf(z)dz=0$ where C is a contour in the complex area.
        + Example2: solve $\oint_C\cfrac{1}{z+2}dz, C:|z|=1$
            + singular point: $z=-2$
            + Construct $D$:
               1. $-2\notin D$
               2. $C \subset D$
            + $D: |z|\leq 1.5$
            + $\oint_C\cfrac{1}{z+2}dz=0$
    + Cauchy integral theorm on complex connected region
        + $f(z)$ is analytic in $D$ bounded in $C_1$ and $C_2$ (contours) and continuous on $\overline{D}=D+C_1+C_2$, then $\oint_{C_1}f(z)dz=\oint_{C_2}f(z)dz$
        + $\oint_Cf(z)dz=\sum_{k=1}^{n}\oint_{C_{k}}f(z)dz$
        + Example: solve $\oint_C\cfrac{1}{(z-1)(z+1)}dz$, $C:$ bound 1 and -1
            + $f(z)=\cfrac{1}{(z-1)(z+1)}=\cfrac{1}{2}\big(\cfrac{1}{z-1}-\cfrac{1}{z+1}\big)$
            + Construct $C_1$, $C_2$ around -1 and 1.
            + $\oint_Cf(z)dz=\oint_{C_1}f(z)dz+\oint_{C_1}f(z)dz$
                + $=\oint_{C_1}(\cfrac{1}{z-1}-\cfrac{1}{z+1})+\oint_{C_2}(\cfrac{1}{z-1}-\cfrac{1}{z+1})$
                + $=0-2\pi i+2\pi i+ 0$
                + $=0$
    + $f(z)$ is analytic in $D$, $z_0\in D$, $F(z)$ is analytic in $D$ and $F'(z)=f(z)$
    + $f(z)$ is analytic in single connect region $D$, $\int_{z_0}^{z_1}f(z)dz=F(z_1)-F(z_0), z_0,z_1\in D$ 
+ Calculate Complex Integration
    + $C:$  not close
        + Paramater
        + N-L Formula 
    + $C: $ contour
        + Parameter
        + Cauchy Theory
        + Important Integral: $\int_c\cfrac{1}{(z-z_0)^n}dz=2\pi i(n=1)$ or $0$ ($n\not =1, n\in Z$)
            + $C:|z-z_0|=r>0$
+ Cauchy Integral Formula
    + If $f(z)$ is analytic in $D$ surrounded by contour $C$, continuous on $C$ and $D$, for all $z_0\in D$,
        + $f(z_0)=\cfrac{1}{2\pi i}\oint_C\cfrac{f(z)}{z-z_0}dz$

    + Application:$\oint_C\cfrac{f(z)}{z-z_0}=2\pi if(z_0)$
        + where $g(z)=\cfrac{f(z)}{z-z_0}$, singular point $z_0$
            $g(z)$ has only one sigular point $z_0$
    + Example: $I_1=\oint_C\cfrac{\sin z}{z} dz, C:|z|=2$
        + $g(z)=\cfrac{\sin z}{z}$, singular point $z=0$
        + $I_1=2\pi i sin(0)$
        + $=0$
    + Example2: $I_2=\oint_{|z-i|=1}\cfrac{1}{z^2+i}dz$
        + $g(z)=\cfrac{1}{z^2+i}$, singular point $z_0=\sqrt[n]{|z|}e^{i(\frac{-\pi/2+2k\pi)}{n}}, k \in {0,1}$
        + $z_0=\cfrac{\sqrt{2}}{2}-\cfrac{\sqrt{2}}{2}i$, $z_1=-\cfrac{\sqrt{2}}{2}+\cfrac{\sqrt{2}}{2}i$
        + $z_1$ in C
        + $\oint_C\cfrac{1}{z^2+i}dz=\oint_C\cfrac{\cfrac{1}{z-z_0}}{z-z_1}dz=2\pi i \cfrac{1}{z-z_0}\bigg|_{z=z_1}=\cfrac{2\pi i}{-\sqrt{2}+\sqrt{2}i}=\cfrac{\sqrt{2}}{2}\pi(1-i)$
    + Example3: $I_3=\oint_{|z|=2}\cfrac{e^z}{(z^2+1)(2z-1)}$
+ if $f(z)$ analytic on $D$, $f^{(n)}=\cfrac{n!}{2\pi i}\oint_C\cfrac{f(z)}{(z-z_0)^{n+1}},n\in N$
    + $\oint_C\cfrac{f(z)}{(z-z_0)^{n+1}}=\cfrac{2\pi i }{n!}f^{(n)}(z_0)$
    + Example: $I_1=\oint_{|z-i|=1}\cfrac{\cos z}{(z-i)^3}$
        + $g(z)=\cfrac{\cos z}{(z-i)^3}$, singular point $z=i$
        + $I_1=2\pi i\cfrac{(\cos z)''}{2!}\bigg|_{z=i}=\pi i (-\cos i)=-\pi i \cfrac{e^{-1}+e}{2}$
    + Example2: $I_2=\oint_{|z|=1}\cfrac{\sin z}{z^{2020}}dz$
        + $g(z)=\cfrac{\sin z}{z^{2020}}$, $z_0=0$
        + $I_2=2\pi i\cfrac{(\sin z)^{(2019)}}{2019!}\bigg|_{z=z_0}=2\pi i\cfrac{-\cos 0}{2019!}=-\cfrac{2\pi i}{2019!}$
    + Example3: $I_3=\oint_{|z|=4}\cfrac{e^z}{z^2(z-1)^2}dz$
        + $z_0=0$, $z_1=1$
        + $\oint_{|z|=4}g(z)dz=\oint_{C_1}\cfrac{\frac{e^z}{(z-1)^2}}{z^2}dz+\oint_{C_2}\cfrac{\frac{e^z}{z^2}}{(z-1)^2}=\cfrac{2\pi i }{1!}\cfrac{e^z}{(z-1)^2}\bigg|_{z=0}+\cfrac{2\pi i}{1!}\cfrac{e^z}{z^2}\bigg|_{z=1}=...$
+ infinite series
    + $\sum_{n=1}^{\infty}z_n$
    + $\sum_{n=1}^{\infty}q^n$ convergence on $|q|<1$
    + $z_n=x_n+iy_n$ convergent then $\sum_{n=1}^\infty x_n$ and $\sum_{n=1}^\infty y_n$ convergent.
    + Example $\sum_{n=1}^{\infty}\cfrac{i^n}{n}$   
        + $=i-\cfrac{1}{2}-\cfrac{1}{3}i+\cfrac{1}{4}+\cfrac{1}{5}i$
        + $=(-\cfrac{1}{2}+1/3-1/6+\cdots)+i(1-1/3+1/5-\cdots)$
    + $\sum_{n=1}^{\infty}|z_n|$ convergent, then $\sum_{n=1}^{\infty}z_n$ convergent.
    + power series
        + $\sum_{n=0}^{\infty}C_n(z-z_0)^n$
        + Abel's Theorm
            + if $\sum_{n=1}^{\infty}C_n(z-z_0)$ convergent at $z_1$, it definitely convergent on $K:|z-z_0|<|z_1-z_0|$
+ Taylor Series
    + Taylor Expansion Theorem: If $f(z)$ analytic in $D$, for all $z_0\in D$, if $K:|z-z_0|<R$ in $D$, $f(z)$ could be expand into $f(z)=\sum_{n=0}^{\infty}C_n(z-z_0)^n$, where 
        + $C_n=\cfrac{1}{2\pi i}\oint_{C_\rho}\cfrac{f(\xi)}{(\xi-z_0)^{n+1}}d\xi=\cfrac{f^{(n)}(z_0)}{n!}$: Taylor Coefficient
        + $z_0$: Expand Center
        + $C_\rho:|\xi-z_0|=\rho$, $0<\rho<R$
        + *Trick:* $\cfrac{1}{\xi-z}=\cfrac{1}{(\xi-z_0)-(z-z_0)}=\cfrac{1}{\xi-z_0}\cfrac{1}{1-\cfrac{z-z_0}{\xi-z_0}}=\cfrac{1}{\xi-z_0}\sum_{n=0}^{\infty}t^n=\sum_{n=0}^{\infty}\cfrac{(z-z_0)^n}{(\xi-z_0)^{(n+1)}}$
        + Example 1: $f(z)=\cfrac{1}{1+z}$, $z_0=0$
            + Singular Point: $z=-1$, $D:z\not ={-1}$
            + $K: |z-z_0|=|z|<1$
            + $\cdots$
    + Taylor Expansion Method
        1. Solve Taylor Coefficient Directly: $C_n=\cfrac{f^{(n)}(z_0)}{n!}$
            + $e^z=\sum_{n=0}^{\infty}\cfrac{z^n}{n!}, |z|<\infty$
            + $\sin(z)=\sum_{n=0}(-1)^n\cfrac{z^{2n+1}}{(2n+1)!}$
            + $\cos(z)=\sum_{n=0}(-1)^n\cfrac{z^{2n}}{(2n)!}$
        2. Solve with known expansion like $\cfrac{1}{1-z}=\sum_{n=0}^\infty z^n, |z|<1$
            + $\cfrac{1}{1-z^2}$, $z_0=0$
                + $R=1$, $|z|<1$
                + $\cfrac{1}{1-z^2}=\sum_{n=0}^\infty z^2n$
                + $\cfrac{1}{1+z^2}=\sum_{n=0}^\infty (-1)^n z^{2n}$
                + $\cfrac{1}{1+z}=\sum_{n=0}^\infty (-1)^n z^n$
            + $\cfrac{z-1}{z+1}$, $z_0=1$
                + $R=2, |z-1|<2$
                + $=1-\cfrac{2}{1+z}=1-\cfrac{1}{2+(z-1)}=1-\cfrac{1}{2}\cfrac{1}{1+\cfrac{z-1}{2}}=1-\cfrac{1}{2}\sum_{n=0}^\infty (-1)^n(\cfrac{z-1}{2})^{2n}$
            + $\cfrac{z}{z^2+3z+2}$, $z_0=2$
                + $R=3$, $|z-2|<3$
                + $=\cfrac{z}{(z+1)(z+2)}=\cfrac{a}{z+1}+\cfrac{b}{z+2}$
                + $a(z+2)+b(z+1)=z$
                + $a=-1$, $b=2$
                + $=-\cfrac{1}{z+1}+\cfrac{2}{z+2}=\cdots$
                    + $\cfrac{2}{z+2}=\cfrac{2}{(z-2)+4}=\cfrac{1}{2}\cfrac{1}{1+\frac{z-2}{4}}=\cfrac{1}{2}\sum_{n=0}^\infty(-1)^n(\cfrac{z-2}{4})^n$
            + $f(z)=\cfrac{z}{z^2-2z+5}$, $z_0=1$
                + singular point: $z^2-2z+5=0$, $1\pm 2$ 
                + $R=2$
                + $f(z)=\cfrac{(z-1)+1}{(z-1)^2+4}=((z-1)+1)\cfrac{1}{(z-1)^2+4}$
                + $=\cfrac{(z-1)+1}{4}\sum_{n=0}^\infty (-1)^n(\cfrac{z-1}{2})^{2n}$
                + $=\cfrac{z-1}{4}\sum_{n=0}^\infty (-1)^n(\cfrac{z-1}{2})^{2n}+\cfrac{1}{4}\sum_{n=0}^\infty (-1)^n(\cfrac{z-1}{2})^{2n}$
        3. Derivative within contour $\cfrac{1}{(z-a)^2}=-(\cfrac{1}{z-a})'$
            + Example: $f(z)=\cfrac{1}{(z+2)^2}$, $z_0=-1$
                + $R=1$, $|z+1|<1$
                + $\cfrac{1}{(z+1)^2}=(-\cfrac{f1}{z+2})'$
                + $-\cfrac{1}{z+2}=-\cfrac{1}{(z+1)+1}=-\sum_{n=0}^\infty (-1)^{n+1}(z+1)^n$
                + $\Rightarrow \cfrac{1}{(z+2)^2}=\sum_{n=1}^\infty (-1)^{n-1}n(z+1)^{n-1}$
            + Example2: $f(z)=\cfrac{1}{(z^2+1)^2}$, $z_0=0$
                + $|z|<1$
                + $\cfrac{1}{(z^2+1)^2}=(-\cfrac{1}{z^2+1})'\cfrac{1}{2z}$
                + $(\sum_{n=0}^\infty (-1)^n z^2n)'\cfrac{1}{2z}$
                + $=\sum_{n=1}^\infty (-1)^{n+1}z^{2n-1}(2n)\cfrac{1}{2z}$
                + $=\sum_{n=1}^\infty (-1)^{n+1}(2n)z^{2n-2}$
            + Example3: $f(z)=\cfrac{z^2}{(z+1)^2}$, $z_0=1$
                + $|z-1|<2$
                + $f(z)=\cfrac{(z+1)^2-2(z+1)+1}{(z+1)^2}=1-\cfrac{}{z+1}+\cfrac{1}{(z+1)^2}$
                + $\cdots$
+ Laurent Series
    + Laurent Expansion
        + Definition: $C_0+C_1(z-z_0)+C_2(z-z_0)^2+\cdots$(1) and $\cfrac{C_{-1}}{z-z_0}+\cfrac{C_{-2}}{(z-z_0)^2}+\cdots$(2), (1)+(2) called Laurent Series.
            + **Expression:** $\sum\limits_{n=-\infty}^\infty C_n(z-z_0)^n$
        + Convergence Region: 
            + Let $\xi=\cfrac{1}{z-z_0}$, then $(2)=c_{-1}\xi+c_-2\xi^2+\cdots$
            + $|\xi|<\cfrac{1}{r}(0\leq r\le \infty)$ convergent
            + $\Rightarrow$ (2) convergent in $|z-z_0| \ge r(0 \leq r\le \infty$
            + When $r<R$, $r \le |z-z_0| \le R$
                + Especially when $r=0$, $0<|z-z_0|<R$
    + $f(z)=\sum\limits_{n=-\infty}^{+\infty}C_n(z-z_0)^n$ could be derivative by steps within $H$
    + $f(z)$ could be integrate along $C$ within $H$
    + Laurent Expansion Theorem
        + $C_n\cfrac{1}{2\pi i}\oint_C\cfrac{f(\xi)}{(\xi-z_0)^{n+1}}d\xi$
            + $C_n\not ={\cfrac{f^{(n)}(z_0)}{n!}}$
        + Example1: $f(z)=\cfrac{z}{z^2+z-2}$, $z_0=-2$
            + singular point: $z=-2,1$
            + $\rho_0=0$,$\rho_1=3$
            + $0< |z+2|< 3$
            + $\cdots$
            
    + Laurent Expansion Method
        + Expand through exsisted Taylor Expansion $\cfrac{1}{1-z}=\sum\limits_{n=0}^\infty z^n,|z|<1$
            + $z_0$ is an analyic point on $f(z)$
            + Example $f(z)=\cfrac{z}{z^2+z-2}$, $z_0=-1$
                + $f(z)=\sum_{n=-\infty}^\infty C_n(z+1)^n$
                + $f(z)=\cfrac{z}{(z+2)(z-1)}=\cfrac{a}{z+2}+\cfrac{b}{z-1}=\cfrac{1}{3}(\cfrac{2}{z+2}+\cfrac{1}{z-1})$
                    + (1) $\cfrac{2}{z+2}=\cfrac{2}{(z+1)+1}=\sum_{n=0}^\infty(-1)^n(z+1)^n$
                    + (1) $\cfrac{1}{z-1}=\cfrac{1}{(z+1)-2}=\cfrac{1}{2}\sum_{n=0}^\infty(\cfrac{z+1}{2})^n$
                    + (2) $\cfrac{2}{z+2}=\cfrac{2}{(z+1)+1}=\cfrac{2}{z+1}\sum_{n=0}^\infty(-1)^n(\cfrac{1}{z+1})^n$
                    + (2) $\cfrac{1}{z-1}=\cfrac{1}{(z+1)-2}=\cfrac{1}{2}\sum_{n=0}^\infty(\cfrac{z+1}{2})^n$
            + Example: $f(z)=\sin \cfrac{1}{z}$, $z_0=0$
                + $0<|z|<+\infty$, $f(z)=\sum C_n z^n$
                + $\sin \frac{1}{z}=\sin t(t=1/z)=\sum_{n=0}^\infty (-1)^n\cfrac{z^{2n+1}}{(2n+1)!}$, $0<|t|<\infty$
                + $\cdots$
        + Integrate/Derivate by steps within domain region
            + Example $f(z)=\cfrac{1}{(z+2)^2}$
                + $f(z)=-(\cfrac{1}{z+2})'$, $z_0=-1$
                + $\cfrac{1}{z+2}=\cfrac{1}{1+(z+1)}=\cfrac{1}{z+1}\cfrac{1}{1+\frac{1}{z+1}}=\cfrac{1}{z+1}\sum_{n=0}^\infty(-1)^n(\cfrac{1}{z+1})^n=\sum_{n=0}^\infty(-1)^{n++1}(\cfrac{1}{z+1})^{n+1}$
                + $(-\cfrac{1}{z+2})'=\sum (-1)^{n+1}(\cfrac{1}{z+1})^n(-\cfrac{1}{(z+1)^2})$
        + Integrate
            + $\oint_Cf(z)dz=\oint_{C_1}f(z)dz+\oint_{C_2}f(z)dz$
            + $\oint_{C_1}f(z)dz ==\oint_{C}\sum_C_n(z-z_0)^n$
                + $f(z)=\sum_{n=0}^\inftyC_n(z-z_0)^n+\sum_{n=-\infty}^{-1}c_n(z-z_0)^n$
                    + **Analytic Part** + **Main Part**
            + $=\sum_{n=-\infty}^\infty \oint_{C_1}C_n(z-z_1)^ndz$
            + $=\sum_{n=0}^\infty\oint_{C_1}C_n(z-z_0)^n+\sum_{n=-\infty}^{-1}\oint_{C_1}C_n(z-z_0)^ndz$
            + $=\sum_{n=-\infty}^{-1}\oint_{C_1}C_n(z-z_0)^ndz$
            + $=\sum_{n=1}^\infty C_{-n}\oint_{C_1}\cfrac{1}{(z-z_0)^n}$
            + $=C_{-1}2\pi i$
+ Residue: $\text{Res}[f(z),z_0]=C_{-1}$
    + Residue Theroem: $\oint_Cf(z)dz=2\pi i\sum_{k=1}^n\text{Res}[f(z),z_k]$
    + Isolated Singularity
        + Classification of Isolated Singularity    
            + Removable Singularity 
                + Main part of $f(z)$ equals to 0, $f(z)=C_0+C_1(z-z_0)+\cdots$, $0<|z-z_0|<R$
                + Append definition $f(z_0)=\lim\limits_{z\to z_0}f(z)=C_0$ then $f(z)$ analytic on $z_0$.
                + Example 1:  Prove that $z=0$ is the removable singularity of $f(z)=\cfrac{\sin z}{z}$
                    + Singularity: $z_0=0$, $0<|z|<+\infty$
                    + $f(z)=\cfrac{1}{z}\sum_{n=0}^\infty(-1)^n\cfrac{z^{2n+1}}{(2n+1)!}$
                    + $\cdots$
                + Th: $z_0$ is the removable singularity of $f(z)$ $\Leftrightarrow$ $\lim\limits_{z\to z_0}f(z)=C_0 (\not ={\infty})$
                + **L'Hospital Rule**: $\lim\limits_{z\to z_0}\cfrac{f(z)}{g(z)}=\lim\limts_{z\to z_0}\cfrac{f'(z)}{g'(z)}$
                + $f(z)=\cfrac{\sin z}{z}$, $z_0=0$
                + $f(z)=\cfrac{e^z-1}{z}$, $z_0=0$
                + $f(z)=\cfrac{1}{e^z-1}-\cfrac{1}{z}$, $z_0=0$ is removable singularity
            + Pole Singularity 
                + $f(z)=\cfrac{C_{-m}}{(z-z_0)^m}+\cdots+ \cfrac{C_{-1}}{z-z_0}+C_0+C_1(z-z_0)+\cdots$ and $C_m\not ={0}$, then $z_0$ is the m-order pole singularity of $f(z)$ 
                + Example: prove that $z=0$ is the 2018-order polar singularity of $f(z)=\cfrac{e^z-1}{z^{2019}}$
                    + $z_0=0$
                    + $f(z)=\cfrac{1}{z^{2019}}(-1+ 1+\cfrac{z^2}{2!}+\cfrac{z^3}{3!}+\cdots$
                    + $\cdots$
                + methods 
                    + $z=z_0\Leftrightarrow \lim_{z\to z_0}f(z)=\infty$, $\cfrac{1}{0}=\infty, \cfrac{1}{\infty}=0, a\cdot \infty=\infty$
                        + Example: $f(z)=\cfrac{e^z-1}{z^{2019}}$
                            + $\lim\limits_{z\to 0}\cfrac{e^z-1}{z^2019}=\lim\limits\cfrac{e^z}{2019z^{2018}}=\infty$
                    + $z_0$ is the pole singularity of $f(z)\Leftrightarrow f(z)$ can be expressed as $f(z)=\cfrac{\phi(z)}{(z-z_0)^m}$ and $\phi(z)$ analytic in $z_0$ and $\phi(z_0)\not ={0}$
                        + Requirements
                            + Polynomial denominator 
                            + **Important:** $\frac{1}{0}$
                        + Example: $f(z)=\cfrac{1}{z^2(z-1)}$, $z_0=0$
                            + $f(z)=\cfrac{\frac{1}{z-1}}{z^2}$
                            + 2-order
                    + $z_0$ is m-order pole singularity of $f(z)\Leftrightarrow z_0$ is m-order 0-point of $g(z)=\cfrac{1}{f(z)}$
                        + Example: $f(z)=\cfrac{1}{e^z-1}$, $z_0=2k\pi i$
                            + $g(z)=e^z-1$
                            + $g^{(1)}(z)=e^z$
                            + $g^{(1)}(2k\pi i)=0$
                            + 1-order
                        + Example 2: $f(z)=\cfrac{z-1}{z(e^z-1)}$
                            + $z_0=0$ or $2k\pi i$
                            + $z_0=0$
                                + $g(z)=\cfrac{z(e^z-1)}{z-1}=\cfrac{1}{z-1}h(z)$
                                + $h(z)=z(e^z-1)$
                                + $g'(z)=(\cfrac{1}{z-1})'h(z)+(\cfrac{1}{z-1})h'(z)$
                                + $g'(0)=(\cfrac{1}{0-1})h'(0)=0$
                                + $g''(0)=(\cfrac{1}{z-1})''h(z)+(\cfrac{1}{z-1})'h'(z)+\cfrac{1}{z-1}h''(z)\Leftrightarrow g''(0)=0\Leftrightarrow h''(0)=0$
                        + $\sin z=\cfrac{e^{iz}-e^{-iz}}{2i}$
                + $f(z)=g(z)h(z)$ where $g(z)$ is removable singularity and $f(z)$ is m-order pole singuarity, then $f(z)$ is m-order pole singularity
                    + $f(z)=\cfrac{\sin z}{z(e^z-1)}=\cfrac{\sin z}{z}\cdot \cfrac{1}{e^z-1}$
            + Essential Singularity 
                + $f(z)=\cdots + \cfrac{C_{-m}}{(z-z_0)^m}+ \cdots$
                + $z=0$, $f(z)=e^{\frac{1}{z}$, $\sin\cfrac{1}{z}$, $\cos \cfrac{1}{z}$
    + Residue of removable singularity: $Res[f(z),z_0]=C_{-1}=0$
        + $Res[\cfrac{z}{e^z-1}]=0$, $\oint_{|z|=10}\cfrac{z}{e^z-1}dz=2\pi i*$
    + Residue of essential singularity: solve with Laurent Expansion
        + Example: $f(z)=\cos\cfrac{1}{z}$
            + $f(z)=1-\cfrac{1}{2!}(1\2)^2$
            + 0
        + Example: $f(z)=\cfrac{z^3}{1+z}e^{\cfrac{1}{z}}$
            + $z=0$
                + $f(z)=(z^3(1-z+z^2-z^3\cdots))(1+\cfrac{1}{z}+\cfrac{1}{2!z}+\cdots)$
                + $=(\cfrac{1}{4!}-\cfrac{1}{5!}+\cfrac{1}{6!}-\cdots)\cfrac{1}{z}+ \cdots$
                + $=(e^{-z}-\cfrac{1}{2!}+\cfrac{1}{3!})(1/z)+\cdots$


    