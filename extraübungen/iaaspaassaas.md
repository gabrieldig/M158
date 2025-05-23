# Analyse: Vergleich von IaaS, PaaS, SaaS und On-Premises

## 1. Überblick über die beiden Grafiken

### Grafik 1 (`iaas-paas-saas-diagram.png`)
- **Darstellung**: Balkendiagramm mit mehreren IT-Schichten
- **Perspektive**: Verantwortungsverteilung (Self vs. Provider)
- **Farbkodierung**:
  - Blau: Selbst gemanaged  
  - Rot: Provider gemanaged 
- **Schichten**: Anwendungen, Daten, Laufzeit, Middleware, OS, Virtualisierung, Server, Storage, Netzwerk
![IaaSPaaSSaaS](/extraübungen/iaas-paas-saas-diagram.png)
### Grafik 2 
- **Fokus**: Verantwortung nach Themenbereichen (z. B. Identität, Geräte, physisches Rechenzentrum)
- **Darstellung**: Matrix mit Kunden-, Microsoft- und geteilten Zuständigkeiten
- **Farben**:
  - Dunkelblau = Kunde
  - Hellblau = Microsoft
  - Schraffiert = geteilte Verantwortung
![Shared-Responsibility](/extraübungen/shared-responsibility.svg)
---

## 2. Gemeinsamkeiten


- Beide zeigen die Verlagerung von Verantwortung vom Kunden zum Cloud-Anbieter, je weiter man sich in Richtung SaaS bewegt.
- Beide differenzieren klar zwischen den Cloud-Modellen: On-Prem, IaaS, PaaS, SaaS.
- Verdeutlichen, dass vollständige Verantwortung nur bei On-Premises liegt.
---

## 3. Unterschiede

| Aspekt  | Grafik 1 | Grafik 2  |
|---------|----------|-----------|
| **Darstellungsform** | Technisches Schichtmodell | Thematische Verantwortungsmatrix|
| **Fokus** | Infrastruktur-Layer und technische Zuständigkeiten | Sicherheit, Compliance, Identitäten etc. |
| **Verantwortungstypen**| You vs Service Provider| Customer & Microsoft & Shared |
| **Detailgrad**| 9 technische Layer | 10 Verantwortungsbereiche |
| **Einsatzgebiet**  | IT-Architektur, Infrastrukturplanung | Sicherheit, Compliance, Risikoanalyse |

---

## 4. Interpretation und Verbindung

- **Grafik 1** eignet sich zur Darstellung der technischen Verantwortlichkeit im Team
- **Grafik 2** hebt die organisatorischen und sicherheitsrelevanten Aspekte hervor.
- Beide Grafiken zeigen komplementäre Perspektiven:
  - **Grafik 1** = *Was* verwaltet wird
  - **Grafik 2** = *Wer* dafür verantwortlich ist – differenziert nach Art der Veranjtwortung 

### Kombinierte Nutzung:
- In einem IT-Konzept können beide Modelle genutzt werden:
  - **Grafik 1** zur Definition interner Zuständigkeiten
  - **Grafik 2** zur Darstellung externer Verantwortlichkeiten im Rahmen von SLAs oder Verträgen

---

## 5. Fazit

Die Grafiken sind Grundätzlich sehr ähnlich, jedoch haben sie auch ihre Eigenen eigenscahften.
- **Grafik 1** ist ideal zur technischen Einordnung und Ressourcenplanung
- **Grafik 2** ist notwendig für rechtliche, sicherheitsrelevante und strategische Überlegungen

---
