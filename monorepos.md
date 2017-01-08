# Monorepos: managing multi-module monoliths majestically

Npm was built with the model of a single developer working on a single module,
and is the most successful tool on the market for that use-case.  However,
most developers don't work alone, but instead work in teams and divisions that
share a large architecture.  Single modules that operate independently can lead
to trouble -- iterating quickly in such an environment can lead to merge
conflicts, integration bugs that aren't caught until production, and lots of
overhead trying to coordinate between teams.  There is another way, though:
monorepos.

We'll talk about how to improve the reproducibility of your javascript builds,
improve the security, reduce merge conflicts and increase developer velocity
by using a monorepo to enforce best practices.  Learn about lerna, the monorepo
build tool that allows you to build a full dependency graph as if it were a
single node module, and learn about how introducing monorepos to open source
projects such as [clefs](https://github.com/doug-wade/clefs) and
[react-server](https://github.com/redfin/react-server), and to close-sourced
projects, such as www.indeed.com and www.redfin.com improved developer
experience.
