# How to contribute

## Table of contents
* [Headers](#Headers)
* [TODO comments](#TODO-comments)
* [Documentation](#Documentation)
* [Commits](#Commits)
* [Readme](#Readme)
* [Testing](#Testing)

## Headers
If you want to add a new file, you must add the copyright line at the top of this.
```ts
// Copyright 2020 Fazt Community ~ All rights reserved. MIT license.
```

## Documentation
We use [JSDoc](https://jsdoc.app/) to documentate anywhere, if you are using Visual Studio Code you can install [Add jsdoc comments extension](https://github.com/Microsoft/vscode-comment) to make them.

## TODO comments
TODO comments should include an issue or the author's github username in parentheses. Example:
```ts
// TODO(fazt): Add tests.
// TODO(#123): New endpoint.
// FIX(#456): Endpoint error.
```

## Commits
The commits must start with the action executed. Example:
```ts
// refactor(commands): Add descriptions.
// fix(endpoint): Get all users.
```

If the commit can have compatibility errors, you must use `!` between `)` and `:`. Example:
```ts
// refactor(embeds)!: Moved embeds to embeds folder.
```

## Readme
If you change any file or add a new feature, you can add yourself in the README file of the project. It must be as follows:
```md
# Contributors
<!-- Other contributors -->
* **Your name** [GitHub](https://github.com/Your username)
```

## Testing
You must test your changes before making commits to the branch, making sure those changes don't break the app and work as expected. Every project has its own tests and you must adapt to it. The tests can be manual but better if they are automatic.
