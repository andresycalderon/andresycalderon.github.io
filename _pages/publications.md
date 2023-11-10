---
layout: archive
permalink: /publications/
title: "Research"
---

## Working Papers

* **The Impact of Hard Discount Stores on Local Labor Markets: Evidence from Colombia** <!--- *([pdf](/assets/Gambling_IS.pdf))*  [[SSRN]](https://ssrn.com/abstract=3020332) -->
	*(with [Lukas Delgado-Prieto](https://ludelgad.github.io/) and [Andrea Otero](https://sites.google.com/view/andrea-otero-cortes/home))*
	
	**Abstract**:
  Hard discount stores have disrupted traditional retail worldwide by selling low-priced products, yet their impact on the labor market is under-researched. To fill this gap in the literature, we study the impact of the entry of these stores on local labor markets in Colombia. We exploit the staggered geographic expansion of the leading hard discount chains across the country and combine it with administrative records on social security and taxes and survey data on the formal and informal sectors to analyze the evolution of labor market outcomes. Our findings show that the entry of hard discounters to a municipality increases local formal employment, particularly in retail, manufacturing, and agriculture. This suggests that there are important spillovers from retail to other industries because most of the goods these stores sell are locally sourced. Regarding the informal sector, the increase in competition among formal and informal retailers does not significantly reduce informal employment in retail. Still, we find a negative trend in informal retailers' labor income, which suggests that the margin of adjustment is via lower earnings due to a decline in profits. These findings have important implications for policymakers and local businesses in developing countries.



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
