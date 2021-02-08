---
layout: post
title: "Exploring new interactions with screencast videos"
permalink: /codemotion
excerpt: I created a prototype mixed-media (text+video) tutorial viewer called Codemotion that segments a screencast video into chunks based on intervals of related code edits. <img src="/assets/codemotion/ui-cropped.png" style="border: 3px solid \#555" />
---

Videos are a pervasive format for delivering online education at scale. They are especially popular for computer programming tutorials since videos convey expert narration alongside the dynamic effects of editing and running code. However, these screencast videos simply consist of raw pixels, so there is no way to interact with the code embedded inside of them. To expand the design space of learner interactions with programming videos, I developed a computer vision algorithm that automatically extracts source code and dynamic edits from existing videos.

Guided by my advisor, I used the algorithm to power a novel video player called *Codemotion* and then elicited ideas from potential users by running an usability study with 10 students followed by four participatory design workshops with 12 other students. Participants collectively generated ideas for 28 kinds of interactions such as inline code editing, code-based skimming, pop-up video search, and in-video coding exercises. (links to [conference talk slides](https://www.icloud.com/keynote/0CrqCVgrx10z1Dov72B_bmG-g#Codemotion-LAS18-Kandarp), [research paper](/files/codemotion-las2018-khandwala.pdf) and [code](https://github.com/kandarpksk/codemotion-las2018))

Check out this 2-minute feature demo of *Codemotion*!
<iframe width="560" height="315" src="https://www.youtube.com/embed/OPROmzq973A" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
