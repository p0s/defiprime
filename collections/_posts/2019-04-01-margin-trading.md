---
layout: page
title:  "Margin trading"
permalink: margin-trading
h1title: Margin trading
pagetitle: Decentralized margin trading - DeFi Short and Leveraged trading platforms    
metadescription: Decentralized margin trading refers to the practice of using borrowed funds from a broker to trade a financial asset, which forms the collateral for the loan from the broker.
category: products
---
Decentralized margin trading refers to the practice of using borrowed funds from a broker to trade a financial asset, which forms the collateral for the loan from the broker.

{% for margin-trading in site.margin-trading %}
### <a href="{{ margin-trading.product-url }}?ref=defiprime.com">{{ margin-trading.product-title }}</a>{% if margin-trading.ecosystem contains 'ethereum' %} ![](images/ether.png "Built on Ethereum or related to Ethereum ecosystem"){% endif %} {% if margin-trading.ecosystem contains 'bitcoin' %} ![](/images/btc.png "Using Bitcoin ecosystem"){% endif %} {% if margin-trading.ecosystem contains 'eos' %} ![](/images/eos.png "Built on EOS or related to EOS ecosystem"){% endif %}

![]({{ margin-trading.image }})

{{ margin-trading.product-description }}

{% endfor %}