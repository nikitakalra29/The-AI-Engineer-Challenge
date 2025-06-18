# 🤖 AI Chat Assistant Frontend

A beautiful, modern chat interface built with Next.js that integrates with the FastAPI backend to provide a seamless AI chat experience powered by OpenAI's GPT-4.1-mini model.

## ✨ Features

- 🎨 **Modern UI**: Beautiful gradient design with smooth animations
- 💬 **Real-time Chat**: Streaming responses from the AI
- 🔐 **Secure API Key Input**: Password field for your OpenAI API key
- ⚙️ **Customizable System Messages**: Define the AI's behavior and role
- 📱 **Responsive Design**: Works perfectly on desktop and mobile
- 🚀 **Fast Performance**: Built with Next.js 15 and optimized for speed

## 🛠️ Tech Stack

- **Framework**: Next.js 15 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Backend Integration**: FastAPI (running on localhost:8000)

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ installed
- The FastAPI backend running on `http://localhost:8000`
- An OpenAI API key

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser

### Usage

1. **Enter your OpenAI API Key**: Paste your API key in the setup section
2. **Customize System Message** (Optional): Define how the AI should behave
3. **Start Chatting**: Type your message and press Send
4. **Enjoy the Conversation**: Watch as the AI responds in real-time!

## 🔧 Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

### Project Structure

```
src/
├── app/
│   ├── page.tsx          # Main chat interface
│   ├── layout.tsx        # Root layout
│   └── globals.css       # Global styles
```

## 🌐 Deployment

This frontend is designed to be deployed on Vercel. The backend should be deployed separately and the frontend URL updated accordingly.

## 🔗 Backend Integration

The frontend communicates with the FastAPI backend at `http://localhost:8000/api/chat`. Make sure the backend is running before using the frontend.

## 📝 License

This project is part of the AI Engineer Challenge.
