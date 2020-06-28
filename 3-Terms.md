# Electrical terms

## Electrical impedance

In electrical engineering, _electrical impedance_ is the measure of the _opposition_ that a circuit presents to a current when a voltage is applied.

Quantitatively, the impedance of a two-terminal circuit element is the _ratio_ of the complex representation of the _sinusoidal voltage between its terminals_, to the complex representation of the _current_ flowing through it. In general, it depends upon the _frequency of the sinusoidal voltage_.

Impedance extends the concept of _resistance_ to _alternating current (`AC`) circuits_, and possesses both _magnitude_ and _phase_, unlike resistance, which has only magnitude. When a circuit is driven with _direct current_ (`DC`), there is _no distinction between impedance and resistance_; the latter can be thought of as _impedance with zero phase angle_.

Impedance is a _complex number_, with the _same units as resistance_, for which the SI unit is the _ohm_ (`Ω`). Its symbol is usually `Z`, and it may be represented by writing its magnitude and phase in the polar form |Z|∠θ. However, cartesian complex number representation is often more powerful for circuit analysis purposes.

The notion of impedance is useful for performing AC analysis of electrical networks, because it allows relating sinusoidal voltages and currents by a simple linear law. In multiple port networks, the two-terminal definition of impedance is inadequate, but the complex voltages at the ports and the currents flowing through them are still linearly related by the impedance matrix.

The reciprocal of _impedance_ is _admittance_, whose SI unit is the _siemens_, formerly called _mho_.

Instruments used to measure the electrical impedance are called _impedance analyzers_.

The term impedance was coined by _Oliver Heaviside_ in July 1886. _Arthur Kennelly_ was the first to represent impedance with complex numbers in 1893.

In addition to resistance as seen in `DC` circuits, impedance in `AC` circuits includes the effects of the induction of voltages in conductors by the _magnetic fields_ (_inductance_), and the electrostatic storage of charge induced by voltages between _conductors_ (_capacitance_).

The impedance caused by these two effects is collectively referred to as _reactance_ and forms the _imaginary part of complex impedance_ whereas _resistance_ forms the _real part_.

Impedance is defined as the frequency domain ratio of the voltage to the current. In other words, it is the voltage–current ratio for a single complex exponential at a particular frequency `ω`.

For a sinusoidal current or voltage input, the polar form of the complex impedance relates the amplitude and phase of the voltage and current. In particular:

The magnitude of the complex impedance is the ratio of the voltage amplitude to the current amplitude;

The phase of the complex impedance is the phase shift by which the current lags the voltage.

The impedance of a two-terminal circuit element is represented as a complex quantity `Z`

The _polar form_ conveniently captures both magnitude and phase characteristics as

$$
\ Z=|Z|e^{j\arg(Z)}
$$

