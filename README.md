# Cloudflare Pages Advanced mode local DO usage example

Install the dependencies with:
```sh
npm i
```

Serve the page locally with:
```sh
npm run dev
```

> [!WARNING]
> you can `wrangler pages deploy` but it won't deploy your DurableObject, for production
> usage you do need to declare your Counter DurableObject in a worker
