# 🍔 Burger

## A responsive landing page template designed to practice modern UI/UX implementation using CSS styling.

## ✨ Features

- **Responsive Design**: Fully optimized for mobile, tablet, and desktop.
- **Modern Layouts**: Built using Flexbox and CSS Grid.
- **Asset Management**: Optimization of images and custom fonts.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3.
- **Design Source**: Static UI Template.
- **Containerization**: Docker + Apache HTTP Server 2.4

---

## ⚙️ Prerequisites

- **Un serveur web (apache ou nginx)**

---

## 📦 Installation

**1. Clone the repository**

```bash
git clone https://github.com/LuzRivera154/burger.git
cd burger
```

**2. Build the Docker image**

```bash
docker build -t burger .
```

---

## Run

**1. Start the container**

```bash
docker run -p 8080:80 --name burger burger
```

**2. Open your browser and go to:**

http://localhost:8080

---

## ⏹️ Stop the app

```bash
docker stop burger
```

## 🗑️ Remove the container

```bash
docker rm burger
```

---
