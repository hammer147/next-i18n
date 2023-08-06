# Next.js i18n (Internationalization) example

A simple demo with 2 pages and 2 languages.

If no language is found in the url, the middleware will redirect to the best language based on the request headers.  
This is done with 2 packages: negotiator and intl-localematcher.

A similar example can be found [here](https://github.com/vercel/next.js/tree/canary/examples/app-dir-i18n-routing)

More info in the [Next.js docs](https://nextjs.org/docs/app/building-your-application/routing/internationalization)
