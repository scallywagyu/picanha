---
{"dg-publish":true,"permalink":"/14th-term/correlation-exam-ch-195/physical-chemistry-review/","tags":["gardenEntry"]}
---


# Physical Chemistry Review
__________________
- [[13th Term/Physical Chemistry/Problem Set Part 2\|Problem Set Part 2]]
- [[13th Term/Physical Chemistry/Problem Set 2\|Problem Set 2]]
- [[13th Term/Physical Chemistry/Problem Set 1\|Problem Set 1]]
- [[13th Term/Physical Chemistry/M2 Exam\|M2 Exam]]
- [[13th Term/Physical Chemistry/M1 Examination CH116P\|M1 Examination CH116P]]
- [[13th Term/Physical Chemistry/January 26, 2023 Recitation CH116P\|January 26, 2023 Recitation CH116P]]
- [[13th Term/Physical Chemistry/January 24, 2023 Meeting\|January 24, 2023 Meeting]]
- [[10th Term/CH138X/CH127X Reviewer\|CH127X Reviewer]]
- [[13th Term/Physical Chemistry/Shorthand Avenue\|Shorthand Avenue]]
- [[13th Term/Physical Chemistry/Question Bank\|Question Bank]]
- [[13th Term/Physical Chemistry/Query Depot\|Query Depot]]
- [[13th Term/Physical Chemistry/Just a spot of tea\|Just a spot of tea]]
- [[13th Term/Physical Chemistry/Electrochemical Systems\|Electrochemical Systems]]

{ .block-language-dataview}
****
![[PhyChemModule.ipynb]]
****
## Fluid Properties
````col
```col-md
> [!abstract] Volumetric Properties
> $$\begin{matrix} \underline{\text{For liquids:}} \\  \\  \text{ln}\begin{pmatrix} \dfrac{V_{2}}{V_{1}} \end{pmatrix}\approx  \underline{\beta \begin{pmatrix} T_{2}-T_{1} \end{pmatrix}}- \underline{\kappa \begin{pmatrix}P_{2}-P_{1} \end{pmatrix}} \\  \\ \begin{pmatrix}\dfrac{\partial V}{\partial T}\end{pmatrix}_{P}=\beta V \hspace{1cm} \fbox{Page 2-356} \\  \\ \begin{pmatrix}\dfrac{\partial V}{\partial P}\end{pmatrix}_{T}=-\kappa V  \hspace{1cm} \fbox{Page 2-259} \\  \\  \\ \underline{\text{For fluids (liquids and gases):}} \\  \\  \text{Equations of State} \\ \fbox{Page 2-349} \end{matrix}$$

```
```col-md
> [!important] Thermodynamic Properties
> $$\begin{matrix} \underline{\text{In terms of compressibility}} \\ \underline{\text{and expansivity:}} \\   \\  dH=C_{P} \space  dT+ \begin{pmatrix}1-\beta T \end{pmatrix}V \space  dP \\  \\ dS=\dfrac{C_{P}}{T}\space  dT- \beta V \space  dP  \end{matrix}$$

> [!info] Maxwell Relations
> $$\begin{matrix} \fbox{Page 3-19} \\  \fbox{Page 4-9} \\  \\ \dfrac{\partial}{\partial y}\begin{pmatrix}\dfrac{\partial z}{\partial x}\end{pmatrix}=\dfrac{\partial}{\partial x}\begin{pmatrix}\dfrac{\partial z}{\partial y}\end{pmatrix}=\dfrac{\partial^{2}z}{\partial x \partial y}=\dfrac{\partial^{2}z}{\partial y \partial x} \end{matrix}$$


```
```col-md
> [!example] Molecular Speeds
> $$\begin{matrix} v_{\text{mp}}=\sqrt{\dfrac{2RT}{M}}  \\  \\ v_{\text{ave}}=\sqrt{\dfrac{8RT}{\pi M}} \\  \\ v_{\text{rms}}=\sqrt{\dfrac{3RT}{M}} \end{matrix}$$

> [!quote] Molecular Collisions
> $$\begin{matrix} l=\dfrac{kT}{\sqrt{2}\sigma P}=\dfrac{1}{\sqrt{2}\pi d^{2}n^{\star}} \\  \\ n=\dfrac{v}{l} \hspace{1cm}  z=\dfrac{nn^{\star}}{2} \end{matrix}$$



```
````
****
## Gas Laws
````col
```col-md
$$\begin{matrix} \fbox{Boyle's Law} \\  \\ P_{1}V_{1}=P_{2}V_{2} \\   \\   \end{matrix}$$
- At *constant* ==temperature==

```
```col-md
$$\begin{matrix} \fbox{Charles' Law} \\  \\ \dfrac{V_{1}}{T_{1}}=\dfrac{V_{2}}{T_{2}}  \end{matrix}$$
- At *constant* ==pressure==

```
```col-md
$$\begin{matrix} \fbox{Gay-Lussac's Law} \\  \\ \dfrac{P_{1}}{T_{1}}=\dfrac{P_{2}}{T_{2}} \end{matrix}$$
- At *constant* ==volume==

```
````
````col
```col-md
$$\begin{matrix} \fbox{Combined Gas Law} \\  \\ \dfrac{P_{1}V_{1}}{T_{1}}=\dfrac{P_{2}V_{2}}{T_{2}} \end{matrix}$$
- Gases under different conditions

```
```col-md
$$\begin{matrix} \fbox{Avogadro's Law} \\  \\ \dfrac{V_{1}}{n_{1}}=\dfrac{V_{2}}{n_{2}} \end{matrix}$$
- At *constant* ==temperature== and ==pressure==

```
```col-md
$$\begin{matrix} \fbox{Ideal Gas Law} \\  \\  PV=nRT \end{matrix}$$
- Applies to *ideal gases*, which obey all other laws perfectly
- Real gases ***deviate*** at *high pressures* or *low temperatures*

```
````
## Intrinsic And Extrinsic Properties
### Pressure-Volume-Temperature Relationships
````col
```col-md

> [!example] Boyle's Law
> $$\begin{matrix} P_{1}V_{1}=P_{2}V_{2} \\   \\   \end{matrix}$$
> - At *constant* ==temperature==

****
- The **Boyle temperature** is the range of temperature where the real gas approaches ==ideal gas behavior==
> - If ==$B=0$==, then ==$Z=1$== *(ideal gas compressibility factor)*
****
- Generalized compressibility relationships *(correlations)* are faster and more convenient to use, but my yield values ==far from the actual values==
> - These *correlations* are based on the **Virial equation of state**
> $$\begin{matrix}\fbox{Virial Equation of State} \\  Z=\dfrac{Pv}{RT} \\  \\ Z=1+\dfrac{B'P}{RT}+\dfrac{C'P^{2}}{RT}+... \end{matrix}$$

****

![Pasted image 20240923133503.png](/img/user/14th%20Term/Correlation%20Exam%20(CH195)/Attachments/Pasted%20image%2020240923133503.png)
<i><center>Pressure-volume-temperature chart</i></center>

```
```col-md
flexGrow=2
===
- When a piston expands against an external pressure, *expansion* **work** is done
> $$\begin{matrix} W_{\text{ext}}=- \int\limits^{}_{}p \space  dV \end{matrix}$$
> - This process is *reversible*
> ****
> ![Pasted image 20240923131020.png](/img/user/14th%20Term/Correlation%20Exam%20(CH195)/Attachments/Pasted%20image%2020240923131020.png)
> ****
> - For an ==ideal gas== undergoing *isothermal* ***expansion***
> 
> $$\begin{matrix} \begin{matrix} W_{\text{ext}}=-nRT \text{ ln}\begin{pmatrix}\dfrac{V_{2}}{V_{1}}\end{pmatrix} \end{matrix} & \hspace{1cm}  & \begin{matrix} W_{\text{ext}}=-nRT \text{ ln}\begin{pmatrix}\dfrac{P_{1}}{P_{2}}\end{pmatrix} \end{matrix} \end{matrix}$$
> - This process is still *reversible*

- PVT partial derivatives give important properties for the ***expansion***/***compression*** of gases
> $$\begin{matrix} \begin{matrix} \begin{matrix} \fbox{Expansion Coefficient} \\ \alpha=\dfrac{1}{V} \begin{pmatrix}\dfrac{\partial V}{\partial T}\end{pmatrix}_{P}  \end{matrix} & \hspace{1cm}  & \begin{matrix} \fbox{Isothermal Compressibility} \\ \kappa=-\dfrac{1}{V}\begin{pmatrix}\dfrac{\partial V}{\partial T}\end{pmatrix}_{T} \\  \\ \underline{\underline{-\kappa \begin{pmatrix}P_{2}-P_{1} \end{pmatrix}=\text{ln}\begin{pmatrix}\dfrac{V_{2}}{V_{1}}\end{pmatrix}}} \end{matrix} \end{matrix} \\  \\  \\  \begin{matrix} \fbox{Volume Expansion} \\ \beta=\dfrac{1}{V}\begin{pmatrix}\dfrac{\partial V}{\partial T}\end{pmatrix}_{P} \\  \\ \underline{\underline{\beta \begin{pmatrix}T_{2}-T_{1} \end{pmatrix}=\text{ln}\begin{pmatrix}\dfrac{V_{2}}{V_{1}}\end{pmatrix}}} \end{matrix} \end{matrix}$$
> ##### where:
> - **Expansion coefficient $(\alpha)$** measures how much a substance's <u>volume</u> ***expands*** or ***contracts*** as the ==temperature changes== at *constant pressure*
> - **Isothermal compressibility $(\kappa)$** measures how much a substance's <u>volume</u> ***changes*** as the ==pressure is changed== at *constant temperature*
> - **Volume expansivity $(\beta)$** measures the ***changes*** in <u>volume</u> in terms of both ==pressure== and ==temeprature==


```
````
****
#### Equations of State
- **Equations of state** detail the gases' behavior outside of *ideality*
````col
```col-md
$$\begin{matrix} \fbox{Ideal Gas Law} \\ \begin{matrix} P \overline{V}=RT & \text{or} & Z=\dfrac{P \overline{V}}{RT} \end{matrix} \\  \\ \overline{V}=Z \begin{pmatrix}\dfrac{RT}{P}\end{pmatrix}=\overline{V}_{\text{ig}}   \\  \\ \text{where:}  \\ Z \text{ is the }\colorbox{#FD8E7F}{\color{black}{compressibility factor}} \end{matrix}$$



- The easiest assumption to make for a gas, is that it behaves ==ideally==
- An **ideal gas** is a gas that has
> - *Negligible* ***atomic volume*** ==$(b=0)$==
> - *Negligible* ***intermolecular forces*** ==$(a=0)$==

****

##### MOSS Method (Calculator)
1) Get the ideal gas volume
2) Use it as the initial molar volume $v$
3) In the following iterations, substitute $v$ with the ==$\text{ans}$ function== until ***convergence***
- Not all roots of the cubic equation of state are useful
- Do not use ==$\text{Shift + Solve}$== to determine molar volumes
> - There can be up to 3 real roots and only a maximum of 2 values are useful
- MOSS is best at determining the useful values of $Z$

****
- ##### Van der Waals Equation
> $$\begin{matrix} \fbox{Van der Waals}  \\  P=\dfrac{RT}{\overline{V}-b}-\dfrac{a}{\overline{V}^{2}} \end{matrix}$$
- ##### Virial Equation
> $$\begin{matrix} \fbox{Virial Equation} \\ \dfrac{P \overline{V}}{RT} =1+ \dfrac{B}{\overline{V}}+\dfrac{C}{\overline{V}^{2}}+... \end{matrix}$$

```
```col-md
flexGrow=1.75
===






- ##### The **cubic equation of state** can be transformed into a specific model based on the parameters substituted into it
> $$\begin{matrix} \fbox{General Cubic Equation of State} \\  P=\dfrac{RT}{\overline{V}-b}-\dfrac{a}{(\overline{V}+ \epsilon b)(\overline{V}-\sigma b)} \\  \\ a=\Psi \dfrac{\alpha R^{2}T_{c}^{2}}{P_{c}} \\  \\ b=\Omega \dfrac{RT_{c}}{P_{c}}  \end{matrix}$$
> - The **cubic equation of state** ***corrects*** for both ==volume $(b)$== and ==intermolecular forces $a$==
> > - Accounting for these factors, makes the predicted gas behavior *more realistic*
> ****
>
> | Eqn. of State | $\alpha(T_{r})$ | $\sigma$ | $\epsilon$ | $\Omega$ | $\Psi$ | $Z_{c}$ |
> | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
> | vdW (1873) | 1 | 0 | 0 | 1/8 | 27/64 | 3/8 |
> | RK (1949) | $T_{r}^{-1 \text{/}2}$ | 1 | 0 | 0.08664 | 0.42748 | 1/3 |
> | SRK (1972) | $\alpha_{\text{SRK}}(T_{r}; \omega)$ | 1 | 0 | 0.08664 | 0.42748 | 1/3 |
> | PR (1976) | $\alpha_{\text{PR}}(T_{r}; \omega)$ | $1+\sqrt{2}$ |$1-\sqrt{2}$  | 0.07780 | 0.45724 | 0.30740 |
> 
> $$\begin{matrix}\underline{\text{Some examples:}} \\  \\  \alpha_{\text{SRK}}(T_{r}; \omega)=\begin{bmatrix} 1+(0.480+1.574 \omega - 0.176 \omega^{2})(1-T_{r}^{1 \text{/}2}) \end{bmatrix}^{2} \\  \\ \alpha_{\text{PR}}(T_{r}; \omega)=\begin{bmatrix}1+(0.37464+1.54226\omega-0.26992\omega^{2})(1-T_{r}^{1 \text{/}2}) \end{bmatrix}^{2} \end{matrix}$$
>  
> ****
> $$\begin{matrix} \fbox{Vapor Form} \\ Z=1 + \beta - q \beta \dfrac{Z-\beta}{\begin{pmatrix}Z+\epsilon \beta \end{pmatrix}\begin{pmatrix}Z + \sigma \beta \end{pmatrix}} \end{matrix}$$
> $$\begin{matrix} \hline  \\ \beta=\dfrac{bP}{RT} \hspace{2cm} q=\dfrac{a}{bRT} \\  \\ \hline \end{matrix}$$
> $$\begin{matrix} \fbox{Liquid Form} \\ Z=\beta + \begin{pmatrix} Z+ \epsilon \beta \end{pmatrix}\begin{pmatrix} Z+\sigma \beta \end{pmatrix}\begin{pmatrix}\dfrac{1+\beta -Z}{q \beta}\end{pmatrix}  \end{matrix}$$



```
````
****
### Enthalpy & Internal Energy
- **Enthalpy** is the measure of energy in open systems where *heat* is ***transferred*** from the ==system== to the ==surroundings (universe)==
````col
```col-md

$$\begin{matrix} \fbox{Joule-Thomson Coefficient} \\ \begin{matrix}  \mu_{JT} & = & \begin{pmatrix}\dfrac{\partial T}{\partial P}\end{pmatrix}_{H} \end{matrix} \end{matrix}$$
- A gas undergoing an *isenthalpic process $(\Delta H  =0)$* will experience a *temperature* ***change*** as the ==pressure changes==
> - In a ***throttling*** process, the ==pressure== of the ==gas== decreases 📉
> > - Pressure turns into kinetic energy *(therefore a rise in temperature)*
- This change in temperature can be predicted using the **Joule-Thomson coefficient $(\mu_{\text{JT}})$**
> - ==For ideal gases:== $\mu_{\text{JT}}=0$
> > - Ideal gas enthalpy is *independent* of ==pressure==
> - ==For real gases:== $\mu_{\text{JT}}=\pm  \mu_{\text{JT}}$
> > - *Negative $[-\mu_{\text{JT}}]$* means an ***increase*** in temperature 🌡️
> > - *Positive $[+\mu_{\text{JT}}]$* means a ***decrease*** in temperature 📉🧊

```
```col-md
flexGrow=2
===
$$\begin{matrix} H & = & U & + & PV \end{matrix}$$


- **Enthalpy** is a *state function*, resigning the significance of their values only at the ==initial== and ==final states==
> ![Pasted image 20240102002651.png](/img/user/10th%20Term/CH138X/Attachments/Pasted%20image%2020240102002651.png)
> - ***Enthalpy change*** can be divided into the contributions of temperature and pressure




- For an ideal gas *(where pressure is constant)*, the total enthalpy is
> $$\begin{matrix}  H  & = & \Delta H_{f} \degree  & + &   \int\limits^{T}_{\text{298.15K}}C_{P}\space  dT \end{matrix}$$
> ##### where:
> - $\Delta H_{f} \degree$ is the ==standard enthalpy of formation==
> - $C_{P}$ is the ==molar heat capacity==
> ****
> - For process changes, the change in enthalpy is calculated as
> $$\begin{matrix} \Delta H  & = & \int\limits^{T_{2}}_{T_{1}}C_{P} \space  dT   & = &  C_{P,\text{ave}} \Delta T \end{matrix}$$
> ****
> - ==Case 1:== $C_{P}$ is *constant*
> > $$\begin{matrix} \Delta H  & = & \Delta C_{P}^{\text{ig}}\Delta T \end{matrix}$$
> - ==Case 2:== $C_{P}$ has a defined temperature function
> > $$\begin{matrix} \Delta H & = & \int\limits^{T_{2}}_{T_{1}} \underset{C_{P}}{\underline{a + bT + cT^{2}}} \space  dT \end{matrix}$$
> - ==Case 3:== Averaging $C_{P}$ is acceptable
> > $$\begin{matrix} \begin{matrix} \Delta H   & = & C_{P,\text{ave}} \Delta T \end{matrix} \\  \\ C_{P,\text{ave}}=\dfrac{C_{P,T_{1}}+C_{P,T_{2}}}{2} \end{matrix}$$

- When the temperature is constant for a process, the dependence of enthalpy on pressure is described as:
> $$\begin{matrix} \begin{pmatrix}\dfrac{\partial H}{\partial P}\end{pmatrix}_{T} & = & -T \begin{pmatrix}\dfrac{\partial V}{\partial T}\end{pmatrix} & + & V \end{matrix}$$
> - The change in volume is interpreted in terms of the **volumetric expansion coefficient $(\alpha)$** *(usually given as a numerical quantity)*
> > $$\begin{matrix} \underline{\alpha=\dfrac{1}{V}\begin{pmatrix}\dfrac{\partial V}{\partial T}\end{pmatrix}_{P}} & \hspace{2cm}  \rightarrow \hspace{2cm}   & \begin{matrix} \underline{\underline{\Delta H = \int\limits^{P_{2}}_{P_{1}} V \begin{pmatrix} q- \alpha T \end{pmatrix}\space  dP}} \\  \\ \underset{\text{(Incompressible, constant V)}}{\underline{\underline{\Delta H = V \begin{pmatrix}1 - \alpha T \end{pmatrix}\Delta P}}} \end{matrix} \end{matrix}$$
> > - $\alpha$ is either given as a *numerical quantity* or evaluated using ==equations of state==
> > - For *incompressible* solids and liquids, we can assume that the ==volume== is *independent* of the ==pressure==

```
````
****
- **Internal energy** is the *bulk energy contribution* from the ==molecular activity== of atoms/molecules contained in a substance
````col
```col-md
$$\begin{matrix} H & = & U & + & PV \end{matrix}$$
- Usually used for closed systems

```
```col-md
flexGrow=2
===
- For an ideal gas *(where volume is constant)*, the total internal energy is calculated similarly to the enthalpy
> $$\begin{matrix} U  & = & \Delta U_{f} \degree   & +  & \int\limits^{T}_{\text{298.15K}}C_{V}\space  dT \end{matrix} $$
> - $\Delta U_{f} \degree$ is the ==standard internal energy of formation==
> - $C_{V}$ is the ==molar heat capacity at constant volume==
> ****
> - For process changes, the change in internal energy is calculated as
> $$\begin{matrix} \Delta U & = &  \int\limits^{T_{2}}_{T_{1}} C_{V}\space  dT & = & C_{V,\text{ave}}\Delta T \end{matrix}$$



```
````
****
### Entropy & Gibbs Free Energy 

