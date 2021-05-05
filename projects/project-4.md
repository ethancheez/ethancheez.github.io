---
layout: project
type: project
image: images/music-match-square.png
title: Music Match
permalink: projects/music-match
# All dates must be YYYY-MM-DD format!
date: 2021-05-04
labels:
  - Semantic UI React
  - Meteor
  - Database
  - Web Development
  - JavaScript
  - HTML/CSS
  - Software Engineering
summary: The final project for ICS 314 designed to allow people to share their favorite music and connect with others that share music interests.
---

<img class="ui center floated image" src="../images/music-match.png">

At the end of the Spring 2021 semester, it was finally time to merge all of my knowledge gained throughout the semester. Javascript, to HTML/CSS, to Semantic UI, to Semantic UI React, and finally Meteor. Everything I learned all in one major project. The Music Match project was a web application designed to allow students to upload their profile indicating their music interests, talents, and goals. Users can view other profiles and network with new friends with similar music interests. Additionally, users are able to share their favorite music, or "jams", for others to listen to.  

My main contributions towards this project involved the back end development and the final deployment of the site. This included implementing the functionality for the different collections in the database, profiles, and jams. Specifically, I created the profile and jams collections which allows users to create a profile and add jams to the site's database. I also integrated a music interest multi-select field within the profile which allowed users to pick multiple music interests from a set list. The jams included a like and comment feature so users can interact with each individual jam. For the front end development of the site, I was in charge of redesigning the landing page to make it more visually appealing. Upon receving feedback from multiple users, I made some minor adjustments to the site. I implemented new filters to the browse jam pages, allowing users to sort jams by the date created, alphabetical, number of likes, or by user.

<img class="ui center floated image" src="../images/music-match-browse-jams.png">

This was the first time I have ever created a website. In the beginning, I expected to run into many issues because it was difficult to grasp how Meteor works. However, completing this project allowed me to gain a lot of skills in web development. Primarily, I had a better understanding of how Meteor and MongoDB operates. Being able to create multiple collections, and even integrating a collection inside of another collection, was the most useful method of learning. For example, the profile collection contained the music interest collection. Likewise, the jams collection contained the likes and comments collection. Being able to accomplish this, I believe I am able to have an easier time solving issues for future sites I will develop. Ultimately, learning the foundations of frameworks such as Semantic UI will be very helpful in future web development projects as it is easier to integrate and more visually appealing as compared to raw HTML/CSS.

The final product of this project turned out much better than I had expected. Despite this, I still hoped to learn more about web design by implementing additional features such as:
	- Private chatting feature between two people or a group of people
	- Ability upload videos from other sources and not being restricted to YouTube
	- Fixing the copyright issue that prevents certain videos to be played on the site

The source code of the game can be found in this [GitHub Repo](https://github.com/music-match/music-match)

Our project page can be viewed [here](https://music-match.github.io/)
