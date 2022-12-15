# My Awesome Project
This is an eCommerce Store that sells audio products.

<a href="https://audio-ecommerce-store.vercel.app/" target="_blank">LIVE DEMO</a>

## How It's Made:

**Tech used:** Next.js, Sanity, Stripe

This store was build using Next.js to speed up load times thanks to server side rendering. Less time loading, more shopping! Sanity, a content management system, is used to easily add, change, or delete products that can be sold. Stripe is a massively used payments api since it is quick and simple to implement so I went with that for this store.

## Lessons Learned:

This is a test project so I could learn about how Next.js works and it turns out to be pretty awesome. I found the file-based routing to be intuitive and aside from different ways of doing things like using getServerSideProps instead of useEffect, I found Next.js to be just as fun to use as React.

## Changes to be Made:

There is currently a bug where interacting with an item in the cart moves said item to the top of the cart.
