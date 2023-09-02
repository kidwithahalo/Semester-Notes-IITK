
<hr>

#todo 
+ 

<hr>

Book Name : 
Date Started : 12-08-2023
Date Finished : 

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

Everything starts with Planck's equation, 
$$\tag{given by $u_\nu $}\text{Energy Density}= \frac{8 \pi \nu^{2}}{c^{2}}  {\frac{h \nu}{e^{h \nu / kT}-1}}$$

Now, the above quantity is density. Also a short trick is to multiply the density by velocity to get intensity. So doing same, 
$$\tag{Radiation Intensity} B_{\nu} = \frac{2 h \nu^{3}}{c^{3}}  {\frac{1}{e^{h \nu / kT}-1}}$$

And now integrating this intensity all  over the solid angle, we will get the flux which essentially means the radiation per unit area per unit time. This is the quantity that we observe from the stars and stellar bodies
![[Screenshot 2023-09-01 at 8.59.35 PM.png]]
and the notation above of $f_\nu$ means the flux in given frequency interval. 


###### <span  style = "color:Orchid">Luminosity</span>
The total power emanated by the spherical body, isotropically called its luminosity.
Which in other words means what is the total flux at a given instant of time and frequency that leaves the entire surface of stellar bodies. 
$$L_{\nu} = f_{\nu}(r_{*})\ 4 \pi r_{*}^2$$

Similarly, the flux that an observer at a distance $d$ from the star will measure will be 
$$f_{\nu}(r_{*}) \frac{r_{*}^2}{d^2}$$

![[Screenshot 2023-09-01 at 9.06.34 PM.png]]
and since the total energy in any interval fof wavelength of freuqncy is same, we can also write that 
$$\tag{1}B_{\lambda} d \lambda = B_{\nu} d \nu$$


###### <span  style = "color:Orchid">Relation between frequency interval and wavelength interval</span>
$$\tag{2} d \lambda = \Biggr|\frac{d \lambda}{d \nu}\Biggr| d \nu = \frac{\nu}{c^{2}}d \nu$$

From 1 and 2, we have 
$$B_{\lambda} = B_{\nu} \Biggr| \frac{d \nu}{d \lambda}\Biggr| = B_{\nu} \frac{c}{\lambda}$$
$$B_{\lambda} = \frac{2 h c^{2}}{\lambda^{5}}  {\frac{1}{e^{h c / \lambda kT}-1}}$$

#### <span  style = "color:Tomato">Some results from Stefan-Boltzmann Law</span>
When we want to get the wavelength or frequency of the peak of a blackbody spectrum, we will take the derivative and equate it to $0$, this gives the maximisation values as 

$$\tag{Wien's Law}\bbox[8px, border: 2px solid red] {\lambda_{max} \ T = 0.29 \text{ cm K}}$$
and 
$$\bbox[8px, border: 2px solid red] {h \nu = 2.8 \ kT}$$
mind that here the $k$ is Boltzmann's constant. 


##### <span  style = "color:SpringGreen">Far from the peak values</span>
Far from their peak frequencies or wavelengths, the Planck blackbody spectra as- sume two simple forms. These forms are formulations which we historically achieved before Planck formula but it failed horribly to explain what happened in between. 
So if we take the limits 
+ Frequency $\nu$ much lower than the peak, i.e.  $h \nu << kT$
$$B_{\nu} = \frac{2 \nu^2}{c^{2}}kT$$ or 
$$B_{\lambda} = \frac{2ckT}{{\lambda}^4}$$
<span  style = "color:coral">This is called the Rayleigh-Jeans side of the thermal spectrum. And if you are having problem getting this simplification, I presume there had been a linear approximation od $e^x$ and then it reduces such.</span>

<br>

+ Frequency $\nu$ much higher than the peak, i.e.  $h \nu >> kT$
$$B_{\nu} \sim e^{ - \frac{h \nu}{kT}}$$
or 
$$B_{\lambda} \sim e^{ - \frac{h c}{\lambda kT}}$$
<span  style = "color:magenta">This is called the “Wien tail” of the distribution.</span>

<figure>
<center>
<img src="https://www.researchgate.net/publication/282642501/figure/fig4/AS:670698439733270@1536918377466/Comparison-of-Rayleigh-Jeans-Formula-for-the-spectrum-of-the-radiation-from-a-blackbody.png" alt="" style="width:100%">
<figcaption align = "center">
<b></b>
</figcaption>
</center>
</figure>

<br> 

## <span  style = "color:PaleGreen">MEASUREMENT OF STELLAR PARAMETERS</span>
+ The plane of the Earth’s orbit is called the “ecliptic plane” 
<br>
+ Though the core of a star can have $T \sim 10^{6} \text{ K}$ , the outer surface can have temperatures in range of $\sim 10^{3}\text{ K}$
<br>
+ Layers in the surface of star from where the stars are able to escape is called 'Photosphere'. The depth of the base of the photosphere can be wavelength dependent due to the variation in the absorption and scattering probabilities. 
+ 

