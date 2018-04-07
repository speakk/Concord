# Concord

Concord is a feature complete ECS.
It's main focus is on speed and usage. You should be able to quickly write code that performs well.

Documentation for Concord can be found in the Wiki tab

## Installation
Download the repository and drop it in your project, then simply require it as:
```lua
local Concord = require(PathToConcord).init({

})
```

## Configuration
Concord has a initialization function which takes a table of boolean parameters:
| Name | Default | Meaning |
| --- | --- | --- |
| useEvents | false | Lets Concord overwrite love.run and automatically propagate events |

You will only need to call .init once. 

## Modules
Below is a list of modules.
More information about what each done can be found in the Wiki

```
local Concord = require("concord")
local Entity = require("concord.entity")
local Component = require("concord.component")
local System = require("concord.system")
local Instance = require("concord.instance")
```
