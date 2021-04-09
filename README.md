# QuantumultX网易云音乐版权解锁
第一步、下载CA证书，前往“设置-通用-描述文件”，安装「UnblockNeteaseMusic Root CA」，然后在“设置-通用-关于本机-证书信任设置”处开启对「UnblockNeteaseMusic Root CA」的信任。
CA证书（复制到浏览器中打开）：https://github.com/nondanee/UnblockNeteaseMusic/raw/master/ca.crt

第二步、添加网易云音乐策略组，分流订阅，以及解锁所需的节点。
# 策略组
[policy]
static=网易云音乐, resource-tag-regex=网易云音乐解锁, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/Netease.png

# 远程分流规则订阅
[filter_remote]
https://raw.githubusercontent.com/GlitterZero/QuantumultX/NeteaseMusic/NeteaseMusic.list, tag=解锁网易云音乐, force-policy=网易云音乐, update-interval=86400, opt-parser=true, enabled=true

# 服务器引用（节点订阅）
[server_remote]
https://raw.githubusercontent.com/GlitterZero/QuantumultX/NeteaseMusic/NeteaseMusic_jd.txt, tag=网易云音乐解锁节点, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/Netease.png, update-interval=86400, opt-parser=true, enabled=true
