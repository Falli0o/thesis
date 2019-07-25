# Master Thesis
This project describes an approach to building a task--oriented dialogue response system. 
The system is an end-to-end hybrid model which combines Reinforcement Learning (RL) with the Supervised Learning (SL) paradigm. 
Four experiments are conducted in order to investigate the performance of such a hybrid model. 
Each experiment examines one model which is constructed by either the pure SL or the hybrid architecture. 
All models are trained and tested on a dialogue corpus in the restaurant search domain. 
The experimental results suggest that it is possible for the hybrid model to learn the dialogue policies and select 
the appropriate system actions in human-machine interaction. 
Comparing with the traditional method, the RL approaches avoid using the hand-crafted, rule-based dialogue strategies in 
the system design. This is the one advantage of the RL-based dialogue system. In addition, although the performance of 
the hybrid model is inferior to the pure SL approach, the hybrid approach is less expensive because it is trainable without 
using the pre--defined dialogue states. 
This is the another advantage of the end-to-end trainable hybrid model.
