# Services

## hello.service
- Type: systemd
- User: appsvc
- Purpose: learning service lifecycle

Status: running (lab)

## apache2.service
- autostart
- DocumentRoot: /srv/project/html
- Config: /etc/apache2/sites-available/acme-gmbh.conf