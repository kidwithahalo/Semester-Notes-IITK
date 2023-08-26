In the last lecture, we saw that specific intensity remains constant along the ray free space 
$$\tag{1} \frac{d I_{\nu}}{ds} = 0$$

What will happen if the matter is present along the ray path ? 
+ If the matter emits, it will add to the specific intensity $\rightarrow$ this will be taken care of by adding emmission coefficient, $j_{\nu}$ on the right hand side of Eq. 1
+ If the radiation gets absorbed, it will add a negative term in the RHS of Eq. 1. 
  Also, if the intensity of radiation is strong, there is more energy to get absorbed. Hence, the attenuation term will be proportional to $I_{\nu}$

Final radiative transfer equation in presence of matter is 
$$\tag{2}\frac{d I_{\nu}}{ds} = j_{\nu} \ - \ \alpha_{\nu}I_{\nu}$$
where $\alpha_{\nu} =$ absorption coefficient which depends on the frequency and the material properties.

#### <span  style = "color:Orchid">Solutions</span>
It is quite easy to solve equation. 2, if either the emission coefficient or absorption coefficient is zero.

##### <span  style = "color:SpringGreen"> Emission coefficient is zero</span>
If we consider $j_{\nu} = 0$, then Eq.2 becomes
$$\frac{dI_{\nu}}{ds} = -\alpha_{\nu}I_{\nu}$$
$$\tag{3} \Longrightarrow I_{\nu} (s) = I_{\nu}(s_{0)}\ \exp \left({\int_{s_0}^{s}\alpha{_\nu}(s')ds'}\right)$$

This is the specific intensity at distance $s$ when ray is moving from $s_0$ to $s$

Let us examine the solution 3 in the details. 

We will introduce the quantity called optical depth, wiki widely used in astrophysics. This is actually defined as 
$$d\  \tau_{\nu} = \alpha_{\nu} \ ds$$ 
such that 
$$\tag{4}\tau_{\nu} = \int_{s_0}^{s}\alpha_{\nu}(s')ds'$$

If the optical depth $\tau_{\nu} >> 1$ along a ray path through an object, then the object is known as optically thick. On the other hand if $\tau_{\nu} << 1$, an object is known as optically thin. 
$$I_{\nu}\ (s) = I_{\nu}(s_0)\exp(-\tau_{\nu})$$
or , $$\tag{5} I_{\nu}(\tau_{\nu}) = I_{\nu} (0) \exp (-\tau_\nu)$$ 

###### <span  style = "color:Orchid">Physical Meaning</span>
An optically thick object extinguishes the light of a source behind it. 

For optically thin object, the light from the source does not get extinguished  much. 
(Optically thick roughly means opaque and optically thin roughly means transparent)

##### <span  style = "color:SpringGreen">Both co-efficient is present</span>
[ Both $j_\nu$ and $\alpha_\nu$ are present ]

Divide the radiative transfer Eq. 2 by $\alpha_\nu$, we get 
$$\frac{dI_\nu}{\alpha_{\nu}\ ds} = \frac{j_\nu}{\alpha_{\nu}}- I_\nu$$
$$\tag{6} \frac{dI_\nu}{d\tau_{\nu}}= s_{\nu}- I_\nu$$

and here we define a quantity as , $\frac{j_\nu}{\alpha_{\nu}}= s_{\nu}= \text{Source function}$

Multiplying the Eq.6 by $e^{\tau_\nu}$ , we get
$$e^{\tau_{\nu}} \frac{dI_{\nu}}{d \tau_{\nu}}+ I_{\nu} \ e^{\tau_{\nu}}= s_{\nu} \ e^{\tau_\nu}$$
$$\tag{7} \frac{d}{d \tau_{\nu}} (I_{\nu}\ e^{\tau_{\nu}}) = s_{\nu} \ e^{\tau_\nu}$$

Now let us integrate this equation from a ray path $s_0$ to $s$ which means basically over optical depth $0$ to $\tau_\nu$
After integrating, 
$$\int_{0}^{\tau_{\nu}} d \left( I_{\nu} \ (\tau_{\nu}') \ e^{\tau_{\nu}'} \right) = \int_{0}^{\tau_{\nu}} s_{\nu} (\tau_{\nu}') \ e^{\tau_{\nu}'}$$

$$\tag{8} \Longrightarrow I_{\nu}(\tau_{\nu}) = I_{\nu}(0) \ e^{-\tau_{\nu}} \ + \ \int_{0}^{\tau_{\nu}} e^{(\tau_{\nu} - \tau_{\nu}')}$$

In order to get, how specific intensity looks like after travelling a path from $s_0$  to  the distance $s$ of optical depth $\tau$ , we need to solve the Eq. 8 which is general solution of radiative transfer equation. 

##### <span  style = "color:SpringGreen">A case to solve equation 8 for material with constant properties</span>
A major underlying assumption here is that 
<b> Matter through which radiation is passing has constant properties</b>

$$s_{\nu}= \text{constant} = \frac{j_\nu}{\alpha_{\nu}} = \text{constant}$$
Eq.8 then becomes, 
$$\Rightarrow I_{\nu} (\tau_{\nu}) = I_{\nu}(0) \ e^{\tau_{\nu}} \ + \ s_{\nu}(1 - e^{-\tau_{\nu}})$$
Now, let's do some approximation, 
+ No source behind the object, $I_{\nu}(0) = 0$
+ $I_{\nu}(\tau_{\nu}) = s_{\nu}(1 - e^{-\tau_{\nu}})$

###### <span  style = "color:Orchid"> For optically thin case</span>
$$\tau_{\nu} << 1 \text{  meaning that } \Rightarrow e^{-\tau_{\nu}} \approx 1-\tau_\nu$$
$$\therefore I_{\nu}(\tau_{\nu}) = s_{\nu} \tau_{\nu} \approx \frac{j_{\nu}}{\alpha_{\nu}} \tau_{\nu}$$
If $L$ = total length of ray path, then $\tau_{\nu} = \alpha_{\nu} \ L$
$$\bbox[8px, border: 2px solid red] {\tag{10} \therefore I_{\nu}= j_{\nu}\ L}$$

###### <span  style = "color:Orchid">For optically thick case</span>
We have here , $\tau_{\nu} >> 1$, 
$$\bbox[8px, border: 2px solid red] {\tag{11} \therefore I_{\nu}(\tau_{\nu}) = s_{\nu}}$$


#### <span  style = "color:Tomato">Kirchhoff's  Law </span>
One of the direct implication we see for radiative transfer is in the form of Kirchhoff law  


![[Screenshot 2023-08-26 at 1.28.15 PM.png|300x200]]


Suppose we have a box that is kept at thermodynamic equilibrium. Now, if we make a small hole, we know that the radiation coming out of the hole will be the blackbody radiation. 
Hence the specific intensity as we studied earlier will be 
$$\tag{12} I_{\nu} = B_{\nu}(T)$$
where 
$$B_{\nu}(T) = \frac{2 \pi \nu^{3}}{c^{2}} \frac{1}{\exp (\frac{h \nu}{k_{B}T})-1} $$

Now let's put some optically thick object behind the hole as shown in figure. 
What will happen now ? 

If this optically  thick object is in equilibrium with the surrounding in the box, then it will emit the blackbody radiation too. It won't be disturb the environment. Therefore in this case too, the specific intensity will be given by $B_{\nu}(T)$

But on the other hand, when we solve the radiative transfer equation for optically thick case, we get $I_{\nu} = s_{\nu}$

For this example case, we can derive how the source function look like
$$s_{\nu}= B_{\nu}(T)$$
$$\Rightarrow \frac{j_{\nu}}{\alpha_{\nu}} = B_{\nu}(T)$$
$$\tag{This is famous Kirchhoff's law}\bbox[10px, border: 2px solid red] {j_{\nu}= \alpha_{\nu} B_{\nu}(T)}$$

##### <span  style = "color:SpringGreen">In simple words</span>
The ratio of emission coefficients to the absorption  coefficient should be smooth, blackbody radiation $B_{\nu}\ (T)$

#### <span  style = "color:Tomato">Significance</span>
##### <span  style = "color:SpringGreen">For optically thin system [e.g, hot transparent gas]</span>
The radiation coming from it is essentially the emission coefficient. Also we know that emission coefficient is expected to have peaks at spectral lines. Hence, from a optically thin system we would expect emission to bee mainly in spectral lines. 


##### <span  style = "color:SpringGreen">For optically thick material / space [e.g. , a hot piece of iron]</span>
We just derived the source function for a optical system is basically its emission and that is blackbody radiation

<span  style = "color:Sienna">The nature of radiation from any astrophysical sources crucially depends on whether the source is optically thin or optically thick ? </span>

Emission from a tenuous nebula is in spectral lines. 
But emission from the stars are very much like a black body. 

> ### <span  style = "color:AquaMarine">Why like a blackbody and not exactly like a black body ? </span>
> Because while solving the radiative transfer equation, we assume that the source have constant properties which is certainly not the case for a real stars. 

<br>

## <span  style = "color:PaleGreen">Application of the radiative transfer equation : Stellar Atmosphere</span>

General solution of radiative transfer equation
$$I_{\nu}(\tau_{\nu}) = I_{\nu}(0)e^{-\tau_{\nu}}  \ + \ \int_{0}^{\tau_{\nu}} e^{-(\tau_{\nu} - \tau_{\nu}')}\ s_{\nu} (\tau_{\nu} ') \ d \tau_{\nu}'$$

Why it is difficult to solve this general solution of radiative transfer because we need to know apriori all the information of the source function which is not a trivial job. 

Finding simultaneously the radiation field and temperature is most challenging and to get that we make several approximations. 

One of the assumption is plane parallel atmosphere. 

This means for a stellar atmosphere we neglect the spherical curvature and assume all the parameters constant over horizontal. 

#### <span  style = "color:Tomato">Plane parallel atmosphere</span>
We consider the ray path $ds$

![[Untitled Diagram.drawio.png|500x300]]

All the properties are constant along horizontal planes and all the thermodynamic variables are function of $Z$ alone. 
If for a distance element '$ds$' along the ray path, $dz$ is the change in $z$. 
Then, 
$$ds = \frac{dz}{\cos \theta} = \frac{dz}{\mu}$$
where $\mu = \cos \theta$  or, $\theta = \cos ^{-1} \mu$

Usually we know , $I_{\nu} \approx I_{\nu}(\vec{r}, t, \hat{n})$ but we are considering a static case. 
Hence, $I_{\nu} = I_{\nu}(z, \mu)$ for plane parallel atmosphere

#### <span  style = "color:Tomato">Radiative Transfer Equation</span>
$$\frac{d I_{\nu}}{ds} = j_{\nu} - \alpha_{\nu} I_{\nu}$$
$$\tag{14} \mu \frac{d I_{\nu}(z,\mu)}{dz} = j_{\nu} - \alpha_{\nu} I_{\nu}$$

##### <span  style = "color:SpringGreen">Defining optical depth</span>
In this case, we define optical depth as 
$$d \tau_{\nu} = - \alpha_{\nu} \ dz$$
Point to note 
+ negative sign, than usual notation is because optical that naturally increases as we go deeper down towards the star (Normal convention is to take $\tau_{\nu}=0$ at the top of stellar depth)
+ Defined along vertices axis $dz$ not along $ds$

Writing Eq. 14 in terms of optical depth (i.e. dividing by $\alpha_{\nu}$ on both side)
$$\tag{15} \mu \frac{dI_{\nu}(\tau_{\nu}, \mu)}{d \tau_{\nu}} = I_{\nu} - s_{\nu}$$
where  we have , $s_{\nu}= \frac{j_{\nu}}{\alpha_{\nu}}$

Similarly, want to we did earlier and then multiply Eq. 15 by $e^{\frac{-\tau_{\nu}}{\mu}}$ , we get
$$\mu \frac{d}{d \tau_{\nu}}(I_{\nu} \ e^{(\frac{-\tau_{\nu}}{\mu})} = -s_{\nu} e^{\frac{-\tau_{\nu}}{\mu}} $$

Integrating this equation, from some reference optical depth $\tau_\nu$ , we can write
$$\tag{16} I_{\nu} \ e^{\frac{-\tau_{\nu}}{\mu}} \Biggr|_{\tau_{\nu},\  0}^{\tau_{\nu}} = -\int_{\tau_{\nu},\  0}^{\tau_{\nu}} \frac{s_{\nu}}{\mu}e^{\frac{-\tau_{\nu}}{\mu}} d \tau_{\nu}'
$$

###### <span  style = "color:Orchid">Consider two case</span>
Case 1 : 
$0 \leq \mu \leq 1 \Rightarrow$ The ray path proceeding in and outwards direction in the stellar atmosphere. 

In this case, the assumed a ray path is starting from deep inside the star and we take $\tau_{\nu , 0} = \infty$
Then Eq. 16 becomes, 
$$\tag{17} I_{\nu} (\tau_{\nu}, \mu ) = \int_{\tau_{\nu}}^{\infty} s_{\nu} \ e^{-(\frac{\tau_{\nu}' - \tau_{\nu}}{\mu})} \frac{d \tau_{\nu}'}{\mu}$$
This will be a general solution for case - I


<br>
<br>

Case 2 : 
$-1 \leq \mu \leq 0 \Rightarrow$ Ray path is going inward to the star and we can assume $\tau_{\nu,0} = 0$ at the top of stellar atmosphere and $I_{\nu}(0, \mu) = 0$

Eq. 16 becomes, 
$$\tag{18} I_{\nu}(\tau_{\nu}, \mu) = \int_{\tau_{\nu}}^{\infty} s_{\nu} \ e^{-(\frac{\tau_{\nu}' - \tau_{\nu}}{-\mu})} \frac{d \tau_{\nu}'}{-\mu}$$

Only obstacle. We have to get the specific intensity at any optical death is unknown source function for both case 1 and 2. 
Further, solution of Eq. 17 and 18 needs information about $s_\nu$

###### <span  style = "color:Orchid">Solution</span>
Recall the Kirchhoff's law : if the stellar atmosphere local thermodynamic equilibrium, then the source function can be written as $s_{\nu}=B_{\nu}(T)$

Now, we want to find out the source function at any optical depth $\tau_\nu$ and the material there is in it.  Then $s_{\nu} = B_{\nu} (T(\tau_{\nu})) \approx B_{\nu}(\tau_{\nu})$ (for simplification). 

Hence, source function at a nearby point with optical depth $\tau_{\nu}'$ can be written as 
$$\tag{19} s_{\nu}(\tau_{\nu}') = B_\nu(\tau_{\nu}) + (\tau_{\nu}' - \tau_{\nu}) \frac{dB_{\nu}}{{d}\tau_{\nu}}$$

This is the source function in equation 17 and 18. 
For the ray path with $\text{+ve} \ \mu$ and $\text{-ve}\ \mu$ to obtain the specific intensity. 
$$\tag{20} I_{\nu}(\tau_{\nu}, \mu) = B_{\nu}(\tau_{\nu}) \ + \ \mu \frac{dB_{\nu}}{d \tau_{\nu}}$$
provided $\tau_{\nu} >> 1$ and $e^{-\tau_{\nu}} \approx 0$

Again, if you recall the previous class of blackbody radiation, $I_{\nu} \approx B_{\nu}(\tau_{\nu})$ but in the presence of material, there is an extra term which takes care of the deviations from blackbody radiation and gives rise to anisotropy in the radiation field

##### <span  style = "color:SpringGreen">Fluxes, Energy density and Pressure due to radiation field passing through the stellar atmosphere</span>
Things you learn from lecture 3 will be handy now to calculate this quantity as you know how the $I_{\nu}(\tau_{\nu}, \mu)$ looks like.

As we learned already in the previous class, how to calculate each quantity. Now we will just follow that 
$$\text{Energy Density} = \frac{1}{c} \int_{}^{} I_{\nu} \  d \Omega$$
$$F_{\nu} = \int I_{\nu} \cos \theta \ d \Omega$$
$$P_{\nu}= \frac{1}{c} \ \int I_{\nu} \cos^{2} \theta \ d \Omega$$

Note : if a quantity $I(\cos \theta)$ or $I(\mu)$ is any function of angle in a plane parallel atmosphere, then, 
$$\int I(\cos \theta) \ d \Omega = \int_{\theta = 0}^{\pi} \int_{\phi = 0}^{2 \pi} I(\cos \theta) \ d \theta \ d \phi$$
$$ = 2 \pi \int_{-1}^{+1} I(\mu) \ d \mu$$

Hence, it gives, 
$$U_{\nu}= \frac{2 \pi}{c} \int_{-1}^{+1} I_{\nu} (\mu) d \mu \ \ = \ \ \frac{4 \pi}{c} B_\nu(\tau_{\nu})$$
$$F_{\nu}= {2 \pi} \int_{-1}^{+1} I_{\nu} (\mu)  \mu \ d \mu \ \ = \ \ \frac{4 \pi}{3} \frac{d B_{\nu}}{d \tau_{\nu}}$$
and, 
$$P_{\nu}= \frac{2 pi}{c} \int_{-1}^{+1} I_{\nu} \ \mu^2 \ d \mu$$
$$ = \frac{4 \pi}{3c} B_{\nu}(\tau_{\nu})$$

Anisotropy in the radiation can be measured as
$$\left( \frac{d B_{\nu }}{ d \tau_{\nu}} \right) \frac{1}{B_{\nu}} \approx \frac{3 F_{\nu}}{c \ U_\nu}$$

If we consider the flux all over the wavelength then, 
$$F_{\nu} \approx F  \ \ \ , \ \ \ U_{\nu} \approx U$$
$$\text{Anisotropy} = \frac{3F}{c\ U} = \approx \frac{\sigma \ T_{eff}^4}{a \ T^4}$$
This is the measure of anisotropy in the field. 

###### <span  style = "color:Orchid">Note :</span>
Eq. 20 gives us how the radiation field varies in the stellar atmosphere and to know that we need to know how temperature varies within the atmosphere which is not known apriori in general and gives us huge challenge to study stellar atmosphere



