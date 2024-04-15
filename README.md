# Population Synthesizer using Hidden Markov Models and Gibbs Sampling

Population synthesis is a vital component in various fields like urban planning, transportation modeling, and public health research, providing realistic demographic profiles for simulation and analysis. This project introduces the development of a population synthesizer leveraging Hidden Markov Models (HMMs), a statistical technique used for generating synthetic data from limited survey data.

## Overview

Conventional approaches to population synthesis often rely on deterministic methods, which may overlook the intricate dynamics and heterogeneity within real-world populations. This project addresses these limitations by proposing a novel approach based on Hidden Markov Models (HMMs). HMMs allow for the generation of synthetic populations with probabilistic transitions between states, mimicking the complex behavior observed in real populations.

## Methodology

The project employs Hidden Markov Models (HMMs) to iteratively model the transition between different states of demographic variables such as age, gender, and educational background. By incorporating constraints derived from available survey data, including transition probabilities and emission probabilities, the synthesizer produces synthetic populations that closely mirror the target population's characteristics.

## Key Features

- **Hidden Markov Models:** Utilizes HMMs, a powerful statistical technique, for generating synthetic populations with probabilistic transitions between states.
- **Probabilistic Transitions:** Models transitions between demographic states probabilistically, capturing the dynamic nature of real populations.
- **Incorporation of Constraints:** Incorporates constraints derived from survey data to ensure the synthesized populations closely match the target population's characteristics.
- **Flexibility:** Offers a flexible and versatile tool for generating synthetic populations tailored to specific modeling and analysis needs.

## Experimental Results

Experimental results demonstrate the effectiveness of the proposed population synthesizer in generating synthetic populations that exhibit high fidelity to the characteristics of real populations. 

## Potential Applications

The development of a population synthesizer utilizing Hidden Markov Models represents a significant advancement in population modeling and synthesis. This tool can find applications across diverse domains, including:

- Urban Planning
- Transportation Modeling
- Public Health Research

## How to Use

To utilize the population synthesizer, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies as specified in the documentation.
3. Run the main script with the desired parameters to generate synthetic populations.
4. Analyze the generated populations and integrate them into your modeling or analysis pipeline.

## Contributors

- Atharva Keny

## References

1. Saadia, I., Mustafa, A., Teller, J., Farooq, B., & Cools, M. (2016). Hidden Markov Model-based population synthesis. https://www.researchgate.net/publication/301739619_Hidden_Markov_Model-based_population_synthesis
2. Konduri, K. C., & Mondal, A. (Year). Stochastic multimodal network modeling: Hidden Markov model based synthetic population generation for use in microsimulation models of transit systems (Final Report). University of Connecticut. https://rosap.ntl.bts.gov/view/dot/64375
3. Dataset of 200 Population: Representative Sample: https://drive.google.com/file/dBoJZNhVfAs9uxT1nwhSEaSZl3CKez1Pn/view

*The Problem Statement was given as a part of a task by CISTUP IISC*

## License

This project is licensed under the MIT License - see the (LICENSE.md) file for details.

## Feedback and Contributions

Feedback and contributions are welcome! If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request.
