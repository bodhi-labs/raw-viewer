This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

## **Next.js Tauri with Shadcn**

# **Next.js**

### **Create frontend project with shadcn**

Run the `init` command to create a new Next.js project or to setup an existing one:

**pnpm**

```bash
pnpm dlx shadcn@latest init
```

for others package managers and detail process see https://ui.shadcn.com/docs/installation/next

[**Setup (Tauri CLI)**](https://tauri.app/start/create-project/#manual-setup-tauri-cli)

```bash
cargo install tauri-cli --version "^2.0.0" --locked
```

### In your project directory, initialize Tauri:

1. [pnpm](https://tauri.app/start/create-project/#tab-panel-1247)
    
    ```bash
    cargo tauri init
    ```
    
    After running the command it will display a prompt asking you for different options:
    
    ```bash
    ✔ What is your app name? tauri-app
    ✔ What should the window title be? tauri-app
    ✔ Where are your web assets located? ..
    ✔ What is the url of your dev server? http://localhost:5173
    ✔ What is your frontend dev command? pnpm dev
    ✔ What is your frontend build command? pnpm build
    ```
    
    This will create a `src-tauri` directory in your project with the necessary Tauri configuration files.
    
2. Verify your Tauri app is working by running the development server:
    
    [**cargo**](https://tauri.app/start/create-project/#tab-panel-1254)
    
    ```bash
    cargo tauri dev
    ```
    
    This command will compile the Rust code and open a window with your web