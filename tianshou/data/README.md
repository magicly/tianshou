# TODO:

Notice that we will separate actor and critic, and batch will collect data for optimizing policy while replay will collect data for optimizing critic.

# Batch

YouQiaoben

fix as stated in ppo_example.py



# Replay

ShihongSong

a Replay.py file. must have collect() and next_batch() methods for training.

integrate previous ReplayBuffer codes.


# adv_estimate

YouQiaoben (gae_lambda), ShihongSong(dqn after policy.DQN)

seems to be direct python functions. also may write it in a functional form.