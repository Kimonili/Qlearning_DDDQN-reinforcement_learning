# Qlearning_DDDQN-reinforcement_learning
This is the repository of a project for my masters in Data Science @ City University of London for the purpose of Deep Learning 3: Optimization module. 

In the [q_learing_policies](https://github.com/Kimonili/Qlearning_DDDQN-reinforcement_learning/tree/master/qlearning_policies) directory are located the 4 ipynb files, each of which apply a different exploration policy. The algorithm is applied to a self made environment which is based on the [frozen lake](https://gym.openai.com/envs/FrozenLake-v0/) principles. We investigate the importance of the selected exlporation technique in the simple Q Learinng algorithm on the efficiency of the model. The compared exploration strategies are:

- random policy
- epsilon greedy-constant policy
- epsilon greedy-decay policy
- boltzmann policy

[dddqn_LunarLander.ipynb](https://github.com/Kimonili/Qlearning_DDDQN-reinforcement_learning/blob/master/dddqn_LunarLander.ipynb) contains a Dueling Double Deep Q Network implementation in the Lunar Lander environment from OpenAI. Information about the environment can be found both in the [report](https://github.com/Kimonili/Qlearning_DDDQN-reinforcement_learning/blob/master/KonstantinosGkolias_KimonIliopoulos_DeepLearningOptimization_Report%20(1).pdf) of this repo and in the official website of the [environment](https://gym.openai.com/envs/LunarLander-v2/).

For the completion of the project _Kimon Iliopoulos_ and _Konstantinos Gkolias_ contributed equally. 
