
# 📖 [The Great Gatsby] — Bilingual Reader with Audio

**[Author]** · English / 中文 side by side · section-by-section audio in both languages

*Words That Think · 品词坊 · 以词启思*

**▶ Open the reader:**[https://dwang055.github.io/great-gatsby-bilingual-reader/]

No sign-up, no download and no app needed. It works in any modern browser on a phone, tablet or computer.

---

## What you can do

| Feature | How to use it |
|---|---|
| **Read in two languages** | English on the left, 中文 on the right. On a phone, switch with the **🇬🇧 English / 🇨🇳 中文** buttons. |
| **Listen** | Press play on the 🎵 bar. Use **EN / 中文** to switch the language of the recording. |
| **Choose how to read** | **Mode:** *Sections* (one section at a time), *Full Chapter*, or *Pages*. |
| **Simplified text** | **Switch to Simplified** gives an easier version of the English and the 中文. |
| **Learn vocabulary** | Tap a highlighted word to see its meaning, then 🔊 to hear it. |
| **Test yourself** | Short true/false questions with explanations appear after each section or chapter. |
| **Highlight and take notes** | Select any text, then choose **🖍 Highlight** or **📝 Note**. Open **📒 My Notes** to see them all. |
| **Make it comfortable** | **A− / A+** changes the text size. **🌙 Dark Mode** is easier on the eyes at night. |

## How the audio works

- Each section can have two recordings: **English** and **中文**. The **EN / 中文** buttons appear only when both exist.
- In **Sections** mode the player follows the section you are reading.
- In **Pages** mode it follows the page you are on.
- In **Full Chapter** mode, use the drop-down beside the player to choose which section to hear.
- If a section has **no recording**, a **🔊 Read Aloud** button appears instead. It uses your device's built-in voice and reads the English only, so the quality depends on your phone or computer.
- **Listen to more than one section:** beside the player, choose **▸ This section only** (default), **▸▸ Whole chapter** or **▸▸▸ Whole book**. When a recording ends, the next one starts by itself and the page follows along. Your **EN / 中文** choice is kept from section to section (a section without that language plays in English).
- Single-section playback pauses when you leave the browser tab. **Whole chapter / Whole book keeps playing**, but some phones stop audio when the screen locks. If that happens, press ▶ again.

## Your notes and progress

- Your reading position, highlights, notes, text size and dark-mode choice are saved **in your own browser, on this device only**.
- They do **not** move to another phone or computer by themselves, and they are lost if you clear the browser's site data or use a private window.
- To keep or move them: **📒 My Notes → 💾 Full Backup → ⬇️ Export All Data**. On the other device, open the same page and choose **⬆️ Import All Data** in the same place.
- When the book is updated, your notes stay as long as the book keeps the same Book ID.

## Reading offline

1. On GitHub, choose **Code → Download ZIP** and unzip it.
2. Open `index.html` in your browser.
3. Keep the `audio` folder **next to** `index.html`. Do not move or rename it.

---

## For the teacher: how this repository is organised

```
[repo-name]/
├── index.html          ← the reader
├── audio/
│   ├── ch01-s1.mp3        chapter 1, section 1, English
│   ├── ch01-s1-zh.mp3     chapter 1, section 1, 中文
│   ├── ch01-s2.mp3
│   ├── ch01-s2-zh.mp3
│   └── …
└── README.md
```

- A chapter **without** sections uses `ch01.mp3` and `ch01-zh.mp3`.
- The generated reader is named `[Book Title]_reader.html`. **Rename it to `index.html`** so the link above works without a file name.
- **Use lowercase and the exact names.** GitHub Pages treats `Ch01-s1.mp3` and `ch01-s1.mp3` as different files, even though your computer does not.

### Publish for the first time

1. Create a repository for the book and add `index.html`, the `audio` folder and this README.
2. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` → Folder: `/ (root)` → Save**.
3. After a minute or two the page is live at `https://dwang055.github.io/[repo-name]/`.

### Update the book or the audio

1. Replace `index.html` with the newly generated reader and add or replace files in `audio/`.
2. In GitHub Desktop, write a short summary, **Commit to main**, then **Push origin**.
3. Wait one to two minutes, then hard refresh the page (**Ctrl+F5**, or **Cmd+Shift+R** on a Mac).
4. Keep the **Book ID** unchanged in the creator so students keep their notes.

### Size

GitHub rejects any single file over 100 MB, and a Pages site should stay under about 1 GB. A section recording is normally a few MB, so a full book fits comfortably.

---

## Troubleshooting

| Problem | What to check |
|---|---|
| No audio bar, but a **🔊 Read Aloud** button | That section has no recording linked. Link or generate its MP3 and regenerate the reader. |
| The player shows but nothing plays | Open `https://dwang055.github.io/[repo-name]/audio/ch01-s1.mp3` directly. If it does not play, the file is missing or its name or capitalisation is different. |
| Works on your computer but not online | File names are case-sensitive online. Use lowercase, exactly as the reader expects. |
| The **中文** button is missing | There is no `-zh` recording for that section. |
| An old version still shows | Hard refresh, or wait a couple of minutes for GitHub Pages to rebuild. |
| Notes or progress disappeared | You may be on a different browser or device, in a private window, or have cleared site data. Restore from your **Full Backup** file. |
| Read Aloud sounds odd | It uses your device's own voice. Choose a section that has a recording instead. |

---

## 中文快速指南

- **打开阅读器**：点击上方链接即可，无需注册或下载，手机、平板、电脑都可以。
- **双语阅读**：左边英文，右边中文；手机上用 **🇬🇧 English / 🇨🇳 中文** 按钮切换。
- **听音频**：点击 🎵 播放条；播放条旁可选 **只听本节（默认）/ 整章连续 / 整本书连续**；有两种录音时，用 **EN / 中文** 切换语言。没有录音的小节会显示 **🔊 Read Aloud**（朗读英文）。
- **生词**：点击高亮单词查看释义，再点 🔊 听发音。
- **笔记与高亮**：选中文字后点 **🖍 Highlight** 或 **📝 Note**；在 **📒 My Notes** 里集中查看。
- **进度保存在本设备**：阅读进度、笔记和高亮只保存在当前浏览器中。换设备或清除浏览器数据前，请先到 **📒 My Notes → 💾 Full Backup → ⬇️ Export All Data** 导出备份。
- **离线使用**：下载 ZIP 并解压，用浏览器打开 `index.html`，并保持 `audio` 文件夹与它放在一起。

---

*Made with Words That Think · 品词坊 · 以词启思*
