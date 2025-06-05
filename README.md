# PopSynth

# A deep generative model for feasible and diverse population synthesis
Kim, E. J., & Bansal, P. (2023). A deep generative model for feasible and diverse population synthesis. Transportation Research Part C: Emerging Technologies, 148, 104053. https://doi.org/10.1016/j.trc.2023.104053

## Overview
This model is to generate the synthetic population based on deep generative models (VAE and GAN), using tabular NHTS data for individual-specific attributes, such as sociodemographics. Two novel loss functions control the trade-off between feasibility and diversity in a data-driven manner. 

## Getting Started

### Dependencies
* Python 3.11.4
* Tensorflow 2.13.0 , Keras 2.13.1

### Components

#### Dataset
* 'data' contains an anonymised, pre-processed extract of the South Korean National Household Travel Survey (HTS).
All personally identifiable information was removed before distribution.

##### WGAN_OOSDivH_SampleCode.ipynb
* In this one notebook, we contain sample code for implementing two loss functions: R_AD and R_BD.
* Since all functions and class structures have been broken down, you can easily understand the code if you follow them step-by-step.


## Notice
* Full paper will be provided after the peer-review process, but you can refer to the SSRN draft.
* Detailed logic behind the code is described in the full paper.
* https://doi.org/10.1016/j.trc.2023.104053

## Authors
[@Eui-Jin Kim](https://sites.google.com/view/euijinkim)


## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

