---
title: "Shallow Dip: Statistically Significant"
author: Peachfuzzz
pubDatetime: 2025-02-13T14:37:22.873306
slug: shallow-dip-statistically-significant
featured: true
draft: false
tags:
  - TFT
  - design
  - shallow dip
description: "A discussion on the removal of augment statistics from TFT"
---

# Table of Contents

# Introduction: Augment Stats Removal Redux

On November 13th, Riot Mortdog announced on his Twitter and posted to r/CompetitiveTFT about the removal of augments from the post-match summary, effectively eliminating augments from statistics aggregator sites. You can find his tweet below.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Hey folks. I’d like to talk to you today about removing Augments from the end of game and match history, and, therefore, from stats sites.<br><br>The last time we tried to remove the Augment stats in Runeterra Reforged, we saw some immediate positives toward TFT game health—lobbies had… <a href="https://t.co/961qEXbVtq">pic.twitter.com/961qEXbVtq</a></p>&mdash; Riot Mort (@Mortdog) <a href="https://twitter.com/Mortdog/status/1856785428852216007?ref_src=twsrc%5Etfw">November 13, 2024</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

In response, sentiments have centered on a few ideas:

- Augment stats increase accessibility for learning the game
- Augment stats limit the creativity around the game

The broader topic about the usage of statistics in TFT (and games beyond) is a topic that is beyond the scope of this essay, but the specific removal of _augment_ stats is an interesting topic for idiosyncratic reasons. Augment stats have been a cornerstone of autochessmetrics since their introduction in set 6. There are a number of players, pros included, who make their decisions about augments purely on their average placement (AVP), filtering for stage and position. This has been generally accepted as a viable—and even relatively strong—strategy for decision-making.

However, augment data had a brief leave of absence during the middle of set 9. This was cause for some controversy through its implementation, which we’ll not go into here. The basic incentive of the removal of augment data has remained the same regardless. Riot wants the game to be more fun, and they believe that removing augment stats from the game will create an environment more conducive to the sort of fun they envision from TFT: quick decision making, high variance, and clever innovation. In this essay, I argue that the removal of augment stats is a small and slightly positive change for the overall game health of TFT, in particular surrounding the purpose of statistics and augments in TFT, at the cost of information and transparency.

# Background knowledge and shared assumptions

## Assumptions

Before I begin forcing my opinions upon you, I’ll first outline a few key assumptions that I am making about TFT and Riot surrounding the upcoming changes.

- **Riot Games wants the game to be fun.**
  Look, this isn’t very complicated. Players want a fun game because they play games for fun. Riot wants the game to be fun because a game that people want to play makes money. **Players and devs share the same goals here!** Game balance, game health, and game fun-ness have (what hopefully most of us assume) a positive correlation, so Riot is incentivized to make a game as fun as possible. I am not saying the game will be perfectly balanced (because it’ll never be), nor am I saying that balance is desirable from the perspective of the dev team (but it tends to be), but I am saying that Riot is not intentionally working against the player base when it comes to the balance of the game. If we’re going to share any assumptions, this is the most important one to keep in mind.
- **Riot Games will have internal data for augments.**
  Various devs have shown in the past that Riot’s internal tools are intentionally kept from the public. This is natural and I expect augments will be no different. If anyone deserves to be informed, it’s the developers, who need as much evidence as possible to make decisions.
- **90% of Augments will be within the interval of 4.0-5.0 AVP**
  This is maybe an unhelpfully generous confidence interval, but historically we’ve seen most augments fall within this range. For example, in the last patch of Set 12 for Diamond+, 2/259 of augments fall outside this range (I know that this is the last patch of a four month set, but cut me some slack). If only supercomputers with infinite foresight played the game, augments should share an AVP of 4.5, but this is completely unrealistic. Generally, it is safe to assume that the disparity between augments _should_ mostly come from their utilization in game, rather than their raw power level. If you pick an econ augment at 4-2 when you desperately need items for a secondary carry, that’s just on you.
