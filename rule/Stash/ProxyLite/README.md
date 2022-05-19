# 🧸 ProxyLite

## 前言

![](https://shields.io/badge/-移除重复规则-ff69b4) ![](https://shields.io/badge/-移除无法解析的域名-important) ![](https://shields.io/badge/-DOMAIN与DOMAIN--SUFFIX合并-green) ![](https://shields.io/badge/-DOMAIN--SUFFIX间合并-critical) ![](https://shields.io/badge/-IP--CIDR(6)合并-blueviolet) 

ProxyLite规则由《RULE GENERATOR 规则生成器》自动生成。

分流规则是互联网公共服务的域名和IP地址汇总，所有数据均收集自互联网公开信息，不代表我们支持或使用这些服务。

请通过我国(中华人民共和国)合法的互联网出入口信道访问规则中的地址，并确保在使用过程中符合相关法律法规。

## 规则说明
对比Proxy，ProxyLite移除无法访问的域名，排除广告、苹果、微软和谷歌的规则，便于搭配使用。

## 规则统计

最后更新时间：2022-05-19 13:06:42

各类型规则统计：
| 类型 | 数量(条)  | 
| ---- | ----  |
| DOMAIN | 163  | 
| DOMAIN-KEYWORD | 22  | 
| DOMAIN-SUFFIX | 33651  | 
| IP-CIDR | 92  | 
| IP-CIDR6 | 3  | 
| USER-AGENT | 7  | 
| TOTAL | 33938  | 


## Stash 

#### 使用说明
- ProxyLite.yaml，请使用 behavior: classical。
- ProxyLite_Classical.yaml，请使用 behavior: classical。
- ProxyLite_Domain.txt，请使用 behavior: domain-text。

#### 配置建议
- ProxyLite_Classical.yaml 单独使用。
- ProxyLite.yaml、ProxyLite_Domain.txt 共同使用。

#### 规则链接
**实时版**

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Stash/ProxyLite/ProxyLite.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Stash/ProxyLite/ProxyLite_Classical.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Stash/ProxyLite/ProxyLite_Domain.txt

**实时版CDN**

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Stash/ProxyLite/ProxyLite.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Stash/ProxyLite/ProxyLite_Classical.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Stash/ProxyLite/ProxyLite_Domain.txt

**稳定版**

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Stash/ProxyLite/ProxyLite.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Stash/ProxyLite/ProxyLite_Classical.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Stash/ProxyLite/ProxyLite_Domain.txt

**稳定版CDN**

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Stash/ProxyLite/ProxyLite.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Stash/ProxyLite/ProxyLite_Classical.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Stash/ProxyLite/ProxyLite_Domain.txt

## 子规则/排除规则


当前分流规则，未包含其他子规则。

当前分流规则，已排除以下规则：
| 排除规则  |  |  |  |  | 
| ---- | ---- | ---- | ---- | ----  |
| Advertising | AppStore | Apple | AppleDaily | AppleMail  | 
| AppleMusic | AppleNews | AppleProxy | AppleTV | China  | 
| ChinaIPs | Chromecast | FindMy | FitnessPlus | GitHub  | 
| Google | GoogleDrive | GoogleSearch | GoogleVoice | Microsoft  | 
| OneDrive | Siri | SystemOTA | Teams | TestFlight  | 
| YouTube | YouTubeMusic | iCloud | iCloudPrivateRelay  |  | 

## 数据来源

《ProxyLite》的数据来自以下链接，如与本项目的《ProxyLite》规则混合使用，可能会造成规则大量重复。

- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/BlackList/BlackList.list
- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Proxy.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyGFWlist.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyLite.list
- https://raw.githubusercontent.com/Hackl0us/SS-Rule-Snippet/master/Rulesets/Surge/Basic/Apple-proxy.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/Proxy/Proxy.list
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/greatfire.txt
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/gfw.txt
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/proxy.txt
- https://raw.githubusercontent.com/GeQ1an/Rules/master/QuantumultX/Filter/Outside.list
- https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/proxy.txt


感谢以上规则作者的辛勤付出（排名不分先后）。

## 最后

### 感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) [@chenyiping1995](https://github.com/chenyiping1995) 

提供规则数据源及改进建议。

### 其他

请不要对外宣传本项目。