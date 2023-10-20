---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<style>
  * {
    box-sizing: border-box;
  }

  .column1 {
    float: left;
    width: 70%;
    padding: 10px;
  }

  .column2 {
    float: left;
    width: 30%;
    padding: 10px;
  }

  .row:after {
    content: "";
    display: table;
    clear: both;
  }

  img.fit-picture {
    width: 100%;
    height: auto;
  }

  h1 {
    text-align: center;
    font-size: 2.5em;
  }

  h2 {
    color: #333366;
    font-size: 2em;
  }

  p {
    text-align: justify;
  }

  a {
    color: #3366CC;
  }
</style>

<body>

## Ongoing Projects

### [Normative Institutions in Online Social Systems](https://bit.ly/information_steward)

<div class="row">
  <div class="column2">
    **Status:** Ongoing  
    **Type:** Working Paper
  </div>
  <div class="column1">
    Description: Human societies throughout history have demonstrated a universal capacity to build emergent formal and informal institutions to solve large-scale cooperation problems. However, theories of collective behaviour in large online social systems have largely overlooked the role of informal institutions, such as political influencers, opinion leaders, and partisan media. In this paper, we develop a framework of _institutional stewarding_, which uses a game-theoretic underpinning of normative institutions as coordinators of decentralized norm enforcement. We show that many empirically observed phenomena, such as the spiral of silence and false polarization, can be explained through a process of opinion stewarding by informal institutions with different incentives and strategic choices made by a heterogeneous population on whether to express their normative opinions. The model also provides insights into the limits of this institutional capacity. In particular, we show that the capacity of institutions to mitigate adverse social outcomes depends on multiple factors, such as how far institutions can deviate from prevailing community beliefs and the presence of other strategic institutions in the environment. This project aims to build a theory based on institutions, norms, and individual incentives for better design of online social interaction platforms.
  </div>
</div>

## Completed Projects

### A Generalized Cognitive Hierarchy Model for Dynamic Games

<div class="row">
  <div class="column2">
    ![Image](/images/gen_cog_hierar.png)  
    **Type:** Research Paper
  </div>
  <div class="column1">
    **Description**: While there has been an increasing focus on the use of game theoretic models for autonomous driving, empirical evidence shows that there are still open questions around dealing with the challenges of common knowledge assumptions as well as modeling bounded rationality. To address some of these practical challenges, we develop a framework of generalized dynamic cognitive hierarchy for both modelling naturalistic human driving behavior as well as behavior planning for autonomous vehicles (AV). This framework is built upon a rich model of level-0 behavior through the use of automata strategies, an interpretable notion of bounded rationality through safety and maneuver satisficing, and a robust response for planning. Based on evaluation on two large naturalistic datasets as well as simulation of critical traffic scenarios, we show that i) automata strategies are well suited for level-0 behavior in a dynamic level-k framework, and ii) the proposed robust response to a heterogeneous population of strategic and non-strategic reasoners can be an effective approach for game theoretic planning in AV
  </div>
</div>

### Safety Validation of Strategic Planners

<div class="row">
  <div class="column2">
    ![Image](/images/hypergames.png)  
    **Type:** Research Paper
  </div>
  <div class="column1">
    **Description**: TA particular challenge for both autonomous and human driving is dealing with risk associated with dynamic occlusion, i.e., occlusion caused by other vehicles in traffic. Based on the theory of hypergames, we develop a novel multiagent dynamic occlusion risk (DOR) measure for assessing situational risk in dynamic occlusion scenarios. Furthermore, we present a white-box, scenario-based, accelerated safety validation framework for assessing safety of strategic planners in AV. Based on evaluation over a large naturalistic database, our proposed validation method achieves a 4000% speedup compared to direct validation on naturalistic data, a more diverse coverage, and ability to generalize beyond the dataset and generate commonly observed dynamic occlusion crashes in traffic in an automated manner.
  </div>
</div>

### Waterloo Multi-Agent Traffic Dataset

<div class="row">
  <div class="column2">
    ![Image](/images/wmad.png)  
    **Type:** Dataset
  </div>
  <div class="column1">
    **Description**: A multi-agent dataset of traffic interactions covering various scenarios, such as, busy intersections, crosswalk interaction with pedestrians, roundabouts, and interaction between pedetrians and AV. The dataset is under active development, and the intersection and crosswalk dataset is [available here](http://wiselab.uwaterloo.ca/waterloo-multi-agent-traffic-dataset/)
  </div>
</div>

### Taxonomy of Strategic and Non-strategic Interactions

<div class="row">
  <div class="column2">
    ![Image](/images/taxonomy.png)  
    **Type:** Research Paper
  </div>
  <div class="column1">
    **Description**: n order to enable autonomous vehicles (AV) to navigate busy traffic situations, in recent years there has been a focus on game-theoretic models for strategic behavior planning in AVs. However, a lack of common taxonomy impedes a broader understanding of the strategies the models generate as well as the development of safety specification to identity what strategies are safe for an AV to execute. Based on common patterns of interaction in traffic conflicts, we develop a taxonomy for strategic interactions along the dimensions of agents' initial response to right-of-way rules and subsequent response to other agents' behavior. Furthermore, we demonstrate a process of automatic mapping of strategies generated by a strategic planner to the categories in the taxonomy, and based on vehicle-vehicle and vehicle-pedestrian interaction simulation, we evaluate two popular solution concepts used in strategic planning in AVs, QLk and Subgame perfect epsilon-Nash Equilibrium, with respect to those categories.
  </div>
</div>

</body>
