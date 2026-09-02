---
title: Home
layout: home
nav_order: 1
---

# Welcome to the Learning Mechanics DeCal!
Deep learning is in a peculiar situation at this moment in time. Empirically, the capabilities of AI leveraging deep learning (eg. LLMs) have surpassed the expectations of even the most radically optimistic researchers. Publicly available LLMs are [disproving math conjectures](https://x.com/__alpoge__/status/2079028340955197566) left and right, AI is being [injected into every stage of real drug development life cycles](https://icml.cc/virtual/2026/invited-talk/67266), entire [business models have been destroyed](https://tinyurl.com/2hhcsnz7) by improving AI capabilities, and at this point, AI [winning a Nobel Prize](https://www.nobelprize.org/prizes/chemistry/2024/press-release/) is old news. Yet, we lack a comprehensive scientific framework for understanding 
how exactly these models work and the development of frontier models is closer to alchemy than science.

Not long ago, engineers built working steam engines before anyone understood the science behind them. The effort to understand and build better engines ended up creating an entirely new branch of science: statistical mechanics. Deep learning may be our generation's steam engine. _Learning mechanics_ is the emerging discipline that aims to understand it from first principles, treating deep learning the way physics treats the natural world: seeking compact mathematical principles, tight connections between theory and experiment, and simple, intuitive explanations for complex phenomena.

This course is for those who want to be part of building that new science.

Readings draw heavily from the perspective paper <a href="https://arxiv.org/pdf/2604.21691">_There Will Be a Scientific Theory of Deep Learning_ (Simon et al., 2026)</a> and the primary literature it synthesizes.

All [lecture notes](course-notes.html) and [homework](problem-sets.html) are also linked inline below, next to the week they belong to.

<div class="course-calendar" markdown="0">
  <div class="course-calendar__header">
    <h2>Course Calendar</h2>
    <p>Schedule is subject to change.</p>
  </div>

  <div class="cal-timeline">

    <!-- Week 1 ----------------------------------------------------------- -->
    <div class="cal-week cal-week--off">
      <div class="cal-week__marker"><span class="week-num">Wk 1</span><span class="week-date">Aug 26</span></div>
      <div class="cal-week__card">
        <div class="cal-week__title">First Week &mdash; No Class</div>
      </div>
    </div>

    <!-- Week 2 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 2</span><span class="week-date">Sep 2</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 1</span>
          Introduction I: Learning Mechanics
        </h3>
        <p class="cal-week__question">
          What&rsquo;s the evidence for an emerging scientific theory of deep learning?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/2604.21691">Reading: Simon et al. (2026)</a>
          <a class="cal-week__tag cal-week__tag--reading-q" href="https://docs.google.com/forms/d/e/1FAIpQLSdxmAe4dqHV26jDM7UiSWOU30WLIsgPNhhUo5TO-vGOZiR7Fg/viewform?usp=header" target="_blank">Pre-Semester Survey</a>
        </div>
      </div>
    </div>

    <!-- Week 3 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 3</span><span class="week-date">Sep 9</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 2</span>
          Introduction II: Neural Networks
        </h3>
        <p class="cal-week__question">
          What exactly are neural networks? Why are they hard to study? How will we study them anyways?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="http://neuralnetworksanddeeplearning.com">Reading: Nielsen (2019)</a>
          <a class="cal-week__tag cal-week__tag--reading-q" href="https://docs.google.com/forms/d/e/1FAIpQLSd-XSV_Wll4IonOXK-dmwT3RqUgmapmEEPuwdXb5e3GMSNL9g/viewform?usp=header" target="_blank">Reading Questions</a>
          <a class="cal-week__tag cal-week__tag--notes" href="lecture-notes/ch1.pdf">Lecture Notes</a>
          <a class="cal-week__tag cal-week__tag--homework" href="problem-sets/ps1.pdf">Homework</a>
        </div>
      </div>
    </div>

    <!-- Week 4 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 4</span><span class="week-date">Sep 16</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 3</span>
          Toy Model I: Deep Linear Networks
        </h3>
        <p class="cal-week__question">
          What can we learn about deep learning from a highly mathematically tractable toy model in deep linear networks?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/1312.6120">Reading: Saxe et al. (2014)</a>
          <a class="cal-week__tag cal-week__tag--notes" href="lecture-notes/ch2.pdf">Lecture Notes</a>
        </div>
      </div>
    </div>

    <!-- Week 5 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 5</span><span class="week-date">Sep 23</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 4</span>
          Toy Model I: Deep Linear Networks (continued)
        </h3>
        <p class="cal-week__question">
          How can we analytically solve for the training dynamics of deep linear networks?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--notes" href="lecture-notes/ch2.pdf">Lecture Notes</a>
          <a class="cal-week__tag cal-week__tag--homework" href="problem-sets/ps2.pdf">Homework</a>
        </div>
      </div>
    </div>

    <!-- Week 6 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 6</span><span class="week-date">Sep 30</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 5</span>
          Toy Model II: Kernel Regression and the NTK
        </h3>
        <p class="cal-week__question">
          Is there a limit in which neural networks become analytically solvable?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/1902.06720">Reading: Lee et al. (2019)</a>
          <a class="cal-week__tag cal-week__tag--optional" href="https://arxiv.org/pdf/1806.07572">Optional Reading: Jacot et al. (2020)</a>
          <a class="cal-week__tag cal-week__tag--notes" href="lecture-notes/ch3.pdf">Lecture Notes</a>
        </div>
      </div>
    </div>

    <!-- Week 7 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 7</span><span class="week-date">Oct 7</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 6</span>
          Toy Model II: Kernel Regression and the NTK (continued)
        </h3>
        <p class="cal-week__question">
          How can we develop a mathematical framework to study kernel regression? Can we predict how kernel regression will perform on real data?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/2110.03922">Reading: Simon et al. (2023)</a>
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/2510.14878">Reading: Karkada et al. (2026)</a>
          <a class="cal-week__tag cal-week__tag--notes" href="lecture-notes/ch3.pdf">Lecture Notes</a>
          <span class="cal-week__tag cal-week__tag--homework">Homework</span>
        </div>
      </div>
    </div>

    <!-- Week 8 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 8</span><span class="week-date">Oct 14</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 7</span>
          The Lazy (NTK) and Rich (&mu;P) Regimes
        </h3>
        <p class="cal-week__question">
          In the lazy (NTK) regime, neural networks don&rsquo;t learn any structure. Is there a regime where they do?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/2310.17813">Reading: Yang et al. (2024)</a>
          <span class="cal-week__tag cal-week__tag--notes">Lecture Notes</span>
        </div>
      </div>
    </div>

    <!-- Week 9 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 9</span><span class="week-date">Oct 21</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 8</span>
          The Lazy (NTK) and Rich (&mu;P) Regimes (continued)
        </h3>
        <p class="cal-week__question">
          How can we disentangle hyperparameters to maximize feature learning?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/2310.17813">Reading: Yang et al. (2024)</a>
          <span class="cal-week__tag cal-week__tag--notes">Lecture Notes</span>
          <span class="cal-week__tag cal-week__tag--homework">Homework</span>
        </div>
      </div>
    </div>

    <!-- Week 10 ---------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 10</span><span class="week-date">Oct 28</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 10</span>
          Case Study I: Grokking
        </h3>
        <p class="cal-week__question">
          How can we apply the tools of learning mechanics to understand grokking?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/2406.06158v2">Reading: Kunin et al. (2024)</a>
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/2310.06110">Reading: Kumar et al. (2024)</a>
          <a class="cal-week__tag cal-week__tag--optional" href="https://arxiv.org/pdf/2301.05217">Optional Reading: Nanda et al. (2023)</a>
          <span class="cal-week__tag cal-week__tag--notes">Lecture Notes</span>
          <span class="cal-week__tag cal-week__tag--homework">Homework</span>
        </div>
      </div>
    </div>

    <!-- Week 11 ---------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 11</span><span class="week-date">Nov 4</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 11</span>
          Case Study II: Representational Geometry
        </h3>
        <p class="cal-week__question">
          What kind of features are learned by language models? How might we characterize where such features come from and how they&rsquo;re learned?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/2602.15029">Reading: Karkada et al. (2026)</a>
          <span class="cal-week__tag cal-week__tag--notes">Lecture Notes</span>
          <span class="cal-week__tag cal-week__tag--homework">Homework</span>
        </div>
      </div>
    </div>

    <!-- Week 12 ---------------------------------------------------------- -->
    <div class="cal-week cal-week--off">
      <div class="cal-week__marker"><span class="week-num">Wk 12</span><span class="week-date">Nov 11</span></div>
      <div class="cal-week__card">
        <div class="cal-week__title">Buffer Week</div>
      </div>
    </div>

    <!-- Week 13 ---------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 13</span><span class="week-date">Nov 18</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 13</span>
          Final Project Hypothesis Presentations
        </h3>
      </div>
    </div>

    <!-- Week 14 ---------------------------------------------------------- -->
    <div class="cal-week cal-week--off">
      <div class="cal-week__marker"><span class="week-num">Wk 14</span><span class="week-date">Nov 25</span></div>
      <div class="cal-week__card">
        <div class="cal-week__title">Thanksgiving Break &mdash; No Class</div>
      </div>
    </div>

    <!-- Week 15 ---------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 15</span><span class="week-date">Dec 2</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 14</span>
          Final Project Office Hours
        </h3>
      </div>
    </div>

    <!-- Week 16 ---------------------------------------------------------- -->
    <div class="cal-week cal-week--off">
      <div class="cal-week__marker"><span class="week-num">Wk 16</span><span class="week-date">Dec 9</span></div>
      <div class="cal-week__card">
        <div class="cal-week__title">RRR Week &mdash; No Class</div>
      </div>
    </div>

  </div>
</div>

---

[^1]: From [Wikipedia](https://en.wikipedia.org/wiki/First_principle): "*In physics and other sciences, theoretical work is said to be from first principles, or ab initio, if it starts directly at the level of established science and does not make assumptions such as empirical model and parameter fitting. "First principles thinking" consists of decomposing things down to the fundamental axioms in the given arena, before reasoning up by asking which ones are relevant to the question at hand, then cross referencing conclusions based on chosen axioms and making sure conclusions do not violate any fundamental laws.*"