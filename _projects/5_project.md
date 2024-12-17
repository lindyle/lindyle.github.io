---
layout: page
title: "esa: emotional support agent"
description: just-in-time interventions to reduce workplace stress
permalink: /projects/esa/
img: assets/img/project/5.png
img_alt: "Esa project thumbnail"
importance: 2
category: accessibility
related_publications: false
---
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div class="project-image">
            <iframe
                src="https://www.youtube.com/embed/1JuiYTbozD8"
                width="930"
                height="523.13"
                frameborder="0"
                allowfullscreen="true"
                title="Esa project pitch video">
            </iframe>
        </div>
    </div>
</div>

## Project Overview
Mental health problems are the leading cause of disability worldwide, <a href="https://pubmed.ncbi.nlm.nih.gov/30729322/" target="_blank">affecting over 1 billion people</a>. Moreover, workplace stress is the <a href="https://www.stress.org/workplace-stress" target="_blank">number one source of stress for American adult</a>s, costing the U.S. economy $300 billion annually. Both these issues were <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7260522/" target="_blank">exacerbated by the COVID-19 pandemic</a>. Esa was a low-cost, intelligent stress-reduction application to address unmet mental health needs and lower workplace stress.

## Approach
Esa originated from my lived experiences with anxiety and depression and was inspired by my emotional support animal, Sasha. Through therapy, I learned that emotional awareness, including mindfulness of stress, is integral to managing my mental health. To that end, I searched high and low for a financially accessible wearable with accurate stress detection, but struggled to find one.

Thus, Esa was an embodied agent designed to serve three main functions: 

1. <strong>Detect user stress</strong>- Esa leveraged the HUE group's <a href= "https://arxiv.org/pdf/1903.12133.pdf" target="_blank">prior research on affective computing</a> to detect user emotion from passive laptop sensors. Data was collected every second from camera, microphone, and application activity and aggregated to calculate a stress score.

2. <strong>Deliver therapeutic interventions</strong>- Esa prompted the user with a just-in-time intervention when it detected that the user's stress level may have been high. Interventions came from a list of evidence-based stress reduction techniques, based on the HUE group's previous research on <a href="https://www.microsoft.com/en-us/research/uploads/prod/2018/03/pn3413-paper.pdf" target="_blank">technologies to support Dialectical Behavioral Therapy</a>.

3. <strong>Adapt to user insights</strong>- Esa used machine learning to personalize stress detection and intervention recommendations for each user. Users could view historical data about their stress levels and completed interventions to build self-awareness about and promote engagement with personal well-being improvements.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project/esa/approach.png" title="Esa Approach" class="img-fluid rounded z-depth-1" alt="Esa delivering a stress intervention that involved deep breathing." %}
    </div>
</div>

## My Role
I created the project concept, designed the interactions, and drove the collaboration with Microsoft Research's Human Understanding and Empathy (HUE) group to build the application.

## Outcomes
Esa resonated with many leaders at Microsoft, winning 2nd place in Microsoft's Global Hackathon. The success of the project led Microsoft to further invest in cognitive and mental health accessibility (see my <a href="/projects/calmerweb/" target="_blank">A Calmer Web</a> project). Additionally, Esa became the prototype for the HUE group's subsequent research on <a href="https://www.microsoft.com/en-us/research/uploads/prod/2022/10/Stress_Sensing_2022.pdf" target="_blank">just-in-time micro-interventions to reduce workplace stress</a>. For more details, see the ACII '23 workshop paper <a href="https://www.microsoft.com/en-us/research/uploads/prod/2023/10/ACII_2023_mWell__Challenges_of_Deploying_Wellbeing_Sensing.pdf" target="_blank">Towards Successful Deployment of Wellbeing Sensing Technologies: Identifying Misalignments across Contextual Boundaries</a>.
