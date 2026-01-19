# Decentralized Student Dashboard

A decentralized student dashboard (DApp) built with JavaScript to let students and institutions manage and verify academic records and credentials on decentralized infrastructure. This README includes a dedicated "Image proof" area so you can add screenshots or verification images (e.g., leaderboard, profile, certificate verification).

[![Last Commit](https://img.shields.io/github/last-commit/Koushikpali/Decentralized-Student-Dashboard-?color=green)](https://github.com/Koushikpali/Decentralized-Student-Dashboard-/commits/main)
[![Language](https://img.shields.io/github/languages/top/Koushikpali/Decentralized-Student-Dashboard-?color=yellow)](https://github.com/Koushikpali/Decentralized-Student-Dashboard-)

Table of Contents
- [About](#about)
- [Features](#features)
- [Tech stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Environment](#environment)
- [Usage](#usage)
- [Development](#development)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)
- [Authors](#authors)
- [Contact](#contact)

## About
This repository contains the frontend UI and integration points for a Decentralized Student Dashboard (DApp). It is designed to display student profiles, recent projects, certificates and a leaderboard with verifiable credential badges.

## Features
- Student profile view
- Recent projects listing
- Certificates with verification badges
- Leaderboard showing top students and points
- Wallet/connect integration-ready

## Tech stack (typical)
- Frontend: JavaScript (React recommended)
- Blockchain: ethers.js / web3.js (integration points)
- Storage: IPFS / Pinning (optional)
- Styling: TailwindCSS / CSS Modules
- Testing: Jest / React Testing Library

## Demo & Image proof
Use this section to show screenshots, verification images, or other proof artifacts. Keep images in the repository under `docs/images/` or `assets/images/` so they are versioned and easy to reference.

Recommended filenames:
- docs/images/proof-leaderboard.png
- docs/images/proof-dashboard.png
- docs/images/proof-certificate-1.png

Recommended sizes:
- Full-width screenshots: ~1200–1600px wide
- Smaller thumbnails: 600–800px wide

Where to add images
1. Create the directory (if missing):
   mkdir -p docs/images
2. Add your images with descriptive names:
   - docs/images/proof-leaderboard.png
   - docs/images/proof-dashboard.png
3. Commit and push:
   git add docs/images/*
   git commit -m "Add image proof screenshots"
   git push


## Prerequisites
- Node.js >= 16
- npm or yarn
- MetaMask or other wallet (for DApp flows, optional during UI development)

## Installation
```bash
git clone https://github.com/Koushikpali/Decentralized-Student-Dashboard-.git
cd Decentralized-Student-Dashboard-
npm install
# or
yarn install
```

## Environment
Copy `.env.example` to `.env` and fill required keys:
```
REACT_APP_RPC_URL=https://...
REACT_APP_CONTRACT_ADDRESS=0x...
REACT_APP_INFURA_KEY=...
```
Make sure `.env` is in `.gitignore`.

## Usage
Start development server:
```bash
npm start
# or
yarn start
```

Build for production:
```bash
npm run build
# or
yarn build
```

## Development
- Use feature branches: `feature/<short-name>`
- Follow eslint/prettier rules (if configured)
- Keep components in `src/components`, pages in `src/pages`, styles in `src/styles`

## Testing
Run unit tests:
```bash
npm test
# or
yarn test
```

## Contributing
Contributions are welcome. Please:
1. Fork the repository
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add some feature"`
4. Push: `git push origin feature/your-feature`
5. Open a Pull Request

Consider adding a `CONTRIBUTING.md` and `CODE_OF_CONDUCT.md`.

## License
No license specified. To make project use clear, add a LICENSE file (e.g., MIT, Apache-2.0).

## Authors
- Koushikpali — https://github.com/Koushikpali

## Contact
Repository: https://github.com/Koushikpali/Decentralized-Student-Dashboard-
![Screenshot 1](Screenshot%202026-01-20%20015706.png)
![Screenshot 2](Screenshot%202026-01-20%20015721.png)
![Screenshot 3](Screenshot%202026-01-20%20015944.png)
![Screenshot 4](Screenshot%202026-01-20%20020016.png)

