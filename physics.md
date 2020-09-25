# Physic 
+ Thermodynamic System (System)
    + open system
    + closed system
    + isolated system
+ State parameter
    + microscopic quantity
    + macroscopic quantity
+ 1 bar=$10^5$ Pa
+ 1 atm=$1.013\times 10^5$ Pa
+ 1 mmHg=1 torr=133.3 Pa
+ Avogadro constant: $N_A\approx 6.0221367\times 10^{23}mol^{-1}$
+ Ideal Gas: $C=\cfrac{pV}{T}=\cfrac{p_0V_0}{T_0}=\cfrac{p_0}{T_0}\cfrac{m}{M}V_m$
    + $R=\cfrac{p_0V_m}{T_0}=8.31 J\cdot mol^{-1}\cdot K^{-1}=0.082 atm\cdot L\cdot mol^{-1}\cdot K^{-1}$
    + Equation of state for ideal gases: $pV=\cfrac{m}{M}RT$
    + $p=\cfrac{m}{M}\cfrac{RT}{V}=\cfrac{m_0N}{m_0V}\cfrac{R}{N_A}T=nkT$
        + Boltzmann constant: $k=\cfrac{R}{N_A}=1.38\times 10^{-23} J\cdot K^{-1}$
        + number density of molecule: $n=\cfrac{N}{V}$
+ $\overline{v_x^2}=\overline{v_y^2}=\overline{v_z^2}=\cfrac{1}{3}\overline{v^2}$
    + $\overline{\epsilon}_{kt}=\cfrac{1}{2}m_0\overline{v^2}$
    + Pressure of Ideal Gas: $p=\cfrac{1}{3}nm_0\overline{v^2}=\cfrac{2}{3}n\overline{\epsilon}_{kt}$
+ Temperature function: $\overline{\epsilon}_{kt}=\cfrac{1}{2}m_0\overline{v^2}=\cfrac{3}{2}kT$
    + $T=\cfrac{2}{3}\cfrac{\overline{\epsilon}_{kt}}{k}$
+ Root-mean-square Speed: $v_{rms}=\sqrt{\overline{v^2}}=\sqrt{\cfrac{3kT}{m_0}}=\sqrt{\cfrac{3RT}{M}}$
    + Absolute Zeor Temperature: $T=0K$, $\overline{\epsilon}_{kt}=0$
+ Degree of Freedom of Gas Molecule
    + Monoatomic molecule: $i=3$
    + Ridge diatomic molecule: $i=5$
    + Ridge polyatomic molecule: $i=6$
+ $\overline{\epsilon}_k=\cfrac{i}{2}kT$
+ Internal Energy of Ideal Gas: $E=\cfrac{m}{M}E_m=\cfrac{m}{M}\cfrac{i}{2}RT$
+ Speed distribution function: $f(v)=\cfrac{dN}{Ndv}$
+ Maxwell speed distribution function: $f(v)=4\pi \bigg(\cfrac{m_0}{2\pi kT}\bigg)^{3/2}e^{-m_0v^2/2kT}v^2$
    + Nomalizing conditon of Speed distribution function: $\int_0^{\infty}f(v)dv=1$
    + Most probable speed: $v_p=\sqrt{\cfrac{2kT}{m_0}}=\sqrt{\cfrac{2RT}{M}}\approx 1.41\sqrt{\cfrac{RT}{M}}$
    + Mean speed: $\overline{v}=\sqrt{\cfrac{8kT}{\pi m_0}}=\sqrt{\cfrac{8RT}{\pi M}}\approx 1.60\sqrt{\cfrac{RT}{M}}$
    + Mean squared speed: $\overline{v^2}=\cfrac{3kT}{m_0}=\cfrac{3RT}{M}$
    + Root mean squared speed: $v_{rms}=\sqrt{\overline{v^2}}=\sqrt{\cfrac{3kT}{m_0}}=\sqrt{\cfrac{3RT}{M}}\approx 1.73\sqrt{\cfrac{RT}{M}}$
+ Boltzmann Distribution Law: $f(v)=4\pi \bigg( \cfrac{m_0}{2\pi kT}\bigg)^{3/2}e^{-\frac{\epsilon_t}{kT}}v^2$
    + $n=\cfrac{dN'}{dxdydz}=n_0e^{-\frac{\epsilon_p}{kT}}$
    + Isothermal Pressure Formula: $p=p_0 e^{-\frac{m_0gz}{kT}}=p_0e^{-\frac{Mgz}{RT}}$
+ Mean Free Path and Mean Collision Frequency
    + Mean Collision Frequency: $\overline{z}=\sqrt{2}\sigma\overline{v}n=\sqrt{2}\pi d^2\overline{v}n$
    + Mean Free Path: $\overline{\lambda}=\cfrac{1}{\sqrt{2}\sigma n}=\cfrac{1}{\sqrt{2}\pi d^2 n}$
        + for ideal gas $p=nkT$, $\overline{\lambda}=\cfrac{kT}{\sqrt{2}\pi d^2 p}$
+ Quasi-steady Theromodynamics Process
    + Volume work: $dW=pDV$
        + $W=\int dW=\int_{V_1}^{V_2}pdV$
        + Work is a quantity of process.
+ First law of thermodynamics: $Q=\Delta E+W$
    + $dQ=dE+dW$
    + for quasi-steady process: $dQ=dE+pdV$
+ Heat Capacity: $C=\lim \cfrac{\Delta Q}{\Delta T}=\cfrac{dQ}{dT}$
    + Specific Heat Capacity: $c (K^{-1}\cdot kg^{-1})$
    + Molar Heat Capacity: $(J\cdot K^{-1}\cdot mol^{-1})$
    + $C_{V,m}=(\cfrac{dQ_m}{dT})_V$
    + $C_{p,m}=(\cfrac{dQ_m}{dT})_p$
    + $E_m=\cfrac{i}{2}RT$
        + $C_{V,m}=\cfrac{i}{2}R$
        + **Mayer Formula:** $C_{p,m}=C_{V,m}+R$
    + Molar Heat Ratio: $\gamma=\cfrac{C_{p,m}}{C_{V,m}}$
+ Isochoric Process: $Q_v=\Delta E=\cfrac{m}{M}C_{V,m}(T_2-T_1)$
+ Isobraic Process: $\Delta E=Q_p-W=\cfrac{m}{M}C_{p,m}(T_2-T_1)-\cfrac{m}{M}R(T_2-T_1)=\cfrac{m}{M}=(C_{p,m}-R)(T_2-T_1)=\cfrac{m}{M}C_{V,m}(T_2-T_1)$
+ Isothermal Process: $Q_T=W=\cfrac{m}{M}RT\ln\cfrac{V_2}{V_1}=\cfrac{m}{M}RT\ln\cfrac{p_1}{p_2}$
+ Adiabatic Process
    + $\Delta E=-W=\cfrac{m}{M}C_{V,m}(T_2,T_1)$
    + Poisson Formula: $pV^{\gamma}=C_1$
        + $TV^{\gamma-1}=C_2$
        + $p^{\gamma-1}T^{-\gamma}=C_3$
    + Ideal Gas turn from $(p_1,V_1)$, for its middle $(p,V)$
        + $p=\cfrac{p_1V_1^{\gamma}}{V^{\gamma}}$
        + $W=\cfrac{p_1V_1}{\gamma-1}\big[1-\big(\cfrac{V_1}{V_2}\big)^{\gamma-1}\big]$
        + $W=\cfrac{1}{\gamma-1}(p_1V_1-p_2V_2)$
+ All above are bullshit, **Watch this**
||||