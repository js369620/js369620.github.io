---
layout: post
title:  "Trolley Problem VR"
date:   2025-03-17 14:10:32 -0400
categories: jekyll update
---

I was part of a team of four who set out to create a VR experience in a four-month time frame. I was our audio designer.

In the beginning, we had many ideas, but we decided on recreating the "trolley problem" dilemma for its simplicity and controversy - we thought, "Discussing it is one thing, but being IN it is another!" 

The experience was made using Unity OpenXR and was developed for the Meta Quest 3. With the Quest 3's hand-tracking abilities, the user was meant to stand before a real-world lever that was mapped with the virtual space on startup so that when they reached out to "grab" the virtual lever, they would also feel the real lever to heighten their immersion.

As the audio designer, my goal was to figure out how to distress the user with sounds. I achieved this in two parts: collecting sounds to use and implementing a spatial audio system. 

I collected sounds online and held voice acting sessions. A handful of my friends volunteered to take on the role of being the victims in the dilemma. I gave them a few lines to read and guided them to perform as if their lives depended on it – the results were excellent. By giving them lines such as, “I have a husband!” or “I’m on the verge of a great medical discovery!” this conveys information to the user that their decision has consequences beyond how many victims perish. And of course, the screams are meant to be a strong punch to the user’s emotional state, as the screams are intense and short-lived from being cut off by the sound of the victims being crushed. 

When it came to bringing those sounds into the project, I programmed an audio system that would hold all the objects that played the voice clips and randomized which ones would play, as well as keep track of which ones were already played to prevent repeats. Then, when the objects were placed on their respective side of the trolley tracks, they were set to have a spatial effect to make their voice clips emanate from their location. 

In the end, the audio experience involves hearing the trolley blowing its horn from afar as the victims attempt to plead with the user. When the trolley arrives, the victims on the chosen side of the tracks scream until they are run over. 

You can listen to some of the voice clips here. Be advised that some are screams, so you may want to adjust your volume accordingly.

[I have a husband!](/assets/Adan_Husband.wav)

[Please, God](/assets/Ava_Mercy.wav)

[Don't do it!](/assets/Makenna_Plead.wav)

[You have to let me out](/assets/Stefan_Discovery.wav)

[Scream 1](/assets/Leanne_Scream.wav)

[Scream 2](/assets/Makenna_Scream.wav)

[Scream 3](/assets/Stefan_Scream1.wav)

You can find the repo here: <a href="https://github.com/gl-rukwa/pr0j3ct-wyrm"> Trolley Problem VR Repository </a>
