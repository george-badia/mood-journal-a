# Project Summary
The Mood Journal project is a platform aimed at enhancing emotional wellbeing through structured journaling. It enables users to track their moods, analyze emotional trends, and receive personalized self-care recommendations. The application securely manages user data with a fully integrated backend, offering features for both free and premium users, including entry limits based on subscription status.

# Project Module Description
The project consists of several functional modules:
- **Authentication**: Manages user login, signup, and profile setup using Supabase for secure authentication.
- **Journal Management**: Users can create, edit, and delete journal entries linked to their accounts, with Row Level Security ensuring privacy.
- **Analytics**: Provides insights through mood charts and analysis of journal entries.
- **Recommendations**: Offers self-care tips based on user data.
- **Notifications**: Sends reminders to encourage regular journaling.
- **Protected Routes**: Ensures users are authenticated before accessing specific pages.
## Project Demo

🎥 **Watch the demo video:**  
[![Watch the demo](https://img.shields.io/badge/Watch%20Demo-Loom-blue?logo=loom&style=for-the-badge)](https://www.loom.com/share/1eb0ced00dfc49479a773dfd867763d6)

🌐 **Try the live project:**  
[**Mood Journal Live Demo**](https://mood-journal-a.vercel.app/#/login)

# Directory Tree
```
uploads/mood-journal-a-main/
├── App.tsx
├── README.md
├── components/
│   ├── Analytics.tsx
│   ├── ConfirmDeleteModal.tsx
│   ├── Dashboard.tsx
│   ├── EditEntryModal.tsx
│   ├── EmotionHeatmapCalendar.tsx
│   ├── EmotionPieChart.tsx
│   ├── History.tsx
│   ├── Journal.tsx
│   ├── Login.tsx
│   ├── MoodChart.tsx
│   ├── NudgeWidget.tsx
│   ├── PremiumModal.tsx
│   ├── Profile.tsx
│   ├── ProfileSetup.tsx
│   ├── ProtectedRoute.tsx
│   ├── RecentEntries.tsx
│   ├── SelfCareRecommendations.tsx
│   ├── Sidebar.tsx
│   ├── StatCard.tsx
│   ├── TriggerDetection.tsx
│   └── Wellness.tsx
├── constants.tsx
├── context/
│   ├── AuthContext.tsx
│   └── JournalContext.tsx
├── hooks/
│   ├── useAuth.ts
│   └── useJournal.ts
├── index.html
├── index.tsx
├── metadata.json
├── package-lock.json
├── package.json
├── pnpm-lock.yaml
├── public/
│   └── asset/
│       └── Generated Image August 31, 2025 - 5_53PM (1).jpeg
├── services/
│   ├── supabase.ts
│   ├── geminiService.ts
│   ├── intersendService.ts
│   └── journalService.ts
├── tsconfig.json
├── types.ts
└── vite.config.ts
```

# File Description Inventory
- **App.tsx**: Main application component.
- **README.md**: Project documentation and setup instructions.
- **components/**: Contains all UI components used in the application.
- **constants.tsx**: Defines constant values used throughout the app.
- **context/**: Provides context for authentication and journal data.
- **hooks/**: Custom hooks for managing authentication and journal state.
- **index.html**: Main HTML file for the application.
- **index.tsx**: Entry point for the React application.
- **metadata.json**: Contains metadata for the application.
- **package.json**: Lists project dependencies and scripts.
- **services/**: Contains service files for backend interactions, including Supabase configuration and journal management.
- **tsconfig.json**: TypeScript configuration file.
- **types.ts**: Type definitions used in the project.
- **vite.config.ts**: Configuration for Vite, the build tool.

# Technology Stack
- **React**: Frontend framework for building user interfaces.
- **TypeScript**: Superset of JavaScript for type safety.
- **Vite**: Build tool for fast development.
- **Supabase**: Backend as a service for authentication and database management.
- **Context API**: For state management.
- **Custom Hooks**: For encapsulating logic.

# Usage
To set up the project, follow these steps:
1. Install dependencies: Run the package manager install command.
2. Create a `.env.local` file with necessary API keys and database credentials.
3. Build the project: Use the build command specified in the package.json scripts.
4. Run the application: Use the start command specified in the package.json scripts.
