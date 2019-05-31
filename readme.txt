Model program for the paper: 

Sergey M. Korogod, Irina B. Kulagina
 
Conditions of dominant effectiveness of distal sites of active uniform dendrites 
with distributed tonic inputs. 

Neirofiziologiya/Neurophysiology 30(4/5):376-382, 1998.

(Kluwer Academic/Plenum Publishers English version: Neurophysiology 30(4/5):310-315, 1999)


Running the mosinit.hoc program recreates all figures of the paper. 
To compute and display a figure click on the corresponding item (e.g. "Fig.1. A-C") 
of the "Article Results" menu window, operating similar to "NEURON Main Menu". 
To get Fig.1, A-C click on "Plot" in "Grapher" windows. 
To get Fig.2 and Fig.3 click on "Init & Run" in "RunControl" window.
Click on "Quiet" in "RunControl" window to get the results quicker.
This presentation was programmed by Valery I. Kukushka.


The model illustrates and explains bistable spatial pattern of the current transfer effectiveness 
in the active dendrite with distributed (multiple) tonic excitatory, NMDA type, synaptic input. 
Introducing steady synaptic conductivity of uniform maximum value in the dendritic membrane
simulates such input. 
With increasing membrane depolarization the voltage-dependent NMDA synaptic conductivity
increases and becomes dominating in the total conductivity (Fig.1A). Correspondingly,
the effective equilibrium potential shifts from the resting level to nearly equilibrium potential 
of the excitatory synaptic current (Fig.1B). Due to such voltage dependence of NMDA 
conductivity the dendritic membrane is non-linear with N-shaped steady current-voltage (I-V) 
relation (Fig.1C). 
This makes the neuron electrically bistabile with one stable state of the membrane potential close 
to the resting level (downstate) and another one (upstate) close to the equilibrium potential of 
excitatory synaptic current (Fig.2 A and B, respectively).
Fig.3, A-D shows how such membrane properties define bistable contribution from various 
dendritic sites to the total current transferred to the soma during tonic NMDA excitation. 
For that the NEURON programs compute and display the path profiles of the membrane 
voltage and effective equilibrium potential (A), total and partial conductivities (B), 
total current per unit membrane area (C) and the core current increment per unit path length (D). 
The latter is the estimate of the current transfer effectiveness as described in: 

                 Korogod SM and Kulagina IB (1998) Biol Cybern 79: 231-242

Tonic dendritic depolarization in both states was the greatest on the distal tip and decayed 
toward the soma. The upstate and downstate dendritic depolarizations were in the range of, 
respectively, positive and negative slope of the N-shaped local I-V relation. Correspondingly, 
in the upstate, more depolarized distal dendritic sites produced smaller (almost zero at the tip) 
current density and smaller contribution to the somatopetal core current than proximal ones. 
An unusual effect was observed in the downstate: more depolarized distal sites were 
more effective than proximal ones.
 

Membrane mechanisms:

PasSA.mod: passive membrane current of the soma and axon
Nmda.mod: synaptic NMDA type channel mechanism

For further details see the above mentioned papers or contact the authors at:
Laboratory of Biophysics and Bioelectronics, 
Dniepropetrovsk National University, 
49050 Dniepropetrovsk, Ukraine
Phone/FAX: +38056 776 91 24
E-mails: korogod@ff.dsu.dp.ua;  kulagina@ff.dsu.dp.ua;  valery@ff.dsu.dp.ua
