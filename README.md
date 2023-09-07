# Description
A package with browserslist configurations. The goal is to unify browserslist configurations for my projects.

## Usage
1. Install package via npm:

```
npm i --save-dev @qimijoy/browserslist-configs
```

2. Add the required configuration in **.browserslistrc** file in your project

```
extends @qimijoy/browserslist-configs/configs/<file-name>
```

## Adding new configurations
Put the configurations in the configs folder. Each configuration is a CommonJS module that exports an array.
https://github.com/browserslist/browserslist#shareable-configs
