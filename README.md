# [Kaikas](https://docs.kaikas.io) + [Web3Modal](https://web3modal.com)

## Working environment

- [Node.js](https://nodejs.org) >=20
- [pnpm](https://pnpm.io/installation#using-corepack) 8

> Other versions may work, but no guarantees.

## Setup

### 1. Install dependencies

```bash
pnpm install
```

### 2. Create `.env` file

```bash
cp .env.example .env.local
```

> Edit .env.local if you want to
>
> - test other networks
> - change WalletConnect Project ID

### 3. Build the project

```bash
pnpm run build
```

### 4. Start the project

```bash
pnpm run start
```

## Develop

```bash
pnpm run dev
```
