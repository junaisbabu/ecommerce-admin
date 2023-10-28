This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

Key Features:

- Using Shadcn UI for the Admin!
- Our admin dashboard is going to serve as both CMS, Admin and API!
- Able to control mulitple vendors / stores through this single CMS! (For example you can have a "Shoe store" and a "Laptop store" and a "Suit store", and our CMS will generate API routes for all of those individually!)
- Able to create, update and delete categories!
- Able to create, update and delete products!
- Able to upload multiple images for products, and change them whenever you want!
- Able to create, update and delete filters such as "Color" and "Size", and then match them in the "Product" creation form.
- Able to create, update and delete "Billboards" which are these big texts on top of the page. Able to attach them to a single category, or use them standalone (Our Admin generates API for all of those cases!)
- Able to Search through all categories, products, sizes, colors, billboards with included pagination!
- Able to control which products are "featured" so they show on the homepage!
- Able to see your orders, sales, etc.
- Able to see graphs of your revenue etc.
- Clerk Authentication!
- Order creation
- Stripe checkout
- Stripe webhooks
- MySQL + Prisma + PlanetScale
