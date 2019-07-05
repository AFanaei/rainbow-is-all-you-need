[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors)

*Do you want a RL agent nicely moving on Atari?*
# Rainbow is all you need!

Step-by-step tutorials from DQN to Rainbow.
Every tutorial contains both of theoretical backgrounds and object-oriented implementation. Just pick any topic in which you are interested, and learn! You can execute them right away with Colab even on your smartphone.

Please feel free to open an issue or a pull-request if you have any idea to make it better. :)


## Contents

01. DQN [[NBViewer](https://nbviewer.jupyter.org/github/Curt-Park/2nd_dlcat_rainbow/blob/master/01.dqn.ipynb)] [[Colab](https://colab.research.google.com/github/Curt-Park/rainbow-is-all-you-need/blob/master/01.dqn.ipynb)]
02. DoubleDQN [[NBViewer](https://nbviewer.jupyter.org/github/Curt-Park/2nd_dlcat_rainbow/blob/master/02.double_dqn.ipynb)] [[Colab](https://colab.research.google.com/github/Curt-Park/rainbow-is-all-you-need/blob/master/02.double_q.ipynb)]
03. PrioritizedExperienceReplay [[NBViewer](https://nbviewer.jupyter.org/github/Curt-Park/2nd_dlcat_rainbow/blob/master/03.per.ipynb)] [[Colab](https://colab.research.google.com/github/Curt-Park/rainbow-is-all-you-need/blob/master/03.per.ipynb)]
04. DuelingNet [[NBViewer](https://nbviewer.jupyter.org/github/Curt-Park/2nd_dlcat_rainbow/blob/master/04.dueling.ipynb)] [[Colab](https://colab.research.google.com/github/Curt-Park/rainbow-is-all-you-need/blob/master/04.dueling.ipynb)]
05. NoisyNet [[NBViewer](https://nbviewer.jupyter.org/github/Curt-Park/2nd_dlcat_rainbow/blob/master/05.noisy_net.ipynb)] [[Colab](https://colab.research.google.com/github/Curt-Park/rainbow-is-all-you-need/blob/master/05.noisy_net.ipynb)]
06. CategoricalDQN [[NBViewer](https://nbviewer.jupyter.org/github/Curt-Park/2nd_dlcat_rainbow/blob/master/06.categorical_dqn.ipynb)] [[Colab](https://colab.research.google.com/github/Curt-Park/rainbow-is-all-you-need/blob/master/06.categorical_dqn.ipynb)]
07. N-stepLearning [[NBViewer](https://nbviewer.jupyter.org/github/Curt-Park/2nd_dlcat_rainbow/blob/master/07.n_step_learning.ipynb)] [[Colab](https://colab.research.google.com/github/Curt-Park/rainbow-is-all-you-need/blob/master/07.n_step_learning.ipynb)]
08. Rainbow [[NBViewer](https://nbviewer.jupyter.org/github/Curt-Park/2nd_dlcat_rainbow/blob/master/08.rainbow.ipynb)] [[Colab](https://colab.research.google.com/github/Curt-Park/rainbow-is-all-you-need/blob/master/08.rainbow.ipynb)]

## Prerequisites
This repository is tested on [Anaconda](https://www.anaconda.com/distribution/) virtual environment with python 3.6.1+
```
$ conda create -n rainbow_is_all_you_need python=3.6.1
$ conda activate rainbow_is_all_you_need
```

## Installation
First, clone the repository.
```
git clone https://github.com/Curt-Park/rainbow-is-all-you-need.git
cd rainbow-is-all-you-need
```

Secondly, install packages required to execute the code. Just type:
```
make dep
```

## Related Papers

01. [V. Mnih et al., "Human-level control through deep reinforcement learning." Nature, 518
(7540):529–533, 2015.](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf)
02. [van Hasselt et al., "Deep Reinforcement Learning with Double Q-learning." arXiv preprint arXiv:1509.06461, 2015.](https://arxiv.org/pdf/1509.06461.pdf)
03. [T. Schaul et al., "Prioritized Experience Replay." arXiv preprint arXiv:1511.05952, 2015.](https://arxiv.org/pdf/1511.05952.pdf)
04. [Z. Wang et al., "Dueling Network Architectures for Deep Reinforcement Learning." arXiv preprint arXiv:1511.06581, 2015.](https://arxiv.org/pdf/1511.06581.pdf)
05. [M. Fortunato et al., "Noisy Networks for Exploration." arXiv preprint arXiv:1706.10295, 2017.](https://arxiv.org/pdf/1706.10295.pdf)
06. [M. G. Bellemare et al., "A Distributional Perspective on Reinforcement Learning." arXiv preprint arXiv:1707.06887, 2017.](https://arxiv.org/pdf/1707.06887.pdf)
07. [R. S. Sutton, "Learning to predict by the methods of temporal differences." Machine learning, 3(1):9–44, 1988.](http://incompleteideas.net/papers/sutton-88-with-erratum.pdf)
08. [M. Hessel et al., "Rainbow: Combining Improvements in Deep Reinforcement Learning." arXiv preprint arXiv:1710.02298, 2017.](https://arxiv.org/pdf/1710.02298.pdf)

## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table><tr><td align="center"><a href="https://www.linkedin.com/in/curt-park/"><img src="https://avatars3.githubusercontent.com/u/14961526?v=4" width="100px;" alt="Jinwoo Park (Curt)"/><br /><sub><b>Jinwoo Park (Curt)</b></sub></a><br /><a href="https://github.com/Curt-Park/rainbow-is-all-you-need/commits?author=Curt-Park" title="Code">💻</a> <a href="https://github.com/Curt-Park/rainbow-is-all-you-need/commits?author=Curt-Park" title="Documentation">📖</a></td><td align="center"><a href="https://www.linkedin.com/in/kyunghwan-kim-0739a314a/"><img src="https://avatars3.githubusercontent.com/u/17582508?v=4" width="100px;" alt="Kyunghwan Kim"/><br /><sub><b>Kyunghwan Kim</b></sub></a><br /><a href="https://github.com/Curt-Park/rainbow-is-all-you-need/commits?author=MrSyee" title="Code">💻</a></td></tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
