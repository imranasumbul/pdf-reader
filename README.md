# PDF Reader

A modern web application for reading PDF files. This application also supports dark mode better readability in low light conditions.

## Features

- **Dark Mode PDF Viewing**: Automatically inverts PDF colors for better readability in low light conditions
- **Drag & Drop**: Easy file uploading with drag and drop support
- **Responsive Design**: Works on desktop and mobile devices
- **Modern UI**: Clean and intuitive user interface

## Tech Stack

- **Next.js**: React framework for server-rendered applications
- **TypeScript**: Type-safe JavaScript
- **Tailwind CSS**: Utility-first CSS framework
- **Shadcn UI**: Reusable UI components

## Project Structure

The project follows a feature-based folder structure for better organization:

```
src/
├── app/                  # Next.js app router
├── components/           # All UI components
│   └── ui/               # Shadcn UI components
├── features/             # Feature-based modules
│   └── pdf-reader/       # PDF reader feature
│       ├── components/   # PDF reader components
│       ├── hooks/        # Custom hooks
│       ├── utils/        # Utility functions
│       └── types/        # TypeScript types
```

## Getting Started

### Prerequisites

- Node.js 18+
- npm or pnpm

## License

MIT
