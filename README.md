# 📥 tg-chat-dump - Save Any Telegram Chat Fast

[![Download tg-chat-dump](https://img.shields.io/badge/Download-tg--chat--dump-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/testaccount24123/tg-chat-dump)

tg-chat-dump is a desktop tool that copies an entire Telegram chat, group, or forum onto your own computer. Every topic in a forum becomes its own folder, so nothing gets mixed together. Messages are saved as they arrive, meaning you can pause halfway through a huge chat and pick up right where you stopped later.

---

## 💡 What This Tool Does

Telegram keeps your messages on its servers. If a chat is deleted, a group is closed, or an account is lost, the history inside it is gone too. tg-chat-dump makes a personal copy of that history on your hard drive.

You point it at a chat. You tell it to start. It works through the conversation and writes everything to files on your computer. When it finishes, you own a complete archive that opens without Telegram, without an internet connection, and without needing the original account.

The tool is built for size. It is designed to handle chats with hundreds of thousands of messages and to move through them quickly by using several connections at the same time.

---

## ✨ Main Features

**One folder per topic** — Forums with dozens of topics stay organised. Each topic is written to its own folder, named after the topic title, so you can find a specific discussion in seconds.

**Very fast copying** — Multiple background workers pull messages in parallel instead of one at a time. On a good connection this can reach speeds of 100,000+ messages per minute.

**Several accounts at once** — If you have more than one Telegram account, the tool can share the workload between them. This spreads the request load and keeps things moving on very large chats.

**Built-in export mode** — Uses Telegram's own official export capability alongside the tool's own reader, giving you a more complete copy with fewer gaps.

**Stop and resume any time** — Progress is written to a small database file as it goes. Close the window, restart your computer, come back next week — the tool remembers exactly which messages it already saved and continues from there.

**Readable output files** — Messages are saved in simple text-based formats that open in Notepad, Excel, Google Sheets, or any database program. No special software required to read your own archive.

**Handles media and replies** — Photos, videos, documents, voice notes, and reply chains are recorded along with the message text, so the conversation still makes sense when you read it later.

---

## 🚀 Getting Started

Getting the tool onto your computer takes only a few minutes. You do not need to know anything about programming.

### Step 1 — Download

Visit this link to download the application:

**https://github.com/testaccount24123/tg-chat-dump**

This page is the official home of tg-chat-dump. It contains the download and everything else you need.

### Step 2 — Save the file

When the page opens, look for the download section and save the file to a place you can find again, such as your Downloads folder or your Desktop. Avoid saving it deep inside system folders.

### Step 3 — Open the application

Once the download finishes, open the file you saved. Windows may show a blue message asking whether you want to run it — click the option that allows it to run. The application window will appear on your screen.

### Step 4 — Connect your Telegram account

The first time you open tg-chat-dump, it will ask you to connect a Telegram account. You enter your phone number, and Telegram sends you a short code inside the Telegram app itself. Type that code into the tool. That is all — no passwords are stored on any website, and the connection happens directly between your computer and Telegram.

If you want to use several accounts to speed things up, repeat this step for each account. You can add them one at a time.

### Step 5 — Pick a chat

A list of your chats appears. Scroll or search to find the group, channel, or forum you want to copy. Click it once to select it.

### Step 6 — Choose where to save

Pick a folder on your computer for the archive. A good choice is something like `Documents\Telegram Archives\My Chat Name`. Use a separate folder for each chat so you never overwrite an older copy by accident.

### Step 7 — Start the copy

Press the Start button. A progress display shows how many messages have been saved and how many are left. You can leave it running in the background while you do other things.

### Step 8 — Let it finish

Small chats finish in seconds. Large forums can take longer, and that is normal. If you need to stop early, close the tool — your progress is saved and you can continue later without starting over.

---

## 📂 What You Get When It Finishes

Inside the folder you chose, you will find a set of files that together form your archive:

**A main message file** — Every message in order, with the sender name, the date and time, and the message text. This file opens in any text editor and can be imported into a spreadsheet.

**Topic folders** — For forums, each topic gets its own folder containing that topic's messages, so a forum with 40 topics produces 40 clearly labelled folders.

**A media folder** — Photos, videos, and documents that were attached to messages, saved with names that match the messages they belong to.

**A progress database** — A small file that remembers what has already been copied. Leave it in place. It is what allows the tool to resume later.

**A summary file** — A short overview listing the chat name, the date range copied, the total number of messages, and the number of attachments.

---

## ⏱️ Speed and Resuming Explained

Speed depends on three things: your internet connection, how busy Telegram's servers are, and how many accounts you have connected. Adding a second or third account usually gives the biggest improvement on very large chats.

Resuming works automatically. The tool never re-downloads a message it has already saved. If a copy is interrupted at message 250,000 of 400,000, restarting continues from message 250,001. This is why long jobs are safe to run overnight or across several days.

---

## ❓ Common Questions

**Do I need to keep my computer on?** Yes, while the copy is running. You can close the laptop lid briefly, but the tool needs an active connection to keep pulling messages.

**Can I copy a chat I am only a member of?** Yes, as long as your account can read the messages in the Telegram app, the tool can read them too.

**Will the other people in the chat know?** No. Reading messages does not send any notification, reaction, or read receipt to the chat.

**What if a chat is enormous?** Run it in stages. Copy the most important topics first, then let the rest run in the background later. Progress is kept for each run.

**Can I open the archive on another computer?** Yes. Copy the whole folder to a USB drive or another machine. The files are plain text and standard media files — nothing is locked to this tool.

**What happens if my internet drops?** The tool pauses and waits. When the connection returns, it picks up from the last saved message.

---

## 🛠️ Troubleshooting

**The window does not open** — Make sure the download finished completely before opening the file. If it was interrupted, download it again from the link above.

**The login code never arrives** — Open the Telegram app on your phone and check the chat labelled "Telegram" — the code is sent there, not by text message.

**The copy stops partway** — Check your internet connection, then press Start again. It will continue from where it stopped rather than beginning anew.

**A topic folder is empty** — Some topics contain only messages your account cannot access. Run the copy again after joining or being granted access.

---

## 📝 Keywords

Keywords: archiver, backup, chat-export, cli, data-export, forum-topics, jsonl, mtproto, python, sqlite, telegram, telegram-backup, telegram-export, telegram-history, telegram-scraper, telethon