# RL-Exploration-Paper-Lists

Paper Collection of Reinforcement Learning Exploration covers exploration of Muti-Arm-Bandit, Reinforcement Learning and Multi-agent Reinforcement Learning. 

Exploration Reinforcement Learning is an important topic in Reinforcement Learning research area, which is to essentially improve the sample efficiency in a MDP setting.

A simple form of exploration-exploitation dilemma can be seen from the Multi-Arm Bandit problems, and we include MAB papers because many theoretical idea can be drived from MAB studies. 

Recently, most DRL exploration researches are focus on sparse reward settings and the target is a little different with the former studies, however we still classify those methods based on their methodology.

Papers are sorted by time and classification. Any suggestions and pull requests are welcome.

The sharing principle of these references here is for research. If any authors do not want their paper to be listed here, please feel free to contact me (Email: ericliuof97 [AT] gmail.com).

## MAB exploration

## RL exploration

### Reward based Exploration (Intrinsic Reward / Surprise / Curiosity / Uncertainty)

#### Review Papers

* <[Formal Theory of Creativity, Fun, and Intrinsic Motivation (1990-2010)](https://www.ece.uvic.ca/~bctill/papers/ememcog/Schmidhuber_2010.pdf)> by Jürgen Schmidhuber, 2010.

* <[What is intrinsic motivation? A typology of computational approaches](https://www.frontiersin.org/articles/10.3389/neuro.12.006.2007)> by Pierre-Yves Oudeyer and Frederic Kaplan, 2007.


#### Counts based methods

##### PAC-MDP

* <[An empirical evaluation of interval estimation for markov decision processes](https://www.researchgate.net/profile/Michael_Littman2/publication/4114612_An_empirical_evaluation_of_interval_estimation_for_Markov_decision_processes/links/54b66cb70cf24eb34f6d19da.pdf)> by Alexander L Strehl and Michael L Littman, 2004.

* <[A theoretical analysis of model- based interval estimation](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.76.1496&rep=rep1&type=pdf)> by Alexander L Strehl and Michael L Littman, 2004.

* <[R-max-a general polynomial time algorithm for near-optimal reinforcement learning](http://www.jmlr.org/papers/volume3/brafman02a/brafman02a.pdf)> by Ronen I Brafman and Moshe Tennenholtz, 2002.

* <[Near-optimal reinforcement learning in polynomial time](https://link.springer.com/content/pdf/10.1023/A:1017984413808.pdf)> by Michael Kearns and Satinder Singh, 2002.

* <[Efficient model-based exploration](https://dspace.library.uu.nl/bitstream/handle/1874/25440/Wiering_98_efficientmodelbased.pdf?sequence=1)> by Marco Wiering and Jürgen Schmidhuber, 1998.


##### Beyesian Reinforcement Learning

* <[Near-bayesian exploration in polynomial time](http://robotics.stanford.edu/~ang/papers/icml09-NearBayesianExplorationPolynomialTime-full.pdf)> by J Zico Kolter and Andrew Y Ng, 2009.

##### Psudo Count

* <[Unifying count-based exploration and intrinsic motivation](http://papers.nips.cc/paper/6383-unifying-count-based-exploration-and-intrinsic-motivation.pdf)> by Marc Bellemare, Sriram Srinivasan, Georg Ostrovski, Tom Schaul, David Saxton, and Remi Munos, 2016.

* <[Count-based exploration with neural density models](https://arxiv.org/pdf/1703.01310)>by Georg Ostrovski, Marc G Bellemare, Aaron van den Oord, and Rémi Munos, 2018

##### State Representation

* <[Contingency-aware exploration in reinforcement learning](https://arxiv.org/pdf/1811.01483)> by Choi, Jongwook and Guo, Yijie and Moczulski, Marcin and Oh, Junhyuk and Wu, Neal and Norouzi, Mohammad and Lee, Honglak, 2018.

* <[# exploration: A study of count-based exploration for deep reinforcement learning](https://papers.nips.cc/paper/6868-exploration-a-study-of-count-based-exploration-for-deep-reinforcement-learning.pdf))> by Haoran Tang, Rein Houthooft, Davis Foote, Adam Stooke, OpenAI Xi Chen, Yan Duan, John Schulman, Filip DeTurck, and Pieter Abbeel, 2017.



#### Information theory based methods

##### Mutual Information

* <[Variational information maximisation for intrinsically motivated reinforcement learning](https://papers.nips.cc/paper/5668-variational-information-maximisation-for-intrinsically-motivated-reinforcement-learning.pdf)> by Shakir Mohamed and Danilo Jimenez Rezende, 2015.

* <[An information-theoretic approach to curiosity-driven reinforcement learning](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.302.1588&rep=rep1&type=pdf)> by Susanne Still and Doina Precup, 2012.

##### Information Gain

* <[Vime: Variational information maximizing exploration](https://papers.nips.cc/paper/6591-vime-variational-information-maximizing-exploration.pdf)> by Rein Houthooft, Xi Chen, Yan Duan, John Schulman, Filip De Turck, and Pieter Abbeel, 2016.

#### Prediction Error based methods

* <[Large-Scale Study of Curiosity-Driven Learning](https://arxiv.org/pdf/1808.04355)> by Burda, Yuri and Edwards, Harri and Pathak, Deepak and Storkey, Amos and Darrell, Trevor and Efros, Alexei A, 2018.

* <[Curiosity-driven exploration by self-supervised prediction](https://pathak22.github.io/noreward-rl/resources/icml17.pdf)> by Pathak, Deepak and Agrawal, Pulkit and Efros, Alexei A and Darrell, Trevor, 2017.

### Policy based Exploration

* <[Provably efficient RL with Rich Observations via Latent State Decoding](https://arxiv.org/pdf/1901.09018)> by Du, Simon S and Krishnamurthy, Akshay and Jiang, Nan and Agarwal, Alekh and Dud{\'\i}k, Miroslav and Langford, John, 2019.

* <[Parameter Space Noise for Exploration](https://arxiv.org/pdf/1706.01905)> by Plappert, Matthias and Houthooft, Rein and Dhariwal, Prafulla and Sidor, Szymon and Chen, Richard Y and Chen, Xi and Asfour, Tamim and Abbeel, Pieter and Andrychowicz, Marcin, 2018.

### Search Exploration

* <[Monte-Carlo exploration for deterministic planning](https://www.aaai.org/ocs/index.php/IJCAI/IJCAI-09/paper/viewPaper/470)> by Hootan Nakhost and Martin Müller, 2009

* <[Bandit based monte-carlo planning](https://link.springer.com/content/pdf/10.1007/11871842_29.pdf)> by Levente Kocsis and Csaba Szepesvári, 2006

## MARL exploration
