<p align="center">
  <img src="assets/header.svg" alt="Hammad Ali: Flutter and AI developer building healthcare apps" width="100%">
</p>

### About me

I build cross-platform mobile apps with **Flutter** and connect them to real
backends and **AI**. My focus is healthcare: products that have to be fast,
private and trustworthy, where the UX decides whether people actually use
them.

- 🩺 Currently building **DermaCare**, an AI skin-screening and dermatology telemedicine app
- 🧠 Interested in applied AI: vision models, LLM-assisted triage, safety rules around model output
- 🔐 Care about security by design: row-level security, server-side secrets, least privilege
- 🎨 Detail-oriented about UI/UX: motion, accessibility and design systems
- 📍 Lahore, Pakistan

### Featured project: DermaCare

<img src="assets/dermacare-banner.svg" alt="DermaCare" width="100%">

**Scan a skin concern in about a minute, then get a licence-verified dermatologist on it.**
One Flutter codebase with patient, doctor and admin apps on Android, iOS and the web.

- **AI triage:** Gemini vision classifies photos into six condition groups with a strict JSON schema; blurry or non-skin photos are rejected with a retake tip; any meaningful cancer signal is always flagged for a doctor; retries and a fallback model keep scans working under load
- **Own model, too:** Flask + TensorFlow/Keras (VGG19 transfer learning) classifier server, used automatically when it's online
- **Secure backend:** Supabase Postgres with row-level security on every table, admin-verified doctors, private photo storage, Deno edge functions so no API key ships in the app
- **Full care loop:** booking with clash prevention, chat, Stream video calls, PDF reports, reviews, family profiles, emergency SOS
- **Craft:** a motion system, painted 3D visuals, skeleton loading, screen-reader labels and reduce-motion support
- **Quality:** 79 automated checks, including a 33-step live end-to-end suite covering RLS isolation, booking and account deletion; CI builds for APK, AAB and IPA

<sub>The repository is private. A demo is available on request.</sub>

### Tech I work with

<p>
  <img alt="Flutter" src="https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white">
  <img alt="Dart" src="https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white">
  <img alt="Supabase" src="https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
  <img alt="Flask" src="https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white">
  <img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white">
  <img alt="Gemini" src="https://img.shields.io/badge/Gemini%20API-8E75B2?logo=googlegemini&logoColor=white">
  <img alt="Deno" src="https://img.shields.io/badge/Deno-000000?logo=deno&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white">
  <img alt="Android" src="https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white">
  <img alt="iOS" src="https://img.shields.io/badge/iOS-000000?logo=apple&logoColor=white">
</p>

### Let's connect

Open to collaborating on **Flutter** and **AI-for-health** projects. The
quickest way to reach me is through GitHub.
