---
layout: post
title: "Making a D3.js bubble chart to visualize lines of dialogue in The Office (U.S.)"
date: 2018-04-27
---

[/r/dataisbeautiful](https://www.reddit.com/r/dataisbeautiful/) has monthly data visualization battles where moderators choose a dataset and participants post their data visualizations. For April 2018, the dataset was every line of dialogue in the American version of the TV show The Office.

I’ve been wanting to learn more D3.js so I decide to pick [one of the visualizations featured in the D3.js gallery](https://github.com/d3/d3/wiki/Gallery).

Jim Vallandingham created [this viz for the Gates Foundation’s spending](http://vallandingham.me/vis/gates/). While it's true that [Bubble charts are not really the best way to visualize data for a variety of reasons](http://junkcharts.typepad.com/junk_charts/2013/03/blowing-the-whistle-at-bubble-charts.html
), I think this visualization is engaging from a UX standpoint. (And honestly, I figured Reddit would be all over something fairly flashy.)

Mostly, bubble charts can lead to very misleading representations of data. But after playing around with Vallandingham’s viz, I wanted to apply it to my Office dataset. The first thing I wanted to ask&mdash;who speaks the most?

Michael Scott is the boss of Dunder Mifflin. He obviously has a lot of lines throughout the show, but who else has the most dialogue? Is it consistent across the seasons of the show?

The second thing I wanted to know: what is the highest frequency of words each character uses?

[This is what I ended up with](https://joeforyou.github.io/office-text-analysis).