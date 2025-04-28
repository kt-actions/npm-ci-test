# npm-ci-test

NPM Continuous Integration test action

- checkout
- kt-actions/npm-run-script
  - setup node environment (kt-actions/setup-node-minmax, use cache)
  - install dependencies or restore from cache (uses cache)
  - run tests (default: `npm run build && npm test`)
