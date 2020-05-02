# Cypress Dictator Example

An example usage of [Cypress Dictator](https://github.com/tomasbjerre/dictator-cypress).

This example will download the `dictator-cypress` package published in `registry.npm.org` which contains fake `cypress.zip`. You will need to publish your own package with not fake zip-files.

Try it by running:

```bash
$ npm install

> dictator-cypress-example@0.0.1 prepare /home/bjerre/workspace/dictator/dictator-cypress-example
> npx dictator-cypress@0.0.9

      _   _          _             _                                                                           
   __| | (_)   ___  | |_    __ _  | |_    ___    _ __            ___   _   _   _ __    _ __    ___   ___   ___ 
  / _` | | |  / __| | __|  / _` | | __|  / _ \  | '__|  _____   / __| | | | | | '_ \  | '__|  / _ \ / __| / __|
 | (_| | | | | (__  | |_  | (_| | | |_  | (_) | | |    |_____| | (__  | |_| | | |_) | | |    |  __/ \__ \ \__ \
  \__,_| |_|  \___|  \__|  \__,_|  \__|  \___/  |_|             \___|  \__, | | .__/  |_|     \___| |___/ |___/
                                                                       |___/  |_|                              
  Built with dictator-builder@0.0.14.
  https://github.com/tomasbjerre/dictator-builder

Copy linux cypress to cypress.zip
    Up to date: copy linux-x64.zip to cypress.zip
.npmrc should have reference to cypress binary
    Up to date: .npmrc should have lines
.gitignore should include the copied zip
    Up to date: .gitignore should have lines
```


```bash
$ ls
cypress.zip  package.json  package-lock.json  README.md
```


```bash
$ cat .npmrc 
CYPRESS_INSTALL_BINARY=cypress.zip
```
