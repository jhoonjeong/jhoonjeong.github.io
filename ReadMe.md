I am a Data Scientist and looking for an opportunity to share my skills as well as learn new things.

# Background
As a former theoretical physicist, I have a strong background in advanced-level mathematical subjects,
such as differential geometry, abstract algebra, topology, and field theory. My academic research focused
on developing modified general relativity models and finding gravitational solutions of superstring theory.
I have extensive experience with lagrangian optimization. Specifically, solving differential equations of
tensors is one of my mathematical skills. For analytic calculation, I aggressively used Mathematica as rule based programming language to overcome notoriously lengthy computation.

# Data Science Experience
With Python as my first programming language, I have been actively using **Pandas**, **Tensorflow**, and **Matplotlib** for data cleaning, analysis, and visualization. I have been applied various machine leaning algorithms to conduct my data science projects. 

## MCMC in Bayesian Inference
I probabilistically modeled the 2D galaxy profile in Bayesian Inference using big astronomical survey data. I started with the big tables that include photometric information of ~200 million objects in the closest external galaxy, Large Magellanic Cloud (LMC). To properly model the 2D galaxy profile, I identified unique object by efficiently removing duplicates from these huge catalogs using the spacing indexing **k-d tree** algorithm. And then, I used the unique object catalog to model 2D galaxy morphology using **Markov Chain Monte Carlo** sampling in the Bayesian inference. 

## Simulating Unicycle with Reinforcement Learning
I built a unicycle simulation model using pybullet as a test bed. This unicycle consists with two wheels, and the unicycle reacts with two driving torques. On the early stage of learning, the unicycle falls down in about 1 second. As the algorithm learns, the neural network gets tuned finely, and eventually the unicycle was able to balance by itself as long as I wanted. With **DDQN** algorithm, it took tens of thousands episodes to properly learn, while it took only 2 thousand episodes with **DDPG**. My codes are available through my [Github page](https://github.com/jhoonjeong/RL_unicycle). 

## Weather Anomaly Detection Using AnoGAN
Recently, I have started a new project on climate data. I downloaded publicly available Local Climatological Data(LCD), which has been collected at land-based stations across the United States. In particular, I analyzed the data collected in 38 stations in Pennsylvania state from 2017 to 2018. The data consists over million time-series measurements with an hour cadence. It also has daily and monthly values (e.g., average, high, low). For the simple test, I mangled data of 2018 containing only dry-bulb temperature value with 38 station columns and 8760 hourly index line to train **Generative Adversarial Network (GAN)**. GANs is supposed to mimic the real temperate data based on a training dataset. After training GAN with 2018 temperature data, I randonly selected a test sample from 2017 data to test the trained model. The ground truth (from 2017 data) and the predicted temperature maps roughly agree with each other; the global patterns are consistent, but the local variations exist. 
