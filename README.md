## Hi, ich bin Tobias 👋

Angehender **Wirtschaftsinformatiker (staatl. anerkannt)** aus **Heidelberg** mit Praxisfokus auf **KI/LLM** und **Full-Stack-Entwicklung**. Ich baue echte, nachvollziehbare Lösungen — von RAG-Systemen über MCP-Server bis zu produktiv genutzten Web-Apps. Kurz gesagt: KI, die auch im Unternehmen bestehen kann — on-prem, DSGVO-konform, wartbar.

- 🔭 **Aktueller Fokus:** Retrieval-Augmented Generation, LLM-Anwendungen, On-Prem-/DSGVO-KI, Prozessautomatisierung
- 🛠️ **Stack:** Python · TypeScript · Next.js · React · FastAPI · Docker · PostgreSQL · Ollama · ChromaDB/Qdrant · MCP
- 🎯 **Ziel:** Einstieg als AI Engineer / KI- & Automation-Consultant im Raum Rhein-Neckar (ab Okt. 2026)

---

### 📌 Öffentliche Projekte

**[notebooklm-clone](https://github.com/ikonclast/notebooklm-clone)** — dokumentengestützter KI-Assistent (RAG)
Antworten ausschließlich aus eigenen Dokumenten, mit Quellen-Zitaten & Confidence, komplett lokal/DSGVO-konform (Ollama). Next.js + FastAPI, ChromaDB, Docker Compose.
→ *Öffentliche, datenschutzsaubere Demonstration desselben Ansatzes, den ich im Praktikum als on-prem Ticket-Assistenten (bge-m3 · Qdrant · Ollama) produktiv erprobt habe.*

**[Rechnungserkennung](https://github.com/ikonclast/Rechnungserkennung)** — DSGVO-konforme Rechnungsextraktion (§14 UStG)
Belegdaten deterministisch statt per LLM extrahiert — mit Confidence-Scoring, §14-Validierung, Human-in-the-Loop-Review-UI und DATEV-Export. Docling + FastAPI + PostgreSQL/MinIO, self-hosted.
→ *Prozessautomatisierung für die Buchhaltung: auditierbar und ohne Halluzinationsrisiko bei Beträgen — bewusst kein Sprachmodell über den gebuchten Zahlen.*

**[bob_der_botmeister](https://github.com/ikonclast/bob_der_botmeister)** — Plattform für quantitative Handelsstrategien
Generierung, Backtesting, Monte-Carlo- & Walk-Forward-Validierung, Paper-Trading. Python, Docker, freqtrade.

**[Rezepte-Api](https://github.com/ikonclast/Rezepte-Api)** — REST-API-Backend (Abschlussprojekt)
Laravel, MySQL, Token-Auth (Sanctum), OpenAPI-Doku — Backend zur zugehörigen Android-App.

---

### 🏢 Ausgewählte Praxisprojekte

*Umgesetzt während meines Praktikums bei einem IT-Systemhaus im Raum Rhein-Neckar. Der Code ist intern und nicht öffentlich; ich beschreibe daher Kontext, Technik und Ergebnis. Details gerne im Gespräch.*

- **On-Prem RAG-Assistent** — lokaler Retrieval-Chat über einen internen Ticket-Bestand, der Lösungsvorschläge liefert. Harte Vorgabe: läuft komplett on-prem, Inhalte verlassen das Gerät nie. Stack (bge-m3 · Qdrant · Ollama) auf CPU-only validiert, GPU folgt. *(Öffentlicher Zwilling: notebooklm-clone.)*
- **Compliance-Self-Assessment-Web-App** — full-stack entwickelt und produktiv gesetzt: TypeScript, Prisma, PostgreSQL, eigener Docker-Stack je Umgebung. Inkl. Sicherheits-Härtung (Cookie-Auth, CSRF, Rate-Limiting, Login-Lockout, Tenant-Isolation, Audit-Log) und abgesichertem Live-Cutover.
- **4 eigene MCP-Server** — Model-Context-Protocol-Server (u. a. Datei-Sandbox, read-only DB-Zugriff) mit Wrapper- und Berechtigungs-Doppelschicht.
- **Unternehmensweiter KI-Rollout + Automatisierung** — KI-Assistenz auf zwei Oberflächen konzipiert und begleitet, inkl. Schulungsreihe fürs technische Team und Entwurf einer KI-Nutzungsrichtlinie. Prozess-Automatisierung mit Power Automate / n8n und Microsoft 365 / Graph.
- **DevOps im Alleinbetrieb** — Linux-Server mit ~10 produktiven Docker-Containern hinter Nginx-Reverse-Proxy (TLS), backup-first Auto-Updater per Cron, alles als versionierte Infrastruktur-Konfiguration.

---

### 🧭 Arbeitsweise

Gründlich statt schnell-und-brüchig: keine Mock-Daten, keine Quick-Fixes, alles versioniert und mit echtem Output validiert. Wichtige Änderungen lasse ich vor dem Go-Live gezielt gegenprüfen, und ich baue bewusst so, dass eine Lösung auch ohne mich wartbar bleibt. Datenschutz ist Design-Prinzip, nicht Nachgedanke.

---

### 📫 Kontakt

Am besten über [LinkedIn](https://www.linkedin.com/in/tobias-hinze) — Bewerbungsunterlagen auf Anfrage.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
