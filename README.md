## 使用方法[视频]
1. 新建一个私人仓库，项目可随意命名，但要避开BPB敏感词。
2. 在该项目创建`.github/workflows/Obfuscate.yml`。
3. 复制`创建仓库源码.js`的代码，粘贴到项目，保存。
4. 点击`Obfuscate.yml`旁边的小黄点同步到 BPB 代码，同步完成生成`_worker.js`与`origin.js`，前者是混淆代码，后者是明文代码。
7. 到`Cloudflare`里创建`Pages+github`，找到刚刚的 github 项目，用其创建Pages项目，并修改下面的变量及绑定 kv 空间。
8. 引用请注明出处：[SO启程Github](https://github.com/Setout8/Book-Pen-Book)。

## 变量的使用
1. `UUID`，[在线生成](https://1024tools.com/uuid)。
2. `PROXYIP`，来源于网络分享：`proxy.xxxxxxxx.tk`、`edgetunnel.anycast.eu.org`、`ts.hpc.tw`、`cdn.xn--b6gac.eu.org`、`cdn-all.xn--b6gac.eu.org`、`bestproxy.onecf.eu.org`。
3. `TR_PASS`，默认要修改的密码。
4. `kv`，绑定`KV命名空间`。
5. `/panel`，部署成功后，在url后面增加/panel来进行访问面板，访问面板修改的密码将会保存在`kv`对里。

# 特别感谢
[bia-pain-bache](https://github.com/bia-pain-bache)
