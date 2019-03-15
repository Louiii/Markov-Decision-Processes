# Markov-Decision-Processes

Hosted here:
https://colab.research.google.com/drive/1gJXtdfnFLR0Q00LrK8rWCgbQEV69TsVQ#scrollTo=QRpxDsXQGbaM

These dynamic programming examples do not have a definite final stage from which we work back via backwards induction. These are problems with no natural final stage: infinite horizon problems. These problems are only manageable if we impose some additional structure on how the stages progress; some version of the Markov property is what we need here. We have seen that Markov chains can be used to model the evolution of systems that change in some random fashion which may depend on their current state but not on their earlier history. These are Markov decision processes, a useful and important class of models which allow us to take actions which at some known cost modify the transition probabilities of a system. The question of interest is how to optimally choose which actions to take.

