
## <span  style = "color:PaleGreen">LIMB Darkening</span>

To explain limb - darkening or understanding the atmosphere of the sun or sun(qualitatively), we usually  follow an approximation called grey atmosphere approximation - where we assume all the qualities mainly the absorption coefficients is constant for all frequencies. 
Remember that there is no real atmosphere with this property. 

In this case, the specific intensity and the source function all become independent of frequency 
$$I = \int I_{\nu}d \nu \ \ \ \ \ \ \text{and} \ \ \ \ \ \ S = \int s_{\nu}\ d \nu$$

The radiative transfer equation becomes 
$$\tag{21} \mu \frac{d I(\tau, \mu)}{d \tau} = I - s $$


##### <span  style = "color:SpringGreen">1st Step : </span>
Multiplying Eq.21 by $\frac{1}{2}$ and integrating over $\mu$
$$\frac{1}{2} \frac{d}{d \tau} \int_{-1}^{+1} I(\tau, \mu) \ \mu \ d \mu \ =\  \frac{1}{2} \int_{-1}^{+1} I\  d \mu  - \frac{1}{2} \int_{-1}^{+1} s\  d \mu$$
$$\tag{22} \frac{1}{4 \pi} \frac{dF}{d \tau} = j - s$$
where $F$ in terms of $I$ , we already know, $\bbox[6px, border: 1px solid white]{F = 2 \pi \int_{-1}^{+1} I(\tau, \mu) \mu d \mu}$ and $\bbox[6px, border: 1px solid white] { J = \frac{1}{2}\int_{-1}^{+1} I(\tau, \mu) \mu d \mu}$ , and this $J$ is the average intensity over the $\mu$ (all angles)
$$ = \frac{c}{4 \pi} U $$ 
where $U$ = energy density


##### <span  style = "color:SpringGreen">2nd Step : </span>
Multiply Eq. 21 by $\frac{2 \pi \mu}{c}$ and integrating over $\mu$, we get 
$$\frac{d}{d \tau} \int_{-1}^{+1} \frac{2 \pi}{c} I(\tau, \mu) \mu^2 d \mu$$
$$\frac{2 \pi}{c} \int_{-1}^{+1} I(\tau, \mu) \mu d \mu - \int_{-1}^{+1}s \mu d \mu$$
$$\tag{23} \frac{dP}{d \tau} = \frac{F}{c}$$

We actually were able to establish relationship with observational quantities.
Also, very often within a stellar atmosphere, we do not have a source or sink of energy and the flux which is coming from the source is independent of depth and to achieve this condition i.e.  for flux $F$ to be constant, the average specific intensity needs to be equal to the source function 
$$\tag{Radiative equation} J = s $$

Also, if you remember, for  isotropic radiation field from any source, the pressure can be related to the energy of the object and we have
$$\tag{25} P = \frac{1}{3}U$$

This is not always valid, but below the photosphere and in the interior of star, this is valid and this is called Eddington's approximation

If flux remains constant , $F = \text{constant}$ , integrating Eq. 23, 
$$\tag{26} P = \frac{F}{c} (\tau + q)$$
where $q$ is the integration constant

Now combining Eq 23,24,25,26 we find that the 
$$J = \frac{c}{4 \pi} U = \frac{c}{4 \pi} 3P$$
$$\bbox[9px, border: 2px solid red]  {\tag{27} S = \frac{3F}{4 \pi}(\tau + q)}$$

This gives the source function for a plane parallel grey atmosphere.

If you have the source function known, it is bit easier to calculate the specific intensity.

![[Untitled Diagram.drawio 1.svg|550x350]]

