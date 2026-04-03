# Day 03 - Linux File Permissions

## Objective

Understand Linux file and directory permissions, user types, and how to modify permissions and ownership. Practice applying these concepts to control access effectively.

---

## What I Learned

- Every file and directory in Linux has permissions that define who can access it and what they can do (read, write, execute)
- 3 Type of Users: User(u) File Owner, Group(g) Users in the file's group, Others(o) Everyone else
- 3 Type of Permissions: Read(r), Write(w), Execute(x)
- Changing permissions: Symbolic mode: using +, -, = with u, g, o, a. Octal (numeric) mode: using numbers (r=4, w=2, x=1)
- Ownership: files are tied to owner and group; can be changed using chown.
- Directory permissions behave differently: execute (x) allows entering the directory, write (w) allows adding/removing files, read (r) allows listing contents.

---

## What I Built / Practiced

- Made a script executable: chmod +x myscript.sh
- Gave group write access to a directory
- Restricted access to a file (owner only)
- Made a file publicly readable:

---

## Challenges Faced

- Remembering the difference between symbolic and octal permission modes.
- Understanding directory execute (x) permission and how it affects cd.
- Ensuring ownership changes with chown reflect correctly for both owner and group.
  
---

## Key Takeaways

- File permissions are crucial for Linux security and control over access.
- Symbolic mode is intuitive for small changes, numeric mode is compact for setting exact permissions.
- Directory permissions have special behavior; execute permission is key for navigation.
- Ownership controls who can change permissions and access files.

---

## Resources

- Linux chmod, chown man pages: man chmod, man chown
- Online tutorial: Linux File Permissions Explained
- Example exercises from Day 3 lesson notes.

---

## Output

<img width="1349" height="151" alt="6p" src="https://github.com/user-attachments/assets/fc5d36b6-2716-4d27-a894-ad112b647d16" />

