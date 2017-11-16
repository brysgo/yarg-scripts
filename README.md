# yarg-scripts

Automatically load git-style subcommand pattern with yargs

# Usage

First install `yarg-scripts` as usual:

`yarn add yarg-scripts` or `npm install --save yarg-scripts`

Then set your bin directive in your `package.json` to point to `yarg-scripts`:

```json
...
  "bin": {
    "<your command name>": "./node_modules/yarg-scripts/index.js"
  },
...
```

Now, create a directory called scripts, and fill it with javascript files that export configuration for yargs subcommands as specified by yarg's `command` function.

See [yargs command documentation](http://yargs.js.org/docs/#api-commandcmd-desc-builder-handler) for more details.
