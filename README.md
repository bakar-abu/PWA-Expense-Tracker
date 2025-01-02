# Expense Tracker

**Expense Tracker** is a modern, user-friendly Progressive Web App (PWA) developed using Vite, React, and TailwindCSS. It helps users track and manage their expenses efficiently, view insightful statistics, and access their data even when offline.

## Features

- **User-Based Expense Tracking**: Track expenses on a per-user basis, enabling personalized data and insights.
- **Statistics and Charts**: Visualize your spending patterns with dynamic charts powered by Victory.js.
- **Offline Availability**: Thanks to Service Workers and IndexedDB, the app works seamlessly even without an internet connection.
- **Intuitive UI**: Built with TailwindCSS and React for a sleek and responsive design.
- **Date Filtering**: Easily filter and view expenses by day, week, or month using `date-fns`.
- **Secure Data Handling**: Integrated with Supabase for user authentication and cloud-based data storage.
- **PWA Support**: Install the app on your device and use it like a native app.

---

## Tech Stack

- **Frontend**: React, TailwindCSS
- **State Management**: React Hooks
- **Charts**: Victory.js
- **Backend**: Supabase (Authentication & Database)
- **Offline Storage**: IndexedDB (via `idb`)
- **Build Tool**: Vite
- **PWA Support**: `vite-plugin-pwa` and `workbox-window`

---

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/expense-tracker.git
   cd expense-tracker
