# Magic Snapchat Memory Downloader 🪄📸

A powerful, private, and fast web tool to batch download all your Snapchat memories at once.

**Magic Snapchat Downloader** runs 100% in your web browser. It uses a smart "Worker Pool" system to download multiple memories in parallel, directly from Snapchat to your hard drive, without ever sending data to a third-party server.

## 🚀 Key Features

- **⚡ Parallel Downloads:** Download 1 to 20 files simultaneously. Maximize your bandwidth and save hours of waiting.
- **🛡️ 100% Private & Local:** No backend server. No API keys. Your data never leaves your device.
- **🧠 Smart Resume:** Stopped halfway? The tool calculates exactly which index to resume from so you never miss a file.
- **📅 Chronological Naming:** Files are automatically renamed by date (e.g., `0001_2023-01-01_14-30_snap.mp4`) for perfect sorting.
- **🚨 Connection Guard:** Automatically detects if your CORS extension disconnects and pauses to prevent errors.

## 🛠️ Prerequisites

Because this tool runs in the browser but fetches data from Snapchat's servers, you **must** bypass browser security (CORS) restrictions.

1. **Install the "Allow CORS" Extension:**
   - [Chrome/Edge Store Link](https://chromewebstore.google.com/detail/allow-cors-access-control/lhobafahddgcelffkeicbaginigeejlf)
   - [Firefox Add-on Link](https://addons.mozilla.org/en-US/firefox/addon/access-control-allow-origin/)
2. **Toggle it ON** (The icon should turn colored/active) before opening the tool.

## 📖 How to Use

1. **Request Your Data:** Go to Snapchat Settings -> "My Data" and request your JSON data. Wait for the email download link.
2. **Launch:** Open the [Web App](https://bit.ly/snap-memories-downloader) (or `index.html` if running locally).
3. **Verify:** Click the "Verify Extension" button to ensure you are ready.
4. **Load Data:** Select the `memories_history.json` file from your unzipped Snapchat export.
5. **Configure:**
   - **Start Index:** Leave at 0 for a fresh start.
   - **Parallel Downloads:** Default is 5. Increase to 10-20 if you have fast internet.
6. **Start:** Click **START DOWNLOAD**.

### ⚠️ Critical Step: "Allow Multiple Downloads"
When you start, your browser will try to save the first batch of files. It will show a popup asking for permission to **"Download multiple files"**.
**You MUST click "Allow"**, otherwise the browser will block every file after the first one.

## 💡 Pro Tips

- **Organize First:** Before starting, go to your Browser Settings -> Downloads and **change the default download folder** to a new empty folder (e.g., "Snapchat Backup"). This prevents your main Downloads folder from getting flooded with thousands of files.
- **Disable "Ask where to save":** Ensure your browser settings are NOT set to "Ask where to save each file", or you will get a popup window for every single memory!

## 🔒 Privacy Policy

This project is open source and serverless.
- **No Analytics:** We do not track your usage.
- **No Data Storage:** We do not see, store, or touch your `json` file or your memories.
- **Direct Connection:** The tool creates a direct link between your browser and Snapchat's media servers.

## 📝 Disclaimer
This tool is for personal backup purposes only. Not affiliated with Snap Inc. Use responsibly.
