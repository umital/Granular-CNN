# Granular-CNN

This repository documents notebooks used to generate results for the following peer-reviewed publication:

Mital, U., Andrade, J.E. Bridging length scales in granular materials using convolutional neural networks. Comp. Part. Mech. (2021). https://doi.org/10.1007/s40571-021-00405-1

I do not have the rights to distribute the data used in this work. If interested in the data, please contact the authors of the following publication: <br>
Marteau, E., Andrade, J.E. A novel experimental device for investigating the multiscale behavior of granular materials under shear. Granular Matter 19, 77 (2017)

## Project summary:
In this work, I developed a new deep learning framework to model macroscopic properties of granular materials, using microscopic or grain-scale information. A key insight was that incorporating spatial correlations in grain-scale data is key to model macroscopic properties. This meant that using convolutional neural networks (CNN) is critical for using a deep learning framework to bridge length scales in granular systems. For a uniaxial compression test, using CNN (vs a fully-connected neural network) improved the model accuracy by 91%.
