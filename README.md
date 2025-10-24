# JAQUP – Java Automated Quality & Unit-testing Pipeline

Automatisiertes Test- und Code-Qualitäts-System für Java mit:
- GitHub Actions (CI/CD)
- Docker Containerisierung
- SonarQube Code-Analyse

## 🔧 Technologien
| Bereich         | Tool |
|----------------|------|
| Programmiersprache | Java 21 |
| Build-Tool | Maven |
| Tests | JUnit 5 |
| Code-Analyse | SonarQube |
| Pipelines | GitHub Actions |
| Container | Docker |

---

## 🚀 Lokales Setup

### 1️⃣ SonarQube starten

➡️ UI unter: http://localhost:9000  
Login (Standard): `admin / admin`

### 2️⃣ Java Build & Tests


---

## 🔍 CI/CD Pipeline

Das Repository enthält eine GitHub Actions Workflow-Datei:

**.github/workflows/ci.yml**
- Checkout Code
- Maven Build
- Automatisierte Tests
- SonarQube Scan
- Docker Build

SonarQube Token muss in GitHub gespeichert werden:

> `Settings` → `Secrets and variables` → `Actions`  
> → **SONAR_TOKEN**

---

## 🎯 Roadmap
- ✅ CI-Pipeline
- ✅ Docker + SonarQube
- ⬜ Test Coverage mit JaCoCo
- ⬜ Deployment-Optionen
- ⬜ Security-Scanning

---

## 📄 Lizenz
Siehe Datei **LICENSE**

