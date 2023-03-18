---
title: "Web Scraping NBA Data"
date: 2023-03-16
image: "/images/post-pics/nba.webp"
tags:
  - web-scraping
  - basketball
---

### The NBA Draft

As a fan of the Utah Jazz, I am particularly interested in basketball players coming into the league.
Every team gets two picks each year in a draft, and whichever of the new players they pick will be on their team for at least the next few seasons.
The thing that makes this interesting is that the order of the draft is based on how many wins the team had in that season.

For Utah, this will be an important draft
The team recently traded away several of its stars and seemingly is trying to reset.
This can be a good thing for NBA teams because it means they have better chances at getting a good, young player on their team which tend to stay for a long time.
All of that depends entirely on how well the team can choose acurately players that will find success.
I would like to find something of an answer to the question: how good are NBA teams at assessing which players will succeed in the league.

For this project, I found some useful data on the website [Basketball-reference](https://www.basketball-reference.com/),
which has a page for each year of the NBA draft.
They have a [robots.txt](https://www.basketball-reference.com/robots.txt) file which allows for people to scrape that part of the site with a limit of the rate of requests to the site (1 every 3 seconds),
so I proceeded to web-scrape the data.

The process was fairly simple for a single site.
In python you could simply use the `read_html` method and extract the necessary table.
Problems arose with 
