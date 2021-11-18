
# dead-exports

**Find unused exports in your project.**
this includes classes, functions and anonymous functions

use npx:

    npx dead-exports

or with settings:

    npx dead-exports --e=folder --s=ignore,ingnoreMe

to change entry folder and ignore some folders


by default it will look recursively in your ./src folder but this can be changed
if you don´t want a folder to be searched use --s (skip), this can be handy if you have a subrepo.

| Command  | Explanation |- Default  | Example |
|--|--|--|--|
|--e=    | sets the entry of the search  | --e=./src | npx dead-exports --e=folder
| --s= | ignore some folders  |--s= |npx dead-exports --s=ignore,ingnoreMe

please report any bugs at https://github.com/Tobbb/dead-exports
