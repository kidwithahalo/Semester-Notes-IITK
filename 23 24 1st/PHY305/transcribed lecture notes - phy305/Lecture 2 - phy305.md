  
In this lecture, we will be discussing the night sky and how we observe and measure the position of stars and galaxies in the visible universe. Also, we will learn about the different techniques and different windows to the universe.

#### <span  style = "color:Tomato">Night Sky Observation</span>
If you observe the night sky from any point in the world, you will see some stars in the horizon and some of them near the zenith, but we cannot see many stars that are below the horizon. As night goes on, many stars arise from the east and set in the west. Although Copernicus showed that the notion of a geocentric universe is not correct, our observation of the heavenly bodies is still geocentric, i.e., in a reference frame centered on earth.

##### <span  style = "color:SpringGreen">Challenges :: </span>
The daily motion of the earth is coupled with the annual motion of the sun and the slow wobble of its rotation axis  $\Longrightarrow$ results  $\Longrightarrow$  constantly changing position of the celestial bodies. We need to come up with some coordinate system in which the locations of astronomical objects will be specified and will not be sensitive to that short variation of the earth's motion.

### 1. <span  style = "color:AquaMarine">Altitude - Azimuthal Co-ordinate Systems</span>
One of the interesting things about observing the night sky is that to view it, we only require directions, not distances. Two coordinates would suffice for that.  
One of the most straightforward coordinate systems is based on the observer's local horizon. The azimuthal distance from the horizon of the star, along with the altitude of the star, can give the location of the star.
The azimuthal $A = \text{The angle eastward along the horizon from the north to the great circle. }$

##### <span  style = "color:SpringGreen">Issues with Altitude - Azimuthal co-ordinates </span>
Different locations on the earth will measure different coordinates. Also, if you start from the same location at a specified time, the coordinate changes from day to day. This is because the sun rises approximately every 4 minutes (or $1 \degree$) earlier on each successive night. 

<span  style = "color:Tan">Since earth completes one sidereal period in approximately 365.26 days, it moves a slight less than $1 \degree$  around its orbit in 24 hours. Hence the star rises 4 min before, everyday. </span>
<span  style = "color:PaleGreen">To overcome, all shortcoming a new co-ordinate system was proposed, which is called the <u>Equatorial Co-ordinate system.</u> </span>

### 2. <span  style = "color:AquaMarine">The Equatorial Co-ordinate System</span>
The equatorial coordinate system is straight-forward. It is similar to the earth's longitude and latitude, but it is independent of the earth's rotation.
> ###### <span  style = "color:Orchid">Declination is very close to Earth's latitude. </span>

In this system, two reference point have been used to determine both declination and Right Ascension. 
The first one is the celestial equator, which is a projection of the earth's equator in the celestial sphere. Declination is basically calculated by measuring the angle between the maximum altitude of the a star in the meridian and the celestial equator, which we refer to as $\delta$

> ###### <span  style = "color:Orchid">This is very interesting because if you know the altitude of a star and the declination, you can calculate the latitude of the place.</span> 
> latitude = 90 - star altitude + star declination
> For example, you see the north star Polaris, at the angle from the horizon at Kanpur ~ $\beta$
> From Catalogue, you know the declination $\approx + 89 \degree 15' \  50.8''$
> Then your latitude $\approx 90 - \beta+ 89 \degree 15' \  50.8''$
> This will be true for any observation made from any place on earth. 

Just like earth's longitude, we need to fix a reference point. As the Earth's is orbiting around the sun in an ecliptic with a tilt  $23.5 \degree$, the celestial equator & eclipse are not the same. Two times a year, the sun actually intersect with celestial sphere. In the norther hemisphere, it is <u>Vernal Equinox</u> and we assume it as a reference point & construct $\text{RA = 0 hr}$. We will coe to the details about the RA soon but just before that let me discuss some important point regarding declination. 

##### <span  style = "color:SpringGreen">How does it help to observe the stars ? </span>
Let's say I want to observe a start at $\text{RA = 7 hr}$
Based on your location, you need to figure out your $\text{RA}$ line $\longrightarrow$ i.e. the circle connecting NCP and SCP via Zenith. 
Assume the $\text{RA}$ line is 5hr 30min.  
When will my star be on the meridian, i.e., the highest point in the sky? Now, the answer to this question is in differences, i.e., 1 hour 30 minutes.

If your $\text{RA}$ line is 8hr , that means the star already crossed the meridian. The difference is 1hr (15 degrees) past the meridian. Therefore, at the maximum, the observer has 4-5 hours to observe the star. 

##### <span  style = "color:SpringGreen">Advantage</span>
As the equatorial system is based on the celestial equator and the vernal equinox, the observer's latitude and longitude does not affect the RA and declination.
Also, they are unaffected by the annual rotation of earth around the sun. 

<span  style = "color:Tan">But this is not 100% true. </span>

It has been found that the earth's rotation axis changes with time. This is because of its non-spherical shape and its gravitational interaction with the sun and moon.

Earth's precession period is 25770 years, which is slow compared to human time but important for the astrophysical time scale.

Also, the precession actually alters the position of vernal equinox along the ecliptic $\longrightarrow$ that means it is actually changing your reference point . As a result, we need to specify an epoch where the vernal equinox kept fixed, and all other measurement are done based on that. 

> <span  style = "color:dodgerblue">For RA measurement, we fixed the time at noon on January 1, 2000 GMT. A catalog using this reference date is designated as J2000. The prefix refers to the Julian calendar, which was introduced by Juilis Caeser.</span>

