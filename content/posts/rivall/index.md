---
title: "Rivall"
date: 2024-06-25
description: "My third year project"
summary: "A mobile game to challenge your friends"
tags: ["project"]
params:
    showEdit: false
---

During my third year of my IT Bachelor's degree (BUT informatique), I developed a cross-platform mobile game called "Rivall" with four of my classmates.

## Game Objective

Our application is a mix between a game and a social network. Users can add friends, modify their profiles, and communicate with each other via messaging. To start a game, a group must be created. At this point, the group members receive quests. The objective is to complete as many quests as possible as quickly as possible.

Once a quest is validated by the group members, the player receives points and can view the group's leaderboard.
![score](./score.png)

## My Contribution

In this project, I set up a REST API with `Django Rest Framework`. This allowed me to configure the registration and authentication mechanisms for our mobile application. Later in the project, I added a layer to manage the WebSocket protocol, which enabled me to implement instant messaging in our application.
