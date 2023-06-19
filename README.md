<h1>Reinforcement Learning using Deep Q-Networks and Custom Wrappers in the Lunar Lander Environment of OpenAI's Gymnasium</h1>

The details of the project are located in the ipynb and html file. 

The models were trained over 1 million iterations which are labelled <i>target_net_1000000_model{number}.pt</i>.

<h2>The six models used</h2>

Model 1: No wrapper, wind enabled (WE)

Model 2: WE + Additional action of firing both side engines simultaneously

Model 3: WE + Multiplying rewards between 0 and 100 by 1.5

Model 4: Model 2 + Model 3

Model 5: Model 4 + distance from center penalty

Model 6: Model 5, but change multipliers for reward and penalty

<b>Configurations of the models can be found in the notebook and html file.</b>

<h2>References</h2>
https://keras.io/examples/rl/deep_q_network_breakout/
https://stable-baselines3.readthedocs.io/en/master/modules/dqn.html
https://stable-baselines.readthedocs.io/en/master/guide/examples.html#basic-usage-training-saving-loading
https://goodboychan.github.io/python/reinforcement_learning/pytorch/udacity/2021/05/07/DQN-LunarLander.html
https://gymnasium.farama.org/
https://deeplearning.neuromatch.io/projects/ReinforcementLearning/lunar_lander.html
https://github.com/yuchen071/DQN-for-LunarLander-v2
https://www.katnoria.com/nb_dqn_lunar/
https://hub.packtpub.com/openai-gym-environments-wrappers-and-monitors-tutorial/
DQN Tutorial prepared by Damian Dailisan for ML3 Session, May 2023. Tutorial was used as a starting point of this work.****
