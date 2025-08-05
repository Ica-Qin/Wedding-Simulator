# Wedding-Simulator
*A game made by Peiyang Qin, Xueyi Wang, Xinru Xie, Haoqing Yan*

![游戏logo](https://github.com/user-attachments/assets/dab80e32-879c-41d0-9028-577fece7dac1)



---

## Project Title: Wedding Simulator

### Project Description

This project addresses wedding anxiety in China, where personal desires conflict with social expectations. Couples imagine weddings as intimate celebrations of happiness and life milestones, while traditions often transform them into public announcements—a set of requirements and a place for the relational network of the two people to be woven together, sometimes causing embarrassment and discomfort at a moment meant for joy.

We asked: if these conflicts and awkward moments happened only in a game without real-life consequences, what choices would players make? Thus, we decided to make a game for the players to enjoy a wedding of “complete freedom”: eat as much as they like or throw away everything, smile to respond to the guests or slap them and even change the background music to Plants v.s. Zombies BGM. Every behavior might trigger an achievement, no matter rude or polite. Smiles would add score, and other actions might deduct score, but no matter how many scores, or how many minus scores one gets in the end, we, as the Game Producer, would congratulate them for whatever they get from the game experience.

The player tests showed that the game brings fun and laughter, as participants happily slapped and threw items despite penalty points. We hope this case demonstrates how a playful simulation can help alleviate life’s anxieties by giving players a safe, stress-free space to explore social pressures.

### Technical Description

Our Unity demo includes three scenes: start screen, wedding introduction, and ceremony. 3D assets combine commercial packs and custom models crafted in Blender. Real-time smile detection and hand-tracking leverage OpenCV and UltraLeap plugins. UI layouts were designed with CorelDRAW. Player input and camera movement are handled via Joy-Con/Gamepad using a custom Unity player controller. The game features ten achievements integrated into a live scoring system, with animated pop-up notifications for score changes. A dialogue system with dynamic text and branching choices manages NPC interactions, while NPCs use Animator blend trees to react to player behaviour and game events.


### Personal Contributions

I engineered the Joy-Con player control system using a custom Unity controller, enabling intuitive navigation and camera movement. I also integrated Leap Motion–based gesture interactions for eating, throwing, and slapping, fine-tuning input mappings and response thresholds. I built the real-time scoring and achievements system with animated pop-up notifications. Additionally, I managed translation workflows and implemented dynamic text localisation to ensure narrative coherence across languages. Together, we conducted user interviews to inform game design, iterated collaboratively on gameplay mechanics, ran comprehensive player tests, produced detailed documentation, and prepared the presentation.

**Team-mates:**

**Xinru Xie**:
Initial Research Framework / Questionnaire Design / Interview Structures Design / Research Analysis and Reports / OpenCV Smile Recognition / Score Animation

**Haoqing Yan**:
Modelling and Building the Game Items and Sceneries / NPC and Second Scenery Animation / Player Guide Image / Camera Moving Control / Switches of Sceneries

**Xueyi Wang**:
Initial Game Framework / UI & Visual design / NPC Chats Writing / NPC Dialogue System / The Beginning Scene / Video Production / Early Stage Arduino Controller

**Peiyang Qin**:
Joycon(Gamepad) Player Control / Leap Motion Gesture Interaction Control(Eat, Throw, Slap) / Score and Achievements Systems / Dialogue and Text Translation

**Togeter**:
Interviews, Game Design, Player tests, Documentations, Presentation

---

### Project Images and Demo Video

**Demo Video (Please Unmute)**
[![Watch the video](https://img.youtube.com/vi/视频ID/hqdefault.jpg)](https://www.youtube.com/watch?v=视频ID)


**Images and GIF**

![opening](https://git.arts.ac.uk/23014796/Responsive-Environments-Blog-2024/assets/1264/0eb36909-295f-4ed3-a03f-c2a48ea06297)

![微笑](https://github.com/user-attachments/assets/238ace0f-b2d7-4ab5-8d0a-f79dbd0a7a3c)

![扇巴掌背后 (2)](https://github.com/user-attachments/assets/f86e9d99-c8be-4cfc-a408-8a35243bd850)

![eat](https://git.arts.ac.uk/23014796/Responsive-Environments-Blog-2024/assets/1264/2b169c0a-6e10-4dfa-8331-300ac9b055cb)

![achievement](https://git.arts.ac.uk/23014796/Responsive-Environments-Blog-2024/assets/1264/4a3208d2-cfe5-4e9c-9e9d-5af770e075ab)
![finalscore](https://git.arts.ac.uk/23014796/Responsive-Environments-Blog-2024/assets/1264/7215b615-2871-4143-925f-5aae2155e953)



### Project Files and Assets

[Google Drive: Unity Package and Game Package Ready to Play](https://drive.google.com/drive/folders/1964qhad8_6lLrK5bnlYVya_2SSICtfa4?usp=drive_link)

There are too many files in the package, which makes it difficult to upload it to GitHub, so we use Google Drive as a replacement. There are the raw Unity package together with a ready-to-play package. 

**Playing Gudie**:

To enjoy the full version of the game, please open the PC Camera, link a Leap Motion 2, and connect an Xbox gamepad or Joy-Con L to your computer(to connect Joy-Con, you need to install BetterJoyForCemu). If you want to try the game without the mentioned hardware, you can only use the PC Camera for smile detection, and use keyboard and mouse to control the player (WASD for moving, mouse for views, E for interactions, Space for next, and B for slap).

[Research Figma Board](https://www.figma.com/board/7OxuoWrRuigS35JgUnCIRj/%E5%A9%9A%E7%A4%BC%E7%84%A6%E8%99%91-%E7%94%A8%E6%88%B7%E8%B0%83%E7%A0%94?node-id=0-1&t=K1sH5q51nyxYS8l3-1)

---

### Playtest Results and Revision Plan

**Test Process**

At Demo Day, we invited 6 players to participate in player testing. We aimed to collect player feedback by having players fill out pre- and post-test comparative questionnaires. 

![term3 final_playtest](https://git.arts.ac.uk/23014973/Responsive-Environments-Blog-2024/assets/1292/5ea0d3f0-2c12-4902-8bb4-5d95c6fa4dcf)

The test questions were designed around aspects such as "wedding anxiety index," "authentic emotional expression," and "emotional changes before and after the game." The questionnaire structure referred to **CEDAR** (a structured observation tool in user testing that includes Context, Expectations, Decisions, Actions, and Responses).

For the **pre-test questionnaire**, to reduce the players’ testing burden and allow them to quickly enter the game, we adopted a **multiple-choice questionnaire** format.

For the **post-test questionnaire**, to better explore players’ authentic thoughts and their experiences of the game, we chose an **open-ended questionnaire** format.

Link to [questionnaire content & data feedback](https://git.arts.ac.uk/23014973/Responsive-Environments-Blog-2024/blob/main/term3%20Final%20Project/Playtest%20Questionnaires.md)

**Test Analysis**

*Pre-Post Player Data Comparison*
| Player         | Pre-Test Profile                                                 | In-Game Main Actions & Decisions                  | Post-Test Emotional Change & Feedback                            |
| -------------- | ---------------------------------------------------------------- | ------------------------------------------------- | ---------------------------------------------------------------- |
| **Player 1**   | Moderate anxiety, eager to explore emotions, independent mindset | Changed music, threw food, slapped a guest        | Felt lighter, weddings seemed less rigid, safe emotional release |
| **Player 2**   | High anxiety, high social pressure, wanted to feel understood    | Smiled at guests, threw cake, slapped a guest     | Anxiety decreased, breaking rules brought relief, felt safe      |
| **Player 3**   | Relaxed, neutral to positive attitude, eager for self-expression | Changed music freely, threw food, slapped a guest | No emotional change, purely fun, felt freedom                    |
| **Player 4**   | Low pressure, focused on politeness and partner collaboration    | Smiled at guests, changed music                   | No big emotional change, felt positive, explored playful options |
| **Player 5**   | High anxiety, high pressure, hoped to relieve stress             | Threw cake, slapped a guest, changed music        | Less concerned about wedding formality, felt free to explore     |
| **Player 6**   | Moderate anxiety, slight tension, hoped for support              | Changed music, threw cake, slapped a guest        | Felt more relaxed about wedding ideas, enjoyed safe exploration  |


**Test Results**


- **Wedding anxiety eased to some extent**

  High-anxiety players (Player 2, 5) experienced emotional release through rude or playful behaviours (such as throwing cake, slapping guests, and changing the music to something unconventional). They generally reported reduced anxiety, and the feeling that weddings “must be perfect” was weakened.

- **Strong sense of a safe space for expression**

  Players generally felt that the game provided a safe, non-judgmental environment where they could try things they wouldn’t dare to do in real life and boldly express their true emotions.

- **Free exploration enhanced positive emotions**

  Regardless of initial anxiety levels, almost all players experienced a sense of freedom and fun during the game (even low-anxiety players reported that the game made them feel more relaxed).

- **The game inspired new reflections on weddings**

  Several players mentioned in the post-test that weddings don’t necessarily have to be rigid or formal. The experience made them view weddings in a more open and inclusive way.


**Revision Plan**

Based on the playtest findings, we propose several directions for improving and expanding the **Wedding Simulator** to better support player engagement, emotional exploration, and long-term impact. 

- First, we recommend adding more **achievement conditions** that are tailored to different personality types. For example, we could design specific achievements that reward not only playful or disruptive actions, but also thoughtful, kind, or  creative behaviours. This would encourage players with various temperaments—whether shy, bold, humorous, or detail-oriented—to feel recognised for their unique play styles, while motivating them to explore alternative wedding scenarios.

- Additionally, we suggest including an **end-of-game emotional summary or psychological reflection feature**. This could present players with a gentle recap of their key decisions and emotional responses, helping them reflect on how the game   influenced their thoughts or reduced their anxieties about weddings or social interactions. Such feedback could deepen the self-awareness benefits of the game.

- Finally, we see great potential in **developing a multiplayer mode** where players can experience and negotiate wedding behaviours collaboratively. This could simulate real-life social dynamics and provide opportunities to practice  communication, compromise, and emotional expression in a fun, low-pressure environment. Together, these enhancements would further support the game’s mission of helping players explore and embrace the diversity of wedding experiences.
