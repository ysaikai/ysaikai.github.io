---
title: "Research"
permalink: /research/
---

As a data-driven approach to optimal control, reinforcement learning (RL) has tremendous potential to optimise a wide variety of real-world systems that were previously unamenable to mathematical optimisation due to the lack of explicit models of dynamics. Among the key challenges of real-world RL, I am interested in sample efficient learning and offline learning.

For applied work, I am interested in precision agriculture, a form of agriculture that exploits advanced farming technologies for increased productivity. Modern sensor devices and actuators provide high spatiotemporal granularity of management units. To fully exploit the technologies and achieve right management at the right place at the right time, it is necessary to discover good policies that process high-dimensional sensor feedback and prescribe right management for each parcel of a field anytime farmers make decisions. I tackle this challenging spatiotemporal control problem using RL and Bayesian optimisation.

<br/>

## Bayesian optimisation
An optimization technique with two appealing features: sample efficiency and flexibility for complex objective functions. It has a lot of potential for applications to agricultural production, which usually takes time due to the seasonal production cycle. In other words, evaluating an agricultural production function or input response function is expensive, and therefore Bayesian optimizaton is a cost-efficient technique to identify good input combinations for profitability.

<!--
Bayesian optimization is still a novel technique in most scientific disciplines. The following videos may give you some idea.<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/WkZueBgKFYM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/vz3D36VXefI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
-->

<br/>

## Agent-based modeling
Agent-based modeling has become one of the standard approaches to studying complex systems and emergent behavior. In agent-based models, an observed macroscopic phenomenon emerges as a result of interaction among heterogeneous agents in a dynamically evolving environment. Agents typically follow simple decision rules and influence each other either directly or indirectly through the environment, which itself evolves according to its own rules and agent actions. Because the processes being explicitly modeled are complex, researchers use computer simulations to examine outcomes over a wide range of parameter values. In short, agent-based models are laboratory experiments conducted *in silico*. The idea is nicely captured by the following video (though we usually don't have physical robot agents).
<iframe width="560" height="315" src="https://www.youtube.com/embed/dDsmbwOrHJs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br/>

## Papers
- Mixtures of Gaussian process experts based on kernel stick-breaking processes
  - with [Khue-Dung Dang](https://scholar.google.com.au/citations?user=lg56IkAAAAAJ&hl=en)
  - Paper, [Code](https://github.com/ysaikai/GPKSBP)
- Deep reinforcement learning for irrigation scheduling using high-dimensional sensor feedback
  - with Allan Peake and [Karine Chenu](https://researchers.uq.edu.au/researcher/1740)
  - [Paper](https://arxiv.org/abs/2301.00899), [Code](https://github.com/ysaikai/RLIR)
- The case for fully Bayesian optimisation in small-sample trials
  - [Paper](https://arxiv.org/abs/2208.13960), [Code](https://github.com/ysaikai/case4fbo)
- [An agent-based model of insect resistance management and mitigation for Bt maize: A social science perspective](https://github.com/ysaikai/BTABM)
  - with [Paul Mitchell](https://aae.wisc.edu/faculty/pdmitchell/) and [Terrance Hurley](https://www.apec.umn.edu/people/terrance-hurley)
  - Published at [Pest Management Science](https://doi.org/10.1002/ps.6016)
- [Machine learning for optimizing complex site-specific management](https://github.com/ysaikai/BOPA)
  - with [Vivak Patel](http://pages.stat.wisc.edu/~vrpatel6/) and [Paul Mitchell](https://aae.wisc.edu/faculty/pdmitchell/)
  - Published at [Computers and Electronics in Agriculture](https://doi.org/10.1016/j.compag.2020.105381)
- [Adaptive experimental design using Bayesian optimization to improve the cost efficiency of field trials](https://github.com/ysaikai/AEDBO)
  - with [Vivak Patel](http://pages.stat.wisc.edu/~vrpatel6/), Shawn Conley, and [Paul Mitchell](https://aae.wisc.edu/faculty/pdmitchell/)
  - Presented at [2019 ASA-CSSA-SSSA International Annual Meeting](https://scisoc.confex.com/scisoc/2019am/meetingapp.cgi/Paper/122496)
- [A bandit algorithm for efficient on-farm research](https://github.com/ysaikai/MABPS)
  - with [Paul Mitchell](https://aae.wisc.edu/faculty/pdmitchell/)
  - Presented at [2018 AAEA Annual Meeting](https://www.aaea.org/meetings/2018-aaea-annual-meeting)

<!-- - [An agent-based model for promoting modest technologies](https://github.com/ysaikai/TechAdoption)
  - Based on the course project (AAE731 "Frontiers in Development Economics 2", Spring 2016) at UW-Madison
- [An impure public good model of local food systems: Aggregative games of four locals](https://github.com/ysaikai/LFSGames)
  - Based on the honours thesis (2014) at the Australian National University
-->

<br />
