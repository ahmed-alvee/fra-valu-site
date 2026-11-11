---
layout: default
title: Ahmed Alvee, AI and workflow automation
description: >-
  I turn manual processes into production systems. Available for contract
  work now, through my KVK-registered practice in Rotterdam.
permalink: /
---

<section class="hero" id="top">
  <div class="wrap hero-inner">
    <h1>I turn manual processes<br><span class="accent">into production systems.</span></h1>
    <p class="hero-lead">I spent over three years building data pipelines and integrations across five markets, and now do that work on my own from Rotterdam.</p>
    <div class="cta-row">
      <a class="btn btn-primary" href="#contact">Get in touch</a>
      <a class="btn btn-outline-inverse" href="#work">See the work</a>
    </div>
    <p class="hero-meta">Available for contract work now</p>
  </div>
</section>

<nav class="subnav" aria-label="Section">
  <div class="wrap">
    <a href="#about">About</a>
    <a href="#work">Work</a>
    <a href="#how">How I work</a>
    <a href="#hire">Working with me</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<section id="about">
  <div class="wrap intro-split">
    <p class="eyebrow">Hello</p>
    <div class="intro-text">
      <p>I am Alvee. I am finishing an MBA at Rotterdam School of Management. I like the way systems fit together, and that is what led me into solutions architecture. Most of my working life has gone into turning a task a team does by hand every week into something that runs on its own.</p>
    </div>
  </div>
</section>

<section id="work">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">Selected work</p>
      <h2>Four things I built, and what changed.</h2>
      <p>All of this was done in earlier roles, before I started working on my own.</p>
    </div>

    <div class="service-grid">
      <div class="service-card">
        <h3>Clinical records, thirty clinics</h3>
        <p>More than thirty clinics sent CSV and Excel files with different column and package names, and a person cleaned each file by hand in about an hour.</p>
        <p class="card-result">An hour a file became six to ten minutes, including human review.</p>
        <p class="card-meta">Mesh Bio, Singapore &middot; LangGraph, Claude on Bedrock, Pydantic, ChromaDB</p>
      </div>

      <div class="service-card">
        <h3>Onboarding new labs and clinics</h3>
        <p>Every new lab and clinic needed its own hardcoded Lambda, which meant copying code and testing incoming data against it. I rebuilt it as one pipeline driven by configuration. It is still in use across Hong Kong, the Philippines, Singapore, Malaysia and Indonesia.</p>
        <p class="card-result">Onboarding improved from 3-5 days to under 1 day.</p>
        <p class="card-meta">Mesh Bio, Singapore &middot; AWS Lambda, SQS, SNS, EventBridge Pipes, Step Functions</p>
      </div>

      <div class="service-card">
        <h3>A first overseas customer, and a team of three</h3>
        <p>The first overseas customer had a deadline and its own way of working. I recommended an API-based workflow, cut the scope to fit, and led three weeks of on-site deployment. I later built and led a team of three solutions engineers, who took over and expanded the APIs and pipelines.</p>
        <p class="card-result">The customer became a lighthouse account with follow-on regional projects.</p>
        <p class="card-meta">Mesh Bio, Singapore &middot; Leading a team of 3 solutions engineers</p>
      </div>

      <div class="service-card">
        <h3>Portfolio monitoring</h3>
        <p>An impact investor monitored its portfolio by hand. We defined the problem with the client, designed a five-stage monitoring workflow, and built AI tools and agents as proofs of concept and an MVP across all five stages, from data clean-up to reporting. I pitched the recommendations to the investor's leadership.</p>
        <p class="card-result">Projected to improve monitoring time by about 45%.</p>
        <p class="card-meta">With four classmates, Rotterdam School of Management &middot; Gemini, Claude and Tally.so</p>
      </div>
    </div>

    <div class="feature" style="margin-top:48px">
      <div>
        <p class="eyebrow">Built on my own</p>
        <h3>Electives navigator</h3>
        <p>Every year my school hands students a stack of PDFs: a course overview, a schedule, an outline per class. None of it is a calendar, so everyone copies the dates across by hand and hopes nothing clashes.</p>
        <p>I built a tool that handles all of it at once. You pick your courses and see them on a real calendar, clashes are flagged automatically, and instructor backgrounds are a click away.</p>
                <p><a class="btn btn-outline" href="https://ahmed-alvee.github.io/mba27-electives/" rel="noopener" target="_blank">Open the navigator</a></p>
      </div>
      <figure class="shots">
        <a href="{{ '/assets/hire-electives-calendar.jpg' | relative_url }}" target="_blank" rel="noopener"><img src="{{ '/assets/hire-electives-calendar.jpg' | relative_url }}" alt="Electives navigator calendar view, showing a term's course sessions colour-coded by subject"></a>
        <a href="{{ '/assets/hire-electives-conflicts.jpg' | relative_url }}" target="_blank" rel="noopener"><img src="{{ '/assets/hire-electives-conflicts.jpg' | relative_url }}" alt="Electives navigator conflict panel, flagging overlapping course sessions"></a>
        <figcaption>Tap a screenshot to see it full size.</figcaption>
      </figure>
    </div>

    <div class="feature" style="margin-top:48px">
      <div>
        <p class="eyebrow">Before the data work</p>
        <h3>Robots, and the software around them</h3>
        <p>At SUTD in Singapore I mapped two floors and five rooms in under six minutes with a system of twelve or more robots, owning the locomotion code, and wrote C++ for a legged mapping robot. I built a machine-learning pipeline that recognized seven hand gestures to command unmanned vehicles, and designed a custom Bluetooth board for a knitted knee-monitoring wearable, published in Advanced Healthcare Materials in 2023.</p>
        <p>Then, at a Singapore medtech company, I owned the annotation and user-interaction layer of the imaging software for a robot that ablates cancer cells with focused ultrasound, including DICOM export.</p>
      </div>
      <div class="video-frame">
        <iframe src="https://www.youtube-nocookie.com/embed/qfH4ocXLslI" title="Autonomous robot navigation, SUTD" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" loading="lazy" allowfullscreen></iframe>
      </div>
    </div>
  </div>