- A generalized measure of disorder defined by the ==second law of thermodynamics==
````````col
```````col-md

- Entropy change from heat transfer
> $$\begin{matrix} \Delta S= \int\limits^{T_{2}}_{T_{1}}\dfrac{Q_{\text{rev}}}{T}  \hspace{0.5cm} \rightarrow \hspace{0.5cm} \Delta S=\dfrac{\Delta H_{\text{fus}}}{T}  \\  \\ \underline{\text{For an ideal gas:}} \\ \Delta S= \int\limits^{T_{2}}_{T_{1}} \dfrac{C_{P}^{\text{ig}}}{T}\space  dT - R \text{ ln}\begin{pmatrix}\dfrac{P_{2}}{P_{1}}\end{pmatrix} \end{matrix}$$


```````
```````col-md
flexGrow=2
===
````col
```col-md
- For liquids and solids, assuming incompressible
> $$\begin{matrix} \Delta S=C_{p} \text{ ln}\begin{pmatrix}\dfrac{T_{2}}{T_{1}}\end{pmatrix} \end{matrix}$$



```
```col-md
- Entropy from lost work *(irreversibility)*
> $$\begin{matrix} \dot{S}_{\text{gen}}=\dfrac{\dot{W}_{\text{lost}}}{T_{\text{surr}}}=\dot{m}\Delta s_{fs}-\dfrac{Do  Q}{T_{\text{surr}}} \end{matrix}$$

```
````
````col
```col-md
- Entropy change from *spontaneous* ***mixing*** of two perfect gases
> $$\begin{matrix} \Delta S & = & -nR \begin{bmatrix}x_{1} \text{ ln}\begin{pmatrix}x_{1} \end{pmatrix} & + & x_{2} \text{ ln}\begin{pmatrix}x_{2} \end{pmatrix} \end{bmatrix} \end{matrix}$$

