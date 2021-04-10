# Contributing

**The issue tracker is only for issue reporting or proposals/suggestions. If you have a question, you can find us in our [Discord Server]**.

To contribute to this repository, feel free to create a new fork of the repository and
submit a pull request. We highly suggest [ESLint] to be installed
in your text editor or IDE of your choice to ensure builds from GitHub Actions do not fail.

1. Fork, clone, and select the **main** branch.
2. Create a new branch in your fork.
3. Make your changes.
4. Ensure your linting and tests pass by running `yarn test && yarn lint`
5. Commit your changes, and push them.
6. Submit a Pull Request [here]!

## Working on Hornet locally

To work on Hornet locally a few steps should be taken.

1. Install [Node.JS] and [Yarn].


A few other important commands:

```bash
# Lints and format all the code:
$ yarn lint

# Build Hornet Code
$ yarn build
```

## Hornet Concept Guidelines

There are a number of guidelines considered when reviewing Pull Requests to be merged. _This is by no means an exhaustive list, but here are some things to consider before/while submitting your ideas._

-   Everything should follow [OOP paradigms] and generally rely on behaviour over state where possible. This generally helps methods be predictable, keeps the codebase simple and understandable, reduces code duplication through abstraction, and leads to efficiency and therefore scalability.
-   Everything should follow our ESLint rules as closely as possible, and should pass lint tests even if you must disable a rule for a single line.
-   Everything should follow [Discord Bot Best Practices]

Code of Conduct
This project has a [Code of Conduct] which all contributers must follow.

<!-- Link Dump -->

[discord server]: https://discord.gg/menudocs
[here]: https://github.com/MenuDocs/hornet/pulls
[eslint]: https://eslint.org/
[node.js]: https://nodejs.org/en/download/
[yarn]: https://classic.yarnpkg.com/en/docs/install
[oop paradigms]: https://en.wikipedia.org/wiki/Object-oriented_programming
[discord bot best practices]: https://github.com/meew0/discord-bot-best-practices
[Code of Conduct]: ./CODE_OF_CONDUCT.md
