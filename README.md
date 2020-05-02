# Haffaz Example

An example usage of [Haffaz](https://github.com/tomasbjerre/dictator-haffaz).

Try it by running:

```bash
$ npm install

> dictator-haffaz-example@0.0.1 prepare /home/bjerre/workspace/dictator/dictator-haffaz-example
> npx haffaz@0.0.2

npx: installed 24 in 18.061s
  _                __    __               
 | |__     __ _   / _|  / _|   __ _   ____
 | '_ \   / _` | | |_  | |_   / _` | |_  /
 | | | | | (_| | |  _| |  _| | (_| |  / / 
 |_| |_|  \__,_| |_|   |_|    \__,_| /___|
                                          
  Built with dictator-builder@0.0.5.
  https://github.com/tomasbjerre/dictator-builder

Found 3 dictatables:

 [ 'commitlint', 'linting', 'mix' ]

Applying: copy pre-commit-hook.txt to .git/hooks/pre-commit
Applying: copy gitmessage.txt to .gitmessage
npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN dictator-haffaz-example@0.0.1 No repository field.
npm WARN dictator-haffaz-example@0.0.1 No license field.

up to date in 18.347s
```

Notice: `Applying: ....`. The Haffaz dictator dictates what this repository should look like. So that this code does not need to be duplicated in all repositories!
