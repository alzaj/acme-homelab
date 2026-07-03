# Ticket #0001

## Title
Deploy first application service

## Background
Acme GmbH bereitet sich vor die erste interne Anwendung zu installieren.

## Requirements:
  - einen System-User mit dem Namen appsvc für die Anwendung anlegen
  - der System-User muss keine Möglichkeit haben sich interactiv einzuloggen
  - die Anwendung wird gespeichert in 
    - /srv/project/hello
  - die Anwendung besteht aus einem Bash-Schript
  - die Anwendung wird ausgeführt über systemd
  - die Anwendung muss unter dem System-User appsvc laufen
  - ausgabe der Anwendung muss in den Journal von systemd eingetragen werden
  
## Acceptance Criteria

- der Dienst hello.service kann mit "systemctl start hello" gestartet werden
  - "systemctl status hello" zeigt keine Fehler
- der Dienst schreibt mit bestimmten Zeitabständen Einträge in systemd-Journal

## Related Stage
  - Stage 2 First Service (hello)
  
## Related Incidents
  - Incident #0001 203/Exec (missing traverse permission)