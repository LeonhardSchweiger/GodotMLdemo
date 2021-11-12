This project uses RL, Proximal Policy Optimization to let multiple agent pairs play Catch.
In each agent pair, the red Agent tries to catch the blue Agent.

A strong reward gets handed out if the red Agent is near enough to the blue Agent.
A strong punishment gets handed out if the blue Agent is near enough to the red Agent.

Hyperparameters for good observable results:
agent_pairs = 250
batch_size = 64
n_epochs = 8
alpha = 0.00005
n_actions=4
input_dims = 4 (x1, y1, x2, y2)
reward = +-1 (when catched)
step_distance = 15 Frames
total_steps = 500000
N = 40
