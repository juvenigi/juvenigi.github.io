---
layout: post
title: Dota, Autoexec, and game design - What I've learned
key: 20180120
tags: [ dota, english, valve, gamedev ] 
---

[Source engine] is the product of **Valve Corporation** and is being currently used in its few flagship titles such as **Dota 2, Counter-Strike: Global Offensive,** and **Team Fortress 2.** One of its prominent features is to use a file called `autoexec.cfg` which allows the player to modify the game's user configuration to a possibly absurd degree. It could even be argued that this is in fact one of the distinguishing and a sought-after feature that adds a unique level of customization.  
Yet sadly, all of that is being thrown away and slowly dismantled, as the company is trying to create an equal competitive playing field, whatever that means. This is not only vague, but perhaps also quite damaging to one specific community in question, the one of Dota's.

## Multiplayer games are skill-based, although skill is arbitrary
Scripting is always a grey area in video games. I must fully disclose that I am biased in favour of scripting due to my own perception of player's skill. I disbelieve that one's finesse should be completely determined by being first at pressing a button (reaction time) or superb utilization of imperfect controls. Rather, their speed of mental calculation is what matters to me personally. Consequently, any script that makes doing an action easier doesn't bother me because he still has to think in order to make a decision.

## Small history of Dota controls
The predecessor of Dota 2, **Defense of the Ancients** is a **Warcraft** mod. Thus, it has many peculiarities in game mechanics due to the engine's innate limitations. What it meant was that the controls were—*how to put it*—sub-par. This could be remedied by using **WarKeys**, which practically remapped all hero's ability from semi-random location to a much more reasonable top row, qwerty. This wasn't seen as something bad because the defaults were really troublesome to use and Blizzard Entertainment, creators of Warcraft, *didn't seem to care*.

Out comes the new rendition of the game on a modern engine. Although the controls are miles better compared to the previous version, some people wanted to have more control over the keys than what the default client had to offer. Such example is [loopuleasa's customizable Dota 2 layout engine] which made multiple modifier keys possible. Additionally, it uncovered some of the obscure features which at that time was only known by autoexec enthusiasts: an ability to look at specific position on the map by pressing a key.  
Community was fractured into different camps: those who used these modifications, those who were indifferent, and those who were appalled by the notion of editing a file outside a game. Accusations of scripting were flying in the air saying that specific heroes were rendered too simple to use because one could set up the hotkeys in a way that could accomplish multiple tasks at once, *clearly an unfair advantage?*

## An exploit or a game mechanic?
For me this has to do with the fact that a new audience was introduced to the game, the one that has not seen the horrors of the past. Furthermore, a new way of thinking is formed where the way how player input is done is dictated by the developer. This is harmful, because many cool features are often unexpected byproducts of design which creators often want to patch. This goes for **rocket-jumping and bunny-hopping**, *bug-as-features* first found in the Quake engine, the ancestor of Source. Even though the community loved these features, [the devs were on the verge of removing them].

See you next time when I'll talk about another Valve's game called Team Fortress 2 and how scripting is used there.

[Source engine]: https://en.wikipedia.org/wiki/Source_(game_engine)
[loopuleasa's customizable Dota 2 layout engine]: https://github.com/loopuleasa/Dota2-TheCore-Config-Engine
[the devs were on the verge of removing them]: https://www.rockpapershotgun.com/2014/09/02/quake-3-john-carmack-strafejumping/
