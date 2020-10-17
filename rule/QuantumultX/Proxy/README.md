# 

## 前言

本项目的分流规则由爬虫程序自动维护。

定时爬取互联网上开源的分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。


最后检查时间：2020-10-17 22:43:51。

## 规则统计

总计规则：5984 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN | 1 |
| DOMAIN-KEYWORD | 27 |
| DOMAIN-SUFFIX | 5865 |
| IP-CIDR | 85 |
| IP-CIDR6 | 3 |
| USER-AGENT | 3 |
## 重复统计

分流规则，与本项目其他分流规则重复情况统计。

点击重复数量可以查看重复规则明细。

| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [Adobe](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Adobe)    | 34   | [8](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Adobe.list)   |   23.53%  |
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Advertising)    | 157451   | [87](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Advertising.list)   |   0.06%  |
|  [AdvertisingLite](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/AdvertisingLite)    | 52923   | [28](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/AdvertisingLite.list)   |   0.05%  |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Apple)    | 51   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Apple.list)   |   3.92%  |
|  [AppleBlock](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/AppleBlock)    | 6   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/AppleBlock.list)   |   16.67%  |
|  [Bahamut](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Bahamut)    | 5   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Bahamut.list)   |   20.00%  |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/BlackList)    | 778   | [773](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/BlackList.list)   |   99.36%  |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/China)    | 593   | [21](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/China.list)   |   3.54%  |
|  [Cloudflare](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Cloudflare)    | 15   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Cloudflare.list)   |   6.67%  |
|  [Discord](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Discord)    | 6   | [6](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Discord.list)   |   100.00%  |
|  [Dubox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Dubox)    | 2   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Dubox.list)   |   100.00%  |
|  [Facebook](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Facebook)    | 25   | [16](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Facebook.list)   |   64.00%  |
|  [Steam](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Steam)    | 16   | [6](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Steam.list)   |   37.50%  |
|  [SteamCN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/SteamCN)    | 13   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/SteamCN.list)   |   7.69%  |
|  [Game](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Game)    | 28   | [12](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Game.list)   |   42.86%  |
|  [Google](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Google)    | 64   | [53](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Google.list)   |   82.81%  |
|  [YouTube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/YouTube)    | 14   | [7](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/YouTube.list)   |   50.00%  |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Microsoft)    | 99   | [27](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Microsoft.list)   |   27.27%  |
|  [Niconico](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Niconico)    | 5   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Niconico.list)   |   40.00%  |
|  [Telegram](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Telegram)    | 20   | [13](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Telegram.list)   |   65.00%  |
|  [Netflix](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Netflix)    | 40   | [6](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Netflix.list)   |   15.00%  |
|  [Global](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Global)    | 842   | [514](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Global.list)   |   61.05%  |
|  [GlobalMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/GlobalMedia)    | 296   | [52](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/GlobalMedia.list)   |   17.57%  |
|  [Github](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Github)    | 6   | [6](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Github.list)   |   100.00%  |
|  [Spotify](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Spotify)    | 8   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Spotify.list)   |   25.00%  |
|  [Spark](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Spark)    | 4   | [3](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Spark.list)   |   75.00%  |
|  [Sony](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Sony)    | 5   | [5](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Sony.list)   |   100.00%  |
|  [Sina](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Sina)    | 10   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Sina.list)   |   10.00%  |
|  [Scholar](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Scholar)    | 76   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Scholar.list)   |   1.32%  |
|  [TestFlight](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/TestFlight)    | 3   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/TestFlight.list)   |   33.33%  |
|  [Twitter](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Twitter)    | 11   | [11](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Twitter.list)   |   100.00%  |
|  [Instagram](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Instagram)    | 2   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Instagram.list)   |   100.00%  |
|  [Wikipedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Wikipedia)    | 12   | [12](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Wikipedia.list)   |   100.00%  |
|  [Whatsapp](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Whatsapp)    | 16   | [16](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Whatsapp.list)   |   100.00%  |
|  [TeamViewer](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/TeamViewer)    | 10   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/TeamViewer.list)   |   20.00%  |
|  [Lan](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Lan)    | 24   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Lan.list)   |   4.17%  |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### QuantumultX 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/Proxy/Proxy.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/QuantumultX/Proxy/Proxy.list

## 数据来源

本项目的分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，建议不要与本项目的分流规则混合使用，以免造成规则重复。

- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/BlackList/BlackList.list
- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Proxy.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyGFWlist.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyLite.list


感谢以上分流规则作者的辛勤付出（排名不分先后）。

如果你有更好的分流规则，欢迎提交给我，我会将它加到数据源中继续完善。

## 最后

### 正则过滤

爬虫程序在清洗原始规则数据时，可根据正则定向过滤规则，以达到保留特定规则的目的。经过正则过滤的规则，无法100%涵盖原始规则数据，请知悉。

### 黑名单

爬虫程序内置部分规则黑名单，在对原始数据进行清洗时，自动将可能引起异常的黑名单规则去除。经过黑名单去除的规则，无法100%涵盖原始规则数据，请知悉。

### 完善规则

如果你：

1. 有更优的原始规则数据
2. 有更多的黑名单规则数据
3. 有更好的优化建议
4. 在使用分流规则时出现异常
5. 有其他问题

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的分流规则。

感谢

[@zjcfynn](https://github.com/zjcfynn) [@Tartarus2014](https://github.com/Tartarus2014)

提供规则数据源及改进建议

### 其他问题

爬虫开发的初衷是为满足自己几方面需求：

1. 去除混用多个去广告规则造成的重复
2. 去除多个去广告规则中某些规则
3. 多个分流规则间重复情况检查
4. 定时同步数据源更新

本项目的分流规则还是以自用为主，请不要对外宣传此分流规则。所以，还是请低调使用吧。