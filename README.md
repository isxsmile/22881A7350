# 🔗 SHORTURL–URL Shortener

**SHORTURL** is a sleek, client-side URL shortener built with **React** and **Next.js**, designed to convert long links into shareable shortcodes, track analytics, and offer a smooth, interactive UI—all without a backend!

---

## 📘 Project Overview

**SHORTURL** transforms complex URLs into clean, customized short links while offering an intuitive interface, real-time analytics, and a built-in chatbot assistant. It's designed with modern frontend practices, focusing on user experience, speed, and local data persistence.

---

## 🌟 Features

| Feature | Description |
|--------|-------------|
| 🔗 **URL Shortening** | Converts long URLs into unique, custom shortcodes |
| ✍️ **Custom Code Support** | Users can define their own shortcodes and set expiry times |
| ⏳ **Expiry Handling** | Links expire after 30 minutes by default, customizable by the user |
| 📈 **Analytics Page** | Tracks click counts and displays real-time stats |
| 🤖 **Chatbot Assistant** | Integrated AI chatbot for helping users with FAQs and navigation |
| 🌙 **Light/Dark Toggle** | Responsive theme switching with persistence |
| 🔐 **Logging Middleware** | Captures logs and sends them securely to an external server |
| 🧠 **Pure Client-Side Logic** | Entirely frontend-powered using `localStorage` and `fetch` |
| 💬 **Dynamic Notifications** | Toast alerts and messages for instant user feedback |


*Desktop View*

---![PHOTO-2025-07-28-12-11-12](https://github.com/user-attachments/assets/f48eed29-321f-407b-b4d9-344b8c287647)

*mobile view*
<img width="1081" height="1280" alt="image" src="https://github.com/user-attachments/assets/4b204194-cfb9-457b-9acd-f7f766e4660a" />


## 🔐 Logging System

**SHORTURL** uses a robust logging utility (`logger.ts`) to track every interaction, helping with debugging and external evaluation.

### 🔍 Log Structure

- **Component Source** – Where the event originated
- **Log Type** – `info`, `warn`, `error`
- **Timestamp** – Time of occurrence
- **Message** – Custom debug/informational content

### 📤 Log Transmission

Logs are stored locally and also sent to the evaluation service:

POST http://20.244.56.144/evaluation-service/logs

🧩 Summary

SHORTURL demonstrates the power of frontend-only architecture, combining utility and UX into one polished tool. Whether you're shortening links or experimenting with AI chat and analytics, this app offers a lightweight, fast, and fully extensible solution.

Contributions, feedback, and pull requests are welcome!
