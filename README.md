# 6 or 7 Hand Detector

This small web app uses your **camera** and **Google’s Mediapipe Hands** AI library to detect whether you show your **left hand** or **right hand**:

- 👋 Left hand → shows **6**  
- ✋ Right hand → shows **7**  
- ❓ No hand → shows **?**

---

## 🚀 1. Fork or Download

You can try the project in **three different ways** — pick whichever is easiest for you:

### 🅰️ Option A – Run it Offline (Quickest)
1. Download the project ZIP file from your teacher or GitHub.  
2. Unzip it (for example: `Downloads/demo`).
3. Double-click the file named `index.html`.
4. Your browser should open the app. Click **Start** and allow **camera access**.

✅ Works even without GitHub!

---

### 🅱️ Option B – Use VS Code + Live Server (for coding locally)
1. Install **[Visual Studio Code](https://code.visualstudio.com/)** if you don’t have it.
2. Open VS Code → click **File → Open Folder...** → choose the project folder.
3. Install the **Live Server** extension in VS Code (search for it in the Extensions panel).
4. Right-click `index.html` → choose **“Open with Live Server.”**
5. Allow camera access when prompted.

You can now **edit the HTML, CSS, or JS** and instantly see your changes!

---

### 🅾️ Option C – Fork & Code on GitHub (for online learners)
If you already have a **GitHub account**, this is the best way to share your project online.

1. Go to the original GitHub repository link (your teacher will share it).  
2. Click the **Fork** button (top-right corner).  
   → This makes your own copy under your GitHub account.  
3. Open your new repository (your version).  
4. Click **Add file → Upload files**, or **Edit this file** to start coding directly in your browser.  
5. When done, scroll down and click **Commit changes** to save.  
6. Enable GitHub Pages to make it public:
   - Go to your repo’s **Settings → Pages**
   - Under “Branch,” select `main` (or `master`) → click **Save**
7. Wait about 30–60 seconds, then refresh. You’ll see a link like: https://yourusername.github.io/6-or-7-detector/
8. Open that link and click **Start** to test your app online 🎉

🧩 You can now **edit it online anytime** from your GitHub editor or even connect it to **Replit** or **Codespaces** for live coding.

---

## ⚙️ 2. Troubleshooting

| Problem | Solution |
|----------|-----------|
| ❌ Camera not showing | Click “Allow” when your browser asks for camera access. |
| ⚠️ Blank screen | Try refreshing or using **Google Chrome**. |
| 🖥 Doesn’t work on phone | Use Chrome or Safari (not inside TikTok, Instagram, or Discord browsers). |
| 🔒 Permission blocked | Click the 🔒 lock icon beside the URL → enable “Camera.” |

---

## 🧠 3. How It Works

- This project uses **[Google Mediapipe Hands](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker)**.  
- Mediapipe uses **AI and computer vision** to detect hand landmarks in real-time (like fingertips and palm position).  
- It recognizes if it’s your **Left** or **Right** hand, then updates the big image (6, 7, or ?).  
- Everything happens **locally in your browser** — no video is uploaded anywhere.

---

## 💡 4. Try These Fun Add-Ons

Here are mini challenges to make it your own:

- 🔊 Play a sound when a hand is detected.  
- 🌈 Change background color for left/right hand.  
- 🧮 Add a counter to show how many times each hand appears.  
- ✏️ Add your name or logo in the top-left corner.  

---

## 🔗 5. Learning Links

- 🤖 Mediapipe Hands Docs → [developers.google.com/mediapipe](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker)  
- 🧠 Mediapipe GitHub → [github.com/google/mediapipe](https://github.com/google/mediapipe)  
- 🎥 getUserMedia API → [developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia)  
- 🧰 HTML Video & Camera → [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/API/HTMLVideoElement)  

