

<hr>

Book Name : 
Date Started : 02-11-2023
Date Finished :  02-11-2023

<hr>

### <span  style = "color:Plum">Suggested Links </span>
+ 

<hr>


### <span  style = "color:dodgerblue">Questions to track </span>
+ 


<hr>

### <span  style = "color:Coral">Accretion Disks </span>
In an accretion disks, the particles move on approximately circular orbits and lose energy and angular momentum due to viscous interaction with particles moving along orbits at adjacent radii. As a result the particles slowly drift to progressively smaller radii until reaching the surface of the star (or the Schwarzschild radius, if the accreted is a black hole).
The heat produced due to the viscous friction radiates away. 

This is a very active field of research and we understand general properties of this object. 

Consider a mass element $dM$ in the accretion disk around a star of mass $M$. To fall from a circular orbit $r + \Delta r$ to an orbit of radius $r$, the mass element should also lose some potential energy. Half of the lost potential energy is necessarily converted into additional $\text{K.E.}$ at the smaller radius with its higher Keplerian velocity and the remaining half will be converted to the heat. 
The gain in the thermal energy of the mass element will be 
$$\tag{gain in the $E_{thermal}$} dE_{th} = \frac{1}{2}\bigg(\frac{GMdM}{r} - \frac{GMdM}{(r + \Delta r)}\bigg)$$
$$ = \frac{1}{2}GM \dot{M}\;  \frac{dr}{r^{2}}= 2 (2 \pi r )dr\; \sigma \; T^4$$
where, 
$\dot{M} = \text{accretion rate through a particluar annulus of the disk}$
$\sigma = \text{Stefan Boltzmann Constant}$

And the factor of 2 is assumed for two sides of the annulus area both top and bottom. 

From the above equation, we can find the temperature profile of the accretion disk.
$$T(r) = \bigg(\frac{GM \dot{M}}{8 \pi r}\bigg)^{\frac{1}{4}} r^{\frac{-3}{4}}$$ 

In a steady state , $\dot{M}$ must be independent of $r$ (otherwise material would pile up in the disk or there will be a shortage of material in the smaller radii) and must be equal to accretion rate reaching out to the stellar surface. 

Hence, $T \propto r^{-3/4}$ meaning that inner regions of the disk are the hottest one and it is from them most the luminosity emerges. 

The total luminosity of an accretion disk with inner and outer radii $r_i$ to $r_{out}$ is found by integrating from all annuli. 
$$L = \int_{r_{in}}^{r_{out}} 2 (2 \pi r) \sigma\; T^{4}(r)\;dr$$
$$ = \frac{1}{2}G M \dot{M} \bigg(\frac{1}{r_{in}} - \frac{1}{r_{out}}\bigg)$$

This result in principle could have been also obtained from conservation of energy. 

If $r_{out} >> r_{in}$ , the result simplifies  further to 
$$L = \frac{1}{2} \frac{GM\dot{M}}{r_{in}}$$


#### <span  style = "color:Tomato">Radiative Efficiency</span>
We can calculate the radiative efficiency of accretion disk by dividing the luminosity above by $mc^2$ , then the hypothetical power that would be obtained if all the accreted  rest mass were converted to the energy. 
$$\eta = \frac{\frac{1}{2}\frac{GM \dot{M}}{r_{in}}}{\dot{M}c^{2}}= \frac{GM}{2\;r_{in}\;c^2}$$

If the accretion object is $1.4 M_{\bigodot}$ neutron star then the accretion disk reaching  down to the stellar surface at the radius of 10  Km. 

$\therefore \; r_{in}$ is almost 2.5 times the Schwarzschild radius which is 3 km for a mass $1.4 M_{\bigodot}$

Hence the rest mass to radiative energy conversion efficiency is then about $0.10$

For blackhole accretors, it turns out to be $0.08$ from all general relativistic calculations. 

