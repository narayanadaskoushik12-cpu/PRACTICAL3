<<<<<<< HEAD
# OS_Pract2
=======
# ShellForge

ShellForge is a Unix-like shell developed as part of the Operating Systems and Systems Programming Project-Based Learning course.

## Features (Week 1)

- Interactive REPL loop
- Makefile-based build
- Git repository
- Linux development environment

## Build

make

## Run

make run
>>>>>>> 9d6caae59e94dc8d9a279251ecccf5aa7ab98743
# OSSP Practical 4 – Process Synchronization

## 📌 Description

This practical demonstrates process synchronization in Linux using C programs.

The practical covers:

1. Creating multiple child processes using `fork()`
2. Synchronizing child processes using `wait()`
3. Synchronizing a specific child process using `waitpid()`
4. Understanding the difference between `wait()` and `waitpid()`
5. Creating and observing a zombie process
6. Eliminating a zombie process using proper synchronization
7. Uploading C programs to a GitHub repository

---

## 🛠️ Technologies Used

- C Programming
- Linux/Unix Operating System
- GCC Compiler
- Git
- GitHub

---

## 📂 Programs Included

### 1. `wait_waitpid_demo.c`

This program creates three child processes and demonstrates the use of both `wait()` and `waitpid()`.

The child processes have different execution times.

### `wait()`

`wait()` waits for **any child process** that terminates.

```c
wait(&status);
