# ChatGPT Clone with Next.js

This README file provides step-by-step instructions to set up and run a Next.js project for a ChatGPT clone. The project requires configuration of environment variables for OpenAI API and MongoDB.

## Prerequisites

Before starting, ensure you have the following installed:

- Node.js (v14.x or later)
- npm (v6.x or later) or yarn (v1.x or later)
- Git

## Getting Started

### 1. Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/chatgpt-clone.git
cd chatgpt-clone
```

### 2. Install Dependencies

Install the required dependencies using npm or yarn:

```bash
npm install
```
or
```bash
yarn install
```

### 3. Set Up Environment Variables

Create a `.env.local` file in the root directory of the project. This file will hold your environment variables.

```bash
touch .env.local
```

Open `.env.local` in a text editor and add the following lines, replacing `your-openai-api-key` and `your-mongodb-uri` with your actual OpenAI API key and MongoDB URI:

```env
OPENAI_API_KEY=your-openai-api-key
MONGODB_URI=your-mongodb-uri
```

### 4. Run the Development Server

Start the development server with the following command:

```bash
npm run dev
```
or
```bash
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application running.

That's it! You now have a working ChatGPT clone running with Next.js. If you encounter any issues or have questions, feel free to open an issue in the repository.