For the sun, we are considering rays which are going outward and $\mu \geq 0$.
Therefore, the radiative transfer equation solution would need to be considered for $\mu \geq 0$ and 
$$\tag{28} I(\tau, \mu\geq 0) = \int_{\tau}^{\infty} s  \ e^{\frac{-(\tau' - \tau)}{\mu}} \frac{d\tau'}{\mu}$$

Let's assume the radiation coming out of the stellar surface and we can obtain it by putting $\tau= 0$, 
$$I(0, \tau) = \int_{0}^{\infty} s \ e^{\frac{-\tau'}{\mu}} \frac{d \tau'}{\mu}$$
$$ = \int_{0}^{\infty} \frac{3F}{4 \pi} (\tau' + q) \ e^{\frac{-\tau'}{\mu}} \frac{d \tau'}{\mu}$$
and only unknown parameter is $q \longrightarrow$ the integration constant

After integrating, $\frac{\tau'}{\mu} = x \implies d \tau' = \mu dx$
$$I(0, \mu) = \int_{0}^{\infty} \frac{3F}{4 \pi} \mu\  x e^{-x}\  dx + \int_{0}^{\infty} \frac{3F}{4 \pi} q e^{-x}\  dx$$
$$ =  \frac{3F}{4 \pi} \mu\ \Biggr[ (x e^{-x}) \Biggr|_{0}^{\infty}  -  (e^{-x})\Biggr|_{0}^{\infty} \Biggr] + \frac{3F}{4 \pi}q $$
$$I(0, \mu) = \frac{3F}{4 \pi} \Bigr[ \mu + q \Bigr] $$

Also remember that, $$F = 2 \pi \int_{0}^{1} I \mu d \mu $$
$$ = 2 \pi \int_{0}^{1} \frac{3F}{4\pi} \mu^{2} \ d \mu \ + \ 2 \pi \int_{}^{} \frac{3F}{4\pi} q \ \mu\ d \mu$$
$$F = \frac{3F}{2} \Biggr[ \frac{\mu^{3}}{3} \Biggr]_{0}^{1} + \frac{3Fq}{2} \Biggr[ \frac{\mu^{2}}{2} \Biggr]_{0}^{1}$$
$$F = \frac{3F}{2} \Biggr\{ \frac{1}{3} + \frac{q}{2} \Biggr\}$$
$$q = \frac{2}{3}$$
$$I(0, \mu) = \frac{3F}{4\pi} \Biggr(\mu + \frac{2}{3}\Biggr)$$

Hence we can calculate the intensity at different location.

$$\frac{I(0, \mu)}{I(0,1)} = \frac{3}{5} \Biggr( {\mu+ \frac{2}{3}} \Biggr)$$

This explains the occurrence  of limb darkening. 


### <span  style = "color:AquaMarine">Stellar Types and Stellar Temperatures</span>
From previous study, we saw that the emitted spectrum of the star is largely determined by the temperature in the outer surface - which we call photosphere. The photosphere can be roughly defined as the region from which photons are able to escape a star without further absorption or scattering. 

Recall the radiative transfer solution, 
$$I_{\nu}(\tau, \mu) = B_{\nu}(\tau_{\nu}) \ + \ \mu \frac{dB_{\nu}}{d \tau_{\nu}}$$

For direct incoming ray from the star, $\mu= 1$ and also from a region, 
$$I_{\nu(0,1)}= B_{\nu(0)}\ + \frac{dB_{\nu}}{d \tau_{\nu}}$$
If we expand $B_{\nu}(\tau_{\nu}= 1)$ in  a Taylor series around $\tau_{\nu} = 0$ , we get
$$B_{\nu}(\tau_{\nu}= 1) = B_{\nu}(\tau_{\nu}= 0) \ + \ (1-0) \frac{dB_{\nu}}{d \tau_{\nu}}$$
$$= B_{\nu}(0) + \frac{dB_{\nu}}{d \tau_{\nu}}$$
$$\Longrightarrow I_{\nu(0,1)}= B_{\nu}(\tau_{\nu}=1 )$$

The amount of radiation coming from the sun without getting absorbed it same as the blackbody radiation of spectra optical depth,  $\tau = 1$ 
This is called photosphere and this layer has optical depth of 1 i.e. $\tau = 1$ 

For measuring stellar temperature, we actually use a Planck distribution. We define the colour temperature as the temperature of Planck function with shape almost closely with the option of spectrum. 

If we identify the position of the peak of the spectrum, we could use the Wien's law to set the temperature. But when we observe a star, the peak will often be outside the wavelength range for which we have the data. Further more, it is a broad feature that is hard to identify.
$$\tag{Wien's law} \ \lambda_{max} T = 0.29 \text{ cm-K}$$

##### <span  style = "color:SpringGreen">A more practical approach</span>
Measuring fluxes at two different wavelength say, $\lambda_1, \  \lambda_2$ i.e $f(\lambda_{1})\ ,  f(\lambda_2)$, then find the temperature of blackbody that gives such a ratio. 

Another kind of temperature can be associated with the photosphere of a star by examining absorption features in discrete wavelength in distiller atmosphere 