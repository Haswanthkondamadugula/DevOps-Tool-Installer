# 🚀 DevOps Tool Installer & Uninstaller  

![image](https://github.com/user-attachments/assets/227483dc-2f68-42c2-b456-30d306c06e45)

Easily **install and uninstall essential DevOps tools** on **Linux & Windows** with a single script! Whether you're a **DevOps Engineer, Cloud Enthusiast, or System Administrator**, this toolkit automates setup and cleanup of your environment — saving time and effort.  

---

![image](https://github.com/user-attachments/assets/979a078c-5bf9-4346-a6a3-8bb83497c631)

## 🔥 Why Use This?  

✅ **One-Click Installation & Uninstallation** – Set up or clean up all required DevOps tools effortlessly.  
✅ **Multi-OS Support** – Works on **Ubuntu, Debian, CentOS, Fedora, Arch, Alpine & Windows**.  
✅ **Auto-Detection** – Automatically detects your OS and applies the correct package manager.  
✅ **Interactive Checklist UI** – Select tools with `whiptail` (Linux) or menus (PowerShell).  
✅ **Advanced Cleanup** – Stops services, removes configs, logs, and binaries cleanly.  
✅ **Dry Run Mode** – Simulate uninstallation before applying changes.  
✅ **Timestamped Logs** – Every operation is logged for traceability.  
✅ **Universal Launchers** – Use a single `devops.ps1` / `devops.sh` to install or uninstall tools.  

---

## 📌 Supported DevOps Tools  

### 🔹 Containerization & Orchestration  

✔️ Docker 🐳 | ✔️ Kubernetes (kubectl) ☸️ | ✔️ Helm ⛵ | ✔️ Minikube | ✔️ Istio | ✔️ OpenShift CLI  

### 🔹 Infrastructure as Code & Automation  

✔️ Ansible | ✔️ Terraform | ✔️ Packer | ✔️ Vagrant  

### 🔹 CI/CD & Monitoring  

✔️ Jenkins | ✔️ GitLab Runner | ✔️ Prometheus | ✔️ Grafana  

### 🔹 Cloud & Security  

✔️ AWS CLI | ✔️ Azure CLI | ✔️ Google Cloud SDK | ✔️ Vault | ✔️ Consul  

---

## 🛠️ Installation Guide  

### 🚀 Method 1: One-Liner (Quick Install)  

#### 📌 Windows (PowerShell):  

```powershell
iwr -useb https://raw.githubusercontent.com/Haswanth/DevOps-Tool-Installer/master/devops.ps1 | iex
```

#### 📌 Linux (Bash):  

```bash
curl -s https://raw.githubusercontent.com/Haswanth/DevOps-Tool-Installer/master/devops.sh | bash
```

🆕 These **combined launchers** (`devops.ps1` and `devops.sh`) automatically guide you to install or uninstall tools via an interactive prompt!

---

### 🖥️ Method 2: Clone the Repository  

#### 📌 Linux  

```bash
git clone https://github.com/Haswanth/DevOps-Tool-Installer.git  
cd DevOps-Tool-Installer  
chmod +x devops.sh  
./devops.sh
```

#### 📌 Windows  

```powershell
git clone https://github.com/Haswanth/DevOps-Tool-Installer.git  
cd DevOps-Tool-Installer  
.\devops.ps1  
```

---

## ❌ Uninstallation Guide  

🧹 This tool supports **clean uninstallation** with:  

- ✅ Interactive selection  
- ✅ Advanced cleanup (configs, services, logs)  
- ✅ Dry run mode for previewing changes  
- ✅ Timestamped logs saved in the `logs/` folder  

### 🔧 Linux & macOS  

Use the universal launcher:  

```bash
curl -s https://raw.githubusercontent.com/Haswanth/DevOps-Tool-Installer/master/devops.sh | bash
```

---

### 🔧 Windows  

Use PowerShell launcher:  

```powershell
iwr -useb https://raw.githubusercontent.com/Haswanth/DevOps-Tool-Installer/master/devops.ps1 | iex
```

---

🧭 **After running the launcher**, you'll be prompted to:  

- Select **Install Tools** or **Uninstall Tools**  
- Choose the tools from an interactive checklist  
- Run the selected operation with full logging

---

## 📋 What’s New  

- ✅ **`devops.sh` / `devops.ps1` launchers** – A single entrypoint for install/uninstall  
- ✅ **Uninstaller script (`uninstall_devops_tools.sh`)** with advanced logic  
- ✅ **Dry run mode** with `--dry-run` flag  
- ✅ **Interactive CLI/GUI checklist for tools**  
- ✅ **Logs saved to `logs/uninstall_YYYYMMDD_HHMMSS/`**  
- ✅ **Grouped tool categories for easier selection**  

---

## 📝 How It Works  

1️⃣ Run the script (via quick method or cloned repo)  
2️⃣ Choose **Install** or **Uninstall**  
3️⃣ Select tools interactively  
4️⃣ Script detects your OS and uses the appropriate package manager  

### OS-Specific Package Managers  

| OS        | Package Manager |
|-----------|------------------|
| Ubuntu/Debian | `apt`        |
| CentOS/RHEL   | `yum`        |
| Fedora        | `dnf`        |
| Arch Linux    | `pacman`     |
| Alpine        | `apk`        |
| SUSE          | `zypper`     |
| Windows       | `choco`      |

---

## 🤝 Contribution  

Contributions are welcome!  

- 🐞 Report bugs by opening issues  
- ✨ Suggest new tools or features  
- 🔧 Submit PRs to improve install/uninstall logic  

---

## 🔗 Join the Community  

💬 **Telegram:** [Join our group](https://t.me/DevOpsTechTeam)  
⭐ **GitHub:** [Follow me](https://github.com/Haswanthkondamadugula)  
📖 **Blog:** [DevOpsTech](https://hashnode.com/@Haswanth13)  
💼 **LinkedIn:** [Haswanth Reddy](http://linkedin.com/in/haswanthkondamadugula)  

