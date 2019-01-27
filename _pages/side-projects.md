---
layout: archive
title: "Side Projects"
permalink: /side-projects/
author_profile: true
---

{% include base_path %}


I am currently working on developing a serverless Slackbot.  The slackbot runs on the OpenFaaS serverless framework, which builds off of Kubernetes.  As of now, the slackbot scales down to zero, and is booted whenever someone joins a Slack channel, welcoming the user to the channel.  The slackbot then scales back down to zero, consuming minimal computational resources.

The code to my Slack Bot can be found [here](https://github.com/gregcusack/serverless-slack-bot). 
  