</section>

<section id="how" class="band-cream">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">How I work</p>
      <h2>I build the one thing that pays back first.</h2>
    </div>
    <div class="flow">
      <div class="flow-step">
        <div class="flow-num">1</div>
        <h3>Map the work</h3>
        <p>I sit with the people doing the work and find out where the hours actually go.</p>
      </div>
      <div class="flow-step">
        <div class="flow-num">2</div>
        <h3>Rank and price</h3>
        <p>Every repeated task gets a cost. Most are not worth automating, and I say so before you spend anything.</p>
      </div>
      <div class="flow-step">
        <div class="flow-num">3</div>
        <h3>Build</h3>
        <p>I build with plain tools, inside the systems you already run, and the code is yours to keep.</p>
      </div>
      <div class="flow-step">
        <div class="flow-num">4</div>
        <h3>Measure what changed</h3>
        <p>I check what it saved. If it came in under what I expected, you hear that from me first.</p>
      </div>
    </div>

    <dl class="spec" style="margin-top:44px">
      <div class="spec-row">
        <dt>Languages</dt>
        <dd>I work in Python, and have shipped production C++ and Qt.</dd>
      </div>
      <div class="spec-row">
        <dt>AI and agents</dt>
        <dd>LangChain, LangGraph, Amazon Bedrock, Claude, Gemini, Pydantic, ChromaDB and n8n.</dd>
      </div>
      <div class="spec-row">
        <dt>Cloud and infrastructure</dt>
        <dd>AWS Lambda, SQS, SNS, Step Functions and Terraform. I am an AWS Certified Solutions Architect – Associate.</dd>
      </div>
    </dl>
  </div>
</section>

<section id="hire">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">Working with me</p>
      <h2>You can bring me in on contract today.</h2>
    </div>

    <ul class="timeline">
      <li class="tl-item is-now">
        <span class="tl-when">Now</span>
        <p class="tl-what"><b>I am available for contract work and can start immediately.</b> Engagements are invoiced through Fravalu, my KVK-registered practice in Rotterdam.</p>
      </li>
      <li class="tl-item">
        <span class="tl-when">March 2027</span>
        <p class="tl-what">I graduate from Rotterdam School of Management.</p>
      </li>
    </ul>

    <dl class="spec">
      <div class="spec-row">
        <dt>Where I am based</dt>
        <dd>Rotterdam, and I work on site when a project calls for it.</dd>
      </div>
      <div class="spec-row">
        <dt>Fixed-fee audit</dt>
        <dd>I log how your team spends its week, price each repeated task, and hand you a ranked list of what is worth automating. The list is yours to keep.</dd>
      </div>
      <div class="spec-row">
        <dt>Earlier career</dt>
        <dd>I spent three and a half years at Mesh Bio in Singapore, from 2022 to 2025, and became a Solutions Architect leading a team of three solutions engineers. Before that I was a software engineer at a Singapore medtech company and a research assistant in robotics and wearable systems at SUTD.</dd>
      </div>
    </dl>
  </div>
</section>

<section id="contact" class="band-tint">
  <div class="wrap contact-grid">
    <div>
      <p class="eyebrow">Let's talk</p>
      <h2 style="font-size:clamp(28px,3.4vw,38px)">Tell me where the hours go.</h2>
      <p style="font-size:18px;color:var(--slate);max-width:48ch;margin:0 0 28px">Pick a time below, or email me directly. I will take it from there.</p>
      <div class="cta-row" style="padding-left:0">
        <a class="btn btn-primary" href="mailto:contact@fra-valu.com">contact@fra-valu.com</a>
        <a class="btn btn-outline" href="https://linkedin.com/in/alveeahmed" rel="noopener" target="_blank">LinkedIn</a>
      </div>
    </div>

    <div class="booking-card">
      <p class="sh-label" style="margin:0 0 14px">Pick a time</p>
      <div class="calendly-inline-widget"
        data-url="https://calendly.com/alvee-fra-valu/30min?hide_landing_page_details=1&background_color=FFFFFF&text_color=112733&primary_color=00684A"
        style="min-width:280px;height:640px;"></div>
      <script type="text/javascript" src="https://assets.calendly.com/assets/external/widget.js" async></script>
      <noscript>
        <p style="margin:0;font-size:14px;color:var(--slate)">Booking needs JavaScript. Write to
          <a href="mailto:contact@fra-valu.com">contact@fra-valu.com</a> and I will send you times.
        </p>
      </noscript>
    </div>
  </div>
</section>
