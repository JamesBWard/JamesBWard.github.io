---
layout: post
title:  "Exploring the lichess puzzle database"
date:   2026-09-03 15:28:58 -0700
categories: projects
---
There are two popular chess websites on the internet. Chess.com is the most popular site and charges REAL MONEY to play chess online. Lichess.org is free, opensource, and doesn't track or advertise users. Their feature set is superior but somehow chess.com remains more popular. I could never figure that one out. Anyway, lichess has a free database of chess puzzles anyone can download: 

https://database.lichess.org/

Test data can be hard to come by, and this is one of my favorite free datasets to use for projects. I've used it in classes I've taught and for coding challanges I've written professionally. Lichess has several databases including 8 billion rated games of chess, 6 million rated chess puzzles and 400 million selected positions which have been analyzed in depth by advanced engines. 

Here is how to search the lichess puzzle database and a few selected interesting puzzles I was able to find: 

Step 1: when you're processing a lot of data make sure you have sufficiently fast storage. I'm lucky to have build my current PC before memory prices went verticle, so I'll be using a ramdisk: 

