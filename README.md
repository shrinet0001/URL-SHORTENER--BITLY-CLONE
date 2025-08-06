# URL-SHORTENER--BITLY-CLONE
A full-stack URL shortening service that allows users to generate short links for long URLs with redirection support. Built with *Java Spring Boot* on the backend and *React.js* on the frontend, styled using *Tailwind CSS, and containerized using **Docker* for smooth deployment.

## 🚀 Features

- 🔗 *URL Shortening*  
  Converts long URLs into short, shareable links with unique identifiers.

- 🌐 *Redirection Support*  
  Automatically redirects short URLs to the original destination.

- ⚙ *RESTful Backend API*  
  Built with Spring Boot, supports POST and GET requests for URL operations.

- 🎨 *Modern Frontend*  
  React.js + Tailwind CSS for responsive and clean user interface.

- 🐳 *Dockerized Backend*  
  Backend containerized using Docker for consistent and portable deployment.

- ⚡ *Vite-Powered Frontend Build*  
  Uses Vite for lightning-fast frontend builds and development workflow.

## 🛠 Tech Stack

| Frontend        | Backend            | Other Tools       |
|-----------------|--------------------|--------------------|
| React.js        | Java Spring Boot   | Docker             |
| Tailwind CSS    | Maven              | ESLint             |
| Vite            | RESTful API Design | Environment Config |

## 📂 Project Structure
rl-shortener-project/
├── url-shortener-react/ # React frontend
│ ├── src/
│ ├── tailwind.config.js
│ └── vite.config.js
│
├── url-shortener-sb/ # Spring Boot backend
│ ├── src/
│ ├── pom.xml
│ └── Dockerfile
