---
layout: examples
title:  Amazon
description: Amazon Automation
date: 2021-03-01
toc: true
author: Dhruv Techapps
tags: ["amazon", "auto like", "auto clicker", "auto fill"]
---
# Sign In

{{< readfile highlight="json" file="json/amazon/Amazon_SignIn.json" >}}

{{< readfile highlight="json" file="json/amazon/Amazon_Trigger_Login.json" >}}

{{<callout>}}
<h3>Important</h3>
<p>Order of configuration should be Sign In as <code>first</code> and <code>Trigger Login</code> second</p>
<ul class="list-group list-group-flush">
  <ol class="list-group-item">Amazon Trigger Login is used to click on login link </ol>
  <ol class="list-group-item">Amazon Sign is used to click on login link </ol>
</ul>
{{</callout>}}

{{<img amazon-reorder.png>}}