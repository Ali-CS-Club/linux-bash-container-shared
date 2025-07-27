# 🐧 Ubuntu Dev Container

This folder contains a lightweight **Ubuntu-based Docker image** tailored for development and scripting tasks in a terminal environment.

---

## 📦 Image Overview

The `ubuntu-dev` container is designed for:

- General-purpose scripting and automation
- Installing and testing CLI utilities
- Running Python-based tools or environments
- Clean, minimal base for custom toolchains

---

## 📁 File Structure

```
ubuntu-dev/
├── Dockerfile     # Defines the base image and installed tools
└── README.md      # You're reading it!
```

---

## ⚙️ What's Inside

The container typically includes:

- `ubuntu:latest` as the base image
- `curl`, `wget`, `git`, and common CLI tools
- Optional: Python 3, pip, build-essential, etc.

You can modify the `Dockerfile` to include whatever packages you need for your workflow.

---

## 🚀 How to Build and Run

### Build the Image

```bash
docker build -t ubuntu-dev .
```

### Run the Container

```bash
docker run -it ubuntu-dev
```

You can mount volumes or set environment variables depending on your development setup.

---

## 🧠 Use Cases

This container is great for:

- Rapid prototyping with Bash and Python
- Learning CLI tools in a clean Linux environment
- Running small utilities or scripts without affecting your host OS

---

Happy hacking with Ubuntu! 🛠️🐧
