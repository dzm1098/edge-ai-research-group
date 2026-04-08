---
title: "Research"
layout: default
excerpt: "Research directions in Edge AI, hierarchical inference, and learning-enabled systems"
sitemap: false
permalink: /research/
---

<section class="research-section">
  <h2>Overview</h2>
  <p>
    We are interested in decision-making, learning, and resource
    allocation/scheduling problems that arise in networking and information
    systems. Our current research centers on efficient inference in Edge AI
    systems, including hierarchical inference, inference offloading, and the
    Age of Information.
  </p>
  <p>
    The methods behind this work draw on regret analysis, approximation
    algorithms, queueing theory, stochastic network calculus, and Markov
    decision processes.
  </p>
</section>

<section class="research-section">
  <h2>Hierarchical and Cascade AI</h2>
  <p>
    AI is most useful when it runs where data is created, but the models that
    fit on tiny devices are often weaker than their cloud counterparts. We are
    interested in the algorithmic foundations of device-edge-cloud inference
    pipelines that decide when to answer locally and when to offload.
  </p>
  <p>
    This line of work studies confidence-aware routing, queueing effects,
    regret-optimal offloading, and practical decision modules for
    resource-constrained hardware.
  </p>
  <p class="research-links">
    <a href="{{ site.url }}{{ site.baseurl }}/publications/">See selected publications</a>
  </p>
</section>

<section class="research-section">
  <h2>Inference Offloading and Edge Systems</h2>
  <p>
    We design algorithms for deciding when to run models on-device, when to
    use an edge server, and when to escalate to the cloud. The goal is to
    optimize accuracy, latency, and system cost jointly rather than treating
    them as separate concerns.
  </p>
  <p>
    Recent projects include cost-sensitive binary classification at the edge,
    offloading under time constraints, and offload queues for hierarchical
    inference.
  </p>
</section>

<section class="research-section">
  <h2>Age of Information</h2>
  <p>
    Information freshness matters in distributed sensing, monitoring, and
    control. We study Age of Information as a systems and modeling problem,
    especially when data arrives over constrained or stochastic networks.
  </p>
  <p>
    Our recent work includes spatio-temporal sensing processes and broader
    freshness-aware network analysis.
  </p>
</section>

<section class="research-section">
  <h2>Online Learning and Routing</h2>
  <p>
    We also study online learning formulations that arise in adaptive routing
    and hierarchical inference. This includes regret bounds, stochastic expert
    partitioning, and learning policies that remain robust under uncertainty
    and distribution shift.
  </p>
</section>
