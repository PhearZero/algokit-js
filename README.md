# Overview

This is a workspace for resolving deep issues across several projects. It is uses as needed

# Get Started

Setup submodules and checkout working branch

```bash
git clone git@github.com:PhearZero/algokit-js.git
git checkout fix/linking
git submodule update --init --recursive
```

Install dependencies

```bash
npm install
```

Build tools

```bash
npm run build -w @makerx/ts-toolkit
npm run build -w @algorandfoundation/algokit-utils
npm run build -w @algorandfoundation/algokit-client-generator
```

Run tests

```bash
npm run test:ci -w @algorandfoundation/algokit-client-generator
```
