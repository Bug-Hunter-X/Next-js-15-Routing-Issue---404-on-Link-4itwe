# Next.js 15 Routing Bug

This repository demonstrates a common routing issue encountered in Next.js 15 applications. The application has two pages: `Home` and `About`.  However, navigating to the About page via the link provided on the Home page results in a 404 error.

The bug is located in `pages/index.js` and `pages/about.js`.  The solution is also provided.

## Bug

The link in `pages/index.js` uses `next/link`, which is typically used for client-side routing in Next.js. However, in this example it is not working correctly.

## Solution

The solution involves checking the file structure and ensuring the page is correctly named to match the routing and the export name.