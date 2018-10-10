# clipboard-polyfill-test

Reproduction of issue when using import syntax for clipboard-polyfill in TypeScript.

https://github.com/lgarron/clipboard-polyfill/issues/77

Instructions:

1. Clone repository.
2. `npm install`
3. `npm run start`
4. Navigate in your browser to http://localhost:1234/

To fix the issue:
1. `npm install --save-dev typescript@2.7.1`
3. `npm run start`
4. Navigate in your browser to http://localhost:1234/
