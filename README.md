![](https://github.com/charan028/ai_code_review_agent/blob/main/output-gif/Screen%20Recording%202025-05-05%20at%209.07.27%E2%80%AFPM.gif)



# AI Code Review

A modern web application built with Next.js and Convex for AI-powered code review. This project demonstrates the integration of AI capabilities to assist in code review processes, providing automated analysis and suggestions for code improvements.

## Features

- AI-powered code review and analysis
- Real-time collaboration using Convex
- Modern UI built with Next.js and Tailwind CSS
- Type-safe development with TypeScript
- Syntax highlighting for code review

## Tech Stack

- **Frontend**: Next.js 15, React 19, Tailwind CSS
- **Backend**: Convex
- **AI Integration**: OpenAI SDK
- **UI Components**: Radix UI
- **Code Highlighting**: React Syntax Highlighter
- **Type Safety**: TypeScript, Zod

## Getting Started

### Prerequisites

- Node.js (latest LTS version recommended)
- npm or yarn
- Convex account and CLI

### Installation

1. Clone the repository:

```bash
git clone [repository-url]
cd aiagentreview
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Set up your Convex environment:

```bash
npx convex dev
```

4. Start the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

## Project Structure

- `app/` - Next.js application routes and pages
- `components/` - Reusable React components
- `convex/` - Backend functions and database schema
- `public/` - Static assets
- `lib/` - Utility functions and shared code

## Development

The project uses:

- Turbopack for fast development builds
- ESLint for code linting
- TypeScript for type safety
- Tailwind CSS for styling

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

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

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
