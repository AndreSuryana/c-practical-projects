# 🔧 C Practical Projects

## 🧠 About This Repo

This repository documents my learning in C programming, focused on practical applications, system programming, and eventually Linux kernel development.

---

## 📁 Project List

| #   | Project                                      | Category    | Description                                        |
| --- | -------------------------------------------- | ----------- | -------------------------------------------------- |
| 1   | [textstat](fundamental/textstat)             | Fundamental | Counts lines, words, and characters in a text file |
| 2   | [simplegrep](fundamental/simplegrep)         | Fundamental | Pattern matcher like basic `grep`                  |
| 3   | [todo-cli](fundamental/todo-cli)             | Fundamental | Terminal todo list manager with file storage       |
| 4   | [calc](fundamental/calc)                     | Fundamental | CLI calculator with operator precedence            |
| 5   | [unit-converter](fundamental/unit-converter) | Fundamental | Converts between metric and imperial units         |
| 6   | [mycat](systems/mycat)                       | Systems     | Clone of `cat` using system calls                  |
| 7   | [dirlist](systems/dirlist)                   | Systems     | Lists files like `ls -l`                           |
| 8   | [mini-shell](systems/mini-shell)             | Systems     | Minimal shell using `fork` and `exec`              |
| 9   | [filewatcher](systems/filewatcher)           | Systems     | Watches file changes using `inotify`               |
| 10  | [disk-usage](systems/disk-usage)             | Systems     | Recursively calculates folder sizes                |
| 11  | [procstat](toolkit/procstat)                 | Toolkit     | Displays info from `/proc` about processes         |
| 12  | [memwatch](toolkit/memwatch)                 | Toolkit     | Monitors memory usage of a process                 |
| 13  | [multidownload](toolkit/multidownload)       | Toolkit     | Multithreaded HTTP downloader                      |
| 14  | [logfilter](toolkit/logfilter)               | Toolkit     | Filters logs by keyword/time                       |
| 15  | [netcheck](toolkit/netcheck)                 | Toolkit     | Network reachability checker (ping-like)           |
| 16  | [hello.ko](kernel/hello.ko)                  | Kernel      | Hello-world kernel module                          |
| 17  | [klogwatch](kernel/klogwatch)                | Kernel      | Reads kernel logs from `/dev/kmsg`                 |
| 18  | [devmemtool](kernel/devmemtool)              | Kernel      | Reads/writes memory using `/dev/mem`               |
| 19  | [minidriver](kernel/minidriver)              | Kernel      | Dummy character device driver                      |
| 20  | [custom-syscall](kernel/custom-syscall)      | Kernel      | Adds a syscall to the Linux kernel                 |

---

## 🛠 Setup & Tools

- **Compiler**: `gcc`, `clang`
- **Build Tools**: `make`
- **Debugger**: `gdb`, `valgrind`, `strace`
- **Kernel Dev**: `insmod`, `dmesg`, kernel headers
- **System**: Linux-based (Ubuntu, Fedora, Arch)

---

## ✅ Project Template (per folder)

Each project contains:

- `main.c` or source files
- `Makefile` for easy builds
- `README.md` with usage, design, learning notes

---

## 🎯 Learning Goals

These are the skills and concepts I aim to build by completing the projects in each category.

### 🧱 Fundamentals (from `fundamental/`)
- [ ] Write modular and clean C code using pointers, arrays, and structs
- [ ] Handle file I/O and user input effectively
- [ ] Use the C standard library (`stdio.h`, `stdlib.h`, `string.h`, etc.)
- [ ] Practice memory management and debugging basics

### ⚙️ Systems (from `systems`/)
- [ ] Use Linux system calls like `open()`, `read()`, `write()`, and `stat()`
- [ ] Work with directories, file descriptors, and system-level APIs
- [ ] Understand process creation with `fork()` and `exec()`
- [ ] Monitor file system events using Linux-specific interfaces (e.g., `inotify`)
- [ ] Implement file monitoring and process utilities
- [ ] Build command-line tools that mirror real Unix utilities

### 🧰 Toolkit (from `toolkit/`)
- [ ] Access and parse `/proc` to retrieve system and process info
- [ ] Track resource usage and memory allocation patterns
- [ ] Create diagnostic utilities for system monitoring
- [ ] Build multithreaded tools using POSIX threads and synchronization
- [ ] Practice performance profiling and system-level debugging with tools like `gdb`, `valgrind`, and `strace`

### 🧪 Kernel (from `kernel/`)
- [ ] Write and load Linux kernel modules using `insmod` and `rmmod`
- [ ] Log kernel output via `printk()` and inspect it using `dmesg`
- [ ] Access kernel interfaces like `/dev/kmsg` and `/dev/mem`
- [ ] Implement basic character device drivers
- [ ] Add and test a custom syscall in the Linux kernel

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).
