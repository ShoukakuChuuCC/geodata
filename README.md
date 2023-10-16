## **下载地址**：

- **geoip-lite.dat**
  - [Github release](https://github.com/ShoukakuChuuCC/geodata/releases/download/latest/geoip-lite.dat)
  - [JSdelivr](https://cdn.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geoip-lite.dat)
  - [JSdelivr-CF](https://testingcf.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geoip-lite.dat)
 
- **geoip-lite.db**
  - [Github release](https://github.com/ShoukakuChuuCC/geodata/releases/download/latest/geoip-lite.db)
  - [JSdelivr](https://cdn.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geoip-lite.db)
  - [JSdelivr-CF](https://testingcf.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geoip-lite.db)

- **geoip-lite.metadb**
  - [Github release](https://github.com/ShoukakuChuuCC/geodata/releases/download/latest/geoip-lite.metadb)
  - [JSdelivr](https://cdn.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geoip-lite.metadb)
  - [JSdelivr-CF](https://testingcf.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geoip-lite.metadb)

- **geoip.dat**
  - [Github release](https://github.com/ShoukakuChuuCC/geodata/releases/download/latest/geoip.dat)
  - [JSdelivr](https://cdn.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geoip.dat)
  - [JSdelivr-CF](https://testingcf.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geoip.dat)

- **geoip.db**
  - [Github release](https://github.com/ShoukakuChuuCC/geodata/releases/download/latest/geoip.db)
  - [JSdelivr](https://cdn.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geoip.db)
  - [JSdelivr-CF](https://testingcf.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geoip.db)

- **geoip.metadb**
  - [Github release](https://github.com/ShoukakuChuuCC/geodata/releases/download/latest/geoip.metadb)
  - [JSdelivr](https://cdn.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geoip.metadb)
  - [JSdelivr-CF](https://testingcf.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geoip.metadb)

- **geosite.dat**
  - [Github release](https://github.com/ShoukakuChuuCC/geodata/releases/download/latest/geosite.dat)
  - [JSdelivr](https://cdn.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geosite.dat)
  - [JSdelivr-CF](https://testingcf.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geosite.dat)

- **geosite.db**
  - [Github release](https://github.com/ShoukakuChuuCC/geodata/releases/download/latest/geosite.db)
  - [JSdelivr](https://cdn.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geosite.db)
  - [JSdelivr-CF](https://testingcf.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/geosite.db)
  
- **cn.txt**
  - [Github release](https://github.com/ShoukakuChuuCC/geodata/releases/download/latest/cn.txt)
  - [JSdelivr](https://cdn.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/cn.txt)
  - [JSdelivr-CF](https://testingcf.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/cn.txt)

- **bt-tracker.txt**
  - [Github release](https://github.com/ShoukakuChuuCC/geodata/releases/download/latest/bt-tracker.txt)
  - [JSdelivr](https://cdn.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/bt-tracker.txt)
  - [JSdelivr-CF](https://testingcf.jsdelivr.net/gh/ShoukakuChuuCC/geodata@release/bt-tracker.txt)

## **geoip-lite.dat,geoip-lite.db,geoip-lite.metadb 内容** 

国家仅包含CN/JP,精简体积,替换一些类别
- 新增类别（方便有特殊需求的用户使用）：
  - `geoip:cloudflare`
  - `geoip:cloudfront`
  - `geoip:facebook`
  - `geoip:bilibili`
  - `geoip:google`
  - `geoip:netflix`
  - `geoip:telegram`
  - `geoip:twitter`
  - `geoip:apple`

## **geoip.dat,geoip.db,geoip.metadb 内容**

同 [Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat)
- 新增类别（方便有特殊需求的用户使用）：
  - `geoip:cloudflare`
  - `geoip:cloudfront`
  - `geoip:facebook`
  - `geoip:fastly`
  - `geoip:google`
  - `geoip:netflix`
  - `geoip:telegram`
  - `geoip:twitter`

## **geosite.dat,geosite.db,geosite.metadb 内容**

用法同 [Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat)  
  - `geosite:category-ads-all` 仅使用域名作为广告拦截用途作用有限，因此不作额外域名添加
  - `geosite:cn` 源替换为 [ios_rule_script/ChinaMax_Domain](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/ChinaMax)
  - `geosite:onedrive` 合并 [ios_rule_script/OneDrive](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/OneDrive)
  - `geosite:steam@cn` 合并 [ios_rule_script/SteamCN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/SteamCN) 的内数据
  - 新增类别
  - `geosite:biliintl` 来源 [biliintl](https://raw.githubusercontent.com/xishang0128/rules/main/biliintl.list)
  - `geosite:tracker` 来源 [TrackersList](https://trackerslist.com/#/zh)以及[blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/PrivateTracker)
  - `geosite:anti-ad` 来源 [anti-AD](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-domains.txt)
  - `geosite:bt-tracker` 来源 [XIU2/TrackersListCollectiont](https://raw.githubusercontent.com/XIU2/TrackersListCollection/master/all.txt)和[ngosang/trackerslist](https://raw.githubusercontent.com/ngosang/trackerslist/master/trackers_all.txt) (已去重)

## *cn_ip.txt 内容*

主要用于mosdns v5分流
内容来自:  
[blackmatrix7/ios_rule_script](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/ChinaMax/ChinaMax_ip.yaml)

## *cn_domain.txt 内容*

主要用于mosdns v5分流
内容来自:  
[blackmatrix7/ios_rule_script](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/ChinaMax/ChinaMax_Classical.yaml)


## *bt-tracker.txt 内容*

主要用于mosdns v5分流
内容来自: 
[XIU2/TrackersListCollectiont](https://raw.githubusercontent.com/XIU2/TrackersListCollection/master/all.txt)  
[ngosang/trackerslist](https://raw.githubusercontent.com/ngosang/trackerslist/master/trackers_all.txt)

## 致谢

- [@privacy-protection-tools/anti-AD](https://github.com/privacy-protection-tools/anti-AD)
- [@XIU2/TrackersListCollectiont](https://github.com/XIU2/TrackersListCollection)
- [@ngosang/trackerslist](https://github.com/ngosang/trackerslist)
- [@MetaCubeX/meta-rules-dat](https://github.com/MetaCubeX/meta-rules-dat)
- [@Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip)
- [@v2fly/domain-list-community](https://github.com/v2fly/domain-list-community)
- [@Loyalsoldier/domain-list-custom](https://github.com/Loyalsoldier/domain-list-custom)
- [@felixonmars/dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list)
- [@gfwlist/gfwlist](https://github.com/gfwlist/gfwlist)
- [@cokebar/gfwlist2dnsmasq](https://github.com/cokebar/gfwlist2dnsmasq)
- [@Loyalsoldier/cn-blocked-domain](https://github.com/Loyalsoldier/cn-blocked-domain)
- [@AdblockPlus/EasylistChina+Easylist.txt](https://easylist-downloads.adblockplus.org/easylistchina+easylist.txt)
- [@AdGuard/DNS-filter](https://kb.adguard.com/en/general/adguard-ad-filters#dns-filter)
- [@PeterLowe/adservers](https://pgl.yoyo.org/adservers)
- [@DanPollock/hosts](https://someonewhocares.org/hosts)
- [@crazy-max/WindowsSpyBlocker](https://github.com/crazy-max/WindowsSpyBlocker)
- [@blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)
