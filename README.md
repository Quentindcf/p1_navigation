# Project Details

This is an amended version of the DQN implementation that was built to solve the moon lander game. It has been adapted to the unity problem by using the unity wrapper instead of gym and adapting to the new environment:
- Observation space is of length 37
- Action space is made up of 4 actions

Following this, the agent was modified to use the double DQN modification. The rest is identical to the moon lander solution.


# Getting Started
## Dependencies

To set up your python environment to run the code in this repository, follow the same instructions as for the course repo:

1. Create (and activate) a new environment with Python 3.6.

	- __Linux__ or __Mac__: 
	```bash
	conda create --name drlnd python=3.6
	source activate drlnd
	```
	- __Windows__: 
	```bash
	conda create --name drlnd python=3.6 
	activate drlnd
	```
	
2. Follow the instructions in [this repository](https://github.com/openai/gym) to perform a minimal install of OpenAI gym.  
	- Install the **box2d** environment group by following the instructions [here](https://github.com/openai/gym#box2d).
	
3. Clone the repository, and navigate to the `python/` folder.  Then, install several dependencies.
```bash
git clone https://github.com/udacity/Value-based-methods.git
cd Value-based-methods/python
pip install .
```

4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `drlnd` environment.  
```bash
python -m ipykernel install --user --name drlnd --display-name "drlnd"
```

5. Before running code in a notebook, change the kernel to match the `drlnd` environment by using the drop-down `Kernel` menu. 



# Instructions

To train the agent, run the code in the report notebook.
