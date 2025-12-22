# Stationary Tangential Pumping Liquid Metal Liner for Magnetized Target Fusion

This paper proposes a stationary, tangential-pumping configuration that achieves equivalent azimuthal flow and liner shaping without mechanical rotation

Conceptual White Paper: Stationary Tangential-Pumping Liquid Metal Liner for Magnetized Target Fusion

⸻

Abstract

General Fusion’s liquid metal–piston compression approach represents one of the most visible Magnetized Target Fusion (MTF) efforts. However, its reliance on a mechanically rotating liquid metal (LM) liner introduces scaling challenges tied to high-speed rotation and vacuum-sealed rotary joints. This paper proposes a stationary, tangential-pumping configuration that achieves equivalent azimuthal flow and liner shaping without mechanical rotation, rotary vacuum joints, or moving seals. Sequentially actuated pistons drive tangential flow within a stationary vessel, generating a rotating liquid metal shell for plasma compression. This design eliminates major mechanical failure modes and simplifies scaling to reactor-relevant dimensions.

⸻

1 Background and Motivation

General Fusion’s LM26 device demonstrates a promising intermediate step toward practical MTF. Its architecture—combining synchronized pneumatic pistons with a rotating liquid metal liner—has shown the potential to form and compress magnetized plasmas with millisecond precision.

However, several core engineering barriers limit scalability:
	•	Rotational inertia and synchronization: Scaling up to reactor-sized systems multiplies mechanical stresses and demands unprecedented timing accuracy across hundreds of pistons.
	•	Gas-tight rotary joints: The interface between the rotating compression sphere and stationary pneumatic drives must maintain ultra-high vacuum and handle plasma-compatible materials under cyclic loading—an inherently difficult task.
	•	Thermal management: Differential heating between stationary drive systems and rotating containment structures complicates coolant routing and structural integrity.
	•	Economic scalability: The mechanical and precision control complexity scales super-linearly with reactor size, posing financial and reliability risks.

The proposed stationary concept addresses these limitations by decoupling fluid rotation from mechanical rotation, using hydrodynamic control rather than moving assemblies.

⸻

2 Stationary Tangential-Pumping Concept Overview

In the stationary configuration, the fusion vessel and all external components remain static. Instead of spinning the liquid metal liner mechanically, tangentially oriented piston tubes inject and recirculate liquid metal to impart azimuthal angular momentum within the liner layer.

Key Elements
	•	Stationary spherical, spheroidal, or cylindrical vessel with inner walls lined by a liquid metal (e.g., Pb–Li or Ga–In–Sn).
	•	Tangential piston ports arranged symmetrically around the equator or distributed hemispherically.
	•	Sequential actuation of pistons to create controlled azimuthal flow patterns, effectively generating a rotating liquid metal shell while the vessel remains stationary.
	•	A cylindrical vessel design allows realization of any rotationally symmetric wall shape by adjusting the corresponding piston pump speeds.
	•	Pulsed compression sequence, where all pistons fire inward quasi-simultaneously after establishing rotation, compressing the central magnetized plasma target.

Advantages
	•	No rotary vacuum joint: All seals remain stationary, vastly improving vacuum reliability and simplifying maintenance.
	•	Reduced mechanical complexity: No massive rotating structures or bearings; drive systems are modular and independently serviceable.
	•	Simplified scaling: Larger systems can be constructed with proportionally more pistons and distributed pumping arrays rather than scaling a single rotating mass.
	•	Improved thermal control: Stationary vessel allows conventional coolant routing and heat exchanger integration.
	•	Dynamic control: Liner rotation rate and compression profile can be tuned via software-controlled piston sequencing rather than fixed mechanical rotation.

⸻

3 Physics and Fluid Dynamics Considerations

The concept relies on controlled injection momentum from tangential pistons to generate a stable, rotating liquid metal layer. CFD modeling indicates that azimuthal velocity can be maintained through timed actuation cycles, provided tangential momentum injection offsets viscous and wall losses, with viscous coupling between sequentially pulsed jets preserving coherence of the liner’s rotation.

