# DDPG-Mountain-Car
DDPG algo

My simple implementation of the DDPG actor-critic algorithm from https://arxiv.org/pdf/1509.02971.pdf
It uses and solves OpenAI Gym's Continuous Mountain Car environment.

Note: this code is quite hacky and not written in vectorized form for higher dimensional problems. Batch Norm is not used.

For more details on the Continuous Mountain Car problem see my blog at https://medium.com/@asteinbach/actor-critic-using-deep-rl-continuous-mountain-car-in-tensorflow-4c1fb2110f7c for description of code.  This blog uses a simpler actor-critic algo rather than DDPG

For the theory of this simpler actor-critic algo see my blog at https://medium.com/@asteinbach/rl-introduction-simple-actor-critic-for-continuous-actions-4e22afb712
