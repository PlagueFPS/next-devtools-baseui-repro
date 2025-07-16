# next-devtools-baseui-repro

This is a minimal reproduction of an issue with Next.js dev tools underlying component library `base-ui` and their `detectBrowser.js` file that runs some platform-specific logic.

On Windows machines, this issue causes the error `[TypeError: Cannot read properties of undefined (reading 'includes')]`.

## Reproduction

1. Clone this repository
```bash
git clone https://github.com/PlagueFPS/next-devtools-baseui-repro.git
cd next-devtools-baseui-repro
```
2. Install dependencies
```bash
pnpm install
```
3. Run development server
```bash
pnpm dev
```
4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
