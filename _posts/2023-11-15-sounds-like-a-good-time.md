---
layout: post
title: Sounds like a good time, a bike ride visual synthesizer
---

Often when I am moved by art, it is because the artist has taken the seemingly mundane and, by framing it, revealed its beauty.

Perhaps you had become desensitized to the way the sunset looks through the subway window as it grinds over the manhattan bridge, or had never carefully examined the shape and color of fish scales. And then, wham, some painting puts you in closer contact with reality.

Beauty is mostly a matter of attention. Focus on anything with an open mind and you are bound to find nuance.

This seems to be the art of life! Figuring out how to direct your attention. Learning, and then re-learning, how to focus on things that are vital but not loud. 

I was thinking about this as it relates to cycling. 

I have a complicated relationship with riding my bike. When I have been at my lowest points, burnt out or depressed, cycling was the only thing that brought me joy and made me feel truly free. 

But, as I began to take the sport more seriously, the joy started to go out of it. The feeling of wind in my hair, of being in motion, gave way to a focus on heart rate zones and target mph.

Then, last year, I had a major crash. I fell off the bike at ~25 mph, and skidding across the pavement felt like being swallowed by a concrete wave. My kneecap was shattered, and I spent about 3 months in recovery and physical rehab relearning how to walk. 

When I finally got back on the bike, I was, obviously, not the same. Not only had I lost all my strength, but I now had intermittent swelling and bone pain if I pushed too hard. The loudest voice in my head wanted me to get back to where I had been, as quickly as possible. Technology made this worse. Every time I did laps in the park, Strava would remind me that I was a full minute slower than my fastest time, that todays average speed had only been 12mph.

Slowly, I narrowed the gulf, each week shaving a few seconds off. As I got stronger, I realized that I no longer felt safe going faster than ~15mph. On every downhill my body would snap tense and I'd flash back to the moments before my fall. 

I spent a lot of time re-wiring my brain here, teaching myself that I wasn't in danger, that I wasn't a failure for going a little slower. Trying to get back to a place where I could just enjoy riding my bike again. 

As part of this reclaimation effort, I felt compelled to make something beautiful out of the experience.

I immediately thought of <a href="https://www.youtube.com/watch?v=sIe9p7tslpg">Best of Luck with the Wall</a>, a stunning 2020 short film that uses satellite imagery to make tangible the vastness of the US-Mexico border (and the inherent absurdity of policing it). Perhaps, with the lat-long data from the ride, I could create a similar experience?

![Best of luck with the wall](/assets/bestofluck.gif)

Simply visualizing a bike ride was briefly interesting, but quickly became repetitive. How could I go deeper, uncover another layer of beauty here? I decided to generate an accompanying soundtrack based on the bike ride data, interpreting visual elements from each frame as a musical score.

The result is a mesmerizing, fully playable instrument. You as the user can decide which pixels get mapped to music, which instruments play, tempo, key, volume.

![Sounds like a good time](/assets/bike.gif)


I have been deeply moved by watching and listening to this. It has reminded me on a very visceral level that the experiences we have matter, and that there is beauty in everything that we do, should we take the time to look. 



* Use the synth <a href="https://www.soundslikeagoodti.me/visualize?circles=2&mode=dorian&mode2=dorian&key=E2&key2=E2&instrument=clarinet&instrument2=cello&speed=422.53521126760563&volume2=8">here</a>
* Built with js, ffmpeg, sharp, toneJS, docker, aws ECS, mapbox
* <a href="https://github.com/JordanSucher/videos-from-strava">Github repo</a>

