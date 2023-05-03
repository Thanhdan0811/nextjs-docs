Types of pre-rendering
1. Static Generation.
  Without data
  With data
  Incremental Static Generation
  dynamic parameters when fetching data
2. Server-side rendering
  Data fetching.
  
# 1. Static Generation
A method of pre-rendering where the html pages are generated at build time.
The HTML with all the data that makes up the content of the web page are generated in advance when you build your application.
Page can be built once, cached by a CDN and served to the client almost instantly.
EX ; blog pages, e-commerce product pages, documentation and marketing pages.

The HMTL for every page will automatically be statically generated when we build our application.

Prod Server : An optimized build is created once and you deploy that build. We dont't make code changes on the go once it is deployed.
  a page will be pre-rendered once when we run the build command.
Dev Server : We should be able to make changes in our code and we want that code to immediately reflect in the browser.
  the page is pre-rendered for every request you make.
