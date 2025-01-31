# 🔥 Vulnerabilità del Coges MyKey Srix4K – Documentazione di Sicurezza

**🚨 AVVISO: Questo repository è destinato esclusivamente a scopi educativi e di ricerca sulla sicurezza. L'accesso non autorizzato, la modifica o l'uso fraudolento dei sistemi di pagamento sono ILLEGALI. L'obiettivo di questa documentazione è sensibilizzare i professionisti della sicurezza sulle vulnerabilità del sistema Coges MyKey.**

---

## 📖 Indice

- [🇬🇧 English](#english)
- [🇮🇹 Italiano](#italiano)
- [🇪🇸 Español](#español)
- [🇫🇷 Français](#français)
- [🇷🇺 Русский](#русский)
- [📌 Gruppi Telegram](#gruppi-telegram)

---

## 🇬🇧 English

### ⚡ Introduction
This repository documents vulnerabilities in the **Coges MyKey** cashless payment system, specifically in **MyKey with Srix4K NFC chips**. The goal is to highlight security weaknesses in **cashless vending machine transactions** and encourage vendors to **adopt stronger security measures**.

Research is based on **Flipper Zero (Unleashed 0.65)** and aims to **document and report fraudulent activities**.

### 🛠️ How MyKey Works
The **Coges MyKey** system is a **prepaid NFC key** for vending machines. It operates on **ISO14443-2 Type B** and stores:
- **User credits**
- **Transaction history**
- **Vendor identification data**

Data is protected by **ST25TB04K NFC chips** with **encrypted EEPROM and 32-bit counters** to prevent unauthorized modifications.

### 🔍 Vulnerability Analysis
- **Flipper Zero** can **read and dump NFC data** from MyKey.
- The **ST25TB04K chip contains credit balance** in EEPROM blocks.
- **Cloning MyKey** onto blank NFC tags is possible.
- **Credit modification** can occur via **checksum bypass techniques**.

### 🛡️ Security Recommendations
✅ **Firmware updates**  
✅ **Anomaly detection for fraud**  
✅ **Stronger encryption protocols**  
✅ **Secure elements with tamper protection**  

🚀 **Cashless payment systems must evolve to prevent exploitation.**

---

## 🇮🇹 Italiano

### ⚡ Introduzione
Questo repository documenta le vulnerabilità del sistema di pagamento **Coges MyKey**, in particolare delle chiavi NFC **Srix4K**. L'obiettivo è evidenziare le debolezze nei pagamenti cashless per i distributori automatici e incoraggiare i fornitori a implementare misure di sicurezza più robuste.

La ricerca si basa su **Flipper Zero (Unleashed 0.65)** e mira a **documentare e segnalare attività fraudolente**.

### 🛠️ Come Funziona MyKey
Il sistema **Coges MyKey** è una **chiave NFC prepagata** per distributori automatici. Funziona su **ISO14443-2 Tipo B** e memorizza:
- **Crediti dell'utente**
- **Storico delle transazioni**
- **Dati di identificazione del fornitore**

I dati sono protetti da **chip NFC ST25TB04K** con **EEPROM crittografata e contatori a 32 bit** per prevenire modifiche non autorizzate.

### 🔍 Analisi della Vulnerabilità
- **Flipper Zero** può **leggere e scaricare i dati NFC** da MyKey.
- Il **chip ST25TB04K contiene il saldo dei crediti** nei blocchi EEPROM.
- È possibile **clonare MyKey** su tag NFC vuoti.
- La **modifica dei crediti** può avvenire tramite **tecniche di bypass del checksum**.

### 🛡️ Raccomandazioni di Sicurezza
✅ **Aggiornamenti del firmware**  
✅ **Rilevamento di anomalie per frodi**  
✅ **Protocolli di crittografia più robusti**  
✅ **Elementi sicuri con protezione anti-manomissione**  

🚀 **I sistemi di pagamento cashless devono evolversi per prevenire sfruttamenti.**

---

## 📌 Gruppi Telegram
📌 **Gruppo Principale:** [Unisciti Qui](https://t.me/joinchat/PjejVk6LbnKu-O7zQMEM3Q)  
📌 **Aggiornamenti Software:** [Mikai Downloads](https://t.me/mikaidownload)  
📌 **Hub di Hacking:** [Mikai App](https://t.me/mikai_app)  
