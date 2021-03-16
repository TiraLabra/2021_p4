---
layout: info
title:  "Topic ideas"
categories: jekyll update
tag: info
permalink: /en/topics/
---

You can either come up with your own topic or pick one from the ones below. The topics below are just examples, you can modify them if you want. The final topic will be decided with the help of, and approved by, the course assistant. Some more ideas may be found from older course [pages](https://github.com/TiraLabra/).

## Graphs and pathfinding

* How to find the fastest way possible out of a labyrinth. The labyrinth could be ASCII-art or a picture.

* How to find the fastest/shortest path between two nodes in a grapth. The nodes could be for isntance street addresses, bus stops or coordinates. See this article if interested: http://theory.stanford.edu/~amitp/GameProgramming/AStarComparison.html

* Compare at least two different path finding algorithms, one of which differs clearly from what you have learnt in Data structures and algorithms course. Eg. JPS, IDA*, fringe search (complicated). A-star is not sufficient for the demanding algorithm.

* Maps for pathfinding can be found at [Moving AI Lab](http://www.movingai.com/benchmarks/) and the [downloads site](http://kartat.kapsi.fi/) for the National Land Survey of Finland.

* Implement a visualization of the path and covered nodes / jump points at early stage of development. Otherwise it is difficult to see whether the algorithm is correct. Although there may be data of certain paths and their lengths with your maps, a correct length does not guarantee that the algorithm works like it should. The visualization helps both checking the correctness of a complete work and finding errors during the development.

* Public transit data [https://developers.google.com/transit/gtfs/](https://developers.google.com/transit/gtfs/) or [https://digitransit.fi/en/developers/](https://digitransit.fi/en/developers/) and open map data [https://www.openstreetmap.org](https://www.openstreetmap.org) have also been popular.

## Data compression

* How to compress a given file as efficiently as possible? A desired outcome would be at least a 40-60 % reduction in size. And the file has to be inflatable back to the original. How well can your implementation fare compared to existing solutions?
    * Huffman
    * Lempel Ziv

## AI

* Chess, Go, expanded naughts and crosses and so on are fun and challenging games. Can you create an AI that can play against a human opponent as well as against itself? How good is it?

* You can find a java template for a chess bot using [xboard](https://www.gnu.org/software/xboard/) and the [Lichess api](https://lichess.org/blog/WvDNticAAMu_mHKP/welcome-lichess-bots) from here: [https://github.com/TiraLabra/chess](https://github.com/TiraLabra/chess)

* Rock-paper-scissors ia a very familiar game. Can you create an AI that beats a person? How about [Rock-Paper-Scissors-Lizard-Spock](http://www.youtube.com/watch?v=x5Q6-wMx-K8). Note that this topic is pretty challenging for the background knowledge of typical students taking the course. ![lizard spock](http://upload.wikimedia.org/wikipedia/commons/a/ad/Pierre_ciseaux_feuille_l%C3%A9zard_spock_aligned.svg)

* A solver for the well-known [15 puzzle](http://en.m.wikipedia.org/wiki/15_puzzle). The 15 puzzle can be a bit challenging. Can you create a program that solves any 15 puzzle very fast? How about bigger play areas?

* [Minesweeper](https://en.wikipedia.org/wiki/Minesweeper_(video_game)) is another popular puzzle. Why not create a solver/helper using the project template avaialble at [https://github.com/TiraLabra/minesweeper](https://github.com/TiraLabra/minesweeper)

* [halite](https://halite.io/) AI. Or any other similar online AI challenge.

## Dungeon generator
* A fairly popular topic is creating dungeons for games such as Rogue or NetHack. There exist several algorithms that can be implemented or you could just roll your own. Generation can be either entirely done before hand or be dynamic.


## Data structure comparisons
* There are many different data structures that do basically the same thing. Which of them is best for some given problems? Compare some (for example 4) different data structures and see what happens.


## Encryption and security
* Security is a very important topic in the modern world. There are many different ways to encrypt or hash data for many different reasons. This website has many ideas related to this topic: http://rumkin.com/tools/cipher/index.php

* There are many ways to attack compressed, encrypted or hashed data. The above link contains some ideas for this as well. Or how about using frequency analysis to analyze an encrypted file? This is also very closely related to Huffman compression: http://rumkin.com/tools/cipher/frequency.php


## Signal processing (images, sound)
* Implement one or more signal processign algorithms and report on your findings. Note that this may require some background knowledge of linear algebra.

## Something else
* The logistics company FastFreight wants to minimize the space wasted when packing containers. How can you calculate how to pack containers as efficiently as possible given a number of packages with given sizes?

* Design and implement a regular expression engine. Why? Read this for an answer: https://web.archive.org/web/20181227172507/https://blog.stevenlevithan.com/archives/10-reasons-to-learn-and-use-regular-expressions
