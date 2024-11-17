
# ChatPdf
**PDF Query Assistant**  
A full-stack application enabling users to query and upload PDF files, leveraging a Retrieval-Augmented Generation (RAG) system with OpenAI’s API. Built with a React frontend, FastAPI backend, and MongoDB for query history storage, it provides seamless interaction and intelligent responses based on PDF content.

## Features

- 🚀 **Vite**: Blazing fast development and build tooling.
- ⚛️ **ReactJS**: Component-based UI for dynamic applications.
- 📜 **TypeScript**: Static typing for enhanced development experience.
- 🎨 **Tailwind CSS**: Utility-first CSS framework for rapid UI design.
---

## Prerequisites

Make sure you have the following installed:

- **Node.js** (v16+ recommended)
- **npm** or **yarn**

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Rjjha/ChatPdf-Frontend.git
   cd ChatPdf-Frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

---

## Development

Start the development server:

```bash
npm run dev
# or
yarn dev
```

The app will be live at [http://localhost:5173](http://localhost:5173).

---

## Build

To create a production-ready build:

```bash
npm run build
# or
yarn build
```

The built files will be available in the `dist/` folder.

---

## Scripts

- **`npm run dev`**: Start the development server.
- **`npm run build`**: Build the project for production.
- **`npm run preview`**: Preview the production build locally.
- **`npm run lint`**: Lint the TypeScript and React code.

---

## Tailwind Configuration

Tailwind CSS is configured in `tailwind.config.js`. Modify this file to customize your design system.

---

## Project Structure

```
├── public/          # Static assets
├── src/
│   ├── assets/      # Images and static files
│   ├── components/  # Reusable React components
│   ├── pages/       # Page-level components
│   ├── styles/      # Global and component styles
│   ├── App.tsx      # Root component
│   └── main.tsx     # Application entry point
├── index.html       # Main HTML file
├── package.json     # Project metadata and scripts
├── postcss.config.js # Tailwind CSS config integration
├── tailwind.config.js # Tailwind CSS configuration
├── tsconfig.json    # TypeScript configuration
└── vite.config.ts   # Vite configuration
```

---

## Contribution

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add feature-name'`.
4. Push the branch: `git push origin feature-name`.
5. Open a Pull Request.

---

## Acknowledgements

- [Vite](https://vitejs.dev/)
- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)

---