During compression, the azimuthal motion provides centrifugal stabilization and magnetic flux trapping, akin to the rotating configuration. Pulsed inward compression proceeds while maintaining flow symmetry, minimizing Rayleigh–Taylor instabilities at the plasma–metal interface. After compression and energy release, the liner re-expands, and the tangential flow is re-established for the next cycle.

During compression, magnetohydrodynamic effects such as induced currents and Lorentz forces may modify azimuthal flow profiles, motivating coupled CFD–MHD analysis to assess stability and angular momentum retention.

Vortex-Assisted Liner Rotation and Compression (Conceptual Extension)

An alternative or complementary mechanism for sustaining azimuthal liquid metal motion involves the deliberate formation of a controlled hydrodynamic vortex, analogous to the well-known bathtub drain vortex. In this configuration, tangential momentum is continuously injected into the liquid metal liner while a coordinated radial or axial flow component induces inward transport of the liquid metal toward the compression region.

Conservation of angular momentum naturally amplifies azimuthal velocity as the effective liner radius decreases, producing a self-organizing rotating shell with a narrowed central cavity. This vortex-driven geometry can inherently reduce the enclosed plasma volume while maintaining rotational stabilization, without requiring mechanical rotation of the vessel or liner.

Periodic or pulsed inward “lid” compression—implemented via synchronized piston actuation—may then be applied to rapidly intensify the vortex and compress the magnetized plasma target. In this regime, liner shaping and compression arise from coupled hydrodynamic effects rather than purely geometric piston convergence, potentially reducing sensitivity to mechanical tolerances.

Such a vortex-assisted mode may offer additional benefits, including:
	•	Continuous regeneration of angular momentum to offset viscous and wall losses
	•	Hydrodynamically determined liner shaping governed by flow conditions rather than fixed structures
	•	Reduced reliance on precise global synchronization, as angular momentum amplification occurs naturally during inward flow

The stability of vortex-assisted liquid metal liners under fusion-relevant magnetic fields and compression rates would require dedicated CFD–MHD modeling and experimental validation. Nevertheless, this approach represents a promising extension of the stationary tangential-pumping concept, leveraging well-understood fluid dynamical principles to enhance liner rotation and plasma compression.

⸻

4 Engineering Feasibility

Key subsystem simplifications include:
	•	Piston systems: Standard pneumatic or hydraulic drivers with stationary seals, similar to LM26’s proven components.
	•	Vacuum containment: Continuous stationary barrier, compatible with standard high-vacuum practices.
	•	Maintenance: Modular replacement of piston assemblies without disturbing core alignment.
	•	Diagnostics access: Easier integration of probes and optics due to lack of rotating structures.

Potential challenges include:
	•	Achieving uniform azimuthal flow without full mechanical rotation.
	•	Managing localized shear heating in tangential flow zones.
	•	Synchronizing piston firing sequences across large numbers of actuators.

⸻

5 Development Pathway

A practical roadmap to demonstrate feasibility would proceed as follows:
	•	Bench-scale hydrodynamic validation using transparent analog fluids (e.g., gallium or silicone oils) to measure flow stability and liner rotation profiles.
	•	Numerical simulation with coupled CFD–MHD models to predict plasma–liner interaction under tangential pumping.
	•	Small-scale plasma compression trials using stationary metal liners to confirm confinement symmetry and flux conservation.
	•	Integration of a full tangential-piston array for continuous operation cycles.

⸻

6 Conclusion

The stationary tangential-pumping liquid metal liner concept offers a promising alternative to mechanically rotating MTF systems. By removing rotary vacuum interfaces and leveraging hydrodynamic rotation through piston sequencing, this design addresses the most challenging scalability barriers identified in systems like LM26. While significant modeling and experimental work remain to validate stability and plasma coupling, the architecture presents a clear pathway toward a mechanically simpler, more maintainable, and potentially more scalable fusion compression platform.

⸻

Acknowledgments

