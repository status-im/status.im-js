# status-im-js
A repo for all the shared JS across our websites

## How to use

To add to a new static website.
- `cd` down to where you want the JS folder added. e.g. from project route: `cd themes/navy/source/js`
- `clone` the repo as a submodule: `git submodule add git@github.com:status-im/status-im-js.git shared-js`
- you can then reference files in `/themes/navy/source/js/shared-js`
	- e.g. in a status static site, this would be done by adding them to the js sources array in the gulp file