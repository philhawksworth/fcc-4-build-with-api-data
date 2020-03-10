## freeCodeCamp JAMstack examples

# 4 - Generating the site from a content API

This repo holds one of a series of examples of JAMstack sites from a freeCodeCamp video. The video, "Introduction to JAMstack" is available to view for free on freeCodeCamp.

## About this example

The 4th of our 6 code examples, this example builds on [example 3](https://findthat.at/jamstack/ex3) to generate content in the site with the use of a [static site generator](https://staticgen.com?utm_source=github&utm_medium=fcc-examples-pnh&utm_campaign=devex) first pulling content from a content API at build time.

Here in the video, we begin to source news content from the [News API](https://newsapi.org/) feed, and use this in our generated site.

## Local development

To work on this example locally, you can clone the repository and start editing, although there are a few pre-requisites:

- [NodeJS and NPM](https://nodejs.org/)
- A free [Netlify account](https://www.netlify.com?utm_source=github&utm_medium=fcc-examples-pnh&utm_campaign=devex)
- A free [newsapi.org](https://newsapi.org/) API key

```bash

# clone the repo
git clone https://github.com/philhawksworth/fcc-4-build-with-api-data

# move into the working directory and install dependencies
cd fcc-4-build-with-api-data
npm install

# build and start the local development server
npm start

# just run the build
npm run build

```

## Clone and deploy

If you wanted to quickly clone this repository and deploy it as a new site on [Netlify](https://www.netlify.com?utm_source=github&utm_medium=fcc-examples-pnh&utm_campaign=devex) you can click the button below for a rapid start. This will give you a ready-made CI/CD pipeline linked to your git commits.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/philhawksworth/fcc-4-build-with-api-data)



## Watch the video

For a better understanding of what this example is and why it exists, you can jump directly into the video at the point we are discussing this example

[![JAMstack video](https://www.freecodecamp.org/news/content/images/size/w1000/2020/03/jamstack.png)](https://youtu.be/A_l0qrPUJds?t=84m09s)


## Other code examples in this series

- [Example 1 - All simply static](https://findthat.at/jamstack/ex1)
- [Example 2 - Changing the DOM with JavaScript](https://findthat.at/jamstack/ex2)
- [Example 3 - Introducing a static site generator](https://findthat.at/jamstack/ex3)
- [Example 4 - Generating pages from a content API](https://findthat.at/jamstack/ex4) (👈 you are here)
- [Example 5 - Generating localized pages, with geo-IP routing at the CDN](https://findthat.at/jamstack/ex5)
- [Example 6 - Client-side rendering targeted API content](https://findthat.at/jamstack/ex6)


## More JAMstack resources to explore

- [jamstack.org](https://jamstack.org?utm_source=github&utm_medium=fcc-examples-pnh&utm_campaign=devex) - More info and resources
- [Official JAMstack slack](https://jamstack.org/slack) - conversation about JAMstack and web development (come on in!)
- [Modern Web Development on the JAMstack, O'reilly, 2019](https://findthat.at/jamstack/book) - Book on building websites with the JAMstack. Available as a free e-book.
