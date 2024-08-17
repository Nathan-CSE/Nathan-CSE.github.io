---
layout: page
title: aKin Winter Hackathon
description: Received 1st place for developing a solution to teach robots new behaviours through user-defined outcomes and actions.
img: assets/img/akin/thumbnail.jpg
importance: 1
category: competitions
---
### Overview

In July 2024, I joined Vincent Ho, Tharun Yogenthra, and Cooper Haiden to take part in aKin's Winter Hackathon. Together, we developed a solution that enables users to teach robots new behaviors as part of the software stream of the hackathon.

Over the two-day event, we focused on understanding human communication to serve as the basis of our final solution, which emphasised contextual decision-making as a core feature. 

When learning new behaviours and making decisions, the robot would take into consideration both its overarching goal (as defined by the user) in addition to both explicit and implicit user interactions. For instance, in service of ensuring an user's happiness, the robot may interpret an explicit request to clean up the living room. In addition to this, the robot may observe that the user has a tendency to leave the living room in disarray, and as such, may take the initiative to learn new behaviours in service of its overarching goal of ensuring user happiness.

These behavioural routines would be retrieved from a company cloud service, and then modified by the robot to fit the current environmental context and it's overarching goal. These routines would also exist in the form of scheduled and conditional behaviours, with the former being executed at set times throughout the week to align with a user's needs, with latter being executed when a user provides an explicit instruction.

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/akin/systemDiagram.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
  The system diagram for our solution.
</div>

Users interact with the robot primarily through a mobile app. On initial set up, users specify their preferences, goals and special needs that the robot needs to consider. From there, the robot creates its behavioural routines and populates the behaviour schedule and list of saved routines. Users are able to provide feedback to the robot based on its actions (explicit action) which the robot can use to further fine-tune its behaviours. Users are also able to modify their routines in an intuitive drag-and-drop interface (similar to Scratch) and share routines online with other users.

<div class="row">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/akin/mockups.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/akin/routines.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
  Prototypes for the mobile app, including the behaviour schedule, suggestions features and routine editing tools.
</div>

Overall, the hackathon was an amazing experience and whilst participating at the event I was able to gain insight regarding aKin's unique approach to developing artificial intelligence models. Our team was able to place first overall which was an amazing result and I definitely learned a lot from this experience.

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/akin/thumbnail.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
  The system diagram for our solution.
</div>