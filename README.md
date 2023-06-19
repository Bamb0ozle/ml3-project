<h1>Reinforcement Learning using Deep Q-Networks and Custom Wrappers in the Lunar Lander Environment of OpenAI's Gymnasium</h1>

The details of the project are located in the ipynb and html file. 

The models were trained over 1 million iterations which are labelled "target_net_1000000_model{number}.pt".

<h2>The six models used:</h2>

Model 1: No wrapper, wind enabled (WE)
Model 2: WE + Additional action of firing both side engines simultaneously
Model 3: WE + Multiplying rewards between 0 and 100 by 1.5
Model 4: Model 2 + Model 3
Model 5: Model 4 + distance from center penalty
Model 6: Model 5, but change multipliers for reward and penalty

<b>Configurations of the models can be found in the notebook and html file.</b>
