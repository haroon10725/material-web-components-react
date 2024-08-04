# Material Web Components for React

[![npm version](https://badge.fury.io/js/material-web-components-react.svg)](https://www.npmjs.com/package/material-web-components-react)
![release](https://img.shields.io/badge/release-beta-blue)
[![docs](https://img.shields.io/badge/read%20the%20docs-8A2BE2)](https://material-web.dev)
[![docs](https://img.shields.io/badge/live%20demo-FFA500)](https://material-web-components-react.grayhat.studio)

A thin React wrapper over [@material/web](https://github.com/material-components/material-web/). Aims to be a locally-installable, accessible and customizable Material standard for React. Recommended to use with [MUI](https://mui.com/). Free. Open Source. **Looking for maintainers**.

![hero](https://material-web-components-react.grayhat.studio/opengraph-image.jpg)

## Installation

To use Material Web Components for React as a **library** in your project, run:

```sh
npm install material-web-components-react
```

## Documentation

Under the hood, this library simply uses the official [@material/web](https://github.com/material-components/material-web/) components. Visit [the official Material Web Components docs](https://github.com/material-components/material-web/blob/main/docs/intro.md) to learn how to use those components. The props remain the same!

## Contributing

We're looking for maintainers and contributors!

### Roadmap 🚀

- [ ] Make sure all native Web Components are properly working
  - [x] Demo all components
  - [x] Add all missing events
  - [ ] Add theming (design tokens) through Tailwind (i.e. remove all ts-ignores)
- [x] Resolve SSR/SSG issues, make compatible with NextJS (i.e. remove all dynamic imports)
- [x] Separate the demo from the actual UI code
- [x] Make installable as a package.
- [ ] Make installable as code-in-project, like shadcn/ui, so developers have more control
- [ ] Add better TypeScript support
- [ ] Sync with upstream (i.e. https://github.com/material-components/material-web/blob/main/docs/intro.md) through webhooks and automations
  - [ ] Use [Copybara](https://github.com/google/copybara) (or good ol' GitHub webhooks) to automate syncing with upstream
  - [ ] Use [lit-analyzer](https://www.npmjs.com/package/lit-analyzer) to see which Web Components changed. Perhaps mix with an LLM to compare existing and newly autogenerated code.
  - [ ] Create a PR with the new Component code.
- [ ] Mix this library with Tailwind and BaseUI in order to complete missing Components which may prove useful for building production applications
  - [x] App Bars
    - [x] Top App Bar
    - [x] Bottom App Bar
  - [x] Stack
  - [x] Box
  - [x] Navigation Rail
  - [x] Container
  - [x] Typography

### Credits

Huge shout out to Elizabeth Mitchell ([asyncLiz](https://github.com/asyncliz/)) and the rest of the Material Design team for their awesome Web Components implementation.

Thank you [Travis Reeder](https://github.com/treeder) for your Web Component implementation of Navigation Rail. I had to copy it to this project. I couldn't use yours directly because it would import `@material/web` again and bring conflicts.

Thanks for making the crappy, brain-dead wrapper components:

- [ChatGPT](https://chatgpt.com/share/574a9601-8927-4992-884e-16c58f24a982)

Thanks for improving the demo:

- [TalhaHere12](https://github.com/TalhaHere12)

Thanks for building BottomSheet:

- [Aroonaongithhub](https://github.com/Aroonaongithhub/)
