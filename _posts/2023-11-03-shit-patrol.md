---
layout: post
title: Shit Patrol, an automated playlist
---

Years ago, I was involved in college radio. Every week, we would get hundreds of new albums from bands & promoters that wanted us to put their music on air.

We listened to every single CD we received. At least a few tracks, at least 30 seconds per. We called this Shit Patrol, and it was as mind expanding as it was brain melting. Often 100 genres in as many minutes.

Today, the struggle to discover new music is real. Spotify algorithms help, but by design they will not push you out of your comfort zone. Proactively seeking out new music can become a grind.

You can't do Shit Patrol for every new album that comes out. But, it turns out you can do it for every band that plays in New York City on any given week!

<iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/0cchFuZ8BigXzce2s9rHQH?utm_source=generator" width="100%" height="152" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>


Then, when you hear something you love, you can have the immediate gratification of getting to see that band live! (or the FOMO of not being able to)

* Updated daily, via an AWS Lambda on a cron
* Concert listings come from ohmyrockness.com (via an internal API and a clever webscrape)
* Built with js, postgres. 
* <a href="https://github.com/JordanSucher/Shows-in-NYC-Autoplaylist/tree/main">Github repo</a>

