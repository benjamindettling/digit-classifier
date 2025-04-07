# 🧠 Digit Classifier

Draw a digit in your browser and get a real-time prediction using a PyTorch neural network model served via FastAPI.

🔗 **Live Demo:** [digit.benjamindettling.ch](https://digit.benjamindettling.ch)

## 📂 Project Structure
- [`digit-classifier-client`](https://github.com/benjamindettling/digit-classifier-client) – Frontend (React + SCSS)
- [`digit-classifier-server`](https://github.com/benjamindettling/digit-classifier-server) – Backend (FastAPI + PyTorch)

## ✨ Features

- 🎨 Canvas-based digit drawing interface
- 🧠 Digit prediction using a trained PyTorch model
- ⚡ FastAPI backend for real-time inference
- 🔁 Clear separation of frontend and backend
- 🌐 Deployed with Netlify (frontend) and Render (backend)

## 🛠 Tech Stack

**Frontend**
- React + Vite
- SCSS Modules
- Canvas for user input

**Backend**
- FastAPI
- PyTorch (trained model)
- Uvicorn (ASGI server)

## 📸 Screenshots
<p align="center">
  <img src="./screenshot.png" width="400" alt="Digit classifier UI"/>
</p>

## 🧠 What I Learned

- Setting up FastAPI to serve ML models
- Deploying full-stack apps with Netlify & Render
- Building an interactive drawing canvas in React

---

> This project was a fun challenge combining frontend interactivity with machine learning inference.
