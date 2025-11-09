# Stationary-Tangential-Pumping-Liquid-Metal-Liner-for-Magnetized-Target-Fusion
This paper proposes a stationary, tangential-pumping configuration that achieves equivalent azimuthal flow and liner shaping without mechanical rotation



Conceptual White Paper: Stationary Tangential-Pumping Liquid Metal Liner for Magnetized Target Fusion



Abstract


General Fusion’s liquid metal–piston compression approach represents one of the most visible Magnetized Target Fusion (MTF) efforts. However, its reliance on a mechanically rotating liquid metal (LM) liner introduces scaling challenges tied to high-speed rotation, vacuum-sealed rotary joints, and precise piston timing. This paper proposes a stationary, tangential-pumping configuration that achieves equivalent azimuthal flow and liner shaping without mechanical rotation, rotary vacuum joints, or moving seals. Sequentially actuated pistons drive tangential flow within a stationary vessel, generating a rotating liquid metal shell for plasma compression. This design eliminates major mechanical failure modes and simplifies scaling to reactor-relevant dimensions.




1. Background and Motivation


General Fusion’s LM26 device demonstrates a promising intermediate step toward practical MTF. Its architecture—combining synchronized pneumatic pistons with a rotating liquid metal liner—has shown the potential to form and compress magnetized plasmas with millisecond precision.

However, several core engineering barriers limit scalability:

Rotational inertia and synchronization: Scaling up to reactor-sized systems multiplies mechanical stresses and demands unprecedented timing accuracy across hundreds of pistons.
Gas-tight rotary joints: The interface between the rotating compression sphere and stationary pneumatic drives must maintain ultra-high vacuum and handle plasma-compatible materials under cyclic loading—an inherently difficult task.
Thermal management: Differential heating between stationary drive systems and rotating containment structures complicates coolant routing and structural integrity.
Economic scalability: The mechanical and precision control complexity scales super-linearly with reactor size, posing financial and reliability risks.


The proposed stationary concept addresses these limitations by decoupling fluid rotation from mechanical rotation, using hydrodynamic control rather than moving assemblies.




2. Stationary Tangential-Pumping Concept Overview


In the stationary configuration, the fusion vessel and all external components remain static. Instead of spinning the liquid metal liner mechanically, tangentially oriented piston tubes inject and withdraw liquid metal to impart azimuthal angular momentum within the liner layer.


Key Elements


Stationary spherical or spheroidal vessel with inner walls lined by a liquid metal (e.g., Pb–Li or Ga–In–Sn).
Tangential piston ports arranged symmetrically around the equator or distributed hemispherically.
Sequential actuation of pistons to create controlled azimuthal flow patterns, effectively generating a rotating liquid metal shell while the vessel remains stationary.
Pulsed compression sequence, where all pistons fire inward quasi-simultaneously after establishing rotation, compressing the central magnetized plasma target.



Advantages


No rotary vacuum joint: All seals remain stationary, vastly improving vacuum reliability and simplifying maintenance.
Reduced mechanical complexity: No massive rotating structures or bearings; drive systems are modular and independently serviceable.
Simplified scaling: Larger systems can be constructed with proportionally more pistons and distributed pumping arrays rather than scaling a single rotating mass.
Improved thermal control: Stationary vessel allows conventional coolant routing and heat exchanger integration.
Dynamic control: Liner rotation rate and compression profile can be tuned via software-controlled piston sequencing rather than fixed mechanical rotation.





3. Physics and Fluid Dynamics Considerations


The concept relies on controlled injection momentum from tangential pistons to generate a stable, rotating liquid metal layer. CFD modeling indicates that azimuthal velocity can be maintained through timed actuation cycles, with viscous coupling between sequentially pulsed jets preserving coherence of the liner’s rotation.

During compression:

The azimuthal motion provides centrifugal stabilization and magnetic flux trapping, akin to the rotating configuration.
Pulsed inward compression proceeds while maintaining flow symmetry, minimizing Rayleigh–Taylor instabilities at the plasma–metal interface.
After compression and energy release, the liner re-expands, and the tangential flow is re-established for the next cycle.





4. Engineering Feasibility


Key subsystem simplifications include:

Piston systems: Standard pneumatic or hydraulic drivers with stationary seals, similar to LM26’s proven components.
Vacuum containment: Continuous stationary barrier, compatible with standard high-vacuum practices.
Maintenance: Modular replacement of piston assemblies without disturbing core alignment.
Diagnostics access: Easier integration of probes and optics due to lack of rotating structures.


Potential challenges include:

Achieving uniform azimuthal flow without full mechanical rotation.
Managing localized shear heating in tangential flow zones.
Synchronizing piston firing sequences across large numbers of actuators.


6. Development Pathway


A practical roadmap to demonstrate feasibility would proceed as follows:

Bench-scale hydrodynamic validation using transparent analog fluids (e.g., gallium or silicone oils) to measure flow stability and liner rotation profiles.
Numerical simulation with coupled CFD–MHD models to predict plasma-liner interaction under tangential pumping.
Small-scale plasma compression trials using stationary metal liners to confirm confinement symmetry and flux conservation.
Integration of full tangential-piston array for continuous operation cycles.





7. Conclusion


The stationary tangential-pumping liquid metal liner concept offers a promising alternative to mechanically rotating MTF systems. By removing rotary vacuum interfaces and leveraging hydrodynamic rotation through piston sequencing, this design addresses the most challenging scalability barriers identified in systems like LM26. While significant modeling and experimental work remain to validate stability and plasma coupling, the architecture presents a clear pathway toward a mechanically simpler, more maintainable, and potentially more scalable fusion compression platform.




Acknowledgments


This concept builds upon insights from the challenges observed in General Fusion’s LM26 program and broader MTF research, seeking to preserve the physics advantages of rotating liquid metal liners while eliminating the mechanical liabilities of rotation.
