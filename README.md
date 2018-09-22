# TypeScript starter for Lerna based projects

- https://github.com/lerna/lerna

### Installation
```
npm install
```

### Compile and publish
```
npm run publish
```

### Important bits

- Project have three packages which are connected to npm organization @hospital-sdk/*
- Each package have own tsconfig.json which inherit base config from project root
- Each package have *src* folder where all *TypeScript* files are placed
- Each package have custom npm script *tsc*, which is triggered by *lerna run tsc* before publishing

### Integration

*integration* folder download, install and use published packages from NPM.