# How to update the jsdeliver version

## Using npm

When changes to the script are made:

1. Update the src/ files.
2. run `npm run mini` un your terminal.
3. update the version on the dist/package.json
4. run `cd dist`
5. run `npm publish` (you will need to login if you haven't).
6. Purge jsdelivr by entering to this link https://purge.jsdelivr.net/npm/six_vertical/

## Using github

to upload new versions you just change the files inside the src folder in the Github repository using the GitHub webpage. And create a new release following this instructions https://docs.github.com/es/repositories/releasing-projects-on-github/managing-releases-in-a-repository
