---
title: "The Ghost in the Bronze"
date: 2026-07-31 20:00:00 +0700
permalink: /posts/2026/07/ghost-in-the-bronze/
categories:
  - Reflection
tags:
  - machine learning
  - AI agents
  - competitions
  - learning
  - Talos
excerpt: "A review on AI coding agents."
header:
  teaser: /assets/images/talos.jpg
---
<p align="center">
  <img
    src="{{ '/assets/images/talos.png' | relative_url }}"
    alt="A pencil sketch of Talos overlooking the sea"
    style="width: 100%; max-width: 480px; height: auto;"
  >
</p>

Before [Alan Turing asked whether machines could think](https://academic.oup.com/mind/article/LIX/236/433/986238), the ancient Greeks imagined Talos.

Forged from bronze by Hephaestus, the god of craft and metallurgy, Talos guarded the island of Crete. Three times each day, he circled its shores and hurled boulders at approaching ships.

In Apollonius of Rhodes's [*Argonautica*](https://www.theoi.com/Text/ApolloniusRhodius4.html), his metallic body contained a single vein near the ankle. It carried ichor, the life-giving fluid of the gods, and was protected only by a thin layer of skin. Damage that vulnerable point, and the bronze guardian would fall.

In her book *Gods and Robots*, classicist Adrienne Mayor describes Talos as a product of *biotechne*, life crafted through art and science. He could move independently, respond to his surroundings, and repeat an assigned task without tiring. A [*Smithsonian Magazine* article](https://www.smithsonianmag.com/history/was-talos-the-bronze-automaton-who-guarded-the-island-of-crete-in-greek-myth-an-early-example-of-artificial-intelligence-180986467/) explores how closely this ancient automaton resembles modern ideas about robots and artificial intelligence.

Talos performed his duty with tireless precision. His story also raises a familiar question: what happens to human skill when a machine handles too much of the struggle?

### The Comfort Trap

Growing up in Java, I often heard elders say, *“Mengko tuman.”*

The phrase roughly means, “You will get used to it.” It was usually offered as a warning that repeated comfort could become a habit.

As a child, the saying felt unnecessarily harsh. It seemed to suggest that enjoyment had to be rationed and that life should remain difficult simply for the sake of discipline.

Its meaning became clearer with time. Convenience is useful, but it can quietly change what we are willing to do for ourselves.

Machine learning competitions once offered very little convenience.

When I began joining them in 2020, nearly every attempt ended in defeat. Weekends disappeared into feature distributions, validation schemes, data leakage, and tensor-shape errors.

A week-long data science workshop, a handful of online courses, and several books had once made me feel ready to give a TED Talk or impress colleagues with jargon. Competition quickly revealed how little any of that meant without the ability to turn knowledge into something that actually worked.

Most ideas failed before producing anything useful.

That friction made the competitions rewarding.

A better leaderboard position was always welcome, but the deeper satisfaction came from understanding something that had previously been confusing. Each submission exposed another gap in knowledge. Each failure created a reason to return.

Then coding agents arrived.

### Getting My Own Talos

Using an AI coding agent for the first time felt like gaining access to Hephaestus's forge.

A command-line agent could inspect a dataset, organize a project, generate a baseline pipeline, configure cross-validation, and suggest experiments within minutes. Tasks that once consumed an evening could be completed before the first cup of coffee went cold.

The efficiency was remarkable.

Coding agents gradually became part of my daily work and later part of my competition workflow. Top 20 and Top 10 finishes became more common.

Yet the competitions began to feel strangely flat.

The problem was difficult to notice because the work still appeared productive. Code was being written. Experiments were running. Leaderboard scores were improving.

My own role, however, had slowly changed. More time was spent supervising terminal logs, approving suggestions, and asking the agent to try another variation. Less time was spent forming hypotheses and struggling directly with the problem.

Because every action still required a prompt or approval, it was easy to feel responsible for the entire result. That assumption was too generous.

The machine was producing more, while the person behind it grew increasingly convinced that prompting, reviewing, and approving the output meant remaining fully in control.

The ichor was flowing through the bronze body, but my hands had drifted away from the forge.

I had become *tuman*.

I was building slop.

### The Agent as Co-Pilot

The response was a small adjustment in how the tools were used.

Coding agents remained useful for boilerplate, repetitive transformations, debugging, and routine analysis. Strategy, domain assumptions, architecture, and major modeling decisions required more direct involvement.

Around that time, ThinkOnward released the [**No Second Guessing challenge**](https://thinkonward.com/app/c/challenges/no-second-guessing), a machine learning competition involving petrophysics and agentic AI.

Participants had to create a workflow capable of processing raw well-log files, producing a petrophysical suite, identifying potential pay intervals, and avoiding misleading honeypots hidden throughout the data.

The timing was fortunate. My team at Pertamina Geothermal Energy was already exploring agentic AI, so the challenge offered a practical way to study what these systems could contribute.

It also created an odd contradiction.

The competition encouraged participants to build an autonomous agent. Meanwhile, I was deliberately reducing the autonomy of my own coding agent.

That limitation helped restore the parts of the process that had been fading.

The goal remained modest. Petrophysical interpretation depends on context, uncertainty, and professional judgment. A machine-generated result can provide a useful preliminary view, helping specialists direct their attention and identify cases that require closer review.

The coding agent stayed in the role of a laboratory assistant. It helped implement ideas and manage repetitive work. The core architecture, validation approach, domain assumptions, and strategic modeling choices received more direct attention.

For two weeks, the familiar routine returned. Well logs were inspected. Assumptions were questioned. Promising shortcuts failed. Some experiments performed worse than the simple baselines they were meant to replace.

Progress became slower, but it felt meaningful again.

When the competition closed, the submission stood fifth on the public leaderboard.

That result was enough. Whatever happened on the private leaderboard, winning seems impossible anyway.

There was still plenty that could have been improved, and stronger solutions were clearly ahead on the leaderboard. Still, the competition had restored something more valuable than a ranking: curiosity about the problem itself.

Talos was powerful because he could patrol Crete without rest. Modern agents offer a similar promise of tireless execution, and that ability deserves to be used.

The harder question is deciding how much to hand over.

Some forms of friction merely waste time. Others build judgment, intuition, and understanding. Remove all of them, and even good results can begin to feel distant from the person producing them.

The machine can keep the ichor flowing.

We should still spend some time at the forge.

Then I slept soundly.

*Or so I thought. It was tagged as Promotions.*

<p align="center">
  <img
    src="{{ '/assets/images/announcementemail.jpg' | relative_url }}"
    alt="A winner announcement"
    width="480"
  >
</p>


