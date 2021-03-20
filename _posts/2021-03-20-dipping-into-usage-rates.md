---
toc: true
layout: post
description: Understanding Usage Rate Trends of various PL teams
categories: [football]
title: Dipping into Usage rates
---

# Defining Possession Usage rates

## The calculations

Usage rate is a metric used in basketball analytics to understand how much of a team's possessions are used by a player. This metric has been shown to be correlated with centrality in pass network by [Devin Pleuler](https://www.mlssoccer.com/post/2014/08/20/central-winger-how-measure-players-influence-through-touches-or-lack-thereof). It allows us to measure which players on a team are central to the attack and how efficient they are with the ball.

>[Usage rate](https://www.nbastuffer.com/analytics101/usage-rate/), a.k.a., usage percentage is an estimate of the percentage of team plays used by a player while he was on the floor.

I have used [Martin Hawkes-Teeter](http://www.onceinabluemean.com/2015/11/city-is-kevin-de-bruynes-team-already.html)'s definitions of Usage rates and positive to negative ratios in this article. The formula is rather straightforward as can be seen below. Terms which have a '+' sign as a superscript are considered positive actions and those with a '-' sign are considered negative.


> ![\Large UsageRate=\frac{(Shots^+ + KeyPasses^+ + Miscontrols^- + Dispossessions^- + Unsuccesful Take Ons^- + Unsuccesful Passes^-)}{(SquadTotals * \frac{90s\ Played}{Total\ 90s})}](https://latex.codecogs.com/gif.download?%5Clarge%20%5CLarge%20Usage%20Rate%20%3D%20%5Cfrac%7B%28Shots%5E+%20+%20KeyPasses%5E+%20+%20Miscontrols%5E-%20+%20Dispossessions%5E-%20+%20Unsuccesful%20Take%20Ons%5E-%20+%20Unsuccesful%20Passes%5E-%29%7D%7B%28SquadTotals%20*%20%5Cfrac%7B90s%5C%20Played%7D%7BTotal%5C%2090s%7D%29%7D) 

With the context set, let's dive into the profiles of some teams in the Premier League over the last 4 seasons.

## Chelsea
Chelsea's attack was often described as completely dependent on Eden Hazard during his time here. This is particularly true under Sarri's regime. Him and Willian are on a completely different level in terms of using possession and also being highly efficient with their actions. The median usage rate is the lowest it has been while the efficiency is pretty high. That goes to show that the majority of attaking impetus and risk taking came from Hazard and to an extent Willian. This is also borne out by the fact that Hazard had the most positive actions(183 Shots+KP)
![](https://i.imgur.com/w0gyqCb.png)

## Manchester City
Kevin de Bruyne is amazing. When he's fit and firing, there's simply nobody in the PL who can touch him in terms of creativity. He is the hub of this team Pep has built. 
![](https://i.imgur.com/uYK9Bp4.png)

## Liverpool
All I can say is Salah, Mane and Firmino are exceptionally efficient players.
![](https://i.imgur.com/hqkI8PX.png)

## Manchester United
It's the Bruno Fernandes show at Manchester United. He has a very high influence on United's attack but he's also wasteful. Nobody else really takes risks, so that works out well for them. Luke Shaw is also having a really good season.
![](https://i.imgur.com/b9CmURc.png)