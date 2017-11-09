＃声明使用的基础镜像
从微软/ aspnetcore：1.1
＃将本地dotnet核心应用拷贝到容器/ app /目录下
＃ COPY /root/.jenkins/workspace/Docker/Solution1/WebApplication1/bin/Debug/netcoreapp1.1/publish/ /应用/
＃设置工作目录
＃ WORKDIR /应用/
＃设置导出端口
EXPOSE 8082 / tcp
＃指定应用入口点
ENTRYPOINT [ “dotnet”，“/root/.jenkins/workspace/Docker/Solution1/WebApplication1/bin/Debug/netcoreapp1.1/publish/WebApplication1.dll” ]

