# Day 04 - Linux Architecture: The Full Picture

## Objective

What was the goal for today?
I needed to go back to the basics and build up gradually. The plan is to understand every layer of Linux : Hardware, Kernel, Shell and Applications — and how they connect to each other

---

## What I Learned

- Linux has 4 layers: Hardware → Kernel → Shell → Applications → Me
- The Kernel has 4 jobs: memory, process, device and file management
- Every running program in Linux is called a process
- There are different types of shells (bash, zsh, sh, fish) — bash is most common
- Applications like Python and Git all sit on top of the shell/kernel layers


---

## What I Built / Practiced

- Ran uname -r to inspect my kernel
- Ran cat /etc/shells to see all shells installed on my system
- Ran ps aux to see all running processes managed by the kernel
- Explored ls / to see the root filesystem

---

## Challenges Faced

- 
- 

---

## Key Takeaways

- The kernel is the real boss — everything passes through it
- The shell is just a translator between me and the kernel
- Every command I type becomes a process that the kernel manages
- Linux was designed to run on any hardware — that's why servers run Linux

---

## Resources

- https://linuxjourney.com
- https://www.kernel.org (official Linux kernel site)

---

## Output

<img width="1339" height="692" alt="7p" src="https://github.com/user-attachments/assets/04ee9616-21a1-4361-a20b-fdb861f27efd" />

