As in the last class, we discussed the electromagnetic wave which is coming from the astrophysical source, contains a lot of information about the object. Hence, understanding how the radiation actually travels through the interstellar medium and how it gets detected is a very important question. In that respect, we need to understand the interaction of radiation with matter.

Such an interaction of radiation in planetary atmosphere or when the radiation coming through the stellar atmosphere becomes topic of interest.

Interaction of matter with radiation can be studied into levels 
+ Macroscopic 
	+ In macroscopic level, we introduce suitably defined a mission and absorption coefficient and try to solve basic equations assuming these coefficients to be given. This subject is known as <b style = "color:RebeccaPurple">radiative transfer</b>
+ Microscopic
	+ At the microscopic level, we try to calculate the emission and absorption coefficient from the fundamental physics of the atom.

For astrophysics, we always are interested in the macroscopic scale. For micro physics, we need to concentrate on atomic and molecular physics.

<br>

### <span  style = "color:AquaMarine">Theory of Radiative Transfer</span>

#### <span  style = "color:Tomato">Radiation Field</span>
Let us first consider how we can provide the mathematical description of radiation at a given point in space. It is particularly easy to give a mathematical description of a black body radiation, which is isotropic  and homogeneous in a container.
Probably all of you are familiar with blackbody radiation. 

#### <span  style = "color:Tomato">Blackbody Radiation</span>
When a body is heated, it emits radiation because of the temperature. The radiation coming from the heating of material is called thermal radiation. This thermal radiation which comes to equilibrium with the matter is called black body radiation. 

This one is very well explained by Kirchhoff. He considered a cavity bed with radiation. The walls can be considered as a heat bath for radiation. The walls emit and absorb electromagnetic waves. In equilibrium , the walls and radiation must have the same temperature.
Therefore, when a body does not reflect/re-emit any radiation in any way of land, it is called a blackbody. Radiation from the blackbody is called blackbody radiation. 

One of the most famous result in the theory of blackbody radiation is Planck's law, which specified the energy density $U_{\nu}$ in the frequency range $\nu$ and $\nu + d \nu$ of blackbody radiation as given below 
$$ \tag{1} 
U_{\nu} \  d \nu = \frac{ 8 \pi h}{c^{3}} \left( \frac{\nu^{3}d \nu }{\exp\left(\frac{h \nu}{k_{B}t}\right)- 1 }\right) $$

This law more or less gives us complete information about the blackbody radiation at a given temperature, T. <u style = "color:Sienna">One important thing to notice is that blackbody radiation coming from a source is isotropic and it does not provide any directional information. </u>

Remember for radiation, from any arbitrary source is not always isotropic. Simple example is when we have sunlight streaming into a room, we have a non-isotropic situation involving the flow of radiation from a preferred direction. There are four, we require a more complicated prescription to describe such a radiation mathematically

##### <span  style = "color:SpringGreen"> Macroscopic description of a propagation of radiation</span>

When the scale of a system greatly exceeds the wavelength of radiation(e.g. light shining through a keyhole), we can consider radiation to travel in a straight line (called rays) in free space or homogeneous media. One of the most important concept (primitive) is that of energy flux. 

Consider an area $dA$ exposed to radiation for time $dt$, the amount of energy passing through the surface $dA$ and $dt$ should be proportional to $dA \ dt$, and we can write $E = F\ dA\ dt$ where $F$ is the energy flux $(erg/s/cm^2)$
> Note that $F$ can depend on the orientation of the element. 

<br>

#### <span  style = "color:Tomato">Flux from Isotropic square law - The Inverse square law </span> 
Isotropic source $\longrightarrow$  system containing isolated spherical star 

We put two imaginary surfaces $S_1$ and $S_2$ with $r_1$ and $r_2$ distance from the star (here sun)
![[Screenshot 2023-08-11 at 3.45.29 AM.png]]
As no energy is being lost while passing through this two area, the total energy passing through them would be same i.e. 
$$F(r_{1)}\cdot 4 \pi r_{1}^{2}= F(r) \cdot 4 \pi r^{2} $$
$$F(r) = \frac{F(r_{1}) 4 \pi r_{1}^{2}}{{4 \pi r^{2}}}\ $$
$$\tag{inverse square} \approx \frac{1}{r^2}$$

This is another statement for conservation of energy. 

