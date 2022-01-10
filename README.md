# How to update the jsdeliver version

When changes to the script are made:

1. Update the src/ files.
2. run `npm run mini` un your terminal.
3. update the version on the dist/package.json
4. run `cd dist`
5. run `npm publish` (you will need to login if you haven't).
6. Purge jsdelivr by entering to this link https://purge.jsdelivr.net/npm/six_vertical/
