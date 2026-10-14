# Foliage Labs

What we're attempting would normally take a large studio years. We simulate real places and how their plants grow
over decades. Our renderer has to match photographs of those places, not just look plausible. And we're building a
library of real species from real specimens: leaves cut from herbarium sheets, bark from field photos, measured
traits from botanical data.

We're a small team, and we can take this on because AI runs through every step of how we work. That means more than
AI writing code. Agents do much of the engineering, research and data processing. Some jobs need the same judgement
thousands of times, like choosing reference photos or checking each leaf cut from a herbarium sheet. For those we
train our own models on our own decisions, and a model takes over only once it does the job as well as we do. Every
failure becomes a rule or a check, so we can move fast without cutting corners.

## What we're aiming for

We want to build the most realistic real-time simulation of the natural world that runs in any browser: real places,
at real dates and times, growing as they actually would. We plan to open-source the engine so others can build on
it. We want real places and real plants within reach of anyone doing research, teaching or design. And we want the
engine to carry better real-time software apps than the web has seen so far, starting with our own.

## How we work

Quality comes before speed. We would rather ship one thing that holds up than ten that almost do. Reality is the
judge: when a render and a photograph disagree, the photograph wins, and we find out which part of the simulation is
wrong instead of tuning until it looks right. We use AI fully and openly, and we say so. Every mistake teaches us
something, and we turn it into a better way of working rather than a one-off fix. And we give credit where it's due.
Our work stands on photographers, botanists, herbaria and open-data projects. We check every licence, credit the
people behind each source, and ask whenever a licence doesn't cover what we need.

## What we're building

- **Foliage**: the engine. A WebGPU simulator and renderer for real-world nature, to be open-sourced.
- **Plant Library**: a research and education app for real species, built on pieces of the renderer. It works with
  Foliage or on its own.
- **A landscape-architecture app**, next: years of growth at a real site, before anything is planted.

A devlog about how we build it is on the way.
