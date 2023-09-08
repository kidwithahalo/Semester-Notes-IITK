#todo 
+ 

<hr>

Book Name : 
Date Started : 04-09-2023
Date Finished : 

<hr>

### <span  style = "color:Plum">Things to remember</span>
+ Solar Luminosity, $L_{\bigodot} = 3.8 \times10^{33} \text{ ergs}^{-1}$

<hr>


### <span  style = "color:dodgerblue">Questions to track </span>
+ 


<hr>

### <span  style = "color:Coral">Chapters Section </span>
+ [[Stellar Physics#^712c55|Stellar Physics]]
+ [[Stellar Physics#^eb9cfe|Virial Theorem and Hydrostatic Eqb.]]
+ [[Stellar Physics#^c00231|Mass continuity]]
+ [[Stellar Physics#^f3dd5f|Radiative Energy Transport]]

<hr>


## <span  style = "color:PaleGreen">Stellar Physics</span>

^712c55

![[stellar.pdf]]

## <span  style = "color:PaleGreen">HYDROSTATIC EQUILIBRIUM AND THE VIRIAL THEOREM</span>

^eb9cfe

A star is a sphere of gas that is held together by its self gravity, and is balanced against collapse by pressure gradients

> Hydrostatic equilibrium (hydrostatic balance, hydrostasy) is **the condition of a fluid or plastic solid at rest, which occurs when external forces, such as gravity, are balanced by a pressure-gradient force**.

![[Note 08-Sep-2023.pdf]]

## <span  style = "color:PaleGreen">MASS CONTINUITY</span>

^c00231

In reality, it is not just $P(r)$ which varies with the $r$ , but   , $\rho (r)$ and $T(r)$ which have a radial distance dependence from the source. 

So we know, $$dM(r) = \rho(r) 4 \pi r^2dr$$
and this reduces to 
$$\bbox[18px, border: 4px solid yellow] {\frac{dM(r)}{dr} = 4 \pi r^{2}\ \rho(r)}$$

and the  above equation is also known as <span  style = "color:Sienna">equation of mass continuity or equation of mass conservation. </span>
Though notice that it is just a equation for stellar density. 


## <span  style = "color:PaleGreen">RADIATIVE ENERGY TRANSPORT</span>

^f3dd5f

The radial gradient in $P(r)$ that supports a star is produced by a gradient in $ρ(r)$ and $T(r)$. In much of the volume of most stars, $T(r)$ is determined by the rate at which radiative energy flows in and out through every radius, i.e., the luminosity $L(r)$

![[Note 08-Sep-2023 1.pdf]]

Luminosity is now simply the result of anisotropic behaviour in the interior of sun. So far, we have establsihed that interior of  sun behaves pretty much like the black body radiation. 
So , all the energy are radiating isotropically. However, there is a net flow of radiation energy outwards, meaning there is some small anisotropy (a preferred direction), and implying there is a higher energy density, at smaller radii than at larger radii.
<span  style = "color:Orchid"><b> This outflow is basically your Luminosity $L(r)$</b></span>
Now, we have diffusion equation as 
$$\underbrace{\frac{L(r)}{4 \pi r^{2}}}_{\text{Energy Flux}}= - \underbrace{\frac{c\ l}{3}}_{\text{diffusion coefficient}} \overbrace{\frac{du}{dr}}^{\text{Gradient in Energy Density}}$$
This is known as <span  style = "color:yellow">Diffusion equation</span>, describing the outward flow of the energy.

Now, we have 
The energy density is given by $u = a T^4$
Further we can have using implicit chain and substitution
$$\frac{du}{dr} = \frac{du}{dT} \frac{dT}{dr} \ \ \ = \ \ \ 4aT^{3} \frac{dT}{dr}$$

![[Screenshot 2023-09-08 at 2.22.28 PM.png]]

## <span  style = "color:PaleGreen">ENERGY CONSERVATION</span>

![[Note 08-Sep-2023 2.pdf]]


## <span  style = "color:PaleGreen">THE EQUATION OF STATE</span>

![[Note 08-Sep-2023 3.pdf]]


## <span  style = "color:PaleGreen">OPACITY</span>
read from the notes maybe 

## <span  style = "color:PaleGreen">NUCLEAR ENERGY PRODUCTION</span>

From the virial theorem, we saw that the thermal energy resulting from such a contraction(we assume that source of sun's energy is gravitational i.e. that the Sun had radiated until now the potential energy liberated by contracting from infinity to its present radius) is minus one-half the gravitational energy
$$E_{gr} = -2 E_{th}$$
Now therefore the thermal energy the results from contraction, and which Sun can radiate is 
$$E_{th} \sim \frac{1}{2} \frac{G M_{\bigodot}^2}{r_{\bigodot}}$$
and ![[Screenshot 2023-09-08 at 7.35.20 PM.png]]

<< notes from professor shall explain it better >> 