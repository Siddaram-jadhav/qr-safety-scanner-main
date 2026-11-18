# QR Safety Scanner 🛡️

### Scan Smart. Stay Safe.

QR Safety Scanner is an Android-based cybersecurity application that scans QR codes, extracts embedded URLs, and analyzes them for suspicious patterns before users open them.

## 📌 About the Project

QR codes are widely used for payments, websites, restaurant menus, and information sharing. However, attackers can create malicious QR codes that redirect users to phishing websites.

QR Safety Scanner helps users identify potentially suspicious links by analyzing URLs and displaying security warnings before opening them.

## ✨ Features

- 📷 Real-time QR Code Scanning using the mobile camera.
- 🔗 Automatic URL Extraction.
- 🔒 HTTPS Security Check.
- 🌐 IP Address Detection.
- ⚠️ URL Shortener Detection.
- 🔍 Suspicious Keyword Detection.
- 🟢🟡🔴 Risk Classification (Low Risk, Suspicious, High Risk).
- 📊 Risk Score Display.
- 🚫 Open Anyway and Don't Open Options.
- 📜 Scan History.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Kotlin | Android development |
| Android Studio | Development environment |
| Jetpack Compose | User interface |
| Google ML Kit | QR code scanning |
| CameraX | Camera integration |
| SQLite | Local scan history |
| Gradle | Build management |

## ⚙️ How It Works

1. Open the QR Safety Scanner application.
2. Scan a QR code using the mobile camera.
3. Extract the URL from the QR code.
4. Analyze the URL for suspicious patterns.
5. Display the security verdict and risk score.
6. Choose whether to open or reject the link.
7. View previously scanned links in scan history.

## 🔍 Security Checks

The application checks:

- Whether the URL uses HTTPS or HTTP.
- Whether the URL contains an IP address.
- Whether the URL uses a shortening service.
- Whether suspicious keywords are present.
- Whether the URL has unusual patterns.

**Note:** The application uses rule-based URL analysis. It identifies potential warning signs but cannot guarantee that a website is completely safe.

## 🚀 Installation

1. Clone this repository.
2. Open the project in Android Studio.
3. Allow Gradle synchronization to complete.
4. Connect an Android device.
5. Run the application.

## 🎯 Project Objective

The main objective is to improve QR code security awareness and help users identify potentially harmful links before visiting unknown websites.

## 🔮 Future Enhancements

- Integration with VirusTotal API.
- Machine learning-based phishing detection.
- Lookalike domain detection.
- Advanced threat intelligence.
- Improved URL reputation analysis.

## 👨‍💻 Developer

**Siddaram Jadhav**

Project: QR Safety Scanner

---

⭐ If you find this project useful, consider giving the repository a star!
