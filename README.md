# AI Agent Recommendation System

A modern web application that provides AI-powered agent recommendations based on user requirements and preferences.

## Features

- Interactive UI for specifying agent requirements
- AI-powered recommendation engine
- Real-time response generation
- Modern, responsive design with TailwindCSS
- Server-side processing for complex AI operations

## Tech Stack

- **Frontend:**
  - React with TypeScript
  - Vite for build tooling
  - TailwindCSS for styling
  - React Query for data fetching
  - React Markdown for content rendering

- **Backend:**
  - Node.js with Express
  - CORS enabled for cross-origin requests
  - Environment variable support with dotenv

## Prerequisites

- Node.js 18 or later
- npm or yarn

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-agent-recommendation.git
cd ai-agent-recommendation
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory with any required environment variables:
```env
# Add your environment variables here
```

4. Start the development servers:
```bash
# Start both frontend and backend servers
npm run dev:all

# Or start them separately:
npm run dev     # Frontend only
npm run server  # Backend only
```

5. Open [http://localhost:5173](http://localhost:5173) in your browser.

## Development

- `npm run dev` - Start the frontend development server
- `npm run server` - Start the backend server
- `npm run dev:all` - Start both frontend and backend servers concurrently
- `npm run build` - Build the frontend for production
- `npm run lint` - Run ESLint for code quality checks
- `npm run preview` - Preview the production build locally

## Project Structure

```
├── src/              # Frontend source code
├── public/           # Static assets
├── DuneQueries/      # Query-related files
├── server.js         # Backend server
├── vite.config.ts    # Vite configuration
├── tailwind.config.js # TailwindCSS configuration
└── tsconfig.json     # TypeScript configuration
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License.
