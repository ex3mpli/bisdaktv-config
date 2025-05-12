# BISDAKTV Config (Hosted with Cloudflare Workers)

This repo hosts the `config.json` file used for BISDAKTV.

## 📂 Files
- `config.json` – The main configuration for categories, channels, and DRM.
- `worker.js` – Cloudflare Worker script that serves the JSON publicly.

## 🌐 How to Access
Once deployed using [Cloudflare Workers](https://workers.cloudflare.com/), your file will be available at:

## 🚀 How It Works
The Cloudflare Worker fetches the latest `config.json` from GitHub and returns it as JSON with the correct `Content-Type` headers.

## ✏️ Editing Config
Edit `config.json` in the GitHub repo and it will automatically update on the Worker URL after a few seconds.
