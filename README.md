# IdentityServer
IdentityServer和Api合成一个项目
运行时需要读取本地证书，编辑.csproj文件
    `<AspNetCoreHostingModel>`InProcess`</AspNetCoreHostingModel>`移除，或者修改为
    `<AspNetCoreHostingModel>`OutProcess`</AspNetCoreHostingModel>`
