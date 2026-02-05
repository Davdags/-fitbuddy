# FitBuddy

This repository contains the initial skeleton for the FitBuddy app, including iOS and Android setups, backend, CI workflows, and environment configuration examples.

## Environment Setup
Please create a `.env` file in the root of your repository using the provided `.env.example`. Replace the placeholders with your actual keys.

## Build/Run/Test Steps
### iOS
- Open the project in Xcode.
- Build and run the app on an iOS simulator or device.

### Android
- Open the project in Android Studio.
- Build and run the app on an Android emulator or device.

## Instructions for Adding Environment Keys
1. Open `.env` file.
2. Add your Supabase keys:
   - `SUPABASE_URL`
   - `SUPABASE_ANON_KEY`
   - `SUPABASE_SERVICE_ROLE_KEY` (keep server-side, do not commit)
3. Add RevenueCat and Google keys:
   - `REVENUECAT_API_KEY_PLACEHOLDER`
   - `GOOGLE_CLIENT_ID`
   - `APPLE_CLIENT_ID`

## Enabling Row Level Security (RLS)
Make sure to enable RLS in your Supabase project settings.

## Running Supabase Locally
To run a local instance of Supabase, follow the official documentation for setting up Supabase locally.

---

## Folder Structure
- `ios/`: iOS app skeleton with Swift 5 and SwiftUI MVVM setup.
- `android/`: Android app skeleton with Kotlin and Jetpack Compose MVVM setup.
- `backend/`: SQL schema and Supabase Edge Function templates.
- `payments/`: RevenueCat integration notes.
- `.env.example`:** example keys for environment configuration.
- `.gitignore`: Lists files and directories to ignore in the repository.
- `.github/workflows/`: Contains the GitHub Actions CI workflows for iOS and Android builds.
- `assets/`: Placeholder for app icon and branding colors.

## Note
Remember to keep your sensitive keys secure and do not commit them to your repository.
