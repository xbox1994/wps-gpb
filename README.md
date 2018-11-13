# wps-github.com/xbox1994/wps-gpb
WPS go project builder  

# 运行方式
1. 依赖：Golang、Git，将当前用户的ssh key保存到git远端服务器
2. 在本项目根目录下执行`go install`
3. 在任意目录下执行`github.com/xbox1994/wps-gpb`
4. 按照生成之后的项目内的README文件安装依赖，运行应用

# 参考输入
	RepoName:         "github.com/xbox1994/wps-gpbtest",
	RepoNamespace:    "galaxy",
	Username:         "wangtianyi1",
	Password:         "xxx",
	
# 项目构建方式
1. `go get github.com/rakyll/statik`
2. `statik -src=project/gomicrocli/microTemplate -dest vendor -Z`