# 🧩 NetworkConfig

![Static Badge](https://img.shields.io/badge/Clash%20Meta-grey)
![Static Badge](https://img.shields.io/badge/Surge-blue)
![Static Badge](https://img.shields.io/badge/Shadowrocket-purple)
![Static Badge](https://img.shields.io/badge/SmartDNS-green)

代理工具规则集，SmartDNS域名分流规则集，每日通过 Github Action 自动从上游拉取并更新。

## 配置文件`Conf`

  * [Clash Meta](./Conf/ClashMeta.yaml) - 需修改文件添加自己的订阅地址
  * [Surge](./Conf/Surge.conf) - 需修改文件添加自己的订阅地址
  * [Shadowrocket](./Conf/Shadowrocket.conf)  - 仅规则，代理与规则分离

## 📄 规则目录
* 通用规则集 `Rules`
  * [OpenAi](./Rules/OpenAi.list)
  * [GoogleFCM](./Rules/GoogleFCM.list)
  * [Google](./Rules/Google.list)
  * [SteamCommunity](./Rules/SteamCommunity.list)
  * [Bing](./Rules/Bing.list)
  * [OneDrive](./Rules/OneDrive.list)
  * [Microsoft](./Rules/Microsoft.list)
  * [MicrosoftCDN](./Rules/MicrosoftCDN.list)
  * [Apple](./Rules/Apple.list)
  * [AppleCDN](./Rules/AppleCDN.list)
  * [Telegram](./Rules/Telegram.list)
  * [Netflix](./Rules/Netflix.list)
  * [ProxyMedia](./Rules/ProxyMedia.list)
  * [SteamCN](./Rules/SteamCN.list)
  * [Epic](./Rules/Epic.list)
  * [Origin](./Rules/Origin.list)
  * [Nintendo](./Rules/Nintendo.list)
  * [Sony](./Rules/Sony.list)
  * [ProxyGFWlist](./Rules/ProxyGFWlist.list)
  * [Global](./Rules/Global.list)
  * [GoogleCN](./Rules/GoogleCN.list)
  * [ChinaIp](./Rules/ChinaIp.list)
  * [ChinaDomain](./Rules/ChinaDomain.list)
  * [ChinaCompanyIp](./Rules/ChinaCompanyIp.list)
  * [Download](./Rules/Download.list)
  * [LocalAreaNetwork](./Rules/LocalAreaNetwork.list)
  * [BT](./Rules/BT.list)
* Rules/Clash Meta
  * [Netflix](./Rules/Clash%20Meta/Netflix.list)
  * [ProxyMedia](./Rules/Clash%20Meta/ProxyMedia.list)
  * [Download](./Rules/Clash%20Meta/Download.list)
  * [OneDrive](./Rules/Clash%20Meta/OneDrive.list)
> `Rules/Clash Meta`为 Clash Meta 专用规则集，其内容与 Rules 中同名规则集一致，区别在于替换 URL-REGEX 和 USER-AGENT 为受 Clash Meta 支持的 DOMAIN-REGEX和 IN-USER
* SmartDNS域名分流 `SmartDNS`
  * [中国大陆加速域名](./SmartDNS/accelerated-domains.china.txt)
  * [GFW](./SmartDNS/gfw.txt)
  * [Apple CDN](./SmartDNS/apple.china.txt)
  * [Microsoft CDN](./SmartDNS/microsoft.china.txt)
  * [Google CDN](./SmartDNS/google.china.txt)

## 📈 规则统计

### Last Update: 2024-08-10

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th>类型</th>
      <th>数量(条)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>DOMAIN</td>
      <td>615</td>
    </tr>
    <tr>
      <td>DOMAIN-KEYWORD</td>
      <td>90</td>
    </tr>
    <tr>
      <td>DOMAIN-SUFFIX</td>
      <td>96946</td>
    </tr>
    <tr>
      <td>IP-CIDR</td>
      <td>7314</td>
    </tr>
    <tr>
      <td>USER-AGENT</td>
      <td>45</td>
    </tr>
    <tr>
      <td>URL-REGEX</td>
      <td>7</td>
    </tr>
    <tr>
      <td>PROCESS-NAME</td>
      <td>62</td>
    </tr>
    <tr>
      <td>TOTAL</td>
      <td>105079</td>
    </tr>
  </tbody>
</table>

## 🌐 Ruleset Server
* <a href="https://ruleset.zcsouls.com/">Ruleset Server</a><br>

## 📊 数据来源

* <a href="https://ruleset.skk.moe/">Sukka Ruleset</a><br>
* <a href="https://github.com/ACL4SSR/ACL4SSR">ACL4SSR</a><br>
* <a href="https://github.com/Loyalsoldier/v2ray-rules-dat">v2ray-rules-dat</a><br>
* <a href="https://github.com/felixonmars/dnsmasq-china-list">dnsmasq-china-list</a><br>