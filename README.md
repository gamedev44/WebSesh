# WebSesh

**WebSesh** is a cool smoking‑game application for WeedTube built entirely by the one and only **Asterisk**, designed to reward you in times of boredom.

---

## Table of Contents

1. [Live Demo](#live-demo)  
2. [Summary](#summary)  
3. [Demo & Play](#demo--play)  
4. [Features](#features)  
5. [Tech Stack](#tech-stack)  
6. [Usage](#usage)  
7. [Persistence](#persistence)  
8. [Store & Economy](#store--economy)  
9. [Responsive & Mobile Support](#responsive--mobile-support)  
10. [Contributing](#contributing)  
11. [Author](#author)  
12. [License](#license)  

---

## Live Demo

<a href="https://gamedev44.github.io/websesh" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/►%20Play%20Live-WebSesh.io-blue?style=for-the-badge" alt="Play Live">
</a>

---

## Summary

WebSesh turns your webcam into a sensor‑driven smoking simulator. It detects “rip” motions (bong, pipe, or chop) by color tracking on the video feed, counts your hits, levels you up through hilarious “lung” ranks, and rewards you with tokens to spend in an in‑game store.

---

## Demo & Play

Simply visit the live link above—no installation or build steps required.

---

## Features

- **Three Modes**  
  - **Bong Mode**: Clean → Dirty → Stanky stages with custom bong art  
  - **Pipe Mode**: Pipe rip sound & graphic  
  - **Chop Mode**: “Get to the choppa” sound & mixed strain/tobacco  

- **Real‑time Rip Detection** via HSV color thresholding  
- **Hit Counter & Ranks** (Baby → Hellfire Lungs)  
- **Token Economy & Store** (earn one token per rip, spend on items)  
- **Persistent Settings** (name, mode, tokens, purchases saved in localStorage)  
- **Clean‑Your‑Bong Modal** when it’s time to recycle  
- **Responsive & Mobile‑Friendly** layout and touch support  
- **Audio Unlock** flow to bypass autoplay restrictions  

---

## Tech Stack

- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)  
  
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)  
   
- ![WebRTC](https://img.shields.io/badge/WebRTC-4D148C?style=flat&logo=webrtc&logoColor=white) ![Canvas API](https://img.shields.io/badge/Canvas_API-777777?style=flat)  
   
- ![LocalStorage](https://img.shields.io/badge/LocalStorage-FFD600?style=flat)  
   

---

## Usage

1. Grant camera access.  
2. Enter your name and pick **Bong**, **Pipe**, or **Chop** mode.  
3. Choose a strain (or mix in Chop mode).  
4. Click **Start Sesh** and rip in front of your webcam—each release adds to your score, rank, and tokens.  
5. Hit **Store** to spend tokens on items like a Bic lighter or new strains.

---

## Persistence

All key data (user name, selected mode, score, tokens, owned items) is stored in **`localStorage`** so your progress carries across sessions.

---

## Store & Economy

- Earn **WeedTokens** on every successful rip.  
- Open the **Store** to buy:
  - **Bic Lighter** — 50 tokens  
  - **New Strain** — 100 tokens  
- Purchases persist and once owned, remain “Owned.”

---

## Responsive & Mobile Support

- Fluid layouts (`vw`, Flexbox, Grid)  
- Media queries for small screens  
- Large, touch‑friendly controls  

---

## Contributing

WebSesh is 100% open‑source—feel free to clone and help out!  
```bash
git clone https://github.com/gamedev44/websesh.git
```  
Pull requests welcome, just mind the upcoming **Apache 2.0** license—no sticky fingers allowed. 😉

---

## Author

**Asterisk**  
[Resume & Contact](https://gist.github.com/gamedev44/04c21006def2d0ffe54ecc1b57aca2cd)  
[![GitHub](https://img.shields.io/badge/GitHub-@gamedev44-181717?logo=github)](https://github.com/gamedev44)

---

## License

This project is planned to be licensed under the **Apache 2.0** License.  
```
