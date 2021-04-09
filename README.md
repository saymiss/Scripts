
# Zero｜Surge&QuantumultX频道：https://t.me/Light_Zero

# QuantumultX_Zero入门配置：
https://raw.githubusercontent.com/GlitterZero/QuantumultX/main/Zero.conf

新导入配置的用户，添加机场订阅之后，开启全局模式更新配置内容

# 策略、分流及重写：
引用神机分流规则/Nobyda的去广告分流、脚本重写订阅

# BoxJS httpbackend配置

[http_backend]
https://raw.githubusercontent.com/chavyleung/scripts/master/chavy.box.js, tag=BoxJs, path=^/, enabled=true

Quantumult X 用户配置BoxJs改为使用http backend方式，访问地址改为http://127.0.0.1:9999 ，更新配置后请长按风车-更新，然后重启代理之后再开启backend开关

BoxJs配置使用说明: https://chavyleung.gitbook.io/boxjs/#quanx

# QuantumultX SSID设置
用翻墙路由器的可以设置一下SSID，无的话直接无视就行，毕竟用不上
[general]
#第一个filter为4g模式开启规则分流，第二个filter为其他wifi下开启规则分流，第三个wifi1修改成你路由器翻墙的wifi名开启直连模式，第四个wifi2为你需要全局代理的wifi名（这个一般不需要随便写就行）

#默认关闭根据wifi切换模式，如需开启，删除下方的“#”即可！

#running_mode_trigger=filter, filter, 你家wifi名:all_direct, 你家wifi名:all_direct, 你家wifi名2: all_proxy

# Task脚本库整理：
为大家整理好的大佬们的 Task脚本仓库 方便大家使用

♻️ Ease整理羊毛合集：https://gitee.com/ydj0602/hym/raw/master/Ease1.json

♻️ 锄禾整理合集：https://dove.589669.xyz/task2qxgallery?sub=https://raw.githubusercontent.com/ChuheGit/1/main/Surge/Module/Task.sgmodule&img=1

♻️ 少年歌行合集：https://raw.githubusercontent.com/sngxpro/QuanX/master/task/AllinOne.json

♻️ 少年歌行整理肥皂羊毛合集：https://raw.githubusercontent.com/sngxpro/QuanX/master/task/age174.json

♻️ HotKids：https://raw.githubusercontent.com/HotKids/Rules/master/Quantumult/X/TaskGallery.json

♻️ blackmatrix7: https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/gallery.json

♻️ lxk 大佬京东合集：https://jdsharedresourcescdn.azureedge.net/jdresource/lxk0301_gallery.json

♻️ Peng-YM：https://gist.githubusercontent.com/Peng-YM/cc2cd6205b305d36544a44ec77129832/raw/gallery.json

♻️ HuiDoY自用薅羊毛脚本收集（cookie获取在附件）：https://raw.githubusercontent.com/HuiDoY/QX_Task/main/H.json

只为了方便大家使用Task脚本，不定期补充，脚本需求的Cookie 重写，请自行解决

# 策略组图标：
引用契阔设计的策略图标-mini图标聚合频道：https://t.me/Orzmini
