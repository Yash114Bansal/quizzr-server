# Quizzr Backend 

*Quizzr is  an online platform to create and play exciting quizzes made in Node.ts, Sockets.io, Prisma, ensuring smooth performance and adaptability.*

**Check the Website [here](https://quizzr-one.vercel.app/)**

**Check the Frontend Repository [here](https://github.com/yash114bansal/quizzr/)**.

## Table of contents

- [About our project💻](#About-our-project)
- [Tech Stack Used💡](#Tech-Stack-Used)
- [Key Features ✨](#key-features-)
- [Running the server⚙️](#running-the-server-%EF%B8%8F)

# About our project

Welcome to Quizzr, where learning meets excitement! Join live quiz battles, create personalized challenges, and connect with peers in real-time. With adaptive difficulty and interactive features, Quizzr offers an engaging learning experience for users of all levels. Create an account, customize your profile, and dive into the world of quizzes today. Get ready to buzz with excitement on Quizzr!

# Tech Stack Used

![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

## Key Features ✨

- **User Authentication:** Secure Google OAuth Sign In system using Next-Auth.

- **Quizzr Creation:** Create new quizzrs(quizzes) and add questions to it.

- **Host a Quizzr:** Host a new Game Session for the quiz.

- **Real-time Updates:** Get Realtime player and presenter interations.

- **Player Management:** Manage players in a game through presenter, system to kick unwanted players.

- **Leaderboard:** See the leaderboard after each question round.

---

## RUNNING THE SERVER ⚙️

*Get started on the local machine*

1. Clone the repository: 
   ```CMD
   git clone https://github.com/yash114bansal/quizzr-server.git
   ```
*To run the server, you need to have NodeJS installed on your machine. If you don't have it installed, you can follow the instructions [here](https://nodejs.org/en//) to install it.*

2. Setup .env file in base directory:
   ```
   PORT = 8080
   DATABASE_URL = ''
   ```

3. Running with local machine

   - Install dependencies

      ```CMD
      npm install
      ```
   - Run the server on localhost:
      ```CMD
      npm run dev
      ```
   ---
    
*You can access the endpoints from your web browser following this url:*
   ```url
   http://localhost:[PORT]
   ```
