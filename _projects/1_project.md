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
Many decision support systems are dependent on the ability to accurately model user preferences. However, people's preferemces are contextual and often change throughout the decision-making process. Moreover, traditional optimization techniques require full knowledge of the model's objective and constraints. 

To address these issues, we built a system that combined LLMs with constraint programming: LLMs facilitated natural communication between the user and the system, translating user preferences into constraint functions for the optimization solver. We studied this hybrid framework through the lens of meeting scheduling, a time-consuming daily activity faced by a multitude of information workers.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project/meetmate/model.png" title="MeetMate Model" class="img-fluid rounded z-depth-1" alt="MeetMate supports preference elicitation through preference construction and preference incorporation." %}
    </div>
</div>

## Approach
 To evaluate our framework, we conducted three studies: 

1. A diary study to characterize contextual scheduling preferences
2. A quantitative evaluation of the system's performance
3. A user study that used our system as a technology probe to elicit design insights

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project/meetmate/approach.png" title="MeetMate Approach" class="img-fluid rounded z-depth-1" alt="MeetMate combines LLMs and Constraint Programming to facilitate meeting scheduling." %}
    </div>
</div>

## Results
Our work highlights the potential for a hybrid LLM and optimization approach for iterative preference elicitation and design considerations for building systems that support human-system collaborative decision-making processes {% cite 10.1145/3685053 %}.


