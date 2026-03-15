# drskc9.github.io

A minimalist **developer dashboard homepage** designed to act as a central launcher for personal apps and projects hosted on GitHub.

This project is built as a **single self-contained `index.html` file** that works instantly with **GitHub Pages**. The page provides a clean black-and-white developer interface with a live clock, monthly calendar, and quick access cards for different applications.

---

## Overview

This dashboard functions as a **personal command center** for navigating projects, tools, and subdirectory applications hosted in GitHub repositories.

The design is inspired by launcher dashboards such as Heimdall and Homer, but implemented as a **lightweight static page** without any external dependencies.

Everything runs directly in the browser using **pure HTML, CSS, and JavaScript**.

---

## Features

### Minimal Developer UI

* Clean **black and white theme**
* Monospace system fonts for a terminal-like aesthetic
* Responsive layout for desktop and mobile
* Smooth hover interactions for app cards

### Live Clock

* Displays the current time
* Updates every second
* Automatically adapts to the visitor's **local timezone**

### Monthly Calendar

* Dynamically generates the **current month calendar**
* Highlights the **current day**
* Built entirely with JavaScript

### App Launcher

* Grid of launcher cards linking to apps or repositories
* Designed for quick access to:

  * tools
  * projects
  * dashboards
  * subdirectory apps

Links can be easily edited inside the HTML file.

### Keyboard Command Palette

Inspired by developer tools like VS Code.

Keyboard controls:

* `/` → Open command palette
* Type → Filter available apps
* `Enter` → Open selected app
* `Esc` → Close palette

This allows fast navigation using only the keyboard.

---

## Design Philosophy

This project follows a **self-contained architecture**:

* No CDNs
* No external fonts
* No frameworks
* No external scripts

All styles and scripts are embedded directly inside `index.html`.

Benefits:

* Works offline
* Loads instantly
* No external dependencies
* Perfect for GitHub Pages hosting

---

## File Structure

```
drskc9.github.io
│
└── index.html
```

The entire dashboard is implemented in this single file.

---

## Customization

To add or edit apps:

1. Open `index.html`
2. Locate the **launcher card section**
3. Update the link URLs

Example:

```
<a href="/app1/">App 1</a>
<a href="/app2/">App 2</a>
<a href="/tool-dashboard/">Tool Dashboard</a>
```

Changes will automatically appear on the dashboard.

---

 License

This project is free to modify and use for personal dashboards.
