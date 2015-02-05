# doc-resources
Ontotext documentation resources

Adding this repository as submodule to another repository
---------------------------------------------------------
1. Go to the root of your git repository clone
2. Adding submodule via:
 * assets - `git submodule add -b assets --name assets https://github.com/Ontotext-AD/doc-resources.git assets`
 * release - `git submodule add -b release --name release https://github.com/Ontotext-AD/doc-resources.git release`
 * _layouts -`git submodule add -b _layouts --name _layouts https://github.com/Ontotext-AD/doc-resources.git _layouts`
3. Now you are ready to commit new directory `assets`, `release`, `_layouts` and `.gitmodules` file.


Cloning a documentation repository and fetching the submodule
---------------------------------------------------------

If you're cloning a documentation repository, the `assets`, `release` and `_layouts` folder may be empty. To fetch it run:
`git submodule update --init --recursive`

Ref:  http://git-scm.com/book/en/v2/Git-Tools-Submodules#Cloning-a-Project-with-Submodules
