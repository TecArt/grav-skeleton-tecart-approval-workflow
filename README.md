![](tecart-logo-rgba_h120.png)
# TecArt® Approval Workflow

TecArt® Approval Workflow ist ein Skeleton für das Flat-File CMS [Grav](http://github.com/getgrav/grav). Es beinhatet u.a. folgende Plugins:
- TecArt® Fork des Grav Plugin Admin
- TecArt® Fork des Grav Plugin GitSync
- Grav Plugin TecArt® Jira Connector
- Grav Plugin TecArt® Review workflow

## Installation

**Installationsvoraussetzung**

Alle notwendigen Werkzeuge werden in der [Dokumentation](https://learn.getgrav.org/basics/requirements) zum Grav CMS erläutert.

**Installationsanleitung**

1. Das Grav CMS als [ZIP-Datei](https://getgrav.org/download/core/grav/1.5.3) herunterladen und entpacken
2. Dann das Skeleton TecArt® Approval Workflow als [ZIP-Datei](https://github.com/TecArt/grav-skeleton-tecart-approval-workflow/archive/master.zip) herunterladen
3. Anschließend den gesamten Ordnerinhalt des `User`-Ordners im Stammverzeichnis der `Grav`-Instanz mit dem Inhalt aus dem Skeleton ersetzen
4. Setup ausführen

```bash
cd grav
bin/grav install
```

5. Integrierten PHP Webserver starten und loslegen

```bash
php -S localhost:8000 system/router.php
```
