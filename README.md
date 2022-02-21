# opengl-tutorial
OpenGL tutorial

## linux开发环境配置
### 安装OpenGL库
```
sudo apt-get install libgl1-mesa-dev
```
### GLFW
下载源代码 http://www.glfw.org/docs/latest/compile_guide.html
cmake编译

### GLAD
https://glad.dav1d.de/

在这个网站上生成合适的库，我选择了 C/C++ OpenGL Core Version 4.6 然后点击 GENERATE 即可得到压缩包。把压缩包内 include 目录的东西放到本机 include 目录下(/usr/include), 把 src 下的源码拷贝到工程内。