##### <span  style = "color:SpringGreen">Specific Intensity</span>
![[Screenshot 2023-08-11 at 12.27.55 PM 1.png|350]]
In the same way as previous let us consider energy $dE_{\nu}\ d \nu$ is passing through the area $dA$ from a solid angle $d \Omega$ in the time $dt$.  It would be very straight forward to understand that energy $dE_{\nu}\ d \nu$ (in frequency range $\nu$ and $\nu + d\nu$) would propagated to the projected effective area. 

$$\tag{2} dE_{\nu}\ d \nu = I_{\nu} (r,t,\hat{n}) dA \ \cos \theta dt\ d\Omega\ d\nu$$
where $\hat{n}$ is unit vector from which the radiation is coming. If $I_{\nu}(\vec{r}, t, \hat{n})$ specified for all directions at every point of a region at a time, we will have prescription of the radiation field in that region at that time. For all of our next studies, we shall restrict ourselves only to radiation which are independent of time.

##### <span  style = "color:SpringGreen">Why we define specific intensity ? </span>
###### <span  style = "color:Orchid">Radiation Flux</span>
The beauty is if we know specific intensity at a point in space, all other important quantity like radiation flux, energy density and radiation pressure can be calculated very easily.

As we defined earlier, radiation flux $=$ total energy of radiation flux coming from all direction at a point per unit time and unit area. Therefore from Eq. 2, we have
$$F_{\nu} = \int_{\text{solid angle}}^{} \frac{\text{amount of energy}}{dA\ dt} = \int I_{\nu} \cos \theta \ d\Omega$$
Above quantity is the flux associated with the frequency $\nu$.

Total radiation flux would be $$F = \int F_{\nu}\  d\nu$$

<br>

##### <span  style = "color:SpringGreen">Energy Density</span>
![[Screenshot 2023-08-11 at 1.05.45 PM.png|300]]
<figure>
<center>
<figcaption align = "center">
<b>Fig 3.1</b>
</figcaption>
</center>
</figure>

Amount of energy passing through this area is 
$$dE_{\nu}  = I_{\nu}\  dA \  dt\ d\Omega\ d\nu$$

In time $dt$ this radiation will travel a distance $c \ dt$. 

Therefore, , in time $dt$ the radiation will fill a cylinder of axial length $c\ dt$ with base $dA$ (for inclination $\theta, dA\cos\theta$)

$\therefore \text{Energy Density} = \frac{d E_{\nu}}{dA \ cdt} = \frac{I_{\nu}}{c} d\Omega$

If the ray's coming from all directions, 
$$U_{\nu} = \int \frac{I_{\nu}}{c} d\Omega$$

Now remember for blackbody radiation, it is isotropic
$$\therefore U_{\nu} = 4 \pi \frac{I_{\nu}}{c}$$
and for blackbody, we define , 
$$ U_{\nu} =  \frac{4 \pi}{c} B_{\nu}(T)$$
or, Specific intensity of blackbody radiation
$$B_{\nu}(T) = \frac{ 2 h \nu^{3}d \nu}{c^{2}} \left( \frac{1 }{\exp\left(\frac{h \nu}{k_{B}t}\right)- 1 }\right)$$
Units will be $erg\ s^{-1}\ cm^{-2}\ steradian^{-1}\ Hz^{-1}$

##### <span  style = "color:SpringGreen">Radiation Flux for black body Radiation</span>
 << Refer to the Fig. 3.1 for schematic >>
$$F_{\nu} = \int_{\theta = 0}^{\theta = \pi} I_{\nu} \cos \theta d\Omega$$
here we are assuming only half spheres. So, 
$$= 2 \pi \int I_{\nu} \cos \theta \sin \theta d\theta$$
$$= \frac{I_{\nu}}{2} 2 \pi \int \sin 2 \theta d\theta$$
$$= \frac{1}{2} \left[ {\cos 2 \theta} \right]^{\pi/2}$$
$$= \frac{1}{2} I_{\nu} 2 \pi = \pi I_{\nu} = \frac{1}{2} \left[ {-\cos \pi + \cos 0} \right] \equiv 1$$

Therefore, the flux coming from the outer space over half a sphere can be written as
$$\tag{3} F_{\nu} = \pi I_{\nu} = \pi B_{\nu}(T)$$
CGS Unit will be $erg \ cm^{-2} s^{-1}$
This is the flux actually we observe from the stars or any astronomical body. Also, the total power radiated by a spherical, isotropically emitting star of radius $R_*$ is usually called <u>luminosity</u> and we can write it as , 
$$L_{\nu} = F_{\nu} (R_{*})4\pi R_{*}^2$$

