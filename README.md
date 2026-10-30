# Calibre-Web-Automated for LazyCat

- Upstream https://github.com/crocodilestick/Calibre-Web-Automated, version 4.0.8, GPL-3.0.
- Package `community.lazycat.app.calibre-web-automated`, Linux amd64, minimum LazyCat OS 1.5.0.
- Image `docker.io/crocodilestick/calibre-web-automated:v4.0.8` mirrored via `docker.1ms.run` with required digest matching.
- Port 8083. Persistent paths: `/config`, `/cwa-book-ingest`, `/calibre-library`. PUID/PGID 1000.

## Credentials

Upstream ships a well-known default admin password (`admin123`), documented in its README. This package does not ship that credential to users: deployment parameters generate a random 20-character initial password at install time, and the login page is autofilled from those parameters. Users should change the password after first login. The application stays behind LazyCat authentication with no public-path exemption.

## Publication

Reusable LazyCat workflow with versioned Release assets. Automatic private and official publishers stay disabled; only the independently verified Release URL/SHA256 is submitted to MiaoMiao community store after full alias/package/source duplicate checks.

No file-chooser interceptor, smoke job or runtime gate. Configuration/workflow checks, mirror verification and LPK SHA256 do not establish device startup, library initialization, format conversion or automatic ingest. Those runtime behaviors remain unverified.
