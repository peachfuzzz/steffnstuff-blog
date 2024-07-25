---
title: "Shallow Dip: Comparing League champion difficulty"
author: Stephen Wu
pubDatetime: 2023-10-26T16:30:12.000+00:00
slug: comparing-league-champion-difficulty
featured: false
draft: false
tags:
  - league of legends
  - design
  - shallow dip
description: "A two-axes perspective on execution difficulty in League of Legends"
---

## Table of Contents

## Comparing League champion difficulty

Champion difficulty (and through it, champion design) is an often debated topic, with more than its fair share of controversy. Definitions of “difficulty” vary, but often you see two main axes upon which difficulty is measured:

1. Mechanical execution: the difficulty of pressing buttons in the optimal way in order to create an optimal output.
2. Diversity of decision-making: the amount of variables a player needs to consider when making decisions in-game.

When comparing champions, tier lists are often employed as a visual tool to understand relative qualities. They’re constructed by evaluating items by a specific criteria and ranking them against each other, grouping by thresholds of quality in a linear fashion. As such, they’re good for organizing some things, like comparing fast food or the speed of various birds, but they’re bad for other things, like ranking the difficulty of League of Legends champions.

This isn’t really a hit against people who make tier lists, but more so an observation about game design. You’ll see a variety of viewpoints regarding champion difficulty without necessarily outlining what definition(s) are used, which results in rather drastic differences in difficulty ratings. For example, here’s VeigarV2’s opinion on the matter.

### VeigarV2 tier list

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">My tierlist on difficult champions in league of legends video game. <a href="https://t.co/WszR5VypUB">pic.twitter.com/WszR5VypUB</a></p>&mdash; Veigarv2 (@Veigar_v2) <a href="https://twitter.com/Veigar_v2/status/1499445007694155797?ref_src=twsrc%5Etfw">March 3, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


VeigarV2 mixes a variety of decision-making and mechanical skill into his tier list, resulting in some more controversial picks (Anivia, Fiddlesticks, Aurelion Sol pre-rework). These aren’t your traditionally super flashy champions, but his arguments hold some ground. There is a ton of nuance in how Anivia can use her wall or how Shaco can manipulate his clone.

Although only regarding top lane, Bwipo makes an interesting addition: he adds a tier which includes champions with unique decision-making required, noting that while they may not be more mechanically difficult than some of the champions they are placed above, they too cannot be piloted by a new player in ranked with consistent success without some prior understanding of the champion’s nuances.

### Bwipo tier list

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">try me <a href="https://t.co/95PnBR8uRF">pic.twitter.com/95PnBR8uRF</a></p>&mdash; Bwipo (@Bwipo) <a href="https://twitter.com/Bwipo/status/1655327795965489152?ref_src=twsrc%5Etfw">May 7, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


Personally, I think we should push one step further and abandon tier lists altogether. Mixing the two axes of mechanical skill and decision making reduces the clarity of each argument, and I think a graph with 2 axes, plotting the relative mechanical and decision-making skill required gives us a more nuanced picture of where champions fall in terms of difficulty.

### Implementation chart

![implementation chart](@assets/images/implementation_chart.png)

