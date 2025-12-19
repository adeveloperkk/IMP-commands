---

````md
# 🚀 DeveloperKK – Important Commands & Developer Notes

Welcome to my GitHub repository!  
This README contains **frequently used commands, quick references, and best practices** that help in **Linux administration, Git, Frappe/ERPNext, and web development workflows**.

---

## 👨‍💻 About Me

**Krishnaveer Singh**  
Founder – **DeveloperKK | ElevateBharat**  
Award-winning Digital Marketing & Web Development Professional  
💼 5+ years of industry experience in:
- Website Development
- Graphic Design
- SEO & Digital Marketing
- Linux & Server Management
- AI & Automation

🌐 Websites:
- https://developerkk.in  
- https://elevatebharat.com  

---

## 🐧 Important Linux Commands

### System & Process
```bash
uname -a          # System information
top               # Live process monitoring
htop              # Advanced process monitor
df -h             # Disk usage
free -m           # Memory usage
uptime            # System running time
````

### File & Directory

```bash
ls -la            # List files with permissions
pwd               # Current directory
mkdir foldername  # Create directory
rm -rf folder     # Delete folder forcefully
cp -r src dest    # Copy directory
mv old new        # Rename / move files
```

### Permissions

```bash
chmod 755 file.sh
chown user:user file
```

---

## 🌱 Git Essential Commands

```bash
git init
git clone <repo_url>
git status
git add .
git commit -m "Initial commit"
git branch
git checkout -b new-branch
git pull origin main
git push origin main
```

### Fix Common Git Issues

```bash
git reset --hard
git clean -fd
git stash
git stash pop
```

---

## ⚙️ Frappe / ERPNext Commands

### Bench Basics

```bash
bench start
bench restart
bench stop
```

### Site Management

```bash
bench new-site sitename
bench --site sitename migrate
bench --site sitename clear-cache
bench --site sitename clear-website-cache
bench --site sitename install-app app_name
```

### Production

```bash
bench setup production frappe
bench setup nginx
bench setup supervisor
```

---

## 🌐 Server & Networking

```bash
sudo systemctl status nginx
sudo systemctl restart nginx
sudo systemctl restart supervisor
sudo ufw status
sudo ufw allow 80
sudo ufw allow 443
```

---

## 🧠 Useful Developer Tips

* Always take **backup before migration**
* Use `.env` for sensitive credentials
* Optimize images before upload
* Enable **HTTPS + caching**
* Monitor logs regularly

```bash
tail -f logs/web.error.log
tail -f logs/worker.error.log
```

---

## 📌 SEO & Web Best Practices

* Use clean URLs
* Optimize meta title & description
* Compress assets
* Use CDN where possible
* Mobile-first design

---

## 🔗 Connect With Me

[![Website](https://img.shields.io/badge/Website-developerkk.in-blue)](https://developerkk.in)
[![Website](https://img.shields.io/badge/Website-elevatebharat.com-green)](https://elevatebharat.com)
[![GitHub](https://img.shields.io/badge/GitHub-DeveloperKK-black)](https://github.com/adeveloperkk/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-DeveloperKK-blue)](https://www.linkedin.com/in/developerkk/)

---

## ⭐ Support

If this repository helped you:

* ⭐ Star this repo
* 🍴 Fork it
* 🔁 Share with developers

---

**© DeveloperKK | ElevateBharat**
*Building scalable digital solutions for India 🇮🇳*

```

---
```
