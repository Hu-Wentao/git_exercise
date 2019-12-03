## Git 报错：error setting certificate verify locations
    证书地址设置有误
    解决方案1
        在命令行输入
        git config --system http.sslverify false
    解决方案2
        Git 目录下的 Git\mingw64\etc\gitconfig 文件，编辑该文件，将 sslCAInfo 的地址设置为正确的地址