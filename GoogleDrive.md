
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



