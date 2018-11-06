# hello-lua

## Requirements
* Lua rocks:
  * [hellofromlua](https://github.com/hfagerlund/hellofromlua_rock/) v1.0-1

## Usage

```shell
# clone hello-lua repo
$ git clone https://github.com/hfagerlund/hello-lua.git
$ cd hello-lua
# clone hellofromlua rock repo
$ git clone https://github.com/hfagerlund/hellofromlua_rock.git
# install dependencies to local tree
$ cd hellofromlua_rock
$ luarocks make --local
# verify installation of hellofromlua module
$ luarocks list
## or
$ luarocks show hellofromlua
# (for Linux) run the following
$ luarocks path --bin
## ...and add export LUA_PATH, LUA_CPATH and PATH values from the above output to .bashrc (or .zshrc)
# compile
$ cd ..
$ lua helloFromLua.lua
```

- - -

## License
Copyright (c) 2018 Heini Fagerlund. Licensed under the [3-Clause BSD License](https://github.com/hfagerlund/hello-lua/blob/master/LICENSE).
