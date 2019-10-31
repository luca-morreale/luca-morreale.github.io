---
layout: post
title: "Learning and Mining Player Motion Profiles in Physically Interactive Robogames"
date: 2018-01-10 15:38:28
comments: false
description: "Human-Robot Interaction"
keywords: "HRI"
categories:
- projects
img: hri.png # Add image post (optional)
tags: [Human Robot Interaction, Machine Learning, Robotics, Perception, Player Modeling] # add tag
---

**Abstract:** Physically-Interactive RoboGames (PIRG) are an emerging application whose aim is to develop robotic agents able to interact and engage humans in a game situation. In this framework, learning a model of players’ activity is relevant both to understand their engagement, as well as to understand specific strategies they adopted, which in turn can foster game adaptation. Following such directions and given the lack of quantitative methods for player modeling in PIRG, we propose a methodology for representing players as a mixture of existing player’s types uncovered from data. This is done by dealing both with the intrinsic uncertainty associated with the setting and with the agent necessity to act in real time to support the game interaction. Our methodology first focuses on encoding time series data generated from player-robot interaction into images, in particular Gramian angular field images, to represent continuous data. To these, we apply latent Dirichlet allocation to summarize the player’s motion style as a probabilistic mixture of different styles discovered from data. This approach has been tested in a dataset collected from a real, physical robot game, where activity patterns are extracted by using a custom three-axis accelerometer sensor module. The obtained results suggest that the proposed system is able to provide a robust description for the player interaction.


{% comment %}
Human Robot Interaction (HRI) is a multidisciplinary field involving, among other, Robotics and Machine Learning which studies the behavior of human and robots while they interact. The goal of this project was to study the behavior of the player in a robogame scenario. In such environment it is fundamental to distinguish the player, i.e., track its movements, and comprehend his/her behavior to properly match it with a behavior from the robot which maximize the fun during the game. A similar approach is used in online games which, based on wins and losses, the players are ranked to have fair matches in the forthcoming games.
We model the player behavior as mixture of existing player models, extracted from a training set of games.
{% endcomment %}

{% comment %}
I worked with the PhD candidate Ewerton Lopes Oliveira to model the behavior of humans in a robogame scenario. We initially published a journal article on a special issue about classification player behavior, afterwards we studied methods to identify, and track, a player in a robogame environment based on its movements.
{% endcomment %}

#### Related Publication

[[HTML](https://www.mdpi.com/1999-5903/10/3/22/html)][[PDF](https://www.mdpi.com/1999-5903/10/3/22/pdf)][[CODE](https://github.com/ewerlopes/lda-player-model)] E.L.S. Oliveira, D. Orrù, L. Morreale, T.P. Nascimento, A. Bonarini. *Learning and mining player motion profiles in Physically Interactive Robogames* **@** Special Issue of Future Internet on Human-Robot Interaction (Journal)
