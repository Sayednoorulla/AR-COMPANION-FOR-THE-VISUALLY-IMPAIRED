# EchoSight AI
### Empowering Independence through Intelligent Visual Assistance

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-1.0.0-orange)

## Problem Statement
Over 285 million individuals worldwide are visually impaired. Navigating complex urban environments, reading print media, and recognizing everyday objects remains a significant challenge. **EchoSight AI** bridges this gap by providing real-time, AI-driven visual feedback through a seamless, accessibility-first interface.

## Key Features
- 👁️ **AI Scene Description**: Get detailed, natural language descriptions of your surroundings.
- 📦 **Object Recognition**: Identify key elements in a scene with high-confidence labels.
- 📖 **Text-to-Speech Reader**: Extract text from images and have it read aloud instantly.
- 🔊 **Auditory Feedback**: Seamless integration of high-quality speech synthesis for all insights.
- ♿ **Accessibility-First Design**: Optimized for screen readers, keyboard navigation, and high contrast.

## Tech Stack
| Layer | Technology |
|---|---|
| **Frontend** | Next.js 15, React 19, Tailwind CSS |
| **AI Processing** | Google Gemini 2.5 Flash, Genkit |
| **UI Components** | Shadcn UI, Lucide Icons |
| **State Management** | React Hooks |
| **Styling** | Tailwind CSS with Semantic HSL variables |

## System Architecture
EchoSight AI operates on a multi-layered architecture:
1. **Input Layer**: Mobile/Web client captures image data.
2. **Processing Layer**: Genkit flows orchestrate requests to multimodal AI models.
3. **Intelligence Layer**: Gemini 2.5 Flash performs OCR, object detection, and scene reasoning.
4. **Output Layer**: Auditory synthesis converts textual insights into speech for the user.

## Setup Instructions
1. **Clone the repository**
2. **Install dependencies**: `npm install`
3. **Environment Variables**: Configure your `.env` file with your Google AI API Key.
4. **Run Development Server**: `npm run dev`

## License
Distributed under the MIT License. See `LICENSE` for more information.