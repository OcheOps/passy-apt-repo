# Passy APT Repo

This repo serves `.deb` packages for the **Passy** CLI.

## 🧪 Usage (Ubuntu/Debian)

```bash
echo "deb [trusted=yes] https://ocheops.github.io/passy-apt-repo stable main" | sudo tee /etc/apt/sources.list.d/passy.list
sudo apt update
sudo apt install passy
```

## 📦 Maintainer
[OcheOps](https://github.com/OcheOps)
