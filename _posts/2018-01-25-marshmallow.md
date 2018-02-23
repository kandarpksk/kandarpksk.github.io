---
layout: post
title: "android permissions reimagined"
permalink: /marshmallow
excerpt: Starting from Marshmallow (v6), Android allows the user to place an app either in a position of absolute distrust or one with a high level of trust. We show how this does not offer the flexibility to allow certain actions while preventing undesirable ones. This paper aims to address the problem by bringing out potential misuse of permissions to the user’s attention. To do so, we come up with a new way to assign and declare permissions that can minimize interactions between two sensitive resources which we argue to be what really needs to be monitored and controlled. We also perform static code analysis of seven open-source applications to measure the impact of the proposed model both in terms of usability and from the perspective of developers.
---

<!-- note: sync with excerpt -->
Starting from Marshmallow, Android allows the user to place an app either in a position of absolute distrust or one with a high level of trust. We[^1] show how this does not offer the flexibility to allow certain actions while preventing undesirable ones. This paper aims to address the problem by bringing out potential misuse of permissions to the user’s attention. To do so, we come up with a new way to assign and declare permissions that can minimize interactions between two sensitive resources which we argue to be what really needs to be monitored and controlled. We also perform static code analysis of seven open-source applications to measure the impact of the proposed model both in terms of usability and from the perspective of developers.
<a target="_blank" href="http://kandarp.xyz/files/kandarp-permissions.pdf">(link to paper)</a>

<!-- Defined a new, secure permission model for Android that prevents misuse of permissions while reducing user interruption -->

[^1]: along with Ajay Mohan, Heli Modi, Shreeja Kumar and Yu Shen
