

# chatbot
Next.js AI Chatbot
An open-source AI chatbot app template built with Next.js, the Vercel AI SDK, OpenAI, and Vercel KV.

Features · Model Providers · Deploy Your Own · Running locally · Authors


# Features
Next.js App Router
React Server Components (RSCs), Suspense, and Server Actions
Vercel AI SDK for streaming chat UI
Support for OpenAI (default), Anthropic, Cohere, Hugging Face, or custom AI chat models and/or LangChain
shadcn/ui
Styling with Tailwind CSS
Radix UI for headless component primitives
Icons from Phosphor Icons
Chat History, rate limiting, and session storage with Vercel KV
NextAuth.js for authentication
Model Providers
This template ships with OpenAI gpt-3.5-turbo as the default. However, thanks to the Vercel AI SDK, you can switch LLM providers to Anthropic, Cohere, Hugging Face, or using LangChain with just a few lines of code.

Deploy Your Own
You can deploy your own version of the Next.js AI Chatbot to Vercel with one click:

Deploy with Me

Creating a KV Database Instance
Follow the steps outlined in the quick start guide provided by Vercel. This guide will assist you in creating and configuring your KV database instance on Vercel, enabling your application to interact with it.

Remember to update your environment variables (KV_URL, KV_REST_API_URL, KV_REST_API_TOKEN, KV_REST_API_READ_ONLY_TOKEN) in the .env file with the appropriate credentials provided during the KV database setup.

## Running locally
You will need to use the environment variables defined in .env.example to run Next.js AI Chatbot. It's recommended you use Vercel Environment Variables for this, but a .env file is all that is necessary.

Note: You should not commit your .env file or it will expose secrets that will allow others to control access to your various OpenAI and authentication provider accounts.

Install Vercel CLI: npm i -g vercel
Link local instance with Vercel and GitHub accounts (creates .vercel directory): vercel link
Download your environment variables: vercel env pull
pnpm install
pnpm dev