```
````

```````
````````
- **Gibbs free energy** relies on entropy as the criterion for a chemical reaction's spontaneity
````col
```col-md
##### Fundamental:
$$\begin{matrix} \Delta G = \Delta H - T \Delta S \\  \\ \Delta G = \Delta U + P  \Delta V -  T \Delta S \end{matrix}$$

- Quantification of the maximum work that can be obtained in a given system 
- It plays a role in determining spontaneity of processes
> $$\begin{matrix} \Delta G =-RT  \text{ ln }K \end{matrix}$$
> - *(A negative $\Delta G$ means that a process is spontaneous)* 

- **Excess Gibbs free energy** is used in modelling and predicting behavior of mixtures 
> $$\begin{matrix} G^{R}=G-G^{\text{ideal}} \end{matrix}$$


```
```col-md
flexGrow=2
===
- In terms of the equilibrium quotient
> $$\begin{matrix} \Delta G=\Delta G \degree  + RT \text{ ln}(Q) \\  \\ \Delta G \degree  = -RT \text{ ln}(K) \end{matrix}$$
> ##### where:
> - $\Delta G$ is the ==Gibbs free energy==
> - $\Delta G \degree$ is the ==standard change in Gibbs free energy==
> - $R$ is the ==gas constant== *$\begin{pmatrix} 8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix}$*
> - $T$ is the ==temperature== in *$\text{K}$*
> - $Q$ is the ==reaction quotient==
> - $K$ is the ==equilibium constant==

- In terms of volume and pressure
> $$\begin{matrix} \Delta G = V \Delta P \end{matrix}$$
> - Total work done is equal to the Gibbs free energy
- ==Phase rule:== degrees of freedom for equilibrium systems $(F=2-P+C)$

```
````
- **Chemical potential** is a thermodynamic property that measures the tendency of one substance to move from ==one location== to ==another==
````col
```col-md
$$\begin{matrix} \mu_{i}=\mu_{l} \\ T_{1}=T_{2} \\ P_{1}=P_{2} \end{matrix}$$

```
```col-md
flexGrow=2
===
$$\begin{matrix} \Delta \mu=\text{RT}\text{ ln}\begin{pmatrix}\dfrac{P_{2}}{P_{1}}\end{pmatrix} \end{matrix}$$
$$\begin{matrix} \underline{\text{Partial molar Gibbs free energy:}} \\  \dfrac{\partial G}{\partial n} \end{matrix}$$
```
````
****
## System Properties
````col
```col-md
##### Important Assumptions

1) > [!quote] Isochoric Process
> $$\begin{matrix} Q=\Delta U= \int\limits^{T_{2}}_{T_{1}}c_{V} \space  dT \end{matrix}$$
> - ==$\Delta V=0$:== Constant volume

2) > [!quote] Adiabatic Process
> $$\begin{matrix} W=\dfrac{P_{1}V_{1}}{\gamma-1}\begin{bmatrix}\begin{pmatrix}\dfrac{P_{2}}{P_{1}}\end{pmatrix}^\dfrac{\gamma-1}{\gamma}-1 \end{bmatrix} \\  \\ \gamma=\dfrac{c_{P}}{c_{V}} \end{matrix}$$
> - ==$Q=0$:== No heat is released

3) > [!quote] Isobaric Process
> $$\begin{matrix} Q=\Delta H = \int\limits^{T_{2}}_{T_{1}}c_{P} \space  dT \\  \\ W=-R \begin{pmatrix}T_{2}-T_{1} \end{pmatrix} \end{matrix}$$
> - ==$\Delta P=0$:== Constant pressure

4) > [!quote] Isothermal Process
> $$\begin{matrix} \Delta U = \Delta H =0 \\  \\ W=-RT \text{ ln}\begin{pmatrix}\dfrac{V_{2}}{V_{1}}\end{pmatrix} \\  \\ Q=-W \end{matrix}$$
> - ==$\Delta T=0$:== No change in temperature

5) > [!quote] Isntropic Process
> $$\begin{matrix} \Delta S = 0 \\  \\ S_{1}=S_{2} \end{matrix}$$

```
```col-md
flexGrow=1.5
===
- ##### Energy balance in a *closed system*
> $$\begin{matrix} dU  & = & dQ & + & dW \end{matrix}$$
- ##### Reversible Expansion / Compression Work
> $$\begin{matrix} dW & = & -P \space  dV \end{matrix}$$
- ##### Enthalpy
> $$\begin{matrix} H & = & U & + & PV \end{matrix}$$
- ##### Heat Capacity
> $$\begin{matrix} c_{P} & = & \begin{pmatrix}\dfrac{\partial H}{\partial T}\end{pmatrix}_{P}  & \hspace{1cm}  & c_{V} & = & \begin{pmatrix}\dfrac{\partial U}{\partial T}\end{pmatrix}_{V} \end{matrix}$$
- ##### Heat Capacity of Ideal Gases
> $$\begin{matrix} c_{P} & = & c_{V} & + & R \end{matrix}$$
- ##### Process calculations in *ideal gas state*
> $$\begin{matrix} dQ & = & c_{V} \space  dT+\dfrac{RT}{V}\space  dV & = & c_{P}\space  dT - \dfrac{RT}{P}\space  dP \\  \\  \\ dW & = & -\dfrac{RT}{V}\space  dV & = & -R \space  dt+\dfrac{RT}{P}\space  dP \end{matrix}$$
- ##### Calorimetry
> $$\begin{matrix} \begin{matrix} \fbox{Constant-Pressure Calorimetry} \\ \Delta H=q_{P} \end{matrix}\hspace{1cm}  \begin{matrix} \fbox{Constant-Volume Calorimetry} \\ \Delta U = q_{V} \end{matrix} \end{matrix}$$ 
- ##### Hess' Law
> - The standard reaction enthalpy is the sum of the values for the individual reactions into which the overall reaction may be divided
- ##### Standard Enthalpy of Formation
> $$H_{f}\degree=0$$
> - A **pure element** at its *standard state* is defined to have a ***reference standard enthalpy of formation*** of *zero*
> - This statement has wide-ranging implications in the study of reaction thermodynamics
> - Elements can form compounds, and we can determine the enthalpy of formation of the elements
- ##### Standard Enthalpy of Vaporization
> $$\begin{matrix} \Delta H_{\text{vap}}=\dfrac{Q}{n} \end{matrix}$$


```
````
****
## Laws of Thermodynamics
````col
```col-md


```
```col-md
flexGrow=2
===
0) ##### ==Zeroth law of thermodynamics:== states that when **two objects** are in thermal equilibrium with a ***third object***, they are in thermal equilibrium with each other 
> $$\begin{matrix} \text{1st Object = 3rd Object} \hspace{1cm} \text{2nd Object = 3rd Object}\\ \mathbf{1st \space Object = 2nd \space  Object} \end{matrix}$$
1) ##### ==First law of thermodynamics:== The total quantity of energy in the universe stays constant *(law of conservation of energy)*
> $$\begin{matrix} \Delta \begin{bmatrix}\text{Energy} \\ \text{of the} \\ \text{system} \end{bmatrix} & + & \Delta \begin{bmatrix}\text{Energy} \\ \text{of the} \\ \text{surroundings} \end{bmatrix} & = & 0 \end{matrix}$$


```
````
````col
```col-md

- The second law imposes restrictions on the direction the process transforms energy
> 1. Work is readily transformed into other forms of energy such as potential or kinetic energy, often regarded as *useful energy*
> 2. Heat is regarded as *waste energy*
> > - Complete heat conversion into mechanical energy has failed
> > - Heat can be converted into other forms of energy, albeit at a reduced rate
> > - The **Carnot efficiency** states that thermal engines can only have conversion efficiencies at around $30-50\%$ due to practical limitations like friction, turbulence, etc

```
```col-md
flexGrow=2
===
2) ##### ==Second law of thermodynamics:== The entropy *(disorder)* in the universe only ever increases 
> $$\begin{matrix} dS=\dfrac{dQ}{T} \end{matrix}$$
> - The more entropy $\uparrow S$, the less order $\downarrow \text{order}$, the more chaos $\uparrow$
> ****
> $$\begin{matrix} \eta_{C} & = & \dfrac{|W|}{Q_{h}} & = & 1-\dfrac{T_{c}}{T_{h}} \end{matrix}$$
> $$\begin{matrix}\text{COP}=\dfrac{T_{C}}{T_{H}-T_{C}} \\  \\ \text{If you changed }T_{H} \text{ the effect is more substantial} \\  \\ T_{H} \text{ as  }T_{H} \rightarrow T_{C}  \\  \\ \text{COP increases}  \end{matrix}$$
> - The **Carnot cycle** represents the most ideal conversion of fuel (potential energy) into heat, whose efficiency is measured by the its ==hot== and ==cold temperature==
> > ##### <center> Process: </center>
> > 1) *Isothermal* ***expansion***
> > 2) *Adiabatic* ***expansion***
> > 3) *Isothermal* ***compression***
> > 4) *Adiabatic* ***compression***

- The change in entropy in a system is calculated as
> $$\begin{matrix} \Delta S= \int\limits^{T_{2}}_{T_{1}} \dfrac{C_{P}^{\text{ig}}}{T}\space  dT - R \text{ ln}\begin{pmatrix}\dfrac{P_{2}}{P_{1}}\end{pmatrix} \end{matrix}$$

- The entropy can decrease in the systems themselves such as
> - Refrigeration systems
> - Chemical reactions (bond-forming reactions like crystallization)

```
````
````col
```col-md

```
```col-md
flexGrow=2
===
3) ##### ==Third law of thermodynamics:== At absolute zero *$(\text{0 K}=-273.15 \degree  \text{C})$*, the **perfect solid crystaline structure** is ***formed***


```
````
****
## Phase Equilibria
````col
```col-md
> [!example] Henry's Law (For dilute solutions)
> $$\begin{matrix} P_{A}=Hx_{A} \\  \\ \underset{\text{Dalton's Law}}{\underline{y_{A}P_{T}}}=\underset{\text{Henry's Law}}{\underline{Hx_{A}}} \end{matrix}$$
> - The solute has 
> > - A ***partial pressure $P_{A}$***
> > - A ***Henry's constant $H$*** *(for the selected solute)*
> - **Henry's law** becomes *more correct* as it reaches ==infinite dilution $x_{a} \rightarrow 0$==
> > - The solute is in focus


```
```col-md
> [!quote] Dalton's Law
> $$\begin{matrix} P_{A}=y_{A}P_{T} \\ P_{B}=y_{B}P_{T} \end{matrix}$$
> - Only applicable to ==ideal gas/vapor mixtures==
> - A ==*more concentrated* component== in a gas mixture ***contributes*** a ==larger pressure==
> - $y_{A}$ is the ==gas component== of $A$

> [!info] Clapeyron Equation
> $$\begin{matrix} \dfrac{dP}{dT}=\dfrac{\Delta H_{\text{trans}}}{T_{\text{trans}}\Delta \overline{V}_{\alpha \rightarrow \beta}} \\  \\  \\ \underline{\begin{matrix} \text{When one phase is vapor:} \\ (\text{since }V_{v}>>V_{l}>>V_{s}) \end{matrix}} \\  \\ \dfrac{dP}{dT}=\dfrac{\Delta H}{T \cdot \begin{pmatrix}\dfrac{RT}{P}\end{pmatrix}}=\dfrac{P \Delta H}{RT^{2}}    \end{matrix}$$

```
```col-md
> [!important] Raoult's Law (For dilute solutions)
> $$\begin{matrix} P_{B}=x_{B}P_{B}^{\star} \\  \\ \underset{\text{Dalton's Law}}{\underline{y_{B}P_{T}}}=\underset{\text{Raoult's Law}}{\underline{x_{B}P_{B}^{\star}}}  \end{matrix}$$
> - Only applicable for ==ideal solutions==
> - The solvent has
> > - A ***partial pressure $P_{B}$***
> > - A ***vapor pressure $P_{B}^{\star}$***
> - **Raoult's law** becomes *more correct* as the solution becomes a ==pure liquid $x_{B} \rightarrow 1$==
> > - The solvent is in focus
> - $y_{A}$ is the ==liquid component== of $A$

```
````
### Important Phase Diagrams
````col
```col-md
![Pasted image 20240102005711.png](/img/user/10th%20Term/CH138X/Attachments/Pasted%20image%2020240102005711.png)
- **P-v diagrams** are useful for observing phase changes of substances 
- **T-s diagrams** are used primarily for closed loop systems involving the transfer of heat and work 
- **P-h diagrams** are useful for refrigeration calculations

- Additional sources of property data
> - EoS and Correlations 
> - Property Tables
> - Thermodynamic diagrams
> - Perry's Handbook


```
````
****
## Colligative Properties
$$\begin{matrix} \fbox{Van't Hoff Factor} \\ i=\dfrac{\Delta T_{f}}{\begin{pmatrix} \Delta T_{f} \end{pmatrix}_{0}}=\dfrac{\Delta T_{b}}{\begin{pmatrix} \Delta T_{b} \end{pmatrix}_{0}}=\dfrac{\Delta P}{\begin{pmatrix}\Delta P \end{pmatrix}_{0}}=\dfrac{\Pi}{\begin{pmatrix} \Pi \end{pmatrix}_{0}} \end{matrix}$$
````col
```col-md
1) ##### Boiling Point Elevation (BPE)
> $$\begin{matrix} \Delta T_{b}=K_{b}m i \end{matrix}$$
> ##### where:
> - $K_{b}$ is the ==boiling point constant==
> - $m$ is the ==molality==
> - $i$ is the ==Van hoff't factor==
> ****
> $$\begin{matrix} \underset{\text{Solvent}}{\underline{\text{H}_{2}\text{O}}}+\underline{\text{salt}}\rightarrow \underline{\text{solution}} \\  \\ \text{BP}=100 \degree  \text{C} \end{matrix}$$
> - There are added particles with water
> - The solution encounters an increased difficulty in heat transfer
> - Hency why the boiling point is ***elevated***
> ****
> $$\begin{matrix} m=\dfrac{\text{mol solute}}{\text{kg solvent}} \end{matrix}$$
> ****
> $$\begin{matrix} \fbox{Van't Hoff Factor} \\  \\  \end{matrix}$$
> - The degree of dissociation of the solute in the solvent
> - For non electrolytes, $i=1$
> - The **Van't Hoff factor** describes the amount of ions that forms upon dissociation within the solvent
> > - For example
> > $$\begin{matrix} \text{NaCl}  \hspace{0.5cm} \rightarrow \hspace{0.5cm} \underline{\text{Na}^{+}} \space \underline{\text{Cl}^{-}} \\  \\ i=2 \\  \\  \\ \text{MgCl}_{2}  \hspace{0.5cm} \rightarrow \hspace{0.5cm} \underline{\text{Mg}}^{2+} \space  \underline{\text{Cl}^{-}} \\  \\ i=3 \end{matrix}$$

```
```col-md
flexGrow=2
===
2) ##### Freezing Point Depression (FPD)
> $$\begin{matrix} \Delta T_{f}=K_{f}mi \end{matrix}$$
> ##### where:
> - $K_{f}$ is the ==freezing point constant==
> - $m$ is the ==molality==
> - $i$ is the ==Van hoff't factor==
> ****
> - The solution is easier to ***freeze*** or ***crystallize*** 🥶 is easier when there are already solid particles dissolved within it
> - As the molality increases 📈, the freezing point temperature decreases 📉

3) ##### Vapor Pressure Lowering
> $$\begin{matrix} P_{\text{solution}}=x_{\text{solvent}}P_{\text{solvent}}^{\star}  \end{matrix}$$
> ##### where:
> - $P_\text{solution}$ is the ==vapor pressure of the solution==
> - $P_{\text{solvent}}^{\star}$ is the ==vapor pressure of the solvent==
> - $x_{\text{solvent}}$ is the ==concentration of the solute==
> ****
> The more solute 🧂 is added 📈, the less the vapor pressure of the solution 🎈⬇️
> ****
> $$\begin{matrix} x_{\text{solvent}}=\dfrac{n_{\text{solvent}}}{n_{\text{solute}}+n_{\text{solvent}}} \end{matrix}$$

4) ##### Osmotic Pressure
> ![Pasted image 20240827090141.png](/img/user/13th%20Term/Physical%20Chemistry/Class%20Notes/Attachments/Pasted%20image%2020240827090141.png)
> - Imagine a semipermeable membrane where solvent can pass through but solute cannot
> - The hydrostatic pressure pushes the solvent through the semipermeable membrane
> - The tendency of particles is to move from a ==higher concentration region== to a ==lower concentration region==
> - But the osmotic pressure on the other side prevents this
> ****
> $$\begin{matrix} \Pi=MRT \hspace{2cm}   \Pi=MRTi \end{matrix}$$
> ##### where:
> - $\Pi$ is the ==osmotic pressure==
> - $M$ is the ==molarity of the solution==
> - $R$ is the ==gas constant== at *$0.08206 \frac{\text{L}\cdot \text{atm}}{\text{mol}\cdot \text{K}}$*
> - $T$ is the ==temperature== in *$\text{K}$*
> - The Van't Hoff factor may be added if the solution has electrolytes/ions

- ##### Ebullioscopic constants
> |                   Solvent                    | Boiling point ($\degree  \text{C}$) | $K_{b} \space  \begin{pmatrix} \frac{\degree \text{C}}{\text{m}} \end{pmatrix}$ | $\text{FP }(\degree  \text{C})$ | $K_{f} \space  \begin{pmatrix} \frac{\degree  \text{C}}{\text{m}} \end{pmatrix}$ |
> | :------------------------------------------: | :---------------------------------: | :-----------------------------------------------------------------------------: | :-----------------------------: | :------------------------------------------------------------------------------: |
> |        Water, $\text{H}_{2}\text{O}$         |                 100                 |                                      ==0.51==                                       |                0                |                                       ==1.86==                                     |
> |     Benzene, $\text{C}_{6}\text{H}_{6}$      |                80.1                 |                                      2.53                                       |               5.5               |                                       5.12                                       |
> | Ethanol, $\text{C}_{2}\text{H}_{5}\text{OH}$ |                78.4                 |                                       1.2                                       |             -114.6              |                                       0.99                                       |
> |    Carbon Tetrachloride, $\text{CCl}_{4}$    |                76.8                 |                                      5.02                                       |              -22.3              |                                       29.8                                       |
> |         Chlorofrm, $\text{CHCl}_{3}$         |                61.2                 |                                       3.6                                       |              -63.5              |                                       0.68                                       |
> 
> $$\begin{matrix} k_{b}=\dfrac{RT_{b}^{2} \overline{M}_{B}}{\Delta H_{v,A}} \end{matrix}$$
- ##### Degree of dissociation
> $$\begin{matrix} \gamma=\dfrac{i-1}{n-1} \end{matrix}$$
- ##### Trouton-Hildebrand-Everet rule
> $$\begin{matrix} R \begin{pmatrix}4.5 + \text{ln }T_{b} \end{pmatrix}= \Delta S_{v} \end{matrix}$$
- ##### Van't Hoff Equation
> $$\begin{matrix} \fbox{Van't Hoff Equation} \\  \text{ln}\begin{pmatrix}\dfrac{K_{2}}{K_{1}}\end{pmatrix}=-\dfrac{\Delta H \degree }{R}\begin{pmatrix}\dfrac{1}{T_{2}}-\dfrac{1}{T_{1}}\end{pmatrix} \end{matrix}$$

```
````
****
## Other Topics
````col
```col-md
- ##### Electrochemistry
> $$\begin{matrix} \Delta G = -n_{e}FE_{\text{cell}}^{0}=-nRT \text{ ln }K \\  \\ Q=It=n_{e}F  \end{matrix}$$
- ##### Nernst Equation
> $$\begin{matrix} E & = & E \degree  -\dfrac{RT}{n_{e}F} \text{ ln }K \end{matrix}$$
> ##### where:
> - $E$ is the ==electrochemical potential==
> - $E \degree$ is the ==standard cell potential==
> - $R$ is the ==gas constant== *$8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}}$*
> - $T$ is the ==temperature== in *$\text{K}$*
> - $n$ is the ==number of electrons transferred in the reaction===
> - $F$ is the ==Faraday constant== in *$\text{96485}\frac{\text{C}}{\text{mol}}$*
> - $Q$ is the ==reaction quotient==
- ##### Debye-Huckel Equation
> $$\begin{matrix} i=\dfrac{\Delta T_{f}}{\begin{pmatrix}\Delta T_{f} \end{pmatrix}_{0}}=\dfrac{\Delta T}{\begin{pmatrix}\Delta T_{b} \end{pmatrix}_{0}}=\dfrac{\Delta P}{\begin{pmatrix} \Delta P \end{pmatrix}_{0}}=\dfrac{\Pi}{\begin{pmatrix} \Pi \end{pmatrix}_{0}} \end{matrix}$$

```
```col-md
flexGrow=1.5
===
- ##### Le Chatelier's Principle
> ![Pasted image 20240927111510.png](/img/user/14th%20Term/Correlation%20Exam%20(CH195)/Attachments/Pasted%20image%2020240927111510.png)

- ##### Equilibrium Constant
> $$\begin{matrix} K_{P}=K_{C} \begin{pmatrix}RT \end{pmatrix}^{\Delta n} \\  \\ \Delta n= \begin{pmatrix}\text{moles of product}-\text{moles of reactants} \end{pmatrix} \end{matrix}$$

```
````
****
## Solving Problems
### Gas Laws / Equations of Change
````col
```col-md
> [!question] 
> ###### Keeping the pressure constant, to double the volume of a given mass of an ideal gas at 27°C, the temperature should be raised to \_\_\_\_\_\_\_ °C


```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} \fbox{Charles' Law} \\  \\  \dfrac{V_{1}}{T_{1}}=\dfrac{V_{2}}{T_{2}} \\  \\  \dfrac{V_{1}}{\text{27+273.15 K}}=\dfrac{2V_{1}}{T_{2}} \\  \\ T_{2}= (2)(\text{298.15 K})=\text{596.3 K} \\  \\ T=\text{596.3}-\begin{vmatrix} \text{273.15 K} \end{vmatrix}=\mathbf{\underline{323.15 \degree  C}}  \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> ###### Use the van der Waals equation of state to calculate the pressure exerted by exactly 1 mol of gaseous ammonia, NH<sub>3</sub>, held at a temperature of 1000 K in a vessel of volume 2.50 dm<sup>3</sup> 
> - The values of the van der Waals parameters for ammonia are:
> 	- <u>a = 422.5 kPa dm<sup>6</sup> mol<sup>-2</sup></u>
> 	- <u>b = 3.71 x 10<sup>-2</sup> dm<sup>3</sup> mol<sup>-1</sup></u>

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} \fbox{Van der Waals}  \\  P=\dfrac{RT}{\overline{V}-b}-\dfrac{a}{\overline{V}^{2}} \\  \\ P=\dfrac{\begin{pmatrix} 8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}}  \end{pmatrix}\begin{pmatrix} \text{1000 K} \end{pmatrix}}{\text{2.50 dm}^{3}-3.71 \cdot 10^{-2} \frac{\text{dm}^{3}}{\text{mol}}} -\dfrac{422.5 \frac{\text{kPa}\cdot \text{dm}^{6}}{\text{mol}^{2}}}{\begin{pmatrix}\text{2.50 dm}^{3} \end{pmatrix}^{2}} \\  \\  P =\underline{\mathbf{3308.1 \space kPa}}=\underline{\mathbf{3.31 \space MPa}}  \end{matrix}$$
```
````
****
### Molecular Speeds / Collisions
````col
```col-md
> [!question] 
> ###### Calculate the root-mean-squared speed of methane, CH4, molecules in a sample of at 25 °C


> [!note] ノート
> $$\begin{matrix} \text{1 J}=1\dfrac{\text{kg}\cdot \text{m}^{2}}{\text{s}^{2}} \end{matrix}$$
> - To obtain the root-mean-square speed in meters per second (m/s), the molar mass must also be in kilograms per mole (kg/mol)

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} M_{\text{CH}_{4}}=(1)(12.01)+(4)(1)=16.01 \\  \\ v_{\text{rms}}=\sqrt{\dfrac{3RT}{M}} \\  \\ v_{\text{rms}}=\sqrt{\dfrac{\begin{pmatrix} 3 \end{pmatrix}\begin{pmatrix} 8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix}\begin{pmatrix} \text{25+273.15 K} \end{pmatrix}}{16.01 \frac{\text{g}}{\text{mol}}\cdot  \begin{vmatrix} \frac{\text{1 kg}}{\text{1000 g}} \end{vmatrix}}} \\  \\ v_{\text{rms}}=\underline{\mathbf{682 \frac{m}{s}}}  \end{matrix}$$



