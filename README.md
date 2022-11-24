# Sapper Example

This project is a brief example of a [Sapper](https://sapper.svelte.dev/) app that can be deployed to 2comms with zero configuration.

## Deploy Your Own

Deploy your own Sapper project to 2comms.

[![Deploy with 2comms](https://2comms.com/button)](https://2comms.com/build?repo-url=https://github.com/2comms/templates/sapper&template=sapper)

_Live Example: https://sapper-template.2comms.app_

### How this template was created

To get started with Sapper deployed to 2comms, you can use [degit](https://github.com/Rich-Harris/degit) to initialize the project:

```shell
$ npx degit "sveltejs/sapper-template#webpack" my-sapper-app
```

> The only change made is to change the build script in `package.json` to be `"sapper export"`.
