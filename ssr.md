Server-side rendering for fun and profit

React is an amazing library for client-side user interface, and it has the
added benefit of being able to be rendered on the server, which keeps the
initial page load fast. However, server-side rendering in practice is
significantly more complicated than just calling ReactDOMServer's renderToString
and piping out the result, especially if you want to make sure your site loads
quickly in a mobile-first world. There are a number of frameworks available to
smooth out the common problems you run into with React server-side rendering,
encodes performance best practices into the framework, and makes it easy to
build high performance websites by default.  I will discuss what kinds of
applications  are most benefited by using a server-side rendering library, and
what the tradeoffs are between React Server, next.js and electrode.  I'll
discuss above the fold rendering, sever-side rendering component caching, code
splitting, and state management with Redux for server-side rendered apps.

I gave an earlier version of the talk at [react nl](http://reactnl.org/#program).
The video will be available [on their site](http://reactnl.org/2016/talks); the
slides are [already available](https://doug-wade.github.io/slides/meet-react-server.html#/).

I am a Seattle-based Senior Front-end engineer at Indeed.  I'm a beer enthusiast,
cyclist and soccer hooligan.
