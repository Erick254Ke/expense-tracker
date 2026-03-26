# Design System: Expense Tracker

This document defines the design tokens used in the local Expense Tracker project to ensure Stitch remains in sync with the development environment.

## 🎨 Color Palette

### Base Colors
- **Main Background**: `#0b0e14` (`--bg-main`)
- **Surface (Light)**: `#151821` (`--surface-light`)
- **Surface (Lighter)**: `#1d212b` (`--surface-lighter`)
- **Border**: `rgba(255, 255, 255, 0.06)` (`--border-color`)
- **Border Highlight**: `rgba(255, 255, 255, 0.12)` (`--border-highlight`)

### Text
- **Primary Text**: `#f3f4f6` (`--text-primary`)
- **Secondary Text**: `#9ca3af` (`--text-secondary`)

### Accents & Semantics
- **Accent Blue**: `#6366f1` (`--accent-blue`)
- **Accent Blue Hover**: `#4f46e5` (`--accent-blue-hover`)
- **Success (Green)**: `#10b981` (`--accent-green`)
- **Danger (Red)**: `#ef4444` (`--accent-red`)
- **Warning/Pending**: `#f59e0b` / `#fcd34d`
- **Cost/Special**: `#a78bfa`

## 🏁 Dashboard Categories

| Category | Text Color | Background | Bar Color |
| :--- | :--- | :--- | :--- |
| **Food & Shopping** | `#15803d` | `#dcfce7` | `#16a34a` |
| **Transport** | `#1d4ed8` | `#dbeafe` | `#2563eb` |
| **Bills & Utilities** | `#a16207` | `#fef9c3` | `#ca8a04` |
| **Airtime & Data** | `#6d28d9` | `#ede9fe` | `#7c3aed` |
| **Money Sent** | `#b91c1c` | `#fee2e2` | `#dc2626` |
| **Money Received** | `#065f46` | `#d1fae5` | `#059669` |
| **Savings & Loans** | `#0f766e` | `#ccfbf1` | `#0d9488` |
| **Other** | `#374151` | `#f3f4f6` | `#6b7280` |
| **Uncategorised** | `#92400e` | `#fef3c7` | `#f59e0b` |

## 📐 Typography

- **Font Family**: `'Outfit', sans-serif`
- **Weights**: `400` (Regular), `500` (Medium), `600` (Semi-Bold), `700` (Bold)
- **Hierarchy**:
  - `H1`: `18px`, Bold, `-0.4px` letter-spacing
  - `Body`: `13px` - `14px`
  - `Small/Secondary`: `11px`

## ✨ Effects & Radius

- **Corner Radius**:
  - Large (Modals): `24px`
  - Medium (Cards/Inputs): `14px`
  - Small (Buttons/Chips): `12px` / `10px`
  - Pill (Badges): `99px`
- **Blur**: `12px` (`backdrop-filter`) for topbar and modals.
- **Shadows**:
  - Soft: `0 2px 4px rgba(0,0,0,0.1)`
  - Elevated: `0 4px 6px -1px rgba(0,0,0,0.1)`
  - Modal: `0 -10px 40px rgba(0,0,0,0.5)`

## 🛠 Project Metadata
- **Stitch Project ID**: `3419919112109723496`
- **Tailwind**: No `tailwind.config.js` found; currently using Vanilla CSS with variables.
