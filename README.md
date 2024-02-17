<img src="https://github.com/MoarTube/MoarTube-Client/assets/26640616/539be602-3608-428d-b6d6-34aec9b4a05d" alt="logo" width="200"/>

# MoarTube-Client
A repository containing the client software for managing your [MoarTube Node](https://github.com/MoarTube/MoarTube-Node). The client software is a cross-platform terminal-based Node.js Express application that makes managing your node's videos and live streams as simple as reading this sentence.

# How to Get Started
Welcome to the MoarTube Client setup guide! This document will guide you through the different setup methods to get your MoarTube Client up and running. Don't worry; MoarTube is so easy to set up and use, you'll be done in minutes. When ready, head over to [MoarTube Node](https://github.com/MoarTube/MoarTube-Node) if you haven't yet.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation Methods](#installation-methods)
  - [npm](#npm)
  - [git](#git)
- [Next Steps](#next-steps)
  - [Open the MoarTube Client](#open-the-moartube-client)
  - [Default Login Credentials](#default-login-credentials)
  - [Get MoarTube Node](#get-moartube-node)

## Features
 - Cross platform support for Windows/macOS/Linux
 - Video on demand (VoD) and HLS live streaming
 - Admin panel for managing videos and live streams
 - **HLS** *(H.264, AAC)*, **MP4** *(H.264, AAC)*, **WEBM** *(VP9, Opus)*, **OGV** *(VP8, Opus)* container formats
 - Transcode static MP4/WEBM video to HLS/MP4/WEBM/OGV
 - Transcode RTMP stream ([such as from OBS](https://moartu.be/nodes/chris_moartube_node/videos/e9p_nivxkX7)) to HLS live stream
 - Video output resolutions: 2160p, 1440p, 1080p, 720p, 480p, 360p, 240p
 - No server-side encoding; client-side only
 - [HTTPS/WSS](https://moartu.be/nodes/chris_moartube_node/videos/L9qCCrsMtJl) capabilities
 - [GPU acceleration](https://moartu.be/nodes/chris_moartube_node/videos/X3xL5oPTJaz) for Nvidia and AMD (Windows only)
 - Different video player modes: streamer, theater, fullscreen
 - Dark mode option and browser appearance configuration recognition
 - Anonymous video comments section and live stream chat
 - Reports section for comments and videos
 - Comment monitoring overview with moderation functionality
 - Run your node in the cloud or on your home WiFi
 - Can run on a Raspberry Pi Zero 2 W
 - Publicize your node's content on [MoarTube](http://www.moartube.com) or run your node privately
 - [Dual box compatible](https://moartu.be/nodes/chris_moartube_node/videos/f7w9spnInuN); broadcast an RTMP stream with software such as OBS from a primary system over a network (WAN or LAN) to a secondary system running the MoarTube Client, separating stream broadcasting from stream processing. This is achieved without any special plugins, such as NDI.
 - [Cloudflare Turnstile](https://moartu.be/nodes/chris_moartube_node/videos/gQcsrSmsmrY); next-generation bot detection and human verification without the annoyance of captcha.
 - [Cloudflare one-click integration](https://moartu.be/nodes/chris_moartube_node/videos/9aP6aY4DYeH); easily integrate your node into the [Cloudflare Network](https://www.cloudflare.com/network/), allowing for global media delivery capabilities of your videos and live streams that rivals major platforms, all from a single node. Features automated caching strategy configuration and automated cache management, and of course the best security from the world's leading CDN.

![image](https://github.com/MoarTube/MoarTube-Client/assets/26640616/0d8ac95f-f68b-4e36-849e-28139b45ce50)

![image](https://github.com/MoarTube/MoarTube-Client/assets/26640616/918aa074-b6e2-49f1-8d14-5c2ed1bcd582)

![image](https://github.com/MoarTube/MoarTube-Client/assets/26640616/068ec86b-a3d8-4285-9b64-4b71f64cce41)

## Prerequisites

Choose any one of the following to set up your client.

### npm
If you're using npm to install the software, make sure that [Node.js and npm](https://nodejs.org/en) is installed on your machine.

### git
You can clone the repo, but make sure that [Node.js and npm](https://nodejs.org/en) is installed on your machine.

## Installation Methods

### [npm](https://www.npmjs.com/settings/moartube/packages)

```bash
npm i @moartube/moartube-client
```

open a terminal in the installation directory and run the client:

```bash
node node_modules/@moartube/moartube-client/moartube-client.js
```

### [git](https://github.com/MoarTube/MoarTube-Node)

```bash
git clone https://github.com/MoarTube/MoarTube-Client
```

open a terminal in the installed directory and install dependencies:

```bash
npm install
```
Run the client:

```bash
node moartube-client.js
```

## Next Steps

### Open the MoarTube Client

Open a web browser at [localhost:8080](http://localhost:8080) to view the MoarTube Client user interface.

### Default Login Credentials

The default login credentials for your node are below. Be sure to change these upon logging in.

**username**: admin<br/>**password**: admin

### Get MoarTube Node

Once you've got your client up and running, it's time to get the [MoarTube Node](https://github.com/MoarTube/MoarTube-Node).
