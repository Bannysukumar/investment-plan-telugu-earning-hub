<!-- readme-seo: bannysukumar-professional-v4 -->

# Telugu Earning Hub Investment Plan

This repository is a separate pnpm workspace from `Telugu-Earning-Hub`. Its ROI app document title is still Telugu-Earning-Hub, and the source layout is the investment platform under `artifacts/roi-platform` plus `artifacts/api-server`.

## Overview

`artifacts/roi-platform/index.html` sets the page title to Telugu-Earning-Hub. The root package builds `@workspace/api-server` and `@workspace/roi-platform`. `artifacts/mockup-sandbox` is a UI prototyping tool titled Mockup Canvas. That sandbox is not the product name.

Node.js `>=20.19.0` and pnpm are required. Firebase rules and `firebase.json` are in the repository. This repo has no GitHub homepage set.

## Features

The workspace contains the same kind of ROI app and API layout used for plans, investments, and withdrawals:

- `artifacts/roi-platform` React client
- `artifacts/api-server` API package
- `artifacts/mockup-sandbox` prototyping sandbox
- Firebase project files: `firebase.json`, `firestore.rules`, and `storage.rules`

## Tech Stack

| Technology | Where it shows up |
|---|---|
| TypeScript | Root `tsconfig.json` |
| pnpm | `pnpm-workspace.yaml` and `enforce-pnpm.cjs` |
| React and Vite | `artifacts/roi-platform` |
| Firebase | `firebase.json` and `.firebaserc` |
| Node.js 20.19+ | `package.json` `engines` |

## Architecture

React app in `artifacts/roi-platform` → API package `artifacts/api-server` → Firebase configuration in the repository root.

## Project Structure

```text
investment-plan-telugu-earning-hub/
├── artifacts/roi-platform/
├── artifacts/api-server/
├── artifacts/mockup-sandbox/
├── lib/
├── firebase.json
├── package.json
└── pnpm-workspace.yaml
```

## Prerequisites

- Node.js 20.19.0 or newer
- pnpm

## Installation

```bash
git clone https://github.com/Bannysukumar/investment-plan-telugu-earning-hub.git
cd investment-plan-telugu-earning-hub
pnpm install
pnpm dev
```

## Configuration

Firebase settings live in `firebase.json`, `.firebaserc`, `firestore.rules`, and `storage.rules`. Do not commit service-account keys.

## Usage

Run `pnpm dev`, then open the ROI platform dev server. The in-app document title in this repository is Telugu-Earning-Hub. For the sibling repository with its own README, see [Telugu-Earning-Hub](https://github.com/Bannysukumar/Telugu-Earning-Hub).

## Contributing

Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## License

Licensed under MIT. See [LICENSE](LICENSE).

## Author

Banny Sukumar

GitHub: https://github.com/Bannysukumar