This concept builds upon insights from the challenges observed in General Fusion’s LM26 program and broader MTF research, seeking to preserve the physics advantages of rotating liquid metal liners while eliminating the mechanical liabilities of rotation.




                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

1. Definitions.

   "License" shall mean the terms and conditions for use, reproduction,
   and distribution as defined by Sections 1 through 9 of this document.

   "Licensor" shall mean the copyright owner or entity authorized by
   the copyright owner that is granting the License.

   "Legal Entity" shall mean the union of the acting entity and all
   other entities that control, are controlled by, or are under common
   control with that entity. For the purposes of this definition,
   "control" means (i) the power, direct or indirect, to cause the
   direction or management of such entity, whether by contract or
   otherwise, or (ii) ownership of fifty percent (50%) or more of the
   outstanding shares, or (iii) beneficial ownership of such entity.

   "You" (or "Your") shall mean an individual or Legal Entity exercising
   permissions granted by this License.

   "Source" form shall mean the preferred form for making modifications,
   including but not limited to software source code, documentation
   source, and configuration files.

   "Object" form shall mean any form resulting from mechanical
   transformation or translation of a Source form, including but not
   limited to compiled object code, generated documentation, and
   conversions to other media types.

   "Work" shall mean the work of authorship, whether in Source or
   Object form, made available under the License, as indicated by a
   copyright notice that is included in or attached to the work
   (an example is provided in the Appendix below).

   "Derivative Works" shall mean any work, whether in Source or Object
   form, that is based on (or derived from) the Work and for which the
   editorial revisions, annotations, elaborations, or other modifications
   represent, as a whole, an original work of authorship. For the purposes
   of this License, Derivative Works shall not include works that remain
   separable from, or merely link (or bind by name) to the interfaces of,
   the Work and Derivative Works thereof.

   "Contribution" shall mean any work of authorship, including
   the original version of the Work and any modifications or additions
   to that Work or Derivative Works thereof, that is intentionally
   submitted to Licensor for inclusion in the Work by the copyright owner
   or by an individual or Legal Entity authorized to submit on behalf of
   the copyright owner. For the purposes of this definition, "submitted"
   means any form of electronic, verbal, or written communication sent
   to the Licensor or its representatives, including but not limited to
   communication on electronic mailing lists, source code control systems,
   and issue tracking systems that are managed by, or on behalf of, the
   Licensor for the purpose of discussing and improving the Work, but
   excluding communication that is conspicuously marked or otherwise
   designated in writing by the copyright owner as "Not a Contribution."

   "Contributor" shall mean Licensor and any individual or Legal Entity
   on behalf of whom a Contribution has been received by Licensor and
   subsequently incorporated within the Work.

2. Grant of Copyright License. Subject to the terms and conditions of
   this License, each Contributor hereby grants to You a perpetual,
   worldwide, non-exclusive, no-charge, royalty-free, irrevocable
   copyright license to reproduce, prepare Derivative Works of,
   publicly display, publicly perform, sublicense, and distribute the
   Work and such Derivative Works in Source or Object form.

3. Grant of Patent License. Subject to the terms and conditions of
   this License, each Contributor hereby grants to You a perpetual,
   worldwide, non-exclusive, no-charge, royalty-free, irrevocable
   (except as stated in this section) patent license to make, have made,
   use, offer to sell, sell, import, and otherwise transfer the Work,
   where such license applies only to those patent claims licensable
   by such Contributor that are necessarily infringed by their
   Contribution(s) alone or by combination of their Contribution(s)
   with the Work to which such Contribution(s) was submitted. If You
   institute patent litigation against any entity (including a
   cross-claim or counterclaim in a lawsuit) alleging that the Work
   or a Contribution incorporated within the Work constitutes direct
   or contributory patent infringement, then any patent licenses
   granted to You under this License for that Work shall terminate
   as of the date such litigation is filed.

