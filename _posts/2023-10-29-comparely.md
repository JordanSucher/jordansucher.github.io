---
layout: post
title: Comparely, a competitive intelligence proof-of-concept
---


In b2b SaaS, keeping tabs on the competition is an existential need. Sure, there is discourse over how much to base decisions around what competitors are doing - but if your biggest competitor rolls out a new feature, you want to understand why.

This cuts across teams. Sales needs to speak about competitors on calls. Marketing needs to design relative positioning. Product needs to advocate for (and against!) roadmap items based on where others in the market are now and where they're going.

<!-- In practice, this research gets distributed across a company. PMs might do a feature analysis for a specific product they are working on. Sales folks might note what they learn about competitors during sales calls in Salesforce. The CEO might hear intel on a new competitor gaining traction from an investor.  -->

You can glean a lot about a company from public sources. Take a company's site, tweets linkedin posts, articles about them on techcrunch, interviews with the founders, jobs the company is hiring for, and you can get a pretty solid picture of the company's priorities, strengths, and weaknesses.

<!-- This research can't be fully automated, but it can certainly be more streamlined than it is today! Baseline here is setting a google alert for when competitors show up in the news or going websites one at a time and taking notes. -->

Comparely is a proof of concept exploring how automation & AI might be used to give b2b teams better telemetry on what is happening in the market. 

The idea: pull data on a recurring basis, synthesize it with LLMs, and automatically notify stakeholders of anything important. This poc implements a basic feature comparison, but the potential to provide deeper insights is there.

![Homepage](/assets/comparely-1.png)
![Generate a comparison](/assets/comparely-2.png)
![Feature comparison](/assets/comparely-3.png)

* Built with js, python, perplexity, gpt4
* Data streamed to front-end via server-side-events
* Automated emails with emailjet
* <a href="https://github.com/JordanSucher/Comparely">Github repo</a>


