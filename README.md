# HEOR Scenario Lab

A transparent cost effectiveness model that shows which assumptions drive the result and what would make it flip.

**[Try the live demo](https://heor-scenario-lab.vercel.app)**. It works straight away with no setup, runs entirely in your browser, and stores nothing. All data is fictional or synthetic.

## Why I built it

In health economics discussions, a single ratio often ends up carrying the whole argument. I wanted the price or benefit needed to cross the threshold to be one glance away, and uncertainty to be shown openly.

## The problem

Cost effectiveness results often get reduced to one ratio that can be undefined, can mean the opposite thing in a different quadrant, or can hide which assumption is doing the work.

## What I built

A two strategy model using annual costs and quality of life, discounting and a willingness to pay threshold. It reports incremental cost, QALYs and net monetary benefit, shows the ratio only where it means something, and adds scenarios, a sensitivity chart with break even values and a 2,000 draw uncertainty analysis.

## Who it's for

HEOR, market access, pricing and medical affairs teams.

## What it does

- Enter annual costs, quality of life and treatment duration for a hypothetical new treatment and comparator
- Set the time horizon, discount rates and willingness to pay
- See incremental results, net monetary benefit and the cost effectiveness plane
- Run preset or custom scenarios and compare them
- See which assumptions matter most and the value at which the result flips
- Run a 2,000 draw uncertainty analysis with an acceptability curve

## Decisions that shaped it

1. **Net monetary benefit first:** the ratio appears only where it's meaningful.
2. **Annual and total kept apart:** inputs are annual, and totals are clearly labelled.
3. **Careful language:** results describe the model and stop short of any reimbursement view.

## Key takeaway

Net monetary benefit leads, every quadrant is handled properly, and results describe the model rather than a reimbursement decision.

## Built with

- HTML, CSS and JavaScript in a single file
- A seeded random number generator, so the uncertainty analysis is reproducible

## Run it locally

Open `index.html` in any browser. There's nothing to install.

## About this project

This is a working prototype I built to explore a real problem space. It uses illustrative, fictional data and isn't connected to any organisation's systems. You can find more of my work at [jane-natividad.github.io](https://jane-natividad.github.io).

Built by [Jane Natividad](https://github.com/jane-natividad).
