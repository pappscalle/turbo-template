## Template usage & submodules

This repository was created from a template.

### External dependncies

This project uses external Turbo Pascal Unit (`.tpu`) files, included via a Git subtree.

The is lcated at `src/external/src/units`

### Creating a new repository from this template

After creating a new repository from this template, clone it:
```
git clone git@github.com:pappscalle/my-cloned-repo.git
```
### Initializing or syncing submodules
To setup and download the units subtree, run the *init-units-script*
```
./init-units.sh
```
### Updating the submodule to the latest version
If you want the newest version of the units, you cab update them by running: 
```
./update-units.sh
```
