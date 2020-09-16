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

