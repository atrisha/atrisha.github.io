---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column1 {
  float: left;
  width: 50%;
  padding: 10px;}
.column2 {
  float: left;
  width: 20%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>
<h1>Ongoing</h1>
<h2>Normative persuasion in online social systems</h2>

<div class="row">
  <div class="column2" style="background-color:#FFFFFF;">
<a href="https://www.dropbox.com/s/zgf2hyizmgyfum8/Normative_information_design_for_online_social_systems_2.pdf?dl=0">Working paper</a>
  </div>
  <div class="column1" style="background-color:#FFFFFF;">
  <p>In online social communities, influencers, moderators of communities,new media figures, etc., hold a privileged position on accountof their visibility, and have been referred to as norm entrepreneursbecause of their ability to broadcast their views about right andwrong. In recent years, there have been calls to consider regulationand reevaluate their roles and responsibilities towards the healthof our social institutions. However, any act of regulation needsfurther understanding of their macro-level impact on society andexpectation of an ideal behaviour. In this project, we take a step inthat direction by formalising the following question. What shouldbe the ideal behaviour of such highly visible entities towards mitigatingadverse societal phenomena such as opinion polarisation.
We refer to such entities as information stewards and answer theabove question by elaborating the role of descriptive norms within a Bayesian persuasion framework.   

This question is importantfor lawmakers and platform designers alike since both need insightinto an ideal behaviour expected from information stewards aspart of any legislative process and evaluating the effect of platformdesign changes, respectively</p>
  </div>
</div>
<h1>Completed</h1>
<h2>A generalized cognitive hierarchy model for dynamic games</h2>

<div class="row">
  <div class="column2" style="background-color:#FFFFFF;">
    <img class="fit-picture" style="width: 55vw;"
     src="/images/gen_cog_hierar.png"
     alt="Image of the generalized cognitive hierarchy architecture">
  </div>
  <div class="column1" style="background-color:#FFFFFF;">
  <p>While there has been an increasing focus on the use of game theoretic models for autonomous driving, empirical evidence shows that there are still open questions around dealing with the challenges of common knowledge assumptions as well as modeling bounded rationality. To address some of these practical challenges, we develop a framework of generalized dynamic cognitive hierarchy for both modelling naturalistic human driving behavior as well as behavior planning for autonomous vehicles (AV). This framework is built upon a rich model of level-0 behavior through the use of automata strategies, an interpretable notion of bounded rationality through safety and maneuver satisficing, and a robust response for planning. Based on evaluation on two large naturalistic datasets as well as simulation of critical traffic scenarios, we show that i) automata strategies are well suited for level-0 behavior in a dynamic level-k framework, and ii) the proposed robust response to a heterogeneous population of strategic and non-strategic reasoners can be an effective approach for game theoretic planning in AV</p>
  </div>
</div>



<h2>Safety Validation of strategic planners</h2>

<div class="row">
  <div class="column2" style="background-color:#FFFFFF;">
    <img class="fit-picture" style="width: 55vw;"
     src="/images/hypergames.png"
     alt="Image showing the general scheme for dynamic occlusion risk validation process">
  </div>
  <div class="column1" style="background-color:#FFFFFF;">
  <p>A particular challenge for both autonomous and
human driving is dealing with risk associated with dynamic
occlusion, i.e., occlusion caused by other vehicles in traffic.
Based on the theory of hypergames, we develop a novel multiagent dynamic occlusion risk (DOR) measure for assessing
situational risk in dynamic occlusion scenarios. Furthermore,
we present a white-box, scenario-based, accelerated safety
validation framework for assessing safety of strategic planners
in AV. Based on evaluation over a large naturalistic database,
our proposed validation method achieves a 4000% speedup
compared to direct validation on naturalistic data, a more
diverse coverage, and ability to generalize beyond the dataset
and generate commonly observed dynamic occlusion crashes in
traffic in an automated manner. </p>
  </div>
</div>

<h2>Waterloo Multi-Agent Traffic Dataset</h2>

<div class="row">
  <div class="column2" style="background-color:#FFFFFF;">
    <img class="fit-picture" style="width: 55vw;"
     src="/images/wmad.png"
     alt="Image of Waterloo Multi-Agent Traffic Dataset screenshot">
  </div>
  <div class="column1" style="background-color:#FFFFFF;">
  <p> A multi-agent dataset of traffic interactions covering various scenarios, such as, busy intersections, crosswalk interaction with pedestrians, roundabouts, and interaction between pedetrians and AV. The dataset is under active development, and the intersection and crosswalk dataset is available <a href="http://wiselab.uwaterloo.ca/waterloo-multi-agent-traffic-dataset/">here</a></p>
  </div>
</div>

<h2>Taxonomy of strategic and non-strategic interactions</h2>

<div class="row">
  <div class="column2" style="background-color:#FFFFFF;">
    <img class="fit-picture" style="width: 55vw;"
     src="/images/taxonomy.png"
     alt="Image showing the taxonomy organization of strategic interactions in traffic">
  </div>
  <div class="column1" style="background-color:#FFFFFF;">
  <p>In order to enable autonomous vehicles (AV) to navigate busy traffic situations, in recent years there has been a focus on game-theoretic models for strategic behavior planning in AVs. However, a lack of common taxonomy impedes a broader understanding of the strategies the models generate as well as the development of safety specification to identity what strategies are safe for an AV to execute. Based on common patterns of interaction in traffic conflicts, we develop a taxonomy for strategic interactions along the dimensions of agents' initial response to right-of-way rules and subsequent response to other agents' behavior. Furthermore, we demonstrate a process of automatic mapping of strategies generated by a strategic planner to the categories in the taxonomy, and based on vehicle-vehicle and vehicle-pedestrian interaction simulation, we evaluate two popular solution concepts used in strategic planning in AVs, QLk and Subgame perfect epsilon-Nash Equilibrium, with respect to those categories. </p>
  </div>
</div>

</body>
</html>