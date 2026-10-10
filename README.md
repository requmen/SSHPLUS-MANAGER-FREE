# SSHPlus Manager

![SSHPlus Manager](Imagenes/SSHPLUS_MANAGER.png)

> **Durum:** Proje artık güncellenmiyor. Bu depodaki sürüm 38’dir; son güncelleme tarihi 09/08/2021’dir.

Linux sunucularda SSH ve VPN bağlantılarını yönetmek için kullanılan bir araçtır. Orijinal geliştirici: [@crazy_vpn](https://t.me/crazy_vpn).

## Gereksinimler

- Ubuntu veya Debian tabanlı Linux sunucusu
- Kurulum için yönetici (root) yetkisi

## Kurulum

Bağımlılıklar kurulum sırasında otomatik olarak yüklenir.

```bash
apt-get update -y;
apt-get upgrade -y;
wget https://raw.githubusercontent.com/requmen/SSHPLUS-MANAGER-FREE/master/Plus;
chmod +x Plus* && ./Plus
```

**Tek satırda (güncelleme adımlarını atlayarak):**

```bash
wget https://raw.githubusercontent.com/requmen/SSHPLUS-MANAGER-FREE/master/Plus; chmod +x Plus* && ./Plus
```

Kurulumdan sonra menüyü açmak için:

```bash
menu
```

## İsteğe bağlı: AdminPlus

![AdminPlus](Imagenes/adminplus.png)

```bash
wget -qO "/bin/adminplus" https://raw.githubusercontent.com/requmen/SSHPLUS-MANAGER-FREE/refs/heads/master/Proyectos/Adminplus/adminplus; chmod +x /bin/adminplus
```

AdminPlus menüsünü açmak için:

```bash
adminplus
```
