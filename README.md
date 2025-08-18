# 7Bench: a Comprehensive Benchmark for Layout-guided Text-to-image Models

[Elena Izzo](https://www.linkedin.com/in/elena-izzo-b87b69164)\*, [Luca Parolari](https://github.com/lparolari)\*, [Davide Vezzaro](https://www.linkedin.com/in/davidevezzaro/)\*, [Lamberto Ballan](http://www.lambertoballan.net/) \
Department of Mathematics, University of Padova, Padova, Italy

🌟 Accepted to 23rd International Conference on Image Analysis and Processing (ICIAP) 2025, 15-19 September 2025, Rome, Italy

\*These authors contributed equally to this work and are listed in alphabetical order.

![benchmark.png](docs/benchmark.png)

## Abstract

Layout-guided text-to-image models offer greater control over the generation process by explicitly conditioning image synthesis on the spatial arrangement of elements.
As a result, their adoption has increased in many computer vision applications, ranging from content creation to synthetic data generation.
A critical challenge is achieving precise alignment between the image, textual prompt, and layout, ensuring semantic fidelity and spatial accuracy. 
Although recent benchmarks assess text alignment, layout alignment remains overlooked, and no existing benchmark jointly evaluates both. 
This gap limits the ability to evaluate a model's spatial fidelity, which is crucial when using layout-guided generation for synthetic data, as errors can introduce noise and degrade data quality.
In this work, we introduce 7Bench, the first benchmark to assess both semantic and spatial alignment in layout-guided text-to-image generation.
It features text-and-layout pairs spanning seven challenging scenarios, investigating object generation, color fidelity, attribute recognition, inter-object relationships, and spatial control.
We propose an evaluation protocol that builds on existing frameworks by incorporating the layout alignment score to assess spatial accuracy.
Using 7Bench, we evaluate several state-of-the-art diffusion models, uncovering their respective strengths and limitations across diverse alignment tasks. 
The benchmark is available at https://github.com/Elizzo/7Bench.

## Code coming soon!

