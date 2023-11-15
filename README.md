Run either `npm install` or `yarn install`

Run `npm run build` to build UI and Custom Server component correctly. 

Run `npm run start` to start the compiled custom server - works without issues.

Run `npm run package` to try and package the app into a single bundle file using NCC. 

Fails with the following error
```
Error: Module not found: Error: Package path ./server.edge is not exported from package C:\dev\test-ncc\node_modules\react-dom (see exports field in C:\dev\test-ncc\node_modules\react-dom\package.json)
Did you mean './react-dom/server.edge'?
Requests that should resolve in the current directory need to start with './'.
Requests that start with a name are treated as module requests and resolve within module directories (node_modules).
If changing the source code is not an option there is also a resolve options called 'preferRelative' which tries to resolve these kind of requests in the current directory too.
Module not found: Error: Package path ./static.edge is not exported from package C:\dev\test-ncc\node_modules\react-dom (see exports field in C:\dev\test-ncc\node_modules\react-dom\package.json)
Did you mean './react-dom/static.edge'?
Requests that should resolve in the current directory need to start with './'.
Requests that start with a name are treated as module requests and resolve within module directories (node_modules).
If changing the source code is not an option there is also a resolve options called 'preferRelative' which tries to resolve these kind of requests in the current directory too.
Module not found: Error: Package path ./server.edge is not exported from package C:\dev\test-ncc\node_modules\react-dom (see exports field in C:\dev\test-ncc\node_modules\react-dom\package.json)
Did you mean './react-dom/server.edge'?
Requests that should resolve in the current directory need to start with './'.
Requests that start with a name are treated as module requests and resolve within module directories (node_modules).
If changing the source code is not an option there is also a resolve options called 'preferRelative' which tries to resolve these kind of requests in the current directory too.
Module not found: Error: Package path ./server-rendering-stub is not exported from package C:\dev\test-ncc\node_modules\react-dom (see exports field in C:\dev\test-ncc\node_modules\react-dom\package.json)
Did you mean './react-dom/server-rendering-stub'?
Requests that should resolve in the current directory need to start with './'.
Requests that start with a name are treated as module requests and resolve within module directories (node_modules).
If changing the source code is not an option there is also a resolve options called 'preferRelative' which tries to resolve these kind of requests in the current directory too.
Module not found: Error: Package path ./server-rendering-stub is not exported from package C:\dev\test-ncc\node_modules\react-dom (see exports field in C:\dev\test-ncc\node_modules\react-dom\package.json)
Did you mean './react-dom/server-rendering-stub'?
Requests that should resolve in the current directory need to start with './'.
Requests that start with a name are treated as module requests and resolve within module directories (node_modules).
If changing the source code is not an option there is also a resolve options called 'preferRelative' which tries to resolve these kind of requests in the current directory too.
Module not found: Error: Package path ./server.edge is not exported from package C:\dev\test-ncc\node_modules\react-dom (see exports field in C:\dev\test-ncc\node_modules\react-dom\package.json)
Did you mean './react-dom/server.edge'?
Requests that should resolve in the current directory need to start with './'.
Requests that start with a name are treated as module requests and resolve within module directories (node_modules).
If changing the source code is not an option there is also a resolve options called 'preferRelative' which tries to resolve these kind of requests in the current directory too.
    at C:\dev\test-ncc\node_modules\@vercel\ncc\dist\ncc/index.js.cache.js:38:1896272
    at C:\dev\test-ncc\node_modules\@vercel\ncc\dist\ncc/index.js.cache.js:38:396262
    at _done (eval at create (C:\dev\test-ncc\node_modules\@vercel\ncc\dist\ncc/index.js.cache.js:21:75523), <anonymous>:9:1)
    at eval (eval at create (C:\dev\test-ncc\node_modules\@vercel\ncc\dist\ncc/index.js.cache.js:21:75523), <anonymous>:34:22)
error Command failed with exit code 1.
```