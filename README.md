# ball
球球大作战，前端分h5、u3d版，后端skynet

# macos平台

# skynet

## 编译

```shell

# make macosx

```

# lua-cjson
- 该仓库下的 lua-cjson 支持 Lua5.4.x, fork from [mpx/lua-cjson]
## 编译
- 修改 Makefile , 打开 Maxos 平台的编译参数
 ```txt
  ## MacOSX (Macports)
  PREFIX =            /opt/local
  CJSON_LDFLAGS =     -bundle -undefined dynamic_lookup
 ``
执行 make install 编译并安装
