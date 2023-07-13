---
layout: post
title:  "we need to return to first principles"
date:   2023-07-12 00:00:00 -0400
categories: ai
---

**Thesis.** We need to return to first principles and engineer more sustainable deep learning systems.

**Motivation.** There are several motivations here that describe suboptimal properties of the intelligence of these systems (as opposed to the capability).

1. *Impracticality.* Current deep learning systems are monolithic and unwieldy. The training of the best models takes hundreds of millions of dollars, petabytes of data, and hundreds of thousands of GPU hours.
2. *Inflexibility.* Current deep learning systems are frozen compressions of the world. Any updates or revisions to the system require fine-tuning or complete pre-training at similar scale.
3. *Expertise.* Current models still exhibit tradeoffs in fidelity and diversity (we see the best systems sidestep this by implementing a mixture of experts) which require larger models be built to close gaps in expertise.

These fallacies of current implementations bring to light a handful of deeper symptoms.

1. *Governance.* Properties 1 and 2 place the exclusive control of deep learning systems to the oligopoly that produce them.
2. *Privacy.* Property 3 suggests that the best systems are tailored to the individual use case, but Properties 1 and 2 are usually prohibitively expensive and also require invasive data collection techniques.
3. *Saliency.* Methods trying to achieve Property 3 and circumvent Property 1 realize the data saliency is paramount. So much generated content will be on the internet soon that it will be nearly impossible to cherry-pick real high-quality data, which will become ever scarcer.

**Proposition.** All of the above call for a return to the need for architecting deep learning systems from first principles. Below are the properties that will bring us to the next optimum of intelligent and flexible systems.

1. *Multi-modality.* Compression of multi-modal data will shortcut the learning curve by forming richer abstractions across more anchor points to the world.
2. *Reflexivity.* Ability to recognize self-shortcomings and self-improvements will further improve data effectiveness and in-domain expertise.
3. *Autonomy.* Combined with the first two points, autonomy will allow the system to scalably improve on its own.

Ultimately, we want a system whose learning process we can control with chat, not just a system whose capabilities we can control with chat. Capabilities are the byproduct of intelligence.
