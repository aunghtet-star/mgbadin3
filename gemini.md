# Project Context: mgbadin3

## 🏗 Identifiers
- **App Name:** mgbadin3
- **Subdomain:** 3.mgbadin.top
- **Instance:** Tertiary (Clone of mgbadin)

## 🌐 Networking Configuration
- **Backend API Port:** 3003
- **Nginx Config Name:** 3.mgbadin.top
- **API Base URL:** https://3.mgbadin.top/api
- **Environment:** Production (DigitalOcean Droplet)

## 🚀 DevOps & Management
- **PM2 Backend Name:** mgbadin3-backend
- **PM2 Frontend Name:** mgbadin3-frontend
- **Project Root:** /root/nextjsproject/mgbadin3

## 🛠 Critical Rules for Gemini
1. **Port Restriction:** Only use Port 3003 for this project. Port 3001 is reserved for the primary app, and 3002 for the secondary.
2. **Nginx Path:** The configuration lives in `/etc/nginx/sites-available/3.mgbadin.top`.
3. **PM2 Commands:** When I say "restart," use `pm2 restart mgbadin3-backend`.
4. **Environment Variables:** Ensure `.env` files reflect the 3003 port and the `3.mgbadin.top` origin.

