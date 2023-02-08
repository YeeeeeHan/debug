### Stesp to reproduce

1. `yarn install`
2. `yarn dev`
3. Observe error

```
error - Error [ERR_REQUIRE_ESM]: require() of ES Module /Users/limyeehan/Desktop/debug/node_modules/wagmi/dist/index.js from /Users/limyeehan/Desktop/debug/node_modules/@0xsequence/rainbowkit-plugin/dist/sequence-connector.js not supported.
Instead change the require of index.js in /Users/limyeehan/Desktop/debug/node_modules/@0xsequence/rainbowkit-plugin/dist/sequence-connector.js to a dynamic import() which is available in all CommonJS modules.
    at Object.<anonymous> (/Users/limyeehan/Desktop/debug/node_modules/@0xsequence/rainbowkit-plugin/dist/sequence-connector.js:15:17)
    at Object.<anonymous> (/Users/limyeehan/Desktop/debug/node_modules/@0xsequence/rainbowkit-plugin/dist/sequence-wallet.js:13:30)
    at Object.<anonymous> (/Users/limyeehan/Desktop/debug/node_modules/@0xsequence/rainbowkit-plugin/dist/index.js:17:14)
    at @0xsequence/rainbowkit-plugin (/Users/limyeehan/Desktop/debug/.next/server/pages/index.js:129:18)
    at __webpack_require__ (/Users/limyeehan/Desktop/debug/.next/server/webpack-runtime.js:33:42)
    at eval (webpack-internal:///./src/pages/index.tsx:16:87)
    at __webpack_require__.a (/Users/limyeehan/Desktop/debug/.next/server/webpack-runtime.js:97:13)
    at eval (webpack-internal:///./src/pages/index.tsx:1:21)
    at ./src/pages/index.tsx (/Users/limyeehan/Desktop/debug/.next/server/pages/index.js:108:1)
    at __webpack_require__ (/Users/limyeehan/Desktop/debug/.next/server/webpack-runtime.js:33:42)
    at __webpack_exec__ (/Users/limyeehan/Desktop/debug/.next/server/pages/index.js:282:39)
    at /Users/limyeehan/Desktop/debug/.next/server/pages/index.js:283:28
    at Object.<anonymous> (/Users/limyeehan/Desktop/debug/.next/server/pages/index.js:286:3)
    at Object.requirePage (/Users/limyeehan/Desktop/debug/node_modules/next/dist/server/require.js:88:12)
    at /Users/limyeehan/Desktop/debug/node_modules/next/dist/server/load-components.js:48:73
    at async Object.loadComponents (/Users/limyeehan/Desktop/debug/node_modules/next/dist/server/load-components.js:48:26)
    at async DevServer.findPageComponents (/Users/limyeehan/Desktop/debug/node_modules/next/dist/server/next-server.js:563:36)
    at async DevServer.findPageComponents (/Users/limyeehan/Desktop/debug/node_modules/next/dist/server/dev/next-dev-server.js:1041:20)
    at async DevServer.renderPageComponent (/Users/limyeehan/Desktop/debug/node_modules/next/dist/server/base-server.js:951:24)
    at async DevServer.renderToResponse (/Users/limyeehan/Desktop/debug/node_modules/next/dist/server/base-server.js:980:32)
    at async DevServer.pipe (/Users/limyeehan/Desktop/debug/node_modules/next/dist/server/base-server.js:407:25)
    at async Object.fn (/Users/limyeehan/Desktop/debug/node_modules/next/dist/server/next-server.js:759:21)
    at async Router.execute (/Users/limyeehan/Desktop/debug/node_modules/next/dist/server/router.js:253:36)
    at async DevServer.run (/Users/limyeehan/Desktop/debug/node_modules/next/dist/server/base-server.js:384:29)
    at async DevServer.run (/Users/limyeehan/Desktop/debug/node_modules/next/dist/server/dev/next-dev-server.js:743:20)
    at async DevServer.handleRequest (/Users/limyeehan/Desktop/debug/node_modules/next/dist/server/base-server.js:322:20) {
  code: 'ERR_REQUIRE_ESM',
  page: '/'
}
```
