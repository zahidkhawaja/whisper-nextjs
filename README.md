# Next.js Template for Stable Diffusion

This is a [Next.js](https://nextjs.org/) template for  🍌 [Banana](https://www.banana.dev/) deployments of Stable Diffusion on serverless GPUs. Feel free to customize this frontend and make it your own! Enter your API keys in .env.local and go bananas! 🎉

## Getting Started

1. Clone this repo.

2. Create a `.env.local` file with `BANANA_API_KEY=your_api_key` and `BANANA_MODEL_KEY=your_model_key`.

3. Install dependencies:

```bash
npm i
```

4. Run the development server:

```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) with your browser to see your project!

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

An [API route](https://nextjs.org/docs/api-routes/introduction) has already been created [http://localhost:3000/api/diffusion](http://localhost:3000/api/diffusion). This endpoint uses the Banana API keys you provide and can be edited at `pages/api/diffusion.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## 🍌 Banana Docs

To learn more about Banana, take a look at the following resources:

- [Banana Documentation](https://www.banana.dev/docs) - learn about Banana's API.
- [1-Click Stable Diffusion model on Banana](https://www.banana.dev/stable-diffusion) - the world's easiest way to deploy Stable Diffusion on serverless GPUs.

To customize the model beyond the one-click template, see [Banana's GitHub repository](https://github.com/bananaml/serverless-template-stable-diffusion) - full credit goes to Banana for making this project possible!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

Important note: Vercel's "free" plan has a serverless function execution timeout of 10 seconds. You may need a "pro" plan (which has a 60 second timeout) to run this in production without issues. This limitation does not affect local development.

## Use 🍌 Banana for scale.
