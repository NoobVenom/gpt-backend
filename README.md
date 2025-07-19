# ChatGPT Chrome Extension Backend

This is a simple **Node.js + Express** backend used for a Chrome extension. It forwards prompts from the extension to a ChatGPT-compatible API and returns responses securely — **without storing any user data**.

---

## 🚀 Features

- 🔐 No prompt data is stored
- 🌐 CORS-enabled for frontend access (Chrome Extension)
- 📡 Uses OpenAI-compatible API (chatanywhere.tech)
- ⚡ Lightweight and easy to run locally

---

## 📁 File Structure

✅ Step-by-Step Guide
1. Install Node.js
If you haven't already installed Node.js:

Download from: https://nodejs.org/

Install the LTS version.

2. Create a Project Folder (if needed)
If your file isn’t already in a folder, create one and place server.js inside it.

3. Open Terminal or Command Prompt
Navigate to your project folder using the terminal:
Run: cd path/to/your/project

4. Initialize a package.json File

Run: npm init -y
5. Install Required Packages
Your code uses these packages: express, axios, and cors.

Run: npm install express axios cors
6. Run the Server
Now start the server with:

node server.js