```
````
****
````col
```col-md
> [!question] 
> ###### Calculate the mean free path of carbon dioxide molecules, CO<sub>2</sub>, in a sample of gas at standard ambient temperature and pressure
> - The collision cross-section of a carbon dioxide molecule is 0.52 nm<sup>2</sup>

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} l=\dfrac{kT}{\sqrt{2}\sigma P} \\  \\ \underline{\text{Boltzmann's constant}} \\ k=1.380469 \cdot 10^{-23} \frac{\text{J}}{\text{K}} \\  \\ l=\dfrac{\begin{pmatrix} 1.380469 \cdot 10^{-23} \frac{\text{J}}{\text{K}} \end{pmatrix}\begin{pmatrix} \text{25 + 273.15K} \end{pmatrix}}{\sqrt{2}\begin{pmatrix} 0.52 \text{ nm}^{2} \cdot  \begin{vmatrix} \frac{\text{1 m}}{10^{9} \text{ nm}} \end{vmatrix}^{2} \end{pmatrix}\begin{pmatrix} \text{101325 Pa} \end{pmatrix}} \\  \\ l=\text{5.52}\cdot 10^{-8} \text{m} \cdot  \begin{vmatrix} \frac{10^{9} \text{ nm}}{\text{1 m}} \end{vmatrix}=\underline{\mathbf{55.23 \space  nm}} \end{matrix}$$
```
````
****
### System Properties 
````col
```col-md
> [!question] 
> ###### Calculate the work done on the system when 1.00 mol of gas held behind a piston expands irreversibly from a volume of 1.00 dm<sup>3</sup> to a volume of 10.0 dm<sup>3</sup> against an external pressure of 1.00 bar

> [!note] ノート
> $$\begin{matrix} \text{1 kPa}=1 \dfrac{\text{J}}{\text{L}\cdot \text{atm}} \end{matrix}$$
> 
> $$\begin{matrix} \text{101.325 J} \text{ per }\text{L}\cdot \text{atm} \end{matrix}$$


```
```col-md
flexGrow=2
===
##### 答える：

$$\begin{matrix} W=-P_{\text{ext}} \Delta V \\  \\ W=\underline{-\begin{bmatrix}\text{1.00 bar} \cdot  \begin{vmatrix} \dfrac{\text{0.9869 atm}}{\text{1 bar}} \end{vmatrix} \end{bmatrix}\begin{bmatrix}\begin{pmatrix} 10.0 \text{ dm}^{3}-\text{1.00 dm}^{3} \end{pmatrix} \cdot  \begin{vmatrix} \dfrac{\text{1 L}}{\text{1 dm}^{3}} \end{vmatrix} \end{bmatrix}} \\  \\ W=\underline{-8.8821 \text{ L}\cdot \text{atm}}\cdot  \begin{vmatrix} \dfrac{\text{101.325 J}}{\text{1 L}\cdot \text{atm}} \end{vmatrix}  \\  \\ W=\mathbf{\underline{-900 \space  J}} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> - If enthalpy is defined as present in a constant pressure process change of state, using the relationship of ΔH=ΔU+ΔPV, where H is enthalpy, U is the energy change in the system and PV represents pressure and volume states
> ****
> ###### Determine the ΔU and ΔH of 1 kg of water when vaporized at constant temperature of 100 ̊ C and constant pressure of 101.325kPa
> - The specific volumes of liquid and vapor water are 0.001041 and 1.67 m3/kg 
> - An amount of 2257 kJ of heat is added to the water

```
```col-md
flexGrow=2
===
##### 答える：

- $\text{2257 kJ}$ of heat was ***added*** to the system for ==1 kg of water==
> - This would be the change in enthalpy
- Solve for the change in internal energy
> $$\begin{matrix} \Delta H = \Delta U + P \Delta V \\  \\  \Delta U = \Delta H - P  \Delta V \\  \\ \Delta U =\begin{pmatrix} 2257 \frac{\text{kJ}}{\text{kg}} \end{pmatrix}- \begin{pmatrix}\text{101.325 kPa} \end{pmatrix}\begin{pmatrix}1.67 \frac{\text{m}^{3}}{\text{kg}}-0.001041\frac{\text{m}^{3}}{\text{kg}} \end{pmatrix} \\  \\  \Delta U =\underline{\mathbf{2087 \frac{kJ}{kg}}} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> ###### <center> Calculate the difference between the molar internal energy and the molar enthalpy for a perfect gas at $\text{298.15 K}$ </center>

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} \begin{matrix} \begin{bmatrix}\hline  \begin{matrix} \Delta H= \Delta U + \underline{P \Delta V}  \\  \\ PV=nRT \\  \\ \Delta H = \Delta U+nRT \\  \\ \Delta H   =   \Delta U + (\text{1 mol})RT \end{matrix}  \\ \hline \end{bmatrix} \end{matrix}  \hspace{1cm}   \begin{matrix} \Delta H - \Delta U & = &  RT \\  \\ & = &\begin{pmatrix} 8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix}\begin{pmatrix} \text{298.15 K} \end{pmatrix} \\  \\  & = &  \mathbf{\underline{2479 \space  \frac{J}{mol}}}=\mathbf{\underline{2.4790 \space \frac{kJ}{mol}}} \end{matrix} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> ###### Calculate the change in molar entropy of a perfect gas when it is compressed isothermally from a pressure of 1 bar to 10 bar

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} \Delta S = \cancelto{0 \text{ (isothermal)}}{\int\limits^{T_{2}}_{T_{1}}\dfrac{C_{P}}{T} \space  dT} - R \text{ ln}\begin{pmatrix}\dfrac{P_{2}}{P_{1}}\end{pmatrix} \\  \\ \Delta S=-\begin{pmatrix} 8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix} \text{ ln}\begin{bmatrix}\begin{pmatrix} \dfrac{\text{10 bar}}{\text{1 bar}} \end{pmatrix} \cdot  \begin{vmatrix} \dfrac{0.9869 \text{ atm}}{\text{1 bar}} \end{vmatrix} \end{bmatrix} \\  \\ \Delta S=\mathbf{\underline{-19.03 \frac{J}{mol \cdot K}}} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> ###### Calculate the change in entropy when exactly 1 mol of solid iodine, I<sub>2</sub>, at a temperature of 360 K is heated at constant pressure to produce liquid iodine at a temperature of 410 K
> - The constant pressure molar heat capacity of solid iodine is <u>54.44 J K<sup>–1</sup> mol<sup>–1</sup></u> and of liquid iodine is <u>80.67 J K<sup>–1</sup> mol<sup>–1</sup></u>
> - The melting temperature of iodine is 387 K, and the molar enthalpy of fusion of iodine is <u>7.87 kJ mol<sup>–1</sup></u>

```
```col-md
flexGrow=2
===
##### 答える：
1) Heating the iodine to the melting temperature
> $$\begin{matrix}  \Delta S_{1} & = & \int\limits^{T_{2}}_{T_{1}}\dfrac{C_{P}}{T}\space  dT \\  \\  & = & \int\limits^{\text{387 K}}_{\text{360K}} \dfrac{54.44 \frac{\text{J}}{\text{mol}\cdot \text{K}}}{T}\space  dT \\  \\  & = & 3.9371 \frac{\text{J}}{\text{mol} \cdot \text{K}} \end{matrix}$$
2) Melting the iodine from solid to liquid
> $$\begin{matrix}  \Delta S_{2} & = & \int\limits^{T_{2}}_{T_{1}}\dfrac{C_{P}}{T}\space  dT \\  \\   & = & \dfrac{\Delta H_{\text{fus}}}{T}  \\  \\  & = & \dfrac{7.87 \frac{\text{kJ}}{\text{mol}}\cdot  \begin{vmatrix} \frac{\text{1000 J}}{\text{1 kJ}} \end{vmatrix}}{\text{387 K}} \\  \\  & = & 20.3359 \frac{\text{J}}{\text{mol}\cdot \text{K}}   \end{matrix}$$
3) Heating the liquid iodine from 387K to 410K
> $$\begin{matrix}  \Delta S_{3} & = & \int\limits^{T_{2}}_{T_{1}}\dfrac{C_{P}}{T}\space  dT  \\  \\  & = & \int\limits^{\text{410K}}_{\text{387K}}\dfrac{80.67 \frac{\text{J}}{\text{mol}\cdot \text{K}}}{T}\space  dT \\  \\  & = & 4.6573 \frac{\text{J}}{\text{mol}\cdot \text{K}}  \end{matrix}$$
4) Combine all entropy from the phase changes
> $$\begin{matrix} \Delta S=\Delta S_{1}+\Delta S_{2}+ \Delta S_{3} \\  \\ \Delta S =  3.9371 \frac{\text{J}}{\text{mol} \cdot \text{K}}  + 20.3359 \frac{\text{J}}{\text{mol}\cdot \text{K}} + 4.6573 \frac{\text{J}}{\text{mol}\cdot \text{K}} \\  \\ \Delta S = \underline{\mathbf{28.9303 \frac{J}{mol \cdot K}}}  \end{matrix}$$


```
````
````col
```col-md
> [!question] 
> - The partial pressure of a component in a gas-phase reaction is 0.452 atm
> ****
> ###### <center> What is the activity of the component? </center>

```
```col-md
flexGrow=2
===
##### 答える：

$$\begin{matrix} \alpha = \dfrac{P_{A}}{P_{T}}=\dfrac{\text{0.452 atm}}{\text{1 atm}}=\underline{\mathbf{0.452}}  \end{matrix}$$

```
````
****
### Clausius-Clapeyron Equation
````col
```col-md
> [!question] 
> - The standard enthalpy of vaporization of water, H<sub>2</sub>O, Δ<sub>vap</sub>H° = 40.7 kJ mol<sup>–1</sup> at 373 K
> - Assuming this value to remain constant at temperatures close to 373 K
> ****
> ###### <center> Use the Clausius–Clapeyron equation to estimate the vapour pressure of liquid water at 80 °C </center>

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} \dfrac{dP}{dT}=\dfrac{\Delta H}{T \overline{ V}} \\  \\ P \overline{V}=\cancelto{1}{n}RT  \hspace{0.5cm} \rightarrow \hspace{0.5cm} \overline{V}=\dfrac{RT}{P} \\  \\ \dfrac{dP}{dT}=\dfrac{\Delta H_{\text{vap}}}{T \cdot \dfrac{RT}{P}} \\  \\ \dfrac{dP}{dT}=\dfrac{\Delta H_{\text{vap}}P}{RT^{2}} \\  \\ \int\limits^{}_{} \dfrac{dP}{P}=\dfrac{\Delta H_{\text{vap}}}{R} \int\limits^{}_{}\dfrac{dT}{T^{2}} \\  \\ \text{ln}\begin{pmatrix}\dfrac{P_{2}}{P_{1}}\end{pmatrix}=\dfrac{\Delta H_{\text{vap}}}{R}\begin{pmatrix}-\begin{bmatrix} \dfrac{1}{T_{2}}-\dfrac{1}{T_{1}} \end{bmatrix} \end{pmatrix} \\  \\ P_{2}=P_{1}\text{ exp}\begin{bmatrix} \dfrac{\Delta H _{\text{vap}}}{R}\begin{pmatrix}-\begin{bmatrix} \dfrac{1}{T_{2}}-\dfrac{1}{T_{1}} \end{bmatrix} \end{pmatrix} \end{bmatrix} \\  \\ P_{2}=\text{(101325 kPa)}\text{ exp}\begin{bmatrix} \dfrac{40.7 \frac{\text{kJ}}{\text{mol}}\cdot  \begin{vmatrix} \frac{\text{1000 J}}{\text{1 kJ}} \end{vmatrix}}{8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}}}\begin{pmatrix}-\begin{bmatrix} \dfrac{1}{\text{80+273.15K}}-\dfrac{1}{\text{373K}} \end{bmatrix} \end{pmatrix} \end{bmatrix} \\  \\ P_{2}=\mathbf{\underline{48455 \space  Pa}}=\underline{\mathbf{48.46 \space kPa}}  \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> - The triple point of acetylene, C2H2, lies at a temperature of 192.4 K and pressure of 128 kPa
> - Assuming that the enthalpy of vaporization of acetylene, Δ<sub>vap</sub>H = 31.3 kJ mol<sup>–1</sup>, is invariant with temperature
> ****
> ###### <center> Calculate the normal boiling temperature </center>

```
```col-md
flexGrow=2
===
##### 答える：

$$\begin{matrix}  \dfrac{dP}{dT}=\dfrac{\Delta H}{T \overline{ V}} \\  \\ P \overline{V}=\cancelto{1}{n}RT  \hspace{0.5cm} \rightarrow \hspace{0.5cm} \overline{V}=\dfrac{RT}{P} \\  \\ \dfrac{dP}{dT}=\dfrac{\Delta H_{\text{vap}}}{T \cdot \dfrac{RT}{P}} \\  \\ \dfrac{dP}{dT}=\dfrac{\Delta H_{\text{vap}}P}{RT^{2}} \\  \\ \int\limits^{}_{} \dfrac{dP}{P}=\dfrac{\Delta H_{\text{vap}}}{R} \int\limits^{}_{}\dfrac{dT}{T^{2}} \\  \\ \text{ln}\begin{pmatrix} \dfrac{P_{2}}{P_{1}} \end{pmatrix}=\dfrac{\Delta H_{\text{vap}}}{R}\begin{pmatrix}-\begin{bmatrix} \dfrac{1}{T_{2}}-\dfrac{1}{T_{1}} \end{bmatrix} \end{pmatrix} \\  \\ T_{2}=\dfrac{1}{\dfrac{1}{T_{1}}-\dfrac{R\text{ ln}\begin{pmatrix} \dfrac{P_{2}}{P_{1}} \end{pmatrix}}{\Delta H_{\text{vap}}}} \\  \\ T_{2} =\dfrac{1}{\dfrac{1}{\text{192.4 K}}-\dfrac{\begin{pmatrix} 8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix}\text{ ln}\begin{pmatrix}\dfrac{\text{101.325 kPa}}{\text{128 kPa}} \end{pmatrix}}{31.3 \frac{\text{kJ}}{\text{mol}}\cdot  \begin{vmatrix} \frac{\text{1000 J}}{\text{1 kJ}} \end{vmatrix}}} \\  \\ T_{2}=\underline{\mathbf{190.13 \space  K}} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> - The vapor pressure of liquid carbon disulfide, $\text{CS}_{2}$ is $\text{23.5 kPa}$ at $\text{280 K}$ and $\text{51.3 kPa}$ at $\text{300 K}$
> ****
> ###### <center> Calculate the enthalpy of vaporization of carbon disulfide at 290 K </center>
> - **A.** $17.9 \frac{\text{kJ}}{\text{mol}}$
> - **B.** $27.3  \frac{\text{kJ}}{\text{mol}}$
> - **C.** $94.1  \frac{\text{kJ}}{\text{mol}}$
> - **D.** $97.2 \frac{\text{kJ}}{\text{mol}}$

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix}  \dfrac{dP}{dT}=\dfrac{\Delta H}{T \overline{ V}} \\  \\ P \overline{V}=\cancelto{1}{n}RT  \hspace{0.5cm} \rightarrow \hspace{0.5cm} \overline{V}=\dfrac{RT}{P} \\  \\ \dfrac{dP}{dT}=\dfrac{\Delta H_{\text{vap}}}{T \cdot \dfrac{RT}{P}} \\  \\ \dfrac{dP}{dT}=\dfrac{\Delta H_{\text{vap}}P}{RT^{2}} \\  \\ \int\limits^{}_{} \dfrac{dP}{P}=\dfrac{\Delta H_{\text{vap}}}{R} \int\limits^{}_{}\dfrac{dT}{T^{2}} \\  \\ \text{ln}\begin{pmatrix} \dfrac{P_{2}}{P_{1}} \end{pmatrix}=\dfrac{\Delta H_{\text{vap}}}{R}\begin{pmatrix}-\begin{bmatrix} \dfrac{1}{T_{2}}-\dfrac{1}{T_{1}} \end{bmatrix} \end{pmatrix} \\  \\  \begin{matrix} \Delta H_{\text{vap}}  & = & \dfrac{R \space  \text{ln}\begin{pmatrix} \dfrac{P_{2}}{P_{1}} \end{pmatrix}}{\begin{pmatrix}-\begin{bmatrix} \dfrac{1}{T_{2}}-\dfrac{1}{T_{1}} \end{bmatrix} \end{pmatrix}} \\  \\   & = & \dfrac{\begin{pmatrix} 8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix}\text{ ln}\begin{pmatrix}\dfrac{\text{51.3 kPa}}{\text{23.5 kPa}}\end{pmatrix}}{\begin{pmatrix}-\begin{bmatrix} \dfrac{1}{\text{300 K}}-\dfrac{1}{\text{280 K}} \end{bmatrix} \end{pmatrix}}  \\  \\  & = & \mathbf{\underline{27260 \frac{J}{mol}}}=\mathbf{\underline{27.3 \frac{kJ}{mol}}} \end{matrix}  \end{matrix}$$
```
````
****
### Phase Equilibria
````col
```col-md
> [!question] 
> - The partial molar volumes of water, H<sub>2</sub>O, and methanol, CH<sub>3</sub>OH, are 17.8 cm<sup>3</sup> mol<sup>-1</sup> and 38.4 cm<sup>3</sup> mol<sup>-1</sup> respectively at 25.0 °C for dilute mixtures of methanol in water
> ****
> ###### Calculate the total volume when 15 cm<sup>3</sup> of methanol is added to 250 cm<sup>3</sup> of water at this  temperature
> - The density of methanol is <u>0.791 g cm<sup>-3</sup></u>

```
```col-md
flexGrow=2
===
##### 答える：
1) Calculate the total moles of methanol in solution
> $$\begin{matrix} M_{\text{CH}_{3}\text{OH}}=1(12.01)+4(1)+1(16)=32.01  \frac{\text{g}}{\text{mol}} \\  \\ n_{\text{CH}_{3}\text{OH}}=\begin{pmatrix} \dfrac{0.791 \frac{\text{g}}{\text{cm}^{3}}}{32.01 \frac{\text{g}}{\text{mol}}}  \end{pmatrix}\begin{pmatrix} \text{15 cm}^{3} \end{pmatrix} \\  \\  n_{\text{CH}_{3}\text{OH}}=\text{0.3707 mol}  \end{matrix}$$
2) Calculate the total moles of water
> $$\begin{matrix} M_{\text{H}_{2}\text{O}}=2(1)+1(16)=18 \frac{\text{g}}{\text{mol}} \\  \\ n_{\text{H}_{2}\text{O}}=\begin{pmatrix}\dfrac{1 \frac{\text{g}}{\text{cm}^{3}}}{18 \frac{\text{g}}{\text{mol}}}\end{pmatrix}\begin{pmatrix} \text{250 cm}^{3} \end{pmatrix} \\  \\ n_{\text{H}_{2}\text{O}}=\text{13.8889 mol} \end{matrix}$$

3) Calculate the total volume by calculate equivalent partial volume of the moles in the solution
> $$\begin{matrix} V =\begin{pmatrix}\text{13.8889 mol} \end{pmatrix}\begin{pmatrix} 17.8 \frac{\text{cm}^{3}}{\text{mol}} \end{pmatrix}+ \begin{pmatrix}\text{0.3707 mol} \end{pmatrix}\begin{pmatrix} 38.4 \frac{\text{cm}^{3}}{\text{mol}} \end{pmatrix} \\  \\ V=\underline{\mathbf{261.46 \space cm^{3}}} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> - A solution is prepared by dissolving 5.32 g of benzene, C<sub>6</sub>H<sub>6</sub>, in 93.2 g of toluene, C<sub>6</sub>H<sub>5</sub>CH<sub>3</sub>, at 25 °C
> - The vapour pressures of pure benzene and pure toluene are 12.7 kPa and 3.8 kPa at this temperature
> ****
> ###### <center> Use Raoult's law to determine the partial vapour pressure of each of the two components for the mixture </center>

