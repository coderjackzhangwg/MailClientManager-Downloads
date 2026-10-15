# Windows 安装指引

1. 在本仓库的 **Releases** 中下载对应版本的安装程序及 `SHA256SUMS.txt`。
2. 在 PowerShell 中验证安装包完整性：

   ```powershell
   Get-FileHash -Algorithm SHA256 -LiteralPath 'C:\Users\你的用户名\Downloads\MailClientManager-Setup-版本.exe'
   ```

   将输出与同一 Release 的 `SHA256SUMS.txt` 比较。
3. 运行安装包，阅读用户许可协议和隐私说明后选择是否继续。
4. 首次使用时自行配置已获授权的邮箱。不要使用未获授权的公司邮箱。
5. 控制中心可打开本地网页。托盘菜单可明确退出程序；开机后台启动是可选项。

本地邮件归档及数据库与程序安装目录分开保存。卸载软件不一定会清理这些数据，应按自身数据保存政策管理。

## 遇到问题

打开软件的日志页面导出排障文件，**先自行删除敏感内容**，再通过支持渠道反馈。不要在 GitHub Issues 公开原始日志、邮件正文、附件或密码。
