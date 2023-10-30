

<hr>

Book Name : 
Date Started : 30-10-2023
Date Finished : 30-10-2023

<hr>

### <span  style = "color:Plum">Suggested Links </span>
+ 

<hr>


### <span  style = "color:dodgerblue">Questions to track </span>
+ 


<hr>

### <span  style = "color:Coral">Chapters Section </span>
+ 

<hr>



## <span  style = "color:PaleGreen">Properties of White Dwarf</span>
![[Screenshot 2023-10-30 at 11.03.58 AM.png]]
$$\Downarrow$$

###### <span  style = "color:Orchid">Mass Radius Relationship</span>
We can again use the scaling relations for the hydrostatic equation mass continuity. 

Hydrostatic Equilibrium $\Longrightarrow$ $$\frac{dP}{dr} \approx \frac{-GM \rho (r)}{r^2}$$
or 
$$P \sim \frac{GM \rho}{r}$$
We also know , 
$$\rho \sim \frac{M}{r^{3}} \Longrightarrow P \sim \frac{GM^2}{r^4}$$
![[Screenshot 2023-10-30 at 11.16.10 AM.png]]

$$\Downarrow$$
This gives the mass radius relationship as 
$$\tag{3} r \sim \frac{b}{G} M^{\frac{-1}{3}}$$
$$\Downarrow$$
![[Screenshot 2023-10-30 at 11.18.06 AM.png]]

$$\Downarrow$$

This is an order of estimate from the stellar structure equation. 
However, if we solve full stellar structure equations then the radius of white dwarf would be 
$$r_{wd} = 2.3 \times 10^{9} em \Bigg(\frac{Z}{A}\Bigg)^{\frac{5}{3}} \Bigg(\frac{M}{M_{\bigodot}}\Bigg)^{\frac{-1}{3}}$$
and for $\frac{Z}{A} = 0.5$ and $M = 1M_{\bigodot}$ , we get $r = 4000 \text{ km}$

#### <span  style = "color:Tomato">The Chandrashekhar Mass</span>
As we see from previous equation that larger the mass of white dwarf, the smaller the radius of white dwarf becomes  $\Longrightarrow$ larger densities and therefore larger momenta to which the electrons are pushed

When the electron velocities become comparable to the speed of light, we can no longer assume $v = \frac{p}{m}$, instead the velocity $v$  which dictates the rate at which collisions transfer momentum to the container wall, approaches to $c$.

In this ultra relativistic limit, we can replace $v$ with $c$ and the equation of the state then becomes 
$$P_{e}= \frac{1}{3} \int_{0}^{P_{f}} \frac{8 \pi}{h^{3}}\;p^2\;p\;c\;dp$$
$$ = \frac{8 \pi c}{3h^{3}} \frac{p_{f}^4}{4}$$
and also we have , recalling 
$$P = \frac{1}{3} \int_{0}^{\infty} n(p)\;p\;v\;dp$$
Hence, for ultra-relativistic degenerate spin $\frac{-1}{2}$ fermions gas, the equation of state changes to 
$$\tag{4} P_{e}= \Bigg( \frac{3}{8 \pi} \Bigg)^{1/3}{\frac{hc}{4m_{p}^{4/3}}}\Bigg( {\frac{Z}{A}}\Bigg)^{4/3}\rho^{4/3}$$

![[Screenshot 2023-10-30 at 11.55.31 AM.png]]

$\bbox[12px, border: 4px solid cyan] {\text{Things to Note}}$
The pressure equation does not depend on the mas of electron anymore like the non-relativistic case. What does that mean ?? 
This means that this pressure equation holds for any degenerate $\frac{1}{2}$ spin particles in the ultra-relativistic regime behaves same. 

Also, for ultra-relativistic particles, the rest mass is a negligible fraction of  the total energy $E = (m^{2}c^{4}+ p^{2}c^{2})^\frac{1}{2}$ and hence $p = E/c$

As previous calculation showed that if white dwarf mass increases, the electron gradually moves from non-relativistic regime to ultra-relativistic regime with power law index of $\rho$ gradually decreasing  from $\frac{5}{3} \text{ to } \frac{4}{3}$

<span  style = "color:dodgerblue">As we go to the higher masses and the density increases due to the shrinking radius, the pressure support will rise more and more slowly, so that the radius shrinks even more sharply with increasing mass.</span>

![[Screenshot 2023-10-30 at 12.37.44 PM.png]]

$$\Downarrow$$

$$P \sim \rho^{\frac{4 + \epsilon}{3}}$$
$$\Downarrow$$
![[Screenshot 2023-10-30 at 12.41.41 PM.png]]
$$\Downarrow$$
In other words, for the mass that is high enough for electrons become ultra-relativistic, the electron pressure becomes incapable of supporting the star against gravity and the radius shrinks  to zero and the density becomes infinite , unless some other kind of pressure sets in. 
$$\Downarrow$$
We will see at high enough density, the degeneracy pressure due to protons and neutrons  begin to operate and it can sometimes stop the full gravitational collapse producing objects called neutrons star. 
$$\Downarrow$$
This also implies  that there will be a mass limit upto which the star can be supported by degenerate electrons pressure. This mass is called ==Chandrashekhar Mass.==

#### <span  style = "color:Tomato">Estimation of Chandrashekhar Mass</span>
Recall the stellar structure model and Virial theorem 
$$\tag{1} \bar{P}V = \frac{-1}{3}E_{gr}$$
In this equation, the pressure will be balanced by the self-gravity of the star. 
Now replacing, the pressure due to ultra relativistic electrons derive before we can write
![[Screenshot 2023-10-30 at 12.48.50 PM.png]]

$$\Downarrow$$
This is again from simplified solution from Virial Theorem. If one solves for full hydrostatic equation, then we will have 
$$\tag{Eqn. of Chandrashekar Mass}\bbox[8px, border: 2px solid red] {M \approx 0.21 \bigg(\frac{Z}{A}\bigg)^{2}\bigg(\frac{hc}{Gm_{p}^2} \bigg)^{3/2}m_p}$$

$$\Downarrow$$

![[Screenshot 2023-10-30 at 12.54.22 PM.png]]

$\bbox[8px, border: 2px solid dodgerblue] {\text{To add to context}}$
$\alpha_G$ represents the strength of gravitational interaction and it is the gravitational analogue of the fine structure constant. 
$$\alpha_{em} \sim \frac{e^{2}}{hc} \approx \frac{1}{137}$$
which measures the strength of EM radiation. 

$$\Downarrow$$

Hence, we can calculate maximum mass that can be supported by electron degeneracy pressure
$$M_{ch} = 0.21 \times(0.5)^{2}\times(10^{-39})^{\frac{3}{2}}\times1.7\times 10^{-24}$$
$$ = 1.4 M_{\bigodot}$$
And this is infact, observationally verified and no white dwarf with mass higher than $M_{ch}$ have been found. 
Apparently there is a lower bound of $0.25M_{\bigodot}$ for white dwarf. As a finite age of universe, $1.4 \times10^{10}$ years , stars with initial mass of $0.8M_{\bigodot}$ have not had enough time to go through their main sequence life time even if they form early in the history of universe. 
