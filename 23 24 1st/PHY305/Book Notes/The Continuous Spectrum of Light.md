#todo 
+ 

<hr>

Book Name :  Carroll, Dale - An Introduction to Modern Astrophysics
Date Started : 08-08-2023
Date Finished : 09-08-2023

<hr>

### <span  style = "color:Plum">Suggested Links </span>
+ 

<hr>


### <span  style = "color:dodgerblue">Questions to track </span>
+ 


<hr>

### <span  style = "color:Coral">Chapters Section </span>
+ [[The Continuous Spectrum of Light#^43336b|The Stellar Parallax]]
+ [[The Continuous Spectrum of Light#^c68bf0|The Magnitude Scale]]
+ [[The Continuous Spectrum of Light#^bb38f8|The Wave Nature of Light]]
+ [[The Continuous Spectrum of Light#^771f1b|The BlackBody Radiation]]
+ [[The Continuous Spectrum of Light#^751ecd|The Quantization of the Energy]]
+ [[The Continuous Spectrum of Light#^f554dd|The Color Index]]

<hr>

### <span  style = "color:AquaMarine">3.1 Stellar Parallax</span>

^43336b
<figure>
<center>
<img src="https://www.astro.utu.fi/~cflynn/Stars/full/parallax.gif" alt="" style="width:80%">
<figcaption align = "center">
<b>Stellar Parallax</b>
</figcaption>
</center>
</figure>

+ 1 light year = $9.46 \times 10^{15}$ m
+ I parsec = 3.26 light year
+ 1 AU = $1.49 \times 10^{8}$ m


<hr>


### <span  style = "color:AquaMarine">3.2 The Magnitude Scale</span> 

^c68bf0

One thing is as much clear that all the data and inferences that we have drawn for the universe was based on the emitted light that we received. 

##### <span  style = "color:Coral">The Apparent Magnitude</span>
For the classification of stars in terms of their brightness, following was the strategy that the Hipparchus applied. 
+ For the brightest start, the magnitude system of $m=1$ and 
+ For the faintest start, the magnitude $m= 6$  

And the fact that human eyes perceive the logarithms of the difference of the luminosity of the stars
> By the modern definition, a difference of 5 magnitudes corresponds exactly to a factor of 100 in brightness, so a difference of 1 magnitude corresponds exactly to a brightness ratio of $100^{1/5} \approx2.512$.Thus a first magnitude star appears 2.512 times brighter than a second-magnitude star, $2.512^2 \approx 6.310$ times brighter than a third-magnitude star, and 100 times brighter than a sixth-magnitude star.

##### <span  style = "color:Coral">Flux, Luminosity, and the Inverse Square Law</span>
The “brightness” of a star is actually measured in terms of the <b style = "color:red">radiant flux, F</b> received from the star.
⩺ The radiant flux is the total amount of light energy of all wavelengths that crosses a unit area oriented perpendicular to the direction of the light’s travel per unit time; that is, it is the number of joules of starlight energy per second (i.e., the number of watts) received by one square meter of a detector aimed at the star.
$$\text{F} = \frac{L}{4 \pi r^2 }$$
 where,
 $F$ = Radiant Flux
  $L$ = Luminosity
  $r$ = distance from the source (assumed spherical)

##### <span  style = "color:Coral">Absolute Magnitude</span>
Definition wise, This is defined to be the apparent magnitude a star would have if were located at a distance of 10 pc. Value system of same $M$ is used here as used earlier for brightest and faintest star. 
On same concept ,the flux ratio is given by 
$$\frac{F_1}{F_2} = 100^{(m_1 - m_2)/5}$$
and after logarithm of same , we have 
$$m_1 - m_2 = -2.5 \log_{10} \frac{F_1}{F_2}$$
<hr>

##### <span  style = "color:Coral">Distance Modulus</span>
Connecting the star's apparent and absolute magnitude and the distance by the formula of 
$$m - M = 5 \log_{10} (d) - 5 = 5 \log_{10} \frac{d}{10 \text{ pc}}$$
and $m - M$ is known as <span  style = "color:dodgerblue">distance modulus.</span>


![[Pasted image 20230808203205.png|15]] Ratio of their radiant fluxes is equal to the ratio of their luminosities

<hr>

### <span  style = "color:AquaMarine">3.3 The wave nature of light</span>

^bb38f8

The speed of light was first measured with some accuracy in 1675, by the Danish astronomer Ole Roemer (1644–1710). 

##### <span  style = "color:Coral">Young's Double Slit Experiment</span>
<figure>
<center>
<img src="https://slideplayer.com/1476983/5/images/slide_1.jpg" alt="" style="width:80%">
<figcaption align = "center">
<b>Young's Double Slit Experiment</b>
</figcaption>
</center>
</figure>

##### <span  style = "color:Coral"> Maxwell's Electromagnetic Wave Theory</span>
<figure>
<center>
<img src="https://sites.google.com/a/coe.edu/principles-of-structural-chemistry/_/rsrc/1468739013723/relationship-between-light-and-matter/electromagnetic-spectrum/EMSpectrumcolor.jpg" alt="" style="width:80%">
<figcaption align = "center">
<b>Electromagnetic Spectrum</b>
</figcaption>
</center>
</figure>

##### <span  style = "color:Coral"> The Poynting Vector and Radiation Pressure</span>
Electromagnetic radiation carries energy as it propagates. And this rate at which the radiation carries the energy and momentum with it is called <b style = "color:red">Poynting Vector</b>
$$S = \frac{1}{\mu_0} E \times B$$. where the $S$ has the unit of $W m^{-2}$. Again the Poynting vector runs with the same concept of Energy per unit time per unit area with the perpendicular constraint taken in the consideration. 

In a vacuum the magnitude of the time-averaged Poynting vector, $\langle S \rangle$ is given by 
$$\langle S \rangle = \frac{1}{2 \mu_0} E_0 B_0$$
where,  also another relation that runs is $E_0  = cB_0$ and 
$E_0$ = max amplitude of Electric fields
$B_0$ = max amplitude of Magnetic fields

And as per the radiation pressure goes, we have  radiation pressure for absorption and for reflection 
$$
\tag{For absorption}
F_{rad} = \frac{\langle S \rangle A}{c} \cos \theta
$$


$$
\tag{For reflection}
F_{rad} = \frac{2 \langle S \rangle A}{c} \cos^2 \theta
$$

<hr>

### <span  style = "color:AquaMarine">3.4 BlackBody Radiation</span>

^771f1b

The <b style = "color:red">perfect emitter</b> will not reflect any light and hence won't be visible. Hence the term 'blackbody' and the radiation emanating from them is called blackbody radiation. 

<figure>
<center>
<img src="https://howthingswork.org/wp-content/uploads/2017/04/blackbody-radiation-Fig1.png" alt="" style="width:80%">
<figcaption align = "center">
<b>Black Body spectrum</b>
</figcaption>
</center>
</figure>

Here, we see that tere is a certain peak for each temperature. This relation is given by <b style = "color:red">Wien's Displacement Law</b> which says $$\lambda_{\text{max}} T = 0.29 \text{ cm-K} $$

##### <span  style = "color:Coral">The Stephen-Boltzmann Equation</span>
Josef Stephen gave the equation that luminosity, $L$ of a blackbody with the area $A$ and temperature $K$ is given by $$L = A \sigma T^4$$
where Stephen Botlzmann constant, $\sigma = 5.670400 \times 10^{-8} \text{ W } m^{-2} K^{-4}$
and likewise the surface flux would simply be 
$$
\tag{For effective temp. }
F_{surf} = \sigma T_{e} ^4
$$

<hr>

### <span  style = "color:AquaMarine">3.5 The Quantization of Energy</span>

^751ecd
<figure>
<center> 
<img src="https://semesters.in/wp-content/uploads/2020/11/plancks-law.png" alt="" style="width:80%">
<figcaption align = "center">
</figcaption>
</center>
</figure>

Now the accepted value of $h = 6.626 \times 10^{-34}$ J s

Continuing on the same equation of Planck, we derive for spherical co-ordinates, the amount of radiant energy per unit time having wavelength $\lambda$ and $\lambda + d \lambda$ emitted by a blackbody of temperature $T$ and a surface area $dA$ into a solid angle $d \Omega \equiv \sin \theta \  d \theta  \ d \phi$ is 
$$B_{\lambda}(T)d \lambda \ dA \ \cos \theta \ \sin \theta \ d \theta \ d \phi$$

and in frequency and wavelength terms we have , 

<div style="display: flex; justify-content: center; gap: 10px;">
  <!-- Replace 'image1.jpg' and 'image2.jpg' with the paths to your images -->
  <img src="https://www.colorado.edu/studentgroup/ostem/sites/default/files/styles/medium/public/page/screen_shot_2020-06-18_at_6.06.00_pm.png?itok=9fa1jQRa" alt="Image 1" style="width: 50%;">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTWTNY2iUUpXkivl17b8sQPMeDY2ucE-ofYDUO6TXehnk7EWXK9TV8irGn5-pWTI5pcMg&usqp=CAU" alt="Image 2" style="width: 50%;">
</div>

##### <span  style = "color:Coral">Monochromatic Luminosity</span>
<figure>
<center>
<img src="http://burro.cwru.edu/academics/Astr221/Light/monolum.gif" alt="" style="width:80%">
<figcaption align = "center">
<b>Term on LHS is called monochromatic Luminosity</b>
</figcaption>
</center>
</figure>

and as speculated from prior, the monochromatic luminosity is related to the monochromatic flux $F_{\lambda} d \lambda$
![[Screenshot 2023-08-08 at 10.41.57 PM.png]]
and further, reduce one term with the another  given above. 

#question
But these equations assume that no energy loss happened from source till it was received by the sensor. How do we fix this disparity ?? 

<hr>

### <span  style = "color:AquaMarine">3.6 The Color Index</span>

^f554dd

##### <span  style = "color:Coral">UBV Wavelength Filters</span>
<figure>
<center>
<img src="https://upload.wikimedia.org/wikipedia/commons/c/ce/UBV-System.png" alt="" style="width:80%">
<figcaption align = "center">
<b>Standard UBV system</b>
</figcaption>
</center>
</figure>


<center>
<table> 
&nbsp; <tr>  
&nbsp; &nbsp; <td>Filter Range</td>  
&nbsp;&nbsp;&nbsp; <td>Centered at</td> 
&nbsp;&nbsp;&nbsp; <td>Bandwidth</td> 
&nbsp; </tr>  
&nbsp; <tr>  
&nbsp; &nbsp; <td>U (Ultraviolet) </td>  
&nbsp;&nbsp;&nbsp; <td>365 nm</td>  
&nbsp;&nbsp;&nbsp; <td>68 nm </td>
&nbsp; </tr>  
&nbsp; <tr>  
&nbsp; &nbsp; <td>B (Blue) </td>  
&nbsp;&nbsp;&nbsp; <td>440 nm</td>  
&nbsp;&nbsp;&nbsp; <td>98 nm</td>
&nbsp; </tr>
&nbsp; <tr>  
&nbsp; &nbsp; <td>V (Visual) </td>  
&nbsp;&nbsp;&nbsp; <td>550 nm</td>  
&nbsp;&nbsp;&nbsp; <td>89 nm</td>
&nbsp; </tr>
</table>
</center>

##### <span  style = "color:Coral">Color Indices and Bolometric Corrections</span>
A bolometer is an instrument that measures the increase in temperature caused by the radiant flux it receives at all wavelengths.
And the color index is solely the measure of the temperature of a model blackbody star
$$U - B = M_U - M_B$$ and  $$B - V = M_B - M_V$$

Further, stellar magnitudes decreases with the increasing brightness consequently, a star with a smaller $B - V$ color index is $bluer$  than a star with larger value of $B - V$
Note that since color index is difference of the magnitude , it is independent of the distance of the star.
$\Downarrow$
The difference between a star’s bolometric magnitude and its visual magnitude is called <b style = "color:red">bolometric correction, BC</b>
$$BC = m_{bol} - V = M_{bol} - M_V$$

###### <span  style = "color:Orchid">The Sensitivity Function</span>
Sensitivity Function $S(\lambda)$. 
It is used to describe the fraction of star's flux that is detected at wavelength $\lambda$. For a perfect bolometer, capable of detecting 100% of the light the emanates from the star, we set $S(\lambda) \equiv 1$
$S(\lambda)$ depends on 
+ reflectivity of the telescope mirrors 
+ the bandwidths of $U,B,V$ filters 
+ response of the photometer

<< for star’s ultraviolet magnitude, $U,B,V$ ,refer to section 3.6, page 76 >>

> ## Trivia
> ###### <span  style = "color:Orchid">What does it mean to have a postive bolometric correction ? </span>
> + it mean that the amount of radiation received by the telescope is only a fraction of all the radiation emanated by the star which is much large.  
> + in other words, since a star’s radiant flux over all wavelengths is greater than its flux in any specified wavelength band
> ###### <span  style = "color:Orchid">What does it mean to have a negative bolometric correction ? </span>
> + The radiant flux observed in a certain wavelength range is larger than the radiaint flux in the entire 

### <span  style = "color:Tomato">The Color - Color Diagram</span>
It shows the realtion between $U-B$ and $B-V$ color indices for the main sequence stars. 
<figure>
<center>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS0zdAeBLkgeCySV8RXl6nWb_3GuAAASAqxccZ2PlYTUfaCdnyGf_MzXox_wFlLWrugKGg&usqp=CAU" alt="" style="width:80%">
<figcaption align = "center">
<b>The color-color Diagram</b>
</figcaption>
</center>
</figure>

If stars actually behaved as blackbodies, the color–color diagram would be the straight dashed line. However, stars are not true blackbodies. As will be discussed in detail in Chapter 9, some light is absorbed as it travels through a star’s atmosphere, and the amount of light absorbed depends on both the wavelength of the light and the temperature of the star.