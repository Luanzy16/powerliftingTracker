# 🏋️‍♂️ PowerLifting Tracker Web

Aplicación web gratuita para registrar tus entrenamientos de powerlifting, visualizar tu progreso, y recibir análisis automatizados (como regresión lineal para estimar 1RM). Esta versión usa un frontend en React y un backend inteligente en **n8n**, con almacenamiento en **Google Sheets**.

---

## 🚀 Características principales

- 📋 Registro de datos: ejercicio, peso, repeticiones
- 📊 Visualización gráfica del progreso
- 🤖 Análisis automatizado con regresión lineal vía n8n
- ☁️ Datos almacenados en Google Sheets
- 🔒 (Opcional) Autenticación con Firebase

---

## 🧱 Stack Tecnológico

| Módulo                | Tecnología         | Gratuito |
|----------------------|--------------------|----------|
| Frontend             | React + Vite       | ✅ |
| Gráficas             | Chart.js           | ✅ |
| Backend              | Webhook de n8n     | ✅ |
| Base de datos        | Google Sheets      | ✅ |
| Hosting web          | Vercel             | ✅ |
| Autenticación (opcional) | Firebase Auth     | ✅ |

---

## 📦 Estructura del Proyecto

```plaintext
powerlifting-web/
├── public/
│   └── index.html
├── src/
│   ├── App.jsx
│   ├── components/
│   │   ├── Form.jsx
│   │   └── Chart.jsx
│   └── utils/
│       └── api.js
├── .env (para URL de webhook)
├── package.json
└── README.md
