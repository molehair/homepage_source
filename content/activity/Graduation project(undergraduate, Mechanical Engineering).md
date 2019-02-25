---
date: 2014-12-03
title: Graduation project(undergraduate, Mechanical Engineering)
highlight: "true"
---

As a senior in Mechanical Engineering, I was demanded to participate in a project for my diploma. Among many projects, one in [RISE lab](http://ris.skku.edu/) intrigued me. The project entailed programming skills as well as knowledge of mechanical engineering.

Problem:

> Given a range sensor, make a mobile robot navigate a corridor environment. Full exploration is proven by acquiring the entire map.

[Generalized Voronoi Graph(GVG)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.52.8858&rep=rep1&type=pdf) is one of famous methods for a mobile robot to walk through corridor areas.

<img class="img" src="/activity/Graduation project(undergraduate, Mechanical Engineering)/gvg.png">

The above image is a result of GVG. The lines between thick walls show the path on which a mobile robot goes.

There are two improvements than previous implementation. First, GVG had been implemented with 360°-range sensor. However, what we were given was 180° one, where I enjoyed in a sense. Second, it takes some time for a mobile robot to have stable move along aisles. This settling time was reduced in this project.

Given [this robot](http://www.mobilerobots.com/ResearchRobots/PioneerP3DX.aspx), we tested in the following environment.

<img class="img" src="/activity/Graduation project(undergraduate, Mechanical Engineering)/4th-floor-of-Corporate-Collaboration-Center-at-SKKU.png">

and what we earn is

<img class="img" src="/activity/Graduation project(undergraduate, Mechanical Engineering)/gvg-result.png">

The map from the robot is bent due to the inherent error inside robot. They say it is difficult to get precise map without reference points.

An award always make me happy.

<img class="img" src="/activity/Graduation project(undergraduate, Mechanical Engineering)/graduation_ME_award.jpg">

Details are written into [dissertation](/activity/Graduation project(undergraduate, Mechanical Engineering)/2014.GraduationDissertation.MobileRobot.pdf).