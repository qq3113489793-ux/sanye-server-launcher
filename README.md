# 三叶的服务器启动器 / Sanye Server Launcher

A community server launcher for Windows, customized from [PCL Community Edition](https://github.com/PCL-Community/PCL-CE).

## 项目介绍

本项目由三叶维护，是基于 PCL Community Edition 修改的服务器专用启动器，面向自己的 Minecraft Java Edition 服务器社区。

主要功能：

- 选择社区服务器，检查在线状态，并根据服务器日志推算在线玩家名单。
- 比较远端与本地模组文件名，由玩家选择下载、替换或忽略。
- 下载替换前展示本地匹配目标；替换时禁用旧模组，目标为空时只下载。
- 保存服务器选择和忽略记录，启动并连接所选服务器。
- 玩家版不提供管理员密钥输入、上传模组或保存重启功能。

## Microsoft sign-in and API access

We are applying for Minecraft Java Edition game service API access for our own Microsoft application registration. The intended sign-in flow uses Microsoft OAuth device authorization, followed by Xbox Live, XSTS and Minecraft services authentication, ownership verification, and player profile retrieval. Users authenticate their own accounts through Microsoft's sign-in pages; the launcher does not collect Microsoft account passwords.

Full Microsoft sign-in in this customized build is pending application configuration, API approval and end-to-end testing. Existing cached-session compatibility does not replace a valid authentication session for online-mode servers.

## 项目状态与说明

这是测试中的第三方定制项目，不是 Mojang、Microsoft 或 PCL CE 官方发布的产品。项目基于 PCL CE；上游作者及社区贡献者的权利和署名应保留。

本仓库目前仅提供项目介绍，不提供程序或完整源码。此介绍页不授予上游项目代码的额外许可。

模组文件名相似度推荐需要玩家核对；日志推算的在线名单可能受日志缺失等情况影响。服务器面板权限由面板端控制，不能依靠客户端隐藏凭据保证安全。

## Contact / 联系方式

Maintainer: [三叶 (@qq3113489793-ux)](https://github.com/qq3113489793-ux)

Questions and feedback: please open an issue in this repository. Never post passwords, access tokens, panel API keys or account cache files.
