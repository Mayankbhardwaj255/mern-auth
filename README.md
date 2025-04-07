# 🔐 MERN Authentication & Authorization – No 3rd Party Auth

Welcome to the **mern-auth** repository!\
This project showcases a complete implementation of authentication and authorization using the **MERN stack** – **MongoDB, Express, React, and Node.js** – all without relying on third-party providers like Firebase or Auth0.

Everything is built from scratch using **jsonwebtoken** for secure token-based authentication.

---

## 🔧 Features

- 🚫 No third-party auth providers
- 🔐 Authentication & Authorization using `jsonwebtoken`
- 📩 Email templates powered by **Mailtrap** (configurable for providers like Resend)
- 📁 Clean folder structure with separate **backend** and **frontend**
- ✅ Environment-variable support for Mailtrap integration

---

## 📁 Folder Structure

```
mern-auth/
├── backend/       # Node.js, Express, MongoDB, JWT logic
└── frontend/      # ReactJS client
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Mayankbhardwaj255/mern-auth
cd mern-auth
```

### 2. Install Dependencies

In both folders (`backend` and `frontend`), run:

```bash
npm install
```

### 3. Configure Mailtrap

- Create a free account on [Mailtrap](https://mailtrap.io/)
- Grab your **API Token** and **SMTP credentials**
- Add them to your `.env` file in the backend folder:

```env
MAILTRAP_HOST=<your-mailtrap-host>
MAILTRAP_PORT=<your-mailtrap-port>
MAILTRAP_USER=<your-mailtrap-username>
MAILTRAP_PASS=<your-mailtrap-password>
```

You can also switch to other providers like **Resend** by updating the email config.

### 4. Run the App

From both folders:

```bash
npm run dev
```

> Make sure MongoDB is running locally or update the Mongo URI in the `.env` file.

---

## 💡 Notes

- Frontend uses modern React practices
- Backend is secured with proper token validation
- Mailtrap handles email previews safely in development

---

## 📄 License

This project is licensed under the **MIT License**.

---

**Built with MERN. Secured with JWT. Designed for Developers. 🚀**

made with ❤️ by Mayank
