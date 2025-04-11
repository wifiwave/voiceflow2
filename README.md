# VoiceFlow.AI - README

VoiceFlow.AI is a conversational AI platform that allows businesses to create custom AI voice agents to handle various conversational tasks such as lead qualification, appointment setting, customer support, and reservations.

## Features

- **Custom Voice Agents**: Create AI agents with unique personalities and conversation flows
- **Real-Time Conversations**: Engage with voice agents through text or voice input
- **Play.ai Integration**: Powered by Play.ai's advanced conversational AI API
- **User-Friendly Interface**: Clean, professional design for easy navigation
- **Voice Agent Templates**: Pre-built templates for common business use cases

## Getting Started

### Local Development

1. Clone this repository
2. Install dependencies:
   ```
   npm install
   ```
3. Create a `.env.local` file with your Play.ai credentials:
   ```
   NEXT_PUBLIC_PLAY_AI_USER_ID=your_user_id
   NEXT_PUBLIC_PLAY_AI_API_KEY=your_api_key
   ```
4. Start the development server:
   ```
   npm run dev
   ```
5. Open [http://localhost:3000](http://localhost:3000) in your browser

### Deployment

For deployment instructions, see:
- [Detailed Vercel Deployment Guide](./docs/vercel_deployment_guide.md)
- [Simplified Vercel Guide](./docs/simplified_vercel_guide.md)

## Project Structure

- `/api`: Play.ai API integration modules
- `/components`: React components including voice agent UI
- `/hooks`: Custom React hooks for WebSocket and audio recording
- `/pages`: Next.js pages and routing
- `/public`: Static assets
- `/styles`: CSS and styling

## Key Components

- **Voice Agent Builder**: Create and customize AI voice agents
- **Real-Time Conversation**: Interface for interacting with voice agents
- **Voice Agent List**: Manage your created voice agents

## Play.ai Integration

This platform integrates with Play.ai's API for:
- Text-to-Speech conversion
- Speech-to-Text processing
- Voice agent management
- Real-time conversation handling via WebSockets

## License

This project is proprietary and confidential.

## Support

For support or questions, please contact the development team.
