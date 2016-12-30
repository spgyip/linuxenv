.vimrc
.gitconfig

## 其它需要单独安装的插件
- ctags
- cscope

## vim-go
vim-go依赖go本身提供的工具进行整合，例如gocode、godef、goimports等。

运行
```:GoInstallBinaries```
这些依赖的库会被安装到$GOPATH/bin/


安装gotags
```
go get -u github.com/jstemmer/gotags
```

