# 🔥 Vulnerabilità del Coges MyKey Srix4K – Documentazione di Sicurezza

**🚨 AVVISO: Questo repository è destinato esclusivamente a scopi educativi e di ricerca sulla sicurezza. L'accesso non autorizzato, la modifica o l'uso fraudolento dei sistemi di pagamento sono ILLEGALI. L'obiettivo di questa documentazione è sensibilizzare i professionisti della sicurezza sulle vulnerabilità del sistema Coges MyKey.**

---

## 📖 Indice

- [🇬🇧 English](#-English)
- [🇮🇹 Italiano](#-Italiano)
- [🇫🇷 Français](#-Français)
- _[🇪🇸 Español](#-Español) traduction needed_
- _[🇷🇺 Русский](#-Pусский) traduction needed_
- [📌 Gruppi Telegram](#-Gruppi-Telegram)

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
# 🇫🇷 Français

### ⚡ Introduction
Ce référentiel documente les vulnérabilités du système de paiement **Coges MyKey**, plus précisément dans **MyKey avec les puces NFC Srix4K**. L'objectif est de mettre en évidence les faiblesses de sécurité dans les **transactions de distributeurs automatiques sans espèces** et d'encourager les fournisseurs à **adopter des mesures de sécurité plus strictes**.

La recherche est basée sur **Flipper Zero (Unleashed 0.65)** et vise à **documenter et signaler les activités frauduleuses**.

### 🛠️ Fonctionnement de MyKey
Le système **Coges MyKey** est une **clé NFC prépayée** pour les distributeurs automatiques. Il fonctionne sur **ISO14443-2 Type B** et stocke :
- **Crédits utilisateur**
- **Historique des transactions**
- **Données d'identification du fournisseur**

Les données sont protégées par des **puces NFC ST25TB04K** avec **EEPROM crypté et compteurs 32 bits** pour empêcher les modifications non autorisées.

### 🔍 Analyse des vulnérabilités
- Le **Flipper Zero** peut **lire et vider les données NFC** depuis MyKey.
- La puce **ST25TB04K contient un solde de crédit** en blocs EEPROM.
- **Le clonage de MyKey** sur des tags NFC vierges est possible.
- **La modification du crédit** peut s'effectuer via **des techniques de bypass de checksum**.


### 🛡️ Recommandations de sécurité
✅ **Mises à jour du Firmware**  
✅ **Détection d'anomalies pour fraude**  
✅ **Protocoles de chiffrement plus stricts**  
✅ **Éléments sécurisés avec protection contre les manipulations frauduleuses**  

🚀 **Les systèmes de paiement Cashless doivent évoluer pour empêcher leur exploitation.**

---

# 📌 Gruppi Telegram
📌 **Gruppo Principale:** [Unisciti Qui](https://t.me/joinchat/PjejVk6LbnKu-O7zQMEM3Q)  
📌 **Aggiornamenti Software:** [Mikai Downloads](https://t.me/mikaidownload)  
📌 **Hub di Hacking:** [Mikai App](https://t.me/mikai_app)  
