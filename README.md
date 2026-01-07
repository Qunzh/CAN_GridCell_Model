# Recurrent Continuous Network Model for V1 Orientation Selectivity

## Overview
Reproduction of Recurrent Continuous Network Model for V1 Orientation Selectivity proposed by Ben-Yishai et al.(1995) with help from Wang et al. 2025 Theoretical Neuroscience Chapter 3.5 Network Models and Information Representation. 
  
Biologically realistically, this model suceessfully captures the property which orientation selectivity doesn't change with the level contrast as observed in experiment.  
  
Dyanmically, this model also demonstrates how interaction between specific recurrent excitation and recurrent inhibition could possibly leads to 3 different dynamical regimes in V1:  

## Background
### Structure of Visual Pathway
Visual information of the world is received by photoreceptors which spread on the retina first, and then passed on to their corresponding bipoar cells which connect to the ganglion cells. The ganglion cells then pass the information towards LGN(Lateral Ganglion Nucleus) in thalamus, and then LGN feeds this information towards V1(primary visual cortex).   
### Receptive Fields in Retina and LGN
The bipolar cells are connected to photoreceptors through 2 pathways: the direct 1-1 (photoreceptor-bipolar) pathway which bipolar cells directly receive input about the "center" of receptive field and the indirect pathway controlled by horizontal cells inhibiting a neighboring ring of bipolar cells which led bipolar cells receive input about the "surrounding" of receptive field. For example, for a bipolar cell depolarizes by photoreceptor input (ON-bipolar cell), light shines directly onto this photoreceptor would excite the bipolar cell and light shines onto the surrounding ring of this photoreceptors would inhibit the bipolar cell. For OFF-bipolar cell hyperpolarizes by photoreceptor input the opposite scenario happen. But regardless, light shine onto the center and surrounding ring of photoreceptor would always elicit opposite response from the bipolar cell connected to the photoreceptor.   
The ganglion cells connected to the bipolar cells have the same receptive field property (2 types, off-center ganglion cells which hyperpolarized to receptive field center light input and depolarized to recpetive filed surrounding light input, and on-center ganglion cells which depolarized to receptive field center light input and hyperpolarized to recpetive filed surrounding light input). The surrounding input would always cancel with the center input for these ganglion cells.  
This structure is again preserved in LGN which feeds input to V1.
### Receptive Fields leads to Orientation Selectivity in V1
It was found by Hubel and Wiesel that some V1 Neurons respond best towards light bar at a particular orientation at a particular location of the recpetive field. It is suspected that this orientation selectivity in V1 is brought by convergent input from ganglion cells with connected on/off receptive feilds that are aligned along one axis.  
### Computational Models for Orientation Selectivity in V1 based on LGN Input
## The Problem of Contrast
## Interaction between Recurrent Excitation and Inhibition leads to 3 Dynamical Regime
1) Homogeneous state: small recurrent excitation and inhibition leads to Homogeneous state which steady state condition is completely determined by peak orientation tuning in LGN
2) Marginal State: moderately large recurrent excitation and inhibition leads to Maginal state which steady state is determined by initial condition of orientation tuning and rate amplitude in V1
3) Amplitude Instability state: very large recurrent excitation which escapes from suppression of recurrent inhibition leads to Amplitude Instability state which amplitude escape biologically realistic scenarios. 
## Reference
