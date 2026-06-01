🧠 CogniFlow - Personal Intelligence Training Hub
Project Context
CogniFlow is a personalized daily learning application designed to enhance cognitive abilities through five key areas: English poetry appreciation, world geography knowledge, astronomy/constellation identification, botany (South Indian flowers), and multilingual phrases. The app uses AI APIs to generate fresh content daily, provides interactive learning experiences, and tracks personal progress. Built with Next.js, Supabase, and modern AI integrations for a seamless daily practice routine.
🚀 Tech Stack Highlights:
•	Frontend: Next.js 14+ with App Router, TypeScript, Tailwind CSS
•	UI: shadcn/ui + Hero UI for premium components
•	Database: Supabase with real-time capabilities
•	AI: OpenAI GPT-4 + Vision for content generation and flower identification
•	Animations: Framer Motion for smooth interactions
•	Deployment: Vercel with optimized builds
🧠 Smart Features:
•	Daily AI-generated poetry and astronomy content
•	South Indian flower identification using AI vision
•	Weekly country rotation with cultural insights
•	Multi-language phrase learning (10 languages)
•	Personal collection gallery with achievements
•	Learning streak tracking and progress analytics
The steps are designed to build the entire application systematically, from foundation to deployment, with each step building upon previous ones for seamless development flow. You can now use this guide to generate each component with AI assistance while maintaining consistency and quality throughout the project!



🧠 CogniFlow - Personal Intelligence Training Hub
Project Context
CogniFlow is a personalized daily learning application designed to enhance cognitive abilities through five key areas: English poetry appreciation, world geography knowledge, astronomy/constellation identification, botany (South Indian flowers), and multilingual phrases. The app uses AI APIs to generate fresh content daily, provides interactive learning experiences, and tracks personal progress. Built with Next.js, Supabase, and modern AI integrations for a seamless daily practice routine.
📁 Complete Folder Structure
cogniflow/
├── .env.local
├── .env.example
├── .gitignore
├── package.json
├── tailwind.config.js
├── next.config.js
├── tsconfig.json
├── README.md
├── components.json (shadcn config)
│
├── src/
│   ├── app/
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   │   ├── loading.tsx
│   │   ├── error.tsx
│   │   ├── globals.css
│   │   │
│   │   ├── api/
│   │   │   ├── generate-daily/
│   │   │   │   └── route.ts
│   │   │   ├── identify-flower/
│   │   │   │   └── route.ts
│   │   │   ├── constellation-info/
│   │   │   │   └── route.ts
│   │   │   └── progress/
│   │   │       └── route.ts
│   │   │
│   │   ├── dashboard/
│   │   │   ├── page.tsx
│   │   │   └── layout.tsx
│   │   │
│   │   ├── collection/
│   │   │   ├── page.tsx
│   │   │   └── flowers/
│   │   │       └── page.tsx
│   │   │
│   │   ├── learn/
│   │   │   ├── page.tsx
│   │   │   ├── poetry/
│   │   │   │   └── page.tsx
│   │   │   ├── geography/
│   │   │   │   └── page.tsx
│   │   │   ├── astronomy/
│   │   │   │   └── page.tsx
│   │   │   └── languages/
│   │   │       └── page.tsx
│   │   │
│   │   ├── profile/
│   │   │   └── page.tsx
│   │   │
│   │   └── admin/
│   │       └── page.tsx
│   │
│   ├── components/
│   │   ├── ui/ (shadcn components)
│   │   │   ├── button.tsx
│   │   │   ├── card.tsx
│   │   │   ├── input.tsx
│   │   │   ├── badge.tsx
│   │   │   ├── progress.tsx
│   │   │   ├── tabs.tsx
│   │   │   ├── dialog.tsx
│   │   │   └── toast.tsx
│   │   │
│   │   ├── layout/
│   │   │   ├── header.tsx
│   │   │   ├── navigation.tsx
│   │   │   ├── sidebar.tsx
│   │   │   └── footer.tsx
│   │   │
│   │   ├── dashboard/
│   │   │   ├── daily-poem-card.tsx
│   │   │   ├── constellation-card.tsx
│   │   │   ├── country-cards.tsx
│   │   │   ├── language-phrases-card.tsx
│   │   │   └── progress-overview.tsx
│   │   │
│   │   ├── learning/
│   │   │   ├── flower-identifier.tsx
│   │   │   ├── constellation-viewer.tsx
│   │   │   ├── country-explorer.tsx
│   │   │   ├── poetry-reader.tsx
│   │   │   └── phrase-practice.tsx
│   │   │
│   │   ├── collection/
│   │   │   ├── flower-gallery.tsx
│   │   │   ├── learned-items-grid.tsx
│   │   │   └── achievement-badges.tsx
│   │   │
│   │   └── common/
│   │       ├── loading-spinner.tsx
│   │       ├── error-boundary.tsx
│   │       ├── image-upload.tsx
│   │       └── theme-toggle.tsx
│   │
│   ├── lib/
│   │   ├── supabase.ts
│   │   ├── openai.ts
│   │   ├── constants.ts
│   │   ├── types.ts
│   │   └── validations.ts
│   │
│   ├── utils/
│   │   ├── date.ts
│   │   ├── format.ts
│   │   ├── helpers.ts
│   │   ├── image-processing.ts
│   │   └── content-generators.ts
│   │
│   ├── hooks/
│   │   ├── use-daily-content.ts
│   │   ├── use-flower-identification.ts
│   │   ├── use-progress-tracking.ts
│   │   └── use-debounce.ts
│   │
│   └── data/
│       ├── prompts.ts
│       ├── sample-data.ts
│       └── constants.json
│
├── scripts/
│   ├── setup-database.ts
│   ├── populate-countries.ts
│   ├── populate-languages.ts
│   └── generate-sample-content.ts
│
└── docs/
    ├── api-documentation.md
    ├── database-schema.md
    └── deployment-guide.md
