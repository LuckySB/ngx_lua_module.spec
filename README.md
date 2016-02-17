# ngx_lua_module.spec
spec file for build nginx 1.9.11 with dynamic lua module for Centos 6

Installation
============

1. Install LuaJIT 2.1. LuaJIT can be downloaded from the [LuaJIT project website](http://luajit.org/download.html).

 repack archive with catalog LuaJIT-2.1.0, and set PREREL=
 patched archive of LuaJIT-2.1.0 in src

1. Download the latest version of the ngx_devel_kit (NDK) module [HERE](https://github.com/simpl/ngx_devel_kit/tags).
 
 repack archive an put in SOURCE

1. Download the latest version of ngx_lua [HERE](https://github.com/openresty/lua-nginx-module/tags).

 repack archive an put in SOURCE

1. Download nginx-1.9.11.src.rpm [HERE](http://nginx.org/packages/mainline/centos/6/SRPMS/)
