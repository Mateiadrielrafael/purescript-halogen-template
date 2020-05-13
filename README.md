# Halogen Template

This is a template for starting a fresh project with the [Halogen](https://github.com/slamdata/purescript-halogen) library for writing declarative, type-safe user interfaces.

You can learn more about Halogen with these resources:

- The [Halogen documentation](https://github.com/purescript-halogen/purescript-halogen/tree/master/docs), which includes a quick start guide and a concepts reference.
- The [Learn Halogen](https://github.com/jordanmartinez/learn-halogen) learning repository.
- The [Real World Halogen](https://github.com/thomashoneyman/purescript-halogen-realworld) application and guide.
- The [API documentation](https://pursuit.purescript.org/packages/purescript-halogen) on Pursuit

You can chat with other Halogen users on the [PureScript Discourse](https://discourse.purescript.org), or join the [Functional Programming Slack](https://functionalprogramming.slack.com) ([invite link](https://fpchat-invite.herokuapp.com/)) in the `#purescript` and `#purescript-beginners` channels.

## What does this offer over the original template

1. This uses [pnpm](https://pnpm.js.org/) instead of npm as the package manager
2. This uses [esbuild](https://github.com/evanw/esbuild) for compile times over 100 times faster than webpack

## Getting started

**Prerequisites:** This template assumes you already have Git and Node.js installed with `pnpm` somewhere on your path.

First, clone the repository and step into it:

```sh
git clone git@github.com:Mateiadrielrafael/purescript-halogen-template.git halogen-project
cd halogen-project
```

I personally use nix to install purescript and spago, but if you want to install them with pnpm run:

```sh
pnpm i -D purescript spago
```

Then install the rest of the dependencies with:

```sh
pnpm install
```

## Building

To start the development server run the following command and then open a browser at `localhost:8080`:

```sh
pnpm run dev
```

To generate a production bundle run:

```sh
pnpm run build
```

## Todo:

- Zephyr
- Hygen
- All contributors
- Github actions