> [taken from Rishi's video on Super Smash Bros Melee](https://www.youtube.com/watch?v=Mv6Xx5sCp3M)

Here, characters are placed on their relative difficulty of execution, and their relative diversity of decisions. While League is a very complicated game, with each champion having their own nuances and interactions, we can still evaluate champions relative to each other. Just think of the origin of this graph to the far, far upper right of many playable characters in single-player games.

One way to evaluate champions in their difficulty of execution is whether or not a script drastically helps. Basically, how much is a champion’s effectiveness tied to increasing the skillshots hit and abilities dodged?

Similarly, evaluating difficulty of decision-making can be akin to giving a new player a set of instructions before the game. How broad can the variables you consider be before the decisions made with those variables drop in quality?

## Low execution, easy decisions: Garen

For example, a champion like Garen falls (in my opinion) near the bottom left of the graph. Garen has a very mechanically straightforward kit: he has no skillshots, two point and click abilities, an unmissable aura E, with his only strong expression of skill being his W timing. Being a tanky melee champion with relatively good escape, Garen doesn’t get punished as much for making mistakes, mechanical or positional. Garen’s gameplan is pretty simple as well: he’s a strong duelist who splitpushes very well, punishing the enemy team for their lack of coordination. His combat outputs are also one-dimensional: he basically uses the same combo of Q → E → R on everyone, without much variation in how he approaches fights due to his lack of terrain-scaling mobility. His combo works roughly equally well on everybody, given the armor shred and percent missing health true damage on R, making his target selection relatively uncomplicated.

### Script/flowchart lens:

- Garen is mechanically identical with or without scripts: you just can’t improve much on his mechanical execution. Even dodging abilities doesn’t do _that_ much; he simply is much more tolerant of punishment.
- If a new player picked up Garen with a flowchart of things to consider, their output would not be terribly far off from experienced Garen players. There’s not _that_ much to think about: if you can splitpush, you should probably splitpush. Avoid teamfights unless necessary, fight anyone who can’t kite you and isn’t named Camille.

## High execution, hard decisions: Gangplank

In contrast, I’d tend to agree with Bwipo on Gangplank being firmly in the top right of the graph. In terms of mechanics, Gangplank is extremely intensive. His barrels alone serves as one of the most difficult abilities in the game, being conditional sources of damage which can be contested by his opponents. Together with his Q, his barrel combos are more mechanically intensive than entire champions, requiring precise positioning and timing to maximize effectiveness. He is very punishable if mispositioned, as a (usually) squishy melee champion, so the level of mechanical precision is increased further. Gangplank’s decision-making goes hand-in-hand with his kit. Not only does Gankplank have many points of information to consider when making decisions, (barrel tick rate, range, sheen cooldown, enemy CC), he has a myriad of outputs to express his ideas. One game, Gangplank can be an assassin, fishing for barrels on the enemy backline, while another, he can act as a regular mid-range control “mage,” creating space with barrels and Cannon Barrage. He lanes well. He scales well. He can splitpush effectively, with strong waveclear, good dueling, and high tower damage, but his strong ranged AoE outputs also let him thrive in teamfights. His theoretical outputs are just as varied as his inputs, and even in the most boring front-to-back team fight, vision heavy, scale-for-late pro games, Gangplank is one of the most difficult champions in the game to pilot.

### Script/flowchart lens:

- Scripts _could_ help you dodge abilities easier and space with your Q better, but your barrels are a much more complicated minigame than most scripts can feasibly handle in such a short timeframe. Perhaps you could script a one-part barrel combo, but that’s only one output of a very complex ability.
- Good luck making a flowchart comprehensive enough to cover the majority of situations, yet still simple enough to be useful.

## Low execution, hard decisions: Singed

With the difficulty graph, non-traditional champions get their own little place in the bottom right quadrant. Here, we might find stuff like Singed and Warwick top: champions which have relatively low mechanical ceilings, but very unique decision-making in terms of fight selection, positioning, and wave control.

### Script/flowchart lens:

- Again, scripting is less than stellar here. Most of these champs have low numbers of skillshots, or just janky abilities in general. You’re not getting much out of perfect dodges and ability hits.
- It’s relatively difficult to take the decision-required for champions like Rengar and Warwick and distill them down into a list of choies. These champions are heavily reliant on instinct and experience to maximize their effectiveness: no flowchart is specific enough to tell you how or when you win which encounters.

## High execution, easy decisions: Vayne

And finally, we see champions which _are_ commonly picked for scripting distinguished in the upper left. This is where stuff like Kog’Maw, Zeri, Vayne, and Xerath lie: champions with straightforward gameplans who sit there and out-muscle the competition. There is a caveat, however. Aside for a few extreme examples such as (arguably) Kog’Maw, mechanical complexity tends to merge with decision-making complexity. The two are always intertwined; a large portion of mechanical outputs are a result of considering combat variables. If a champion’s kit has inherent mechanical complexity, they tend to also have to make difficult decisions for optimal play.

### Script/flowchart lens:

- As mentioned, this is basically the perfect choice for a scripter. The effectiveness of these champions rise drastically with skillshot precision and movement/positioning.
- While by no means simple to pilot, a lot of these champions have rather straightforward strategic outputs. They want to get in a fight and win the fight. Rarely are they best-in-class at other options, due to their tendency for low utility.

## Conclusion

I will not pretend that I know where each and every champion falls upon a chart like this, especially given the justification required to grade even universally easy champions. At the same time, I don’t think it’s controversial to say League has a diverse set of champions with unique outputs, each requiring mastery over a unique skillset. However, I also don’t think it’s controversial to say that champions are not made to be equally difficult, nor were they ever intended to be. That’s what makes League so cool, after all. So many ways to express your skill, and you might still end up a Kayn one-trick.