🚀 Lovable AI Frontend Generation Prompt
Generate a Next.js frontend for CogniFlow - Personal Intelligence Training Hub
Create a modern, responsive dashboard application using Next.js 14+ with the following specifications:
Project Structure:
•	Use Next.js App Router structure exactly as shown above
•	Implement TypeScript throughout
•	Use Tailwind CSS for styling
•	Integrate shadcn/ui components (button, card, input, badge, progress, tabs, dialog, toast)
•	Add Framer Motion for smooth animations
Core Pages to Generate:
1.	src/app/page.tsx - Landing page with hero section and feature overview
2.	src/app/dashboard/page.tsx - Main dashboard with daily learning cards
3.	src/app/learn/page.tsx - Learning modules navigation
4.	src/app/collection/page.tsx - Personal collection gallery
5.	src/app/profile/page.tsx - User profile and progress tracking
Key Components to Build:
•	components/layout/header.tsx - Navigation header with theme toggle
•	components/dashboard/daily-poem-card.tsx - Poetry display card
•	components/dashboard/constellation-card.tsx - Astronomy learning card
•	components/dashboard/country-cards.tsx - Geography cards grid
•	components/dashboard/language-phrases-card.tsx - Language learning section
•	components/learning/flower-identifier.tsx - Image upload and identification
•	components/collection/flower-gallery.tsx - Personal flower collection grid
Design Requirements:
•	Modern glassmorphism design with dark/light mode support
•	Gradient backgrounds and subtle animations
•	Card-based layout with hover effects
•	Mobile-first responsive design
•	Clean typography using Inter font
•	Progress indicators and achievement badges
•	Interactive elements with micro-animations
Technical Requirements:
•	Use useState and useEffect for state management
•	Implement proper error boundaries
•	Add loading states and skeleton screens
•	Create reusable utility components
•	Follow accessibility best practices
•	Use proper TypeScript interfaces
Generate clean, production-ready code with proper component organization matching the folder structure above.
________________________________________
📋 Development Steps Guide
📋 STEP 1: Project Foundation & Configuration
What to Generate: Core project setup and configuration files
Files to Save: package.json, tsconfig.json, tailwind.config.js, next.config.js
Prompt for AI: Create the foundation setup for CogniFlow Next.js application. Generate package.json with all required dependencies (Next.js 14+, TypeScript, Tailwind, Supabase client, OpenAI SDK, shadcn/ui, framer-motion), tsconfig.json with proper path mapping, tailwind.config.js with custom theme configuration for glassmorphism effects, and next.config.js with image optimization settings.
Reference files needed:
•	.env.example (for environment variable structure)
•	components.json (for shadcn configuration)
📋 STEP 2: Environment & Database Configuration
What to Generate: Environment setup and Supabase client configuration
Files to Save: .env.example, src/lib/supabase.ts
Prompt for AI: Create environment configuration for CogniFlow. Build .env.example with all required API keys and Supabase credentials. Create src/lib/supabase.ts with Supabase client initialization, authentication helpers, and database connection utilities for the learning app.
Reference files needed:
•	package.json (for dependency context)
•	src/lib/types.ts (for TypeScript interface integration)
📋 STEP 3: Core Type Definitions
What to Generate: TypeScript interfaces and type definitions
Files to Save: src/lib/types.ts, src/lib/validations.ts
Prompt for AI: Create comprehensive TypeScript definitions for CogniFlow. Build src/lib/types.ts with interfaces for DailyContent, UserFlower, Country, LanguagePhrase, ConstellationData, and all database entities. Include src/lib/validations.ts with Zod schemas for form validation and API request/response validation.
Reference files needed:
•	src/lib/supabase.ts (for database schema context)
📋 STEP 4: AI Integration Setup
What to Generate: OpenAI client and AI service utilities
Files to Save: src/lib/openai.ts, src/data/prompts.ts
Prompt for AI: Create AI integration services for CogniFlow. Build src/lib/openai.ts with OpenAI client setup, error handling, and helper functions for text and vision API calls. Create src/data/prompts.ts with optimized prompts for daily content generation, flower identification, and constellation information retrieval.
Reference files needed:
•	src/lib/types.ts (for AI response type definitions)
•	.env.example (for API key structure)
📋 STEP 5: Database Schema & Setup Scripts
What to Generate: Database initialization and data population scripts
Files to Save: scripts/setup-database.ts, scripts/populate-countries.ts
Prompt for AI: Create database setup utilities for CogniFlow. Build scripts/setup-database.ts with Supabase table creation, RLS policies, and storage bucket setup. Create scripts/populate-countries.ts with AI-powered country data population including capitals, flags, languages, and cultural snippets for 52 countries.
Reference files needed:
•	src/lib/supabase.ts (for database client)
•	src/lib/openai.ts (for AI data generation)
•	src/lib/types.ts (for data structure validation)
📋 STEP 6: Language Data Population
What to Generate: Multi-language phrase generation and population
Files to Save: scripts/populate-languages.ts
Prompt for AI: Create language data population script for CogniFlow. Build scripts/populate-languages.ts that uses AI to generate authentic greetings, thank-yous, and goodbyes in 10 languages (Spanish, French, German, Japanese, Mandarin, Italian, Russian, Arabic, Hindi, Swahili) with proper pronunciation guides and cultural context.
Reference files needed:
•	src/lib/openai.ts (for AI translation services)
•	src/lib/supabase.ts (for data storage)
•	src/lib/types.ts (for language data structure)
📋 STEP 7: Daily Content Generation API
What to Generate: Core AI content generation API endpoint
Files to Save: src/app/api/generate-daily/route.ts
Prompt for AI: Create the daily content generation API for CogniFlow. Build src/app/api/generate-daily/route.ts that generates fresh daily content including English poems with authors and excerpts, constellation information with finding tips, and saves to Supabase. Include proper error handling, rate limiting, and content validation.
Reference files needed:
•	src/lib/openai.ts (for AI content generation)
•	src/lib/supabase.ts (for database operations)
•	src/data/prompts.ts (for content generation prompts)
📋 STEP 8: Flower Identification API
What to Generate: AI-powered flower identification service
Files to Save: src/app/api/identify-flower/route.ts
Prompt for AI: Create flower identification API for CogniFlow. Build src/app/api/identify-flower/route.ts that processes uploaded images, uses GPT-4 Vision to identify South Indian flowers, provides botanical information and interesting facts, and saves results to user's personal collection with proper image handling.
Reference files needed:
•	src/lib/openai.ts (for vision AI integration)
•	src/lib/supabase.ts (for image storage and data saving)
•	src/lib/types.ts (for flower data structure)
📋 STEP 9: Date & Time Utilities
What to Generate: Date formatting and manipulation utilities
Files to Save: src/utils/date.ts
Prompt for AI: Create comprehensive date utilities for CogniFlow. Build src/utils/date.ts with functions for daily content scheduling, week calculations for country rotation, learning streak tracking, timezone handling, and date formatting for the Indian locale with proper internationalization support.
Reference files needed:
•	src/lib/constants.ts (for date format constants)
📋 STEP 10: Data Formatting Utilities
What to Generate: Content formatting and display utilities
Files to Save: src/utils/format.ts
Prompt for AI: Create formatting utility functions for CogniFlow. Build src/utils/format.ts with functions for formatting learning progress percentages, streak counters, content truncation for cards, text cleaning for AI responses, and consistent data presentation across the learning dashboard.
Reference files needed:
•	src/utils/date.ts (for date formatting integration)
•	src/lib/types.ts (for data structure context)
📋 STEP 11: General Helper Functions
What to Generate: Common utility functions and data manipulation helpers
Files to Save: src/utils/helpers.ts
Prompt for AI: Create general helper functions for CogniFlow. Build src/utils/helpers.ts with utilities for array shuffling (for randomizing learning content), object deep cloning, error handling helpers, content validation, image URL processing, and data transformation functions for the learning application.
Reference files needed:
•	src/utils/format.ts (for data formatting integration)
•	src/lib/types.ts (for type safety)
📋 STEP 12: Image Processing Utilities
What to Generate: Image handling and optimization functions
Files to Save: src/utils/image-processing.ts
Prompt for AI: Create image processing utilities for CogniFlow. Build src/utils/image-processing.ts with functions for image compression before upload, format validation, thumbnail generation, Supabase storage integration, and image URL management for the flower identification feature.
Reference files needed:
•	src/lib/supabase.ts (for storage operations)
•	src/utils/helpers.ts (for utility functions)
📋 STEP 13: Custom Hooks - Daily Content
What to Generate: React hook for fetching and managing daily learning content
Files to Save: src/hooks/use-daily-content.ts
Prompt for AI: Create daily content management hook for CogniFlow. Build src/hooks/use-daily-content.ts with functionality to fetch today's poem and constellation, handle loading states, cache content, trigger daily content generation if missing, and provide refresh capabilities for the dashboard.
Reference files needed:
•	src/lib/supabase.ts (for data fetching)
•	src/lib/types.ts (for type definitions)
•	src/utils/date.ts (for date management)
📋 STEP 14: Custom Hooks - Progress Tracking
What to Generate: Learning progress and streak tracking hook
Files to Save: src/hooks/use-progress-tracking.ts
Prompt for AI: Create progress tracking hook for CogniFlow. Build src/hooks/use-progress-tracking.ts that manages learning streaks, tracks daily engagement, calculates completion percentages, stores achievements, and provides motivation metrics for the personal intelligence training dashboard.
Reference files needed:
•	src/lib/supabase.ts (for progress data storage)
•	src/utils/date.ts (for streak calculations)
•	src/lib/types.ts (for progress data types)
📋 STEP 15: Custom Hooks - Flower Identification
What to Generate: Flower identification and collection management hook
Files to Save: src/hooks/use-flower-identification.ts
Prompt for AI: Create flower identification hook for CogniFlow. Build src/hooks/use-flower-identification.ts that handles image uploads, calls the identification API, manages loading states, stores identified flowers in user collection, and provides collection retrieval for the South Indian botany learning feature.
Reference files needed:
•	src/app/api/identify-flower/route.ts (for API integration)
•	src/lib/types.ts (for flower data types)
•	src/utils/image-processing.ts (for image handling)
📋 STEP 16: Core Layout Components
What to Generate: Main application layout and navigation components
Files to Save: src/components/layout/header.tsx, src/components/layout/navigation.tsx
Prompt for AI: Create core layout components for CogniFlow. Build src/components/layout/header.tsx with responsive navigation, theme toggle, user profile access, and learning streak display. Create src/components/layout/navigation.tsx with dashboard, learning modules, collection, and profile navigation using modern glassmorphism design.
Reference files needed:
•	src/components/ui/button.tsx (for interactive elements)
•	src/components/common/theme-toggle.tsx (for theme switching)
📋 STEP 17: Dashboard Content Cards
What to Generate: Daily learning content display components
Files to Save: src/components/dashboard/daily-poem-card.tsx, src/components/dashboard/constellation-card.tsx
Prompt for AI: Create dashboard content cards for CogniFlow. Build src/components/dashboard/daily-poem-card.tsx with elegant poetry display, author information, and reading progress. Create src/components/dashboard/constellation-card.tsx with constellation visualization, description, and sky-finding tips using modern card design with hover animations.
Reference files needed:
•	src/hooks/use-daily-content.ts (for content data)
•	src/components/ui/card.tsx (for base card component)
•	src/utils/format.ts (for content formatting)
📋 STEP 18: Geography & Language Learning Cards
What to Generate: Interactive learning components for countries and languages
Files to Save: src/components/dashboard/country-cards.tsx, src/components/dashboard/language-phrases-card.tsx
Prompt for AI: Create geography and language learning components for CogniFlow. Build src/components/dashboard/country-cards.tsx with weekly country rotation, flag displays, capital quizzes, and cultural snippets. Create src/components/dashboard/language-phrases-card.tsx with interactive phrase practice, pronunciation guides, and progress tracking.
Reference files needed:
•	src/lib/supabase.ts (for data fetching)
•	src/components/ui/badge.tsx (for progress indicators)
•	src/utils/date.ts (for weekly rotation logic)
📋 STEP 19: Interactive Learning Components
What to Generate: Advanced learning interaction components
Files to Save: src/components/learning/flower-identifier.tsx, src/components/learning/constellation-viewer.tsx
Prompt for AI: Create interactive learning components for CogniFlow. Build src/components/learning/flower-identifier.tsx with drag-and-drop image upload, AI identification results, and collection saving. Create src/components/learning/constellation-viewer.tsx with interactive star maps, constellation outlines, and educational information display.
Reference files needed:
•	src/hooks/use-flower-identification.ts (for flower identification)
•	src/components/common/image-upload.tsx (for file handling)
•	src/components/ui/dialog.tsx (for result modals)
📋 STEP 20: Collection & Gallery Components
What to Generate: Personal collection display and management
Files to Save: src/components/collection/flower-gallery.tsx, src/components/collection/achievement-badges.tsx
Prompt for AI: Create collection management components for CogniFlow. Build src/components/collection/flower-gallery.tsx with masonry layout for flower photos, search/filter functionality, and detailed view modals. Create src/components/collection/achievement-badges.tsx with learning milestones, streak achievements, and progress celebrations.
Reference files needed:
•	src/hooks/use-progress-tracking.ts (for achievement data)
•	src/components/ui/badge.tsx (for achievement display)
•	src/utils/format.ts (for achievement formatting)
📋 STEP 21: Common Utility Components
What to Generate: Reusable utility and UI components
Files to Save: src/components/common/loading-spinner.tsx, src/components/common/image-upload.tsx
Prompt for AI: Create utility components for CogniFlow. Build src/components/common/loading-spinner.tsx with animated learning-themed spinners and skeleton screens. Create src/components/common/image-upload.tsx with drag-and-drop functionality, preview capabilities, validation, and progress indicators for the flower identification feature.
Reference files needed:
•	src/components/ui/progress.tsx (for upload progress)
•	src/utils/image-processing.ts (for image validation)
📋 STEP 22: Main Application Pages
What to Generate: Core application pages and routing
Files to Save: src/app/page.tsx, src/app/dashboard/page.tsx
Prompt for AI: Create main application pages for CogniFlow. Build src/app/page.tsx with inspiring landing page, feature showcase, and quick start guide. Create src/app/dashboard/page.tsx that combines all daily learning cards, displays progress overview, and provides seamless navigation to learning modules with server-side data fetching.
Reference files needed:
•	src/components/dashboard/daily-poem-card.tsx (for content display)
•	src/components/dashboard/constellation-card.tsx (for astronomy content)
•	src/components/layout/header.tsx (for navigation)
•	src/hooks/use-daily-content.ts (for data management)
📋 STEP 23: Learning Module Pages
What to Generate: Dedicated learning section pages
Files to Save: src/app/learn/page.tsx, src/app/collection/page.tsx
Prompt for AI: Create learning module pages for CogniFlow. Build src/app/learn/page.tsx with navigation to poetry, geography, astronomy, and language modules with progress tracking. Create src/app/collection/page.tsx displaying personal flower collection, learned items grid, and achievement showcase with responsive gallery layout.
Reference files needed:
•	src/components/learning/flower-identifier.tsx (for learning interaction)
•	src/components/collection/flower-gallery.tsx (for collection display)
•	src/hooks/use-progress-tracking.ts (for progress data)
📋 STEP 24: Application Configuration & Constants
What to Generate: App-wide constants and configuration
Files to Save: src/lib/constants.ts, src/data/constants.json
Prompt for AI: Create application constants for CogniFlow. Build src/lib/constants.ts with learning quotas, API rate limits, content refresh intervals, achievement thresholds, and UI configuration. Create src/data/constants.json with static data like constellation information, common flower types, and learning motivation messages.
Reference files needed:
•	src/lib/types.ts (for constant type definitions)
•	src/utils/format.ts (for formatting constants)
📋 STEP 25: Additional API Endpoints
What to Generate: Supporting API routes for enhanced functionality
Files to Save: src/app/api/constellation-info/route.ts, src/app/api/progress/route.ts
Prompt for AI: Create additional API endpoints for CogniFlow. Build src/app/api/constellation-info/route.ts for detailed astronomical data and finding tips. Create src/app/api/progress/route.ts for updating learning streaks, saving achievements, and tracking user engagement metrics with proper data validation and error handling.
Reference files needed:
•	src/lib/openai.ts (for AI-enhanced content)
•	src/lib/supabase.ts (for data operations)
•	src/hooks/use-progress-tracking.ts (for progress logic)
📋 STEP 26: Final Integration & Polish
What to Generate: Application layout, error handling, and final optimizations
Files to Save: src/app/layout.tsx, src/app/error.tsx, src/app/loading.tsx
Prompt for AI: Create final application structure for CogniFlow. Build src/app/layout.tsx with global providers, font loading, theme configuration, and meta tags. Create src/app/error.tsx with user-friendly error pages and recovery options. Build src/app/loading.tsx with branded loading screens and progressive enhancement for the personal intelligence training platform.
Reference files needed:
•	src/components/layout/header.tsx (for layout structure)
•	src/components/common/loading-spinner.tsx (for loading components)
•	src/app/globals.css (for global styles)

