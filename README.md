# Smart Notes Summarizer - Frontend

This is the frontend part of the Smart Notes Summarizer application. It is built with React, Vite, and TailwindCSS.

## Features

- User authentication (login/signup)
- Dashboard to manage AI-generated summaries
- Upload PDF documents or paste text
- View AI-generated summaries, key points, and quizzes
- Download summaries as PDF
- Responsive design with TailwindCSS

## Getting Started

### Prerequisites

- Node.js (v14+)
- npm or yarn

### Installation

1. Clone the repository
2. Navigate to the frontend directory:
   ```
   cd smart-notes-ai/frontend
   ```
3. Install dependencies:
   ```
   npm install
   ```
   or
   ```
   yarn
   ```

### Configuration

Create a `.env` file in the frontend directory with the following content:

```
VITE_API_BASE_URL=http://localhost:5000/api
```

Adjust the URL if your backend is running on a different port or host.

### Development

Start the development server:

```
npm run dev
```

or

```
yarn dev
```

### Building for Production

Build the project:

```
npm run build
```

or 

```
yarn build
```

Preview the production build:

```
npm run preview
```

or

```
yarn preview
```

## Project Structure

- `src/components`: Reusable UI components
- `src/context`: React context for state management
- `src/pages`: Page components
- `src/services`: API service functions
- `src/assets`: Static assets

## Technologies Used

- React 19
- Vite 6
- React Router 7
- TailwindCSS 4
- Axios
- jwt-decode
- html2pdf.js
- React-Toastify
- React-Icons
