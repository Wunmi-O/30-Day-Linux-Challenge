# Day 05 - The Shell Deep Dive: $PATH, Bash & Config Files

## Objective
Understand how bash actually works — how it finds commands,
what config files control it, and how to customise it.

---

## What I Learned
- Bash is just a program that runs a Read→Evaluate→Print→Loop cycle
- $PATH is a list of folders bash searches to find commands
- "command not found" simply means bash searched all of $PATH and found nothing
- Commands are either built-in (live inside bash) or external (programs in /bin etc.)
- ~/.bashrc is bash's config file — it runs every time I open a terminal
- Aliases are custom shortcuts I can create for commands I use often
- Environment variables like $HOME, $USER and $PATH store system-wide settings

---

## What I Built / Practiced
- Ran echo $PATH to see where bash searches for commands
- Used which and type to identify where commands live
- Viewed my command history with history
- Created an alias ll='ls -la' and made it permanent in ~/.bashrc
- Ran source ~/.bashrc to apply changes without restarting terminal

---

## Challenges Faced
- The terms are a bit confusing and I may need to go over this lesson again

---

## Key Takeaways
- $PATH is everything — if bash can't find your command, PATH is where to look
- ~/.bashrc is where I personalise my shell experience
- source ~/.bashrc reloads settings without restarting the terminal
- Aliases save time — I can create shortcuts for commands I use daily

---

## Resources
- https://linuxjourney.com
- Run: man bash (the full bash manual)

---

## Output
<img width="1104" height="571" alt="8p" src="https://github.com/user-attachments/assets/0a9ed10c-04d3-43c9-9aef-5a1e1f023e89" />
<img width="1099" height="564" alt="9p" src="https://github.com/user-attachments/assets/6d3e1345-c3c3-4508-bb0b-e08ec39aa504" />
