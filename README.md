# dead-exports
Find unused exports in your project.

this includes classes, functions and anonymous functions

use npx:

npx dead-exports

by default it will look recursively in your ./src folder but this can be changed with --e=path (default ./src)
if you don´t want a folder to be searched use --s (skip), this can be handy if you have a subrepo. 
use  --s=folder,folder or --s=folder (default empty) 

please report any bugs at https://github.com/Tobbb/dead-exports