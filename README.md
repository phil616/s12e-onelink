# 云梦镜像营销短链

感谢 https://github.com/afoim/Static_Redirect_Group 提供该项目。

这是一个基于 Cloudflare Worker 的全功能短链服务。它无需服务器，利用 Cloudflare Worker 同时托管静态页面（前端）和 API（后端），并使用 GitHub 仓库作为“数据库”存储重定向规则。

## 赞助原作者

如果这个项目对你有帮助，欢迎 [赞助原作者](https://2x.nz/sponsors) 或给原作者一个 Star ⭐️！

## selfhosting

1. Fork本仓库

2. 创建Cloudflare Worker，连接本仓库

3. 更改静态HTML内硬编码的内容

4. 清理短链。并创建你需要的短链（此时，静态重定向功能已经完全可用）

5. 创建GithubToken

6. 绑定各个机密环境变量

7. 访问 /_url 即可创建短链（此时，动态创建短链功能已经完全可用）

