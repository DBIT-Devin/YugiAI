# YugiAI

YugiAI is a monorepo for a Web3-enabled Yu-Gi-Oh! deck building assistant and dueling platform.

## Tech Stack

| Area      | Technology |
|-----------|------------|
| Front-end | Next.js, MUI, dnd-kit |
| Back-end  | Express, Prisma, PostgreSQL |
| Duel Engine | Socket.IO, TypeScript |
| Smart Contracts | Hardhat, Solidity |

## Local Development

```bash
# clone repo
npm install
yarn install
# run both front-end and back-end
npm run dev
```

Ensure PostgreSQL 15 is running and set the `OPENAI_API_KEY` environment variable.

## License

MIT