```
```col-md
flexGrow=2
===
##### 答える：

$$\begin{matrix} M_{\text{C}_{6}\text{H}_{6}}=6(12.01)+6(1)=78.06 \frac{\text{g}}{\text{mol}} \\  \\  n_{\text{C}_{6}\text{H}_{6}}=\dfrac{5.32 \text{ g}}{78.06 \frac{\text{g}}{\text{mol}}}=0.06815 \text{ mol} \\  \\ M_{\text{C}_{6}H_{5}\text{CH}_{3}}=7(12.01)+8(1)=92.07 \frac{\text{g}}{\text{mol}} \\  \\ n_{\text{C}_{6}\text{H}_{5}\text{CH}_{3}}=\dfrac{93.2 \text{ g}}{92.07  \frac{\text{g}}{\text{mol}}}=1.0123 \text{ mol} \\  \\  \\ x_{\text{C}_{6}\text{H}_{6}}=\dfrac{0.06815 \text{ mol}}{0.06815 \text{ mol}+1.0123 \text{ mol}}=0.06308 \\  \\  x_{\text{C}_{6}\text{H}_{5}\text{CH}_{3}}=\dfrac{1.0123 \text{ mol}}{0.06815 \text{ mol}+1.0123 \text{ mol}}=0.9369 \\  \\ P_{T}=P_{\text{C}_{6}\text{H}_{6}}+P_{\text{C}_{6}\text{H}_{5}\text{CH}_{3}} \\  \\ P_{\text{C}_{6}\text{H}_{6}}=\begin{pmatrix} 0.06308\end{pmatrix}\begin{pmatrix} \text{12.7 kPa} \end{pmatrix}=\underline{\mathbf{0.0811 \space  kPa}} \\  \\ P_{\text{C}_{6}\text{H}_{5}\text{CH}_{3}} = \begin{pmatrix} 0.9369 \end{pmatrix}\begin{pmatrix}\text{3.8 kPa} \end{pmatrix}=\underline{\mathbf{3.5602 \space  kPa}} \\  \\ P_{T}=0.0811 \text{ kPa}+\text{3.5602}=\underline{\mathbf{3.6413 \space kPa}} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> ###### <center> Calculate the minimum partial pressure of nitrogen that is necessary to achieve an aqueous ideal–dilute solution of concentration 1.00 mmol dm<sup>-3</sup>
> - The Henry's law constant for nitrogen in water is 6.48 × 10<sup>-3</sup> mol m<sup>-3</sup> kPa<sup>-1</sup>

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} P_{\text{N}}=\dfrac{\begin{pmatrix}1.00 \frac{\text{mmol}}{\text{dm}^{3}} \cdot  \begin{vmatrix} \frac{\text{1 mol}}{\text{1000 mmol}} \end{vmatrix}\cdot  \begin{vmatrix} \frac{\text{10 dm}}{\text{m}} \end{vmatrix}^{3} \end{pmatrix}}{\begin{pmatrix}6.48 \cdot 10^{-3} \frac{\text{mol}}{\text{m}^{3} \cdot \text{kPa}} \end{pmatrix}} \\  \\ P_{\text{N}}=\mathbf{\underline{154.32 \space kPa}} \end{matrix}$$

```
````
****
### Colligative Properties
````col
```col-md
> [!question] 
> ###### <center> Calculate the osmotic pressure exerted by an aqueous solution of sucrose, C<sub>12</sub>H<sub>22</sub>O<sub>11</sub>, of mass concentration 6.51 g dm<sup>-3</sup> at 20 °C </center>
> - The osmotic virial coefficient for dilute aqueous solutions of sucrose at this temperature is 0.382 dm<sup>3</sup> mol<sup>-1</sup>

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} \Pi=MRT \\  \\ MM_{\text{sucr.}}=12(12.01)+22(1)+11(16)=342.12 \frac{\text{g}}{\text{mol}} \\  \\ M=\dfrac{\begin{pmatrix}6.51 \frac{\text{g}}{\text{dm}^{3}} \cdot  \begin{vmatrix} \frac{\text{1 dm}^{3}}{\text{1 L}} \end{vmatrix} \end{pmatrix}}{\begin{pmatrix} 342.12 \frac{\text{g}}{\text{mol}} \end{pmatrix}}=0.01903 \frac{\text{mol}}{\text{L}} \\  \\ \Pi=\begin{pmatrix} 0.01903 \frac{\text{mol}}{\text{L}} \end{pmatrix}\begin{pmatrix} 8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix}\begin{pmatrix}\text{20+273.15K} \end{pmatrix} \\  \\ \Pi=\mathbf{\underline{46.4 \space kPa}}  \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> If Raoult’s Law applies for dilute solutions and osmotic pressure at equilibrium is estimated using the relationship (RT/Va) x ln(Pa°/Pa) where R is 0.0881 atm/mol-K, T is in Kelvin, and Pa and Pa are the vapor pressures in dilute and concentrated solutions, given that the Va is 0.018 L for water
> ****
> ###### <center> Estimate the osmotic pressure difference across a semi-permeable membrane with brackish water on one side and mineral free water on the other at 25 deg C </center> 
> - If a yield of 75% is required, 
> ###### <center> what is the minimum pressure needed to balance the osmotic pressure difference that will develop? </center>

```
```col-md
flexGrow=2
===
##### 答える：
1) First, we need to calculate the osmostic pressure difference using the given relationship
> $$\begin{matrix} \Pi =\begin{pmatrix}\dfrac{RT}{V_{0}} \end{pmatrix}\text{ ln}\begin{pmatrix}\dfrac{P_{0}^{\star}}{P}\end{pmatrix} \end{matrix}$$
> ##### where:
> - $R=0.0881 \frac{\text{atm}}{\text{mol}\cdot \text{K}}$ 
> - $T=25 \degree  \text{C}+273.15=\text{298.15K}$
> - $V_{a}=\text{0.018 L}$ for water
> - $P_{a}^{\star}$ is the ==vapor pressure of pure water==
> - $P_{a}$ is the ==vapor pressure of brackish water==
> ****
> - We don't have the exact values for $P_{a}^{\star}$ and $P_{a}$, but we can make reasonable assumptions
> > - ==$P_{a}$ (pure water at $\text{25}\degree  \text{C}$):== $\text{3.17 kPa}=\text{0.0313 atm}$
> > - ==$P_{a}$ (brackish water will be lower):== $\text{3.00 kPa}=0.0296 \text{ atm}$
> ****
> $$\begin{matrix} \Pi=\dfrac{\begin{pmatrix}0.881 \frac{\text{atm}}{\text{mol}\cdot \text{K}} \end{pmatrix}\begin{pmatrix}\text{298.15 K} \end{pmatrix}}{\begin{pmatrix} \text{0.018 L} \end{pmatrix}}\text{ln}\begin{pmatrix}\dfrac{\text{0.0313 atm}}{\text{0.0296 atm}}\end{pmatrix} \\  \\ \Pi=\mathbf{\underline{7.37 \space  atm}}=\mathbf{\underline{746 \space  kPa}}=\mathbf{\underline{7.46 \space bar}} \end{matrix}$$
> - For a 75\% yield, that applied pressure needs to be 75\% of the osmotic pressure difference
> 
> $$\begin{matrix} 0.75 \Pi = \mathbf{\underline{560 \space kPa}}=\mathbf{\underline{5.60 \space bar}} \end{matrix}$$

```
````
****
### Gibbs Free Energy & Spontaneity
````col
```col-md
> [!question] 
> ###### <center> Calculate the standard reaction Gibbs energy Δ<sub>r</sub>G° at 298 K for the combustion of ethane <u>C<sub>2</sub>H<sub>6</sub>(g) + 3½ O<sub>2</sub>(g) ⇌ 2 CO<sub>2</sub>(g) + 3 H<sub>2</sub>O(l)</u> 
> - Given that the standard Gibbs energies of formation of the components at this temperature are:
> 	- ΔfG°(C<sub>2</sub>H<sub>6</sub>, g) = –32.82 kJ mol<sup>–1</sup>
> 	- Δ<sub>f</sub>G°(CO<sub>2</sub>,g) = – 394.36 kJ mol<sup>-1</sup>
> 	- Δ<sub>f</sub>G°(H<sub>2</sub>O,l) = –237.13 kJ mol<sup>–1</sup>

```
```col-md
flexGrow=2
===
##### 答える：

$$\begin{matrix} \Delta G = \Delta G \degree  + \text{RT ln}(Q) \\  \\  \begin{matrix} \text{C}_{2}\text{H}_{6}\text{ (g)} & + & \frac{7}{2} \text{O}_{2} \text{ (g)} & \rightleftharpoons & \text{2CO}_{2} \text{ (g)} & + & \text{ 3H}_{2}\text{O} \text{ (l)} \end{matrix} \end{matrix}$$
- The problem has not given $Q$, so we assume the change in Gibbs free energy calculated only accounts for the formation
$$\begin{matrix}\fbox{Basis:} \space  \underline{\text{1 mole}} \\  \\  \Delta G = \Delta G \degree  \\  \\ \Delta G = \begin{pmatrix}2 \cdot -394.36 \frac{\text{kJ}}{\text{mol}} + 3 \cdot -237.13 \frac{\text{kJ}}{\text{mol}} \end{pmatrix}-\begin{pmatrix}1 \cdot -32.82 \frac{\text{kJ}}{\text{mol}} +0 \cdot 0 \frac{\text{kJ}}{\text{mol}} \end{pmatrix} \\  \\ \Delta G=\mathbf{\underline{-1467.29 \frac{kJ}{mol}}}  \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> ###### <center> Calculate the change in the chemical potential of a perfect gas when it expands isothermally at a temperature of 20.0 °C so that its volume doubles </center>

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix}\Delta \mu=RT \text{ ln}\begin{pmatrix}\dfrac{P_{2}}{P_{1}}\end{pmatrix} \\  \\ \Delta \mu=\begin{pmatrix} 8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix}\begin{pmatrix}\text{20+273.15K} \end{pmatrix}\text{ ln}\begin{pmatrix}\dfrac{1}{2}\end{pmatrix} \\  \\ \Delta \mu=\underline{\mathbf{-1689 \frac{J}{mol}}}=\underline{\mathbf{-1.689 \frac{kJ}{mol}}}  \end{matrix}$$

- Volume doubling means less pressure on the system because the fluid is more distributed

```
````
****
````col
```col-md
> [!question] 
> ###### <center> Calculate the entropy change when 2.0 mol of a perfect gas A and 3.0 mol of a perfect gas B mix spontaneously </center>

```
```col-md
flexGrow=2
===
##### 答える：

$$\begin{matrix} \Delta S=-nR \begin{bmatrix} x_{A} \text{ ln}(x_{A})+x_{B} \text{ ln}x_{B} \end{bmatrix} \\  \\ x_{A}=\dfrac{n_{A}}{n}=\dfrac{\text{2 mol}}{\text{2 mol}+\text{3 mol}}=0.4 \\  \\ x_{B}=\dfrac{n_{B}}{n}=\dfrac{\text{3 mol}}{\text{2 mol}+\text{3 mol}}=0.6 \\  \\ \Delta S =-\begin{pmatrix} \text{5 mol} \end{pmatrix}\begin{pmatrix}8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix}\begin{bmatrix}0.4 \text{ ln}(0.4)+0.6 \text{ ln}(0.6) \end{bmatrix} \\  \\ \Delta S=\underline{\mathbf{27.98 \frac{J}{K}}} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> Mercury has a molar mass of <u>200.6 g-mol<sup> –1 </sup></u> and a density of <u>13.6 g-cm<sup> –3 </sup></u> when liquid
> ****
> ###### <center>Calculate the change in the molar Gibbs energy of liquid mercury when the pressure increases by 10.0 bar </center>

```
```col-md
flexGrow=2
===
##### 答える：

- Calculate the change in the Gibbs free energy by getting the molar volume of mercury 
> $$\begin{matrix} \Delta G = V \Delta P \\  \\ \Delta G = \begin{pmatrix} \dfrac{200.6 \frac{\text{g}}{\text{mol}}}{13.6 \frac{\text{g}}{\text{cm}^{3}}\cdot  \begin{vmatrix} \dfrac{\text{100 cm}}{\text{1 m}} \end{vmatrix}^{3}} \end{pmatrix}\begin{pmatrix} \text{10 bar}\cdot  \begin{vmatrix} \dfrac{101325\text{ Pa}}{\text{1 bar}} \end{vmatrix}\cdot  \begin{vmatrix} \dfrac{1 \dfrac{\text{N}}{\text{m}^{2}}}{\text{1 Pa}} \end{vmatrix}\cdot  \begin{vmatrix} \dfrac{1\dfrac{\text{kg}\cdot \text{m}}{\text{s}^{2}}}{\text{1 N}} \end{vmatrix} \end{pmatrix} \\  \\ \Delta G =14.95 \dfrac{\text{kg}\cdot \text{m}^{2}}{\text{mol}\cdot \text{s}^{2}} \cdot  \begin{vmatrix} \dfrac{\text{1 J}}{\dfrac{\text{kg}\cdot \text{m}^{2}}{\text{s}^{2}} } \end{vmatrix}  \\  \\ \Delta G =\underline{\mathbf{14.95 \frac{J}{mol}}} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> - The standard molar entropy of but-1-ene, C<sub>4</sub>H<sub>8</sub>, is 307 J K<sup>-1</sup> mol<sup>-1</sup>
> ****
> ###### <center> What is the change in the molar Gibbs energy of but-1-ene heated from 293 K to 303 K?

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} \Delta G = \Delta H - S \Delta T \end{matrix}$$
- The question ==1) mentions no combustion== and ==2) only states a relatively small temperature difference (303 - 293)==, therefore we assume there enthalpy change is negligible
> $$\begin{matrix} \Delta G =\cancelto{0}{\Delta H} - S \Delta T \\  \\ \Delta G = -\begin{pmatrix} 307 \frac{\text{J}}{\text{K}\cdot \text{mol}} \end{pmatrix}\begin{pmatrix}\text{303 K}-\text{293 K} \end{pmatrix} \\  \\ \Delta G =\mathbf{\underline{-3070 \frac{J}{mol}}}=\mathbf{\underline{-3.07 \frac{kJ}{mol}}} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> ###### <center> Calculate the change in the molar Gibbs energy of a perfect gas when it is compressed isothermally at a temperature of 298 K from a pressure of 1 MPa to 5 MPa </center>

```
```col-md
flexGrow=2
===
##### 答える：

$$\begin{matrix} \Delta G = \Delta H - T \Delta S \\  \\ \Delta S = \int\limits^{T_{2}}_{T_{1}} \dfrac{C_{P}}{T}\space  dT - R \text{ ln}\begin{pmatrix}\dfrac{P_{2}}{P_{1}}\end{pmatrix} \end{matrix}$$
- Since this is operated isothermally, we can cancel the temperature term for entropy
> $$\begin{matrix} \Delta S =\cancelto{0}{ \int\limits^{T_{2}}_{T_{1}} \dfrac{C_{P}}{T}\space  dT} - R \text{ ln}\begin{pmatrix}\dfrac{P_{2}}{P_{1}}\end{pmatrix} \\  \\ \Delta S= -\begin{pmatrix} 8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix}\text{ ln}\begin{pmatrix}\dfrac{\text{5 MPa}}{\text{1 MPa}}\end{pmatrix} \\  \\ \Delta S=-13.3809 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{matrix}$$
- Calculate for the Gibbs free energy, once again assuming enthalpy is negligible
> $$\begin{matrix}  \Delta G = \cancelto{0}{\Delta H}- \begin{pmatrix} \text{298 K} \end{pmatrix}\begin{pmatrix} -13.3809 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix} \\  \\ \Delta G = \underline{\mathbf{3987.5 \frac{J}{mol}}}=\underline{\mathbf{3.99 \frac{kJ}{mol}}} \end{matrix}$$
> - In ideal gases, change in enthalpy is dependent on temperature, and since temperature change is zero, it would also be zero


