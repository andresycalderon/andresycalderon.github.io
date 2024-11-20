---
layout: archive
permalink: /publications/
title: "Research"
---

## Working Papers

* **The Impact of Hard Discount Stores on Local Labor Markets: Evidence from Colombia** <!--- *([pdf](/assets/Gambling_IS.pdf))*  [[SSRN]](https://ssrn.com/abstract=3020332) -->
	*(with [Lukas Delgado-Prieto](https://ludelgad.github.io/) and [Andrea Otero](https://sites.google.com/view/andrea-otero-cortes/home))* *([pdf](https://repositorio.banrep.gov.co/bitstream/handle/20.500.12134/10785/DTSERU_326.pdf?sequence=9&isAllowed=y))* 
	
	**Abstract**:
  Hard discount stores have reshaped the retail sector by selling low-cost products. While this business model has gained market shares in many countries, how it affects the labor market is unclear. To fill this gap, we study the impact of discount stores on local labor markets in Colombia,  where these stores had a rapid, staggered geographic expansion. Our results show that discount stores boost local formal employment, especially in retail, manufacturing, and agriculture, suggesting significant spillover effects from retail to other sectors. Consistent with this finding, we also document increases in local tax revenues from manufacturing and commerce activities.



* **The impact of discretionary hiring on bureaucrats’ corruption perceptions, satisfaction, and the mishandling of public resources** *([pdf](../files/discretionaryselection27Dec22.pdf))* 

	**Abstract**:
	This paper examines the impact in a developing country of adopting a system of selection of civil servants through discretionary and temporary contracts on three aspects of the public sector: corruption perceptions of bureaucrats, job satisfaction, and the mishandling of public resources. I study the impact of a legislative reform that incentivized certain Colombian public agencies to hire personnel using the direct-procurement regime. Relying on a *diffence-in-differences* design, I find a relative increase in the awareness of nepotism, the influence of political networks, and the role of money and favors in the selection processes of territorial-order entities, which were the most affected by the reform. Civil servants in these agencies also experienced a differential decrease in satisfaction with job characteristics, and the institutions were more likely to appear in bulletins of sanctions for mishandling of resources. Household data suggests an actual deterioration of meritocracy, and triple difference analyses propose that an image of unfairness in hiring practices might drive the effects on perceptions and satisfaction.




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
