## Rodrigo Ernesto Aguilera Rodriguez

**System Engineer · Linux Infrastructure · Service Orchestration**
Zürich, Schweiz · open to System-Engineer / DevOps / SRE roles in ISP, hosting, infrastructure teams

### Was ich aktuell tue

Ich betreibe eigenverantwortlich einen produktiven Drei-Knoten-Cluster auf **Debian / Ubuntu 24.04 LTS** – seit über einem Jahr und parallel zur Anstellung im Hotel-Frontoffice. Alles selbst aufgebaut, selbst dokumentiert, selbst eskaliert.

```
                  Init7 Fiber7 X2 (25 Gbit/s)
                            │
              MikroTik CCR2004-1G-12S+2XS (Edge)
                            │
       ┌────────────────────┼────────────────────┐
       │                    │                    │
    Node A              Node B               Node C
   (Yoga, primary)    (Forge, executor)   (Acer, validator)
       │                    │                    │
       └──── Tailscale-Mesh + Custom-ACL ────────┘
                            │
              Docker-Compose · Redis · PostgreSQL (Supabase)
              Prometheus · Grafana · Loki · Qdrant · Meilisearch
              NATS · Verdaccio · eigene Docker-Registry
```

### Tech I work with daily

- **Linux:** Debian / Ubuntu LTS, systemd, journald, apt, AppArmor, SSH-Hardening
- **Netzwerk:** Tailscale-Mesh, MikroTik RouterOS, IPv6 Dual-Stack, DNS-Diagnose auf Kernel-Ebene
- **Services:** PostgreSQL · Redis · Prometheus · Grafana · Loki · Qdrant · Meilisearch · NATS · Verdaccio
- **Automation:** Bash (advanced), Node.js, ~360 eigene CLI-Tools, idempotente Reconciliation-Skripte (Puppet/Salt-Paradigma)
- **Containers:** Docker, Docker Compose, Container-Networking
- **ISP-Tools (in Lab-Aufbau):** BIND, PowerDNS, ISC DHCP / Kea, Postfix, Dovecot, Nginx, Apache
- **Languages:** Bash, Python, Node.js / TypeScript, Go, Rust (Grundlagen)

### Lernpfad 2026

- [ ] **LFCS** – Linux Foundation Certified SysAdmin
- [ ] **LPIC-1** – Linux Professional Institute Certification
- [ ] Puppet / Salt – produktive Erfahrung in Team-Setting

### Was sonst noch

- **6 Sprachen C1:** Spanisch (Muttersprache), Deutsch, Englisch, Französisch, Norwegisch, Portugiesisch
- **10+ Jahre Hotellerie** in Night-Audit und Front-Office (Hyatt, Holiday Inn, Thon, ibis budget, B&B) – direkte Vorbereitung auf Engineer-on-Duty-Rotation und 24/7-Schichtbetrieb
- **B-Bewilligung, Führerausweis Kat. B, eigenes Auto, verfügbar sofort**

### Kontakt

- E-Mail: **ronesto@hotmail.com**
- CV (öffentlich, kuratierte Version): siehe Repository [`cv`](https://github.com/R042160/cv)
- Live-Demo meiner Cluster-Infrastruktur per Screen-Sharing oder vor Ort: gerne im Gespräch

---

*Open Source, technische Tiefe vor Marketing, Netzneutralität, Community – das sind für mich keine Buzzwords, sondern Arbeitsweise.*