```
````
****
````col
```col-md
> [!question] Reactive Energy Balances
> ###### Estimate the absolute enthalpy of $\text{5.3kg}$ of oxygen gas a $283 \degree  \text{F}$, atmospheric pressure, in reference to the standard thermodynamic state
> - The $C_{p}$ function for oxygen gas is given as
> 
> $$\begin{matrix} \dfrac{C_{p}}{R}=a+bT+cT^{2}+\dfrac{d}{T^{2}} \end{matrix}$$
> - $a=3.639$
> - $b=5.06 \cdot 10^{-4}$
> - $c=0$
> - $d=-2.27 \cdot 10^{4}$
> - $T$ is in *$\text{K}$*
> - Assume ideal behavior
> ****
> - **(A)** $\text{573 kJ}$
> - **(B)** $-\text{573 kJ}$
> - **(C)** $\text{108 kJ}$
> - **(D)** $\text{-108kJ}$


```
```col-md
flexGrow=2
===
****
###### <center> Answer: </center>
# <center>A. **$\text{573 kJ}$**</center>
****
1) By dimensional analysis, $\frac{C_{p}}{R}$ is dimensionless
> $$\begin{matrix} \begin{matrix} \begin{matrix} C_{p}  & [=]  & \frac{\text{J}}{\text{kg}\cdot \text{K}}  & \rightarrow  & \textcolor{#D8A78D}{\frac{\text{J}}{\text{mol}\cdot \text{K}}} \\  \\ R & [=] & \textcolor{#D8A78D}{\frac{\text{J}}{\text{mol}\cdot \text{K}}}  & \rightarrow  & \frac{\text{Pa}\cdot \text{m}^{3}}{\text{mol}\cdot \text{K}} \end{matrix} &   & \dfrac{C_{p}}{R}  & \rightarrow & \text{dimensionless} \end{matrix}  \\  \\ \text{So when} \\ C_{p} = \begin{bmatrix} a+ bT + cT^{2}+\dfrac{d}{T^{2}} \end{bmatrix}R \\  \\ R \text{ provides the unit} \end{matrix}$$
2) We are to find the absolute enthalpy for $\text{O}_{2}$ 
> $$\begin{matrix} \text{The standard enthalpy of formation for a pure element is} \\ H_{f}^{\degree=0 \\  \\ h=\cancelto{0}{h_{f}\degree }+\Delta}h \\  \\ h= 0 + \int\limits^{T}_{T_{r}}C_{p} \space  dT  \end{matrix}$$
> ##### where:
> - $T_{r}$ is the ==standard reference temperature==
> > *Usually at $T_{r}=25 \degree  \text{C}=\text{298.15K}$*
> - $T$ is the ==actual temperature of the system==
> > - In this case, $T=283 \degree  \text{F}=\text{412.59K}$
> 
> $$\begin{matrix} h=\int\limits^{T}_{T_{r}} \begin{bmatrix} a+bT+cT^{2}+ \dfrac{d}{T^{2}} \end{bmatrix}R \space dT \\  \\ h=\int\limits^{\text{412.59K}}_{\text{298.15K}}\begin{bmatrix} 3.639+5.06 \cdot 10^{-4}T+0+\dfrac{2.27 \cdot 10^{4}}{T^{2}} \end{bmatrix}\begin{pmatrix} 8.314 \frac{\text{J}}{\text{K}\cdot \text{mol}} \end{pmatrix} \\  \\ h=3457.86 \frac{\text{J}}{\text{mol}} \\  \\ h=3457.86 \frac{\text{J}}{\text{mol}} \cdot \begin{vmatrix} \text{5.3 kg O}_{2} \end{vmatrix}\cdot  \begin{vmatrix} \dfrac{\text{1 mol}}{\text{0.032 kg O}_{2}} \end{vmatrix}  \begin{vmatrix} \dfrac{\text{1 kJ}}{\text{1000 J}} \end{vmatrix}=\mathbf{573kJ} \end{matrix}$$

```
````
****
### Equilibrium
````col
```col-md
> [!question] 
> The equilibrium constant for the reaction, <u>CO(g) + H<sub>2</sub>O(g) ⇌ CO<sub>2</sub>(g) + H<sub>2</sub>(g)</u>, is K = 1.03 × 10<sup>5</sup> at 298.15 K 
> ****
> ###### <center> Calculate the standard reaction Gibbs energy at this temperature </center>

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} K=\dfrac{[H_{2}][\text{CO}_{2}]}{[\text{H}_{2}\text{O}][\text{CO}]}=1.03 \cdot 10^{5}  \\  \\  \Delta G=-RT \text{ ln }K \\  \\ \Delta G=-\begin{pmatrix} 8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix}\begin{pmatrix}\text{298.15 K} \end{pmatrix}\text{ ln}\begin{pmatrix} 1.03 \cdot 10^{5} \end{pmatrix} \\  \\ \Delta G=\mathbf{\underline{-28612 \frac{J}{mol}}}=\mathbf{\underline{-28.6 \frac{kJ}{mol}}} \end{matrix}$$
```
````
****
````col
```col-md
> [!question] 
> ###### Calculate the equilibrium constant 25C for the reaction: $$\begin{matrix} \text{NO (g)}+\text{O}_{2} \text{ (g)} \rightleftharpoons \text{2NO}_{2} \text{ (g)} \end{matrix}$$ given that $\Delta_{r} G \degree  = -69.8 \frac{\text{kJ}}{\text{mol}}$
> ****
> ###### <center>  </center>
> - **A.** 1.03
> - **B.** 28.2
> - **C.** $1.7 \cdot 10^{12}$
> - **D.** $5.91 \cdot 10^{-13}$

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} \Delta G = -RT \text{ ln }K  \hspace{0.5cm} \rightarrow \hspace{0.5cm} K=\text{exp}\begin{bmatrix}-\dfrac{\Delta G}{RT} \end{bmatrix} \\  \\ K=\text{exp}\begin{bmatrix}-\dfrac{\begin{pmatrix}-69.8 \frac{\text{kJ}}{\text{mol}} \end{pmatrix}}{\begin{pmatrix}8.314 \frac{\text{J}}{\text{K}\cdot \text{mol}} \end{pmatrix}\begin{pmatrix} \text{25+273.15K} \end{pmatrix}}  \end{bmatrix} \\  \\ K=\mathbf{\underline{1.7 \cdot 10^{12}}} \end{matrix}$$
```
````
****
````col
```col-md
> [!question] 
> - The reaction:
> 
> $$\begin{matrix} \text{Si (s)}+ \text{2H}_{2}\text{ (g)} \rightleftharpoons \text{SiH}_{4} \text{ (g)} \end{matrix}$$ is spontaneous at te 298 K
> - The standard enthalpy reaction is $\Delta_{r} H \degree  = -61.9 \frac{\text{kJ}}{\text{mol}}$ and standard entropy of reaction is $\Delta_{r} S \degree =-76.7 \frac{\text{J}}{\text{mol}\cdot \text{K}}$
> ****
> ###### <center> At what temperature does the reaction cease to be spontaneous? </center>

```
```col-md
flexGrow=2
===
##### 答える：
- A negative Gibbs free energy means a reaction is spontaneous
- At zero, it ceases to be spontaneous

$$\begin{matrix} \cancelto{0}{\Delta G} =  \Delta  H - T  \Delta S \\  \\  0 = \Delta_{r}H \degree  - T \Delta_{r} S \degree \\  \\ T=\dfrac{\Delta_{r} H \degree}{\Delta_{r}S \degree}=\dfrac{-61.9 \frac{\text{kJ}}{\text{mol}\cdot \text{K}}\cdot  \begin{vmatrix} \frac{\text{1000 J}}{\text{1 kJ}} \end{vmatrix}}{-76.7 \frac{\text{J}}{\text{mol}\cdot \text{K}}} \\  \\ T=\mathbf{\underline{807\space  K}}  \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> - When equal amounts of hydrogen, $\text{H}_{2}$, and iodine, $\text{I}_{2}$, are mixed together at a total pressure of 1 bar, the partial pressure of hydrogen iodide, $\text{HI}$, vapour produced from the reaction $\text{H}_{2} \text{ (g)}+\text{I}_{2}\text{ (g)} \rightleftharpoons \text{2HI (g)}$ is $\text{22.8 kPa}$
> ****
> ###### <center> Calculate the equilibrium constant for the reaction </center>

```
```col-md
flexGrow=2
===
##### 答える：

$$\begin{matrix} K=\dfrac{P_{\text{HI}}^{2}}{P_{\text{H}_{2}}P_{\text{I}_{2}}} \\  \\ P_{T}=\text{1 bar}\cdot  \begin{vmatrix} \dfrac{\text{100 kPa}}{\text{1 bar}} \end{vmatrix}=\text{100 kPa} \\  \\ P_{T}=P_{\text{H}_{2}}+P_{\text{I}_{2}}+P_{\text{HI}} \\  \\  P_{\text{H}_{2}}=P_{\text{I}_{2}}=P \\  \\ P=\dfrac{P_{T}-P_{\text{HI}}}{2}=\dfrac{\text{100 kPa}-\text{22.8 kPa}}{2} \\  \\ P=\text{(38.6 kPa)} \\  \\ K=\dfrac{P_{\text{HI}}^{2}}{P \cdot P}=\dfrac{\begin{pmatrix} \text{22.8 kPa} \end{pmatrix}^{2}}{\text{(38.6 kPa)}\text{(38.6 kPa)}} \\  \\ K=  \mathbf{\underline{0.3489}} \end{matrix}$$


```
````
****
````col
```col-md
> [!question] 
> - The equilibrium constant for the ==gas-phase reaction==: N<sub>2</sub>O<sub>4</sub>(g) ⇌ 2NO<sub>2</sub>(g) is 0.1179
> ****
> ###### <center> Calculate the mole fraction of nitrogen dioxide, NO<sub>2</sub>, in the equilibrium reaction mixture when the total pressure is exactly 1 bar </center>

```
```col-md
flexGrow=2
===
##### 答える：

$$\begin{matrix}  K=\dfrac{P_{\text{NO}_{2}}^{2}}{P_{\text{N}_{2}\text{O}_{4}}}=0.1179 \\  \\  P_{T}=P_{\text{NO}_{2}} + P_{\text{N}_{2}\text{O}_{4}} \\  \\ \underline{\text{Assume:}} \\ P_{\text{NO}_{2}}=x\cdot P_{T} \\ P_{\text{N}_{2}\text{O}_{4}}=(1-x)\cdot P_{T} \\  \\  \underline{\text{Cancel }P_{T} \text{ and subsitute into }K:} \\  \\ \dfrac{x^{2}}{1-x}=0.1179 \\  \\ x^{2}+0.1179x-0.1179 \\  \\ \underline{\text{Get the roots from calculator:}} \\ \begin{matrix} x & = & \underline{\mathbf{0.2894}} \\ x & = & -0.4073   \end{matrix}   \\ \fbox{Negative value not permissible} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> - The equilibrium constant for the reaction: $\text{PCl}_{3} \text{ (g)}+\text{Cl}_{2} \text{ (g)} \rightleftharpoons \text{PCl}_{5}\text{ (g)}$ is $K=3.29 \cdot 10^{6}$ at $\text{298 K}$
> ****
> ###### <center> Calculate the value of $K_{C}$, the equilibrium constant expressed in terms of concentrations </center>

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} \text{PCl}_{3} \text{ (g)}+\text{Cl}_{2} \text{ (g)}\rightleftharpoons \text{PCl}_{5} \text{ (g)} \end{matrix}$$
- The equilibrium constant in terms of pressure and concentration can be related as
> $$\begin{matrix} K_{P}=K_{C} \begin{pmatrix} RT \end{pmatrix}^{\Delta n}  \hspace{0.5cm} \rightarrow \hspace{0.5cm} K_{C}=\dfrac{K_{P}}{\begin{pmatrix} RT \end{pmatrix}^{\Delta n}} \\  \\ \Delta n= \begin{pmatrix}\text{moles of product}-\text{moles of reactants} \end{pmatrix} \\  \\ \Delta n =(1-(1+1))=-1 \\  \\ K_{C}=\dfrac{3.29 \cdot 10^{6}}{\begin{bmatrix} \begin{pmatrix}8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix}\begin{pmatrix} \text{298 K} \end{pmatrix} \end{bmatrix}^{-1}} \\  \\ K_{C}=\underline{\mathbf{8.15 \cdot 10^{9}}} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> - The equilibrium constant for the reaction 2HCl(g) + O2(g) ⇌ H2O(g) + Cl2(g) is 13300 at 400 K and 429 at 500 K
> ****
> ###### <center>Use the van't Hoff equation to determine the standard enthalpy of reaction</center>

> [!important] Look
> Notice that the Van't Hoff equation is a derivation of the Clausius-Clapeyron Equation

```
```col-md
flexGrow=2
===
##### 答える：

$$\begin{matrix} \fbox{Van't Hoff Equation} \\  \text{ln}\begin{pmatrix}\dfrac{K_{2}}{K_{1}}\end{pmatrix}=-\dfrac{\Delta H \degree }{R}\begin{pmatrix}\dfrac{1}{T_{2}}-\dfrac{1}{T_{1}}\end{pmatrix} \\  \\ \Delta H \degree =-\dfrac{\text{ln}\begin{pmatrix}\dfrac{K_{2}}{K_{1}}\end{pmatrix}R}{\dfrac{1}{T_{2}}-\dfrac{1}{T_{1}}} \\  \\ \Delta H \degree  =-\dfrac{\text{ln}\begin{pmatrix}\dfrac{429}{13300}\end{pmatrix}\begin{pmatrix} 8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix}}{\dfrac{1}{\text{500 K}}-\dfrac{1}{\text{400 K}}} \\  \\ \Delta H \degree =\mathbf{\underline{-57101 \space  \frac{J}{mol}}}=\underline{\mathbf{-57.1 \space  \frac{kJ}{mol}}} \end{matrix}$$

```
````
- !! NEW
````col
```col-md
> [!question] 
> - Consider a solution of ethyl acetate and sodium hydoxide at 298.15K
> - The initial concentrations of ethyl acetate and sodium hydroxide are $5 \cdot 10^{-3} \frac{\text{mol}}{\text{L}}$
 and $8\cdot 10^{-3} \frac{\text{mol}}{\text{L}}$, respectively
> - A 25-mL aliquot of the solution neutralied 33 mL of $5 \cdot 10^{-3} \frac{\text{mol}}{\text{L}}$ HCl after 400 s
> ****
> ###### <center> Determine the time expected for 20.0 mL of HCl to be required </center>
> - **A.** 
> - **B.** 
> - **C.** 
> - **D.** 

```
```col-md
flexGrow=2
===
##### 答える：

```
````
****
### Electrochemical Cells
````col
```col-md
> [!question] 
> The standard cell potential for the reaction: <u>2Ag(s) + Cl<sub>2</sub>(g) ⇌ 2Ag<sup>+</sup>(aq) + 2Cl<sup>-</sup>(aq)</u> is +0.56 V
> ****
> ###### <center> Use the Nernst equation to calculate the electrochemical potential at 298.15 K for the cell: Ag(s) | Ag+ (aq, 0.34 M)║Cl2 (g, 0.55 atm) |Cl– (aq, 0.098 M)|Pt(s) </center>

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} \text{Ag (s) | Ag}^{+} \text{ (aq, 0.34 M) || Cl}_{2}\text{ (g, 0.55 atm) | Cl}^{-} \text{ (aq, 0.098M) | Pt (s)} \end{matrix}$$
$$\begin{matrix} E=E \degree  - \dfrac{RT}{nF}   \text{ ln }Q \\  \\ \text{2Ag (s)}+\text{Cl}_{2} \text{ (g)}\rightleftharpoons \text{2Ag}^{+} \text{ (aq)}+\text{2Cl}^{-} \text{ (aq)} \\ \underline{\text{Two electrons are transferred from silver to chlorine}} \\  n=2  \\  \\ \underline{\text{Dalton's Law:}} \\ y_{A}=\dfrac{P_{A}}{P_{T}}=\dfrac{\text{0.55 atm}}{\text{1 atm}}=\text{0.55 M} \\  \\ Q=\dfrac{[\text{Ag}^{+}]^{2}[\text{Cl}^{-}]^{2}}{[\text{Cl}_{2}]}=\dfrac{[\text{0.34 M}]^{2}[\text{0.098 M}]^{2}}{\text{[0.55 atm]}}=2.019 \cdot 10^{-3}  \\  \\ E=\text{0.56 V}-\dfrac{\begin{pmatrix} 8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix}\begin{pmatrix} \text{298.15 K} \end{pmatrix}}{\begin{pmatrix} 2 \end{pmatrix}\begin{pmatrix} \text{96485 C} \end{pmatrix}}\text{ ln}(2.019 \cdot 10^{-3}) \\  \\ E=\mathbf{\underline{0.6397 V}} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> For many substances, the variation with temperature of the molar heat capacity at constant pressure of is given by the expression For copper, a = 22.64 J K–1 mol–1, b = 6.28 × 10–3 J K–2 mol–1 with the value of c being negligible
> ****
> ###### <center> Calculate the change in the molar enthalpy of copper when it is heated from 293 to 323 K </center>

```
```col-md
flexGrow=2
===
##### 答える：
- The presence of coefficients $a$ and $b$ calls for Case 2 of the enthalpy change equation
> $$\begin{matrix}  \Delta H = \int\limits^{T_{2}}_{T_{1}} \underset{C_{P}}{\underline{a+bT+\cancelto{0}{cT^{2}}}}\space  dT \\  \\ \Delta H = \int\limits^{\text{323 K}}_{\text{293 K}}\begin{pmatrix}22.64 \frac{\text{J}}{\text{K}\cdot \text{mol}} \end{pmatrix} + \begin{pmatrix}6.28 \cdot 10^{-3} \frac{\text{J}}{\text{K}^{2} \cdot \text{mol}} \end{pmatrix}T \space  dT \\  \\ \Delta H =\underline{\mathbf{737.2272 \frac{J}{mol}}} \end{matrix}$$


```
````
- !! NEW
````col
```col-md
> [!question] 
> 1) ###### <center> Calculate the standard cell potential below using the values for the standard cell potential </center>
> ****
> 2) ###### <center> Calculate for the standard Gibbs Free Energy </center>
> ****
> 3) ###### <center> Calculate the cell potential at 323.15K using the Nernst equation </center>
> - Given that the molal concentration of the $\text{Pb}^{2+}$ aqueous solution $(\text{PbI}_{2})$ is 0.08 mol/kg
> - Use the Davies equation to estimate the mean ionic coefficient
> 
> 
> $$\begin{matrix} \text{Pb}_{\text{(s)}}\rightarrow \text{Pb}^{2+} + \text{2e}^{-}  \\ \hline \underline{\text{(Anode)}} \\  \\ \text{PbI}_{2 \space  \text{(s)}} + \text{2e}^{-} \rightarrow \text{Pb}_{\text{(s)}} + \text{2I}^{-}  \\ \hline \underline{\text{(Cathode)}}  \end{matrix}$$
> ****
> ###### <center>  </center>
> - **A.** 
> - **B.** 
> - **C.** 
> - **D.** 

