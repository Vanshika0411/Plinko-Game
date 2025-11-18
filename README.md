
# Plinko Game

A modern web-based Plinko game built with React, TypeScript, and Express.js. This project features a fun and interactive Plinko game where players can drop balls and watch them bounce through pegs to win prizes.

## Features

- Interactive Plinko game board
- Real-time ball physics simulation
- Score tracking and prize system
- Responsive design for all devices
- Modern UI with smooth animations

## Tech Stack

### Frontend
- React 18
- TypeScript
- Vite
- Tailwind CSS
- React Router
- Axios for API calls

### Backend
- Node.js
- Express.js
- TypeScript
- CORS enabled for cross-origin requests

## Project Structure

```
plinkoo/
├── frontend/           # React frontend application
│   ├── src/           # Source files
│   ├── public/        # Static assets
│   └── package.json   # Frontend dependencies
├── backend/           # Express.js backend server
│   ├── src/          # Source files
│   └── package.json  # Backend dependencies
└── version-1/        # Previous version of the project
```

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd plinkoo
```

2. Install frontend dependencies:
```bash
cd frontend
npm install
```

3. Install backend dependencies:
```bash
cd ../backend
npm install
```

### Running the Application

1. Start the backend server:
```bash
cd backend
npm run build
npm start
```

2. Start the frontend development server:
```bash
cd frontend
npm run dev
```

The application will be available at `http://localhost:5173` (frontend) and the backend API will be running on `http://localhost:3000`.

## Development

- Frontend development server: `npm run dev`
- Backend development: `npm run build` followed by `npm start`
- Linting: `npm run lint`

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License.

## Acknowledgments

- Thanks to all contributors who have helped with this project
- Special thanks to the open-source community for the amazing tools and libraries used in this project 
