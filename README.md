![](tecart-logo-rgba_h120.png)
# TecArt® Approval Workflow

TecArt® Approval Workflow ist ein Skeleton für das Flat-File CMS [Grav](http://github.com/getgrav/grav). Es beinhatet u.a. folgende Plugins:
- TecArt® Fork des Grav Plugin Admin
- TecArt® Fork des Grav Plugin GitSync
- Grav Plugin TecArt® Jira Connector
- Grav Plugin TecArt® Review workflow

## Installation

Laden Sie sich einfach die [ZIP-Datei des letzten Release](https://github.com/TecArt/grav-skeleton-tecart-approval-workflow/releases/download/1.0/grav-skeleton_tecart-approval-workflow_v1.0.zip) herunter, entpacken Sie sie in Ihrem web-root Verzeichnis und Sie können loslegen!

Webserver-Starten:
```bash
php -S localhost:8000 system/router.php
```

Hinweis: Bevor Sie den Content unter der Nutzung der TecArt Plugins bearbeiten können, müssen die Plugins *TecArt GitSync*, *TecArt Jira Connector* und *TecArt Review Workflow* konfiguriert werden. Außerdem sollten die Logins der eingerichteten Nutzer den jeweiligen Loginnamen Ihres Jira- bzw. Bitbucket-Systems entsprechen.

**Kontakt**  
TecArt GmbH  
Sören Müller  
github@tecart.de
