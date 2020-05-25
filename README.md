# WorldModels
An implementation of the ideas from this paper https://arxiv.org/pdf/1803.10122.pdf

Code base adapted from https://github.com/hardmaru/estool

This repo. was created with an objective to learn Generative modeling in an enclosed Open-AI's environment with Evolutionary Strategy using the CMA-ES algorithm. There are some ongoing experiments for the next steps with different backbones and Attention units. 

For full installation and run instructions:

- Create the anaconda environment file from requirement.txt
- Run the notebooks for analysis of the experiments based on the weights and collected data
- For running the benchmarks, in normal mode: 
  python model.py car_racing --filename ./controller/car_racing.cma.xxxxx.best.json --render --final_mode

PS: Experiments and installation instructions are as per the Keras-GPU(v2.3.1) and Tensorflow-GPU(v2.1). (Experimentations done on a AMD's 8-core CPU with a Nvidia's GeForce RTX-2070 (Turing))
