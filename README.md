# Calibre-Web-Automated for LazyCat

Calibre-Web-Automated v4.0.8 packaged as a LazyCat LPK (community store).

## Publication

MiaoMiao community store app 664, APPROVED, version 4.0.8. LPK built by reusable LazyCat workflow (run 41084706487) with mirror delivery verification for `crocodilestick/calibre-web-automated:v4.0.8`. SHA256 `a79cafe8870c9eb0088130fff223527f333c64aeb9c5692a8322032fe9302a5d` recorded by the store at submission.

Configuration-only checks passed; no device startup, library init, format conversion or ingest verification.

## Notes

- Login page uses simple-inject-password autofill (no auto-submit); deploy params provide initial credentials.
- `/calibre-library` is the Calibre library (auto-created on first run), `/cwa-book-ingest` the ingest directory, `/config` app config.
- Fixed manifest YAML quoting bug (passwordSelector nested quotes) found before submission.
