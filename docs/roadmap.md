# Acme GmbH Homelab Roadmap

## Stage 1 — Server Preparation

### Goals
- Linux user management
- permissions model
- systemd basics

Status: COMPLETED

Status Date: 2026-07-02

---

## Stage 2 — First Service (hello)

### Goals
- systemd service
- bash script
- logging via journald

### Tickets
  - Ticket #0001 - Deploy first application service
  - Ticket #0002 - Deploy Apache Web Server
  
### Incidents
  - Incident #0001 - 203/Exec (missing traverse permission)
  - Incident #0002 - 403 Forbidden

Status: COMPLETED

Status Date: 2026-07-03

---

## Stage 3 — Database
- PostgreSQL installation
- users & roles
- simple schema

Status: NOT STARTED

---

## Stage 4 — Reverse Proxy
- nginx / apache
- routing to backend services

Status: NOT STARTED

---

## Stage 5 — Monitoring
- metrics
- logs aggregation
- alerting basics

Status: NOT STARTED

## Interview Competencies

### Linux basics
- [x] users
- [x] groups
- [x] permissions
- [x] ownership
- [x] processes

### systemd
- [x] service
- [x] journalctl
- [x] enable/start
- [x] troubleshooting 203/EXEC

### Networking
- [ ] ip
- [ ] ss
- [ ] routing
- [ ] dns

### Web
- [ ] nginx
- [ ] apache

### Databases
- [ ] PostgreSQL

### Containers
- [ ] Docker

### Monitoring
- [ ] Prometheus
- [ ] Grafana