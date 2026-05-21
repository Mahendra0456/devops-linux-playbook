# <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="45"/> Linux Commands for DevOps & Cloud Engineers

<div align="center">

# ⚡ Ultimate Linux Command Handbook ⚡

### 🚀 Beginner → Advanced → Production Level

<p align="center">

<img src="https://img.shields.io/badge/Linux-Commands-black?style=for-the-badge&logo=linux"/>
<img src="https://img.shields.io/badge/DevOps-Engineering-blue?style=for-the-badge&logo=dev.to"/>
<img src="https://img.shields.io/badge/AWS-Cloud-orange?style=for-the-badge&logo=amazonaws"/>
<img src="https://img.shields.io/badge/Kubernetes-K8S-blue?style=for-the-badge&logo=kubernetes"/>
<img src="https://img.shields.io/badge/Docker-Containers-2496ED?style=for-the-badge&logo=docker"/>
<img src="https://img.shields.io/badge/Terraform-IaC-7B42BC?style=for-the-badge&logo=terraform"/>
<img src="https://img.shields.io/badge/Jenkins-CI/CD-red?style=for-the-badge&logo=jenkins"/>

</p>

---

## 🧠 Learn Linux Like a Real DevOps Engineer

</div>

---

# 📚 Table of Contents

- 🐧 Linux Basics
- 📂 File Management
- 👤 User Management
- 🔐 Permissions
- ⚙️ Process Management
- 🌐 Networking
- 📦 Package Management
- 💾 Storage Commands
- 📈 Monitoring & Logs
- ☁️ AWS Linux Commands
- 🐳 Docker Commands
- ☸️ Kubernetes Commands
- 🏗️ Terraform Commands
- 🚀 Jenkins Commands
- 🔥 Production Troubleshooting

---

# 🐧 Linux Basics

| Command | Description |
|---|---|
| `pwd` | Current directory |
| `whoami` | Current user |
| `hostname` | Server hostname |
| `history` | Command history |
| `clear` | Clear terminal |

```bash
pwd
whoami
hostname
history
```

---

# 📂 File Management Commands

| Command | Description |
|---|---|
| `ls -la` | Show hidden files |
| `mkdir` | Create folder |
| `touch` | Create file |
| `cp` | Copy file |
| `mv` | Move/Rename |
| `rm -rf` | Delete |
| `find` | Search files |

```bash
ls -la
mkdir devops
touch app.py
cp file1 file2
mv old.txt new.txt
rm -rf temp/
find / -name nginx.conf
```

---

# 👤 User Management

| Command | Description |
|---|---|
| `id` | User details |
| `groups` | User groups |
| `adduser` | Create user |
| `passwd` | Set password |
| `usermod` | Modify user |

```bash
id
groups
adduser devops
passwd devops
usermod -aG sudo devops
```

---

# 🔐 Permissions

| Permission | Value |
|---|---|
| Read | 4 |
| Write | 2 |
| Execute | 1 |

```bash
chmod 755 file.sh
chmod +x deploy.sh
chown ubuntu:ubuntu app.py
```

---

# ⚙️ Process Management

```bash
ps aux
top
htop
kill -9 PID
pkill nginx
jobs
fg
bg
```

---

# 🌐 Networking Commands

| Command | Purpose |
|---|---|
| `ip a` | IP Address |
| `ping` | Connectivity |
| `curl` | API Testing |
| `ss -tulnp` | Open Ports |
| `dig` | DNS Lookup |

```bash
ip a
ping google.com
curl ifconfig.me
ss -tulnp
dig google.com
```

---

# 📦 Package Management

## Ubuntu / Debian

```bash
apt update
apt upgrade -y
apt install nginx -y
```

## CentOS / RHEL

```bash
yum install httpd -y
dnf install docker -y
```

---

# 💾 Storage Commands

```bash
lsblk
df -h
du -sh /*
mount
umount /mnt/data
mkfs.ext4 /dev/xvdb
```

---

# 📈 Monitoring & Logs

```bash
free -h
uptime
journalctl -xe
tail -f /var/log/syslog
vmstat 1
iostat -x 1
```

---

# ☁️ AWS Linux Commands

## 📀 EBS Volume

```bash
mkfs.ext4 /dev/xvdb
mount /dev/xvdb /mnt/data
```

## 📂 EFS

```bash
yum install -y amazon-efs-utils
mount -t efs fs-xxxx:/ /mnt/efs
```

---

# 🐳 Docker Commands

```bash
docker ps
docker images
docker logs container_id
docker exec -it container bash
docker system prune
```

---

# ☸️ Kubernetes Commands

```bash
kubectl get pods
kubectl get svc
kubectl describe pod pod-name
kubectl logs pod-name
kubectl top nodes
```

---

# 🏗️ Terraform Commands

```bash
terraform init
terraform plan
terraform apply
terraform destroy
terraform state list
```

---

# 🚀 Jenkins Commands

```bash
systemctl status jenkins
journalctl -u jenkins
cat /var/lib/jenkins/secrets/initialAdminPassword
```

---

# 🔥 Production Troubleshooting

## 🚨 CPU High

```bash
top
htop
ps aux --sort=-%cpu
```

---

## 🚨 Disk Full

```bash
df -h
du -sh /*
find / -size +500M
```

---

## 🚨 Service Down

```bash
systemctl status nginx
journalctl -u nginx
systemctl restart nginx
```

---

# 🧠 Linux Architecture

```text
                User
                  │
                  ▼
            Linux Shell
                  │
                  ▼
               Kernel
                  │
    ┌─────────────┼─────────────┐
    ▼             ▼             ▼

 Process      Memory        Storage
Management   Management    Management
```

---

# 🚀 DevOps Learning Roadmap

```text
Linux
   ↓
Shell Scripting
   ↓
Git & GitHub
   ↓
Docker
   ↓
Kubernetes
   ↓
Terraform
   ↓
CI/CD
   ↓
AWS / Azure / GCP
```

---

# 🔐 Best Practices

✅ Use SSH Keys  
✅ Monitor logs regularly  
✅ Avoid chmod 777  
✅ Automate repetitive tasks  
✅ Learn troubleshooting  
✅ Practice shell scripting  

---

# ⭐ Support

If this repository helps you:

⭐ Star the repository  
🍴 Fork the repository  
📢 Share with friends  

---

<div align="center">

# 🚀 Happy Learning Linux 🐧

### Made for DevOps & Cloud Engineers

</div>
