# gatsby-amp-starter-blog

A gatsby v1 starter for creating an AMP compliant blog.

For a gatsby v0 version, see [this version](https://github.com/chiedo/gatsby-amp-starter-blog/tree/ee71ff98278b0e5e6a34fc0952fac5780ed10c16).

Obviously you will want to invest more time on css/amponly.scss on your project to add more needed styling

Not sure what Amp is? Learn about [Project AMP](https://www.ampproject.org).

## Running in development
`npm run develop`

## Building for production

To create a production build, run `yarn run build`

The build will output to the `public` directory and that directory will contain an `amp` directory which has the amp version of your site.

You can then spin up a web server using MAMP or your tool of choice locally that points to your public directory. And test that your site is AMP compliant using this [Chrome Extension](https://chrome.google.com/webstore/detail/amp-validator/nmoffdblmcmgeicmolmhobpoocbbmknc?hl=en)

## Requirements

- Every image must have an image and width so image tags must be added to markdown as html tags. Img tags haven't been switched out in this example but the change is trivial.
