---
layout: project
type: project
image: img/chat-app/live-chat.png
title: "Simple Chat App"
date: 2015
published: true
labels:
  - Socket.io
  - Node.js
  - React
  - Deployment
summary: "A minimalistic live chat app with user and chat room"
---

# Simple Chat App

<img class="img-fluid" src="../img/chat-app/live-chat.png">

![demo](demo/live-chat.png)

A minimalistic live chat app with user and chat room, built using node.js and socket.io with react.js front-end. It also shows activity likes "user is typing" to other participants in the chatroom.

You can try it out on this website:

https://my-chat-app-five-lemon.vercel.app/

The deployment was done using Vercel for the front-end. Azure Web Service for the back end because vercel doesn't seem to support web socket, at least not easily : \( 


## What I learned

This experience taught me a lot about how to use web socket for real time communications. Deploying it on the web also gave me the experience with Vercel.


The deployment was done using Vercel for the front-end


## Show me the code

Here is a snippet of my code and link to github repo:

{% gist 9defa1fb3f4eb593ba5fa9eacedca960 %}
 
Source: <a href="https://github.com/theVacay/vacay">theVacay/vacay</a>
