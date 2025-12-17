# SnapSaver Local 📸

A private, client-side web tool to batch download your Snapchat memories.

**SnapSaver Local** runs entirely in your web browser. It does not use a backend server, ensuring your data and memories never leave your computer.

## 🚀 Features
- **100% Local & Private:** No data upload. Your memories go directly from Snapchat to your hard drive.
- **Batch Downloading:** Automates the process of clicking "download" for thousands of memories.
- **Smart Naming:** Renames files chronologically (e.g., `0001_2023-01-01_snap.mp4`) so they stay sorted.
- **Resume Capability:** Pick up where you left off by entering a start index.

## 🛠️ Prerequisites
Because this tool runs in the browser but connects to Snapchat's servers, you must bypass browser security (CORS) restrictions.

1. **Install the "Allow CORS" Extension:**
   - [Chrome/Edge Store Link](https://chromewebstore.google.com/detail/allow-cors-access-control/lhobafahddgcelffkeicbaginigeejlf)
   - [Firefox Add-on Link](https://addons.mozilla.org/en-US/firefox/addon/access-control-allow-origin/)
2. **Toggle it ON** (The icon should turn colored/active).

## 📖 How to Use

1. **Request Your Data:** Go to Snapchat Settings -> "My Data" and request your JSON data. Wait for the email.
2. **Open SnapSaver:** Open the `index.html` file in your browser (or the hosted link).
3. **Verify Extension:** Click "Verify Extension" to ensure CORS is enabled.
4. **Load Data:** Select the `memories_history.json` file from your Snapchat export.
5. **Start Download:** Click Start.

### ⚠️ Important: Allowing Multiple Downloads
When you click start, your browser will try to save the first file. It will then show a popup near the address bar asking for permission to download multiple files.

**You must click "Allow"**, otherwise the process will stop after the first file.

## 🔒 Privacy Policy
This project is open source and serverless.
- **No Analytics:** We do not track your usage.
- **No Data Storage:** We do not see, store, or touch your `json` file or your memories.
- **Direct Connection:** The tool creates a direct link between your browser and Snapchat's media servers.

## 📝 Disclaimer
This tool is for personal backup purposes only. Not affiliated with Snap Inc.
