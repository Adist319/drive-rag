# Google Drive Clone with Advanced RAG Capabilities

A personal project that will create a modern, efficient, and smart file management system inspired by Google Drive. To be built with a modern tech stack and designed for extensibility, this application will support core file management with advanced search powered by vector search, and will grow with innovative features.

## Overview

This project will be a Google Drive clone that will let you upload, organize, and search for files using advanced semantic search capabilities. The application will be built on a robust tech stack combining Next.js, React, and TypeScript for the frontend, and Drizzle ORM with SQLite for the backend. Designed primarily for personal use, it will be built with future enhancements in mind.

### Planned Advanced Features

As the project evolves, these additional features will further enhance its capabilities:

1. **Local AI-Powered Summarization & Insights:**  
   Will integrate a local AI model to automatically generate document summaries and extract key insights, making content exploration fast and informative.

2. **Advanced File Previews & Media Handling:**  
   Will provide rich, interactive previews for various file types (PDFs, images, videos, etc.) with smart tagging and auto-categorization powered by AI.

3. **Offline Mode & PWA Capabilities:**  
   Will enable offline access and background synchronization through Progressive Web App (PWA) technology, ensuring a smooth experience even without an internet connection.

4. **Versioning & History Tracking:**  
   Will implement robust version control to track file changes over time, revert to previous versions, and maintain a detailed edit history.

## Features

- **File Management:**  
  Will allow uploading, viewing, and organizing your files in an intuitive interface.

- **Semantic & Vector Search Integration:**  
  Will go beyond keyword search by integrating a vector database (e.g., Pinecone, Qdrant, or even FAISS) to enable true semantic search. This will allow the system to understand the context and meaning behind search queries, returning more relevant results.

- **Modern UI/UX:**  
  Will be built using Next.js and React with Tailwind CSS for a clean and responsive design.

- **Type Safety & Scalability:**  
  Will be developed with TypeScript to ensure reliability and ease of maintenance.

- **Lightweight & Efficient Backend:**  
  Will use SQLite powered by Drizzle ORM to ensure a fast, portable, and easily manageable database.

## Tech Stack

### Frontend
- **Next.js (v15.0.1):** Will use new app directory structure with both server and client components.
- **React & React-DOM (v18.3.1):** Will build interactive UI.
- **TypeScript:** Will provide static type checking and modern JavaScript features.
- **Tailwind CSS:** Will implement custom themes and animations (with tailwindcss-animate plugin).
- **PostCSS:** Will process Tailwind CSS.
- **Lucide-react:** Will provide icon library for a modern look.
- **Radix UI:** Will provide accessible and composable UI components.
- **Utility Libraries:** Will use `clsx`, `tailwind-merge`, and `class-variance-authority` for dynamic class management.
- **Geist:** Will implement the Geist Sans font typography.

### Backend / Database
- **Drizzle ORM & drizzle-kit:** Will provide TypeScript-based ORM for seamless database operations and migrations.
- **@libsql/client:** Will connect to the SQLite database.
- **SQLite:** Will serve as lightweight database solution ideal for personal and demo applications.

### Environment & Tooling
- **Zod:** Will handle schema validation of environment variables.
- **@t3-oss/env-nextjs:** Will manage secure server and client environment variables.
- **ESLint & Prettier:** Will ensure high code quality and consistent formatting.
- **PNPM:** Will manage packages for efficient dependency management.
- **GitHub Actions:** Will provide continuous integration for builds, linting, and type checks.

## Getting Started

### Prerequisites
- **Node.js** (v16 or higher recommended)
- **PNPM**
- **SQLite**

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/google-drive-clone.git
   cd google-drive-clone
   ```

2. **Install Dependencies:**
   ```bash
   pnpm install
   ```

3. **Configure Environment Variables:**
   Create a `.env.local` file in the project root. Will need to refer to `.env.example` for guidance on the required variables.

4. **Run Database Migrations:**
   ```bash
   pnpm run migrate
   ```

5. **Start the Development Server:**
   ```bash
   pnpm run dev
   ```

6. **Open the App:**
   Navigate to [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

- **Search Files:**  
  Will provide a search bar to leverage the vector-based search for finding content within files.

- **Manage Files:**  
  Will allow uploading, viewing, and organizing files using the intuitive interface.

- **Future Enhancements:**  
  Will implement upcoming features like AI summarization, advanced previews, offline support, and versioning.

## Future Roadmap

As development progresses, the project will include:

- **Enhanced Local AI Integration:**  
  Will further improve the local AI model for better summarization and content insights.

- **Advanced File Previews:**  
  Will implement interactive media previews with intelligent tagging and categorization.

- **Offline & PWA Enhancements:**  
  Will develop a full offline mode with background sync capabilities for a robust PWA experience.

- **Version Control:**  
  Will enable comprehensive versioning and history tracking for secure file management.

## Contributing

Although to be tailored for personal use, contributions will be welcome! If you have ideas or improvements, you will be able to open an issue or submit a pull request.

## License

This project will be licensed under the [MIT License](LICENSE).

## Acknowledgements

- Will be inspired by the functionality and design of Google Drive.
- Thanks will be given to the open-source community for tools like Next.js, Tailwind CSS, Drizzle ORM, and more that will make this project possible.