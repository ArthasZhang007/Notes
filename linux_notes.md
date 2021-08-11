# `xxx` 包裹用法
zip result.zip `ll | grep '.json\|.png' | awk '{print $NF}'`
grep 过滤程序
\| 或

# vim ~/.bashrc 
bashrc bash_shell setup \
~根路径 \
.隐藏文件 \
ln 软链接 \
ls \
`pwd` 当前路径 \
> < 重定向 \
SET(OpenCVDIR xxx) 路径 \
LD_LIBRARY_PATH = xx:$LD_LIBRARY_PATH \
xx:新的附加路径, :$ 拼上原来的而不是覆盖 \
mount 挂载 \
nfs 服务器服务 \

HTTP_PROXY: 代理 \
-o: 可执行文件 \
-w: 忽略warning \
-fpermissive: 所有warning均视为error \
-DDEBUG, -DOPENCV 宏控制参数 \
