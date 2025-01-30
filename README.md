# mikai
POC FOR HACK COGES MYKEY WITH FLIPPER ZERO
# 🔥 MyKey Strix4K Vulnerability Documentation

**🚨 WARNING: This repository is for educational and security research purposes only. Unauthorized access, modification, or fraudulent use of payment systems is ILLEGAL. The goal of this project is to document vulnerabilities in the Coges MyKey system and raise awareness among security professionals.**

---

## 📖 Table of Contents

- [English 🇬🇧](#-english)
- [Italiano 🇮🇹](#-italiano)
- [Español 🇪🇸](#-español)
- [Français 🇫🇷](#-français)
- [Русский 🇷🇺](#-русский)

---

## 🇬🇧 **#English**

### ⚡ Introduction
This repository documents vulnerabilities in the **Coges MyKey** cashless payment system, specifically **MyKey with Strix4K NFC chips**. The goal is to highlight weaknesses in **cashless vending machine transactions** and encourage vendors to implement **stronger security measures**.

Research is based on **Flipper Zero (Unleashed 0.65)** and is publicly available to **report and document fraudulent activities**.

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

### 🚨 Telegram Groups Involved
📌 **Main Group:** [https://t.me/joinchat/PjejVk6LbnKu-O7zQMEM3Q](https://t.me/joinchat/PjejVk6LbnKu-O7zQMEM3Q)  
📌 **Software Updates:** [https://t.me/mikaidownload](https://t.me/mikaidownload)  
📌 **Hacking Hub:** [https://t.me/mikai_app](https://t.me/mikai_app)  

### 🛡️ Security Recommendations
✅ **Firmware updates**  
✅ **Anomaly detection for fraud**  
✅ **Stronger encryption protocols**  
✅ **Secure elements with tamper protection**  

🚀 **Cashless payment systems must evolve to prevent exploitation.**

---

## 🇮🇹 **#Italiano**

### ⚡ Introduzione
Questo repository documenta le vulnerabilità nel sistema di pagamento **Coges MyKey**, in particolare nelle chiavi NFC **Strix4K**. L'obiettivo è evidenziare le debolezze nei pagamenti cashless per i distributori automatici.

Questa ricerca è basata su **Flipper Zero (Unleashed 0.65)** e serve per **documentare le attività fraudolente**.

### 🛠️ Come Funziona MyKey
Le chiavi **MyKey** operano su **NFC (ISO14443-2 Type B)** e contengono:
- **Crediti prepagati**
- **Storico delle transazioni**
- **Dati del venditore**

Le informazioni sono protette dal **chip ST25TB04K** con EEPROM crittografata e **contatori a 32 bit**.

### 🔍 Analisi della Vulnerabilità
- **Flipper Zero** può **leggere e clonare** le chiavi MyKey.
- Il **credito è memorizzato nei blocchi EEPROM**.
- **Bypass dei checksum** permette di alterare i crediti.

### 🚨 Canali Telegram Coinvolti
📌 **Gruppo principale:** [https://t.me/joinchat/PjejVk6LbnKu-O7zQMEM3Q](https://t.me/joinchat/PjejVk6LbnKu-O7zQMEM3Q)  

### 🛡️ Raccomandazioni di Sicurezza
✅ **Aggiornamenti firmware**  
✅ **Monitoraggio delle anomalie**  
✅ **Protocolli di crittografia avanzati**  

🚀 **I sistemi di pagamento devono evolversi per rimanere sicuri.**

---

## 🇪🇸 **#Español**

### ⚡ Introducción
Este repositorio documenta vulnerabilidades en el sistema de pago **Coges MyKey**, específicamente en **MyKey con chips NFC Strix4K**.

La investigación se basa en **Flipper Zero (Unleashed 0.65)** y está disponible públicamente para **reportar fraudes**.

### 🛠️ Cómo Funciona MyKey
Las llaves **MyKey** utilizan **NFC (ISO14443-2 Type B)** y almacenan:
- **Créditos prepagados**
- **Historial de transacciones**
- **Datos del proveedor**

Los datos están protegidos con **chips ST25TB04K**, EEPROM cifrada y **contadores de 32 bits**.

### 🔍 Análisis de Vulnerabilidad
- **Flipper Zero** puede **leer y clonar** MyKey.
- **Los créditos se almacenan en la EEPROM**.
- **Modificación de créditos** mediante **bypass de checksums**.

### 🚨 Canales de Telegram Involucrados
📌 **Grupo principal:** [https://t.me/joinchat/PjejVk6LbnKu-O7zQMEM3Q](https://t.me/joinchat/PjejVk6LbnKu-O7zQMEM3Q)  

### 🛡️ Recomendaciones de Seguridad
✅ **Actualizaciones de firmware**  
✅ **Detección de fraudes**  
✅ **Mayor seguridad NFC**  

🚀 **Los sistemas de pago sin efectivo deben adaptarse a las amenazas.**

---

## 🇫🇷 **#Français**

### ⚡ Introduction
Ce dépôt documente les vulnérabilités du système de paiement **Coges MyKey**, en particulier des clés NFC **Strix4K**.

Basé sur **Flipper Zero (Unleashed 0.65)**, ce projet vise à **documenter les fraudes**.

### 🛠️ Comment Fonctionne MyKey
Les clés **MyKey** utilisent **NFC (ISO14443-2 Type B)** et stockent:
- **Crédits prépayés**
- **Historique des transactions**
- **Données du vendeur**

Les données sont protégées par **ST25TB04K** avec EEPROM chiffrée et **compteurs 32 bits**.

### 🔍 Analyse de Vulnérabilité
- **Flipper Zero** permet **la lecture et la copie** des MyKey.
- **Les crédits sont stockés dans l’EEPROM**.
- **Les crédits peuvent être modifiés via un contournement des checksums**.

### 🚨 Groupes Telegram Impliqués
📌 **Groupe principal:** [https://t.me/joinchat/PjejVk6LbnKu-O7zQMEM3Q](https://t.me/joinchat/PjejVk6LbnKu-O7zQMEM3Q)  

### 🛡️ Recommandations de Sécurité
✅ **Mises à jour du firmware**  
✅ **Détection des fraudes**  
✅ **Protocoles de sécurité avancés**  

🚀 **Les systèmes de paiement doivent être sécurisés contre les menaces.**

---

## 🇷🇺 **#Русский**

### ⚡ Введение
Этот репозиторий документирует уязвимости системы **Coges MyKey** с **чипами NFC Strix4K**.

Исследование основано на **Flipper Zero (Unleashed 0.65)**.

### 🔍 Анализ уязвимости
- **Flipper Zero** позволяет **считывать и клонировать** MyKey.
- **Данные о балансе хранятся в EEPROM**.
- **Возможность обхода контрольных сумм**.

### 🚀 **Защита**
✅ **Обновления прошивки**  
✅ **Выявление мошенничества**  

🚀 **Оплата безналичным способом должна оставаться безопасной.**
