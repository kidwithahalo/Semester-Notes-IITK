# <span  style = "color:dodgerblue">Binary Star and their Mass measurement</span>

A direct measurement of stellar mass is generally done by some binary (sometimes double or multiple star system). 
A significant of stars or member of binary system. Depending on different type of observations available, binary system are classified into various types. 

#### <span  style = "color:Tomato">Visual Binaries</span>
These are the system which can be resolved individually. They are seen to be orbiting their common centre of mass. Most of the cases, the separation between the members is so large that the orbital period is very large for human timescale.

#### <span  style = "color:Tomato">Astrometric Binaries</span>
The companion is too faint to be seen, but one of the other members shows minute periodic motion on the sky, while orbiting around the centre of mass.

#### <span  style = "color:Tomato">Eclipsing Binaries</span>
The orbital plane of a pair is inclined and up to the observers line of sight that each member periodically eclipses each other. They are also in general especially unresolved. They are usually resolved if the light from system has been monitored as a function of time. During each orbital period, the brightness of the system will undergo two dips. Each corresponds to the eclipses of one star by the another. 

![[Screenshot 2023-08-26 at 11.41.28 PM.png]]


#### <span  style = "color:Tomato">Spectroscopic Binary</span>
This is spatially unresolved pair that is only revealed by its spectrum. Sometime the observed photospheric absorption spectrum may be a superposition of the specta of two different types of stars. Alternatively, even if the members are of the same type, then orbital velocity may cause large enough Doppler shift $\frac{\Delta \lambda}{ \lambda} \approx \frac{v}{c}$ in the wavelength of absorption, to produce distinct lines with shifts that oscillates periodically during each orbit. 

![[Screenshot 2023-08-26 at 11.42.00 PM.png]]

### <span  style = "color:AquaMarine">Measurement of mass for Binary System</span>
Using Kepler's law, we can actually measure the mass of binary stars. Let us consider a binary system where both the stars are actually orbiting around a common centre of mass in elliptical trajectories. For simplicity we assume a circular path. 
![[Screenshot 2023-08-26 at 11.50.48 PM.png]]

The centre of mass is at the point between them where 
$$\tag{1} r_{1}M_{1}= r_{2}M_2$$
where ,
$r_{1}$ = distance $M_1$ from CM
$r_{2}$ = distance $M_2$ from CM
$a$ = orbital separation $= r_1 + r_2$

$$\tag{2} r_{1}= \frac{M_2}{M_{1}}(a - r_1)$$
or, 
$$\tag{3} r_{1}= \frac{M_2}{M_{1}+ M_{2}} a$$

Similarly, 
$$\tag{4} r_{2}= \frac{M_1}{M_{1}+ M_{2}}a$$

Both of stars are orbiting with angular frequency $\omega$ due to mutual gravitational attraction.
$$M_{1}\omega^{2}r_{1} = \frac{GM_{1}M_2}{a^2}$$
and replacing $r_{1}$ from Eq. 3 , we get
$$\tag{5} \omega^{2}= \frac{G(M_{1}+ M_{2})}{a^3}$$
The above equation is practically the Kepler's law. 

Note : Using this we can easily calculate the mass of the sun. 

The mass of earth is negligible compared to the sun, so 
$$\omega^{2}= \frac{G M_{\bigodot}}{a^3}$$
as $(M_{1} = M_{\bigodot})$ and $M_{2}= M_{\bigoplus}$
Also further, $a = 1 \text{AU} = 1.5 \times 10^{13} \text{cm}$ and $\tau = 1 \text{yr} = 3.15 \times10^{7} \text{sec}$

Above equation reduces to , 
$$M_{\bigodot} = \frac{4 \pi^{2}a^3}{\tau^{2}G}$$
$$\frac{4 \pi^{2}(1.5 \times10^{13} \text{cm})^3}{(3.15 \times10^{7^{2}}\times 6.7 \times10^{-8} \text{erg cm} \text{ g}^{-2})}$$
$$ = 2.0 \times10^{33} \text{ kg}$$

