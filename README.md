# Description
A package with browserslist configurations. The goal is to unify browserslist configurations for my projects.

## Usage
1. Install package via npm:

```
npm i --save-dev @qimijoy/browserslist-config
```

2. Add the required configuration in **.browserslistrc** file in your project

```
extends @qimijoy/browserslist-config/configs/<file-name>
```
## List of configurations
### Modern
* Coverage % are taken from  https://browsersl.ist/#q=last+10+versions%0Anot+dead%0Anot+op_mini+all
* Date: August 10, 2024
* Global:    89.4%
* Russia:    66.0%

### Old
* Coverage % are taken from  https://browsersl.ist/#q=%3E+0.1%25
* Date: August 10, 2024
* Global:    93.1%
* Russia:    70.3%


## Adding new configurations
Put the configurations in the configs folder. Each configuration is a CommonJS module that exports an array.
https://github.com/browserslist/browserslist#shareable-configs
