# Day 07 - Users & Groups: Identity in Linux

## Objective
Understand how Linux manages identity — who you are,
what you're allowed to do, and how sudo gives temporary power.

---

## What I Learned
- Linux was built for multiple users on one machine simultaneously
- There are 3 types of users: root (superuser), regular users, system users
- Root has unlimited power — lives at /root not /home
- Regular users live in /home/username and can only access their own files
- Groups are collections of users that share permissions
- sudo lets you borrow root power for one command at a time
- Every user has a unique ID number — root is always ID 0
- /etc/passwd stores every user on the system

---

## What I Built / Practiced
- Ran whoami and id to see my full identity details
- Read /etc/passwd to see all users on the system
- Used ls -l to see file ownership in action
- Ran sudo ls /root to borrow root power temporarily
- Used id -u and id -g to see my user and group ID numbers

---

## Challenges Faced
-

---

## Key Takeaways
- Never work as root directly — always use sudo for safety
- Every file in Linux is owned by a user and a group
- /etc/passwd and /etc/group are the master lists of users and groups
- This is why chmod from Day 3 matters — permissions only make sense with users

---

## Resources
- https://linuxjourney.com

---

## Output
<img width="698" height="674" alt="16p" src="https://github.com/user-attachments/assets/55fbcc8d-70a9-4918-a4a5-b5eec70bb1d2" />
<img width="525" height="234" alt="17p" src="https://github.com/user-attachments/assets/3843a5ae-5347-4c1b-9748-a609e9b0ceba" />
