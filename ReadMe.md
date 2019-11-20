I am a Data Scientist and looking for an opportunity which let me develop my skills.

As a former theoretical physicist, I have a very strong background advanced-level mathematical subjects,
such as differential geometry, abstract algebra, topology, and field theory. My academic research focused
on developing modified general relativity models and finding gravitational solutions of superstring theory.
I have extensive experience with lagrangian optimization. Specifically, solving differential equations of
tensors is one of my mathematical skills. For analytic calculation, 
I aggressively used Mathematica as rule based programming language to overcome notoriously lengthy
computation.

With my recent interests, I have learned python and tensorflow as tools for manipulating data and
implementing basic algorithms of machine learning. To improve my coding skill, I probabilistically
modeled the 2D galaxy profile in Bayesian Inference using big astronomical data from the Survey of the Magellanic Stellar History. I started with the FITS tables that include photometric information of ~200 million objects in the Large Magellanic Cloud (LMC). To properly understand the LMC, identifying unique LMC stars is necessary. Using the spacing indexing k-d tree algorithm, I was able to efficiently remove duplicated objects from these huge catalogs. After then,  I used the data to model 2D galaxy profile using mcmc sampling in the bayesian inference. I learned Python, Numpy, Matplotlib with this project. 


For the next step, with personal interest, I wanted to study reinforcement learning algorithm. I built a unicycle simulation model using pybullet as a test bed. This unicycle consists with two wheels, and the unicycle reacts with two driving torques. For the first episode of play, the unicycle fall down in about 1 second. As the algorithm learns, the network tuned finely, the unicycle balanced lasts more than 30 seconds. With DDQN algorithm, it took tens of thousands episodes to learn, with DDPG, it took only 2 thousand episodes. My codes are available through my Github page. https://github.com/jhoonjeong/RL_unicycle
 
Recently, I started a new project on climate data. Using Local Climatological Data(LCD) collected in land-based stations within the United States, I analyzed data collected for two years in 38 stations in Pennsylvania state. The data consists over million time-series with 90 columns of hourly, daily and monthly observed values. For simplicity, I mangled data of 2018 containing only dry-bulb temperature value with 38 station columns and 8760 hourly index line to train GAN. Even though GANs are mostly used to generate picture image, it can perform to bare numerical data as well. I put random choice of historical data of 2017 to test trained model. The ground truth and the predicted data t-SNE embedding shows that the prediction follows rough pattern but can’t imitate real data points exactly.
The predicted spatial temperature map is following normal pattern but the local parts need more improvement. 
