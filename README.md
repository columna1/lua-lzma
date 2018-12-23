# lua-lzma
a simple lua bindings for lzma
Edited to be compatible with lua 5.1/luajit
* **LZMA SDK** Copyright (C) 1999-2010 Igor Pavlov

## Usage
```lua
local lzma = require "lzma"

local src = [[
local lzma = require "lzma"
local src = [[

]]
local comp = lzma.compress(src)
assert(lzma.uncompress(comp) == src)
]]

local comp = lzma.compress(src)
assert(lzma.uncompress(comp) == src)

```