where the magnitude `|Z|` represents the ratio of the voltage difference amplitude to the current amplitude, while the argument `arg(Z)` (commonly given the symbol `theta` gives the phase difference between voltage and current. `j` is the _imaginary unit_, and is used instead of `i` in this context to avoid confusion with the symbol for electric current.

In Cartesian form, impedance is defined as

$$
\ Z=R+jX
$$

Where the _real part_ of impedance is the resistance `R` and the _imaginary part_ is the reactance `X`.

To simplify calculations, sinusoidal voltage and current waves are commonly represented as complex-valued functions of time denoted as

$$
{\displaystyle V\ and\ I}.
$$

$$
{\displaystyle {\begin{aligned}V&=|V|e^{j(\omega t+\phi _{V})},\\I&=|I|e^{j(\omega t+\phi _{I})}.\end{aligned}}}{\displaystyle {\begin{aligned}V&=|V|e^{j(\omega t+\phi _{V})},\\I&=|I|e^{j(\omega t+\phi _{I})}.\end{aligned}}}
$$

The impedance of a bipolar circuit is defined as the ratio of these quantities:

$$
{\displaystyle Z={\frac {V}{I}}={\frac {|V|}{|I|}}e^{j(\phi _{V}-\phi _{I})}.}{\displaystyle Z={\frac {V}{I}}={\frac {|V|}{|I|}}e^{j(\phi _{V}-\phi _{I})}.}
$$

Hence, denoting ${\displaystyle \theta =\phi _{V}-\phi _{I}}{\displaystyle \theta =\phi _{V}-\phi _{I}}$, we have

$$
{\displaystyle {\begin{aligned}|V|&=|I||Z|,\\\phi _{V}&=\phi _{I}+\theta .\end{aligned}}}{\displaystyle {\begin{aligned}|V|&=|I||Z|,\\\phi _{V}&=\phi _{I}+\theta .\end{aligned}}}
$$

The magnitude equation is the familiar Ohm's law applied to the voltage and current amplitudes, while the second equation defines the phase relationship.

Validity of complex representation
This representation using complex exponentials may be justified by noting that (by Euler's formula):

$$
{\displaystyle \ \cos(\omega t+\phi )={\frac {1}{2}}{\Big [}e^{j(\omega t+\phi )}+e^{-j(\omega t+\phi )}{\Big ]}}\ \cos(\omega t+\phi )={\frac {1}{2}}{\Big [}e^{j(\omega t+\phi )}+e^{-j(\omega t+\phi )}{\Big ]}
$$

The real-valued sinusoidal function representing either voltage or current may be broken into two complex-valued functions. By the principle of superposition, we may analyse the behaviour of the sinusoid on the left-hand side by analysing the behaviour of the two complex terms on the right-hand side. Given the symmetry, we only need to perform the analysis for one right-hand term. The results are identical for the other. At the end of any calculation, we may return to real-valued sinusoids by further noting that

$$
{\displaystyle \ \cos(\omega t+\phi )=\Re {\Big \{}e^{j(\omega t+\phi )}{\Big \}}}\ \cos(\omega t+\phi )=\Re {\Big \{}e^{j(\omega t+\phi )}{\Big \}}
$$

## Electric current

An electric current is the rate of flow of electric charge past a pointor region. An electric current is said to exist when there is a net flow of electric charge through a region.

Electric charge is carried by charged particles, so an electric current is a flow of charged particles. The moving particles are called charge carriers, and in different conductors may be different types of particle. In electric circuits the charge carriers are often electrons moving through a wire. In an electrolyte the charge carriers are ions, and in an ionized gas (plasma) are ions and electrons.

The _SI_ unit of electric current is the `ampere`, which is the flow of electric charge across a surface at the rate of one coulomb per second. The ampere (symbol: `A`) is an _SI_ base unit. Electric current is measured using a device called an _ammeter_.

Electric currents cause `Joule` heating, which creates light in incandescent light bulbs. They also create magnetic fields, which are used in motors, generators, inductors, and transformers.

The conventional symbol for current is I, which originates from the French phrase intensité du courant, (current intensity). Current intensity is often referred to simply as current.

The `I` symbol was used by _André-Marie Ampère_, after whom the unit of electric current is named, in formulating Ampère's force law (1820).

## Electric potential

An _electric potential_ (also called the _electric field potential_, potential drop or the electrostatic potential) is the:

_Amount of work needed to move a unit of charge from a reference point to a specific point inside the field without producing an acceleration._

Typically, the reference point is the Earth or a point at infinity, although any point can be used.

In classical electrostatics, the electrostatic field is a vector quantity which is expressed as the gradient of the electrostatic potential, which is a scalar quantity denoted by `V` or occasionally `φ`, equal to the electric potential energy of any charged particle at any location (measured in joules) divided by the charge of that particle (measured in coulombs).

By dividing out the charge on the particle a quotient is obtained that is a property of the electric field itself. In short, electric potential is the electric potential energy per unit charge.

This value can be calculated in either a static (time-invariant) or a dynamic (varying with time) electric field at a specific time in units of joules per coulomb (`J⋅C−1`), or volts (`V`). The electric potential at infinity is assumed to be zero.

In electrodynamics, when time-varying fields are present, the electric field cannot be expressed only in terms of a scalar potential.

Instead, the electric field can be expressed in terms of both the scalar electric potential and the magnetic vector potential.

The electric potential and the magnetic vector potential together form a four vector, so that the two kinds of potential are mixed under Lorentz transformations.

Practically, electric potential is always a continuous function in space; Otherwise, the spatial derivative of it will yield a field with infinite magnitude, which is practically impossible.

Even an idealized point charge has `1/r` potential, which is continuous everywhere except the origin. The electric field is not continuous across an idealized surface charge, but it is not infinite at any point.

Therefore, the electric potential is continuous across an idealized surface charge. An idealized linear charge has `ln(r)` potential, which is continuous everywhere except on the linear charge.

The electric potential at a point `r` in a static electric field `E` is given by the line integral

$$
\displaystyle \mathbf V*\mathbf{E} = - \int*{C} E \cdot dl \,
$$

where `C` is an arbitrary path connecting the point with zero potential to `r`. When the curl `∇ × E` is zero `0`, the line integral above does not depend on the specific path `C` chosen but only on its endpoints. In this case, the electric field is conservative and determined by the gradient of the potential:

$$
\displaystyle \mathbf E = - {\nabla } V\_\mathbf{E} \,
$$

Then, by Gauss's law, the potential satisfies Poisson's equation:

$$
{\displaystyle \mathbf {E} =\mathbf {\nabla } \cdot \left(-\mathbf {\nabla } V*{\mathbf {E} }\right)=-\nabla ^{2}V*{\mathbf {E} }=\rho /\varepsilon _{0},\,}\mathbf{\nabla} \cdot \mathbf{E} = \mathbf{\nabla} \cdot \left (- \mathbf{\nabla} V_\mathbf{E} \right ) = -\nabla^2 V\_\mathbf{E} = \rho / \varepsilon_0, \,
$$

Where ρ is the total charge density (including bound charge) and ∇· denotes the divergence.

The concept of electric potential is closely linked with potential energy. A test charge q has an electric potential energy UE given by

$$
{\displaystyle U*{\mathbf {E} }=q\,V.\,}U* \mathbf{E} = q\,V. \,
$$

The potential energy and hence also the electric potential is only defined up to an additive constant: one must arbitrarily choose a position where the potential energy and the electric potential are zero.

These equations cannot be used if the curl `∇ × E ≠ 0`, i.e., in the case of a non-conservative electric field (caused by a changing magnetic field; see Maxwell's equations). The generalization of electric potential to this case is described below.

## Electromotive force

In electromagnetism and electronics, electromotive force (emf, denoted ${\displaystyle }{\mathcal {E}}$ and measured in volts), is the electrical action produced by a non-electrical source. Devices (known as transducers) provide an emf by converting other forms of energy into electrical energy, such as batteries (which convert chemical energy) or generators (which convert mechanical energy). Sometimes an analogy to water pressure is used to describe electromotive force. (The word "force" in this case is not used to mean forces of interaction between bodies).

In electromagnetic induction, emf can be defined around a closed loop of conductor as the electromagnetic work that would be done on an electric charge (an electron in this instance) if it travels once around the loop. For a time-varying magnetic flux linking a loop, the electric potential's scalar field is not defined due to a circulating electric vector field, but an emf nevertheless does work that can be measured as a virtual electric potential around the loop.

In the case of a two-terminal device (such as an electrochemical cell) which is modeled as a Thévenin's equivalent circuit, the equivalent emf can be measured as the open-circuit potential difference, or voltage, between the two terminals. This potential difference can drive an electric current if an external circuit is attached to the terminals, in which case the device becomes the voltage source of that circuit.

Electromotive force is often denoted by ${\displaystyle }{\mathcal {E}}$ or ℰ

In a device without internal resistance, if an electric charge Q passes through that device, and gains an energy W, the net emf for that device is the energy gained per unit charge, or W/Q. Like other measures of energy per charge, emf uses the SI unit volt, which is equivalent to a joule per coulomb.[12]

Electromotive force in electrostatic units is the statvolt (in the centimeter gram second system of units equal in amount to an erg per electrostatic unit of charge).

Inside a source of emf that is open-circuited, the conservative electrostatic field created by separation of charge exactly cancels the forces producing the emf. Thus, the emf has the same value but opposite sign as the integral of the electric field aligned with an internal path between two terminals A and B of a source of emf in open-circuit condition (the path is taken from the negative terminal to the positive terminal to yield a positive emf, indicating work done on the electrons moving in the circuit).

$$
{\mathcal {E}}=-\int _{A}^{B}{\boldsymbol {E}}_{\mathrm {cs} }\cdot \mathrm {d} {\boldsymbol {\ell }}\,
$$

## Ohm's Law

_Ohm's law_ states that:

_the current through a conductor between two points is directly proportional to the voltage across the two points._

Introducing the constant of proportionality, the resistance, one arrives at the usual mathematical equation that describes this relationship

$I={\frac {V}{R}}$

where `I` is the current through the conductor in units of amperes, `V` is the voltage measured across the conductor in units of volts, and `R` is the resistance of the conductor in units of ohms.

More specifically, _Ohm's law_ states that the `R` in this relation is constant, independent of the current. _Ohm's law_ is an empirical relation which accurately describes the conductivity of the vast majority of electrically conductive materials over many orders of magnitude of current.

However some materials do not obey Ohm's law, these are called _non-ohmic_.

The law was named after the German physicist _Georg Ohm_, who, in a treatise published in 1827, described measurements of applied voltage and current through simple electrical circuits containing various lengths of wire. Ohm explained his experimental results by a slightly more complex equation than the modern form above.

In physics, the term _Ohm's law_ is also used to refer to various generalizations of the law; for example the vector form of the law used in electromagnetics and material science:

${\displaystyle \mathbf {J} =\sigma \mathbf {E} ,}\mathbf {J} =\sigma \mathbf {E} ,$

Where `J` is the current density at a given location in a resistive material, `E` is the electric field at that location, and `σ` (sigma) is a material-dependent parameter called the _conductivity_.
