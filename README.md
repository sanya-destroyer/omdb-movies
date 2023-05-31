This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/[movieId].tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## About

![Main screen](https://i.imgur.com/IcD77kv.png)

This project uses OMDB API for fetching movies, filter them by name, year of release
According to the API capabilities, this project has a search by seasons, movies, and franchises, with the ability to filter search results, sort by title or year of release.

![Search screen](https://i.imgur.com/xIVPbZR.png)

Search results contain brief information about the movie or series. All items paginated. Each pagination page is stored in memory to speed up interaction. 

Every search result have a link to a page that displays all the information, such as ratings, a brief summary of the plot.

![Movie info screen](https://i.imgur.com/vHNvutB.png)


