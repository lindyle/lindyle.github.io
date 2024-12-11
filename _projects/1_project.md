---
layout: page
title: meetmate
description: interactive decision support using LLMs and constraint programming
permalink: /projects/meetmate/
img: assets/img/project/1.png
img_alt: "MeetMate project thumbnail"
importance: 1
category: human-centered ai
related_publications: true
---
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project/meetmate/meetmateui.png" title="MeetMate UI" class="img-fluid rounded z-depth-1" alt="MeetMate supports preference elicitation and decision making within the context of meeting scheduling." %}
    </div>
</div>

## Project Overview
 Decision support systems rely on <a href="https://core.ac.uk/download/pdf/147923741.pdf" target="_blank">accurate modeling of user preferences</a>. However, the uncertainty and inconsistency of human preferences <a href="https://link.springer.com/article/10.1007/s11257-011-9116-6" target="_blank">complicates the preference elicitation process</a> between systems and users. MeetMate combined Large Language Models (LLMs) and Constraint Programming to facilitate interactive decision support.

## My Role
I coordinated and facilitated 10 semi-structured interviews to test the usability of MeetMate. I open-coded all 10 interview sessions and organized the data into affinity diagrams to collaboratively iterate on themes using reflexive thematic analysis. I also collaborated with Dr. Jina Suh to develop an interaction model for MeetMate's preference elicitation process.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project/meetmate/model.png" title="MeetMate Model" class="img-fluid rounded z-depth-1" alt="MeetMate supports preference elicitation through preference construction and preference incorporation." %}
    </div>
</div>

## Motivations
The goal of MeetMate was to study how decision support systems can account for the dynamic and subliminal nature of human preferences in decision making.

## Approach
MeetMate supported iterative preference elicitation through a hybrid LLM and Constraint Programming approach. LLMs enabled an intuitive way for users to communicate their preferences and easily translated preferences into structured constraint functions. Constraint Programming techniques allowed the system to reason over the space of outcomes to find optimal solutions given users' expressed preferences. 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project/meetmate/approach.png" title="MeetMate Approach" class="img-fluid rounded z-depth-1" alt="MeetMate combines LLMs and Constraint Programming to facilitate meeting scheduling." %}
    </div>
</div>

## Outcomes
Although users enjoyed the ability to use natural language with MeetMate, they wanted the system to be context-adaptive and provide greater flexibility over what gets optimized. We contributed implications for designing systems that support collaborative human-AI decision-making processes in a paper published in the ACM Transactions on Interactive Intelligent Systems (TiiS) 2024 {% cite 10.1145/3685053 %}.

## Takeaways
This project showed me the importance of an enactivist approach to human-AI interaction research, balancing AI optimization with user agency, to augment and not replace human interactions.


