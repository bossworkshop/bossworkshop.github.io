---
layout: index
title: Programme (PPSN 2024)
description: Schedule of talks and activities at PPSN 2024
---

The workshop will consist of **three invited speakers** (40-45 minutes each) on the workshop topics followed by discussion. Below is the schedule and information about the speakers and planned talks.

## **Schedule**

<table style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr style="background-color: #f5f5f5; border-bottom: 2px solid #ddd;">
      <th style="padding: 10px; text-align: left; border: 1px solid #ddd;">Time</th>
      <th style="padding: 10px; text-align: left; border: 1px solid #ddd;">Activity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 10px; border: 1px solid #ddd;">09:30</td>
      <td style="padding: 10px; border: 1px solid #ddd;"><strong>Welcome/ Workshop opens</strong> (5 mins)</td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td style="padding: 10px; border: 1px solid #ddd;">09:35</td>
      <td style="padding: 10px; border: 1px solid #ddd;"><a href="#elena-raponi"><strong>Elena Raponi</strong> - click for title</a> (45 mins)</td>
    </tr>
    <tr>
      <td style="padding: 10px; border: 1px solid #ddd;">10:20</td>
      <td style="padding: 10px; border: 1px solid #ddd;"><a href="#bhupinder-singh-saini"><strong>Bhupinder Singh Saini</strong> - click for title</a> (45 mins)</td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td style="padding: 10px; border: 1px solid #ddd;">11:05</td>
      <td style="padding: 10px; border: 1px solid #ddd;"><strong>Break</strong> (15 mins)</td>
    </tr>
    <tr>
      <td style="padding: 10px; border: 1px solid #ddd;">11:20</td>
      <td style="padding: 10px; border: 1px solid #ddd;"><a href="#juergen-branke"><strong>Juergen Branke</strong> - click for title</a> (45 mins)</td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td style="padding: 10px; border: 1px solid #ddd;">12:05</td>
      <td style="padding: 10px; border: 1px solid #ddd;"><strong>Opportunity for discussion</strong></td>
    </tr>
    <tr>
      <td style="padding: 10px; border: 1px solid #ddd;">12:30</td>
      <td style="padding: 10px; border: 1px solid #ddd;"><strong>Workshop closes</strong></td>
    </tr>
  </tbody>
</table>

<br>

## **Invited Speakers**

<div id="elena-raponi" style="background-color: #f5f9e9; padding: 15px; margin-bottom: 20px;">
  <div style="display: flex; flex-direction: column;">
    <div style="display: flex; align-items: center;">
      <img src="/images/elena_raponi_profile.jpg" alt="Elena Raponi" style="width: 105px; height: 130px; margin-right: 20px;">
      <div>
        <h3>Elena Raponi</h3>
        <p><strong>Title:</strong> <em>Maximizing Impact with Few Trials Using High-Dimensional Bayesian Optimization</em></p>
      </div>
    </div>
    <div>
      <p><strong>Abstract:</strong> <br> Bayesian Optimization (BO) is a class of powerful surrogate-based, iterative techniques for the optimization of expensive black-box functions. In this talk, I will provide a comprehensive overview of state-of-the-art methodologies in high-dimensional BO, focusing on strategies that address the curse of dimensionality and maximize efficiency and accuracy within small evaluation budgets.
I will present a range of techniques, including variable selection, additive models, and methods for search space reduction such as the use of trust regions and both linear and nonlinear mappings. Additionally, I will discuss case studies demonstrating the application of BO in engineering design, highlighting its significant potential for solving complex problems in both academic and industrial contexts. The presentation will conclude with an examination of current challenges and open questions in the field, identifying key areas for future research.</p>
      <p><strong>Bio:</strong><br>
      Elena Raponi is an Assistant Professor in the Natural Computing Research Group at the Leiden Institute of Advanced Computer Science, Leiden University. Previously, she was a Postdoctoral Researcher at the Technical University of Munich, Chair of Computational Mechanics, and Sorbonne University, LIP6 Department. Her position was funded by a DAAD Prime Postdoctoral Fellowship, which was awarded in December 2021. She received her Ph.D. in Applied Mathematics from the University of Camerino, Italy, in May 2021. Her research mainly focuses on surrogate-based optimization in continuous domains, high-dimensional Bayesian optimization, and analytical and numerical modeling techniques for the optimization of geometries and materials in structural mechanics.</p>
    </div>
  </div>
</div>

