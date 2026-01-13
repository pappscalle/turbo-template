# dos-template

A simple Turbo Pascal program used as a template.
Target computer: 286-12MHz

Uses external tpu files, added via "git submodule"
They will reside in `src/external/src/units`

To set up the external submodule:

```
git submodule add https://github.com/pappscalle/dos-tp-units.git src/external
```

If the submodule is not downloaded:

```
git submodule update --init --recursive
```
