# Jest + jest.config.ts fails with monorepo

This is a miimal reproduction of the issue described here: https://github.com/jestjs/jest/issues/11453

Jest fails to load `jest.config.ts` when `type: module` is set in `package.json`, and the package is a sub package of a monorepo.
