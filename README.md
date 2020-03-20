# Embodied closed-loop architecture of 'saccades for scene understanding'

![](https://img.shields.io/github/license/ccnmaastricht/CDP4_NRP)
![](https://img.shields.io/github/issues/ccnmaastricht/CDP4_NRP)
![](https://img.shields.io/github/forks/ccnmaastricht/CDP4_NRP)
![](https://img.shields.io/github/stars/ccnmaastricht/CDP4_NRP)

Human vision operates in light of physical constraints imposed by the eye as well as functional requirements such as having high visual acuity while maintaining a large field of view. Physically, the organization of the retina meets these constraints by densely packing photoreceptors within a small central region, the fovea, and letting photoreceptor density decrease rapidly towards the periphery. Functionally, this arrangement introduces a challenge for the visual system since only the region of external space fixated by the eyes is resolved with high acuity. To overcome this, vision involves information integration across samples of external space obtained by continuously repositioning the eyes.
Co-design project 4 has developed a closed-loop architecture consisting of five functional modules:

- ![Ganglion density based image resampling]()
- ![object recognition]()
- ![saliency computation](https://github.com/alexanderkroner/saliency)
- ![visual target selection](https://github.com/ccnmaastricht/target_selection)
- ![saccade generation]()

and embodied this in a virtual iCub robot simulated on the ![neurorobotics platform](https://neurorobotics.net/)
