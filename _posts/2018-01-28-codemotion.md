---
layout: post
title: "Exploring new interactions with screencast videos"
permalink: /codemotion
excerpt: Codemotion is a prototype video player created by me for the purpose of surfacing a technical solution in a neutral way, and gathering ideas about where users would like to see it integrated in their own workflows.<br/><br/><img src="/assets/codemotion/ui-cropped.png" />
---

Videos are a pervasive format for delivering online education at scale. They are especially popular for computer programming tutorials since videos convey expert narration alongside the dynamic effects of editing and running code. However, these screencast videos simply consist of raw pixels, so there is no way to interact with the code embedded inside of them. To expand the design space of learner interactions with programming videos, I developed a computer vision algorithm that automatically extracts source code and dynamic edits from existing videos.

I used my algorithm to prototype a novel video player called *Codemotion*. The UI is a kind of a mixed-media (text+video) tutorial viewer that segments a screencast video into chunks based on intervals of related code edits. It was created by me for the purpose of surfacing what the algorithm can do in a neutral way (as far as possible), and gathering ideas about where users would like to see it integrated in their own workflows.
<img src="/assets/codemotion/ui.png" />
<ol type="a">
  <li>The UI first uses the extracted code edits to split the original video into intervals based on groups of closely-related edits. Each mini-video represents the times when the instructor was coding up one specific component of their demo. The corresponding portion of the speech transcript (automatically generated by YouTube) appears above each mini-video.</li>
  <li>As each mini-video plays, the code that's being written in that video gets displayed in a text editor alongside that video. The user can copy-paste the code to play with it themselves.</li>
  <li>If there are multiple code editor panes present in a given video, the user can choose which one gets displayed in the UI.</li>
  <li>The user can search for code (or any text) within the video, and string matches get highlighted in each mini-video.</li>
</ol>

Guided by my advisor, we then elicited ideas from potential users by running an usability study with 10 students followed by four participatory design workshops with 12 other students. Participants collectively generated ideas for 28 kinds of interactions such as inline code editing, code-based skimming, pop-up video search, and in-video coding exercises. (links to [conference talk slides](https://www.icloud.com/keynote/0CrqCVgrx10z1Dov72B_bmG-g#Codemotion-LAS18-Kandarp), [research paper](/files/codemotion-las2018-khandwala.pdf) and [code](https://github.com/kandarpksk/codemotion-las2018))

Check out this 2-minute feature demo of *Codemotion*!
<iframe width="100%" height="500" src="https://www.youtube.com/embed/OPROmzq973A" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
