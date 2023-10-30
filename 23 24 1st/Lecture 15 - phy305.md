

<hr>

Book Name : 
Date Started : 17-10-2023
Date Finished :  30-10-2023

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

# <span  style = "color:dodgerblue">White Dwarf and Electron Degeneracy Pressure</span>

The major question $\Longrightarrow$  WHAT IS THE END STATE OF STELLAR COLLAPSE ? 

> The first white dwarf ever found and nearest to us is the SIRIUS-B. 
> It has the orbital period of 50 years

Like all white dwarf, Sirius-B is low luminosity and high temperature , which imply a small radius of about 6000 Km (less than the radius of the earth). Hence, the mean density, $\bar{\rho} = 1 \text{ ton}/ \text{cm}^3$

Our aim is now to work out basic physics of white dwarfs and matter at these extreme densities.

#### <span  style = "color:Tomato">What happens to the matter at quantum densities ? </span>
![[Screenshot 2023-10-17 at 4.38.25 PM.png]]
$$\Downarrow$$
To get an idea of the conditions under which this happens , we need to calculate the de-Broglie wavelength of a particle with momentum $p$ which can be written as 
$$\lambda = \frac{h}{p} = \frac{h}{\sqrt{2mE}} = \frac{h}{(2m \cdot \frac{3}{2}kT)^\frac{1}{2}}$$
$$= \frac{h}{(3mkT)^\frac{1}{2}}$$

If we consider electron and proton in temperature $T$, then electron and proton shares same energy but as electrons are lighter, their wavelength becomes larger and it is the electron density that will first reach the quantum domain. 

At inter-particle separations of order less than than the half a de Broglie wavelength, quantum effects should become important. The density corresponding to that would be 
$$\rho_{q}= \frac{m_{p}}{(\lambda / 2)^{3}}= \frac{m_{p}\times8m_p(3mkT)^{\frac{3}{2}}}{h^3}$$

Let us determine its numerical value 
![[Screenshot 2023-10-17 at 4.51.19 PM.png]]
This is the required density for the matter to go to  quantum domain. Below this value , gas remains in the classical regimen. 
##### <span  style = "color:SpringGreen">NOTE !!!</span>
![[Screenshot 2023-10-17 at 4.52.28 PM.png]]


## <span  style = "color:PaleGreen">Equation of state of a degenerate electron gas </span>
![[Screenshot 2023-10-17 at 4.55.28 PM.png]]
![[Screenshot 2023-10-17 at 4.56.35 PM.png]]

$$\Downarrow$$
Another interpretation of Heisenberg uncertainty principle is that two identical particles that are in same phase space cell are in the same quantum state. 
$$\Downarrow$$
Further , according to Pauli's Exclusion principle, two identical fermions cannot occupy the same quantum state. 

Hence, the electrons that are closely packed and localised into a small volume $dV$ must have a large uncertainty in momentum and have momenta $P$ that are different from those of the other fermions in the volume. This necessarily pushes the fermions to a large $p's$ and large momenta implies large/strong pressure. 
Spin of electron is $, s = \frac{1}{2}$

![[Screenshot 2023-10-17 at 5.04.28 PM.png]]

The Fermi - Dirac phase space distribution for an ideal gas of fermions is 
$$dN = \frac{2s + 1}{\exp(\frac{E - \mu(T)}{kT})-1} \frac{d^3pdV}{h^3}$$

where $s$ is the spin of each fermions in unit of $h$ and $\mu(T)$ is the chemical potential of the gas 

<hr> 

$\bbox[8px, border: 8px solid red] {\text{Digression : Recalling what is Chemical Potential of the Gas }}$

<figure>
<center>
<img src="https://qph.cf2.quoracdn.net/main-qimg-a3f79d682beb13bc4ce9a6fd371c7655.webp" alt="" style="width:100%">
<figcaption align = "center">
<b>Chemical Potential</b>
</figcaption>
</center>
</figure>

<hr>

Interesting fact : 
When $T \rightarrow 0$, then $\mu(T)$ approaches an asymptote value, e.g. when $kT << E_f$, then $f(E) = \frac{2s + 1}{\exp(\frac{E - \mu(T)}{kT})-1}$ approaches a step function, in which all the particles occupy the lowest energy states possible without violation of Pauli's principle. 
![[Screenshot 2023-10-17 at 5.19.33 PM.png]]

