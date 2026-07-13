# 🗼 Lighthouse

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js)
![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3-38BDF8?logo=tailwindcss)
![Claude AI](https://img.shields.io/badge/Claude_AI-Anthropic-orange)
![MIT License](https://img.shields.io/badge/License-MIT-green)

### An AI-powered analytics dashboard for understanding, monitoring, and exploring data through intelligent insights.

**🌐 Live Demo:** https://lighthouse-alpha-two.vercel.app/

</div>

---

# Overview

**Lighthouse** is a modern analytics platform designed to transform raw data into actionable insights.

Rather than presenting users with static dashboards full of charts, Lighthouse combines interactive data visualization with AI-powered analysis to help users understand what is happening, why it matters, and what to do next.

Built with modern web technologies and optimized for performance, Lighthouse focuses on delivering a fast, intuitive, and visually engaging experience.

---

# Why I Built It

Traditional dashboards often overwhelm users with numbers while leaving the interpretation up to them.

I wanted to build something different.

Lighthouse explores the idea that dashboards should do more than display information—they should help explain it.

By combining modern frontend development with AI-generated insights, the project experiments with a more intelligent approach to analytics.

---

# Features

### 📊 Interactive Dashboards

Visualize complex datasets through responsive charts and intuitive layouts.

---

### 🤖 AI-Powered Insights

Leverages Anthropic's Claude API to generate contextual explanations and summaries from available data. :contentReference[oaicite:0]{index=0}

---

### 📈 Rich Data Visualizations

Interactive charts built with Recharts provide a clean, responsive experience across devices. :contentReference[oaicite:1]{index=1}

---

### ⚡ Fast Modern UI

Built with Next.js 15 and React 19 for excellent performance and developer experience. :contentReference[oaicite:2]{index=2}

---

### 📱 Fully Responsive

Designed to work seamlessly across desktop, tablet, and mobile devices.

---

### 🎨 Clean Interface

A minimalist design focused on readability, usability, and reducing cognitive load.

---

# Screenshots

> Replace these placeholders with screenshots from your application.

| Dashboard | Analytics |
|------------|-----------|
| ![](docs/dashboard.png) | ![](docs/analytics.png) |

| AI Insights | Mobile |
|--------------|--------|
| ![](docs/insights.png) | ![](docs/mobile.png) |

---

# Technology Stack

## Frontend

- Next.js 15
- React 19
- TypeScript

## Styling

- Tailwind CSS

## Charts

- Recharts

## AI

- Anthropic Claude SDK

## Icons

- Lucide React

## Deployment

- Vercel

These dependencies are reflected in the project's lockfile, including Next.js, React, Recharts, Lucide React, and the Anthropic SDK. :contentReference[oaicite:3]{index=3}

---

# Architecture

```
User
      │
      ▼
Next.js Frontend
      │
      ├──────────► Interactive Charts
      │
      ├──────────► Dashboard Components
      │
      └──────────► Claude AI
                     │
                     ▼
             AI-generated Insights
```

---

# Project Structure

```
src/
│
├── app/
├── components/
├── hooks/
├── lib/
├── services/
├── utils/
├── types/
└── styles/
```

*(Adjust to match your actual folder structure if needed.)*

---

# Engineering Goals

This project explores several areas of modern frontend engineering:

- Building highly responsive dashboards
- Creating reusable UI components
- Presenting complex information clearly
- Integrating AI into user workflows
- Maintaining excellent performance with React Server Components
- Designing interfaces that prioritize clarity over visual clutter

---

# Local Development

Clone the repository

```bash
git clone https://github.com/raf0x/lighthouse.git
```

Install dependencies

```bash
npm install
```

Run the development server

```bash
npm run dev
```

Open

```
http://localhost:3000
```

---

# Roadmap

Future improvements include:

- 🔐 User authentication
- ☁️ Saved dashboards
- 📤 Export reports
- 📄 PDF generation
- 📈 Additional visualization types
- 🤖 More advanced AI recommendations
- 🌙 Dark mode
- ⚙️ Dashboard customization
- 📱 Progressive Web App support
- 🔄 Real-time data updates

---

# Lessons Learned

Building Lighthouse strengthened my experience in:

- Next.js App Router
- TypeScript
- AI API integration
- Dashboard design
- Responsive layouts
- Component architecture
- Data visualization
- Performance optimization

---

# Contributing

Contributions, ideas, and feedback are welcome.

If you'd like to contribute:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

# License

Released under the MIT License.

---

# Author

**Rafael Lemor**

Frontend Developer • Product Designer • AI Enthusiast

If you found this project interesting, consider giving it a ⭐ on GitHub.

---

> Lighthouse is an independent personal project built for experimentation, learning, and exploring modern approaches to analytics, AI, and frontend development.
