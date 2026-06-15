# test1-again

A simple Node.js Express application

## Owner

user:default/ptk

## Tech Stack

- **Node.js** - JavaScript runtime
- **Express** - Web framework
- **Jest** - Testing framework

## Getting Started

### Prerequisites

- Node.js 18+ installed
- npm or yarn

### Installation

```bash
# Install dependencies
npm install
```

### Running the Application

```bash
# Development mode with auto-reload
npm run dev

# Production mode
npm start
```

The application will be available at `http://localhost:3000`

### API Endpoints

- `GET /` - Hello World message
- `GET /health` - Health check endpoint

### Testing

```bash
npm test
```

## Project Structure

```
.
├── index.js           # Main application file
├── package.json       # Dependencies and scripts
├── catalog-info.yaml  # Backstage catalog metadata
└── README.md          # This file
```

## Environment Variables

- `PORT` - Port number (default: 3000)

## Next Steps

1. Add more routes and endpoints
2. Add database integration
3. Add authentication
4. Set up CI/CD pipeline
5. Deploy to your preferred platform

## License

MIT
