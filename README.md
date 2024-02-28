# ATLAS 🌍

Final year project by [Jesse Amarquaye](mailto:jesseamarquayelegendary@gmail.com "Send email") and Greatman Akomea,
computer engineering students from [Ghana Communication Technology University](https://www.gctu.edu.gh "GCTU").

## Table Of Contents

- [Introduction](#introduction)
  - [Why work on hallucination in LLMs?](#why-work-on-hallucination-in-llms)
  - [Why Atlas?](#why-atlas)
  - [Aims or Objectives](#aims-or-objectives)
- [Methodology](#methodology)

## Introduction

Atlas is a hallucination detector for Large Language Models.
Its main focus is on **generative text** as that is the most widely used medium for interacting with LLMs.

### Why work on hallucination in LLMs?

Large language models (LLMs) are revolutionizing human-computer interaction, generating increasingly _fluent_ and
_human-like text_.
However, a significant challenge in LLMs is their tendency to produce **hallucinations**, or factually incorrect,
nonsensical, or misleading content.
As humans become increasingly reliant on LLMs for information and decision-making, ensuring their reliability and
accuracy is crucial.
This project aims to address this challenge by developing a software for **detecting** and **mitigating**
hallucinations in LLMs so users can rely on LLM outputs with greater confidence, leading to wider adoption and
societal benefits and also reduces the risk of misinformation to promote responsible use of LLMs.

### Why Atlas?

The story of Atlas in Greek mythology is closely tied to his role in supporting the heavens. According to one myth,
during the _Titanomachy; the war between the Titans and the Olympian gods_, Atlas sided with the Titans. After their
defeat, Zeus condemned Atlas to bear the weight of the heavens on his shoulders for eternity.

The name **Atlas** symbolizes the software's commitment to bearing the responsibility of overseeing the cognitive
aspects of language models, maintaining their stability, and preventing them from collapsing into inaccuracies or
hallucinations. The association with Atlas also conveys _strength_, _resilience_, and _reliability_, suggesting a
software that can handle the weight of complex language processing tasks with steadfastness and precision.

### Aims or Objectives

- [x] Explore techniques for mitigating hallucinations in LLMs.
- [ ] Develop a software for automatic detection of hallucinations in LLMs.
- [ ] Evaluate the effectiveness of the developed tool in different LLMs.

## Methodology

Our approach will be the design and implementation of a software to detect or flag and mitigate
hallucinations in LLMs.
The ultimate objective is the creation of a browser extension to actively scan the output from LLMs and
compare them with results from trusted sources on the web and inform the user of any occurrence of hallucinations.
An additional feature (probably in the future) will be to find the sources of the response the LLM generated.

<details>

<summary> View Flow Diagram </summary>

![Flow diagram](docs/img/flow.svg)

</details>
