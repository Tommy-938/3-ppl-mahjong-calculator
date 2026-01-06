# Simple React App

A simple React application built with Vite.

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

### Development

Run the development server:
```bash
npm run dev
```

The app will be available at `http://localhost:5173`

### Build

Build for production:
```bash
npm run build
```

### Preview

Preview the production build:
```bash
npm run preview
```

## Publishing to GitHub

### Step 1: Initialize Git Repository

If you haven't already, initialize a git repository:

```bash
git init
```

### Step 2: Add and Commit Files

Add all files to git and make your first commit:

```bash
git add .
git commit -m "Initial commit: Simple React app"
```

### Step 3: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Enter a repository name (e.g., "simple-react-app")
5. Choose public or private
6. **Do NOT** initialize with README, .gitignore, or license (we already have these)
7. Click "Create repository"

### Step 4: Connect and Push to GitHub

GitHub will show you commands. Use these (replace `YOUR_USERNAME` and `YOUR_REPO_NAME`):

```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git branch -M main
git push -u origin main
```

**Note:** If you're using SSH instead of HTTPS:
```bash
git remote add origin git@github.com:YOUR_USERNAME/YOUR_REPO_NAME.git
```

### Step 5: Verify

Visit your repository on GitHub to confirm all files are uploaded.

## Features

- Simple counter component with increment/decrement buttons
- Modern, responsive UI
- Built with React 18 and Vite
