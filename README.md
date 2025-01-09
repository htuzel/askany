# AskAny - Anonymous Q&A Platform

<div align="center">
  <h3>Create instant Q&A sessions with privacy in mind</h3>
  <p>
    <a href="https://askany.me" target="_blank">Live Demo</a> ·
    <a href="#features">Features</a> ·
    <a href="#getting-started">Getting Started</a> ·
    <a href="#deployment">Deployment</a>
  </p>
</div>

## About The Project

AskAny is an open-source, privacy-focused Q&A platform that allows you to create instant anonymous question-answer sessions. Perfect for events, meetings, webinars, and classrooms where participants might hesitate to ask questions publicly.

### Key Features

- 🚀 **Instant Setup**: Create a session with one click, no registration required
- 🔒 **Privacy First**: Anonymous questions, no personal data stored
- ⚡ **Real-time Updates**: Questions appear instantly for all participants
- 👆 **Upvoting System**: Most relevant questions rise to the top
- 🗑️ **Auto-cleanup**: Data automatically deleted after 7 days
- 🎯 **Session Management**: Mark questions as answered, manage the flow
- 📱 **Responsive Design**: Works seamlessly on all devices

## Getting Started

### Prerequisites

- Node.js 16+ and npm
- Redis 6+

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/htuzel/askany.git
   cd askany
   ```

2. Install dependencies for both frontend and backend
   ```sh
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. Set up environment variables
   ```sh
   # Backend (.env)
   REDIS_URL=redis://localhost:6379
   PORT=3001
   CORS_ORIGIN=http://localhost:3000

   # Frontend (.env.local)
   NEXT_PUBLIC_API_URL=http://localhost:3001
   ```

4. Start the development servers
   ```sh
   # Start backend (from backend directory)
   npm run dev

   # Start frontend (from frontend directory)
   npm run dev
   ```

## Architecture

- **Frontend**: Next.js, TailwindCSS, Axios
- **Backend**: Express.js
- **Database**: Redis
- **Real-time**: Polling (5s intervals)

## Deployment

### Frontend (Next.js)

Deploy to Vercel:
```sh
vercel
```

### Backend (Express)

Deploy to any Node.js hosting:
- Heroku
- DigitalOcean
- AWS
- Railway

### Database (Redis)

Recommended hosting options:
- Redis Cloud
- Upstash
- Self-hosted Redis

## Contributing

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Hayreddin Tüzel - [@htuzel](https://github.com/htuzel)

Project Link: [https://github.com/htuzel/askany](https://github.com/htuzel/askany)

## Support

If you find this project helpful, consider:
- Giving it a GitHub star ⭐
- [Buying me a coffee ☕](https://www.buymeacoffee.com/htuzel)

## Acknowledgments

- [Next.js](https://nextjs.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [Express](https://expressjs.com/)
- [Redis](https://redis.io/) 
