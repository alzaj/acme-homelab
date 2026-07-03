# Incident 0001 — systemd EXEC permission failure

## Symptom
Service failed with status=203/EXEC

## Cause
Missing execute permission on /srv/project path

## Detection
- systemctl status
- journalctl logs
- ls -l permissions

## Fix
chmod +x /srv/project

## Lesson learned
Systemd requires execute permission on all directories in execution path.