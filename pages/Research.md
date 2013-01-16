---
layout: page
title: "Research"
description: ""
group: "navigation"
---
{% include JB/setup %}

For now, I'm working on dynamic models, where the utility of an agent not only depends on his decisions today, but also on decisions he'll make tomorrow. A basic example is the famous cake eating problem, where an agent receives a cake and has to decide on when to eat it. Should the agent eat everything today, leave some for tomorrow, or eat it whole tomorrow? There exist a lot of methods to estimate such models, and I started looking into simulated maximum likelihood estimators. [Here](simulated_max_lik.html) you'll find an example taken from Cameron and Trivedi's book - Microeconometrics Methods and Applications, where the authors maximize a simulated log likelihood. I attempted to translate the code to R.

More to come soon.