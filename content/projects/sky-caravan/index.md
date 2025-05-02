---
title: "Sky Caravan"
date: 2022-05-05
draft: false
description: "a description"
summary: "Text Based RPG [Unity]"
tags: ["game dev", "game", "portfolio"]
showReadingTime: false
showDate: false
showWordCount: false
showAuthor: true
showAuthorBadges: true
showPagination: false
weight: 2
---

> You are the captain - and the clouds are waiting!

{{< gallery >}}
  <img src="a1.png" class="grid-w33" />
  <img src="a2.png" class="grid-w33" /> 
  <img src="a3.png" class="grid-w33" />   
  <img src="a4.png" class="grid-w33" />
{{< /gallery >}}

## Technical Details

- Released on [Steam](https://store.steampowered.com/app/1792270/Sky_Caravan/) in 2022
- Released on the [Nintendo Switch](https://www.nintendo.com/us/store/products/sky-caravan-switch/) in 2023 
- Developed in Unity and written in the [Ink](https://github.com/inkle/ink) scripting language
- Extensive use of the [ImGui](https://github.com/ocornut/imgui) framework for testing and debugging

## Details & Responsibilities

**Lead Programmer, Business Developer**

Sky Caravan was my first commercial title alongside [Studio Bravarda](https://studiobravarda.com/). We were coming from a canceled project, and it was really important for us as a studio and as individual developers to release something on Steam. Having the full experience from first prototype to a complete game on the swtore was definitely worth it and taught me a few very important lessons that now accompany me in every project moving forward.

As the lead programmer, it was my responsibility to empower the game designers and writers to create/alter/test/play the game's content in the most efficient way possible. I still think this is one of the most important aspects of a programmer's work in a game development context. 

It was my first time using the [ImGui](https://github.com/ocornut/imgui) framework in a professional capacity, and using it completely changed the way I develop features. It's now clear to me how every single feature, if possible, must have a bloat-free testing GUI for the final user, be they programmers, designers, or artists. We used it to implement our own testing interface. The game's content was written using the [Ink](https://github.com/inkle/ink) scripting language and there wasn't a testing GUI with the necessary features inside the engine. After we implemented it, the writers/designers/testers could jump to any point in the story, see the choices in plain text with all the meta-info, fast forward to the next choice, and see the value of every single backend gameplay variable in realtime. ImGui proved to be extremely useful and I simply cannot start a project without it anymore.

{{< gallery >}}
  <img src="imgui_1.png" class="grid-w50" />
  <img src="imgui_2.png" class="grid-w50" /> 
{{< /gallery >}}

> Ink Manager that helped writers and designers Ink content. | 
> The Missions Control allowed jumps around in the story/missions.

During the final stretch I felt something that was new to me: the last 10% of work actually matters to the player. It's not easy for a developer to experience this fully, you have to swing for the fences and go for a full release for this moment to happen. One such moment was while I was waiting for a QA round to end. As I had a few hours with the project for myself, I implemented a few physics-simulated cables in the HUD using Verlet integration—something I've wanted to use for a while. In the grand scheme of things, it was just a flare, a tiny feature that didn't impact the gameplay and wasn't *really* necessary. The team loved it! They said that it increased immersion and the artists even did some particles to go along with it. Some players did notice it as well! This is the type of lesson you can only learn when you go above 90% of completion in a project and go for the final push to release it.

{{< video src="verlet_cables" autoplay="false" >}}

> Cables, cables everywhere!

I've also learned that the game you release might be very different from the game you've started developing. It's not a secret anymore—we've discussed it in podcasts and blog posts—but Sky Caravan started as a "narrative roguelite" and was later reworked to be a linear narrative. At the start we crafted numerous small story moments that were pieced together by a procedural system. It was very exciting to design a new system with a weighted randomized selection of story moments based on tags—*mystery, crew, action, location, etc*. We found out later rather than much-much-later that without a bespoken narrative thread gluing the story moments together, everything felt flat and uninspiring. After a very brief moment of discussion where everyone agreed, we switched to a linear experience. The funny thing is that the roguelite backend system is still there, but it always draws the same story moments in the same order—this was cheaper than rewriting the entire sytem. The game released as a branching linear narrative and it is much better for it. Embrace change when it's better for the project, we learned.

Post-launch is another period that you can only reach if you, well, launch the game. While the obvious focus was fixing bugs, adding additional accessibility features, and fixing more bugs, there's a chance that the team can work on something extra. For example, we worked on a full Twitch integration to enable streamers to play alongside the chat. This feature wasn't in the original scope of the game, of course, but launching the complete game and seeing it live on Twitch was the encouragement we needed to add this new way to play. Seeing people playing your game, after working on it for a while, is always a good feeling.

{{< video src="twitch_integration" autoplay="false" >}}

> Twitch integration that could be used by streamers.

Sky Caravan was a fantastic project! To this day we call it our post graduation course on game development. We learned a lot, shipped a complete game, launched it for the Switch and created a true Brazilian game that we are really proud of. Currently the game has 100% positive reviews on Steam, which brings me immense joy.

## Steam Page 

<iframe src="https://store.steampowered.com/widget/1792270/" frameborder="0" width="646" height="190"></iframe>