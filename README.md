# SuperScannerPro v2

## Syfte / Mål
Detta projekt syftar till att skapa ett script som samlar in viktig systeminformation från Linux-miljöer.  
Målet är att underlätta säkerhetsanalyser genom att snabbt ge en översikt över systemets aktuella status och identifiera potentiella felkonfigurationer som kan leda till **Privilege Escalation (CWE-269)**.

---

## Funktion
Scriptet samlar in följande information:

- **Systeminformation**  
  - OS-version  
  ....

> **INFO:**  
> All insamlad information sparas i en CSV textfil med namnet:  
> `[DATE]-[HOSTNAME]-VSCAN-RESULT.TX`  

---

## Systemkrav
- Linux-baserad miljö (t.ex. Ubuntu, Debian, Kali Linux)  
...

Scriptet kontrollerar automatiskt användarens privilegier innan det startar.

---

## Instruktioner för körning

```bash
git clone https://github.com/ditt-användarnamn/linux-info-collector.git
cd linux-info-collector
chmod +x info_collector.py
./info_collector.py
```

## Flaggor

- `-h` eller `--help` – Visar hjälptext  
- `-v` eller `--version` – Visar version och utvecklare  

---

## Screenshot / Film

Länka eller infoga en skärmdump eller film som visar scriptet när det körs.

**Exempel:**

---

## Flödesschema

Länka eller infoga flödesschemat som visar scriptets logik.

**Exempel:**