- **Bugs will happen, and they will hopefully be fixed.**
  Bugs are an unavoidable part of games. Unfortunately, because TFT has a myriad of interactions, they can be both difficult to detect while being rather impactful. Beyond praying at 2 a.m. for the head honchos at Riot to allocate more development money and time to TFT’s Gameplay Analysis and Quality Assurance teams, there’s not much players can do beyond continuing to report bugs when caught. Bugs will forever be here to stay, and we must acknowledge with certainty that they will show up in varying degrees of quantity and magnitude.

If any of these assumptions don’t match up, please understand that I’m trying to give Riot the benefit of the doubt while maintaining some degree of skepticism. I’m a Riot glazer for fun (though it’d be nice to get paid for it), but ultimately I think that a certain level of trust should be levied toward the developers of the game that we are putting our time and effort into. Sometimes Riot makes some heavy mistakes that are worthy of criticism, but on balance (hehe), they’re doing alright. The video game Teamfight Tactics is pretty fun.

## What do augments do for the game?

Augments as a mechanic provide a few things. They introduce high game-to-game variance, force a committed decision at significant points in the game to create an interesting narrative, and incentivize another layer of theorycrafting beyond team compositions and itemization.

A common statement about augment stats warns that this is a slippery slope in removing stats from TFT to make information unobtainable. “First augments, then items, then champions!” However, it is important not to get the purpose of augments mixed up with the purpose of items. Items exist to empower characters and differentiate them from the rest of the team. They create **heterogeneity in output** besides inherent unit numbers—with items, you can choose which units you want to empower above the rest and what outputs you want to increase. Augments exist in a different space—they create interesting variance in between games, giving players a set of choices which heavily determine how the rest of the game should or shouldn’t play out. The item system is designed to test your ability to recognize which parts of your team are most important. The augment system is designed to test your ability to adapt on the fly. These are two different skillsets, and as such, should be approached differently when stats are discussed.

This difference in design is reflected in the level of variance for items vs. augments. For a vague numbers check, the average player can expect to see at least fifty shops per game, and at least twelve components roughly normalized to include one of each. You’ll be able to find champions and items in similar frequencies game-to-game; the law of large numbers all but guarantees this outcome. In direct opposition, augments have far higher variance: there are over 200 per set, and 50-150 per tier (silver has least, gold has most). Even if two games have identical augment tier distribution and you roll all six augments on 2-1, you still have **less than a 50% chance of seeing at least one augment shared between games** (this is an extremely rough calculation, the actual rules are messier). The difference in variance between items, which you can rely on for consistency multiple times in a single game, and augments, which are rare to see repeated over 5 games, shows how these two systems are built with different intentions in mind.

Really, I just did a bunch of vague gesturing all to say that augments are not intended to be optimized in the same way that items and compositions are. Augments are not as replicable, not as universal, but still very much intentional. They are fun and interesting precisely because they create variance. This is foundational to why they became an evergreen addition to TFT. Riot’s approach toward augments is unlikely to change, given how important they are to creating unique game states. It is not a bad thing to want to optimize augments, but it is also not optimizable in quite the same way as other aspects of the game.

## What do stats do for the game?

The purpose of statistics in TFT is to provide evidence for gameplay hypotheses. Stats are, by nature, a collection of correlations rather than a manual of causations. If we theoretically knew that Dominator Crest had an AVP of 4.8, what does that say about the strength of the augment? In my opinion, it’s an indicator that something is vaguely weak with the Dominator lines, but it tells us little about exactly what. Here’s a facetious list of potential issues we could think of that influence the AVP:

