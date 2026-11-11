# Hey, I'm Tamir 👋

I'm a frontend engineer at **CaliAlfa** and one of the code owners of our frontend monorepo, the React + TypeScript code behind a real-time sports betting platform. When something keeps slowing my team down, I usually end up building a tool for it.

### Things I built because I got tired of doing them by hand

- **Socket Manipulator**: our apps run on WebSockets, and testing what happens when the feed misbehaves was painful. So I built a proxy that sits in the middle and lets you duplicate, throttle, flood or rewrite messages live, decode Protobuf, and grab any socket open in Chrome with one click.
  <br><sub>Tauri · React · Node · ws · protobufjs</sub>
- **Generate Commit Message**: a ✨ button in VS Code (plus a `gcm` CLI) that writes your commit message with whatever AI CLI you already have (Claude Code, Codex, Kiro, Gemini), then checks it against the repo's commitlint rules so it actually passes.
  <br><sub>VS Code API · TypeScript · esbuild</sub>
- **Port Forward Listener**: `kubectl port-forward` has a habit of dying quietly. This little terminal UI keeps your forwards running and restarts them when they drop.
  <br><sub>Ink · React · execa</sub>
- **Automatic Client Login**: logging into a local build used to mean pasting snippets into the console. Now a Chrome extension copies your session from the dev site into localhost and reloads the tab.
  <br><sub>Chrome Extensions API · Playwright</sub>

### What I work with

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,react,vite,tailwind,materialui,styledcomponents,nodejs,express&perline=9" alt="TypeScript, JavaScript, React, Vite, Tailwind, MUI, styled-components, Node.js, Express" />
  <br>
  <img src="https://skillicons.dev/icons?i=vitest,pnpm,git,githubactions,vscode,tauri,rust,docker,kubernetes&perline=9" alt="Vitest, pnpm, Git, GitHub Actions, VS Code, Tauri, Rust, Docker, Kubernetes" />
</p>

Plus the things I reach for every day: TanStack Query, Table and Virtual · Zustand · Zod · React Hook Form · Radix and shadcn/ui · Playwright · Storybook · Biome · Sentry · PostHog

### How I like to work

- Small PRs, and a test that fails before the fix.
- Claude Code is part of my everyday workflow, and I like building tooling around it.
- If I've explained something twice, it turns into a README or a script.

<!-- TODO: optional line about you outside of code, e.g. "When I'm not coding, you'll find me ..." -->
