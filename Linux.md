Operating System:  

An operating system acts as an intermediary between the user of a computer and computer hardware. In short its
an interface between computer hardware and user.  

Workflow:  

<img width="689" height="339" alt="image" src="https://github.com/user-attachments/assets/e131d010-5228-4f41-93af-1ace2986c245" />  

Functions of OS:  

<img width="720" height="349" alt="image" src="https://github.com/user-attachments/assets/98a6b3a8-dc15-4ea1-9c6d-246c9b90bb48" />  

Different types of OS available:

<img width="701" height="341" alt="image" src="https://github.com/user-attachments/assets/72891998-e648-4507-9332-137f0ab9a941" />


Components of an Operating Systems:
There are two basic components of an Operating System.
- Shell is the outermost layer of the Operating System and it handles the interaction with the user. It interprets input for the OS and handles the output from the OS.
- Kernel is the core component of operating system. The kernel is the primary interface between the Operating system and Hardware.

Linux operating system:
- Linux is free and open-source, accessible to everyone.
- Its source code can be inspected and modified by anyone.
- This promotes global collaboration and innovation.
- Linux offers efficient performance and strong security.
- It works well across many devices and industries.

---CLI (Command-Line Interface)

What it is: A text-based interface where you type commands.

How it looks: A black/white terminal screen (like when you use Linux commands).

Examples:

ls → list files

cd /home → change directory

rm file.txt → remove a file

-Pros:

Very powerful and precise.

Uses fewer system resources (lightweight).

Can be automated with scripts.

-Cons:

Steeper learning curve.

You need to remember commands and syntax.

---GUI (Graphical User Interface)

What it is: A visual interface with windows, icons, menus, and buttons.

How it looks: Like Windows desktop, Ubuntu Desktop, macOS — you use a mouse and keyboard.

Examples:

Clicking folders in File Explorer instead of using ls.

Using Google Chrome browser instead of typing curl or wget.

Managing files with drag-and-drop.

-Pros:

Easier for beginners.

Intuitive and user-friendly.

Good for tasks that are visual (editing images, browsing).

-Cons:

Consumes more memory and CPU.

Less efficient for automation and repetitive tasks.

---Simple Analogy

CLI = Talking to the computer in its own language (commands).

GUI = Pointing and clicking to tell the computer what you want.

---Why We Need to Use Linux Commands

1. Servers don’t have GUI (mostly)

Cloud servers (AWS, GCP, Azure), production servers, or remote systems usually run Linux without any desktop interface.

The only way to work with them is through commands in the terminal (via SSH).

2. Automation & Scripting

Repeating tasks manually wastes time.

With commands + shell scripting, you can automate tasks like:

Taking backups

Cleaning logs

Deploying apps

Scheduling jobs with cron

Faster & More Efficient

3. Commands are often faster than clicking through menus.

Example:

find /var/log -name "*.log" -size +10M


👉 This finds all log files bigger than 10MB in one go. Doing this with GUI = time consuming.

4. Power & Flexibility

You can combine commands using pipes (|) and redirection.

Example:

ps aux | grep python > process_list.txt


Finds all running Python processes and saves them into a file.

5. More Control Over the System

Linux commands let you control things Windows GUI doesn’t easily allow:

Changing permissions (chmod, chown)

Managing processes (kill, top)

Monitoring network (netstat, ping, ifconfig)

6. Universal Language for Tech

In DevOps, Data Engineering, Cybersecurity, Cloud, AI/ML, Linux commands are a common skill.

If you know Linux CLI, you can work on almost any system.

7. Lightweight & Remote Friendly

Using commands requires almost no system resources.

Perfect for working on low-power servers or remote connections where GUI is too heavy.

---Quick Analogy

Think of GUI = driving an automatic car (easy, but limited control).
Think of Linux CLI = driving a manual car (harder at first, but full control).
