# git-fly

A command line tool to temporarily clone, run and open git repos on the fly.

To get started install git-fly globally:

`npm install -g git-fly`

Then run the command:

`git-fly`

### git-fly asks for 3 things:

#### repo URL
(required) This is the URL of the repo to clone.

#### run command
(optional) The command to run after cloning the repo.

For example: http-server, npm start etc.

#### open command
(optional) The command to open the cloned repo directory.

For example: atom, open etc.

If a package.json file is detected, git-fly will offer to run npm install.

To skip the questions, you can pass options to git-fly:

```
  Usage: git-fly <git repo> [options]

  Options:

    -h, --help            output usage information
    -V, --version         output the version number
    -r, --run [command]   run command
    -o, --open [command]  open command
```

![](http://i.imgur.com/6HwyoWC.png)
