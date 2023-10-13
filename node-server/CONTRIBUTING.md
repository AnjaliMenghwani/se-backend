# Contributing Guide

1. Fork this repository
1. Clone the forked repository onto your computer
1. Run
    ```bash
    cd node-server
    npm install
    ```
1. Make your code changes in [`node-server`](./node-server/) and write appropriate tests
    1. Keep your test files in `spec` directory as `spec/<filename>Spec.js` (check [`spec/indexSpec.js`](./spec/indexSpec.js) for template)
    1. To run a specific test file, use `npm test spec/<filename>.js`
    1. Validate all tests using `npm test`
1. Use docker to run the project locally as described in [`README.md`](../README.md).
1. After satisfaction, commit and push your changes.
1. Submit a pull request (PR)
1. Follow the comments on your PR