From observing the changes in coordinate relation to J2000. We can write in terms of empathetic relation,
![[Screenshot 2023-08-10 at 8.44.44 PM.png|]]

<br> 
<br>

> #### <span  style = "color:Tomato">Problem Solving</span>
> ![[Screenshot 2023-08-10 at 8.47.00 PM.png]]
> ![[Screenshot 2023-08-10 at 8.47.13 PM.png]]

##### <span  style = "color:SpringGreen">Astronomy Observations in different wavelengths </span>
<center>
<< included in slides >> 
</center>

#### <span  style = "color:Tomato">Magnitude Scales in Color</span>
##### <span  style = "color:SpringGreen">Absolute Magnitude</span>
For relative magnitude $m_{1,} m_2$ with flux $l_{1,}l_2$, we have, 
$$\frac{l_2}{l_{1}}= (100)^{\frac{(m_1 - m_2)}{5}}$$
which translates to
$$\tag{1} m_{1}- m_{2}= -2.5 \log_{10} \left( \frac{l_1}{l_{2}}\right)$$

Now to define the absolute magnitude we need to put the star at distance $d = 10 \text{pc}$
Suppose the star is a distance $d$ had a flux $\approx F$ and apparent magnitude  $m$.
$\therefore$ Flucx at distance $d = \text{10pc}$ will be $F_{10}$ and absolute magnitude $M$ be 
$$\tag{2} m - M = -2.5 \log_{10} \left( \frac{F}{F_{10}}\right) $$

Now it follows the square law of flux. Then the ratio of flux received from $d$  & $\text{10pc}$  will be 
$$\left( \frac{ F_{10}}{ F}\right) = \left( \frac{d }{10 }\right)^2$$
$$m -M = -2.5 \log_{10} \left( \frac{d}{10 \ pc}\right) $$
$$ \tag{3} = 5 \log_{10} \left( \frac{d}{10 \ pc}\right)$$
This quantity $(m-M)$ is a measure of the distance and is called the <b style = "color:red">Distance Module</b> 


> #### <span  style = "color:Tomato">Problem Solving</span>
> ![[Screenshot 2023-08-11 at 1.22.40 AM.png]]


##### <span  style = "color:SpringGreen">Magnitude in Different Colors</span>
SO far all the calculations we showed are for bolometric magnitudes & usually denoted by $m_{bol}$. In practice we define them only within a certain wavelength. 

+ Most used system is 
	+ UBV Wavlength Filters 

<center>
<table> 
&nbsp; <tr>  
&nbsp; &nbsp; <td>Filter Name</td>  
&nbsp;&nbsp;&nbsp; <td>Centered at</td> 
&nbsp;&nbsp;&nbsp; <td>Bandwidth</td> 
&nbsp; </tr>  
&nbsp; <tr>  
&nbsp; &nbsp; <td>U (star's Ultraviolet magnitude ) </td>  
&nbsp;&nbsp;&nbsp; <td>365 nm</td>  
&nbsp;&nbsp;&nbsp; <td>68 nm </td>
&nbsp; </tr>  
&nbsp; <tr>  
&nbsp; &nbsp; <td>B (Blue magnitude) </td>  
&nbsp;&nbsp;&nbsp; <td>440 nm</td>  
&nbsp;&nbsp;&nbsp; <td>98 nm</td>
&nbsp; </tr>
&nbsp; <tr>  
&nbsp; &nbsp; <td>V (Visual magnitude) </td>  
&nbsp;&nbsp;&nbsp; <td>550 nm</td>  
&nbsp;&nbsp;&nbsp; <td>89 nm</td>
&nbsp; </tr>
</table>
</center>

From the definition of absolute magnitude, if we know the distance $d$ of a star, we may determine the absolute color magnitudes $M_{U,}\  M_{B,} \ M_V$
A star's $U-B$ color index is the difference between ultra-violet and blue magnitude $$U-B = M_{U}- M_{B}$$
$$B-V = M_{B}- M_V$$
One thing to notice stellar magnitude, decrease with <u>increasing brightness</u>

So, smaller $B-V$ color means $B$ index is higher $\Longrightarrow$ bluer than larger value of $B-V$

> #### <span  style = "color:Tomato">Problem Solving</span>
> ![[Screenshot 2023-08-11 at 1.49.43 AM.png]]

 Usually we see a certain kind of image for each star with some diffraction pattern. If the camera or telescope is not calibrated well due to earth's atmosphere, then it will create some blurred image.
 Also, if the diameter of telescope cannot resolve the angular separation of the sky objects, then there will be overlapping of images.

In other words, <span  style = "color:Tan">if the source of light with an angular size is smaller than the diffraction limit, then that will produce an image that is unresolved with zero angular extent</span>

<b style = "color:red"> Hence, in principle, at 10 m telescope working the same visual wavelength as the eye can have an angular resolution that is 1000 times better than that of an eye</b>

With same logic, JWST produces much sharper image than the HST.
+ HST $\longrightarrow$ primary mirror $\approx$ 2.4 m
+ JWST $\longrightarrow$ primary mirror $\approx$ 6.5 m

<span  style = "color:Tan"> Another advantage of telescope is larger integration time</span>

#### <span  style = "color:Tomato">Detectors</span>
The type of detectors that is used in optical, UV, x-ray or always charge-coupled device (CCD) , same as the one being used in our camera.

CCD is a slab of silicon that is divided into numerous pixels. Photos that reaches CCD are liberated photoelectrons via photoelectric effect. 