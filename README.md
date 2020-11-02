# Base ESLint + Prettier config for new projects

## Installation

1. Use `install-peerdeps` to install this package with peer dependencies. The arguments below install it as a `devDependency` using `yarn`.

```
npx install-peerdeps -D -Y eslint-config-nhuesmann-base
```

2. Create `.eslintrc.js` in the root directory with the following:

```
module.exports = {
  extends: ['nhuesmann-base'],
};
```

3. Start writing code!
