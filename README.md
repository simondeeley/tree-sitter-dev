# Nix flake template for tree-sitter

[![built with nix](https://builtwithnix.org/badge.svg)](https://builtwithnix.org)

## How to start

To initialize in the current project, copy the following command:

```shell
nix flake init --template "https://flakehub.com/f/simondeeley/tree-sitter-dev/0.1.0"
```

Alternatively, you can initialize the template in a new project by running:

```shell
nix flake new --template "https://flakehub.com/f/simondeeley/tree-sitter-dev/0.1.0" ${NEW_PROJECT_DIRECTORY}
```

## How to use the template

Once the template has been initialized, you can use the provided shell in two ways:

1. If you have [`nix-direnv`][nix-direnv] installed, you can initialize the environment by running `direnv allow`.
2. If you don't have `nix-direnv` installed, you can run `nix develop` to open up the Nix-defined shell.

## Included Packages

- [Node.js][node] 18.16.1
- [Node.js][node-gyp] 10.2.0
- [npm] 9.5.1
- [tree-sitter] 0.24.6

## tree-sitter
`tree-sitter` is a parser generator for programming languages. It is designed to be fast, small, and embeddable. It is used by many popular editors and IDEs to provide syntax highlighting and code completion. To read more about `tree-sitter`, visit the [official website](https://tree-sitter.github.io/tree-sitter/).

## How to contribute

If you'd like to contribute to this template, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request.
