when running `npm install` it installs `@angular/compiler` in the root node_modules dir which is the expected behavior.
but it installs `@angular/router` in child/node_modules, it should be installed in the root node_modules

also, the dependencies of it such as `rxjs` are installed in the child dir even no other versions of the same packages

the project is created in a clean and empty folder, and I cleared the npm cache
