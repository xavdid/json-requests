# Changelog

## 0.3.0

_released `2024-03-29`_

- Drop `node-fetch` dependency. Now it's properly dependency free! Should also work with other popular JS runtimes that have a global fetch.
- :exclamation: require Node.js 20+

## 0.2.2

_released `2023-02-14`_

- Properly include all `*.d.ts` files in the released package, for real this time.

## 0.2.1

_released `2023-02-14`_

- Properly include all built files in the released package. Thanks to @scottbessler for the report! (https://github.com/xavdid/json-requests/pull/4)
- Move `@types/...` dependencies into `devDevepencies` (https://github.com/xavdid/json-requests/pull/4)

## 0.2.0

_released `2023-02-12`_

- Problems with HTTP and JSON parsing now throw custom errors. See the `README` for more info (https://github.com/xavdid/json-requests/pull/1)
- replace usage of Node's `querystring` module with the more universal `URLSearchParams` (https://github.com/xavdid/json-requests/pull/2)

## 0.1.0

_released `2023-01-23`_

This is the initial public release. The API is considered stable, but I want to test it under more real-world conditions before dropping a v1.

- Initial public release
