# Jest demo

Jest is test runner for javascript. It is best to install jest per project. You will need to install NodeJS and have a `package.json` in your root directory.

## Installing Jest

This command will install jest into your project. Make sure you have a `package.json` in your project and NodeJS installed.
```bash
npm install -D jest @types/jest @babel/preset-env
```

This project is an example of using jest. You put your test files in the `__tests__` directory and import the functions you wish to test. Add assertions to your code using the `expect` function. If the function does not return as expected, there will be an error after running the command.

Run Jest on the command line.
```bash
npm exec jest
```

Use the vscode extension (Jest Runner) found by searching the id `firsttris.vscode-jest-runner`. This extension will add a run or debug icon above each test to execute them individually.


## Documentation

Jest has a solid open source community. You can find many answers by looking through the GitHub issues [https://github.com/facebook/jest](https://github.com/facebook/jest) or looking through their documentation at [https://jestjs.io/](https://jestjs.io/)
