---
layout: page
title: Crosslinguistic Emotion Classification
description: An interpretable speech emotion recognition study examining where SER models diverge from human perception.
img: vivid-blurred-colorful-background.jpg
importance: 1
category: work
related_publications: true
---

<hr />

<h2>Problem</h2>
<p>
Many speech emotion recognition (SER) systems achieve high accuracy using large, opaque feature sets, but it remains unclear whether these models rely on the same cues humans use to perceive emotion. This limits interpretability, robustness, and cross-linguistic generalization.
</p>

<hr />

<h2>Approach</h2>
<p>
This project analyzes emotional speech using a <strong>psychoacoustic model of voice quality</strong> that captures perceptually meaningful acoustic dimensions. Human emotion ratings and machine predictions are compared within a shared representational space, and <strong>cross-linguistic comparison metrics</strong> are incorporated to examine variation in emotion acoustics across languages.
</p>

<hr />

<h2>Takeaway</h2>
<p>
The analysis highlights where machine emotion recognition aligns with—and diverges from—human auditory perception, demonstrating the value of <strong>interpretable, perceptually grounded features</strong> for building more transparent and cross-linguistically aware affective speech systems.
</p>

<hr />

<h2>Methods (High-Level)</h2>
<ul>
  <li>
    Cross-linguistic speech emotion analysis using two acted corpora:
    <strong>SUBSECO (Bengali)</strong> and <strong>RAVDESS (English)</strong>, selected for cultural and phonological contrast with comparable validation standards.
  </li>
  <li>
    Unimodal audio-only focus to isolate vocal cues relevant to human emotion perception and enable controlled cross-corpus comparison.
  </li>
  <li>
    Psychoacoustic feature modeling capturing harmonic, inharmonic, prosodic, and temporal aspects of voice quality.
  </li>
  <li>
    Human–machine comparison framework aligning model predictions with perceptual ratings rather than treating labels as ground truth.
  </li>
  <li>
    Integration of cultural distance measures to contextualize acoustic variation across populations.
  </li>
</ul>

<hr />

<h2>Key Insights</h2>
<ul>
  <li>
    Human listeners and machine models rely on overlapping but systematically different acoustic cues when classifying emotion.
  </li>
  <li>
    Cross-linguistic variation reflects both similarities and differences in emotion acoustics.
  </li>
</ul>

<hr />

<h2>Tools &amp; Techniques</h2>
<ul>
  <li>Speech signal processing and acoustic analysis</li>
  <li>Psychoacoustic modeling of voice quality</li>
  <li>Cross-linguistic data analysis</li>
  <li>Human perceptual data integration</li>
  <li>SER model evaluation</li>
  <li>Large-scale dataset curation and normalization with millions of rows</li>
</ul>

<hr />
