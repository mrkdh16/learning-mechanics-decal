---
title: Home
layout: home
nav_order: 1
---

# Welcome to the Learning Mechanics DeCal!
*Learning Mechanics* is the emerging discipline that treats deep learning the way physics treats the natural world: seeking compact mathematical principles, tight connections between theory and experiment, and simple, intuitive explanations for complex phenomena. Pieces of a scientific theory for deep learning are beginning to fit together, and in this course, we will examine what has been assembled so far, what remains contested, and where the field is heading.

Deep learning is among the most powerful technologies humans have ever built, and understanding it promises to be one of the defining intellectual challenges of the early 21st century. As of 2026, the engineering success of deep learning has dramatically outpaced our scientific understanding of it. Closing that gap may amount to founding a genuinely new field of science—one whose implications for our understanding of intelligence, data, and learning extend well beyond the neural networks that motivated it.

Readings draw heavily from the whitepaper _There Will Be a Scientific Theory of Deep Learning_ (Simon et al., 2026) and the primary literature it synthesizes. We will work through the theoretical tools, empirical regularities, and open questions that are laying the groundwork for a physics-like understanding of deep learning.

<div class="course-calendar" markdown="0">
  <div class="course-calendar__header">
    <h2>Course Calendar</h2>
    <p>Schedule is subject to change.</p>
  </div>

  <div class="cal-timeline">

    <!-- Week 1 ----------------------------------------------------------- -->
    <div class="cal-week cal-week--off">
      <div class="cal-week__marker"><span class="week-num">Wk 1</span></div>
      <div class="cal-week__card">
        <div class="cal-week__title">First Week &mdash; No Class</div>
      </div>
    </div>

    <!-- Week 2 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 2</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 1</span>
          Introduction I: Learning Mechanics
        </h3>
        <p class="cal-week__question">
          What&rsquo;s the evidence for an emerging scientific theory of deep learning?
        </p>
        <div class="cal-week__resources">
          <span class="cal-week__tag cal-week__tag--reading">Reading: Simon et al. (2026)</span>
        </div>
      </div>
    </div>

    <!-- Week 3 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 3</span></div>
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
          <span class="cal-week__tag cal-week__tag--notes">Lecture Notes</span>
          <span class="cal-week__tag cal-week__tag--homework">Homework: optional math review</span>
        </div>
      </div>
    </div>

    <!-- Week 4 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 4</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 3</span>
          Analytically Solvable Settings I: Deep Linear Networks
        </h3>
        <p class="cal-week__question">
          What can we learn about deep learning from a highly mathematically tractable toy model in deep linear networks?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/1312.6120">Reading: Saxe et al. (2014)</a>
          <a class="cal-week__tag cal-week__tag--notes" href="#">Lecture Notes</a>
          <a class="cal-week__tag cal-week__tag--homework" href="#">Homework</a>
        </div>
      </div>
    </div>

    <!-- Week 5 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 5</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 4</span>
          Analytically Solvable Settings II + Insightful Limits I: The Neural Tangent Kernel and Kernel Regression
        </h3>
        <p class="cal-week__question">
          How do neural networks simplify in the infinite-width limit?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/1902.06720">Reading: Lee et al. (2019)</a>
          <a class="cal-week__tag cal-week__tag--optional" href="https://arxiv.org/pdf/1806.07572">Optional Reading: Jacot et al. (2020)</a>
          <span class="cal-week__tag cal-week__tag--notes">Lecture Notes</span>
        </div>
      </div>
    </div>

    <!-- Week 6 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 6</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 5</span>
          Analytically Solvable Settings III: Eigenlearning and the HEA
        </h3>
        <p class="cal-week__question">
          How can we develop a mathematical framework to study kernel regression? Can we predict how kernel regression will perform on real data?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/2110.03922">Reading: Simon et al. (2023)</a>
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/2510.14878">Reading: Karkada et al. (2026)</a>
          <span class="cal-week__tag cal-week__tag--notes">Lecture Notes</span>
        </div>
      </div>
    </div>

    <!-- Week 7 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 7</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 6</span>
          Disentangling Hyperparameters I + Insightful Limits II: The Lazy (NTK) and Rich (&mu;P) Regimes
        </h3>
        <p class="cal-week__question">
          In the lazy (NTK) regime, neural networks don&rsquo;t learn any structure. Is there a regime where they do?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/2404.19719">Reading: Karkada et al. (2024)</a>
          <a class="cal-week__tag cal-week__tag--optional" href="https://proceedings.mlr.press/v139/yang21c/yang21c.pdf">Optional Reading: Yang et al. (2021)</a>
          <a class="cal-week__tag cal-week__tag--notes" href="#">Lecture Notes</a>
          <span class="cal-week__tag cal-week__tag--homework">Homework</span>
        </div>
      </div>
    </div>

    <!-- Week 8 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 8</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 7</span>
          Analytically Solvable Settings IV: Balancedness and Feature Learning
        </h3>
        <p class="cal-week__question">
          Are there toy models where we can exactly characterize a lazy/rich phase transition?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://proceedings.neurips.cc/paper_files/paper/2024/file/94074dd5a072d28ff75a76dabed43767-Paper-Conference.pdf">Reading: Kunin et al. (2024)</a>
          <a class="cal-week__tag cal-week__tag--notes" href="#">Lecture Notes</a>
          <a class="cal-week__tag cal-week__tag--homework" href="#">Homework</a>
        </div>
      </div>
    </div>

    <!-- Week 9 ----------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 9</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 8</span>
          Universality I: The Platonic Representation Hypothesis
        </h3>
        <p class="cal-week__question">
          Do deep learning models learn similar representations of data across diverse architectures?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/2405.07987">Reading: Huh et al. (2024)</a>
          <span class="cal-week__tag cal-week__tag--notes">Lecture Notes</span>
        </div>
      </div>
    </div>

    <!-- Week 10 ---------------------------------------------------------- -->
    <div class="cal-week cal-week--off">
      <div class="cal-week__marker"><span class="week-num">Wk 10</span></div>
      <div class="cal-week__card">
        <div class="cal-week__title">Thanksgiving Break &mdash; No Class</div>
      </div>
    </div>

    <!-- Week 11 ---------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 11</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 10</span>
          Universality II: Fourier Features in Learned Representations
        </h3>
        <p class="cal-week__question">
          What kind of features are learned by language models? How might we characterize where such features come from and how they&rsquo;re learned?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/2602.15029">Reading: Karkada et al. (2026)</a>
          <a class="cal-week__tag cal-week__tag--notes" href="#">Lecture Notes</a>
          <a class="cal-week__tag cal-week__tag--homework" href="#">Homework</a>
        </div>
      </div>
    </div>

    <!-- Week 12 ---------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 12</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 11</span>
          Empirical Laws I: The Edge of Stability
        </h3>
        <p class="cal-week__question">
          Why do neural networks routinely train successfully while hovering on the very brink of numerical divergence?
        </p>
        <div class="cal-week__resources">
          <a class="cal-week__tag cal-week__tag--reading" href="https://arxiv.org/pdf/2209.15594">Reading: Damian et al. (2023)</a>
          <span class="cal-week__tag cal-week__tag--notes">Lecture Notes</span>
        </div>
      </div>
    </div>

    <!-- Week 13 ---------------------------------------------------------- -->
    <div class="cal-week cal-week--off">
      <div class="cal-week__marker"><span class="week-num">Wk 13</span></div>
      <div class="cal-week__card">
        <div class="cal-week__title">Buffer Week</div>
      </div>
    </div>

    <!-- Week 14 ---------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 14</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 13</span>
          Final Project Hypothesis Presentations
        </h3>
      </div>
    </div>

    <!-- Week 15 ---------------------------------------------------------- -->
    <div class="cal-week">
      <div class="cal-week__marker"><span class="week-num">Wk 15</span></div>
      <div class="cal-week__card">
        <h3 class="cal-week__title">
          <span class="lecture-num">Lecture 14</span>
          Final Project Office Hours
        </h3>
      </div>
    </div>

    <!-- Week 16 ---------------------------------------------------------- -->
    <div class="cal-week cal-week--off">
      <div class="cal-week__marker"><span class="week-num">Wk 16</span></div>
      <div class="cal-week__card">
        <div class="cal-week__title">RRR Week &mdash; No Class</div>
      </div>
    </div>

  </div>
</div>



# Q&A
What is a *[DeCal](https://lsadvising.berkeley.edu/news/whats-deal-decals)*?


