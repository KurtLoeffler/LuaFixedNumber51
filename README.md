# Lua Fixed Number 5.1

A modified Lua 5.1 source code that uses fixed point numbers instead of doubles. Uses `fpm` for the fixed point implementation.

## Compiling
Must be compiled as C++ due to the usage of `fpm`.

Should be compiled and included with `LUA_FIXEDNUMBER` and `LUA_FIXEDNUMBER_MOD` defined.

The default fixed point format is 20:12 but it can be changed with the `FixedPoint` typedef in `luaconf.h`.