###### <span  style = "color:Orchid">NOTE</span>
> The efficiency of the accretion disc is one order of magnitude  more than the nuclear reaction. 


##### <span  style = "color:SpringGreen">Luminosity and Temperature for a typical accretion disk in various situation</span>
$$L = \frac{1}{2} \frac{GM \dot{M}}{r_{in}}$$

For a cataclysmic variable , the accretor is a white dwarf with 
mass $= 1 M_{\bigodot}$ and 
accretion rate $= 10^{-9} M_{\bigodot} \text{ yr}^{-1}$
$r_{in} =$ can be considered as the radius/surface of the white dwarf = $10^{4}\text{ km}$

![[Screenshot 2023-11-02 at 3.14.22 PM.png]]

At the inner disk, where the luminosity of the accretion disc is overpowering the white dwarf luminosity, the temperature would be 

![[Screenshot 2023-11-02 at 3.16.31 PM.png]]

$$\Downarrow$$
> The thermal spectrum in this temp peaks in the far UV part. Which is different than the spectrum  of main sequence. 


### <span  style = "color:AquaMarine">Accretion Rate & Eddington Luminosity </span>
As it is clear from various discussion that properties of accretion disk depend on various parameter but most significantly $M, \dot{M}, r_{in}$. 
$M \text{ and } r_{in}$ are limited to particular values by the properties of stars and stellar remnants. However, the accretion rate $\dot{M}$ cannot be assumed arbitrarily large. 

To establish this, let us consider an electron at a radius $r$, in an ionised gas is taking part in flow towards the mass $M$. 

The accretion flow produces luminosity per frequency interval = $L_{\nu}$ therefore we can estimate the photon density as given below
$$\Longrightarrow L_{\nu} = 4 \pi r^{2}c\; h \nu\; n_{ph}$$
or, 
$$n_{ph} = \frac{L_{\nu}}{4\pi r^{2}c \;h \nu}$$

The rate at which photon will undergo Thomson scattering with the electron is 
$$R_{scat} = n_{ph} \sigma_{T}\; c$$
where 
$\sigma_{T}= \text{Thomson scattering cross section}$

Each scattering even transfers a momentum (In average)
$$p = \frac{h \nu}{c} \text{   to the electron}$$

The rate of momentum transfer to the electron or force exerted to the electron by the radiation (photons) is then, 
$$\frac{dp}{dt} = R_{scat} \times \frac{h \nu}{c} = \frac{L_{\nu}\sigma_{T}}{4\pi r^{2}c}$$

Total radiative force on electron would be 
$$\tag{integrated over all frequency}F_{rad} = \frac{L \sigma_{T}}{4 \pi r^{2}c}$$

Now this is the force which will repel electron to the fall on the accreting source of luminosity, if there were no gravitational attraction. 

The force will be much greater on protons than on electron. Since Coulomb attraction between electron and proton does not allow proton and electrons to be separated, the gravitational attraction that works on a proton effectively works on the neighbouring electrons. The attractive force on electron hence, 
$$F_{grav} = \frac{GM\; m_p}{r^2}$$
The accretion flow, and its resulting luminosity can proceed only if the radiative force is less than the gravitational force and does not halt the inward flow i.e. $F_{rad} < F_{grav}$ and equating two of them, we can estimate maximum luminosity powered by accretion
$$L_{E } = \frac{4\pi GM\; m_{p}c}{\sigma_T}$$
$$ = \frac{4 \pi \times6.7 \times10^{-8} \times3  \times10^{10} \times2 \times10^{33} \times1.7 \times10^{-24}}{6.7 \times10^{-25}} \frac{M}{M_{\bigodot}}$$
$$= 1.3 \times 10^{38} \frac{M}{M_{\bigodot}} = 6.5 \times10^{4}L_{\bigodot} \bigg(\frac{M}{M_{\bigodot}}\bigg)$$

This limiting luminosity is called ==Eddington Luminosity==