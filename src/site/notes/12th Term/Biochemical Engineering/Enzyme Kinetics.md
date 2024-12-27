---
{"dg-publish":true,"permalink":"/12th-term/biochemical-engineering/enzyme-kinetics/","tags":["gardenEntry"]}
---


# Enzyme Kinetics
_______
````col
```col-md

$$\begin{matrix} \nu=-\dfrac{d \text{[S]}}{dt}\biggr\rvert^{}_{t \rightarrow 0}=\dfrac{d \text{[P]}}{dt}\biggr\rvert^{}_{t \rightarrow0} \end{matrix}$$
- With a constant amount of [[Enzymes|enzyme]] in a system, the **rate of catalysis** ***increases*** with ==substrate concentration== but begins to ***plateau*** and reach a maximum upper limit at ==higher substrate concentration== 
> - This is known as **saturation** 


```
````
****
## Kinetic Models
````col
```col-md
![Pasted image 20240531174641.png](/img/user/12th%20Term/Biochemical%20Engineering/Attachments/Pasted%20image%2020240531174641.png)
###### *In all models, an enzyme-substrate complex is formed*

```
````
- The kinetics of many biological reactions are one of five common types
	1) [[Zero-Order Enzyme Kinetics]]
	2) [[First-Order Enzyme Kinetics]]
	3) [[Michaelis-Menten Kinetics]] **(Saturation Kinetics)** 
		1) [[Briggs-Haldane Kinetics]] 
	4) [[Langmuir-Hinselwood Kinetics]] 
	5) [[Allostery|Allosteric Kinetics]]
****
### Solutions
````col
```col-md
|                                |                                                    Lineweaver-Burk (Double-Reciprocal)                                                |           Eadie-Hofstee           |                                    Hanes-Woolf                                    |
| :----------------------------- | :--------------------------------------------------------------------------------------------------------------------: | :-------------------------------: | :-------------------------------------------------------------------------------: |
| Linearized form of MM Equation | $\dfrac{1}{\nu}=\dfrac{1}{\nu_{\text{max}}}+\dfrac{K_{M}}{\nu_{\text{max}}}\begin{pmatrix}\dfrac{1}{[S]}\end{pmatrix}$ | $\nu=\nu_{\text{max}}-K_{m}\dfrac{\nu}{[S]}$ | $\dfrac{[S]}{\nu}=\dfrac{K_{M}}{\nu_{\text{max}}}+\dfrac{1}{\nu_{\text{max}}}[S]$ |
| Plot                           |                                         $\dfrac{1}{\nu}$ vs. $\dfrac{1}{[S]}$                                          |   $\nu$ vs. $\dfrac{\nu}{[S]}$    |                           $\dfrac{[S]}{\nu}$ vs. $[S]$                            |
| |![Pasted image 20240604164229.png](/img/user/12th%20Term/Biochemical%20Engineering/Attachments/Pasted%20image%2020240604164229.png) |![Pasted image 20240604164254.png](/img/user/12th%20Term/Biochemical%20Engineering/Attachments/Pasted%20image%2020240604164254.png) | ![Pasted image 20240604164239.png](/img/user/12th%20Term/Biochemical%20Engineering/Attachments/Pasted%20image%2020240604164239.png)|
| Advantages| Easy to interpret|Detects deviations much easier|Less error, more accurate/stable fitting|
|Disadvantages|Prone to error at low concentrations|Prone to error at high concentrations|Less intuitive for interpretation|

```
````
 - Different kinetics models shows us the different ways the process of **catalysis** *(reactions with enzymes)* 
````col
```col-md

- The order of a reaction must be determined *experimentally*
> - Understanding the stoichiometry of a reaction is *insufficient* to predict the rate law of reaction
> - The determination of values for $K_{m}$ and $\nu_{\text{max}}$ with high precision can be dificult
> - Typically, experimental data are obtained from **initial-rate experiments**
> > 1) A [[Reactors, Design Equations, and Conversion#Batch Reactor|batch reactor]] is charged with a ==known amount of substrate $[S_{0}]$== and ==enzyme $[E_{0}]$==
> > 2) The product or substrate concentration is ***plotted*** against time
> > > $$\begin{matrix} \underline{[S]} & \text{vs} & \underline{t} \end{matrix}$$

```
````
- Accurate determination of $\nu_{\text{max}}$ is difficult, therefore we make use of ***linearizing*** methods and interpret their plots to obtain parameters
	- [[Lineweaver-Burk Plots|Lineweaver-Burk Plots (Double-Reciprocal Plots)]] 
	- [[Eadie-Hofstee Plots]]
	- [[Hanes-Woolf (Langmuir) Plots]]
