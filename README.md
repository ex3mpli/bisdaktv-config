# BISDAKTV Config (Hosted with Cloudflare Workers)

This repo hosts the `config.json` file for BISDAKTV, served through a secure Cloudflare Worker.

## 📂 Files
- `config.json`: Main channel and category list for OTT Navigator.
- `worker.js`: Cloudflare Worker script that restricts access to OTT Navigator only.

## 🌐 Public Access

Once deployed, your Worker will be available at:


This URL is only accessible via OTT Navigator.

## 🛡 Access Control

- Browser access will be denied (403 error).
- OTT Navigator access is allowed (detected via User-Agent header).

## 🛠 Usage

1. Edit the `config.json` with your data.
2. Deploy `worker.js` in your Cloudflare Worker.
3. Use the Worker URL inside OTT Navigator.

## ✏️ GitHub Repo

- GitHub: [https://github.com/ex3mpli/bisdaktv-config](https://github.com/ex3mpli/bisdaktv-config)
