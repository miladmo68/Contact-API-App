<div align="center">

# 📇 Contact API App

A full-stack contact manager with a React frontend and a Spring Boot and PostgreSQL API.

<a href="https://github.com/miladmo68/Contact-API-App"><img src="https://img.shields.io/badge/Source-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source code"></a>
<a href="https://miladweb.com"><img src="https://img.shields.io/badge/Portfolio-miladweb.com-1E3A8A?style=for-the-badge&logo=aboutdotme&logoColor=white" alt="Portfolio"></a>

</div>

<p align="center">
  <img src="./.github/preview.jpg" alt="Contact API App screenshot" width="100%" />
</p>

## ✨ Features

- Create, view, update and delete contacts
- Photo upload per contact
- Spring Boot REST API with PostgreSQL

## 🛠️ Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![Create React App](https://img.shields.io/badge/Create%20React%20App-09D3AC?style=for-the-badge&logo=createreactapp&logoColor=white) ![React Router](https://img.shields.io/badge/React%20Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white) ![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)

> [!NOTE]
> This project needs its own backend, database or API keys, so it runs locally rather than as a static demo.

## 🚀 Getting Started

**Prerequisites:** [Node.js](https://nodejs.org/) 18 or newer · Java 17+ (the Maven wrapper is included)

**Clone**

```bash
git clone https://github.com/miladmo68/Contact-API-App.git
cd Contact-API-App
```

**Backend (contactapi-back)**

```bash
cd contactapi-back
./mvnw spring-boot:run
```

**contactapp-front**

```bash
cd contactapp-front
npm install
npm start
```

## 📡 API Endpoints

| Method | Path |
| --- | --- |
| `POST` | `/contacts` |
| `GET` | `/contacts` |
| `GET` | `/contacts/{id}` |
| `PUT` | `/contacts/photo` |

## 📁 Project Structure

```
Contact-API-App/
├── contactapi-back/
└── contactapp-front/
```

## 👤 Author

**Milad Mohammadi** — Frontend-Focused Full-Stack Developer, Toronto 🇨🇦

[![Website](https://img.shields.io/badge/Website-miladweb.com-FF6A00?style=flat-square&logo=googlechrome&logoColor=white)](https://miladweb.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-miladmo68-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miladmo68/)
[![GitHub](https://img.shields.io/badge/GitHub-miladmo68-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/miladmo68)

<p align="center"><sub>If you like this project, consider giving it a ⭐</sub></p>
