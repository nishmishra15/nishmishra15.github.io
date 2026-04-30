---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Nishchaya Kumar Mishra, a PhD scholar in the Department of Civil Engineering at Indian Inatitute of Technology Gandhinagar, India. My current work at IIT Gandhinagar lies at the intersection of control algorithms and indoor air quality. The overarching goal is to develop physics-driven and aritificial intelligence control algorithms that are deployable at community scale. 

Themes of my PhD work and highlights:
---

Dynamic Optimization of Exposure and Energy While Ensuring Thermal Comfort
---
1. Indoor PM mitigation and energy consumption trade-off require optimization.
2. Energy normalized exposure reduction quantifies the energy-exposure trade-off.
3. Desired exposure reductions with higher NER can be achieved via optimization.
4. Increasing indoor set temperature lowers energy penalty when it is hotter outside.
5. Internal filtration offsets the high energy penalty associated with exfiltration.

Sensitivity analysis of energy and exposure for low (A and B) and high (C and D) emission activities with distinct W1/W2 ratios where
- (A) and (C) are energy-exposure sensitivity,
- (B) and (D) are variations of normalized exposure reduction (NER)
- (+)ve change means increment, and (−)ve change means reduction
<img src="/images/LD_TGD_Sensitivity.jpg" alt="LD_TGD_Sensitivity" width="600">


DOPEEC (Deep Reinforcement Learning Agent for Optimizing Exposure, Energy, and Thermal Comfort)
---
1. A deep reinforcement learning agent controls ventilation and set temperature.
2. The agent’s performance is compared to a dynamic optimization strategy.
3. The agent achieved ∼17% to ∼373% higher energy normalized exposure reduction.
4. The proposed agent, integrated with low-cost sensors, can be field-deployed.

A framework for developing and testing a deep reinforcement learning agent.
<img src="/images/DOPEEC.jpg" alt="DOPEEC" width="600">

Transferability of Deep Reinforcement Learning Agents
---
1. Assessed the performance of a trained DRL agent when transferred to houses with varying characteristics and environmental conditions.
2. Agent's performance remained comparable to DynOpt, with particulate matter (PM) exposure and energy ratios near unity (1.05 ± 0.03).
3. Under simultaneous variations in house characteristics, the exposure (1.03 ± 0.07) and energy (1.09 ± 0.06) ratios remained close to one. 
4. Agent's performance declines in houses with high PM infiltration under high ambient parameters.

<img src="/images/transferableDRL.png" alt="transferableDRL" width="600">

Uncertainty Aware DRL Agent and Robustness of Action Selection Policies to Optimize Indoor PM Concentration and Energy Consumption
---
1. Monte Carlo dropout used to estimate uncertainty in DQN-based control agents.
2. Multiple action policies (MC-DQNs) tested against a traditional DQN agent.
3. PM exposure reduction ranged from −23 % to +34 % for high emission activities.
4. Few of the MC-DQNs consistently lowered high indoor PM (>40 µg/m³) levels.

<img src="/images/uncertainDRL.PNG" alt="uncertainDRL" width="600">

An Edge Device-Based Wireless Network Architecture for Real-Time Indoor Environment Control Using Deep Reinforcement Learning
---
Experiments ongoing

<img src="/images/deploymentRL.jpg" alt="deploymentRL" width="600">

Read more of my works in [Publication](https://nishmishra15.github.io//publications) section.
  


