---
title: 'Contribute to this project'
permalink: '/contribute/index.html'
layout: layouts/page.njk
---

My aim with this project is to document the hidden history of the open web, 
and to do this in a way that encourages contributions. 
Here are some ways to help.

## Suggestions for people to feature

Perhaps you have a story to tell of your involvement on the web, 
or you know of someone whose contributions should be included. 
In the first instance [raise an issue](https://github.com/rachelandrew/webhistories/issues). 
If you want to do the interview and writing, 
I'll be very happy to act as your editor. 

## Timeline additions

What am I missing? I'd like the timeline to feature the key events in the development of the web platform. 
Raise an issue and I can add the data. 
Or you can submit a Pull Request, 
timeline events are created by adding a new file under `/events` inthe following format:

```
---
title: The W3C is formed
date: '1994-10-01'
image: false
tags: events
---

The World Wide Web Consortium (W3C) was founded by Tim Berners-Lee at MIT.
```

## Biography data

I am trying to write reasonable biographies for anyone mentioned. 
These live under `/people` with the following structure:

```
---
name: Rachel Andrew
twitter: rachelandrew
web: https://rachelandrew.co.uk
image: false
tags: people
---

Text biog date here
```

You can create a PR or raise an issue to add data for someone who doesn't have a biography yet, 
correct or add to existing data.