- In industrial settings, nonlinear methods like *nonlinear* ***regression*** or **[[artificial neural networks|artificial neural networks (ANNs)]]** are preferred for their speed and reliability over traditional methods
****
## Universal Parameters
- The **[[Michaelis-Menten equation]]** is the first to be developed for making sense of the rate of reactions involving enzymes
	- **Briggs-Haldane Kinetics** simplifies the ==M-M equation== under specific conditions when the ==initial substrate concentration== is *greater* than the ==final concentration==
- **Langmuir-Hinselwood Kinetics** is used for [[heterogenous reactions]]
****
``````col
`````col-md
- When the ==reaction rate is half the maximum== *$\begin{pmatrix} \nu= \frac{1}{2} \nu_{\text{max}} \end{pmatrix}$*, the ==dissociation constant equals the substrate concentration== *$\begin{pmatrix} K_{m}=[S] \end{pmatrix}$*
> ````col
> ```col-md
> ![Pasted image 20240602051324.png](/img/user/12th%20Term/Biochemical%20Engineering/Attachments/Pasted%20image%2020240602051324.png)
> ###### *Michaelis-Menten plot*
> ```
> ```col-md
> $\begin{matrix} \begin{bmatrix}\hline  \begin{matrix} K_{m}=\dfrac{k_{-1}+k_{2}}{k_{1}} \end{matrix}  \\ \hline \end{bmatrix}  \\  \\  \begin{matrix}  \nu= \frac{1}{2} \nu_{\text{max}} \\  \\ K_{m}=[S] \end{matrix} \end{matrix}$
> ```

`````
``````
****
- $k_{\text{cat}}$ is the **[[turnover numbers|turnover number]] of an enzyme**
	- It is the quantitative measure of how useful an [[enzymes|enzyme]] is in a reaction
	- Number of ==substrate molecules== converted to ==product== *in a given time* 
		- On a *single-enzyme molecule* as the enzyme is ***saturated***  with substrate
- $K_{M}$ is the **substrate concentration at which the enzyme reaches half its maximum reaction rate**
	- Also known as the ==affinity constant==
	- It is an *intensive property*
	- It is a function of ==rate parameters== and is expected to ***change*** with ==[[temperature]]== or ==[[pH and pOH|pH]]== 
