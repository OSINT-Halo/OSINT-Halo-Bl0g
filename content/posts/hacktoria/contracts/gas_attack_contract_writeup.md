---
title: "[Hacktoria] Gas Attack Contract Writeup"
date: 2023-06-03T11:17:39+05:30
draft: false

categories: ["hacktoria"]
tags: ["contract"]

featuredImage: "/assets/images/hacktoria/gas_attack/gas-attack-f-image.jpg"
featuredImagePreview: "/assets/images/hacktoria/gas_attack/gas-attack-f-image.jpg"
---

This is my first writeup on this blog. In this writeup, I solved the [Hacktoria Gas Attack Contract](https://hacktoria.com/contracts/gas-attack/). I hope you get to learn something new from this.

# Contract Briefing

Greetings, Special Agent K. We have an urgent and very grim scenario on our hands. About 20 minutes ago, we received word from one of our red teams, that they’ve uncovered plans on the dark-web to test a new neuro-toxic gas on an undisclosed city.

The group’s name has not yet been uncovered, but is believed to operate decentralized online, sharing the same ideal in the radical right spheres. Over the past months, we’ve observed talks and discussions, glorification of and finally concrete plans to build a dirty bomb.

As of today, our HUMINT team was able to infiltrate partial circles of the group. Our Red Team was able to pull images from the browser cache of the member our HUMINT team was in contact with.

The image reveals a city, which is believed to be the testing ground for the dirty bomb. We still do not have a time-frame for the attack, all we know is that the amount of gas will cost hundreds of people their lives. Not to mention the suffering ending caused by the gas itself.

Our priorities are to find out more about the group, this is done in collaboration with EUROPOL, hence our main task is finding the location of the city. We hope the realization that the location of their plans has leaked, will cause some of the members to make a bad move.

Your task is to locate the city in the image below.

As always, Special Agent K. The contract is yours, if you choose to accept.

![Locate The City](/assets/images/hacktoria/gas_attack/gas-attack-1.jpg "Locate The City")

# Objective

As per the briefing given in the contract, we have to find the city and the country from the above image before the bomb sets off and its too late. The format of the flag is:
> country-city

# Solution

First of all, I reverse searched this image using the **Google Search** and it instantly gave me the name of the city and country shown in this image. The target of the group is the **Brussels** city which is in **Belgium** country.

![Google Reverse Image Search](/assets/images/hacktoria/gas_attack/gas-attack-2.png "Google Reverse Image Search")

The target of the group is **Parc du Cinquantenaire** as seen by the cross sign in the image.

![Parc du Cinquantenaire](/assets/images/hacktoria/gas_attack/gas-attack-3.png "Parc du Cinquantenaire")

Next, I entered **belgium-brussels** as the flag password into the file and I got the contract card.

![Gas Attack Contract Card](/assets/images/hacktoria/gas_attack/gas-attack-4.png "Gas Attack Contract Card")

I hope you enjoyed reading my writeup for the **Hacktoria Contract**. I will keep posting more learnings and writeups on this blog, so stay tuned for that.