- Dominators, the trait in entirety, is weak.
- 6 Dominators, the comp you’re incentivized to play with the Dominator emblem, is weak.
- Dominator Crest doesn’t give enough gold for the direction it forces you in.
- The individual units that you play in Dominator are weak.
- Dominator Crest is extremely terrible on 2-1, but decent on 3-2 and quite strong on 4-2.
- The Dominator line is unoptimized; Dominator Zeri is actually very strong, but very few people know about this line and are putting Dominator emblem on bad units.
- Bad players, which outnumber the good players, are bad at playing around Dominator emblem, deflating the AVP.
- There is a bug with Dominator emblem that artificially weakens the holder.
- The sample size is too small and the people who happened to play Dominator Crest in the sample population all had poor sleep over the previous couple of days.

There are, of course, ways of using statistics to confirm the veracity of some of these statements. You can compare the augment across stages and against other augments, look at the performance of the Dominator units, filter users and comps with/without Dominator Crest. However, the reality of the situation is that a truly accurate evaluation of an augment is often unknowable without experience and insight into the statistical tools for TFT, and the average stat user is simply not going to perform the necessary research. At a surface level, it is difficult to surmise the objective performance of an augment by simply looking at its stats.

Another issue with statistics is how they are (generally) ignorant of current game state. An augment with an AVP of 4.2 at 2-1 does not dictate exactly how the rest of the game plays out, turn by turn. Rather, in the hundreds of thousands of times this augment has been selected in this spot, the player who selects the augment tends to place around 4.2. This end statistic is a synthesis of all recorded scenarios: the games where someone who was already first in the lobby hit their BIS augment, the games where someone randomly pivoted into a contested line and speedran 8th, the person who sacked too much HP on stages 2 and 3 and petered out to a 6th, and the person who, against all odds, played the best of their horrible hand and squeezed out a 4th. In aggregate, the data talks about all of these people, but for your specific game, you can only be one of these people. When you’re contemplating your choice of augment on stage 3-2, facing the decision of econ vs. combat vs. item vs. emblem, stats are only one (albeit strong) point of reference for your choice.

There is, however, one caveat. **Stats with filtering can account for many of these shortcomings**, and this creates a problem. Once you start filtering stats, particularly augments, for stage, composition, and unit, you begin to approach a true evaluation of an augment’s power level. This does pose a problem for the game, which we’ll explore next.

# Why is the removal of augment stats notable?

We’ve talked about the purpose of augments, and the purpose of stats. Together, we can derive a key realization about augment stats: **in a game of high complexity, augment stats provide what is closest to a definitive answer in a high variance situation.** The problem isn’t necessarily that augment stats provide information to confirm theories, the problem is that augment stats are an unfun be-all end-all answer to a situation which isn’t designed for replicability.

Let’s return to the purpose of augments for a moment. We discussed that augments primarily exist as a major decision point that introduces variance with some player optionality. However, unlike other parts of TFT for which we have data, augments actually control for many variables by themselves. They all happen to the entire lobby at the exact same time, appear among other augments with similar power levels, and have a rather large sample size, owing to the sheer number of games played. As a result, the information they give is streamlined, and more importantly, actionable.

Take, for example, unit stats. Let’s take a hypothetical unit in a hypothetical set, Bard, that averages a 4.1. How does this help your decision making? Well, Bard could have this AVP for a multitude of reasons.

- Bard does a lot of damage.
- Bard provides a large amount of utility.
- Bard is a key part of a very strong composition as the main carry.
- Bard is a synergy bot with great tags.
- Bard is the best Morello holder in the game, and Morello is incredibly strong.
- Bard 3 is broken and game winning, but Bard 1 and 2 are pretty mediocre.
- Bard is a 5 cost, which tend to average an AVP of 3.9, and is actually a bit weak (for the inverse of one of the reasons above, perhaps).

With no other information, you are allowed to conclude that Bard is somehow stronger than the “average unit” (whatever you decide that to mean), and your internal TFT heuristics should account for this by playing around Bard in more situations than you had previously. Indirectly, you’re allowed to hold a hypothesis about Bard’s power level for one of the reasons above, or none of them at all, but confirming your hypothesis requires external information you cannot derive from purely the Bard AVP alone.

