# Server-side rendering for fun and profit

React is an amazing library for client-side user interface, and it has the
added benefit of being able to be rendered on the server, which keeps the
initial page load fast. However, server-side rendering in practice is
significantly more complicated than just calling ReactDOMServer's renderToString
and piping out the result, especially if you want to make sure your site loads
quickly in a mobile-first world. There are a number of frameworks available to
smooth out the common problems you run into with React server-side rendering,
encodes performance best practices into the framework, and makes it easy to
build high performance websites by default.  I will discuss what kinds of
applications are most benefited by using a server-side rendering library.  
I'll discuss above the fold rendering, sever-side rendering component caching,
code splitting, and state management with Redux for server-side rendered apps.

We'll focus on React Server, a framework designed to make universal React
applications easier to write, though we'll touch on the tradeoffs are between
React Server, next.js and electrode.  When you write your app for React Server,
you concentrate on your React components, and React Server takes care of
everything else that's needed to run and deploy real React server-rendered
apps. Under the hood, React Server is doing a bunch of clever optimizations,
many borrowed from the ideas behind Facebook's Big Pipe, to make sure
that your site shows up as quickly as humanly possible for your users.

I gave an earlier version of the talk at [react nl](http://reactnl.org/#program); the
slides are [available](https://doug-wade.github.io/slides/meet-React Server.html#/).
