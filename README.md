# TailAdmin React Dashboard

A responsive admin dashboard built with React, TypeScript, Vite, and Tailwind CSS. It includes ecommerce metrics, sales charts, customer demographics, recent orders, and reusable UI examples.

## Features

- Responsive dashboard layout with collapsible sidebar navigation
- Ecommerce metric cards, sales and statistics charts, and monthly target
- Customer demographic map and recent orders table
- Calendar, profile, form, table, chart, and UI component pages
- Light/dark theme toggle
- Reusable React components and TypeScript types

## Requirements

- Node.js 18 or later
- npm

## Getting started

```bash
npm install
npm run dev
```

Vite prints the local development URL in the terminal.

## Available scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run build` | Type-check and create a production build in `dist/` |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint |

## Project structure

```text
src/
  components/  Shared UI, charts, forms, and dashboard components
  context/     Theme and sidebar state
  hooks/       Reusable React hooks
  layout/      Application header, sidebar, and layouts
  pages/       Dashboard and feature pages
  App.tsx      Application routes
  main.tsx     React entry point
public/
  images/      Static images and icons
```

## Notes

The dashboard currently uses sample data for its charts, metrics, map, and orders. No backend or authentication service is configured.