Note that the $F_{\nu}(R_*)$ is the flux at the start if we want to observe the flux at distance $d$ from the star. Then that will be 
$$\tag{No Energy destroyed}F_{\nu}(d) = \frac{L_{\nu}}{4 \pi R^2}$$
$$= F_{\nu}(R_*)\frac{R_{*}^2}{d_{*}^2}$$
It is often useful to consider the above quantities integrated over all photon frequencies and can be written as

$u = \int_{0}^{\infty} u_{\nu} d\nu$ , $I = \int_{0}^{\infty} I_{\nu} d\nu$, $F = \int_{0}^{\infty} F_{\nu} d\nu$, $L = \int_{0}^{\infty} L_{\nu} d\nu$

<br>

#### <span  style = "color:Tomato">Stefan - Boltzmann Law</span>
 If you perform the integration over $\nu$ for 
 $$\tag{Stefan-Boltzmann law}u = \int_{0}^{\infty} u_{\nu} d\nu \approx aT^4$$
Similarly, if you integrate our flux, 
$$F = \int_{0}^{\infty} F_{\nu} d\nu = \frac{c}{4} aT^{4}= \sigma T^{4}$$
where 
+ $a = \frac{8 \pi ^{5} k^{4}}{15 c^{3}h^{3}}= 7.6 \times 10^{-15} \ erg \ cm^{-3} \ K^{-4}$
+ $\sigma = \frac{c}{4}a = 5.4 \times 10^{-5} \ erg \ s^{-1}\ cm^{-2}\ K^{-4}$


##### <span  style = "color:SpringGreen"> Transforming energy density, radiation flux and luminosity per photon frequency to per photon wavelength</span>
To make this transformation, we recall that the energy in an interval must be same, 
$$\therefore B_{\lambda} d{\lambda} = B_{\nu} d{\nu}$$
$$\Longrightarrow B_{\nu} = B_{\nu} \left| \frac{d \nu}{d {\lambda}} \right| = B_{\nu} \frac{c}{{\lambda}^2}$$
$$\Longrightarrow \frac{2 hc^{2}}{\lambda^{5}} \left( \frac{1 }{\exp\left(\frac{h c}{\lambda kt}\right)- 1 }\right) $$

Here the unit of specified intensity is 
$$B_{\lambda} \sim \ erg \ cm^{-2}\ s^{-1} \ cm^{-1}\ steradian^{-1}$$
Note that we use two $cm^{-2}$ and $cm^{-1}$ because one is for area and the another one is for wavelength; do not compound it and confuse it for volume. 

As we discussed in the class while discussing scaling units that for wavelength we use sometimes non-CGS unit. And for astrophysics, we mostly use and strong. In that specific intensity and brightness has unit $(1 \overset{\circ}{\mathbb{A}} = 10^{-8} cm )$
$$erg \ cm^{-2}\ s^{-1} \ \overset{\circ}{\mathbb{A}}^{-1}\ steradian^{-1}$$

The wavelength where the blackbody spectrum will peak can be found by taking its derivatives and equating it to 0 such that
$$\frac{d B_{\lambda}}{d {\lambda}} = 0  \ \ \ \ \ \ \ \& \ \ \ \ \ \frac{d B_{\nu}}{d {\nu}} = 0$$

which gives us further, the two forms of Wien's Law
1. $\lambda_{max} T = 0.29 \text{ cm K}$
2. $h \nu_{max} = 2.8 \text{ K T}$

For example, the nearest star, the sun, which radiates approximately like a black body at $T = 5800 K$ has a wavelength green light in the middle of visual regime. 
> Fun Fact
> The eyesight of most animal on earth apparently evolved around wavelengths where the sun estimates most of the energy

<br>

#### <span  style = "color:Tomato">Rayleigh Jean Side</span>
We have observed blackbody spectral distribution for a variety of temperature. A few features are important to note 
+ All the function we described above $(u_{\nu}, B_{\nu}, . . )$ are uniquely determined by a single parameter $T$
+ Far away from this peak frequency Plank's blackbody spectrum assume two simple forms,
	For frequency we will take equation, 
	$$B_{\nu}(T) = \frac{ 2 h \nu^{3}d \nu}{c^{2}} \left( \frac{1 }{\exp\left(\frac{h \nu}{k_{B}t}\right)- 1 }\right)$$
For,  $h\nu << kT$ i.e. energy much lower than peak, we have 
$$B_{\nu} \approx \frac{ 2 \nu^{2}}{c^{2}} kT$$
Above equation is called <span  style = "color:Sienna">Rayleigh - Jean side of Spectrum </span>


<br>

