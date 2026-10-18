# Vibe Check — investor demo

Standalone interactive website for Vibe Check. This is a completely separate repository and deployment from PlayLab.

## Deploy on Vercel
1. Open https://vercel.com/new and import **loganlanou/vibe-check**.
2. Select **Other** as the framework preset.
3. Keep **Root Directory** as `./`.
4. Leave the build command blank/disabled, and keep the output directory at `./` (repository root).
5. Deploy. No environment variables or Node dependencies are required.

## Local preview
Run `python3 -m http.server 4173` from the project directory and browse to http://localhost:4173.

## Demo limitations
The project includes interactive search, venue discovery, Vibe On/Off, sample reviews, bookmarks, community actions, and rewards. Initial venue ratings, crowd data, activity and check-ins are illustrations, not verified real-time data. User-created actions are saved locally in the browser, not a shared database. The brand mark is a placeholder until the original logo is supplied. This is an investor prototype, not a production service.

## Independence
Do not import `play-lab`. This repository (`loganlanou/vibe-check`) is the source of truth for Vibe Check.
