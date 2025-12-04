---
layout: project
title: CMHUB
image: "/assets/images/cmhub.png"
tags:
  - devops
  - jenkins
  - django
  - selnium
---

I worked, along with a friend, on a self-initiative project called 'CMHub', which stands for 'Community Managers' Hub'; it is a platofrm for community managers to collaborate in order to make posts before they publish them on Twitter, they can its content and they can get an estimation for how many reacts, comments, and retweets they will get in different time based on the content of the tweet post.
Technically speaking:
- We scraped data from twitter
- We built different models for the reacts, comments, and retweets numbers respectively using Random Forests based models for regression
- We built the web platform using Django as a full stack
- We made a CI CD pipeline on Jenkins that contains a testing stage (both unit testing and front end testing with Selenium), a sonarqube stage, and a stage for Dockerizing the application and uploading it on DockerHub
During this project, we used a lot of tools for the first time, which further enhanced our technical capabilities, and most importantly, we learned how to work as a team, which was definitely challenging because 95% of the interaction was virtual, but we took that challenge and we completely nailed it !

Check it out [here](https://github.com/MohamedBilelBesbes/CMHub).