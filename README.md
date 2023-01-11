# Multi-Agent Reinforcement Learning implementation for Knights Archers Zombies (KAZ) using Tianshou and PettingZoo

In order to run this, it is necessarry to have Tianshou PettingZoo installed.

Afterwards simply run ```python tian.py``` in order to train the agent.
The trained agent can also play by itself by executing the following command
```python tian.py --watch --resume-path log/kaz/dqn/policy.pth --opponent-path log/kaz/dqn/policy.pth```

All the parameters are hardcoded like in the Tianshou tutorial and those can be modified from the code itself.