$$\Downarrow$$
This means that all energy states upto $E_f$ are occupied and all above $E_f$ are empty. Under such conditions, the gas is called <u>degenerate. </u> 
For degenerate electrons, having an isotropic velocity fields, the phase space distribution will be 
![[Screenshot 2023-10-17 at 5.23.08 PM.png]]
$$\Downarrow$$
Further, we can divide the above equation by $dV$ to get the number density of electrons of a given momentum $p$ as given below
![[Screenshot 2023-10-17 at 5.24.54 PM.png]]
<span  style = "color:lightgreen">Above equation is for the : Total number of electrons in the degenerate state</span>

$$\Downarrow$$
Now let us derive a general expression for the pressure exerted by any ideal gas (basic 10+2 class calculations)
![[Screenshot 2023-10-17 at 5.26.45 PM.png]]
The particles in ideal gas only interact at the short distances and hence can transfer momentum only during an impact with another particle.
$$\Downarrow$$
Now let us assume the particles in the ideal gas impinging on the side of a container with a mean interval of $dt$ between two consecutive impacts and let us choose $x$ axis perpendicular to the surface. 
$$\Downarrow$$
Particles with an $x$ component of momentum $p_x$ will transfer $2p_x$ amount of momentum to the surface with each reflection. The force per unit area due to each collision is then, 
![[Screenshot 2023-10-17 at 5.32.32 PM.png]]
where  we put $\frac{dx}{dt} = v_x$
$$\Downarrow$$
Hence, the pressure is obtained by summing the forces due to all particles of all momenta. 
$$\Downarrow$$
![[Screenshot 2023-10-17 at 5.34.12 PM.png]]
$$\Downarrow$$
Pressure  Equation becomes $\longrightarrow$
$$P = \frac{1}{3} \int_{0}^{\infty} \frac{dN(p)}{dV} p\ v\ dp$$
$$= \frac{1}{3}\int_{0}^{\infty} n(p)\  p\ v\ dp$$

Note : If we use $n(p)$ from the classical Maxwell - Boltzmann distribution, we recover classical equation of state $P = nkT$
![[Screenshot 2023-10-17 at 5.41.17 PM.png]] 
$$P_{e}= (\frac{3}{8\pi})^{\frac{2}{3}} \frac{h^2}{5m_{e}}n_{e}^\frac{5}{3}$$
where $n_{e} = \frac{8\pi}{3h^{3}} {p_f}^3$

![[Screenshot 2023-10-17 at 5.46.30 PM.png]]

$$\Downarrow$$
Further , the electron degeneracy pressure is obtained as 
$$\tag{Degeneracy pressure}P_{e}= \Bigg( {\frac{3}{\pi}}\Bigg)\Bigg({\frac{h^2}{20 m_{e} {m_{p}}^{5/3}}} \Bigg)\Bigg({\frac{Z}{A}} \Bigg)^{\frac{5}{3}}\rho^{5/3}$$

$\bbox[28px, border: 6px solid red] {\text{Feature }}$
Electron pressure does not depend on the temperature . 
This is quite intuitive because in our derivation, we have assumed that $KT$ is effectively zero ($KT$ is very low compared to the energy of the most energetic electrons at the Fermi Energy, which are prevented from occupying lower energy states by the Pauli principle)

In a typical white dwarf , $\rho \sim 10^{6}\text{g} \text{ cm}^{-3}, T \sim 10^{7} \text{ K}$.
White dwarfs are generally composed of material that was processed by nuclear reactions into helium, carbon and oxygen and we can take $\frac{Z}{A} = 0.5$ , or $\frac{A}{Z} = 2$. 
Plugging these numbers in pressure (electron degeneracy), we have 
![[Screenshot 2023-10-30 at 10.52.16 AM.png]]

$$\Downarrow$$
As opposed to the electrons, the nuclei at such densities are still completely in the classical regime and we can calculate the thermal pressure due to the nuclei assuming a helium composition. 

![[Screenshot 2023-10-30 at 10.54.02 AM.png]]
$$\Downarrow$$
==The degenerate electron pressure completely dominates the pressure in the white dwarf.==


### <span  style = "color:AquaMarine">White Dwarf Properties </span>
Now we want  to couple the equation of state of the degenerate electron pressure with the other equation of stellar structure for finding out different properties of the white dwarf. 

##### <span  style = "color:SpringGreen">Mass Radius Relationship</span>
![[Screenshot 2023-10-30 at 10.58.10 AM.png]]

$$\Downarrow$$
For the degenerate electron gas equation of state is 
$$\tag{3} P \sim b \ p^{\frac{5}{3}} \sim b \frac{M^{5/3}}{r^5}$$
where $b$ is given by the constant in the electron degenerate pressure.

![[Screenshot 2023-10-30 at 11.00.25 AM.png]]

$$\Downarrow$$
In other words, the radius of a white dwarf decreases with increasing mass. An order of magnitude estimate of radius would be as given above in the screenshot. 