The other key issue here is that this data only looks at end boards, so you have no information for live comparisons. If you’re in a game and you see a Bard in shop and you know his AVP, it doesn’t significantly change your decision making process. You can’t compare the AVP of buying and playing the Bard this round versus literally anything else. Is Bard a good early game item holder? Should I play Bard over a different unit? Do I hold Bards on my bench? Unit AVP has never answered these questions, and never will. **Unit stats are incomplete**—you must still rely upon your understanding of the game, perhaps combined with other statistics, to make a conclusion on what you can do with the knowledge of a unit’s AVP.

Conversely, let’s put ourselves in a similar situation common to when augment stats were around. On 3-2, you’re playing Renata reroll when you get offered Visionary Crest, Starry Night, and Manaflow II. You could use your brain here—depending on your items and current board, you could make your own decision. You could also switch tabs to [tactics.tools](http://tactics.tools) (not sponsored), pop open their explorer, and filter for the highest AVP 3-2 augments for all boards containing Renata 3 and Singed 3. Using an explorer tool with filters cuts out much of the noise of data. Unlike the stats of an individual unit, which has effectively zero filtering innately, we get to observe a decision made at a single point in time. Given we establish our desired end board, and given we want to make the highest AVP decision, we are able to compare the exact choices of augments to each other.

> sidenote: i actually have no idea what the correct choice would be there, but i gave it my best guess. if someone wants to correct me, please do

**This degree of statistical precision does not exist elsewhere in the game!** Unit AVPs ignore when you get the units and when you sell them, item AVPs ignore when you build them and who the users are, and “comp” AVPs ignore so many things it gets annoying to list. Filtered augment AVPs by stage stand alone in their reliability. They alone tell you how to make a specific decision at a specific time, thrice a game. I will not make a value call on whether or not stats were a _better_ way of playing the game than relying on your own knowledge, but they were almost certainly a _viable_, arguably strong method of playing the game. Don’t take it from me—up until last set, many Challengers and even pro players relied on stats to decide their augment choice on 2-1, and still more at least consulted them on 3-2 and 4-2. The biggest issue isn’t so much that augment stats existed, but rather, coupled with filtering mechanisms, they were uniquely actionable, accessible, and applicable.

Now, this would be well and good if people overall liked consulting a statistical tool to play their video games. However, I think we can admit that this is not a particularly fun test of skill or knowledge. All competitive games make some promise of skill to the player. **Teamfight Tactics, for one, promises a game where the skills of on-the-fly decision making and knowledge collection are tested.** It does not promise a game where correctly using statistical tools during the game is a part of these tests. Again, I’m not saying that augment stats were ever the optimal way of playing. However, in the eyes of the player base, stats were at least a viable option, so many people felt it valuable to consider and learn, despite it’s obvious externality to the game client. Whether players liked or disliked the usage of augment stats, Riot must have deemed in worthy of attention in pursuit of making the TFT experience more closely align with their vision. If they felt like player sentiment was negative about the health of augment statistics in gameplay and discussions, then as the developer, they made the choice to remove an unfun optimization that made TFT—as a game, as a product, as a community—less fun.

# Addendum: TFT’s quirks

TFT has a few unique aspects to it which makes it extra volatile to player perception: the unit drafting pool and the (ironically) low variance in game states.

### Every game contains everything

Mostly. There are, of course, decently impactful game-to-game differences: augment tier, encounters, and loot orb quality, but in general, you interact with the same individual units and systems. As a result, if something is generically strong, you can plan to encounter it in the vast majority of your games. Many other games do not have this quirk. If a single character is strong in a fighting game, you might encounter them at a frequency higher than the mean, but there will still be numerous games where you simply don’t see the broken stuff. If a champion is strong in League, bans can give players the agency to remove them from each individual game. In TFT, there is no such mechanism. If a strategy is strong, widely known, and isn’t locked behind a stringent set of conditions, then you can safely expect to see it in every game, or even multiple times a game. Small optimizations quickly become ubiquitous.

By the way, this is why TFT hotfixes so much in comparison to every competitive game ever. A single overwhelming comp can infect the game incredibly quickly once discovered and publicized. A bad meta causes fatigue and churn very quickly because its presence is in every single game. When these stale metas form, the game becomes extremely one-note, since these broken strategies are often quite forceable and consistent. Genuine poor quality metas demand change—otherwise players might experience the exact same unbalanced lobby dynamics for two weeks straight.

### Drafting Pool

The core of TFT is around its drafting pool: players all see shops that pull from the same pool of units, so any time specific units become more popular, they also becomes a significant (and perhaps measurable) degree weaker. Don’t quote me on this—this essay is already long enough so I didn’t want to further extend it—but there’s an estimate floating around somewhere that being contested at least one way adds +1.0 to your AVP, which is a very meaningful hit to consistency. Powerful stuff is likely to be contested, and so naturally causes the players who pilot the strategy to experience higher variance. The “every game contains everything” is a feels-bad for everyone not playing the meta strategies. The drafting pool is a feels-bad for the three contesters remaining.

The combination of these two traits listed above means that **the perception of power in TFT has comparatively more influence on actual play** than most other games. You will see the powerful stuff more frequently, information about them will spread faster, and they will lead to higher variance game states. Balancing TFT is simply extra difficult. The systems are so sensitive to each other that any slight disturbance will be magnified extremely quickly by the game’s mechanics, not even considering the conversations and content around the game. This is why controlling the perception of power in TFT is of great concern to Riot. They can’t control the entire propagation of information around TFT, but given the opportunity, it is reasonable to assume that they would like to manage the game’s image when possible. In a sense, taking away empirical proof of strength (through augment data) protects the player from overindexing into specific beliefs that have a measurable and frequently negative impact on their own experience.

# Conclusions, including my own

This topic is difficult. I just spent a while justifying why the removal of augment stats made sense from a developer perspective, but I’ve also spent three months thinking about whether or not I actually agree with the change.

Personally? **I love the stats side of TFT.** I am actually one of those people who found utilizing statistics to optimize the game as a fun and interesting skill test, even if I myself am not a particularly skilled player. Beyond the advantage stats may have imparted to people, I also just think they’re really interesting. The statistics ecosystem that has cropped up around TFT is a very unique draw to this game, and I am saddened that augment stats are gone because of how much depth they added to examining specifics about optimizing the game. My personal example was Superfan Annie in Set 10: my hypothesis was that frontline and item augments were strongest for Annie reroll before the line was fully developed, and my limited memory tells me that my hypothesis was supported in the augment stats for the line. Is this an intended part of the experience for TFT? Probably not, but I found it very fulfilling, and I’m sure other people share similar experiences. Augment stats meaningfully contributed to my enjoyment of TFT, and I have enjoyed TFT marginally less since its removal.

I don’t think my experience was injective to overall game health. The information that augment stats provided came at a cost of some fun here, some meta development there, and a overall lower quality discussion on the game. I hesitate to use the word “solve,” but the game certainly calcified more quickly with augment stats. When you can point to a number on a website and say “X augment is broken,” even if the reason behind it is complicated, the opportunity for productive discussion decreases. Players are less willing to experiment with situational, interesting picks if the generic choices are visibly performant. I wouldn’t say augment stats had a massive, load-bearing impact on how people interacted with the game, but it certainly seemed to have a measurable **dilutive effect on the intended TFT experience** if the tweet above is accurate.

Is this a strong enough justification to remove an interesting competitive tool? I guess. Would TFT be a significantly worse game if augment stats were still around? I’d personally say no. In the grand scheme of things, augment stats impact a small portion of the player base and carry some costs to game health. Their removal won’t kill TFT or save TFT. It will change the experiences of a few players a lot and most players very little. It is a statistically significant loss for what we can only hope to be a statistically significant gain.

Thank you for reading. Sorry I didn't have better ideas for graphics: this is more of an op-ed than the previous essays that I've written. If you enjoyed what I write, I have other related essays on my website for you to peruse.
