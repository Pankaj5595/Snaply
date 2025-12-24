# 📱 Snaply - Social Media Platform

A dynamic social networking application engineered with Vite, React, TypeScript, and Appwrite. Designed to provide a streamlined interface for connecting, sharing moments, and interacting in real-time.

## 🚀 Features

- **Interactive Feed & Engagement**: Seamlessly create posts, like content, and save favorites
- **Continuous Content Flow**: Optimized infinite scrolling for uninterrupted browsing
- **Live Synchronization**: Instantaneous feed updates and activity tracking
- **Adaptive UI/UX**: Fully responsive layout optimized for mobile and desktop

## 🛠️ Tech Stack

- **Frontend**:
  - Vite
  - React
  - TypeScript
  - Tailwind CSS
  - TanStack Query
  - React Router
  - React Hook Form

- **Backend**:
  - Appwrite

## 🔗 Live Demo & Links

- **Live Website**: [Snaply App](https://snaply-full-stack-social-media-app.vercel.app/)
- **GitHub Repository**: [Source code](https://github.com/raghavkhatri413/Snaply_full_stack_social_media_app)

## 🔧 Installation

1. Clone the project locally
```bash
git clone [https://github.com/raghavkhatri413/Snaply_full_stack_social_media_app.git](https://github.com/raghavkhatri413/Snaply_full_stack_social_media_app.git)
cd snaply
```
2. Install dependencies
```bash
npm install
```

3. Create a `.env` file in the root directory:
```env
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_ENDPOINT=your_endpoint
```

4. Start the development server
```bash
npm run dev
```

## 📁 Project Structure

```
snaply/
├── src/
│   ├── components/     # Reusable UI components
│   ├── hooks/         # Custom React hooks
│   ├── lib/           # Third-party library configs
│   ├── pages/         # Application pages
│   ├── services/      # API and service functions
│   ├── types/         # TypeScript types/interfaces
│   └── utils/         # Helper functions
├── public/
├── .env
└── package.json
```

## 🔨 Scripts

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run preview  # Preview production build
```

## 🌟 Key Features

### Content Management
- Robust post creation tools
- One-click like and bookmarking system
- Live interaction metrics


### Infinite Scrolling
- Efficient data fetching
- Smooth scrolling experience
- Optimized performance

### Real-time Updates
- Instant feed updates
- Live engagement tracking
- Optimistic UI updates

## 🚀 Deployment

1. Build the project
```bash
npm run build
```

2. Deploy the `dist` folder to your preferred hosting platform:
- Vercel
- Netlify
- Firebase Hosting

## 🛠️ Environment Variables

```env
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_ENDPOINT=your_endpoint
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## 👏 Acknowledgments

- Appwrite for backend services
- React community
- TanStack Query team