In a wavelength regime, 
$$B_{\lambda} \approx \frac{ 2 hc^{2}}{\lambda^{5}} \left( \frac{1 }{\exp\left(\frac{hc}{\lambda kt}\right)- 1 }\right) $$
$$ \approx \frac{ 2 hc^{2}}{\lambda^{5}} \frac{ \lambda kT}{hc}$$
$$\approx \frac{ 2 c}{\lambda^{4}} kT$$

Similarly for photon energy, $h\nu >> kT$ i.e. higher wavelength
$$B_{\nu}\approx \exp\left(\frac{h \nu}{ kt}\right) ^{-1}$$
$$B_{\lambda}\sim \exp\left(\frac{h c}{ \lambda kt}\right) ^{-1}$$
This is called <span  style = "color:Sienna">Wien's Tail of Distribution</span>

<br>

##### <span  style = "color:SpringGreen">Some properties of radiation pressure due to radiation</span>
When radiation propagate and falls on the surface, the pressure of the radiation over the surface is given by the flux moment perpendicular to that surface. The momentum associated with energy $dE_{\nu}$ is $\frac{dE_{\nu}}{c}$ and  normal to the surface  is $\frac{dE_{\nu}}{c} \cos \theta$

Now the momentum flux will be
$$\tag{refer to Fig 3.1} \frac{dE_{\nu} \cos \theta}{c\ dA \ dt} $$
$$= \frac{I_{\nu} dA \cos \theta \ dt \ d\Omega}{c\ dA \ dt}$$
$$= \frac{I_{\nu} \cos ^{2} \theta d\Omega}{c}$$

Therefore, the pressure coming from all directions can be calculated overall direction
$$P_{\nu} = \frac{1}{c} \int I_{\nu} \cos ^{2} \theta d \Omega$$
If the radiation field is isotropic, then we get, 
$$P_{\nu} = \frac{4 \pi I_{\nu}}{3c}$$
Remember the relation of  $I_{\nu} , U_{\nu}$from previous calculation and putting it back we get , 
$$P_{\nu} = \frac{1}{3} U_{\nu}$$
This  is the pressure relation for isotropic radiation. 

<br>

#### <span  style = "color:Tomato">Radiative Transfer Equation</span>
So far, we have discussed how we measure radiation from a distant source in terms of specific intensity without assuming how they behave after traveling through space.

As we see, if we go away from the radiation source, the radiation starts to fall off. Therefore, we want to investigate how the specific intensity will vary.

Before we even consider the radiative transfer in a medium, let's find out what happens to a specific intensity if we move along a ray path in an empty space.

Let us consider two area elements separated by a distance $R$ and placed perpendicular to a ray path.
![[Screenshot 2023-08-11 at 7.15.01 PM.png]] 

+ $I_{\nu1}$ is the specific intensity of radiation on the ray path at the area element $dA_1$
+ $I_{\nu2}$ same as at $dA_2$ in the frequency range $\nu$ and $\nu + d\nu$

We again make the use of the fact that energy is conserved. 
$$dE_{1}= I_{\nu1} dA_{1} \ d\Omega_{1}\ dt d \nu_{1}= dE_{2}= I_{\nu2} dA_{2} \ d\Omega_{2}\ dt d \nu_2$$

$$\tag{4} \Longrightarrow I_{\nu1} \ dA_{1} \ d\Omega_{1}\ d \nu_{1}= I_{\nu2} \ dA_{2} \ d\Omega_{2}\ d \nu_2$$

AS we are considering same wavelength, $d \nu_{1}= d \nu_2$, 
For solid angle , $d\Omega_{1}= \frac{dA_2}{R^2}$ where $d\Omega_{2}= \frac{dA_1}{R^2}$

From Eq. 4, 
$$I_{\nu1} = I_{\nu2}$$

$\Longrightarrow$ Specific intensity remains constant along the ray path in free space. Therefore, $I_{\nu} = \text{constant}$
That can be written as 
$$\frac{d I_{\nu}}{ds} = 0$$
 where $ds$ is the differential element along the ray. 
At first instant, this may appear like a surprising result. As we know that intensity  falls off as we move further. <u>Can the specific intensity remain same ?</u> The mystery clears up when we see that specific intensity from a source is essentially its intensity divided by the solid angle it subtends $\Rightarrow$ specific intensity is a measurement of the surface brightness. 

As we go further away from the source, its intensity and angular size fall as $\frac{1}{r^2}$. Hence, the surface brightness which is the ratio on two does not change. 


<hr>

