<hr>

Book Name : 
Date Started : 05-08-2023
Date Finished : 08-08-2023



<hr>

### <span  style = "color:Plum">Suggested Links </span>
+ 

<hr>


### <span  style = "color:dodgerblue">Questions to track/remember </span>
+ 1 AU (astronomical unit) = $1.496 \times 10^{11}$ m



<hr>


Sections : 
+ [[Celestial Mechanics#^84c18d|Elliptical Orbit]]
+ [[Celestial Mechanics#^a555d5|Newtonian Mechanics]] ^cec6ca
+ [[Celestial Mechanics#^6389de|Keplar's Law Derived]]
+ [[Celestial Mechanics#^5abb58|The Virial Theorem]] ^866cf1

<hr>


## <span  style = "color:AquaMarine">Elliptical Orbit</span>


### <span  style = "color:Tomato">Tycho Brahe - The great naked - eye Observer</span>

Though meticulous he was, he was not able to find any substantiating result that Copernican theory was right according to his experiments and thus concluded the theory to be wrong. He was a geocentrist wanting to prove heliocentric nature of universe. 

<hr> 


### <span  style = "color:Tomato">Keplar's Law of Planetary Motion</span>
Keplar was a heliocentrist but wanted to prove and strengthen the geocentrist model, as it was much believed back then, such as Brahe's. 

<figure>
<center>
<img src="https://www.sciencefacts.net/wp-content/uploads/2022/04/Keplers-Laws.jpg" alt="" style="width:100%">
<figcaption align = "center">
<p>The third law is also called Harmonic Law. <br> T is measured in years</p>
</figcaption>
</center>
</figure>

<hr> 



### <span  style = "color:Tomato">The Geometry of Elliptical Motion</span>

[[Short course on Elliptical Geometry]] ^84c18d

>  The geometry of the Ellipse explained 
<figure>
<center>
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20210226214327/ellipse.png" alt="" style="width:80%">
<figcaption align = "center">
</figcaption>
</center>
</figure>

For above ellipse , we also have $$ b^2 = a^2(1 - e^2) $$ and like wise , $2a$ defines here semi-major axis and $2b$ defines the semi-minor axis. 
And total area of ellipse is given by $A = \pi \times a \times b$

##### <span  style = "color:dodgerblue">A latus rectum</span> 

^5b2329

is a straight line passing through the focus of the parabola and is perpendicular to the axis of the parabola. The latus rectum of the parabola is the focal chord which is parallel to the directrix of a parabola. The prabola has only one latus rectum, but the ellipse and hyperbole have two latus rectums.

> ## Trivia
> The <b style = "color:red">eccentricity</b> is measured by the distance between the foci and the center of the conic section. 
> In above figure the eccentricity will be the distance between the centre $O$ and the point on semimajor axis where the latus rectum cuts the axis. 
> - Eccentricity of Circle = 0 (i.e.) e =0.
>- Eccentricity of Line = Infinity (i.e.) e =1.
>- Eccentricity of Parabola = 1(i.e.) e =1.
>- Eccentricity of Ellipse = Between 0 and 1 (i.e.) 0 <e <1.
>- Eccentricity of Hyperbola = Greater than 1(i.e.) e > 1

So , when we say the orbit is elliptical we are also establishing that the sun is at one of the foci. Well in that case the the closes point will be called <b style = "color:red">Perihelion</b> or $(\theta = 0 \degree)$ and the farther point is called <b style = "color:red">Apehelion</b> or $(\theta = 180 \degree)$ ^e6dfa6

![[Screenshot 2023-08-07 at 7.57.08 PM.png]]
+ Here the $r + r' = 2a$  and for $(0 \le e \leq 1)$ thus for <b style = "color:red">for case of planets</b> which have elliptical orbit gives us following equations a
$$ r = \frac{a(1 - e^2)}{1 + e \cos{\theta}} $$
+ and likewise for<b style = "color:red"> case of comet</b> which have a parabolic resemblance $(e = 1)$ for the orbit, we have 
$$ r = \frac{2p}{1 +  \cos{\theta}} $$ 
Here, $p$ is the distance of closest approach to the parabola’s  $one$ focus at $\theta = 0$.
<br>

+ and further for<b style = "color:red"> case of Hyperbolas </b>  $(e > 1)$ for the orbit, we have 
$$ r = \frac{a(e^2- 1 )}{1 +  e \cos{\theta}} $$ 

<hr>




## <span  style = "color:AquaMarine">Newtonian Mechanics</span>

^a555d5
+ First Law - The law of Inertia - The momentum of the object remains same unless it is subjected to an external force. 
+ Second Law - The <em>net</em> force (the sum of all forces) acting on an object is proportional to the object’s mass and its resultant acceleration. $$F = m \cdot a$$ $$F_{net} = \frac{d \vec{p}}{dt}$$

#### <span  style = "color:dodgerblue">Law of Universal Gravitation</span>
![[gravitation formula proof.pdf|50x50]]

Similarly, the gravitation pull on the object of the earth is given as the foced due to gravity and had a value of $9.8 \ ms^{-2}$. $$ g= G \frac{M}{R^2}$$ where $M$ is the mass of earth as $5.9736 \times 10^{24}$  Kg. 
and $R$ is the radius of the earth as $6.378136 \times 10^6$ m.

> ## Trivia
> Brachistochrone problem was given a deadline of one and half year for its solution. Newton was randomly introduced to the problem one evening and by the next morning, he had found out the solution of the problem and along with that he had introduced a new field of mathematics called <b style = "color:red">calculus of variation</b>
> Newton was a effing genius. 
> The problem was given by Johann Bernoulli and Newton pulbished the solution anonymously but it was not a delay to recognise that it was Newton who solved it and hence the quote `by the claw, the lion is revealed`


### <span  style = "color:dodgerblue">Work and Energy </span>
Potential Energy , $U = -G \cdot \frac{Mm}{r}$ 
and also the forces can be found by differentiating, $F = \frac{\partial U}{\partial r}$ which is also represented as $F = -\nabla U$ and known as <b style = "color:red">Gradient of U</b>.

And likewise , the work  must be performed on the massive object if its speed were to change. 
$$ K = \frac{1}{2} mv^2$$
Concept of escape velocity can be derived from here just by equaling the Gravitational energy and Kinetic energy
<hr>

## <span  style = "color:AquaMarine">Keplar's Law Derived</span>

^6389de

When we choose Center of mass of a binary system, we have 
+ reduced mass $\mu = \frac{m_1 \cdot m_2}{m_1  + m_2}$
+ $r_1 = - \frac{\mu}{m_1} r$ (sign is negative)
+ $r_2 = +  \frac{\mu}{m_2} r$ (sign is positive)
<figure>
<center>
<img src="https://cdn1.byjus.com/wp-content/uploads/2021/06/Important-centre-of-mass-formula-1.png" alt="" style="width:80%">
<figcaption align = "center">
<b></b>
</figcaption>
</center>
</figure>

So the total energy of the sytem is given by 
$$E =  \frac{1}{2} m_1 |v_1|^2 + \frac{1}{2} m_2 |v_2|^2 - G \frac{m_1m_2}{|r_2 - r_1|}$$
which can further be written as with the help of reduced mass as 
$$E = \frac{1}{2} \mu v^2  -  G \frac{M \mu}{r}$$
note that $r = |r_2 - r_1|$ here in the equation with reduced masses. 

<br>

![[Pasted image 20230808141747.png|45]] 
The total energy of the system is equal to the kinetic energy of the reduced mass, plus the potential energy of the reduced mass moving about a mass $M$ , assumed to be located and fixed at the origin.

#### <span  style = "color:Coral">Orbital Angular Momentum</span>
Total orbital angular momentum is given by $$L = m_1 r_1 \times v_1 + m_2 r_2 \times v_2 $$
whhich can further be reduced to the following equations, 
$$L = \mu \vec{r} \times \vec{v} = r \times p $$

![[Pasted image 20230808142704.png|20]]  The total orbital angular momentum equals the angular momentum of the reduced mass only.

<hr>

##### <span  style = "color:Coral">Keplar's First law derived</span>
![[keplars 1st law 1.pdf]]

<b style = "color:red">Conic Section</b> - The path of a reduced mass under the infulence of gravity (or any other inverse square law) of another massive body is a conic section.

> For the case of closed of closed planetrary orbits, the total orbital angular momentum is given as $$L = \mu \sqrt{G M a(1- e^2)}$$ and obviously is maximum for $e=0$, i.e. circular motion. 

<hr>

##### <span  style = "color:Coral">Keplar's Second law derived</span>
<figure>
<center>
<img src="https://haygot.s3.amazonaws.com/questions/1883854_1821059_ans_dd25b3625dc64f69b8af18bdca5e170c.jpg" alt="" style="width:80%">
<figcaption align = "center">
<b></b>
</figcaption>
</center>
</figure>

> Further, the energy of a binary orbit system is also to be noted that depend on the semimajor axis $a$ and not on anything else. (Foci are located on semi major axis of the ellipse) $$E = -G \frac{M \mu}{2a} = -G \frac{m_1 m_2}{2a}$$ $$E = \frac{1}{2} \langle U \rangle$$ where $\langle U \rangle$ represents the average over one orbital period and also $\langle U \rangle = - G \frac{M \mu}{a}$ 

<b style = "color:red">Relative velocity of $m_1$ and $m_2$</b>
A useful expression for the velocity of the reduced mass (or the relative velocity of the both bodies ) is $$v^2 = G (m_1 + m_2)\left( \frac{2}{r} - \frac{1}{a} \right)$$

<hr>

##### <span  style = "color:Coral">Keplar's Third law derived</span>
<figure>
<center>
<img src="https://www.researchgate.net/publication/250082824/figure/fig6/AS:668759064842246@1536455994347/Derivation-tree-for-Keplers-third-law-from-the-subtree-in-Figure-3.ppm" alt="" style="width:80%">
<figcaption align = "center">
<b>Keplar's Third Law Derivation</b>
</figcaption>
</center>
</figure>
This is the general form of Kepler’s third law. Not only did Newton demonstrate the re- lationship between the semimajor axis of an elliptical orbit and the orbital period, he also found a term not discovered empirically by Kepler, the square of the orbital period is in- versely proportional to the total mass of the system.

## <span  style = "color:AquaMarine">The Virial Theorem</span>

^5abb58

Earlier we saw that the total energy of the binary orbit system was $E = \frac{1}{2} \langle \text{U} \rangle$. This means that the total energy of the system is necessarily negative i.e system is bound. 
For gravitationally bound systems in equilibrium, it can be shown that the total energy is always one-half of the time-averaged potential energy; this is known as the <b style = "color:magenta">Virial Theorem</b>

<< skipping the proof of the Theorem >> 




