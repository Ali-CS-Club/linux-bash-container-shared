# 🐧 Linux, Bash & Containerization – Shared

👥 Shared with ALI CS Club

---

This repository is for **collaborative learning and experimentation** with:

- 🐚 **Linux command-line tools**
- 🔧 **Bash scripting**
- 📦 **Docker containerization**
- ☸️ **Kubernetes deployments**

It’s a shared space for ALI CS Club members to contribute practical scripts, container setups, orchestration configs, and technical notes.

---

## 📁 Project Structure

```
linux-bash-container-shared/
├── bash-scripts/              # Custom Bash utilities and automation tools
│   └── hello_world.sh
├── docker-images/             # Dockerfiles and image setups
│   ├── ubuntu-dev/
│   │   ├── Dockerfile
│   │   └── README.md          # Documents setup for dev container for general scripting in Ubuntu
│   ├── kali-dev/
│   │   ├── Dockerfile
│   │   └── README.md          # Documents kali-dev container, prepped for pen testing, reverse engineering, and cybersecurity labs using Kali Linux toolsets.
├── k8s-deployments/           # Kubernetes YAML manifests and Helm charts
│   └── nginx-deployment.yaml
├── notes/                     # Markdown docs and quick-reference commands
│   └── linux-permissions.md
└── README.md                  # You're reading it!

```

---

## 🚀 How to Use

### Bash Scripts

Run directly from terminal:

```bash
bash bash-scripts/your_script.sh
```

### Docker Images

Build and run a container:

```bash
cd docker-images/ubuntu-dev
docker build -t ali-dev .
docker run -it ali-dev
```

### Kubernetes Deployments

Apply a deployment (requires `kubectl` and access to a cluster):

```bash
kubectl apply -f k8s-deployments/nginx-deployment.yaml
```

---

## 🤝 Contribution Guidelines

- Add your work to the correct folder (`bash-scripts/`, `docker-images/`, etc.)
- Use descriptive filenames (e.g., `backup_script.sh`, `nginx-deployment.yaml`)
- Add clear comments and include a header comment block in scripts when possible
- If working **independently**, please **fork** or create a **branch** and open a **pull request**
- If collaborating **live with a partner**, only **one person should push changes at a time** to avoid merge issues

---

## 🎯 Purpose

This repo provides hands-on practice with:

- Writing and sharing Bash scripts
- Building and running custom Docker containers
- Deploying apps to Kubernetes clusters
- Using Git/GitHub to collaborate like pros

---

Happy hacking! 🐧💻⚙️
