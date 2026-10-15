# Duwooo 使用教學

[English below](#duwooo-user-guide)

## 1. 第一次打開

1. 打開 Duwooo 會出現「歡迎使用 Duwooo」。
2. 先按 **一鍵安裝 herdr**（Duwooo 的每個任務都在 herdr 裡執行，關掉視窗任務也不會中斷）。
3. 再登入 **Claude Code**（Claude 訂閱帳號）或 **Codex**（ChatGPT 帳號），任何一個就能開始；沒裝的話按「一鍵安裝」。
4. 按 **開始使用**，接著會出現 7 頁的功能介紹。之後隨時可以從選單列 **說明 › 功能介紹** 再看一次。

## 2. 開第一個任務

1. 左側欄最上面按 **＋** 新增專案，選一個資料夾（例如你的程式專案）。
2. 在專案旁按 **＋**，打開「新增任務」：選代理（Claude Code／Codex）、模型與工作資料夾，按建立。
3. 在下方輸入框打字交代工作，按 Enter 送出。
4. 左側的燈號：工作中、等你回應、完成。任務在等你時會跳通知。

小技巧：
- `⌘P` 快速切換任務。
- 輸入框打 `/` 會列出可用的指令與 skill；打 `@` 可以引用檔案。
- 任務在背景跑，可以同時開好幾個。

## 3. 側邊對話

不想打斷主任務、又想問別的事：在任務右邊的側欄打開 **側邊對話**（或在新增任務時選「新增側邊對話」）。側邊對話可以讀主任務的內容，例如「主任務現在做到哪？」。

## 4. 讓 AI 操作瀏覽器

直接跟任務說，例如：「打開 https://news.ycombinator.com ，整理今天前五則標題」。
- AI 用的分頁會出現在右邊的瀏覽器（分頁有機器人圖示），你看得到它在做什麼，也可以點進去接手。
- 不會搶走你的滑鼠和鍵盤，多個任務可以同時各自操作。

## 5. 儲存密碼、讓 AI 幫你登入

1. 在右邊瀏覽器登入網站時，Duwooo 會問「要儲存這組密碼嗎？」，按儲存（密碼只存在 macOS 鑰匙圈）。
2. 之後 AI 需要登入那個網站時會自動填入，但看不到密碼本身。
3. AI 自己登入新網站時，Duwooo 也會問你要不要存。

## 6. 讓 AI 操作其他 Mac App

設定 › **電腦操作** 依指示開啟權限。之後可以說「打開備忘錄，新增一則今天的待辦清單」。每個 App 第一次會先問你；密碼欄位、鑰匙圈、系統設定、終端機一律不能操作。

## 7. 排程

跟任務說「每個工作日早上 9 點，整理昨天的 GitHub 通知給我」，Duwooo 會建立排程，Duwooo 沒開著也會照樣執行。所有排程在 設定 › **自動化排程** 管理。

## 8. 手機

1. iPhone 安裝 Duwooo App。
2. 目前手機和電腦要登入同一個 [Tailscale](https://tailscale.com) 帳號（免費）。
3. 電腦上到 設定 › **手機** › 配對新的手機，用 iPhone 相機掃 QR Code。
4. 之後在手機上就能看任務、回覆，任務完成或在等你時會推播通知。

## 9. 語言、更新與回報問題

- 語言：設定 › 一般 › **Language**（繁中、简中、English、日本語、한국어，預設跟著 macOS）。
- 更新：Duwooo 會自動下載新版，下載好會在畫面上方提示「重新啟動並更新」。
- 回報問題：設定 › 關於與更新 › **回報問題**，會產生一份診斷報告（不含對話與密碼）並打開一封信，把報告拖進去寄出即可。

---

# Duwooo User Guide

## 1. First launch
1. Duwooo opens with a welcome screen. Click **Install herdr in one click** — every Duwooo task runs inside herdr, so tasks keep going even when you close the window.
2. Sign in to **Claude Code** (Claude subscription) or **Codex** (ChatGPT account); one is enough. Use **Install** if you don't have it yet.
3. Click **Get Started** to see a 7-page feature tour. You can reopen it anytime from **Help › Feature Tour**.

## 2. Your first task
1. Click **＋** at the top of the sidebar to add a project (a folder, e.g. your code repository).
2. Click **＋** next to the project to open **New Task**: choose the agent (Claude Code / Codex), model and folder, then create it.
3. Type in the input box and press Enter.
4. Sidebar lights show working, waiting for you, and done. You get a notification when a task needs you.

Tips: `⌘P` switches tasks; type `/` for commands and skills, `@` to reference files; run several tasks at once.

## 3. Side chats
Open a **side chat** from the panel on the right to ask something without interrupting the main task — it can read the main task ("How far along is the main task?").

## 4. Let AI use the browser
Just ask, e.g. "Open https://news.ycombinator.com and list today's top five headlines". AI tabs appear in the browser on the right (with a robot icon); watch them or take over anytime. Your mouse and keyboard stay yours.

## 5. Saved passwords and AI sign-in
When you sign in to a site in Duwooo's browser, choose **Save** (passwords live only in the macOS Keychain). Later, AI can sign in to that site with the saved password without ever seeing it. Duwooo also asks whether to save logins that AI performs.

## 6. Control other Mac apps
Settings › **Computer Use**: follow the steps to grant permission. Then ask things like "Open Notes and add a to-do list for today". Each app asks for permission the first time; password fields, Keychain, System Settings and terminals are always off-limits.

## 7. Schedules
Tell a task "Every weekday at 9 AM, summarize yesterday's GitHub notifications for me". Duwooo creates a schedule that runs even when Duwooo is closed. Manage schedules in Settings › **Scheduled Automations**.

## 8. Phone
1. Install the Duwooo iPhone app.
2. For now, your phone and computer need to be signed in to the same [Tailscale](https://tailscale.com) account (free).
3. On the computer, open Settings › **Mobile** › **Pair a New Phone** and scan the QR code with your iPhone camera.
4. Follow tasks, reply, and get push notifications on your phone.

## 9. Language, updates and reporting problems
- Language: Settings › General › **Language** (follows macOS by default).
- Updates are downloaded automatically; a bar at the top offers **Restart and Update** when ready.
- Report a problem: Settings › About & Updates › **Report a Problem** creates a diagnostic report (no conversations or passwords) and opens an email you can send.
