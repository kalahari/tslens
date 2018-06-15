# TSLens

A VSCode plugin for **typescript** which adds reference code lenses, highlights, gutters for interfaces/classes methods implementations and overrides.

Inspired by tslens extension.

Still under development, but basic functionality is working)

## Works like this:
![Example code with code highlights lens](https://raw.githubusercontent.com/BrainMaxx/tslens/master/screenshot.png)
![Example code with code highlights lens](https://raw.githubusercontent.com/BrainMaxx/tslens/master/screenshot2.png)

## Supported gutters:
![interface](https://raw.githubusercontent.com/BrainMaxx/tslens/master/implementInterface.png) - interface implementation
![interface](https://raw.githubusercontent.com/BrainMaxx/tslens/master/methodEdit.png) - method override
![interface](https://raw.githubusercontent.com/BrainMaxx/tslens/master/fieldEdit.png) - field override

## Configuration properties

- tslens.blackboxTitle
  - Localization for the case where the only usages are from blackboxed sources
- tslens.blackbox
  - Array of glob patterns for blackboxed resources
- tslens.excludeself
  - A flag which indicates whether the initiating reference should be excluded
- tslens.decorateunused
  - A flag which indicates whether the initiating reference should be decorated if it is unsed
- tslens.singular
  - Localization for the singular case
- tslens.plural
  - Localization for the plural case
- tslens.noreferences
  - Localization for the case when there are no references found
- tslens.unusedcolor
  - Color for unused references