```
```col-md
flexGrow=2
===
##### 答える：

|Half-cell reaction|$E \degree  /V$||Half-cell reaction | E°/V|
|----|----|----|---|---|
|K⁺ + e⁻ → K | -2.936||D₂ + 2e⁻ → D₂ | -0.01|
|Ca²⁺ + 2e⁻ → Ca | -2.868||2H⁺ + 2e⁻ → H₂ | 0|
|Na⁺ + e⁻ → Na | -2.714||AgBr(c) + e⁻ → Ag + Br⁻ | 0.073|
|Mg²⁺ + 2e⁻ → Mg | -2.360||AgCl(c) + e⁻ → Ag + Cl⁻ | 0.2222|
|Al³⁺ + 3e⁻ → Al | -1.677||Hg₂Cl₂(c) + 2e⁻ → 2Hg(l) + 2Cl⁻ | 0.2680|
|2H₂O + 2e⁻ → H₂(g) + 2OH⁻ | -0.828||Cu²⁺ + e⁻ → Cu | 0.339|
|Zn²⁺ + 2e⁻ → Zn | -0.762||Cu⁺ + e⁻ → Cu | 0.518|
|Ga³⁺ + 3e⁻ → Ga | -0.549||I₂(c) + 2e⁻ → 2I⁻ | 0.535|
|Fe²⁺ + 2e⁻ → Fe | -0.44||Hg₂SO₄(c) + 2e⁻ → 2Hg(l) + SO₄²⁻ | 0.615|
|Cd²⁺ + 2e⁻ → Cd | -0.402||Fe³+ + e− -> Fe²+ | 0.771|
|Pb₂(c) + 2e⁻ → Pb + 2I⁻ | 0.365||Ag+ + e− -> Ag | 0.7992|
|PbSO₄(c) + 2e⁻ → Pb + SO₄²⁻ | 0.336||Br₂(l) + e− -> 2Br−| 1.078|
|Sn²⁺ + 2e⁻ → Sn(white) | -0.141||O₂(g) + 4H+ -> 4e− -> H₂O| 1.229|
|Pb²⁺ + 2e⁻ → Pb | -0.125||Cl₂(g) + 4H+ -> 4e− -> Cl−| 1.360|
|Fe³⁺ + 3e⁻ → Fe | -0.04||Au+ + e− -> Au| 1.69|

<i><center>Standard Electrode Potentials in $\text{H}_{2}\text{O}$ at $25 \degree  \text{C}$ and 1 br</center></i>

















```
````

****
### Reversible Processes
````col
```col-md
> [!question] Reversible Processes
> - Nitrogen is expanded isentropically
> - Its temperature changes from $620 \degree  \text{F}$ to $60 \degree  \text{F}$
> - If the volumetric ratio is $\frac{V_{2}}{V_{1}}=6.22$
> ###### What is the work done by the gas?
> - **(A)** $-1113 \frac{\text{BTU}}{\text{lb}}$
> - **(B)** $-99 \frac{\text{BTU}}{\text{lb}}$
> - **(C)** $-120 \frac{\text{BTU}}{\text{lb}}$
> - **(D)** $-540 \frac{\text{BTU}}{\text{lb}}$

> [!important] GIven
> - $\text{N}_{2}$ gas
> - $T_{1}=620 \degree  \text{F}$
> - $T_{2}=60 \degree  F$
> - $\frac{V_{2}}{V_{1}}=6.22$


```
```col-md
flexGrow=2.5
===
****
###### Answer:
# B. **$-99 \frac{\text{BTU}}{\text{lb}}$**
****
1) Since it is stated that the expansion is *isentropic*, we turn to polytropic relationships
> $$\begin{matrix} \fbox{Polytropic Processes} \\ PV^{k}=\text{constant} \end{matrix}$$
> - $k=0$ *(isobaric)*
> - ==$k= \gamma$ *(isentropic)*==
> ****
> - We assume that nitrogen is *ideal*
> - For ==diatomic gases==: $\gamma=\frac{C_{P}}{C_{V}}=1.4$
> 
> $$\begin{matrix}  PV=RT  \hspace{0.5cm} \rightarrow \hspace{0.5cm} P_{1}=\dfrac{RT_{1}}{V_{1}} \\  \\ P_{1}V_{1}^{k}=P_{2}V_{2}^{k} \\  \\  \end{matrix}$$
2) To solve for the work done by the expansion, we integrate our expression in terms of our assumptions
> $$\begin{matrix} W=- \int\limits^{}_{} P \space  dV &   & k=\gamma=\dfrac{C_{P}}{C_{V}} \\  \\ W=-\int\limits^{}_{} \dfrac{C}{V^{\gamma}} \space  dV  &    & P = \dfrac{C}{V^{\gamma}} \\  \\ W=-C \int\limits^{}_{} \dfrac{dV}{V^{\gamma}} \\  \\ W=-C \int\limits^{}_{}=-C \int\limits^{}_{}V^{-\gamma} \space  dV \\  \\ W=-C \dfrac{V^{1- \gamma }}{-\gamma + 1} \biggr\rvert^{V_{2}}_{V_{1}} \\  \\ W=-\begin{pmatrix} P_{1}V_{1}^{\gamma} \end{pmatrix}\begin{pmatrix}\dfrac{V_{2}^{1-\gamma}-V_{1}^{1-\gamma}}{1-\gamma}\end{pmatrix} &   & C=P_{1}V_{1}^{\gamma} \\  \\ W=-\begin{pmatrix}\dfrac{RT_{1}V_{1}^{\gamma}}{V_{1}}\end{pmatrix}\begin{pmatrix}\dfrac{V_{2}^{1-\gamma}-V_{1}^{1-\gamma}}{1-\gamma}\end{pmatrix}  &   & P_{1}=\dfrac{RT_{1}}{V_{1}} \\  \\  W=-\begin{pmatrix} RTV_{1}^{\gamma-1} \end{pmatrix}\begin{pmatrix}\dfrac{\begin{pmatrix} 6.22V_{1} \end{pmatrix}^{1-\gamma}-V_{1}^{1-\gamma}}{1-\gamma}\end{pmatrix} &   & \begin{matrix} \dfrac{V_{2}}{V_{1}}=6.22  \\  \\  V_{2}=6.22 V_{1} \end{matrix} \\  \\ W=- \begin{pmatrix} RT \end{pmatrix}\underset{\text{These cancel each other}}{\underline{\begin{pmatrix} V_{1}^{\gamma-1} \end{pmatrix}\begin{pmatrix} V_{1}^{1-\gamma} \end{pmatrix}}}\begin{pmatrix}\dfrac{6.22^{1-\gamma}-1}{\gamma-1}\end{pmatrix} &   & V_{1}^{-(\gamma-1)}=\dfrac{1}{V_{1}^{\gamma-1}}=V_{1}^{1-\gamma} \\  \\ W=-RT_{1} \begin{pmatrix}\dfrac{6.22^{1-\gamma}-1}{1-\gamma}\end{pmatrix}  \end{matrix}$$
> - $R=8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}}$
> - $\gamma=1.4$
> - $T_{1}=620 \degree  \text{F}=\text{599.82K}$
> 
> $$\begin{matrix} W=-\begin{pmatrix} 8.314 \frac{\text{J}}{\text{mol}\cdot \text{K}} \end{pmatrix}\begin{pmatrix} \text{599.82K}\end{pmatrix}\begin{pmatrix} \dfrac{6.22^{1-1.4}-1}{1-1.4} \end{pmatrix} \\  \\ W=-6465.83 \frac{\text{J}}{\text{mol}} \cdot  \begin{vmatrix} \dfrac{\text{1BTU}}{\text{1055J}} \end{vmatrix} \cdot  \begin{vmatrix} \dfrac{\text{1 mol}}{\text{28.02 g}} \end{vmatrix}\cdot  \begin{vmatrix} \dfrac{\text{453.6 g}}{\text{1 lb}} \end{vmatrix} \\  \\ W=\mathbf{-99.21 \dfrac{BTU}{lb}} \end{matrix}$$

```
````
****
### Arrhenius Equation
- !! NEW
````col
```col-md
> [!question] 
> - The thermal cracking reaction of n-noname at $827 \degree  \text{C}$ is 20 times as fast at $727 \degree  \text{C}$
> ****
> ###### <center> What are the Arrhenius parameters $A$ and $E_{A}$? </center>
> - **A.** 
> - **B.** 
> - **C.** 
> - **D.** 

```
```col-md
flexGrow=2
===
##### 答える：

```
````
****
### Heat Transfer
````col
```col-md
> [!question] 
> - The temperature of a copper block of mass 423g rises by 10.1 °C 
> ****
> ###### Calculate the heat transferred, given that the specific heat capacity of copper is 385 J K<sup>–1</sup> kg<sup>–1</sup>

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} Q=mC_{p} \Delta T \\  \\ Q=\begin{pmatrix}\text{423 g}\cdot  \begin{vmatrix} \dfrac{\text{1 kg}}{\text{1000 g}} \end{vmatrix} \end{pmatrix}\begin{pmatrix} 385  \space  \frac{\text{J}}{\text{kg}\cdot \text{K}} \end{pmatrix}\begin{pmatrix}\text{10.1 + 273.15} \end{pmatrix} \\  \\ Q=\underline{\mathbf{46129 \space  J}} \end{matrix}$$
```
````
****
````col
```col-md
> [!question] 
> - A calorimeter was calibrated by passing an electrical current through a heater and measuring the rise in temperature that resulted
> - When a current of 113 mA from a 24.1 V source was passed through the heater for 254 s, the temperature of the calorimeter rose by 2.61 °C
> ****
> ###### <center> Determine the heat capacity of the calorimeter </center>

```
```col-md
flexGrow=2
===
##### 答える：
- To determine the heat capacity of an **electrical calorimeter**, we can use the following relation
> $$\begin{matrix} \fbox{Electrical Calorimeter} \\ Q=C_{P} \Delta T \\  \\ P=VI \hspace{2cm}  Q=Pt \end{matrix}$$
> ##### where:
> - $Q$ is the ==heat absorbed by the calorimeter== in *$\text{J}$*
> - $C_{P}$ is the ==heat capacity of the calorimter== in *$\frac{\text{J}}{\text{K}}$*
> - $\Delta T$ is the ==change in temperature in the calorimeter== in *$\text{K}$*
> - $P$ is the ==electrical power== in *$\text{W}$* or *$\frac{\text{J}}{\text{s}}$*
> - $V$ is the ==voltage== in *$\text{V}$*
> - $I$ is the ==current== in *$\text{A}$*
> - $t$ is the ==time== in *$\text{s}$*

- First, we solve for the electrical charge applied to the calorimter
> $$\begin{matrix} \begin{matrix} P=VI \\  \\ P=\begin{pmatrix}\text{24.1 V} \end{pmatrix}\begin{pmatrix} \text{113 mA}\cdot  \begin{vmatrix} \frac{\text{1 A}}{\text{1000 mA}} \end{vmatrix} \end{pmatrix} \\  \\ P=\text{2.7233 W}  \end{matrix} &  \hspace{1cm}  & \begin{matrix} Q=Pt \\  \\ Q=\begin{pmatrix}\text{2.7233 W} \end{pmatrix}\begin{pmatrix} \text{254 s} \end{pmatrix} \\  \\ Q=691.7182 \text{ J} \end{matrix} \end{matrix}$$
- A temperature change in *$\text{Celsius}$* is the same as a temperature change in *$\text{Kelvin}$*
> $$\begin{matrix} \Delta T \text{ (C)}=\Delta T \text{ (K)}=2.61 \text{ K} \end{matrix}$$
- Then we solve for the heat capacity at constant pressure
> $$\begin{matrix} Q=C_{P} \Delta T  \hspace{0.5cm} \rightarrow \hspace{0.5cm} C_{P}=\dfrac{Q}{T} \\  \\ C_{P}=\dfrac{691.7182 \text{ J}}{\text{2.61}\degree  \text{K}} \\  \\ C_{P}=\mathbf{\underline{265 \space  \frac{J}{K}}} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> - The molar heat capacity at constant volume of argon, Ar, is $12.47 \frac{\text{J}}{\text{mol}\cdot \text{K}}$
> ****
> ###### <center> What is the value of the molar heat capacity at constant pressure? </center>
> - **A.** $4.15  \frac{\text{J}\cdot \text{K}}{\text{mol}}$
> - **B.** $8.31 \frac{\text{J}\cdot \text{K}}{\text{mol}}$
> - **C.** $12.47 \frac{\text{J}\cdot \text{K}}{\text{mol}}$
> - **D.** $20.78 \frac{\text{J}\cdot \text{K}}{\text{mol}}$

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} C_{P} & = & C_{V}+R \\  \\  & = & 12.47 \frac{\text{J}}{\text{mol} \cdot \text{K}}+8.314 \frac{\text{J}}{\text{mol} \cdot \text{K}} \\  \\  & = & \mathbf{\underline{20.784 \space \frac{J}{K \cdot mol}}} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> - In an experiment to determine its enthalpy of vaporization, liquid tetrachloromethane, CCl4, was placed in an open boiler that was equipped with a resistive heating coil and brought to the boil at a constant temperature of 350 K and pressure of 1 bar 
> - The passage of a current of 0.933 A from a 24.0 V supply for 30.0 s was found to result in the vaporization of 3.45 g of tetrachloromethane
> ****
> ###### <center> Calculate the standard enthalpy of vaporization of tetrachloromethane at 350 K </center>

```
```col-md
flexGrow=2
===
##### 答える：

