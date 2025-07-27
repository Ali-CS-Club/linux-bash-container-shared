# 🐉  Kali Dev Container

This folder contains a custom **Kali Linux-based Docker image** tailored for cybersecurity learning, reverse engineering, and penetration testing.

---
## 📦 Image Overview

The `kali-dev` container is designed for:

- Practicing ethical hacking and red teaming
- Running Kali-specific tools in a containerized setup
- Learning cybersecurity fundamentals in a sandboxed space
- Avoiding clutter or security risk to your host OS

---

## 📁 File Structure

```
kali-dev/
├── Dockerfile     # Defines the base Kali image and installed security tools
└── README.md      # You're reading it!
```

---

## 🛠️ What's Inside

The container typically includes:

- `kalilinux/kali-rolling` as the base image
- Common packages like `nmap`, `netcat`, `wireshark`, `metasploit`, and more
- You can tailor the `Dockerfile` to install specific tools based on your study needs

---

## 🚀 How to Build and Run

### Build the Image

```bash
docker build -t kali-dev .
```

### Run the Container

```bash
docker run -it --cap-add=NET_ADMIN --security-opt seccomp=unconfined kali-dev
```

> ⚠️ Some tools may require elevated permissions, extra flags, or a network bridge setup.

---

## 🧠 Use Cases

This container is ideal for:

- Practicing CTF (Capture the Flag) challenges
- Exploring network security tools without risk to your host
- Building custom security workflows and training environments

---

Happy hacking!
