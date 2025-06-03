# Shramika Mitrudu - Feature Pages Component Breakdown

## 1. Find Work
- JobListPage.tsx
  - Displays list of job cards with filters (Location, Skill, Duration)
  - Uses JobCard component
  - FilterBar component for filtering jobs
- JobCard.tsx
  - Shows job details and provider contact info
  - "Apply" button triggers application logic and notification

## 2. Emergency Help
- EmergencyPage.tsx
  - PanicButton component to send SMS/email to emergency contacts and admin
  - MapView component showing local shelters and medical support using Google Maps API
  - Auto-call nearest authority using GPS and Google Maps API

## 3. Resume Generator
- ResumeGeneratorPage.tsx
  - FormInput components for Name, Skills, Experience, Languages, Contact
  - ResumePreview component to show generated resume
  - PDF generation and download/send options

## 4. Messages
- MessagesPage.tsx
  - ChatList component showing conversations
  - ChatWindow component for 1:1 chat between workers and job providers
  - AdminBroadcast component for mass updates

## 5. Calls
- CallsPage.tsx
  - CallLogList component showing recent job calls
  - CallDialer component for in-app voice calls using Twilio API

## 6. Job Matching (AI-based)
- JobMatchingPage.tsx
  - UserDataForm component to collect skills, past work, preferences
  - JobRecommendations component showing matched jobs based on rule-based logic
  - Notification system for new matches

## 7. Government Schemes Integration
- GovernmentSchemesPage.tsx
  - SchemeList component showing schemes like MGNREGA, PMRY, E-Shram
  - Language toggle for scheme titles and descriptions
  - "Apply Now" buttons linking to official websites

## Shared Components
- LanguageToggle.tsx
- NavigationBar.tsx (bottom nav)
- Header.tsx (app name, tagline, language toggle)
- Button.tsx (custom styled buttons)
- Icon components (using Google Material or FontAwesome)

## Utilities
- API clients for Firebase, Twilio, SendGrid, Google Maps
- Localization utilities (i18n)
- Authentication components (Phone OTP login)

---

This breakdown will guide the modular development of the app features.
