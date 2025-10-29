# dev-env v3.0 — **Tek Tıkla Geliştirme Ortamı**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cevikgazi/dev-env/blob/main/dev-env.ipynb)
[![Release](https://img.shields.io/github/v/release/cevikgazi/dev-env?label=Download%20ZIP)](https://github.com/cevikgazi/dev-env/releases/latest)
![Docker](https://img.shields.io/badge/Docker-Ready-blue)
![Forgejo](https://img.shields.io/badge/Forgejo-Ready-green)

> **Code Server + Nexus + Forgejo** — **Sıfır Manuel, Her Yerde Çalışır**

---

## Özellikler

- **Code Server** – VS Code Web IDE (Rust, Python, Git)
- **Nexus** – Maven/PyPI/Docker Proxy
- **Forgejo** – Git GUI + CI/CD (Gitea’nın modern fork’u)
- **Otomatik SSH Key**
- **Rastgele Şifre**
- **VS Code Extensions** (`rust-analyzer`, `python`)
- **`.env` ile yapılandırma**
- **Google Colab’da ZIP oluşturma**

---

## Hızlı Başlangıç

### 1. ZIP İndir (Otomatik Release)
```bash
curl -L -o dev-env.zip https://github.com/cevikgazi/dev-env/releases/latest/download/dev-env.zip
```
### 2. Kur & Başlat


```bash
unzip dev-env.zip -d dev-env
cd dev-env
chmod +x setup.sh
./setup.sh
