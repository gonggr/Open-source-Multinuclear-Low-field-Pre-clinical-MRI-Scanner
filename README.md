Low-field MRI (B0 ≤ 0.2 T) is emerging as a technology with the potential to revolutionize clinical diagnostics and patient monitoring. The reduction in magnetic field strength comes along with a decrement of the scanners cost and the infrastructure required for their operation. This, in turn, enables the development of compact, portable systems that extends imaging capabilities to locations and scenarios that were previously inaccessible. This democratization has empowered research groups worldwide to design and build their own scanners, resulting in a surge of new devices. However, the majority of low-field scanners are optimized for human studies, which limits their application in pre-clinical research and constrains the testing and development of contrast agents tailored for low-field regimes. In particular, hyperpolarized agents hold considerable promise for low-field MRI due to their capacity to enhance signal and provide metabolic imaging of living systems. This signals enhancement counteracts the inherently low signal-to-noise ratio of thermally polarized studies which is the main limitation of low-field MRI. To exploit this potential, hyperpolarization studies frequently require the detection of X-nuclei, such as 13C and 15N, thereby emphasizing the need for versatile, multinuclear pre-clinical scanners. 	
Here, we present an open-source multinuclear low-field MRI scanner that has been specifically designed for hyperpolarized pre-clinical research. The device operates at 66 mT, and allows the detection of 1H, 23Na, 13C, and 15N nuclei. Comprehensive documentation and complete CAD designs are provided to facilitate replication and adaptation by the research community. 

Our multinuclear scanner operates at a mean magnetic field of 0.066 T with a homogeneity of 56 ppm after the implementation of active shimming.
The maximum ROI is a cylinder of 36 mm diameter and 90 mm length.
The Multinuclear scanner presented here was used PHIP hyperpolarization experiments.
With this device, we measured the pyruvate-to-lactate conversion in cancer cells and monitored chemical reactions of 15N compounds that are sensitive to reactive oxigen species (find references below)

The STL files includes the CAD designs for the following components:
1) Main magnet.
2) Gradient and shimming coils.
3) 1H & X-nuclei transreceiver RF coils.
4) Supports for assembling the coil setup.

The architecture and capacitors values used for the RLC circuits it is also available, together with photos and videos of the magnet assembling.

Contact: Dr. Gonzalo Rodriguez to gonzalogabriel.rodriguez@mpinat.mpg.de

REFERENCES

Biological J-Coupling Spectroscopy at Low Magnetic Field
Gonzalo G. Rodriguez, Charlotte von Petersdorff-Campen, Sergey Korchak, Oscar Sucre, Maria D. Santi, Josef Elsasser, Ruhuai Mei, Lisa M. Fries, Jan Felger, Andrea Markus, Frauke Alves, Stefan Glöggler
First published: 31 July 2025 https://doi.org/10.1002/smsc.202500268

15 N Reaction Monitoring at Low and Inhomogeneous Magnetic Fields Enabled by Hyperpolarization With Parahydrogen
Dr. Gonzalo Gabriel Rodriguez, Dr. Ruhuai Mei, Lisa Maria Fries, Dr. Stefan Glöggler
First published: 04 November 2025 https://doi.org/10.1002/chem.202503018
