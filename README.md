[![Netlify Status](https://api.netlify.com/api/v1/badges/be40f4f0-2735-4071-8d81-ae0266b232bf/deploy-status)](https://app.netlify.com/sites/wizardly-murdock-37e478/deploys)

# JAMStack presentation at @codernauts_es
This presentation was delivered on the 1st of February 2020

To run the presentation with live reload type:
```
npm start
```

To generate the static site for the presentation type:
```
npm run build
```

To generate a pdf with the presentation type:
```
npm run build-pdf
```

## About the presentation
It introduces the architecture and technology involved in the [JAMStack](https://jamstack.org/) movement as a "new" (it already existed, but now it has a name ) way to implement modern web sites and applications that has gain traction quite recently.

## Tools used for the presentation
This presentation has been implemented (yes, implemented) following JAMStack principles as it is can be pre-rendered and then statically served from any web server.

It is a Node.js package that uses the awesome library [reveal-md](https://github.com/webpro/reveal-md) which allows to create a presentation using the [reveal.js](https://github.com/hakimel/reveal.js) presentation library while setting the content using Markdown (and a bit of HTML markup for customisation).

## Other references made
TODO