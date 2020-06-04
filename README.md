# branchpanic.me-common

Common files (styles, utils, etc.) for \*.branchpanic.me sites.

This repo is meant to be used as a submodule. Specifically, one named `Common`
placed in `src/` along side Elm and JS source. It primarily acts as an Elm
module, but also contains some shared styling.

As you can probably tell, this has a pretty specific use case...

## Dependencies

Unfortuantey, being a submodule, I can't quite provide dependencies
automatically.

### Elm

- `feathericons/elm-feather`

## Styling

This gets most of the job done:

- `@import` default-colors.css
- Change any variables to your liking
- `@import` base.css
- Add any further site-specific customizations
