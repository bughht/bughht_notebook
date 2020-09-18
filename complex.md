+ $$ f'(z_0)=\lim_{\Delta z\to 0}\cfrac{\Delta w}{\Delta z}$$
+ $$\cfrac{\Delta w}{\Delta z}=f'(z_0)+\eta(\Delta z)\Delta z$$
+ $$Prove  f(z)=z^2 \text{is derivatable and } (z^2)'=2z$$
    $\cfrac{\Delta w}{\Delta z}=\cfrac{(z+\Delta z)^2-z^2}{\Delta z}=\cfrac{2z\Delta z+\Delta z^2}{\Delta z}$
    add lim
    $$=2z$$

+ $$f(z)=\overline{z}, Re z, Im z, |z| \text{ continuous on }z$$
+ $$ u(x,y) \text{is derivatable at }(x,y)\Leftrightarrow \Delta u=A\Delta x+B\Delta y+o(\sqrt{(\Delta x)^2+(\Delta y)^2})$$ 
+ $$f(z)=u(x,y)+iv$$
    + $$u(x,y),v(x,y) \text{is differentiable at }(x,y)$$
    + $$u(x,y), v(x,y) \text{ supports } u_x=v_y, u_y=-v_x\textbf{  C-R Euqation}$$
+ $$\text{if f(z) is derivatable at z, }f'(x)=u_x+iv_x=v_y+iv_x=u_x+iu_y=v_y-iu_y$$
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

        
