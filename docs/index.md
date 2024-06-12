---
layout: default
title: Home
nav_order: 1
has_children: false
---

## Create a new NextJS webapp

1. Create an empty codespace project (https://github.com/codespaces)

```console
user@nextjs_boilerplate:~$ npx create-next-app@latest
user@nextjs_boilerplate:~$ npm install
user@nextjs_boilerplate:~$ npm run dev

// You might need to first install some dependencies: `<npm install next@latest react@latest react-dom@latest>`
```

If you encounter a message similar to "(node:11923) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead." then switch to long-term support version of node with `<nvm install 20.10.0>` and `<nvm use 20.10.0>`.
