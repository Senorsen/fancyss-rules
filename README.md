## fancyss-rules
Forked from [qxzg/Actions](https://github.com/qxzg/Actions).

[![Update Fancyss Rules](https://github.com/Senorsen/fancyss-rules/workflows/Update%20Fancyss%20Rules/badge.svg)](https://github.com/Senorsen/fancyss-rules/actions?query=workflow%3A%22Update+Fancyss+Rules%22)    
每日UTC+8 3:45自动更新[fancyss](https://github.com/hq450/fancyss)规则  
食用方法：
- 手动将`/koolshare/scripts/ss_rule_update.sh`中第10行的  
- `url_main="https://raw.githubusercontent.com/hq450/fancyss/master/rules"`改为  
- `url_main="https://raw.githubusercontent.com/qxzg/Actions/master/fancyss_rules"`  
- 并且每次更新fancyss后需重新修改该脚本
- > x86版本的插件同理，找到更新规则的脚本并替换`url_main`就可以了（注意是否有最后的`/`）
- 如果由于网络问题，更新规则的时候无法访问`raw.githubusercontent.com`，可以使用GitHub CDN源：`https://cdn.jsdelivr.net/gh/Senorsen/fancyss-rules@master/fancyss_rules`

注：由于源更新较慢，大陆白名单已改用[ispip.clang.cn](https://ispip.clang.cn/all_cn.txt)作为规则源，而非[fancyss原版规则](https://github.com/hq450/fancyss/tree/master/rules)中的https://raw.githubusercontent.com/firehol/blocklist-ipsets/master/ipip_country/ipip_country_cn.netset
