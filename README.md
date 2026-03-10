# 🧠 rockyou_uzb

**Uzbek Password Wordlist**

`rockyou_uzb.txt` — bu O‘zbekiston xizmatlaridan sizib chiqqan parollar asosida yig‘ilgan **Uzbek password wordlist**.

Pentesting, red teaming va security research uchun ishlatiladi.

---

## 📦 Dataset Sources

Wordlist quyidagi xizmatlardan olingan sizib chiqqan login parollar asosida tuzilgan:

* Instagram
* Eskiz SMS
* MyGov
* eMaktab
* Mohirdev
* HEMIS
* 1win
* PythonAnywhere

Parollar **tozalangan**, **duplicate olib tashlangan** va **alfavit bo‘yicha saralangan.

---

## 📥 Download

Wordlistni to‘g‘ridan to‘g‘ri yuklab olish:

```
wget https://raw.githubusercontent.com/Yescrypt/rockyou_uzb/main/rockyou_uzb.txt
```

---

## 📥 Git Clone

Repo ni klonlash:

```
git clone https://github.com/Yescrypt/rockyou_uzb.git
cd rockyou_uzb
```

---

## 🐉 Kali Linux Wordlist Installation

Wordlistni Kali wordlist katalogiga qo‘shish:

```
git clone https://github.com/Yescrypt/rockyou_uzb.git
sudo cp rockyou_uzb/rockyou_uzb.txt /usr/share/wordlists/
```

Tekshirish:

```
ls /usr/share/wordlists/rockyou_uzb.txt
```

---

## ⚡ Usage Examples

### Hydra

```
hydra -l admin -P /usr/share/wordlists/rockyou_uzb.txt target ssh
```

### Hashcat

```
hashcat -m 0 hash.txt /usr/share/wordlists/rockyou_uzb.txt
```

---

## ⚠️ Disclaimer

Bu wordlist **faqat security research va penetration testing** uchun.

Noqonuniy foydalanish uchun javobgarlik foydalanuvchiga tegishli.

---

## 👨‍💻 Author

Maintained by **Yescrypt**

Security Research | Wordlists | Pentesting Tools
