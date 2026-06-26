# AI Political Analytics Platform

**Enterprise-Grade Political Analytics & Voter Management System**

A production-ready, AI-powered analytics platform built on Google Cloud for political campaign management, voter engagement, and real-time analytics.

## 🎯 Overview

This platform provides:
- **Real-time Voter Management** with demographic analytics
- **AI-powered Insights** using Vertex AI and Gemini
- **Multi-level Geographic Analytics** (Constituency, Mandal, Ward, Village, Booth)
- **Volunteer & Campaign Management**
- **Advanced Data Import** with validation and normalization
- **Automated Reporting** and background processing
- **Enterprise Security** with RBAC and audit logging

## 🏗️ Architecture

Frontend (Next.js + React) → Cloud Run Backend → Multi-Cloud Storage

## 📦 Tech Stack

- **Frontend**: Next.js 14, React 18, TypeScript, Tailwind CSS, shadcn/ui
- **Backend**: Express.js, Firebase Admin SDK, Prisma ORM
- **Infrastructure**: Google Cloud Run, Cloud SQL, Firestore, BigQuery

## 🚀 Quick Start

```bash
git clone https://github.com/lokeshnaidu1211/lokesh.git
cd lokesh
npm install
npm run dev
```

## 📁 Project Structure

- `apps/frontend/` - Next.js dashboard
- `apps/backend/` - Express API
- `infrastructure/` - IaC and deployment
- `schemas/` - Database schemas
- `docs/` - Documentation

## 🔐 Security

- Firebase Authentication
- Role-Based Access Control (RBAC)
- Firestore Security Rules
- TLS encryption in transit
- Comprehensive audit logging

## 📊 Key Features

- Real-time Voter Management
- AI-powered Analytics
- Geographic Heat Maps
- Multi-source Data Import
- Automated Reporting
- Enterprise Security

## 📝 Documentation

See `docs/` directory:
- ARCHITECTURE.md
- API.md
- DEPLOYMENT.md
- SECURITY.md
- CONTRIBUTING.md

## 📈 Performance

- Supports 1M+ records
- Sub-second dashboard loads
- Optimized queries with indexes
- Redis caching
- CDN for static assets

## 📄 License

MIT License

Built with ❤️ for political analytics