- $[E_{0}]$ is the **initial enzyme concentration**
````col
```col-md
- As per [[Briggs-Haldane Kinetics]], it is a *constant* value 
- It is expressed in terms of $\textcolor{#D8A78D}{\text{M}}$ or $\textcolor{#D8A78D}{\frac{\text{g}}{\text{L}}}$ 

```
```col-md
flexGrow=2
===
- When the enzyme is part of a ***crude preparation***, it is expressed in terms of $\textcolor{#D8A78D}{\text{katal}}$ or $\textcolor{#D8A78D}{\text{U or IU}}$ *(enzyme unit)*
> - **Enzyme unit:** ==Amount of enzyme== required to catalyze ==one micromole of substrate to product per minute==
> - **Katal:** ==Amount of enzyme== required to catalyze ==one mole of substrate to product per minute==
> - *Under specific, usually optimal, conditions*

```
````
- $\nu_{\text{max}}$ is the **maximum rate of reaction** *(maximum velocity)*
````col
```col-md
$\nu_{\text{max}}=k_{\text{cat}}-[E_{0}]$


```
```col-md
flexGrow=2
===
- It is an *experimentally* ***determined*** value: 
> - A function of the ==turnover number== and ==initial enzyme concentration==

```
````
- The **catalytic efficiency** is the ratio of the ==turnover number== over the ==affinity constant==
````col
```col-md
$\begin{matrix} \begin{matrix} \text{Catalytic }\text{Efficiency} \end{matrix}=\dfrac{k_{\text{cat}}}{K_{m}} \end{matrix}$

```
```col-md
flexGrow=2
===
- Substrates with ==higher catalytic efficiency== *$(<K_{m})$* are favorable
> - *Lower ==$K_{m}$ [[Turnover Numbers|value]]==, higher enzyme affinity*


```
````
****
## Active Sites
- The more enzymes available, the more sites for the reaction to be catalyzed
	- *The higher the ==concentration of substrate==, the higher ==rate of reaction== [[#Example Solving for Parameters using Lineweaver-Burk Plot|(see example)]]* 
****
## Allostery
- **[[Allostery|Allostery]]** occurs when **enzymes** have ==two or more active sites== 
	- The normal [[Michaelis-Menten Kinetics|Michaelis-Menten kinetics]] does not account for allosteric binding 
	- **Allosteric binding** may be occur alongside [[enzyme inhibition]] 
- These extra **allosteric sites** allow for inhibition ==without blocking the active site for the substrate==
**** 
## Enzyme Inhibition [[Enzyme Inhibition|(↗️)]]
![Pasted image 20240619075545.png](/img/user/12th%20Term/Biochemical%20Engineering/Attachments/Pasted%20image%2020240619075545.png)

| Inhibitor                     | Where They Bind | Effect on $K_{m}$ | Effect on $\nu_{\text{max}}$ | Binding Allosterically? | Can added substrate overcome inhibition? |
| :---------------------------- | --------------- | ----------------- | ---------------------------- | ----------------------- | ---------------------------------------- |
| [[Competitive Inhibition]]    | E               | Increase          | No Change                    | No                      | Yes                                      |
| [[Noncompetitive Inhibition]] | E and ES        | No Change         | Decrease                     | Yes                     | No                                       |
| [[Uncompetitive Inhibition]]  | ES              | Decrease          | Decrease                     | Yes                     | No                                       |
| [[Substrate Inhibition]]      | ES              | Increase          | Decrease                     |                         | No                                       |
- Sometimes, inhibition of an enzyme's active site is necessary for a proposed reaction mechanism to work properly 
- Binding of [[enzyme inhibitors]] at *allosteric sites* ***warps*** the other ==active site==, making the substrate unable to ***fit*** the way it used to
- Measurements of the rates of catalysis at different concentrations of substrate and inhibitor can serve to distinguish the four types of reversible inhibition
****
## Diffusional Effects
- When an enzyme is [[Enzyme Immobilization|immobilized]], [[Diffusive Mass Transfer Effects|mass transfer effects]] need to be considered
****
## Applications
- [[Cell Growth Kinetics|Batch cell growth kinetics]], or the **rate of formation inside [[Reactors, Design Equations, and Conversion#Batch Reactor|batch reactors]]**, is governed by the [[Michaelis-Menten Equation]]
	- ? How is it different?
****
## Problems 
##### Example: Solving for Parameters using Lineweaver-Burk Plot 
````col
```col-md
> [!question] 
> - The following data have been obtained fo two different initial enzyme concentrations for an enzyme-catalyzed reaction 
>   
>   
> | $[S] \space  \begin{pmatrix} \frac{\text{g}}{L} \end{pmatrix}$ |$\begin{matrix} \underset{\begin{bmatrix}\hline  \begin{matrix} [E_{0}]=0.015 \frac{\text{g}}{\text{L}} \end{matrix}  \\ \hline \end{bmatrix}}{\underline{\nu \space \begin{pmatrix} \frac{\text{g}}{\text{L}\cdot \text{min}} \end{pmatrix}}}  \end{matrix}$| $\begin{matrix} \underset{\begin{bmatrix}\hline  \begin{matrix} [E_{0}]=0.00875 \frac{\text{g}}{\text{L}} \end{matrix}  \\ \hline \end{bmatrix}}{\underline{\nu \space \begin{pmatrix} \frac{\text{g}}{\text{L}\cdot \text{min}} \end{pmatrix}}}  \end{matrix}$ | 
> | :---: | :---: | :---: |
> |20.0|1.14|0.67|
> |10.0|0.87|0.51|
> |6.7|0.70|0.41|
> |5.0|0.59|0.34|
> |4.0|0.50|0.29|
> |3.3|0.44| |
> |2.9|0.39| |
> |2.5|0.35| |

> [!abstract] Required
> 1) ###### Find $K_{m}$
> 2) ###### Find $\nu_{\text{max}}$ for $[E_{0}]=0.015 \frac{\text{g}}{\text{L}}$
> 3) ###### Find $\nu_{\text{max}}$ for $[E_{0}]=0.00875 \frac{\text{g}}{\text{L}}$
> 4) ###### Find $k_{2}$


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



# Lineweaver-Burk Plots
______
![Pasted image 20240607164805.png](/img/user/12th%20Term/Biochemical%20Engineering/Attachments/Pasted%20image%2020240607164805.png)
$\begin{matrix} \fbox{Lineweaver-Burk Plot} \\ \nu=\dfrac{\nu_{\text{max}}[S]}{K_{m}+[S]} \\  \\ \dfrac{1}{\nu}=\dfrac{K_{m}+[S]}{\nu_{\text{max}}[S]} \\  \\ \dfrac{1}{\nu}=\dfrac{K_{m}}{\nu_{\text{max}}[S]}+\dfrac{[S]}{\nu_{\text{max}}[S]} \\  \\  \begin{bmatrix}\hline  \begin{matrix} \begin{matrix} \dfrac{1}{\nu} & = & \dfrac{K_{m}}{\nu_{\text{max}}[S]} & + & \dfrac{1}{\nu_{\text{max}}} \end{matrix} \end{matrix}  \\ \hline \end{bmatrix} \\  \\ \begin{matrix} y & = & mx & + & b  \end{matrix} \end{matrix}$
- A **Lineweaver-Burk plot** gives good estimates on $\nu_{\text{max}}$, but not necessarily on $K_{m}$ 
	- Also known as a ==double-reciprocal plot== *(referencing 1/v and 1/vmax)* 
	- The most common plot
	- Easy to interpret visually
	- & Can be *misleading* at ==lower concentrations== due to magnification of errors
- $y= \dfrac{1}{\nu}$
- $x= \dfrac{1}{[S]}$ 
- $m=\dfrac{K_{m}}{\nu_{\text{max}}}$
- $b=\dfrac{1}{\nu_{\text{max}}}$ 
****

</div></div>
 


```
```col-md
flexGrow=1.5
===
- For this problem, we can use a [[Lineweaver-Burk Plots]] *(also known as a double reciprocal plot)* to find our parameters from the given data
> $\begin{matrix} \dfrac{1}{\nu}=\dfrac{K_{m}}{\nu_{\text{max}}[S]}+\dfrac{1}{\nu_{\text{max}}} \end{matrix}$
- We complete this table and generate a graph for the two initial enzyme concentrations
> 
> | $[S] \space  \begin{pmatrix} \frac{\text{g}}{L} \end{pmatrix}$ | $\begin{matrix} \underset{\begin{bmatrix}\hline  \begin{matrix} [E_{0}]=0.015 \frac{\text{g}}{\text{L}} \end{matrix}  \\ \hline \end{bmatrix}}{\underline{\nu \space \begin{pmatrix} \frac{\text{g}}{\text{L}\cdot \text{min}} \end{pmatrix}}}  \end{matrix}$ | $\dfrac{1}{[S]}$ | $\dfrac{1}{\nu}$ |
> | :------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------: | ---------------- |
> |                              20.0                              |                                                                                                                             1.14                                                                                                                              |      0.050       | 0.877            |
> |                              10.0                              |                                                                                                                             0.87                                                                                                                              |      0.100       | 1.149            |
> |                              6.7                               |                                                                                                                             0.70                                                                                                                              |      0.149       | 1.429            |
> |                              5.0                               |                                                                                                                             0.59                                                                                                                              |      0.200       | 1.695            |
> |                              4.0                               |                                                                                                                             0.50                                                                                                                              |      0.250       | 2.000            |
> |                              3.3                               |                                                                                                                             0.44                                                                                                                              |      0.303       | 2.273            |
> |                              2.9                               |                                                                                                                             0.39                                                                                                                              |      0.345       | 2.564            |
> |                              2.5                               |                                                                                                                             0.35                                                                                                                              |      0.400       | 2.857            |
> 
> ![Pasted image 20240604173810.png](/img/user/12th%20Term/Biochemical%20Engineering/Attachments/Pasted%20image%2020240604173810.png)
> $\begin{matrix}\begin{bmatrix}\hline  \begin{matrix} [E_{0}]=0.015 \frac{\text{g}}{\text{L}} \end{matrix}  \\ \hline \end{bmatrix} \\  y=5.6772x+0.5802 \\  \\  \begin{matrix} \hline \space \fbox{1}\space  & \begin{matrix} \underset{\text{From calculator}}{\underline{\text{y-int}=0.5802}} =\dfrac{1}{\nu_{\text{max}}} \\  \\ \nu_{\text{max}}=\dfrac{1}{0.5802} \\  \\ \nu_{\text{max}}=1.7235 \frac{\text{g}}{\text{L}} \end{matrix} \\  \\ \hline \space \fbox{2}\space  & \begin{matrix}  \underset{\text{From calculator}}{\underline{m=5.6772}} =\dfrac{K_{m}}{\nu_{\text{max}}} \\  \\ K_{m}=(5.6772)\begin{pmatrix}  1.7235 \frac{\text{g}}{\text{L}} \end{pmatrix} \\  \\ K_{m}= 9.7846 \end{matrix}  \\  \hline \end{matrix} \end{matrix}$
> 
> ****
> | $[S] \space  \begin{pmatrix} \frac{\text{g}}{L} \end{pmatrix}$ | $\begin{matrix} \underset{\begin{bmatrix}\hline  \begin{matrix} [E_{0}]=0.00875 \frac{\text{g}}{\text{L}} \end{matrix}  \\ \hline \end{bmatrix}}{\underline{\nu \space \begin{pmatrix} \frac{\text{g}}{\text{L}\cdot \text{min}} \end{pmatrix}}}  \end{matrix}$ | $\dfrac{1}{[S]}$ | $\dfrac{1}{\nu}$ |
> | :------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------: | ---------------- |
> |                              20.0                              |                                                                                                                              0.67                                                                                                                               |      0.050       | 1.493            |
> |                              10.0                              |                                                                                                                              0.51                                                                                                                               |      0.100       | 1.961            |
> |                              6.7                               |                                                                                                                              0.41                                                                                                                               |      0.149       | 2.439            |
> |                              5.0                               |                                                                                                                              0.34                                                                                                                               |      0.200       | 2.941            |
> |                              4.0                               |                                                                                                                              0.29                                                                                                                               |      0.250       | 3.448            |
> 
> ![Pasted image 20240604173828.png](/img/user/12th%20Term/Biochemical%20Engineering/Attachments/Pasted%20image%2020240604173828.png)
> $\begin{matrix}\begin{bmatrix}\hline  \begin{matrix} [E_{0}]=0.00875 \frac{\text{g}}{\text{L}} \end{matrix}  \\ \hline \end{bmatrix} \\  y=9.7841x+0.9902 \\  \\  \begin{matrix} \hline \space \fbox{1}\space  & \begin{matrix} \underset{\text{From calculator}}{\underline{\text{y-int}=0.9902}} =\dfrac{1}{\nu_{\text{max}}} \\  \\ \nu_{\text{max}}=\dfrac{1}{0.9902} \\  \\ \nu_{\text{max}}=1.0099 \frac{\text{g}}{\text{L}} \end{matrix} \\  \\ \hline \space \fbox{2}\space  & \begin{matrix}  \underset{\text{From calculator}}{\underline{m=9.7841}} =\dfrac{K_{m}}{\nu_{\text{max}}} \\  \\ K_{m}=(9.7841)\begin{pmatrix}  1.0099 \frac{\text{g}}{\text{L}} \end{pmatrix} \\  \\ K_{m}= 9.8810 \end{matrix}  \\  \hline \end{matrix} \end{matrix}$
- Comparison plot
> ![Pasted image 20240604173409.png](/img/user/12th%20Term/Biochemical%20Engineering/Attachments/Pasted%20image%2020240604173409.png)
> - The two $K_{m}$ values are not exactly the same
> > $\begin{matrix} K_{m,0.015}=9.7846 \\ K_{m,0.00875}=9.8810 \end{matrix}$
> - The higher the concentration of substrate [S], the higher the rate of reaction $\nu$

```
````
****
````col
```col-md
> [!question] 
> ###### Determine the Michaelis-Menten Parameters $\nu_{\text{max}}$ and $K_{M}$ for the given reaction
> - The rate of reaction is given as a function of urea concentration
> 
> |$C_{\text{urea}} \space \begin{pmatrix} \frac{\text{kmol}}{\text{m}^{3}} \end{pmatrix}$| $-r_{\text{urea}}\space  \begin{pmatrix} \frac{\text{kmol}}{\text{m}^{2} \cdot \text{s}} \end{pmatrix}$ |
> | :---: | :---: |
> |0.2|1.08|
> |0.02|0.55|
> |0.01|0.38|
> |0.005|0.2|
> |0.002|0.09|

```
```col-md
flexGrow=2
===
###### Reaction:
$\begin{matrix} \text{Urea}+\text{Urease} & \ce{<=>[\ce{k_{1}}][\ce{k_{2}}]} & [\text{Urea}\cdot \text{Urease}]^{\star} &   \ce{<=>[\ce{k_{2}}][\ce{+\text{H}_{2}\text{O}}]} & \text{2NH}_{3}+\text{CO}_{2}+\text{Urease} \\  \\ \text{S}+\text{E} & \rightleftharpoons  & \text{E}\cdot \text{S}  & \xrightarrow{+\text{H}_{2}\text{O}} & \text{P}+\text{E} \end{matrix}$

****
##### Lineweaver-Burk:


##### Eadie-Hofstee:


##### Hanes-Woolf:


```
````
****