# Open sourcing react components

React components are small contained functions that take state as input and
produce markup as output, making them easy to reuse.  If you're looking for a
way to give back to the community, open-sourcing a react component is an
accessible way.  We'll take a whirlwind tour of the tools and services that are
available to help open source your React component, looking at
[react-link-to-inbox](https://github.com/indeedeng/react-link-to-inbox) as an
example. I'll explain how to set up your dependencies to avoid duplicate
React errors, setting up unit testing with ava and enzyme, visual testing with
storybook, static analysis with eslint and flow and continuous integration with
travis and appveyor.  I'll also talk about setting up your project to make it
easy for new developers to contribute including setting up your documentation
as a github static site, and the kinds of markdown files (contributing, code of
conduct, readme) that make maintenance and governance easy.

I've published [33 npm modules](https://www.npmjs.com/~douglas.wade) with more than [100,000 downloads in the past year](https://npm-stat.com/charts.html?author=douglas.wade).
