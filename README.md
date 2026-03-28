# Focal MC Launcher

Focal MC Launcher is a desktop launcher for Minecraft: Java Edition (Windows), built with Tauri + React.

## Features

- Microsoft device-code sign-in flow
- Local instance directory management
- Local launcher configuration management

## Authentication and Data Handling

- No Microsoft password collection
- Uses Microsoft OAuth device-code flow
- Stores tokens locally on the user device only
- Does not send account tokens to third-party backend services

## Why Java Edition APIs Are Used

This launcher uses Java Edition game service APIs to:

1. Exchange Microsoft sign-in tokens for Minecraft session tokens
2. Verify account profile and entitlement for authenticated launch
3. Launch Minecraft with the user's own account session

## Tech Stack

- Frontend: React + TypeScript + Vite
- Desktop runtime: Tauri
- Backend: Rust

## Development

Install dependencies:

```bash
npm install
```

Run in development mode:

```bash
npm run tauri dev
```

Build production bundles:

```bash
npm run tauri build
```

## Contact

- Maintainer: FocalSalt
- Email: (add your email)
- Repository: (add your repository URL)

## License

MIT
