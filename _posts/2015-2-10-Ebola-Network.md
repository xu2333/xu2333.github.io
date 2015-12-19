---
layout: post
title: Ebola Network -- Mathematical Contest In Modeling
---

Our goal is to establish a delivery system that optimizes the control and eradication of Ebola.

This question was thrown by the Consortium for Mathematics and Its Application in the 2015 Mathematical Contest in Modeling.
Facing with such inconceivable issue, our team chose complex networks theory to design a model. By the way, I were primarily responsible for mathematical analysis and programming.

Firstly, we explored the spreading patterns among social contact networks. 

![mcm_1.png]({{ site.baseurl }}/images/mcm_1.png)

Secondly, we extended our model and enabled it to reflect geographical information in Python.

![mcm_2.png]({{ site.baseurl }}/images/mcm_2.png)

![mcm_4.png]({{ site.baseurl }}/images/mcm_4.png)

After calculating with respective parameters, we obtained the simulation curves. Following pictures shown part of them.

![mcm_5.png]({{ site.baseurl }}/images/mcm_5.png)

Thirdly, we proposed optimal delivery scenario based on our extended model.

![mcm_3.png]({{ site.baseurl }}/images/mcm_3.png)

Finally, we analyzed all the simulation result and proposed an dynamic programming solution indicating the exact quantity of needed medicine for each district.

Our [**Report**](https://raw.githubusercontent.com/xu2333/xu2333.github.io/master/pdf/MCM.pdf) (in English) was designated as Meritorious Winner, top 9% among 7636 participants.

![certificate.jpg]({{ site.baseurl }}/images/certificate.jpg)