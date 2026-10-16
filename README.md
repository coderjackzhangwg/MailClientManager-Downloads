# 邮件客户端管理工具（MailClientManager）

**适用于 Windows 的本地邮件客户端、离线阅读与归档管理工具。软件免费提供，应用源码目前不公开。**

[下载最新安装包](https://github.com/coderjackzhangwg/MailClientManager-Downloads/releases) · [详细使用说明](docs/USER_GUIDE.md) · [问题反馈](https://github.com/coderjackzhangwg/MailClientManager-Downloads/issues)

## 主要功能

- 支持在 Windows 本地配置 Exchange EWS 及标准 IMAP/SMTP 邮箱，具体连接能力取决于邮箱服务商与管理员策略。
- 提供邮件列表、阅读、搜索、回复和发送功能。
- 可按邮箱选择仅在线阅读、打开后缓存或后台下载完整邮件。
- 支持查看已下载邮件、离线阅读与长期 EML 本地归档。
- 在获得授权的前提下，辅助管理服务器邮箱容量，并将服务器清理与本地存档保留分开处理。
- 支持检查 GitHub 新版本、阅读更新说明、下载并校验安装包。
- 支持 Windows 控制中心、后台任务和系统托盘。

## 下载与安装

1. 打开 [Releases 页面](https://github.com/coderjackzhangwg/MailClientManager-Downloads/releases)。
2. 在对应版本的 Assets 区域下载 `MailClientManager-Setup-版本号.exe`。
3. 如果提供 `SHA256SUMS.txt`，可以用 Windows PowerShell 的 `Get-FileHash` 校验文件。
4. 双击安装包，阅读并确认用户许可与隐私说明。
5. 启动软件，按照自己的邮箱服务商或单位管理员提供的资料添加邮箱账户。

普通用户不需要安装 Python，也不需要下载源码文件。

## 使用说明

**[点击查看完整 Windows 使用指南](docs/USER_GUIDE.md)**

包括邮箱设置、邮件缓存、本地存档、服务器清理、软件更新与常见问题。

## 重要安全说明

本程序主要在用户本人的 Windows 电脑运行。邮件和 EML 存档可能以未加密形式保存在本地，请妥善保护设备并做好独立备份。

企业邮箱访问、导出和删除必须符合所属组织的授权、保密及数据保留制度。服务器永久删除可能无法撤销。

邮件中的远程图片默认受隐私保护，按需加载可能向图片服务器披露 IP 地址及打开时间。

## 软件更新

进入软件内的“软件更新”页面，可以手动检查 GitHub 发布的新版本、阅读更新说明及下载安装包。

安装更新仍需用户自行确认；请先结束正在执行的邮件任务、备份重要数据，再从系统托盘退出旧版并运行新版安装程序。

## 问题反馈

通过 [GitHub Issues](https://github.com/coderjackzhangwg/MailClientManager-Downloads/issues) 报告问题。

**不要公开上传邮箱密码、令牌、真实邮件正文、附件或企业敏感信息。** 即使是脱敏日志，提交前也请检查服务器名称、账号、文件路径等信息。

## 版本与版权说明

本仓库用于公开安装包、使用说明和问题反馈。软件目前免费提供使用，但应用源码不在本仓库开源。第三方组件仍受各自许可证约束。

本工具不是 Microsoft Outlook、Exchange 或其他邮件服务商的官方产品。
