---
layout: title
title: It's raining!
date: 2022-06-21 17:08:43
tags: rain, lofi, chill
---

So, currently, it's raining, and i want my code-fi beats.

I was opening youtube - when I thought:

* Youtube is a **video** hosting site

* **Videos** suck the CPU dry

* Juice from the CPU is needed for compilation

* **Audio** still uses the CPU, but it's not as much as **video**

* **USE AUDIO**

* But then again, `yt-dlp`-ing a video again and again is hard

* I should make a shell script.

Here's the script:

```shellsession
yt-dlp <video here> --output ~/code-fi.mp3
mpv ~/code-fi.mp3 --no-terminal
rm -f ~/code-fi.mp3
```

That's it!