1) Solve for the heat
> $$\begin{matrix} P=VI \hspace{2cm}  Q=Pt \\  \\ \begin{matrix} P=\begin{pmatrix} \text{24.0 V} \end{pmatrix}\begin{pmatrix}\text{0.933 A} \end{pmatrix} \\  \\ P=\text{22.392 W} \end{matrix} \hspace{2cm} \begin{matrix} Q=\begin{pmatrix}\text{22.392 W} \end{pmatrix}\begin{pmatrix}\text{30.0 s} \end{pmatrix} \\  \\ \underline{Q=\text{671.6 J}}  \end{matrix} \end{matrix}$$
2) Solve for the moles affected
> $$\begin{matrix} M_{\text{CCl}_{4}}=1(12.01)+4(35.453) = 153.822 \frac{\text{g}}{\text{mol}} \\  \\ n=\dfrac{m}{M_{\text{CCl}_{4}}} \\  \\ n=\dfrac{\text{3.45 g}}{153.822 \frac{\text{g}}{\text{mol}}} \\  \\ n=\text{0.02243 mol} \end{matrix}$$
3) Solve for the standard heat of vaporization
> $$\begin{matrix} \Delta H_{\text{vap}}=\dfrac{Q}{n} \\  \\ \Delta H_{\text{vap}}=\dfrac{\text{671.6 J}}{\text{0.02243 mol}} \\  \\ \Delta H_{\text{vap}}=\mathbf{\underline{29942 \frac{J}{mol}}}\approx  \underline{\mathbf{30.0 \frac{kJ}{mol}}} \end{matrix}$$

```
````
****
````col
```col-md
> [!question] 
> - The energy released as heat when liquid propanone, CH<sub>3</sub>COCH<sub>3</sub>, is burned in a bomb calorimeter at 298.15 K is 1788 kJ mol<sup>–1</sup>
> ****
> ###### <center> Calculate the enthalpy of combustion of propanone </center>

```
```col-md
flexGrow=2
===
##### 答える：
- A change in the enthalpy of combustion and change in temperature together make up the ==total enthalpy change of a system==
> $$\begin{matrix}  \Delta H_{\text{total}}=nC_{p}(T_{\text{out}}-T_{\text{in}})+\Delta H_{\text{rxn}} \\  \\ \Delta H_{\text{total}}=\underset{\fbox{Sensible Heat Change}}{\underline{nC_{p}(T_{\text{out}}-T_{\text{in}})}}+\underset{\fbox{Latent Heat Change}}{\underline{\Delta H_{\text{rxn}}}} \end{matrix}$$
> 
> - A change in temperature is generally associated with the **sensible heat change**
> - A change in the enthalpy of combustion (aka the enthalpy of reaction) is associated with the **latent heat change**

- Since the problem already tells us the heat ***given off*** from the calorimeter, our answer is
> $$\begin{matrix} \mathbf{-1788 \frac{kJ}{mol}} \\ \textcolor{#D8A78D}{\text{(exothermic reaction)}} \end{matrix}$$

```
````
****
- !! NEW
````col
```col-md
> [!question] 
> - An electric motor under steady load drawes 9.7 amperes at 110 volts, delivering 1.25 hp of mechanical energy
> ****
> ###### <center> What is the rate of heat transfer from the motor, in kW? </center>
> - **A.** 1.19 kW
> - **B.** -0.135 kW
> - **C.** 0.135 kW
> - **D.** 0.295 kW

```
```col-md
flexGrow=2
===
![Pasted image 20241018175623.png](/img/user/14th%20Term/Correlation%20Exam%20(CH195)/Attachments/Pasted%20image%2020241018175623.png)

##### 答える：
$$\begin{matrix} P=VI \\ \hline \\ \\ P_{\text{input}}=\begin{pmatrix}\text{9.7 A} \end{pmatrix}\begin{pmatrix}\text{110 V} \end{pmatrix}=\text{1067 W} \\  \\ P_{\text{output}}=\begin{pmatrix}1\text{1.25 hP} \cdot  \begin{vmatrix} \dfrac{\text{0.7457 kW}}{\text{1 kW}} \end{vmatrix} \end{pmatrix}=\text{0.932 kW} \\  \\ \fbox{Energy Balance} \\ E_{\text{in}}=Q_{\text{out}}+E_{\text{out}} \\  \\ Q_{\text{out}}=E_{\text{in}}-E_{\text{out}} \\  \\ Q_{\text{out}}=1\text{1.067 kW}-\text{0.932 kW} \\  \\ Q_{\text{out}}=\mathbf{\underline{0.135 \space kW}} \end{matrix}$$
```
````
****
````col
```col-md
> [!question] 
> - A tank containing 20 kg of water at $20 \degree  \text{C}$ is fitted with a stirrer that delivers work to water at the rate of $\text{0.25 kW}$
> ****
> ###### <center> How long does it take for the temperature of the water to rise to $30 \degree  \text{C}$ if no heat is lost from the water? </center>
> - For water, $C_{P}=4.184 \frac{\text{kJ}}{\text{kg}\cdot \degree  \text{C}}$
> ****
> - **A.** 1829 s
> - **B.** 3347 s
> - **C.** 3511 s
> - **D.** 2912 s

```
```col-md
flexGrow=2
===
##### 答える：
$$\begin{matrix} \begin{matrix} Q & = & m C_{P} \Delta T \\  \\  & = & \begin{pmatrix} \text{20 kg} \end{pmatrix}\begin{pmatrix} \end{pmatrix} \end{matrix} \end{matrix}$$
```
````
****

## Concept Questions
````col
```col-md
> [!question] Reversible Processes
> - A piston-cylinder assembly intially has a gas contained inside at a volume of $V$ and temperature of $T$
> - When the latches are released, the piston rises up against a vacuum
> ###### Which of the following best describes the work done by the gas? 
> - **(A)** $C_{p}T$
> - **(B)** $>0$
> - **(C)** $0$
> - **(D)** $RT \text{ ln}\begin{pmatrix}\dfrac{P_{2}}{P_{1}}\end{pmatrix}$

```
```col-md
flexGrow=2
===
![Pasted image 20231230002700.png](/img/user/10th%20Term/CH138X/Attachments/Pasted%20image%2020231230002700.png)
****
###### Answer:
# C. **0**
****
- In a vacuum, the external pressure $P_{\text{ex}}=0$ is zero, making our work term from the expansion become
> $$\begin{matrix} W_{\text{ex}}=- \int\limits^{}_{}P_{\text{ex}} \space  dV \\  \\ W_{\text{ex}}=0 \end{matrix}$$

- So long as a system is reversible
> - There is ==no change in internal energy==
> - ==No external work done==

```
````
****
```````col
``````col-md
> [!question] Equations of State
> ###### What is the significance of the parameter "b" in the Van der Waals equation of state?
> - **(A)** It corrects for truncation error
> - **(B)** It accounts for molecular volume
> - **(C)** It corrects for energy losses due to collision of molecules
> - **(D)** It accounts for intermolecular forces

``````
``````col-md
flexGrow=2
===
****
###### Answer:
# B. **It accounts for molecular volume**
****


````col
```col-md
- The easiest assumption to make for a gas, is that it behaves ==ideally==
- An **ideal gas** is a gas that has
> - *Negligible* ***atomic volume*** ==$(b=0)$==
> - *Negligible* ***intermolecular forces*** ==$(a=0)$==
```
```col-md
flexGrow=1.5
===
- The **cubic equation of state** ***corrects*** for both ==volume== and ==intermolecular forces==
> $$\begin{matrix} \fbox{General Cubic Equation of State} \\  P=\dfrac{RT}{v-b}-\dfrac{a}{(v+ \epsilon b)(v-\sigma b)} \\  \\ a=\Psi \dfrac{\alpha R^{2}T_{c}^{2}}{P_{c}} \\  \\ b=\Omega \dfrac{RT_{c}}{P_{c}}  \end{matrix}$$
> - Accounting for these factors, makes the predicted gas behavior *more realistic*
```
````

``````
```````
****
````col
```col-md
> [!question] System Properties
> ###### The residual Gibbs free energy of an ideal gas in equilibrium is always
> - **(A)** Negative
> - **(B)** Zero
> - **(C)** Positive
> - **(D)** Undefined

```
```col-md
flexGrow=2
===
****
###### Answer:
# B. **Zero**
****
$$G^{R}=G-G^{\text{ig}}=0$$

```
````
****
````col
```col-md
> [!question] System Properties
> ###### Which of the following best defines enthalpy?
> - **(A)** The energy that is conserved when a system undergoes a constant temperature process
> - **(B)** The energy that is conserved when a system undergoes a constant-pressure process
> - **(C)** The sum of all kinetic energies associated with the translational, rotational, and vibrational motions of the molecules/atoms in the system
> - **(D)** $H=U+PV$

```
```col-md
flexGrow=2
===
****
###### Answer:
# D. **$H=U+PV$**
****
- The sum of all kinetic energies associated with the translational, rotational, and vibrational motions of the molecules/atoms in the system
> - This defines ==internal energy==



```
````
****
````col
```col-md
> [!question] 
> ###### <center>An equation that relates the pressure, volume, and temperature of a sbstance is called a/an:</center>
> - **(A)** Equation of state
> - **(B)** Equilibrium equation
> - **(C)** Probability equation
> - **(D)** Gibbs-Duhem equation
> ****
> <h6><center>Answer:</center></h6>
> <h1><center>A. <b> Equation of state </b></center></h1>

```
```col-md
> [!question] 
> ###### Which of the following equations are used for predicting the activity coefficient of liquid species from experimental data?
> - **(A)** Margules equation
> - **(B)** Wilson equation
> - **(C)** van Laar equation
> - **(D)** All of the choices
> ****
> <h6><center>Answer:</center></h6>
> <h1><center>D. <b> All of the choices </b></center></h1>


```
```col-md
> [!question] 
> ###### As the gas pressure approaches zero, the ratio of fugacity to pressure $(f/P)$ approaches
> - **(A)** 0
> - **(B)** Infinity
> - **(C)** Indeterminate
> - **(D)** 1
> ****
> <h6><center>Answer:</center></h6>
> <h1><center>D. <b> 1 </b></center></h1>

```
````
****
````col
```col-md
> [!question] 
> ###### <center> Which of the following statements is true for an ideal–dilute solution? </center>
> - A. The solute and solvent both obey Raoult's law
> - B. The solute obeys Raoult's law and the solvent obeys Henry's law  
> - C. The solute obeys Henry's law and the solvent obeys Raoult's law
> - D. The solute and solvent both obey Henry's law
> ****
> <h6><center>Answer:</center></h6>
> <h1><center>C. <b> The solute obeys Henry's law and the solvent obeys Raoult's law </b></center></h1>

```
```col-md
> [!question] 
> ###### <center> The standard cell potential for the Daniell cell </center>
> - A. +20.8 J K<sup>-1</sup> mol<sup>-1</sup>
> - B. –20.8 J K<sup>-1</sup> mol<sup>-1</sup>
> - C. +10.4 J K<sup>-1</sup> mol<sup>-1</sup>
> - D. –10.4 J K<sup>-1</sup> mol<sup>-1</sup> 
> ****
> <h6><center>Answer:</center></h6>
> <h1><center>B.<b> –20.8 J K<sup>-1</sup> mol<sup>-1</sup> </b></center></h1>


```
```col-md
> [!question] System Properties
> ###### Which of the following thermodynamic quantities is not a state function
> - **(A)** Enthalpy
> - **(B)** Work
> - **(C)** Entropy
> - **(D)** Internal Energy
> ****
> ###### <center>Answer:</center>
> # <center>B. **Work**</center>
> <center> Work is a <i>path function</i> </center>



```
````
****
````col
```col-md
> [!question] 
> ###### <center> Which of the following statements is always true for a system at equilibrium under conditions of constant temperature and pressure? </center>
> - A. ΔS > 0  
> - B. ΔG = 0  
> - C. dG = dW<sub>max</sub>  
> - D. ΔG > 0
> ****
> <h6><center>Answer:</center></h6>
> <h1><center>C. <b> dG = dW<sub>max</sub> </b></center></h1>

```
```col-md
> [!question] 
> ###### <center> This is the pressure gas molecules exert in equilibrium with teir liquid phase </center>
> - A. Atmoshperic pressure
> - B. Fugacity
> - C. Vapor pressure
> - D. Partial pressure
> ****
> <h6><center>Answer:</center></h6>
> <h1><center>C. <b> Vapor Pressure </b></center></h1>


```
```col-md
> [!question] 
> ###### <center> On a pressure-temperature phase diagram, the conditions under which a one-component system exists as two phases in equilibrium corresponds to: </center>
> - A. a point
> - B. a line
> - C. an area
> - D. the entire diagram
> ****
> <h6><center>Answer:</center></h6>
> <h1><center>B. <b> a line </b></center></h1>


```
````
****
````col
```col-md
> [!question] 
> ###### <center> An isentropic process is... </center>
> ****
> <h1><center><b> Reversible and adiabatic </b></center></h1>

```
```col-md
> [!question] 
> ###### <center> Which of the following conditions is necessary for a reaction to be   spontaneous?   </center>
> 
> - A. ΔS<sub>sur</sub> 0  
> - B. ΔS<sub>sys</sub> > 0  
> - C. ΔS<sub>sur</sub> + ΔS<sub>sys</sub> < 0  
> - D. None of the above
> ****
> <h6><center>Answer:</center></h6>
> <h1><center> C. <b> ΔS<sub>sur</sub> + ΔS<sub>sys</sub> < 0  </b> </center></h1>


```
```col-md
> [!question] 
> ###### <center> For a spontaneous change in a system at constant temperature and pressure, which of the following statements is true? </center>
> - A. ΔG < 0  
> - B. ΔG = 0  
> - C. ΔG > 0  
> - D. There is no restriction on the value of ΔG
> ****
> <h6><center>Answer:</center></h6>
> <h1><center> A. <b>ΔG < 0  </b> </center></h1>


```
````
****
- The amount of heat absorbed when carbon dioxide gas reacts with solid calcium oxide to form solid calcium carbonate is measured in a bomb calorimeter. The data obtained yields a direct measure of ______________.
	- $C_{P}$
	- $\Delta H$ 
	- $V \Delta P$
	- $\Delta U$ ✅
- Which of the following is the basis of the manufacture of thermometers?
	- Boyle's Law
	- Carnot's Principle
	- Raoult's Law
	- Zeroth Law of Thermodynamics ✅
- The net energy available to a system is given by ___________.
	- enthalpy ✅
	- entropy
	- free energy
	- none of these
- After swimming in the ocean for several hours, swimmers notice that their fingers appear to be very wrinkled. This is an indication that seawater is _________ relative to the fluid in their cells.
	- hypertonic ✅
	- hypotonic
	- isotonic
	- supertonic
- Which of the following non-flow reversible compression processes require maximum work?
	- adiabatic process
	- isothermal process ✅ 
	- isobaric process
	- all require the same work
- ? A more stable system with regard to $\Delta H$ are systems that have \_\_\_\_\_.
	- Zero $\Delta H$ 
	- Minimum $\Delta H$ ✅ 
	- Maximum $\Delta H$
	- None of these
- During the adiabatic reversible expansion of an ideal gas, the amount of heat absorbed by the gas is equal to __________.
	- zero ✅ 
	- one
	- greater than zero
	- infinity
- In a reaction that is first-order with respect to reactant A and second order with respect to reactant B, the rate of reaction
	- Doubles with a doubling of the concentration of B
	- Is halved by a doubling of the concentration of B
	- Quadrupled by a doubling in the concentration of B while the concentration of A is held constant
	- Is tripled by any equal and simultaneous increase in the concentration of A and B
	- Doubles with a doubling of the concentration of either reactant
- The activation energy in the Arrhenius equation can be best be described as
	- A numerical description of the amount of energy needed by colliding reactant molecules in order to form products
	- A numerical description of the amount of energy released by colliding reactant molecules in order to form products
	- A factor which corrects for the conversion between joule and kilojoule
	- A numerical description of how often molecules collide with the proper orientation to react at a specific concentration
	- The probability that a collision between molecules will have the correct relative orientation for reaction to occur
- What is the main driving force in the crystallization of aqueous colloidal particles?
	- A difference in supersaturation
	- A difference in solubility
	- A difference in chemical potential
	- A difference in surface tension 
- The primary nucleation of crystals is said to be homogeneous and has a constant exponential rise in its nucleation rate. But if a foreign particle is introduced, the nucleation rate
	- a. will occur at a slower pace at a higher degree of supersaturation.  
	- b. will occur more readily at a lower supersaturation.  
	- c. will occur at a similar pace at the same degree of supersaturation.  
	- d. will be the same as before.
- Which statement concerning the number of electrons involved in electrolysis is incorrect?
	- When one mole of Fe (s) is produced from Fe^3+ (aq), three moles of electrons are needed
	- The total charge is obtained by multiplying the current in amps by the time in seconds
	- Electroplating of one mole of silver from a solution of silver ions requires one mole of electrons
	- In producing one mole of Cl2 (g) from Cl^- (aq), one mole of electrons is produced
- Among the statements given below, which one is incorrect?
	- A voltaic cell is a type of electrochemical cell
	- All electrochemical cells have at least two electrodes
	- A battery is an example of an electrochemical cell
		- An electrochemical cell can extract electrical energy from a reactant-favored chemical reaction

****