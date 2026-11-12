# Healthcare Communication Academy

A standalone healthcare communication training app with lessons, phrases, quizzes, practice cases, journal references, and a personal action plan.

## Run locally
Serve this directory with any static HTTP server, for example:
```sh
python3 -m http.server 8080
```

## Deploy to Vercel
Import this repository, use the repository root, and select **Other** as the framework. No install command, build command, environment variables, or backend services are required. The entry point is `index.html`; `vercel.json` configures static hosting.

Learning progress, feedback, and commitments are stored in the current browser's local storage. They do not sync between devices.
