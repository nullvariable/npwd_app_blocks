Blocks © 2024 by Nullvariable is licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc-sa/4.0/

![Blocks Demo](https://raw.githubusercontent.com/nullvariable/npwd_app_blocks/master/blocks.gif)

# Installing
* Download the latest [release](https://github.com/nullvariable/npwd_app_blocks/releases/download/v1.0.0/v1.0.0.zip).
* Add to your NPWD:
```

  "apps": [
    ...
    "npwd_app_blocks"
  ],
```
* Add to your server.cfg and ensure it starts before NPWD

# Building
I use bun, but npm pnpm or whatever the latest hotness is should work too
```
cd src
bun install
bun run build
```
