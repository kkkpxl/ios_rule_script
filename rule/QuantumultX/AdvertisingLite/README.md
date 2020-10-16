# 去广告精简版

## 前言

本项目的去广告精简版分流规则由爬虫程序自动维护。

定时爬取互联网上开源的去广告精简版分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。

本分流规则不包含任何知乎去广告规则。如果出现错误拦截，尝试使用WhiteList规则进行修正。

最后检查时间：2020-10-17 22:43:46。

## 规则统计

总计规则：52923 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN | 43619 |
| DOMAIN-KEYWORD | 47 |
| DOMAIN-SUFFIX | 8729 |
| IP-CIDR | 200 |
| URL-REGEX | 328 |
## 重复统计

去广告精简版分流规则，与本项目其他分流规则重复情况统计。

点击重复数量可以查看重复规则明细。

| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [Adobe](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Adobe)    | 34   | [5](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/AdvertisingLite/Adobe.list)   |   14.71%  |
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Advertising)    | 157451   | [52923](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/AdvertisingLite/Advertising.list)   |   33.61%  |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Apple)    | 51   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/AdvertisingLite/Apple.list)   |   1.96%  |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/BlackList)    | 778   | [10](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/AdvertisingLite/BlackList.list)   |   1.29%  |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/China)    | 593   | [5](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/AdvertisingLite/China.list)   |   0.84%  |
|  [ChinaMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/ChinaMedia)    | 75   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/AdvertisingLite/ChinaMedia.list)   |   1.33%  |
|  [WhiteList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/WhiteList)    | 34   | [4](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/AdvertisingLite/WhiteList.list)   |   11.76%  |
|  [YouTube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/YouTube)    | 14   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/AdvertisingLite/YouTube.list)   |   7.14%  |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Microsoft)    | 99   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/AdvertisingLite/Microsoft.list)   |   1.01%  |
|  [Global](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Global)    | 842   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/AdvertisingLite/Global.list)   |   0.12%  |
|  [GlobalMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/GlobalMedia)    | 296   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/AdvertisingLite/GlobalMedia.list)   |   0.68%  |
|  [Hijacking](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Hijacking)    | 209   | [201](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/AdvertisingLite/Hijacking.list)   |   96.17%  |
|  [Privacy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Privacy)    | 2714   | [72](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/AdvertisingLite/Privacy.list)   |   2.65%  |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Proxy)    | 5984   | [28](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/AdvertisingLite/Proxy.list)   |   0.47%  |
|  [Tencent](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Tencent)    | 19   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/AdvertisingLite/Tencent.list)   |   5.26%  |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### QuantumultX 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/AdvertisingLite/AdvertisingLite.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/QuantumultX/AdvertisingLite/AdvertisingLite.list

## 数据来源

本项目的去广告精简版分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，建议不要与本项目的去广告精简版分流规则混合使用，以免造成规则重复。

- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanAD.list
- https://raw.githubusercontent.com/NobyDa/ND-AD/master/Surge/AD_Block.txt
- https://raw.githubusercontent.com/NobyDa/Script/master/Surge/AdRule.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Guard/Advertising.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Liby.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Tide.list
- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Reject.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/Advertising/LianXiangJia/LianXiangJia.list


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

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的去广告精简版分流规则。

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