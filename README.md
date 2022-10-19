## Flare Frontend technical task

The product team have tasked us with building out a dashboard for our customers, that displays some product inventory data.

The backend team have created a REST API endpoint: [`https://my-json-server.typicode.com/flare-code/interview-dummy-api/products`](https://my-json-server.typicode.com/flare-code/interview-dummy-api/products)that returns an array of objects. Each object is a product that is stocked in the online store.

**We’ve been asked to do the following:**

1.  Use the product data from the API to render all of the products in a list.
2.  Highlight products that have a `stockCount` of 0, so that the customer can order more.
3.  If we have time, the product team would like us to be able to filter the list by `tags` too.

**Things to think about**

- How are we going to handle errors?
- How are we going to layout the UI? You're not a designer, so don't worry too much, but any design you can add is great.
- How are we going to approach testing?

We'll be using the react app setup in this repo, so don't both setting up any tooling / bundles.

**Steps to run**

1.  Clone the repo
2.  Install the necessary dependencies (we recommend using yarn)
3.  Run `yarn dev` to spin up the web server.
