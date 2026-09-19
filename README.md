# Nuxt.js Hello World

A minimal [Nuxt.js](https://nuxt.com/) project that renders "Hello, World!" in the browser.

## Project Structure

```
nuxt/
├── helloworld/          # The Nuxt.js application
│   ├── app/             # Vue application source (app.vue)
│   ├── public/          # Static assets
│   ├── nuxt.config.ts   # Nuxt configuration
│   ├── package.json     # Dependencies and scripts
│   └── tsconfig.json    # TypeScript configuration
└── screenshoot/         # Screenshots of running steps
```

## Prerequisites / Dependency Check

Before installing, make sure you have the required tools installed on your machine.

### 1. Node.js (Required)

This project requires **Node.js 20 or newer** (Nuxt 4 requires Node.js >= 20).

Check if Node.js is installed:

```bash
node -v
```

If you see a version number (e.g. `v20.x.x` or higher), Node.js is installed. If the command is not found, install it from the official site: <https://nodejs.org>

### 2. npm (Package Manager)

npm is bundled with Node.js, but you can verify it as well:

```bash
npm -v
```

### 3. Git (Optional, for cloning the repo)

```bash
git --version
```

Install Git from <https://git-scm.com> if needed.

## Installation (Run Locally)

### Step 1: Clone the repository

```bash
git clone https://github.com/mokaddes/nuxt-js.git
cd nuxt-js/helloworld
```

> If you already downloaded the project, simply open a terminal in the `helloworld` folder.

### Step 2: Install dependencies

```bash
npm install
```

### Step 3: Start the development server

```bash
npm run dev
```

Nuxt will start a development server. Open <http://localhost:3000> in your browser — you should see **Hello, World!**

## Production Build

Build the application for production:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## Available Scripts

| Command            | Description                          |
| ------------------ | ------------------------------------ |
| `npm run dev`      | Start the development server         |
| `npm run build`    | Build the app for production         |
| `npm run generate` | Generate a static site               |
| `npm run preview`  | Preview the production build         |
| `npm install`      | Install all dependencies             |

## Troubleshooting

- **`node: not found` / command not recognized** — Node.js is not installed or not on your PATH. Install it from <https://nodejs.org> and restart your terminal.
- **`npm install` is slow** — This is normal on the first run; Nuxt installs many packages.
- **Port 3000 already in use** — Run the dev server on another port with `npm run dev -- --port 3001`.

## License

Free to use and modify.

---

For more information, see the [Nuxt documentation](https://nuxt.com/docs/getting-started/introduction).