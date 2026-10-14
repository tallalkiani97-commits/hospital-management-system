# Hospital Management System

**Responsive hospital workflow prototype for patient registration and appointment operations.**

This project is a frontend-first concept for organizing common hospital workflows into a clear dashboard. It is deliberately static so the information architecture can be reviewed without connecting to real patient data or a production database.

## Problem statement

Healthcare interfaces need to make operational information easy to scan while protecting sensitive data. This prototype explores a calm visual system for patient counts, appointments and a simple registration flow.

## Features

- Patient and appointment summary cards.
- Responsive layout for desktop and mobile.
- Demo registration form with local-session feedback.
- Accessible native form controls.
- Zero backend and zero real patient data.

## User flow

```text
Dashboard → review operational counts → open registration → submit demo record
```

## Quick start

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000` in a browser.

## Project structure

```text
index.html   # UI, styles and demo interaction
README.md    # documentation
```

## Roadmap

- Add a secure authentication layer.
- Add a PostgreSQL-backed API.
- Add role-based access for reception, doctors and administrators.
- Add appointment search, audit logs and validation.
- Add privacy, security and accessibility testing before real use.

## Safety note

This is a portfolio prototype. Never enter real patient information. A production version would require threat modelling, encryption, access control, backups, compliance review and professional healthcare-domain validation.

## Tech stack

HTML5 · CSS3 · Vanilla JavaScript

## Author

Built by **Tallal Kiani**.
