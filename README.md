# grid-users-list

## Task

TBD in English

### What I did not do because of time constraints:

 - no yellow square animation
 - no grid usage (I am not familiar with it)

## Installation

```bash
git clone git@github.com:kzadurska/grid-users-table.git
cd grid-users-table
npm ci
```

## Development

* `npm start`
The app will be available at http://0.0.0.0:8080/

## Contributing
### Code quality
#### Manual

* To lint files run `npm run lint`
* To format code run `npm run prettier`

Both accept `:fix` parameter that'll try to automatically fix whatever is possible.

##### Editor

We recommend to set up your code editor of choice to prettify and lint files `on type` or `on save`.

#### Git hooks
We have two git hooks set up to lint and test files

* `Pre-commit` - run prettier and eslint on files staged for commit, add modified/fixed files to commit
* `Pre-push` - run prettier, eslint and jest on all files. Push will fail if any of these fail.

## Deployment
Run `npm run deploy` and go to https://kzadurska.github.io/grid-users-table/