4. Redistribution. You may reproduce and distribute copies of the
   Work or Derivative Works thereof in any medium, with or without
   modifications, and in Source or Object form, provided that You
   meet the following conditions:

   (a) You must give any other recipients of the Work or
       Derivative Works a copy of this License; and

   (b) You must cause any modified files to carry prominent notices
       stating that You changed the files; and

   (c) You must retain, in the Source form of any Derivative Works
       that You distribute, all copyright, patent, trademark, and
       attribution notices from the Source form of the Work,
       excluding those notices that do not pertain to any part of
       the Derivative Works; and

   (d) If the Work includes a "NOTICE" text file as part of its
       distribution, then any Derivative Works that You distribute must
       include a readable copy of the attribution notices contained
       within such NOTICE file, excluding those notices that do not
       pertain to any part of the Derivative Works, in at least one
       of the following places: within a NOTICE text file distributed
       as part of the Derivative Works; within the Source form or
       documentation, if provided along with the Derivative Works; or,
       within a display generated by the Derivative Works, if and
       wherever such third-party notices normally appear. The contents
       of the NOTICE file are for informational purposes only and
       do not modify the License. You may add Your own attribution
       notices within Derivative Works that You distribute, alongside
       or as an addendum to the NOTICE text from the Work, provided
       that such additional attribution notices cannot be construed
       as modifying the License.

   You may add Your own copyright statement to Your modifications and
   may provide additional or different license terms and conditions
   for use, reproduction, or distribution of Your modifications, or
   for any such Derivative Works as a whole, provided Your use,
   reproduction, and distribution of the Work otherwise complies with
   the conditions stated in this License.

5. Submission of Contributions. Unless You explicitly state otherwise,
   any Contribution intentionally submitted for inclusion in the Work
   by You to the Licensor shall be under the terms and conditions of
   this License, without any additional terms or conditions.
   Notwithstanding the above, nothing herein shall supersede or modify
   the terms of any separate license agreement you may have executed
   with Licensor regarding such Contributions.

6. Trademarks. This License does not grant permission to use the trade
   names, trademarks, service marks, or product names of the Licensor,
   except as required for reasonable and customary use in describing the
   origin of the Work and reproducing the content of the NOTICE file.

7. Disclaimer of Warranty. Unless required by applicable law or
   agreed to in writing, Licensor provides the Work (and each
   Contributor provides its Contributions) on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
   implied, including, without limitation, any warranties or conditions
   of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
   PARTICULAR PURPOSE. You are solely responsible for determining the
   appropriateness of using or redistributing the Work and assume any
   risks associated with Your exercise of permissions under this License.

8. Limitation of Liability. In no event and under no legal theory,
   whether in tort (including negligence), contract, or otherwise,
   unless required by applicable law (such as deliberate and grossly
   negligent acts) or agreed to in writing, shall any Contributor be
   liable to You for damages, including any direct, indirect, special,
   incidental, or consequential damages of any character arising as a
   result of this License or out of the use or inability to use the
   Work (including but not limited to damages for loss of goodwill,
   work stoppage, computer failure or malfunction, or any and all
   other commercial damages or losses), even if such Contributor
   has been advised of the possibility of such damages.

9. Accepting Warranty or Additional Liability. While redistributing
   the Work or Derivative Works thereof, You may choose to offer,
   and charge a fee for, acceptance of support, warranty, indemnity,
   or other liability obligations and/or rights consistent with this
   License. However, in accepting such obligations, You may act only
   on Your own behalf and on Your sole responsibility, not on behalf
   of any other Contributor, and only if You agree to indemnify,
   defend, and hold each Contributor harmless for any liability
   incurred by, or claims asserted against, such Contributor by reason
   of your accepting any such warranty or additional liability.

END OF TERMS AND CONDITIONS

APPENDIX: How to apply the Apache License to your work.

   To apply the Apache License to your work, attach the following
   boilerplate notice, with the fields enclosed by brackets "[]"
   replaced with your own identifying information. (Don't include
   the brackets!)  The text should be enclosed in the appropriate
   comment syntax for the file format. We also recommend that a
   file or class name and description of purpose be included on the
   same "printed page" as the copyright notice for easier
   identification within third-party archives.

Copyright [yyyy] [name of copyright owner]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
