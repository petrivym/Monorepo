# Steps create Monorepo ( React.js & Next.js & libs ( Utils & Types ))

- Create Main work space
  - :smile_cat: npx create-nx-workspace name-work-space
    (you can select another package manager)
  - :eye_speech_bubble: select Integrated -> apps
- add creator plugins to Dependence React.js & Next.js & @nx/js
  - :smile_cat: npm i -D @nx/react @nx/next @nx/js
  - :smile_cat: npm nx g @nx/react:app
  - :smile_cat: npm nx g @nx/node:app
- also we can create share lib for typing & utils and ect...
  - :smile_cat: npm nx g @nx/js:lib name utils
  - :smile_cat: npm nx g @nx/js:lib name types

# Monorepo

<a alt="Nx logo" href="https://nx.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/nrwl/nx/master/images/nx-logo.png" width="45"></a>

✨ **This workspace has been generated by [Nx, a Smart, fast and extensible build system.](https://nx.dev)** ✨

## Understand this workspace

Run `nx graph` to see a diagram of the dependencies of the projects.

## Remote caching

Run `npx nx connect-to-nx-cloud` to enable [remote caching](https://nx.app) and make CI faster.

## Further help

Visit the [Nx Documentation](https://nx.dev) to learn more.
