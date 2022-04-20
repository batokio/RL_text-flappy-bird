# RL_text-flappy-bird
The notebook presents the implementation of the Q-Learning and Expected SARSA algorithms to solve the Text-Flappy-Bird game

![TFB_agent](https://user-images.githubusercontent.com/76013828/164188232-c9602117-d42d-4019-b116-3ccf714196de.gif)

## Text flappy bird game

The implementation of the environment can be found here:
https://gitlab-research.centralesupelec.fr/stergios.christodoulidis/text-flappy-bird-gym

## Final model
Please find below the final model used to measure the performance of the agents:

| Hyperparameters  | Q-Learning  | Expected SARSA |
| :------------ |:---------------| :-----|
| Step-size      | 0.5 | 0.5 |
| Step-size decay      | 1.0        |   0.99999 |
| Epsilon | 0.05        |    0.05 |
| Epsilon decay      | 0.99999        |   0.99999 |
| Discount      | 1.0        |   0.9 |



## Performance

The sum of rewards achieved by both agents:
```python 
Q-Learning: 8,041,130
Expected SARSA : 36,660
```
