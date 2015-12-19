---
layout: post
title: Web Hearthstone -- Browser/Server Game Design
---

To be honest, if Hearthstone was a web game, it would definitely attract more players because of convenience.

During my course of Browser/Server Architecture Software Design, I came up with this idea in a sudden moment.
Since our group of two directly used the screenshots as cards, there is no need for art designer. We both became programmers.

Our Apache server was located on my computer, supporting register, log-in, ranking list and card appreciation.
The communications were implemented through Web Socket. All the data were stored in MySQL.

Following pictures show the functions of our system.

![hs_1.jpg]({{ site.baseurl }}/images/hs_1.jpg)

![hs_2.jpg]({{ site.baseurl }}/images/hs_2.jpg)

The card appreciation module helped new comers to know different cards.

![hs_3.jpg]({{ site.baseurl }}/images/hs_3.jpg)

![hs_4.jpg]({{ site.baseurl }}/images/hs_4.jpg)

Ranking list were counted by Crystal, which was the same with points in standings.

![hs_5.jpg]({{ site.baseurl }}/images/hs_5.jpg)

Our game interface was kind of geek.

![hs_6.jpg]({{ site.baseurl }}/images/hs_6.jpg)

![hs_7.jpg]({{ site.baseurl }}/images/hs_7.jpg)

Your minions could attack enemy minion or enemy hero once a turn.

![hs_8.jpg]({{ site.baseurl }}/images/hs_8.jpg)

![hs_9.jpg]({{ site.baseurl }}/images/hs_9.jpg)

When your enemy hero's health got to zero, you would win this game.

![hs_10.jpg]({{ site.baseurl }}/images/hs_10.jpg)

Our [**Report**](https://raw.githubusercontent.com/xu2333/xu2333.github.io/master/pdf/hearthstone.pdf) (in Chinese) provided more details. You can also experience the complete game process by watching [**Demo**](http://v.youku.com/v_show/id_XMTQxNzk4NjM3Ng==.html) .