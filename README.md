
# 🚀 AI Portfolio Project

Welcome to my **AI & Data Science Portfolio Project**
This project is fully **YAML-driven**, allowing you to manage and update all content from a single file.

---

## 📁 Getting Started

### Option 1: Clone the Repository

```bash
git clone https://github.com/Shivanshvyas1729/Portfolio-Hope-it-help-likeit..git
cd Portfolio-Hope-it-help-likeit..
```

---

### Option 2: Download ZIP

* Click **Download ZIP** on GitHub
* Extract the folder
* Open it in terminal

---

## ⚙️ Prerequisites (IMPORTANT)

Make sure your system has the required tools installed.

---

### 🔹 Install Node.js (via Terminal)

#### 🪟 Windows (Winget)

```bash
winget install OpenJS.NodeJS.LTS
```

#### 🪟 Windows (Chocolatey)

```bash
choco install nodejs-lts -y
```

#### 🐧 Linux (Ubuntu/Debian)

```bash
sudo apt update
sudo apt install nodejs npm -y
```

#### 🍎 macOS (Homebrew)

```bash
brew install node
```

---

### 🔹 Verify Installation

```bash
node -v
npm -v
```

---

### 🔹 Fix PATH (if command not found)

If you see:

```
'npm' is not recognized
```

Run (Windows PowerShell):

```bash
setx PATH "%PATH%;C:\Program Files\nodejs\"
```

Restart terminal after this.

---

### 🔹 (Recommended) Install NVM

```bash
winget install CoreyButler.NVMforWindows
nvm install 18
nvm use 18
```

---

### 🔹 Install Vite (Global)

```bash
npm install -g vite
```

Verify:

```bash
vite -v
```

---

## ⚙️ Setup & Run Locally

1️⃣ Open terminal inside project folder

2️⃣ Install dependencies:

```bash
npm install
```

👉 If errors occur:

```bash
npm install --force
```

OR clean install:

```bash
npm cache clean --force
rd /s /q node_modules
del package-lock.json
npm install
```

---

3️⃣ Start development server:

```bash
npm run dev
```

---

## ✏️ Edit Your Portfolio

All your portfolio content is controlled from:

```bash
src/data/portfolio.yaml
```

You can update:

* 👤 Personal Information
* 💼 Projects
* 🧠 Skills
* 🛠 Services
* 📬 Contact Details

No need to edit other files.

---

## 🌐 Deployment (Netlify)

This project is pre-configured for Netlify 🚀

### Steps:

1. Go to Netlify
2. Click **Import Project**
3. Connect your GitHub repository
4. Set publish directory:

```bash
dist
```

5. Click **Deploy**

---

## 🔑 API Configuration (EmailJS Setup)

Enable the contact form using EmailJS.

---

### 1️⃣ Create Account

Sign up on EmailJS

---

### 2️⃣ Create Email Service

* Go to **Email Services**
* Add a new service (Gmail recommended)

---

### 3️⃣ Create Template

* Go to **Email Templates**
* Add fields:

  * Name
  * Email
  * Message

---

### 4️⃣ Add Credentials

Edit:

```bash
src/data/portfolio.yaml
```

Example:

```yaml
emailjs:
  serviceId: "your_service_id"
  templateId: "your_template_id"
  publicKey: "your_public_key"
```

---

## 🤖 Future Updates

* Gemini API integration
* More AI-powered features

⭐ Star the repository to stay updated!

---

## 💡 Notes

* Use `npm install --force` if installation fails
* Ensure Node.js is added to PATH
* Restart terminal after installations

---

## 🔥 Built For

* Developers
* Students
* AI Enthusiasts
