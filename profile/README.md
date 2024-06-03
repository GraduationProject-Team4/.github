

# Pairing

<img width="1920" alt="23" src="https://github.com/GraduationProject-Team4/.github/assets/80394340/821fe107-c47a-41dc-8ba5-bc24f84f4abb">

---

## Members

|[이유진](https://github.com/youz2me)|[서은수](https://github.com/EunsuSeo01)|[남윤주](https://github.com/SouthYunnnn)|[이윤서](https://github.com/yseo14)|[노현지](https://github.com/hyeonjiroh)|
|:-----:|:-----:|:-----:|:-----:|:-----:|
<img width="200px" src="https://avatars.githubusercontent.com/u/80394340?v=4"/> | <img width="200px" src="https://avatars.githubusercontent.com/u/87434861?v=4"/> | <img width="200px" src="https://avatars.githubusercontent.com/u/98511311?v=4"/> | <img width="200px" src="https://avatars.githubusercontent.com/u/101577272?v=4"/> | <img width="200px" src="https://avatars.githubusercontent.com/u/108173863?v=4"/> |
|iOS|iOS|AI|Server|AI|

## About Pairing
**Pairing** project provides multilateral voice recognition and summary capabilities using ChatGPT, as well as current environmental analysis and risk notification through background sound recording. This aims to help deaf people with life assistance and improve their daily discomfort.

#### 💻🤖 [Repository AI](https://github.com/GraduationProject-Team4/Pairing-AI)
#### 💻🖥️ [Repository Server](https://github.com/GraduationProject-Team4/Pairing-Server)
#### 📱🍎 [Repository iOS](https://github.com/GraduationProject-Team4/Pairing-iOS)

The core technology of this project is the Multilateral Dialogue **Summary through ChatGPT**, environmental sound separation using **Demucs library**, and single sound analysis using **UrbanSound8K library**.

---

## Core Technologies: AI

#### - Classification
Use the Demucs library to classify voice mixed with multiple voices as a single sound.

#### - Analysis
The AI model trained using the AlbanSound8K dataset analyzes a single classified sound and notifies the user which sound belongs to the environmental sound.

---

## Core Technologies: Server

#### - Communication API

We developed a communication API to send the results of the AI AI model to iOS.


---

## Core Technologies: iOS

#### - Multilateral Dialogue Summary:
**Multilateral Conversation Summarization using ChatGPT API** ensures that the blind can identify the conversation at the risk of not being able to read all the mouths in the multilateral conversation and not being able to understand all the conversation.

#### - AVFoundation:
It uses **AVFoundation**, an iOS built-in library, to record a user's voice in the best quality and convert it into a voice file. It is sent through the server to an AI model for separation and analysis.

---

## Tech Stack

| Technology |  |
| ---- | ---- |
| iOS | <img src="https://img.shields.io/badge/swift-F05138?style=for-the-badge&logo=swift&logoColor=white"> |
| Backend | <img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white"> |
| Model | <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> |
| Others | <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> <img alt="Notion" src="https://img.shields.io/badge/Notion-181717.svg?&style=for-the-badge&logo=Notion&logoColor=white"/> <img alt="Figma" src="https://img.shields.io/badge/Figma-181717.svg?&style=for-the-badge&logo=Figma&logoColor=white"/> |

---


