---
layout: page
title: Vex V5 Competitions
description: Overall Work
img:
importance: 4
category: Work
---

### Change Up
My first season in Vex was the Change Up season. The goal of the game was to score balls of your alliance color while de-scoring opposing colors. There were additional bonus points awarded based off of varitations of tik-tack-toe rules. 

The below images and videos document a brief sequence in our design process. I functioned as co-programmer and Creo modeler for this season. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/C_1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/C_2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/C_3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/change_side.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        <video muted controls>
            <source src="{{'assets/video/ChangeUp.MOV' | relative_url}}">
        </video>
    </div>
</div>
The team won the Vex Skills and Excellence awards at states this season.

Overall, the change up season introduced me to the competiton and taught me important engineering fundamentals such as design process, 3D CAD modeling, and coding for electronics.

### Tipping Point
This was my second season in Vex. The goal of the game was to score mobile goals and rings onto a platform or in the home zone.

This season was challenging with the change of team members that occured. We lost 6 of the 10 members at the time and the remaining 4 of us had little experience. Despite this we still perceviered. 

Our initial design utilized a goal focus over ring focus. We created a 6-bar lift along with a cantilever on the back to effectivley pick up two goals.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/T_14.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/T_13.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/T_12.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/T_10.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


This design furthur developed after feedback and testing showed the cantilever was not mechanically sound enough to go low enough to pick up the goal without passive locking and dragging on the ground. We also observed tippage from the distance the 6-bar moved away from the center of gravity. 
Thus our next design featured a U-lift and 4-bar lift to solve the afformentioned issues. Through some polishing of these features and changing the chassis structure to 4-wheel from 6-wheel we concluded with the final design.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/T_7.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/T_6.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/T_5.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Tip_2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Tip_3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Tip_4.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

For programming I was responsible for programming not only driver controls but also several 15 second autonomous routines and a 1 minute autonomous skills routine. This included the maintance of a previously developed turn PID and the development of other feedback controllers for increasing the accuracy of autonomous routines.

This season I took the role of team lead and lead programmer. Through these roles I better refined my coding abilities and my understanding of teamwork and management. During league competitions we won the excellence award. However, there were no awards taken home during the state championship because of unforseen mechanical issues.

### Spin Up

This was last season in vex. The game Spin Up was designed like disc golf where points were earned by shooting disks into one of two goals. Points could also be earned by spinning rollers or expanding the robot's dimensions during endgame to claim territory.

Our original concept was a turret robot where the launcher for discs was placed on a turntable. We had also discussed building an x drive so we didn't have to worry about turning to face the goal. This plan heavily relied on my ability to code control algorithms and my previously developed odometry and PID's. There were several ideas to create an auto aiming turret like the Vex Vision Sensor or relying on the relative postion in comparision to the goal's coordinates.

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/s_1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/s_31.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row mt-3">
    <div class="col-12">
        <video class="img-fluid rounded z-depth-1" controls>
            <source src="{{ 'assets/video/IMG_8420.mp4' | relative_url }}" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>
The odometry I programmed which can be seen in it's own project was not fully tested before the season started. While it worked it may not have been realiable enough for some of our ideas. The vision sensor alternative was tested to turn to face an object that looked like the goal. Despite its promise it proved to have several issues with detecting the goal and distinguishing that from similar colored objects. While there are no doubt solutions to those problems I feared we would not have the time to implement and test them as the auto aimer was proving to be time consuming to develop. The turret design was scrapped because of that and issues with the stability of the Vex turntable we had access to.

Thus the design pivoted to nromal flywheel with a 3600 rpm from gearing. The design relied on an indexer to push disks from the loading done after the intake into the pre-spinning flywheel. 

Unfortunatley due to time and space constraints throughout the several iterations we had to scrap the proper odometry using dead wheels. To maintain optimal flywheel build up time and maintain speed I programmed a take back half algorithm. This algorithm is used in Vex when you need to approach a target like a PID but rather than slowly stopping you want maintain a value. It works similar to a bang-bang but has more applications with flywheels. Using this and the kinematics of the flywheel I succussfully programmed a method to maintain optimal speed for shooting the disks at any distance from the goal. Our PID's had a bit of an issue with tuning since we utilized a speed drive train as opposed to previous years. This meant I had to spend more time tuning it and learn the behaviors for our system better.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/s_5.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/s_6.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/s_7.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/s_10.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/s_9.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/s_11.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

This year the team won excellence awards at both states and leagues. During the Vex World Championships we were the first New Mexico team to have a positive win-streak and ranked 37th in our division out of 100. Thus concluded my time with Vex.

### Code Links
For the code related to Vex Change Up:[Change up](https://github.com/jhunter533/64846B_20-21_PID)

For the code related to Vex Tipping Point:[Tipping Point](https://github.com/jhunter533/64846B_21-22)

For the code related to Vex Spin Up:[Spin Up](https://github.com/jhunter533/64846B_SpinUp_22-23)
