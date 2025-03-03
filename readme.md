
Reproduce depedency error

```bash
npm install
npm start
```

the following error should appear:

```
 stencil-project % npm start
> rewe-digital-components@0.0.1 start
> stencil build --dev --watch --serve --no-open

[18:46.1]  @stencil/core
[18:46.4]  v4.27.1 🍸

[ ERROR ]  Error: Cannot find module 'sass-embedded' Require stack: -
           /Users/user/dev/stencil-project/node_modules/@stencil/sass/dist/index.js
           -
           /Users/user/dev/stencil-project/stencil.config.ts
           -
           /Users/user/dev/stencil-project/node_modules/@stencil/core/compiler/stencil.js
           -
           /Users/user/dev/stencil-project/node_modules/@stencil/core/sys/node/index.js
           -
           /Users/user/dev/stencil-project/node_modules/@stencil/core/bin/stencil
           at Function._resolveFilename
           (node:internal/modules/cjs/loader:1410:15) at defaultResolveImpl
           (node:internal/modules/cjs/loader:1061:19) at resolveForCJSWithHooks
           (node:internal/modules/cjs/loader:1066:22) at Function._load
           (node:internal/modules/cjs/loader:1215:37) at
           TracingChannel.traceSync (node:diagnostics_channel:322:14) at
           wrapModuleLoad (node:internal/modules/cjs/loader:234:24) at
           Module.require (node:internal/modules/cjs/loader:1496:12) at require
           (node:internal/modules/helpers:135:16) at Object.<anonymous>
           (/Users/user/dev/stencil-project/node_modules/@stencil/sass/dist/index.js:3:20)
           at Module._compile (node:internal/modules/cjs/loader:1740:14)

```
