---
layout: post
title:  "Hello World 2.0!"
permalink: /helloworld2/
#permalink: /jekyll2/
date:   2022-06-03 21:20:00 -0400
categories: ["the-weekly-thread", "test"]
drink: "Tokyo Tea"
ingredients: ["1/2 ounce gin","1/2 ounce melon liqueur","1/2 ounce rum","1/2 ounce tequila","1/2 ounce triple sec","1/2 ounce vodka","1 ounce sweet and sour mix*","1 splash club soda","Garnish: lemon wheel","Garnish: maraschino cherry"]
steps: ["Add gin, melon liqueur, rum, tequila, triple sec, vodka and sweet-and-sour mix into a highball glass with ice and stir to combine.", "Top with the club soda.", "Garnish with a lemon wheel and maraschino cherry. "]
tags: ["jacob was here", "first", "i hate css", "tokyo tea"]
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{% include drink.html ingredients=page.ingredients steps=page.steps drink=page.drink %}