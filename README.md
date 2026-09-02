# PK API Portfolio — Final
Static HTML/CSS/JS portfolio with live public API integrations.

## Live APIs
- Open-Meteo: current weather, no API key for open-source/non-commercial use.
- GitHub REST: public profile endpoint. Change `pkdiv6548` in `js/app.js` to your GitHub username.
- Hacker News official Firebase API: top stories.
- Open Library Search API: live book search.
- Random User: live generated profile/photo.
- JokeAPI: public safe-mode joke endpoint.

## Reliability
Every request has:
- HTTP status validation
- JSON validation
- 9-second timeout
- isolated error state
- retry/refresh control
- API online/error indicator
- raw response preview

The page remains usable if any single API fails.

## Run
Open `index.html` or use VS Code Live Server. No Node.js/npm/build step is required.

## Important
These are public/free APIs, not necessarily all "open-source software" in the strict licensing sense. Always follow each provider's current usage/license/rate-limit policy before commercial deployment.
