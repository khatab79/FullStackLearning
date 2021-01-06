This project for self learning 
## installation checking

`Check first the following` pls, be sure to be installed in the system.

```
yarn -v
1.22.5

node -v
v14.15.4

npm -v
6.14.10
```

In the project directory, you can run:

### `yarn start`

by targetting ` "node dist/index.js" `

### or by `yarn dev`

by targetting ` "nodemon dist/index.js" `

### `yarn watch`
this to make the output watching for any change and update it directly to gain time and make it faster.
this watch will be start by both previous syntax.
and will targetting `"tsc -w"`

start one terminal by using ` yarn watch ` then the other terminal by using ` yarn dev `

you should have the following output

```

Windows PowerShell
File change detected. Starting incremental compilation...

Found 0 errors. Watching for file changes.

```

and the other terminal output

```
PS C:\myWork\FullStackProject> yarn dev  
yarn run v1.22.5
$ nodemon dist/index.js
[nodemon] 2.0.7
[nodemon] to restart at any time, enter `rs`
[nodemon] watching path(s): *.*
[nodemon] watching extensions: js,mjs,json
[nodemon] starting `node dist/index.js`
helllo world
[nodemon] clean exit - waiting for changes before restart
[nodemon] restarting due to changes...
[nodemon] starting `node dist/index.js`
helllo yarn
[nodemon] clean exit - waiting for changes before restart
```



