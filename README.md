# 🔥 Dexterceptor — Universal Interceptor for Requests and Runtime Calls on Android

Dexterceptor is a powerful tool for developers and researchers designed to **intercept HTTP(S) requests directly inside Android applications**, even when they are obfuscated.  
It is based on **Xposed / LSPosed** and deeply integrates with **OkHttp**, featuring a built-in **SSL bypass**, a rule system, and an extensible architecture for future interception types.

---

## ✨ Key Features

### 🔗 OkHttp 3/4 Request Interception
Dexterceptor integrates into the application's networking stack and provides real-time access to:

- full request URL  
- request and response headers  
- request and response bodies  
- automatic **cURL generation** for Windows CMD, PowerShell, and Unix shell environments  

---

## 🧬 Request and Response Modification Rules

A flexible rule system enables automatic transformation of network traffic:

- header replacement  
- URL rewriting  
- request and response body modification  

---

## 🔓 Built-in SSL Pinning Bypass

Dexterceptor can disable:

- certificate pinning (TrustKit, OkHttp PinVerifier, Conscrypt, OpenSSL)  
- strict certificate validation  
- hostname verification errors  

This enables full visibility of traffic in external tools such as:

- **Charles**, **Fiddler**, **Proxyman**, **BurpSuite**

---

## 🧰 Native Runtime Call Inspector (Upcoming)

The architecture is designed for future extensibility.  
Planned capabilities include interception of:

- method calls such as `setText()`  
- arbitrary Java/Kotlin methods  
- SQLite I/O  
- IPC calls  
- SharedPreferences access  
- Dex-level functions, even in heavily obfuscated applications  

Dexterceptor is evolving into a **universal runtime inspector for Android applications**.

---

## 🖥️ UI Capabilities

- Darcula-style dark theme  
- real-time logging without delays   
- JSON syntax highlighting   
- filtering, search, sorting  
- rule editor with regex highlighting  

---

## 🏗️ Project Status

- ✔️ OkHttp interception  
- ✔️ HTTP data viewing and storage  
- ✔️ request/response modification  
- ✔️ SSL bypass  
- ✔️ EventBusRx for transferring large logs between processes  
- ⏳ system method interception (`setText`, SQLite, Binder)   
- ⏳ advanced rule/script editor

- ## 📸 Screenshots




<img width="324" height="693" alt="image" src="https://github.com/user-attachments/assets/9e59d8c0-64c2-4354-bf7c-01f2a46793e3" /> <img width="324" height="693" alt="image" src="https://github.com/user-attachments/assets/1f7f3a7d-e81e-4606-8ccc-5d8b67b7df0b" />

<img width="324" height="693" alt="image" src="https://github.com/user-attachments/assets/bb4571fb-fc34-4488-b2c6-619e0cd4516b" /> <img width="324" height="693" alt="image" src="https://github.com/user-attachments/assets/1c2e1812-355a-47ba-bce0-6f23940cc2f0" />



### Spoofing

<img width="324" height="693" alt="image" src="https://github.com/user-attachments/assets/77e38a5e-1f95-4a24-b4b4-4fed996f3a69" /> <img width="324" height="693" alt="image" src="https://github.com/user-attachments/assets/838021fb-f2b5-47d5-9451-336dce8f246b" /> <img width="324" height="693" alt="image" src="https://github.com/user-attachments/assets/17c373c8-b0d4-494d-a6b0-518d11e55dc0" />
