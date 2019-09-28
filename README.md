# CE Array Utils
> Array utility scripts

![License](https://img.shields.io/github/license/kraifpatrik/ce-array-utils)

# Example
```gml
// Here the script scr_reduce_add(a, b) returns a + b
var _a = [1, 2, 3, 4];
var _r1 = ce_array_reduce(_a, scr_reduce_add); // Results to 10
var _r2 = ce_array_reduce(_a, scr_reduce_add, 5); // Results to 15
```

# Installation
Using [Catalyst](https://github.com/GameMakerHub/Catalyst), the open-source package manager for GameMaker Studio 2:

```
catalyst require kraifpatrik/ce-array-utils
```

# Related
This library is a part of project CE. For more information, please visit the project's repository: https://github.com/kraifpatrik/ce
