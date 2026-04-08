---
title: "Home"
layout: homelay
excerpt: "Edge AI Research Group at the University of Victoria"
sitemap: false
permalink: /
---

{% assign latest_news = site.data.news | first %}

<h1>Welcome to the Edge AI Research Group</h1>

<p><strong>News ({{ latest_news.date }}): {{ latest_news.title }}</strong></p>

<p>
  The Edge AI Research Group is led by
  <a href="{{ site.url }}{{ site.baseurl }}/team/jaya-prakash-champati">Jaya Prakash Champati</a>
  in the Department of Computer Science at the University of Victoria.
</p>

<p>
  We study decision-making, learning, and resource allocation problems in
  networking and information systems. Our current interests include Edge AI,
  hierarchical inference, inference offloading, Age of Information, online
  learning, and network-aware decision systems.
</p>

<div id="carousel" class="carousel slide" data-ride="carousel" data-interval="4000" data-pause="hover">
  <ol class="carousel-indicators">
    <li data-target="#carousel" data-slide-to="0" class="active"></li>
    <li data-target="#carousel" data-slide-to="1"></li>
    <li data-target="#carousel" data-slide-to="2"></li>
  </ol>

  <div class="carousel-inner">
    <div class="item active">
      <img src="{{ site.url }}{{ site.baseurl }}/images/slider/slider-image.png" alt="Research group placeholder image" />
    </div>
    <div class="item">
      <div class="carousel-placeholder">Lab photo placeholder</div>
    </div>
    <div class="item">
      <div class="carousel-placeholder">Research photo placeholder</div>
    </div>
  </div>

  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

<p>
  Jaya Prakash Champati received his PhD in Electrical and Computer
  Engineering from the University of Toronto in 2017, after earlier degrees
  from IIT Bombay and NIT Warangal. Before joining UVic, he was a Research
  Assistant Professor at IMDEA Networks Institute and a postdoctoral
  researcher at KTH Royal Institute of Technology.
</p>

<p>
  Recent work from the group spans hierarchical inference with offload queues,
  cost-efficient LLM shepherding, inference offloading for binary
  classification at the edge, and freshness-aware sensing systems. We combine
  theory, algorithms, and systems thinking to make AI practical in real
  deployments.
</p>

<p>
  <strong>We are happy to hear from motivated students and collaborators
  interested in Edge AI, networking, learning, queueing, and information
  freshness</strong> <a href="{{ site.url }}{{ site.baseurl }}/openings/">(more info)</a>.
</p>

<figure class="logo-strip">
  <p>
    <img src="{{ site.url }}{{ site.baseurl }}/images/logo/lab-logo.png" style="width: 130px" alt="{{ site.title }} logo" />
  </p>
</figure>
