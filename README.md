# K6 Template TypeScript

Template project derived from [`grafana/k6-template-typescript`](https://github.com/grafana/k6-template-typescript)

## Why

- Remove Webpack dependency to only use `tsc`
- ESLint

## Getting started

### Prerequisites

- k6
- NodeJS
- Yarn

### Usage

```bash
# Pull down dependencies
yarn

# Compile TypeScript
yarn build

# Run a test
k6 run dist/get-200-status-test.js
```

## Credits

All original contributions go to [`grafana/k6-template-typescript`](https://github.com/grafana/k6-template-typescript).
