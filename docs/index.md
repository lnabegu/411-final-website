---
title: Phlappay Byrd Engine
---

#  Phlappay Byrd Engine 
By: Lauren Lee, Ayush Tibrewal, Lailah Nabegu

---

## 📑 Table of Contents
1. [📖 Overview](#overview)   
2. [⚙️ Getting Started](#getting-started)  
3. [🚀 Demo](#demo) 
4. [📜 Documentation](#documentation)
5. [📐 Architecture](#architecture)   
6. [⚰️ Post Mortem](#post-mortem)  


---

## 📖 Overview
For our final project, we decided to create an engine develop their own version of Phlappay Byrd. There is also a level editor GUI that allows users to design all 3-levels of their game, add and delete pipes, and change pipe gap, and game speed. In the demo section, there is a video with a showing a Phlappay Byrd game we built that takes advantage of our engine tools.  
 
---

## ⚙️ Getting Started

Make sure that SDL2 and SDL_ttf are installed. In order to run the level editor run: 
```
python3 leveleditor.py
```
After you set the levels, you can compile the game using dub and you should be able to play!

---

## 🚀 Demo
[INSERT DEMO HERE]

---


## 📜 Documentation

---

## 📐 Architecture
![Alt text](PNG-image.png "Engine Architecture")

---

## ⚰️ Post Mortem
We're generally pretty happy with what we were able to get done in a month. We were able to recreate an old game that users can customize, and we worked pretty efficiently to do so!
However we would've definitely liked to add more options for customizing (ex: changing backgrounds/sprites, modifying physics, and adding levels). It would have been fun to develop a more general-purpose engine for horizontal scroll games, where people could even import their own game logic or scripts. 

If we had more time, we could have made the logic more modular and extensible so that at least players could upload assets and define more rules of the game. We also could have added sound effects and a score-tracking system! Nonetheless, this project was a great opportunity to combine many of the concepts we learned this semester to make a fun game. We hope you enjoy Phlapping!
