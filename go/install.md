# Mac下go环境的安装
* GOPATH
GOPATH是用来告诉Golang命令和其他相关工具，在哪里可以找到你系统上的Go包目录。
- 每一个列表项的路径其实都是一个工作空间，每个工作区都应当包含源文件（src）、相关包（pkg）、执行文件（bin）三个目录。

解压下载下来的go安装包存放到/Users/eonezhang/workspace/devtools/go目录下，并设置GOROOT环境变量
```~/.zshrc
export GOROOT=/Users/eonezhang/workspace/devtools/go
```