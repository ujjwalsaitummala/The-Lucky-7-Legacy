# 🎰 The Lucky 7 Legacy

### Spin the wheel. Discover your next big idea. Build your legacy.

The Lucky 7 Legacy is an interactive coding project discovery platform designed to make choosing your next development project exciting. Instead of scrolling through endless lists of ideas, spin a colorful slot machine and discover what you could build next.

With a collection of 750 project ideas, a futuristic Matrix-inspired aesthetic, and project progress tracking, The Lucky 7 Legacy transforms random inspiration into a practical journey of learning, coding, and creation.

---

## 📌 Table of Contents

- About the Project
- How It Works
- Features
- Requirements
- How to Download
- How to Run on Windows
- How to Launch on GitHub Pages
- How to Install on Different Devices
- Saving and Transferring Progress
- Offline Support
- Privacy and Security
- Troubleshooting
- Future Improvements
- License

---

## 🚀 About the Project

The Lucky 7 Legacy is built for developers, students, coding enthusiasts, and anyone who wants to turn ideas into real projects.

Whether you're learning programming, practising data structures, exploring web development, or building portfolio projects, the platform helps you discover your next challenge.

**The goal is simple: stop wondering what to build and start building.**

## ⚙️ How It Works

### 1. Spin the slot machine
Interact with the colorful slot-machine interface and discover a randomly selected project idea.

### 2. Explore your project
Read the selected idea and use it as the starting point for your next coding challenge.

### 3. Build the project
Choose your technology stack, plan the features, write the code, and turn the idea into a working application.

### 4. Add your GitHub repository
When your project is complete, add its GitHub repository URL where supported by the application. This helps connect your finished work to the idea.

### 5. Track your progress
Mark completed projects so you can keep track of your progress and focus on new challenges.

### 6. Continue discovering
Return to the slot machine and discover another idea. Build consistently, improve your skills, and expand your portfolio.

---

## ✨ Features

- **750 project ideas:** A large collection of ideas to inspire your next build.
- **Interactive slot machine:** Discover project ideas through a fun, random selection experience.
- **Matrix-inspired interface:** A dark, futuristic visual theme with vibrant slot-machine colors.
- **Project tracking:** Keep track of completed projects.
- **GitHub repository links:** Connect your work to its source repository.
- **Browser-based experience:** No traditional desktop installer is required to use the website.
- **Progressive Web App (PWA):** Designed for installation on compatible browsers and devices.
- **Offline support:** The website can cache its app files for offline access after an initial successful online visit.
- **Local progress storage:** Save progress in the browser on the device you use.
- **Cross-platform design:** Use the website on supported desktop and mobile browsers.
- **GitHub Pages compatibility:** Publish the static website without needing a separate web server.

*Note: Automatic cloud synchronization is not included by default. Local progress on one device does not automatically appear on another device.*

---

## 💻 Requirements

### For Windows

- Windows 10 or Windows 11
- A modern browser such as Google Chrome, Microsoft Edge, or Firefox
- Python 3 installed if you want to run the project through a local web server
- Internet access for downloading the files and publishing the website

### For other devices

- Android phone or tablet with a modern browser
- iPhone or iPad with Safari
- macOS or Linux computer with a modern browser

You do not need Node.js or Electron to run the PWA version.

---

## 📥 How to Download

### Option 1: Download the ZIP package

1. Open the project's GitHub repository.
2. Click the green **Code** button.
3. Select **Download ZIP**.
4. Wait for the download to finish.
5. Extract the ZIP file using your device's archive utility.
6. Open the extracted project folder.

Alternatively, download the ZIP package provided by the project creator.

### Option 2: Clone the repository

If Git is installed, open a terminal and run:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with the actual URL of your repository.

Then open the downloaded project directory.

---

## 🖥️ How to Run on Windows

### Method A: Run with Python

This is a convenient method for testing the PWA locally.

**Step 1:** Extract the project ZIP.

**Step 2:** Open the extracted folder.

**Step 3:** Click the File Explorer address bar, type `cmd`, and press Enter.

**Step 4:** Start the local server:

```bash
py -m http.server 8000
```

If the `py` command is unavailable, try:

```bash
python -m http.server 8000
```

**Step 5:** Open your browser and visit:

```text
http://localhost:8000
```

The application should load from your laptop.

Keep the terminal open while using the local server. Press `Ctrl + C` when you want to stop it.

### Method B: Open the HTML file

You can try double-clicking `index.html` to preview the website. However, browser security restrictions may prevent service workers, installation features, or offline caching from working correctly.

For a full PWA experience, use HTTPS hosting or a local development server.

---

## 🌐 How to Publish on GitHub Pages

GitHub Pages allows you to make the website available through a public URL.

### Step 1: Create a repository

1. Sign in to GitHub.
2. Create a new repository.
3. Give it a name, such as `the-lucky-7-legacy`.
4. Choose public visibility if you want the source code to be publicly accessible.

