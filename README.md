# TV Script Generator

## Project Overview

In this project, I trained an RNN model on [Seinfeld](https://en.wikipedia.org/wiki/Seinfeld) TV scripts. After the training, the Neural Network was able to generate "fake" TV script, based on patterns it reconginzes in this training data. The script was more or less readbale. you could find the same at the end of the jupyter notebook

## Project Instruction

### Instruction

1. Clone the repository and navigate to the downloaded folder.
	```
		git clone https://github.com/eswar3/tv-script-generation-using-RNN.git
		cd tv-script-generation-using-RNN
	```
2. Open the `tv_script_generation.ipynb` file. 
	```
		jupyter notebook tv_script_generation.ipynb
	```
3. Read and follow the instructions in the notebook

## Project Steps

- Explore the Data and Implement Pre-processing Functions
- Build the Neural Network
	- Define forward and backpropagation
- Neural Network Training
	- Train Loop
	- Hyperparameters
	- Train 
- Generate TV Script
	- Generate a new script


### Libraries

- [PyTorch](https://pytorch.org) (LSTM)
