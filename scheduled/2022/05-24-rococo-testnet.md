# Connecting to the Rococo test network

Santiago from the Substrate builder's success team (Parity) and Alejandro, support engineer (Parity) will present what Rococo is today, it's future plans and how you can onboard your parachain to it in a few simple steps. 

* Slide deck [here](https://docs.google.com/presentation/d/1MhM83MY7if-3f02dYkHBqROypgkjhu60iXSBPhl_twA/edit?usp=sharing)
* Crowdcast replay [here](https://www.crowdcast.io/e/substrate-seminar-2/19)

## Plan

_(this is a proposed plan for the seminar, the actual plan will depend on the presenters)_

* Intro: what's Rococo, what it's used for, how it's managed, historical context
* Rococo's runtime: a closer look at onboarding pallets, how does it contrast from other test nets
* Parachain registration process: demo and explanation of how to add a chain to Rococo
* Next steps: questions, future steps, vision

## Q&A 

Here are some interesting questions to consider asking during this seminar (make PR to this page if you have ones that aren't yet here).
### High-level:
* What's the role of Rococo for the Polkadot community?
* How do we envision engaging with the community?
* What will be the decisions we need to make to move from a sudo based system of governance to a council based system?

### Technical:
* How would I perform a runtime upgrade on Rococo ?
* Do HRMP channels close once the 3 day period expires ? How does that work?
* How do the temporary slots work today? What improvements will be made and why?
* What are things teams should be testing on Rococo?
* How can teams find out what the validator logs are?
* How is Kusama both similar and different on a technical level? * What is configured differently?

## Some useful resources for context

* [Cumulus tutorial](https://docs.substrate.io/tutorials/v3/cumulus)
* [Rococo blog post by Parity](https://medium.com/polkadot-network/rococo-revamp-becoming-a-community-parachain-testbed-fe1de1e855d1)

## Links shared during seminar

* [Rococo parachains](https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Frococo-rpc.polkadot.io#/parachains)
* [Zombie net](https://github.com/paritytech/zombienet) for stress testing chains
* [Assigned slots pallet](https://github.com/paritytech/polkadot/blob/master/runtime/common/src/assigned_slots.rs)
* [Rococo community survey](https://docs.google.com/forms/d/1L3u7LC7M3XuVAIf6QE8DyAiAr5KN1jpSsGlcf-oXaxM)
* [Subport repository](https://github.com/paritytech/subport/) to post an issue / start a discussion on potential improvements for Rococo