### Step 2: Upload the project files

Upload the contents of the project folder into the repository root. Make sure these files and folders are included:

```text
the-lucky-7-legacy/
├── index.html
├── manifest.webmanifest
├── sw.js
├── .nojekyll
├── README.md
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

Do not upload only the HTML file. The manifest, service worker, and icons are needed for the intended PWA experience.

### Step 3: Enable GitHub Pages

1. Open your repository.
2. Select **Settings**.
3. Open **Pages**.
4. Under the build and deployment settings, select **Deploy from a branch**.
5. Select your publishing branch, usually `main`.
6. Select the `/ (root)` folder.
7. Save your settings.

### Step 4: Open the website

Once deployment finishes, GitHub Pages will provide your website URL. Open that HTTPS URL in a browser and confirm the application loads correctly.

Official guide: https://pages.github.com/

**Important:** A GitHub repository stores the source code. GitHub Pages serves the website. A public repository does not automatically mean the website has been published.

---

## 📱 How to Install on Different Devices

### Android

1. Open your published HTTPS website in Chrome or another supported browser.
2. Open the browser menu.
3. Select **Install app** or **Add to Home screen**, depending on the browser.
4. Confirm the installation if prompted.

### iPhone and iPad

1. Open the published website in Safari.
2. Tap the Share button.
3. Select **Add to Home Screen**.
4. Follow the prompts.

### Windows

1. Open the published website in a supported browser.
2. Look for the install icon in the address bar or open the browser menu.
3. Select the available **Install app** option.

### macOS and Linux

Open the published HTTPS website in a compatible browser and use its installation or shortcut feature when available.

Installation options and offline behavior vary by browser and operating system.

---

## 💾 Saving and Transferring Progress

The application stores progress locally in the browser.

This means:

- Progress is associated with the browser profile and device where it was saved.
- Clearing browser data may erase locally saved progress.
- Using another browser or another device does not automatically transfer progress.
- If the application provides export/import controls, use them to back up and transfer your progress.

For automatic synchronization across multiple devices, the project would need an additional cloud backend and appropriate authentication.

**Recommendation:** Export backups regularly if you have invested significant time in completing projects.

---

## 📴 Offline Support

The PWA includes a service worker intended to cache the application files.

To use the offline functionality:

1. Open the published HTTPS website while connected to the internet.
2. Wait for the application to finish loading.
3. Allow the service worker to install and cache the app files.
4. Reopen the application or test it offline.

Offline functionality is subject to browser storage policies, caching behavior, and the features used by the application. The first visit requires an internet connection.

---

## 🔐 Privacy and Security

The PWA package does not add a cloud backend or analytics service by itself.

Keep these points in mind:

- Local progress is stored in your browser.
- Anyone with access to the same browser profile may be able to view locally saved information.
- Do not store passwords, API keys, access tokens, or other secrets in project notes.
- A public GitHub repository exposes the source code to other people.
- Never commit private credentials or service-role keys to a public repository.
- If cloud synchronization is added later, configure authentication and database access controls correctly.

The application should be tested before being relied on for important data.

---

## 🛠️ Troubleshooting

### The website does not open locally

Make sure the local server is running and visit:

```text
http://localhost:8000
```

Check that the terminal is in the folder containing `index.html`.

### The `py` command is not recognized

Try:

```text
python -m http.server 8000
```

If neither command works, install Python from https://www.python.org/downloads/ and ensure it is available on your system PATH.

### The website works, but installation is unavailable

Use the published HTTPS website, check browser compatibility, and confirm that the manifest and icon files are accessible. Installation support differs by browser.

### Offline mode does not work

Visit the HTTPS website online first, allow caching to complete, and check the browser's site storage settings.

### Progress disappears

Check whether browser data was cleared, a different browser profile was used, or the application was opened from a different origin. Restore an exported backup if one is available.

---

## 🗺️ Future Improvements

Potential future improvements include:

- Secure cloud synchronization across devices
- User accounts and personalized project collections
- Filters by programming language, difficulty, and category
- Search and favorites
- Project descriptions, suggested technologies, and learning resources
- Completion statistics and achievements
- Improved accessibility and reduced-motion options
- A dedicated Android release on Google Play

These are potential improvements, not a claim that all of them are currently implemented.

---

## 📄 License

Before distributing this project, choose and add a license that reflects how you want others to use, modify, and redistribute the source code.

Until a license is added, do not assume that other people have permission to reuse the project merely because the repository is publicly visible.

---

## 🎯 Final Message

The Lucky 7 Legacy is more than a random project picker. It is a way to turn indecision into action, inspiration into code, and completed projects into a growing record of your skills.

**One spin. One idea. One more step toward your legacy.**

🎰 **Spin. Build. Complete. Repeat.**
