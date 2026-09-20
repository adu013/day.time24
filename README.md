# day.time24
A simple lightweight HTML page to quickly check color-coded days of the week.

## ✨ Features
* **Visual Anchors:** Displays each day of the week (Sunday through Saturday) with distinct background colors.
* **Zero Configuration:** No databases, local servers, or command lines required.
* **Instant Load:** Built using pure HTML, CSS, and basic JavaScript.

## ⚙️ Installation & Usage

You do not need to install anything or run any setup terminal commands.

1. **Download** or clone this repository to your computer.
2. Open the project folder.
3. **Double-click** the `index.html` file to launch the dashboard instantly in your default web browser.

## 📁 File Structure
* `index.html` - The core structure and entry point of the application.

```text
day.time24/
├── src/
│   ├── how-to-customize/
│   │   └── index.html
│   └── index.html  # The entry point of the application.
├── .gitignore
├── colors.txt
├── LICENSE
└── README.md
```

## 🎨 Customization

`day.time24.cc` allows you to entirely personalize your 7-day color theme by syncing with your own GitHub profile. Instead of manually editing source code, you can manage your colors directly through version control!

### How to Create Your Custom Theme:

1. **Fork this repository:** Click the **Fork** button in the top right corner of this page to create a copy under your personal GitHub account.
2. **Edit your colors:** Open the `colors.txt` file inside *your forked repository*. Click the edit pencil icon and change the 7 lines to any hex color codes you prefer. Save and commit (in the `main` branch) your changes.
3. **Sync to the website:** Go to `day.time24.cc`, click **Customize**, enter your **GitHub Username**, and hit **Save & Sync**. Your browser will securely download and save your palette!

### Color File Mapping Reference:
The `colors.txt` file reads hex codes in sequential order starting from Sunday down to Saturday:

* **Line 1:** Sunday Color (Default: `#3c4142`)
* **Line 2:** Monday Color (Default: `#ffc800`)
* **Line 3:** Tuesday Color (Default: `#273e06`)
* **Line 4:** Wednesday Color (Default: `#a94064`)
* **Line 5:** Thursday Color (Default: `#000042`)
* **Line 6:** Friday Color (Default: `#c30f16`)
* **Line 7:** Saturday Color (Default: `#7b3f00`)

> ⚠️ **Note:** Ensure your forked repository remains **Public** and is named exactly `day.time24` so the website API engine can successfully read your file.


## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
