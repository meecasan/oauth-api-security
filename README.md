# OAuth 2.0 API Security Lab

## Description
This project demonstrates OAuth 2.0 authentication using GitHub OAuth and Flask.

The system allows users to:
- Login using GitHub
- Access protected API routes
- Logout securely
- Prevent unauthorized API access

---

## Installation Guide

### Clone Repository

```bash
git clone YOUR_REPOSITORY_LINK
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

---

## OAuth Routes

| Route | Description |
|---|---|
| /login | Login using GitHub |
| /callback | OAuth callback |
| /profile | Protected profile route |
| /logout | Logout route |
| /api/secure-data | Bonus protected API |

---
