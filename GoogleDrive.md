
Google Drive

关掉 开机自动启动

[360安全卫士-网络修复-软件全局代理](https://github.com/7900ms/nottheater_deserted/blob/master/supplementary/360安全卫士-网络修复-软件全局代理.txt)



= = = 碎碎念 2016.10.15 = = =


GoogleDriveAPP

正常使用时的条件1 ✓
  断开一切代理 (环境：Proxifier - 不启用 Default-覆盖，代理：不用添加 googledriveAPP 走 1080，GoAgentX StandAlone Mode)
  GD软件 ProxySetting - Direct 即可   ( AutoDetect or Direct 都可以 )
  用 VPN / Cisco IPSec VPN

正常使用时的条件2
  借助代理
  (环境：Proxifier - 不启用 Default-覆盖)
  (代理：添加 googledriveAPP 走 1080)
  (GoAgentX StandAlone Mode)

  可以正常上传 4M 以下的文件
  无法上传 >4M 的文件 ( !难以置信! )
  (除非用VPN / Cisco IPSec VPN)

正常使用时的条件3
  借助代理
  三方软件 Insync

= = =

安装
  dmg

网盘目录结构
  确保 Google Drive 有一个用于 “接受上传” 的文件夹, 目录结构类似

  Google_Drive
    upload ✓
      上传的文件
    download ✓
      下载的文件 (通常是副本)
    sync ✓
      同步的文件 (基本没用)
    disk
      正式的GoogleDrive里的文件
    r
      回收站

上传测试

  小文件 OK
  大文件 (上传4M会断。必须借助VPN)

-

测试文件
http://speedtest-nyc1.digitalocean.com



= = = 碎碎念2 = = =


网盘的考量

  必须保证是一个 永远不会丢失的账户

  专门用来储物

  tasmanboat # gmail

网盘管理

  网页管理，建 F盘

上传工具 / 软件

  网页上传 or 命令行上传
  https://github.com/prasmussen/gdrive

  G google drive command upload

上传目录 / 相关目录

  上传文件存放的目录
  /Users/E02/G/GoogleDrive数据上传/韩国HD-无删减-激情-90分钟.mp4
  确保传完之后再删除

说明

  上传zip文件 (用keka压缩，没有 MACOSX__ 等杂物)



-