For the visual binaries (which can be resolved) we can directly measure the angle of separation of stars and the common centre of mass that they all orbit 

![[Screenshot 2023-08-27 at 12.07.38 AM.png]]

As both of the stars, are same distance from us, 
$$ \frac{\theta_{1}d}{\theta_{2}d} = \frac{r_1}{r_{2}}= \frac{M_2}{M_1}$$
Also, $(M_{1}+ M_2)$, we can get from Kepler's law by orbital distance between them and further solving $M_{1}+ M_{2}$ and $\frac{M_1}{M_2}$ , we can get the mass of the star. 

For binaries where stars are not resolved, we cannot measure $r1$ and $r2$ separately. From spectra we can measure the amplitude of the oscillations in the line of sight velocities  from doppler Shifts.

![[Screenshot 2023-08-27 at 1.32.42 PM.png]]
Again, we know 
$$|\nu_{1}| = \frac{2 \pi r_{1}}{\tau} \text{    and    } |\nu_{2}| = \frac{2 \pi r_{2}}{\tau}$$ 
$$\tag{6} \therefore \ \frac{|\nu_{1\ obs}|}{|\nu_{2\ obs}|} = \frac{r_1}{r_{2}}= \frac{M_1}{M_2}$$

From Eq. 6, Kepler's Law, we have
$$\omega^{2}= \frac{G(M_{1}+ M_{2})}{a^3}$$
$$\Biggr( \frac{2 \pi}{\tau} \Biggr)^{2} = \frac{G(M_{1}+ M_{2})}{(r_{1}+ r_{2})^3}$$
$$ = \frac{G(M_{1}+ M_{2})}{\Biggr \{ \frac{|\nu_{1}|\tau}{2 \pi} + \frac{|\nu_2|\tau}{2\pi} \Biggr \}^3}$$
or, 
$$(M_{1}+ M_{2}) = \frac{\tau}{2 \pi G } \Bigr( {|\nu_{1|}+ |\nu_2|} \Bigr)^3$$
$$\tag{7} (M_{1}+ M_{2})\sin^{3}i = \frac{\tau}{2 \pi G } \Bigr( {|\nu_{1obs|}+ |\nu_{2obs}|} \Bigr)^3$$

We see that the inclination angles becomes another free parameter.
Hence, we are able to determine the stellar mass only upto a factor of $\sin^{3}i$ 
Sometimes as this system are eclipsing , so mostly they are on edge on and $i = 90\degree$ and we are able to determine the masses. 
Companion is too faint like a planet. 
Therefore, $|\nu_{2obs}|$ is not detectable

Then we replace $M_2$ in terms of observed velocities
$$|\nu_{2obs}| = \frac{M_1}{M_{2}} |\nu_{1obs}|$$
$$(M_{1}+ M_{2})\sin^{3}i = \frac{\tau}{2 \pi G } \Bigr( {1 + \frac{M_1}{M_2}} \Bigr)^{3} {|\nu_{1obs|}}^3$$
Now this is only equation with three unknown $M_{1} , M_{2} , \sin i$
An important case is when $M_{2}<< M_{1}$
Then above equation changes as 
$$M_{2}\sin i = \Bigr( \frac{\tau}{2 \pi G} \Bigr)^{\frac{1}{3}} \ {|\nu_{1obs}|} \ M_{1}^\frac{2}{3}$$

This is a very important result to detect extrasolar planets. If by some means, we are able to calculate the mass of a parent star $M$, we can calculate the mass of the planet. 

###### <span  style = "color:Orchid">Example</span>
Suppose a jupiter like planet orbitting a star of mass $1 M_{\bigodot}$ and orbiting at $1 \text{AU}$
![[Screenshot 2023-08-27 at 2.04.16 PM.png]]
Assumed is that on edge $i = 90\degree$ and $\sin i = 1$
Also, $$ \frac{\Delta \lambda}{\lambda} = \frac{v}{c} = 10^{-7}$$