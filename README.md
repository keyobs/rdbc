# roller derby bordeaux club

This project is the official website for the Roller Derby Bordeaux Club, designed to serve our skaters, fans, and the wider community.
Given that the majority of our audience will likely access information on the go, a primary focus for this development is a mobile-first, responsive design to ensure an excellent user experience on smartphones.

<br>
<br>

## 💻 Stack

Built with **React** framework and **Vite** build tool.  
Enforce **pnpm** use.

**Frontend**

- React **19** + TypeScript
- Reac Router
- Less (styling preprocessor)
- Vite (build tool)
- pnpm (packages manager)

**Optimization**
- React Compiler (react components optimization)

**Code Quality**

- BiomeJs (linter, formatter)
- Vitest (unit testing, component testing)
- Husky (quality check at commit)
- Commitlint (enforce commit messages to respect convention)

**CI/CD & Tooling**

- GitHub Pages (deployment)
- gh-pages (deployment helper)
- only-allow (ensures pnpm usage)

<br>
<br>


# 🚀 Development Setup Guide

To get started, follow these steps:

### Prerequisites

Node.js: Ensure you have Node.js installed on your machine.  
Node v.18 

### Installation

Clone the repository:

```
git clone https://github.com/keyobs/rdbc.git
```

Navigate to the project directory:

```
cd rdbc
```

Install dependencies:

```
pnpm install
```

Running the Project : start the development server:

```
pnpm run dev
```

Launch the app at http://localhost:5173/ (or a similar port).  
Hotload is on : the page will automatically reload as you make changes.

<br>