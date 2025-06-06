# Projektdokumentation – M158 LB2 <br>WordPress-Migration

## Übersicht
# Projektdokumentation – Webserver-Projekt

Diese Dokumentation ist nach den Aufgaben (1–14) gegliedert. Jede Aufgabe ist in drei Phasen unterteilt. Bitte tragen Sie Ihre Ergebnisse jeweils unter den entsprechenden Abschnitten ein.

## Extra Übungen
- [IaaS PaaS SaaS](/extraübungen/iaaspaassaas.md)

- [pfade](/extraübungen/Gabriel.txt)

---

## Aufgabe 1 – Projektplan erstellen
```mermaid
gantt
    title Projektplan Software-Migration M158 – Gabriel
    dateFormat  YYYY-MM-DD
    excludes    weekend
    axisFormat  %d.%m.%Y

    section Entwicklung & Planung
    Dokumentation / Arbeitsjournal :active, 2025-02-23, 71d
    Projektplanung                 :active, 2025-02-23, 7d

    section Phase 2
    AWS                            :done, 2025-03-02, 7d
    Snapshot 1                     :milestone, 2025-03-09, 0d
    OS-Konfiguration               :done, 2025-03-09, 7d

    section Phase 3
    Snapshot 2                     :milestone, 2025-03-16, 0d
    Webserver / DB                 :done, 2025-03-16, 7d
    Snapshot 3                     :milestone, 2025-03-23, 0d
    V-Host                         :done, 2025-03-23, 7d
    Snapshot 4                     :milestone, 2025-03-30, 0d
    DNS-Server                     :done, 2025-03-30, 7d
    Snapshot 5                     :milestone, 2025-04-06, 0d
    Migr-WP-Files                  :done, 2025-04-06, 7d
    Migr-WP-DB                     :done, 2025-04-13, 7d
    WP-Config                      :done, 2025-04-20, 7d
    section Phase 4 - Migration
    Migration :todo 2025-04-20, 7d
    section Phase 5 – Testing
    Snapshot 6                     :milestone, 2025-04-27, 0d
    Diverse Tests                  :done, 2025-04-27, 7d
    Site-Health-Check              :done, 2025-05-04, 1d

```

---

## Aufgabe 2 – Architekturdiagramm erstellen

 
### Stufe 3

![Architekturdiagramm](image-1.png)---

## Aufgabe 3 – AWS-Umgebung einrichten

### Stufe 1

Zu beginn habe ich einen SSH-Keypair erstellt, und denn heruntergeladen, dann habe ich jedesmal, wenn ich eine EC2 Instanz erstelle, den SSH-Key ausgewählt und somit denn SSH-Zugriff gemacht,

### Stufe 2
Ich habe die IP-Addressen, wie im Architekturdiagramm, korrekt zugewiesen, und auch die notweniden Ports geöffnet   
![alt text](image-2.png)
### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 4 – DNS-Konfiguration

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 5 – Webserver konfigurieren

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 6 – PHP einrichten

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 7 – MySQL/MariaDB aufsetzen

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 8 – Web-Datenbanktool (phpMyAdmin/Adminer)

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 9 – FTP-Zugang einrichten

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 10 – WordPress migrieren

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 11 – Backup-Konzept umsetzen

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 12 – Testing der Webapplikation

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 13 – Deployment automatisieren

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

## Aufgabe 14 – Docker verwenden

### Stufe 1

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 2

Fügen Sie hier Ihre Ergebnisse ein

### Stufe 3

Fügen Sie hier Ihre Ergebnisse ein

---