<div id="bhupinder-singh-saini" style="background-color: #f9f7e9; padding: 15px; margin-bottom: 20px;">
  <div style="display: flex; flex-direction: column;">
    <div style="display: flex; align-items: center;">
      <img src="/images/Bhupinder_Saini_profile.jpg" alt="Bhupinder Singh Saini" style="width: 130px; height: 130px; margin-right: 20px;">
      <div>
        <h3>Bhupinder Singh Saini</h3>
        <p><strong>Title:</strong> <em>Multiobjective Optimization Method for Problems with Expensive Objective Function Evaluations: Optimistic NAUTILUS Navigator</em></p>
      </div>
    </div>
    <div>
      <p><strong>Abstract:</strong> <br>Real-world multiobjective optimization problems often involve expensive-to-evaluate objective functions. One way to solve such problems is through the use of so-called online data-driven multiobjective optimization algorithms. These algorithms use data (either pre-existing or generated before optimization) to train surrogate models to replace the expensive objective functions during optimization to generate an approximate non-dominated front. Notably, these algorithms evaluate a few solutions intermittently using the expensive objective functions and retrain the surrogate models to increase the accuracy of the approximation. In practice, however, often, the goal in solving multiobjective optimization problems is to find only one (or few) solutions that are of interest to a decision maker/problem owner. Therefore, spending expensive objective function evaluations with the aim of finding solutions that may not be of interest to the DM may be wasteful.</p>
      <p>In this talk, we showcase an interactive method called O-NAUTILUS, which merges ideas from evolutionary multiobjective optimization and multiple criteria decision making communities. It extends the ideas of trade-off free search and navigation provided by the NAUTILUS Navigator method to surrogate-assisted optimization. It utilizes uncertainty quantification from surrogate models like Kriging or properties like Lipschitz continuity to approximate a so-called optimistic Pareto optimal set. This enables the decision maker to search in unexplored parts of the Pareto optimal set and requires a small amount of expensive objective function evaluations. These evaluations are focused on the decision maker's region of interest, thus making sure that expensive function evaluations are utilized efficiently. O-NAUTILUS comes with a graphical user interface, allowing a decision maker to control the optimization and decision-making process in real-time using intuitive controls.</p>
      <p><strong>Bio:</strong><br> Bhupinder Singh Saini is a Postdoctoral Researcher in the Multiobjective Optimization Group at the University of Jyväskylä. He received his M.Tech degree from the Indian Institute of Technology Kharagpur in 2018 and his PhD from the University of Jyväskylä in 2022. He was awarded MCDM Doctoral Dissertation award in 2024 by the International Society on MCDM. His research interests include multiobjective optimization, interactive methods, data visualization, online and offline data-driven optimization, development of evolutionary algorithms, and real-world applications. He is also one of the primary contributors to the DESDEO framework, an open-source Python framework for interactive multiobjective optimization.</p>
    </div>
  </div>
</div>

<div id="juergen-branke" style="background-color: #e9f1e9; padding: 15px; margin-bottom: 20px;">
  <div style="display: flex; flex-direction: column;">
    <div style="display: flex; align-items: center;">
      <img src="/images/juergen_branke_profile.jpg" alt="Juergen Branke" style="width: 130px; height: 130px; margin-right: 20px;">
      <div>
        <h3>Juergen Branke</h3>
        <p><strong>Title:</strong> <em>Bayesian Optimisation with Simulation Input Uncertainty:</em></p>
      </div>
    </div>
      <p><strong>Abstract:</strong><br> Bayesian optimisation has proven a very sampling-efficient simulation optimisation algorithm. However, in many cases, the input parameters of the simulation model (e.g., arrival time distributions) are not precisely known. In this talk, I will present how Bayesian optimisation can handle input uncertainty, and even decide whether it is more beneficial to spend additional simulation effort, or collect additional data to reduce the input uncertainty. Finally, we will discuss how the presented framework can also be used in interactive multi-objective optimisation to decide when and how often to interact with a decision maker.</p>    
    <div>
      <p><strong>Bio:</strong><br>
      Juergen Branke is Professor of Operational Research and Systems at Warwick Business School, University of Warwick (UK). His main research interests include metaheuristics and Bayesian optimisation applied to problems under uncertainty, such as simulation optimisation, dynamically changing problems, and multi-objective problems.</p>
      <p>Prof. Branke is Editor of ACM Transactions on Evolutionary Learning and Optimization, Area Editor of the Journal of Heuristics and the Journal on Multi-Criteria Decision Analysis, as well as Associate Editor of the Evolutionary Computation Journal.</p>
    </div>
  </div>
</div>

