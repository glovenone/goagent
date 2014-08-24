DON'T PANIC
部署
申请Google Appengine并创建appid。
下载goagent最新版 https://code.google.com/p/goagent/
修改local\proxy.ini中的[gae]下的 appid = 你的appid(多appid请用|隔开)
    双击server\uploader.bat 开始上传, 成功后即可使用了(地址127.0.0.1:8087)
    MacOS/Linux 请在 Terminal 执行 cd server && python uploader.zip
    使用
    Chrome请安装 SwitchySharp 插件（拖放 SwitchySharp.crx 到扩展设置），然后导入 SwitchyOptions.bak
    Firefox请安装 FoxyProxy ，Firefox需要导入证书，方法请见 FAQ
    IE/Opera 用户请右击 goagent.exe 托盘图标设置 IE 代理。
    连接不上的用户可以尝试使用 GoGo Tester 测速。
