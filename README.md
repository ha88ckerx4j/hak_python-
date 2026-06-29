# 🥷 Hak Python - Security & Ethical Hacking Toolkit

<div align="center">

![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-red?style=flat-square)
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=flat-square)

**ابزار جامع امنیتی و هکینگ اخلاقی برای متخصصین امنیت سایبری**

[English](#english) • [فارسی](#فارسی)

</div>

---

## 📚 فارسی

### 🎯 درباره پروژه

**Hak Python** یک کتابخانه جامع و قدرتمند برای:
- 🔍 تست نفوذی و Penetration Testing
- 🛡️ آزمایش امنیتی و Vulnerability Assessment
- 🔐 تحلیل و شناسایی نقاط ضعف
- ⚙️ ابزارهای هکینگ اخلاقی

> **نکته اهم:** این ابزار **فقط برای اهداف آموزشی و قانونی** استفاده شود.

### 🚀 ویژگی‌های اصلی

- ✅ کد متن‌باز و قابل‌توسعه
- ✅ ابزارهای امنیتی پیشرفته
- ✅ Documentation کامل فارسی
- ✅ مثال‌های عملی
- ✅ پشتیبانی فعال

### 📦 نصب

```bash
# Clone کردن
git clone https://github.com/ha88ckerx4j/hak_python-.git
cd hak_python-

# نصب dependency‌ها
pip install -r requirements.txt

# یا
pip install .
```

### 🔧 راهنمای سریع

```python
from hak_python import SecurityTester

# ایجاد instance
tester = SecurityTester()

# تست امنیتی
result = tester.scan_target("target_url")
print(result)
```

### 📖 مثال‌های بیشتر

```python
# Vulnerability Scanning
from hak_python import VulnScanner

scanner = VulnScanner()
vuln = scanner.check_sql_injection("target_url")

# Port Scanning
from hak_python import PortScanner

ps = PortScanner()
ports = ps.scan("192.168.1.1", range(1, 1000))
```

### 🛠️ ابزارهای موجود

| ابزار | توضیح |
|------|-------|
| **Port Scanner** | اسکن پورت‌های باز |
| **Vuln Detector** | تشخیص آسیب‌پذیری‌ها |
| **Payload Generator** | تولید payload برای تست |
| **Encryption Tools** | ابزارهای رمزنگاری |
| **Log Analyzer** | تحلیل لاگ‌ها |

### 📝 ساختار پروژه

```
hak_python-/
├── hak_python/
│   ├── __init__.py
│   ├── scanner/
│   ├── payloads/
│   ├── encryption/
│   └── utils/
├── tests/
├── examples/
├── docs/
├── requirements.txt
└── README.md
```

### 🤝 مشارکت

ما از مشارکت‌های شما استقبال می‌کنیم! 

1. Fork کنید
2. Branch جدید بسازید: `git checkout -b feature/new-feature`
3. تغییرات را commit کنید: `git commit -m 'Add new feature'`
4. Push کنید: `git push origin feature/new-feature`
5. Pull Request بسازید

### ⚠️ تذکر قانونی

⚠️ **مهم:** این ابزار **فقط** برای:
- ✅ تحقیقات امنیتی
- ✅ آموزش و یادگیری
- ✅ تست سیستم‌های خودتان
- ✅ سیستم‌هایی که اجازه دارید

استفاده کنید. هرگونه استفاده غیرقانونی **مسئولیت صاحب استفاده** است.

### 📧 ارتباط

- 👤 GitHub: [@ha88ckerx4j](https://github.com/ha88ckerx4j)
- 📱 Issues: [GitHub Issues](https://github.com/ha88ckerx4j/hak_python-/issues)

### 📜 لایسنس

MIT License - [مشاهده فایل](LICENSE)

---

## English

### 🎯 About Project

**Hak Python** is a comprehensive toolkit for:
- 🔍 Penetration Testing
- 🛡️ Vulnerability Assessment
- 🔐 Security Analysis
- ⚙️ Ethical Hacking Tools

> **Important:** Use this tool only for **legal and educational purposes**.

### 🚀 Features

- ✅ Open Source & Extensible
- ✅ Advanced Security Tools
- ✅ Complete Documentation
- ✅ Practical Examples
- ✅ Active Support

### 📦 Installation

```bash
git clone https://github.com/ha88ckerx4j/hak_python-.git
cd hak_python-
pip install -r requirements.txt
```

### 🔧 Quick Start

```python
from hak_python import SecurityTester

tester = SecurityTester()
result = tester.scan_target("target_url")
```

### 🛠️ Available Tools

| Tool | Description |
|------|-------------|
| **Port Scanner** | Scan open ports |
| **Vulnerability Detector** | Detect vulnerabilities |
| **Payload Generator** | Generate test payloads |
| **Encryption** | Encryption utilities |
| **Log Analyzer** | Analyze logs |

### 🤝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push and create a Pull Request

### ⚠️ Legal Notice

⚠️ **Important:** This tool is for:
- ✅ Security Research
- ✅ Educational Purposes
- ✅ Testing Your Own Systems
- ✅ Authorized Testing Only

Illegal use is **prohibited**.

### 📜 License

MIT License

---

<div align="center">

**Made with ❤️ by [ha88ckerx4j](https://github.com/ha88ckerx4j)**

⭐ اگه پسندیدی، ستاره بزن! ⭐

</div>
