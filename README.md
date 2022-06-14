# Shadowrocket: 2022-03-08 10:01:32
### [General]
```
[General]
include = 去广告.conf
bypass-system = true
skip-proxy = 192.168.0.0/16, 10.0.0.0/8, 172.16.0.0/12, localhost, *.local, captive.apple.com
tun-excluded-routes = 10.0.0.0/8,100.64.0.0/10,127.0.0.0/8,169.254.0.0/16,172.16.0.0/12,192.0.0.0/24,192.0.2.0/24,192.88.99.0/24,192.168.0.0/16,198.18.0.0/15,198.51.100.0/24,203.0.113.0/24,224.0.0.0/4,255.255.255.255/32,0.0.0.0/31
dns-server = 119.29.29.29, 223.5.5.5, system
ipv6 = false
force-http-engine-hosts = api-h2.tiktokv.com:443,api.tiktokv.com:443
```
### [Rule]
```
[Rule]
DOMAIN-SUFFIX,github.com,PROXY
DOMAIN-SUFFIX,emby.nexitally.com,PROXY
DOMAIN-SUFFIX,emby.cjpc.cc,PROXY
DOMAIN-SUFFIX,emby.flowercloud.yt,PROXY
DOMAIN-SUFFIX,emby.maying.club,PROXY
DOMAIN-SUFFIX,emby.mdss.cloud,PROXY
DOMAIN-SUFFIX,emby.ytoo.li,PROXY
DOMAIN-SUFFIX,embyserver.ga,PROXY
DOMAIN-SUFFIX,emby.prprcloud.com,PROXY
DOMAIN-SUFFIX,emby.nyancat.net,PROXY
DOMAIN-SUFFIX,emby.plusmedia.site,PROXY
DOMAIN-SUFFIX,emby-cf.plusmedia.site,PROXY
DOMAIN-SUFFIX,emby.xeton.dev,PROXY
DOMAIN-SUFFIX,jellyfin.xeton.dev,PROXY
DOMAIN-SUFFIX,movie.xeton.dev,PROXY
DOMAIN-SUFFIX,servers.xeton.dev,PROXY
DOMAIN-SUFFIX,emby.otakudrive.life,PROXY
DOMAIN-SUFFIX,emby2.otakudrive.life,PROXY
DOMAIN-SUFFIX,agahk1.jmsooo.com,PROXY
DOMAIN-SUFFIX,agasg1.jmsooo.com,PROXY
DOMAIN-SUFFIX,agajp1.jmsooo.com,PROXY
DOMAIN-SUFFIX,aws.jmsooo.com,PROXY
DOMAIN-SUFFIX,ntt1.jmsooo.com,PROXY
DOMAIN-SUFFIX,hinet.jmsooo.com,PROXY
DOMAIN-SUFFIX,cf1.jmsooo.com,PROXY
DOMAIN-SUFFIX,pornemby.club,PROXY
DOMAIN-SUFFIX,emby.immtel.com,PROXY
DOMAIN-SUFFIX,cf.odysseyplus.site,PROXY
DOMAIN-SUFFIX,agahk.odysseyplus.site,PROXY
DOMAIN-SUFFIX,agasg.odysseyplus.site,PROXY
DOMAIN-SUFFIX,ru.odysseyplus.site,PROXY
DOMAIN-SUFFIX,line.emby.men,PROXY
DOMAIN-SUFFIX,emby.run,PROXY
RULE-SET,https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Guard/Advertising.list,REJECT
RULE-SET,https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/AdRule.list,REJECT
RULE-SET,https://raw.githubusercontent.com/eHpo1/Rules/master/QuantumultX/Filter/Liby.txt,REJECT
DOMAIN-SUFFIX,music.163.com,PROXY
DOMAIN-SUFFIX,interface.music.163.com,PROXY
DOMAIN-SUFFIX,interface3.music.163.com,PROXY
DOMAIN-SUFFIX,apm.music.163.com,PROXY
DOMAIN-SUFFIX,apm3.music.163.com,PROXY
IP-CIDR,59.111.181.38/32,PROXY
IP-CIDR,59.111.181.60/32,PROXY
IP-CIDR,223.252.199.66/32,PROXY
IP-CIDR,223.252.199.67/32,PROXY
IP-CIDR,59.111.160.195/32,PROXY
IP-CIDR,59.111.160.197/32,PROXY
IP-CIDR,47.100.127.239/32,PROXY
IP-CIDR,118.24.63.156/32,PROXY
IP-CIDR,193.112.159.225/32,PROXY
IP-CIDR,39.105.63.80/32,PROXY
IP-CIDR,59.111.181.35/32,PROXY
IP-CIDR,115.236.118.33/32,PROXY
IP-CIDR,115.236.121.1/32,PROXY
IP-CIDR,112.13.122.1/32,PROXY
IP-CIDR,112.13.119.17/32,PROXY
IP-CIDR,103.126.92.132/32,PROXY
IP-CIDR,103.126.92.13/32,PROXY
IP-CIDR,45.254.48.1/32,PROXY
DOMAIN-SUFFIX,raw.githubusercontent.com,PROXY
DOMAIN,apapia-history.manmanbuy.com,DIRECT
URL-REGEX,^https:\/\/.+\.googlevideo\.com\/.+&oad,REJECT
RULE-SET,https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Reject.list,REJECT
RULE-SET,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Loon/Proxy/Proxy.list,PROXY
RULE-SET,https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/China.list,DIRECT
RULE-SET,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/LocalAreaNetwork.list,DIRECT
RULE-SET,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/UnBan.list,DIRECT
RULE-SET,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanAD.list,REJECT
RULE-SET,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanProgramAD.list,REJECT
RULE-SET,https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/all_AdRuleTest.list,REJECT
RULE-SET,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/GoogleCN.list,DIRECT
RULE-SET,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Telegram.list,PROXY
RULE-SET,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/NetEaseMusic.list,DIRECT
RULE-SET,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyMedia.list,PROXY
RULE-SET,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyLite.list,PROXY
RULE-SET,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaDomain.list,DIRECT
RULE-SET,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaCompanyIp.list,DIRECT
URL-REGEX,^https:\/\/.+\.googlevideo\.com\/.+&oad,REJECT
RULE-SET,https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Reject.list,REJECT
RULE-SET,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Loon/Proxy/Proxy.list,PROXY
RULE-SET,https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/China.list,DIRECT
GEOIP,CN,DIRECT
FINAL,PROXY
```
### [Host]
```
[Host]
vip1.kuwo.cn = server:119.28.28.28
trade-acs.m.taobao.com = server:119.28.28.28
api.m.jd.com = server:119.28.28.28
*.tmall.com = server:223.6.6.6
*.jd.com = server:119.28.28.28
*.qq.com = server:119.28.28.28
*.tencent.com = server:119.28.28.28
*.alicdn.com = server:223.5.5.5
*.aliyun.com = server:223.5.5.5
*.weixin.com = server:119.28.28.28
*.bilibili.com = server:119.29.29.29
*.hdslb.com = server:119.29.29.29
*.163.com = server:119.29.29.29
*.126.com = server:119.29.29.29
*.126.net = server:119.29.29.29
*.127.net = server:119.29.29.29
*.netease.com = server:119.29.29.29
*.mi.com = server:119.29.29.29
*.xiaomi.com = server:119.29.29.29
*.pcbeta.com = server:120.52.19.113
*testflight.apple.com = server:8.8.4.4
localhost = 127.0.0.1
```
### [URL Rewrite]
```
[URL Rewrite]
^http:\/\/damiyingshi\.app\.bucuo\.online\/api\/login\/saveerrlog\/ _ REJECT-200
^http://(www.)?g.cn https://www.google.com 302
^http://(www.)?google.cn https://www.google.com 302
(?<=_region=)CN(?=&) JP 307
(?<=&mcc_mnc=)4 2 307
^(https?:\/\/dm[\w-]+\.\w+\.com\/.+)(\?)(.+) $1$3 302
^(https?:\/\/(tnc|dm)[\w-]+\.\w+\.com\/.+)(\?)(.+) $1$3 302
(^https?:\/\/*\.\w{4}okv.com\/.+&.+)(\d{2}\.3\.\d)(.+) $118.0$3 302
^(https?:\/\/tnc[\w-]+\.\w+\.com\/.+)(\?)(.+) $1$3 302
ctier=[A-Z] ctier=A 302
^https:\/\/[\s\S]*\.googlevideo\.com/.*&(oad|ctier) _ REJECT
ctier=[A-Z] citer=A 302
(?<=\?version_code=)1[6-9]..(?=.?.?&) 100. 307
(?<=&app_version=)1[6-9]..(?=.?.?&) 100. 307
^https://api[\w-]*?.tiktokv.com/aweme/v\d/policy/notice/? - reject
^https:\/\/[\s\S]*\.googlevideo\.com/.*&(oad|ctier) - reject
^https?:\/\/api\.21jingji\.com\/ad\/ - reject
^https?:\/\/service\.4gtv\.tv\/4gtv\/Data\/(GetAD|ADLog) - reject
^https?:\/\/app\.58\.com\/api\/home\/(advertising|appadv)\/ - reject
^https?:\/\/app\.58\.com\/api\/home\/invite\/popupAdv - reject
^https?:\/\/app\.58\.com\/api\/log\/ - reject
^https?:\/\/pic\d\.ajkimg\.com\/mat\/\w+\?imageMogr\d\/format\/jpg\/thumbnail\/\d{3}x\d{4}$ - reject
^https?:\/\/\w+\.58cdn\.com\.cn\/brandads\/ - reject
^https?:\/\/(gw|heic)\.alicdn\.com\/\w{2}s\/[\w\/.-]+\.jpg_(9\d{2}|\d{4}) - reject
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.taobao\.idle\.home\.welcome\/ - reject
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.trip\.activity\.querytmsresources\/ - reject
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.film\.mtopadvertiseapi\.queryadvertise\/ - reject
^https?:\/\/render\.alipay\.com\/p\/s\/h5data\/prod\/spring-festival-2019-h5data\/popup-h5data\.json - reject
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.o2o\.ad\.gateway\.get\/ - reject
^https?:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.taobao\.wireless\.home\.splash\.awesome\.get\/ - reject
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.o2o\.ad\.exposure\.get\/ - reject
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alimusic\.common\.mobileservice\.startinit\/ - reject
^https?:\/\/m\d\.amap\.com\/ws\/valueadded\/alimama\/splash_screen\/ - reject
^https?:\/\/[\w-.]+\.ott\.cibntv\.net\/[\w\/-]+.mp4\?sid= - reject
^https?:\/\/api-new\.app\.acfun\.cn\/rest\/app\/flash\/screen\/ - reject
^https?:\/\/api\.bjxkhc\.com\/index\.php\/app\/ios\/ads\/ - reject
^https?:\/\/[\w-]+\.(amemv|musical|snssdk|tiktokv)\.(com|ly)\/(api|motor)\/ad\/ - reject
^https?:\/\/[\w-]+\.snssdk\.com\/.+_ad\/ - reject
^https?:\/\/[\w-]+\.snssdk\.com\/motor\/operation\/activity\/display\/config\/V2\/ - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/img\/ad\.union\.api\/ - reject
^https?:\/\/dsp\.toutiao\.com\/api\/xunfei\/ads\/ - reject
^https?:\/\/pan\.baidu\.com\/rest\/\d\.\d\/pcs\/adx - reject
^https?:\/\/pan\.baidu\.com\/act\/api\/activityentry - reject
^https?:\/\/issuecdn\.baidupcs\.com\/issue\/netdisk\/guanggao - reject
^https?:\/\/c\.tieba\.baidu\.com\/c\/s\/splashSchedule - reject
^https?:\/\/c\.tieba\.baidu\.com\/c\/f\/forum\/getAdInfo - reject
^https?:\/\/c\.tieba\.baidu\.com\/\w+\/\w+\/(sync|newRnSync|mlog) - reject
^https?:\/\/newclient\.map\.baidu\.com\/client\/phpui2\/\?qt=ads - reject
^https?:\/\/mime\.baidu\.com\/v\d\/IosStart\/getStartInfo$ - reject
^https?:\/\/mime\.baidu\.com\/v\d\/activity\/advertisement - reject
^https?:\/\/iface\.iqiyi\.com\/api\/getNewAdInfo - reject
^https?:\/\/act\.vip\.iqiyi\.com\/interact\/api\/show\.do - reject
^https?:\/\/act\.vip\.iqiyi\.com\/interact\/api\/v\d\/show - reject
^https?:\/\/app\.bilibili\.com\/x\/v\d\/splash\/ - reject
^https?:\/\/manga\.bilibili\.com\/twirp\/comic\.v\d\.Comic\/Flash - reject
^https?:\/\/channel\.beitaichufang\.com\/channel\/api\/v\d\/promote\/ios\/start\/page - reject
^https?:\/\/iapi\.bishijie\.com\/actopen\/advertising\/ - reject
^https?:\/\/app\.api\.ke\.com\/config\/config\/bootpage - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/api\/v\d\/app_square\/start_up_with_ad$ - reject
^https?:\/\/www\.bodivis\.com\.cn\/app\/splashAdvertise - reject
^https?:\/\/yxyapi\d\.drcuiyutao\.com\/yxy-api-gateway\/api\/json\/advert\/ - reject
^https?:\/\/clientaccess\.10086\.cn\/biz-orange\/DN\/init\/startInit - reject
^https?:\/\/wap\.js\.10086\.cn\/jsmccClient\/cd\/market_content\/api\/v\d\/market_content\.page\.query - reject
^https?:\/\/m\.client\.10010\.com\/mobileService\/customer\/accountListData\.htm - reject
^https?:\/\/m\.client\.10010\.com\/uniAdmsInterface\/getWelcomeAd - reject
^https?:\/\/cloud\.189\.cn\/include\/splash\/ - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d):\d+/xygj-config-api\/queryData - reject
^https?:\/\/www\.cntv\.cn\/nettv\/adp\/ - reject
^https?:\/\/api\.chelaile\.net\.cn\/adpub\/ - reject
^https?:\/\/api\.chelaile\.net\.cn\/goocity\/advert\/ - reject
^https?:\/\/web\.chelaile\.net\.cn\/api\/adpub\/ - reject
^https?:\/\/cap\.caocaokeji\.cn\/advert-bss\/ - reject
^https?:\/\/api\.caijingmobile\.com\/(ad|advert)\/ - reject
^https?:\/\/m\.caijing\.com\.cn\/startup_ad_ios\.html$ - reject
^https?:\/\/gw\.csdn\.net\/cms-app\/v\d+\/home_page\/open_advertisement - reject
^https?:\/\/m\.ctrip\.com\/restapi\/soa2\/\d+\/json\/getAdsList - reject
^https?:\/\/app\.poizon\.com\/api\/v\d\/app\/advertisement\/ - reject
^https?:\/\/api\.douban\.com\/v\d\/app_ads\/ - reject
^https?:\/\/rtbapi\.douyucdn\.cn\/japi\/sign\/app\/getinfo\?uid=&mdid=iphone&client_sys=ios$ - reject
^https?:\/\/mapi\.dangdang\.com\/index\.php\?action=init - reject
^https?:\/\/e\.dangdang\.com\/media\/api\d\.go\?action=getDeviceStartPage - reject
^https?:\/\/daoyu\.sdo\.com\/api\/userCommon\/getAppStartAd - reject
^https?:\/\/capis(-slb)?\.didapinche\.com\/ad\/ - reject
^https?:\/\/www\.didapinche\.com\/app\/adstat\/ - reject
^https?:\/\/api\.gaoqingdianshi\.com\/api\/v\d\/ad\/ - reject
^https?:\/\/cdn\.dianshihome\.com\/static\/ad\/ - reject
^https?:\/\/app\.ddpai\.com\/d\/api\/v\d\/config\/get\/bootscreen - reject
^https?:\/\/api\.daydaycook\.com\.cn\/daydaycook\/server\/ad\/ - reject
^https?:\/\/cms\.daydaycook\.com\.cn\/api\/cms\/advertisement\/ - reject
^https?:\/\/maicai\.api\.ddxq\.mobi\/advert\/ - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/(adgateway|adv)\/ - reject
^https?:\/\/mobile-api2011.elong.com\/(adgateway|adv)\/ - reject
^https?:\/\/pic\.edaijia\.cn\/adsplash\/ - reject
^https?:\/\/cube\.elemecdn\.com\/[\w\/]+\.jpeg\?x-oss-process=image\/resize,m_fill,w_\d{3},h_\d{4}\/format,webp\/ - reject
^https?:\/\/cube\.elemecdn\.com\/[\w\/]+\.jpeg\?x-oss-process=image\/resize,m_fill,w_6\d{2},h_8\d{2}\/format,webp\/ - reject
^https?:\/\/i\.ys7\.com\/api\/ads - reject
^https?:\/\/foodie-api\.yiruikecorp\.com\/v\d\/(banner|notice)\/overview - reject
^https?:\/\/cdn\.api\.fotoable\.com\/Advertise\/ - reject
^https?:\/\/www\.flyertea\.com\/source\/plugin\/mobile\/mobile\.php\?module=advis - reject
^https?:\/\/dsa-mfp\.fengshows\.cn\/mfp\/mfpMultipleDelivery\.do\?[a-z0-9&=]+adunitid - reject
^https?:\/\/api\.feng\.com\/v\d\/advertisement\/.*Claunch - reject
^https?:\/\/api-release\.wuta-cam\.com\/ad_tree - reject
^https?:\/\/res-release\.wuta-cam\.com\/json\/ads_component_cache\.json - reject
^https?:\/\/(www|s)\.youtube\.com\/api\/stats\/ads - reject
^https?:\/\/(www|s)\.youtube\.com\/(pagead|ptracking) - reject
^https?:\/\/\s.youtube.com/api/stats/qoe?.*adformat= - reject
^https?:\/\/gateway\.shouqiev\.com(:8443)?\/fsda\/app\/bootImage\.json - reject
^https?:\/\/dl\.app\.gtja\.com\/dzswem\/kvController\/[\w\/]+\.jpg$ - reject
^https?:\/\/prom\.mobile\.gome\.com\.cn\/mobile\/promotion\/promscms\/\w+\.jsp - reject
^https?:\/\/smkmp\.96225.com\/smkcenter\/ad/ - reject
^https?:\/\/api\.huomao\.com\/channels\/loginAd - reject
^https?:\/\/api\.hanju\.koudaibaobao\.com\/api\/carp\/kp\? - reject
^https?:\/\/imeclient\.openspeech\.cn\/adservice\/ - reject
^https?:\/\/api\.intsig\.net\/user\/cs\/operating\/app\/get_startpic\/ - reject
^https?:\/\/ih2\.ireader\.com\/zyapi\/bookstore\/ad\/ - reject
^https?:\/\/ih2\.ireader\.com\/zyapi\/self\/screen\/ad - reject
^https?:\/\/ih2\.ireader\.com\/zycl\/api\/ad\/ - reject
^https?:\/\/nnapp\.cloudbae\.cn:\d+\/mc\/api\/advert/ - reject
^https?:\/\/api\.applovefrom\.com\/api\/v\d\/splash\/ - reject
^https?:\/\/ib-soft\.net\/icleaner\/txt\/ad_priority\.txt$ - reject
^https?:\/\/www\.inoreader\.com\/adv\/ - reject
^https?:\/\/api\.m\.jd.com\/client\.action\?functionId=start - reject
^https?:\/\/api\.m\.jd.com\/client\.action\?functionId=queryMaterialAdverts - reject
^https?:\/\/(bdsp-x|dsp-x)\.jd\.com\/adx\/ - reject
^https?:\/\/ms\.jr\.jd\.com\/gw\/generic\/aladdin\/na\/m\/getLoadingPicture - reject
^https?:\/\/img\d+\.360buyimg\.com\/jddjadvertise\/ - reject
^https?:\/\/api\.jxedt\.com\/ad\/ - reject
^https?:\/\/richmanapi\.jxedt\.com\/api\/(ad|adplus)\/ - reject
^https?:\/\/\w+\.kakamobi\.cn\/api\/open\/v\d\/advert-sdk\/ - reject
^https?:\/\/app-api\.jinse\.com\/v\d\/ad\/ - reject
^https?:\/\/ios\.wps\.cn\/ad-statistics-service - reject
^https?:\/\/\w+\.kingsoft-office-service\.com\/ad - reject
^https?:\/\/dict-mobile\.iciba\.com\/interface\/index\.php\?[\w=&]*(c=ad|collectFeedsAdShowCount|KSFeedsAdCardViewController) - reject
^https?:\/\/service\.iciba\.com\/popo\/open\/screens\/v\d\?adjson - reject
^https?:\/\/mobile-pic\.cache\.iciba\.com\/feeds_ad\/ - reject
^https?:\/\/api\.gotokeep\.com\/ads - reject
^https?:\/\/api\.kkmh\.com\/v\d+\/(ad|advertisement)\/ - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/MobileAdServer\/ - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/EcomResourceServer/AdPlayPage/adinfo - reject
^https?:\/\/api\.laifeng\.com\/v\d\/start\/ads - reject
^https?:\/\/api\.club\.lenovo\.cn\/common\/open_ad - reject
^https?:\/\/api\.m\.mi\.com\/v\d\/app\/start - reject
^https?:\/\/api\.jr\.mi\.com\/v\d\/adv\/ - reject
^https?:\/\/api\.jr\.mi\.com\/jr\/api\/playScreen - reject
^https?:\/\/(api-mifit|api-mifit-\w+)\.huami\.com\/discovery\/mi\/discovery\/\w+_ad\? - reject
^https?:\/\/api\.mgzf\.com\/renter-operation\/home\/startHomePage - reject
^https?:\/\/cdn\.moji\.com\/(adoss|adlink)\/ - reject
^https?:\/\/mangaapi\.manhuaren\.com\/v\d\/public\/getStartPageAds - reject
^https?:\/\/img\.meituan\.net\/(adunion|display|midas)\/\w+\.(gif|jpg|jpg\.webp)$ - reject
^https?:\/\/(s3plus|flowplus)\.meituan\.net\/v\d\/\w+\/linglong\/\w+\.(gif|jpg|mp4) - reject
^https?:\/\/p\d\.meituan\.net\/(bizad|wmbanner)\/\w+\.jpg - reject
^https?:\/\/p\d\.meituan\.net\/movie\/\w+\.jpg\?may_covertWebp - reject
^https?:\/\/capi.mwee.cn/app-api/V\d+/app/(ad|getstartad) - reject
^https?:\/\/b-api\.ins\.miaopai\.com\/\d\/ad/ - reject
^https?:\/\/mapi\.mafengwo\.cn\/ad\/ - reject
^https?:\/\/mapi\.mafengwo\.cn\/travelguide\/ad\/ - reject
^https?:\/\/app\.mixcapp\.com\/mixc\/api\/v\d\/ad - reject
^https?:\/\/appconf\.mail\.163\.com\/mmad\/ - reject
^https?:\/\/c\.m\.163\.com\/nc\/gl\/ - reject
^https?:\/\/client\.mail\.163\.com\/apptrack\/confinfo\/searchMultiAds - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/eapi\/ad\/ - reject
^https?:\/\/interface(\d)?.music.163.com\/eapi\/ad\/ - reject
^https?:\/\/sp\.kaola\.com\/api\/openad - reject
^https?:\/\/support\.you\.163\.com\/xhr\/boot\/getBootMedia\.json - reject
^https?:\/\/p\.du\.163\.com\/ad\/ - reject
^https?:\/\/dili\.bdatu\.com\/jiekou\/ad\/ - reject
^https?:\/\/wap\.ngchina\.cn\/news\/adverts\/ - reject
^https?:\/\/app-api\.niu\.com\/v\d\/advertisement\/ - reject
^https?:\/\/slapi\.oray\.net\/client\/ad - reject
^https?:\/\/pss\.txffp\.com\/piaogen\/images\/launchScreen/ - reject
^https?:\/\/api\.(pinduoduo|yangkeduo)\.com\/api\/cappuccino\/splash - reject
^https?:\/\/cmsapi\.wifi8\.com\/v\d\/(emptyAd|adNew)\/ - reject
^https?:\/\/agent-count\.pconline\.com\.cn\/counter\/adAnalyse\/ - reject
^https?:\/\/mrobot\.pconline\.com\.cn\/v\d\/ad2p - reject
^https?:\/\/mrobot\.pconline\.com\.cn\/s\/onlineinfo\/ad\/ - reject
^https?:\/\/mrobot\.pcauto\.com\.cn\/v\d\/ad2p - reject
^https?:\/\/mrobot\.pcauto\.com\.cn\/xsp\/s\/auto\/info\/preload\.xsp - reject
^https?:\/\/app\d\.qdaily\.com\/app\d\/boot_advertisements\.json - reject
^https?:\/\/notch\.qdaily\.com\/api\/v\d\/boot_ad - reject
^https?:\/\/open\.qyer\.com\/qyer\/startpage\/ - reject
^https?:\/\/open\.qyer\.com\/qyer\/config\/get - reject
^https?:\/\/media\.qyer\.com\/ad\/ - reject
^https?:\/\/api\.qbb6\.com\/ad\/ - reject
^https?:\/\/mage\.if\.qidian\.com\/argus\/api\/v\d\/client\/getsplashscreen - reject
^https?:\/\/msspjh\.emarbox\.com\/getAdConfig - reject
^https?:\/\/api\.videozhishi\.com\/api\/getAdvertising - reject
^https?:\/\/api\.rr\.tv\/ad\/ - reject
^https?:\/\/weibointl\.api\.weibo\.cn\/portal\.php\?a=get_coopen_ads - reject
^https?:\/\/tqt\.weibo\.cn\/overall\/redirect\.php\?r=(tqt_sdkad|tqtad) - reject
^https?:\/\/tqt\.weibo\.cn\/[\w=?&%.-]+advert\.index - reject
^https?:\/\/tqt\.weibo\.cn\/api\/advert\/ - reject
^https?:\/\/api\.k\.sohu\.com\/api\/news\/adsense - reject
^https?:\/\/pic\.k\.sohu\.com\/img\d\/wb\/tj\/ - reject
^https?:\/\/s1\.api\.tv\.itc\.cn\/v\d\/mobile\/control\/switch\.json - reject
^https?:\/\/(api|api-bk\d+)\.tv\.sohu\.com\/agg\/api\/app\/config\/bootstrap - reject
^https?:\/\/api\.smzdm\.com\/v\d\/util\/loading - reject
^https?:\/\/app-api\.smzdm\.com\/util\/loading - reject
^https?:\/\/s\d\.zdmimg\.com\/www\/api\/v\d\/api\/thirdAd\.php - reject
^https?:\/\/api\.qiuduoduo\.cn\/guideimage - reject
^https?:\/\/www\.shihuo\.cn\/app\d\/saveAppInfo - reject
^https?:\/\/gw-passenger\.01zhuanche\.com\/gw-passenger\/zhuanche-passengerController\/notk\/passenger\/recommendADs - reject
^https?:\/\/image\.suning\.cn\/uimg\/ma\/ad\/ - reject
^https?:\/\/mpcs\.suning\.com\/mpcs\/dm\/getDmInfo - reject
^https?:\/\/ccsp-egmas\.sf-express\.com\/cx-app-base\/base\/app\/ad\/ - reject
^https?:\/\/consumer\.fcbox\.com\/v\d\/ad\/ - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)(:\d+)?\/V\d\/splash\/getSplashV\d\.action$ - reject
^https?:\/\/g\.cdn\.pengpengla\.com\/starfantuan\/boot-screen-info\/ - reject
^https?:\/\/snailsleep\.net\/snail\/v\d\/screen\/qn\/get\? - reject
^https?:\/\/snailsleep\.net\/snail\/v\d\/adTask\/ - reject
^https?:\/\/api\.futunn\.com\/v\d\/ad\/ - reject
^https?:\/\/api\d\.futunn\.com\/ad\/ - reject
^https?:\/\/ssl\.kohsocialapp\.qq\.com:\d+\/game\/buttons - reject
^https?:\/\/qt\.qq\.com\/lua\/mengyou\/get_splash_screen_info - reject
^https?:\/\/4gimg\.map\.qq\.com\/mwaSplash\/ - reject
^https?:\/\/vv\.video\.qq\.com\/getvmind\? - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/[a-z.]+\.tc\.qq\.com\/[\w\W]+p20\d\.1\.mp4\? - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/[a-z.]+\.tc\.qq\.com\/[\w\W]+=v3004 - reject
^https?:\/\/video\.dispatch\.tc\.qq\.com\/\w+\.p20\d\.1\.mp4 - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/[a-z.]+\.tc\.qq\.com\/[\w\W]+_p20\d_ - reject
^https?:\/\/r\.inews\.qq\.com\/(adsBlacklist|getFullScreenPic|getQQNewsRemoteConfig) - reject
^https?:\/\/news\.ssp\.qq\.com\/app - reject
^https?:\/\/y\.gtimg\.cn\/music\/common\/upload\/t_splash_info\/ - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/music\/common\/upload\/t_splash_info\/ - reject
^https?:\/\/m\.tuniu\.com\/api\/operation\/splash\/ - reject
^https?:\/\/mob\.mddcloud\.com\.cn\/api\/(ad|advert)\/ - reject
^https?:\/\/img\d+\.10101111cdn\.com\/adpos\/ - reject
^https?:\/\/api\.vuevideo\.net\/api\/v\d\/ad\/ - reject
^https?:\/\/app\.variflight\.com\/ad\/ - reject
^https?:\/\/app\.variflight\.com\/v\d\/advert\/ - reject
^https?:\/\/api\.cdmcaac\.com\/ad\/ - reject
^https?:\/\/api\.vistopia\.com\.cn\/api\/v\d\/home\/advertisement - reject
^https?:\/\/app\.wy\.guahao\.com\/json\/white\/dayquestion\/getpopad - reject
^https?:\/\/overseas\.weico\.cc/portal\.php\?a=get_coopen_ads - reject
^https?:\/\/thor\.weidian\.com\/ares\/home\.splash\/ - reject
^https?:\/\/api\.wallstcn\.com\/apiv\d\/advertising\/ - reject
^https?:\/\/api\.xiachufang\.com\/v\d\/ad/ - reject
^https?:\/\/api\.psy-1\.com\/cosleep\/startup - reject
^https?:\/\/portal-xunyou\.qingcdn\.com\/api\/v\d\/ios\/configs\/(splash_ad|ad_urls) - reject
^https?:\/\/portal-xunyou\.qingcdn\.com\/api\/v\d\/ios\/ads\/ - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/api\/v\d\/adRealTime - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/(outadservice|ting\/preload)\/ - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/promotion\/(display_cache|display_ad|feed_display|search_ad) - reject
^https?:\/\/(api|promo)\.xueqiu\.com\/promotion\/(display_cache|display_ad|feed_display|search_ad) - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/brand\/search\/v1\.json - reject
^https?:\/\/www\.xiaohongshu\.com\/api\/sns\/v\d\/system_service\/splash_config - reject
^https?:\/\/api\.catch\.gift\/api\/v\d\/pagead\/ - reject
^https?:\/\/app\.yinxiang\.com\/ads\/ - reject
^https?:\/\/restapi\.iyunmai\.com\/api\/ios\/ad\/ - reject
^https?:\/\/tj\.playcvn\.com\/app\/ads\? - reject
^https?:\/\/\w+\.jstucdn\.com\/(g3\/|js\/ad) - reject
^https?:\/\/api\.zhihu\.com\/commercial_api\/ - reject
^https?:\/\/api\.zhihu\.com\/fringe\/ad - reject
^https?:\/\/api\.zhihu\.com\/ad - reject
^https?:\/\/api\.zhihu\.com\/appview\/api\/v\d\/answers\/\d+\/recommendations - reject
^https?:\/\/api\.zhihu\.com\/\w+\/\d+\/comments\/featured-comment-ad - reject
^https?:\/\/a\.qiumibao\.com\/activities\/config\.php - reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d):\d+\/allOne\.php\?ad_name - reject
^https?:\/\/(api|b)\.zhuishushenqi\.com\/advert - reject
^https?:\/\/api\.zhuishushenqi\.com\/splashes\/ios - reject
^https?:\/\/api\.zhuishushenqi\.com\/notification\/shelfMessage - reject
^https?:\/\/api\.zhuishushenqi\.com\/user\/bookshelf-updated - reject
^https?:\/\/itunes\.apple\.com\/lookup\?id=575826903 - reject
^https?:\/\/www\.zybang\.com\/adx\/ - reject
^https?:\/\/api\.izuiyou\.com\/ad\/ - reject
^https?:\/\/tiku\.zhan\.com\/Common\/newAd\/ - reject
^https?:\/\/webboot\.zhangyue\.com\/zycl\/api\/ad\/ - reject
^https?:\/\/saad\.ms\.zhangyue\.net\/ad - reject
```
### [Script]
```
[Script]
Sub-Store = type=http-request,script-path=https://raw.githubusercontent.com/Peng-YM/Sub-Store/master/backend/sub-store.min.js,pattern=^https?:\/\/sub\.store,max-size=131072,requires-body=true,timeout=120,enable=true
TF下载修正 = type=http-request,script-path=Script/TF_Download.js,pattern=^https?:\/\/testflight\.apple\.com\/v\d\/accounts\/.+?\/install$,max-size=131072,requires-body=true,timeout=10,enable=true
TK去水印 = type=http-request,script-path=https://raw.githubusercontent.com/Tartarus2014/Script/master/Tiktok.js,pattern=https?:\/\/.*\.tiktokv\.com\/aweme\/v\d\/(feed|mix\/aweme|aweme\/post|(multi\/)?aweme\/detail|follow\/feed|nearby\/feed|search\/item|general\/search\/single|hot\/search\/video\/list|aweme\/favorite),max-size=131072,requires-body=true,timeout=60,enable=true
spotify部分解锁premium = type=http-response,script-path=https://raw.githubusercontent.com/app2smile/rules/master/js/spotify-proto.js,pattern=^https\:\/\/spclient\.wg\.spotify\.com\/(bootstrap\/v1\/bootstrap|user-customization-service\/v1\/customize)$,max-size=131072,timeout=10,enable=true
京东多合一签到 = type=cron,cronexpr="5 0,12,23 * * *",timeout=20,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/JD-DailyBonus/JD_DailyBonus.js, enable=true
京喜签到 = type=cron,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jx_sign.js, cronexpr="5 0 * * *", timeout=200, enable=true
京东快递签到 = type=cron,cronexpr="10 0 * * *", timeout=200,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_kd.js
签到领现金 = type=cron,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_cash.js, cronexpr="2 0 * * *", timeout=200, enable=true
十元街 = type=cron,cronexpr=9 8 * * *,timeout=200,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_syj.js
点点券 = type=cron,cronexpr=11 8 * * *,timeout=200,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_necklace.js
领京豆额外奖励 = type=cron,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_bean_home.js, cronexpr="10 7 * * *", timeout=200, enable=true
京东农场 = type=cron,script-path=Script/jd_fruit.js,cronexpr="5 1,5,10,15,20 * * *",timeout=2000,enable=true
京东萌宠 = type=cron,script-path=Script/jd_pet.js,cronexpr="5 6-18/6 * * *",timeout=200,enable=true
京东宠汪汪 = type=cron,cronexpr="15 */2 * * *",timeout=200,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_joy.js, enable=true
宠汪汪喂食 = type=cron,cronexpr="0 0 */2 * * *",timeout=200,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_joy_feedPets.js, enable=true
京东种豆得豆 = type=cron,script-path=Script/jd_plantBean.js,cronexpr="22 7,9,11,13,15,17,19,21 * * *",timeout=2000,enable=true
京东摇钱树 = type=cron,cronexpr="3 */2 * * *",timeout=200,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_moneyTree.js, enable=true
进店领豆 = type=cron,cronexpr="10 0 * * *",timeout=200,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_shop.js, enable=true
京小超 = type=cron,cronexpr="11 1,5,10,15,20 * * *",timeout=2000,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_superMarket.js, enable=true
蓝币换京豆 = type=cron,cronexpr="0,1,2 0 * * *",timeout=2000,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_blueCoin.js, enable=true
京东全民开红包 = type=cron,cronexpr="0,1,2 0 * * *",timeout=200,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_redPacket.js, enable=true
京东摇京豆 = type=cron,cronexpr="5 0,12,23 * * *",timeout=200,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_club_lottery.js, enable=true
京东特权值 = type=cron,cronexpr=5 8 * * *,timeout=200,script-path=https://raw.githubusercontent.com/iisams/Scripts/master/liwo/jdtqz.js
口袋书店 = type=cron,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_bookshop.js, cronexpr="1 8,12,18 * * *", timeout=200, enable=true
京东直播 = type=cron,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_live.js, cronexpr="10-20/5 12 * * *", timeout=200, enable=true
京东赚赚 = type=cron,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_jdzz.js, cronexpr="0 3 * * *", timeout=200, enable=true
京东汽车 = type=cron,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_car.js, cronexpr="10 4 * * *", timeout=200, enable=true
京东汽车兑换 = type=cron,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_car_exchange.js, cronexpr="0 0 * * *", timeout=2000, enable=true
东东小窝 = type=cron,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_small_home.js, cronexpr="16 0 * * *", timeout=200, enable=true
京喜工厂 = type=cron,cronexpr=*/5 2,10,15,20,23 * * *,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_dreamFactory.js, timeout=200, enable=true
京喜农场 = type=cron,cronexpr="0 9,12,18 * * *",script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_jxnc.js,  timeout=200, enable=true
京东抽奖机 = type=cron,cronexpr=11 0,23 * * *,timeout=200,script-path=https://raw.githubusercontent.com/yangtingxiao/QuantumultX/master/scripts/jd/jd_lotteryMachine.js
京东排行榜 = type=cron,cronexpr=11 9,23 * * *,timeout=200,script-path=https://raw.githubusercontent.com/yangtingxiao/QuantumultX/master/scripts/jd/jd_rankingList.js
注销京东会员卡 = type=cron,script-path=https://raw.githubusercontent.com/kitnoob/lxk_script/main/jd_unbind.js, cronexpr="10 23 * * *", timeout=200, enable=true
取关京东店铺商品 = type=cron,script-path=https://raw.githubusercontent.com/he1pu/JDHelp/main/jd_unsubscribe.js,cronexpr="55 */3 * * *",timeout=200,enable=true
燃旅视频 = type=cron,script-path=https://raw.githubusercontent.com/ZhiYi-N/Private-Script/master/Scripts/ranlv.js,cronexpr="0/10 10-13 * * *",timeout=3600,enable=true
W P S = type=cron,cronexp=12 0,14 * * *,wake-system=1,timeout=3600,script-path=https://raw.githubusercontent.com/chavyleung/scripts/master/wps/wps.js
百度签到 = type=cron,cronexp=41 0 * * *,wake-system=1,timeout=3600,script-path=https://raw.githubusercontent.com/chavyleung/scripts/master/tieba/tieba.js
有道云笔记 = type=cron,cronexp=3 1 * * *,wake-system=1,timeout=3600,script-path=https://raw.githubusercontent.com/chavyleung/scripts/master/noteyoudao/noteyoudao.js
加油广东 = type=cron,script-path=https://raw.githubusercontent.com/chavyleung/scripts/master/gdoil/gdoil.js,cronexpr="1,10 7 * * *",timeout=300,enable=true
52破解 = type=cron,cronexp=25 0 * * *,wake-system=1,timeout=3600,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/52pojie-DailyBonus/52pojie.js
电视家 = type=cron,script-path=https://cdn.jsdelivr.net/gh/ziye888/JavaScript@main/Task/dsj.js,cronexpr="0-40/4 9 * * *",timeout=3600,enable=false
电视家 = type=cron,script-path=https://cdn.jsdelivr.net/gh/ziye888/JavaScript@main/Task/dsj.js,cronexpr="0 12,20 * * *",timeout=3600,enable=false
嘀嗒出行 = type=cron,cronexp=10 0 * * *,wake-system=1,timeout=3600,script-path=https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/didachuxing/didachuxing_plus.js
疫情动态 = type=cron,cronexp=0 9 * * *,wake-system=1,timeout=3600,script-path=https://raw.githubusercontent.com/Mazetsz/QX/master/nCov_new.js
腾讯视频会员签到 = type=cron,cronexp=33 0 * * *,wake-system=1,timeout=3600,script-path=https://raw.githubusercontent.com/chavyleung/scripts/master/videoqq/videoqq.js
Epic周免 = type=cron,cronexp=0 9 */7 * *,wake-system=1,timeout=3600,script-path=https://raw.githubusercontent.com/Peng-YM/QuanX/master/Tasks/epic.js
爱奇艺 = type=cron,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/iQIYI-DailyBonus/iQIYI.js,cronexpr="1 1 * * *",timeout=300,enable=true
切换会话 = type=cron,cronexp=0 12 * * *,wake-system=1,timeout=3600,script-path=https://raw.githubusercontent.com/chavyleung/scripts/master/box/switcher/box.switcher.js,enable=false
BoxJs = type=http-request,script-path=https://gitee.com/chavyleung/scripts/raw/master/box/chavy.boxjs.js,pattern=^https?://boxjs.net,max-size=131072,requires-body=true,timeout=120,enable=true
淘宝比价 = type=http-request,script-path=https://raw.githubusercontent.com/yichahucha/surge/master/tb_price.js,pattern=^http://.+/amdc/mobileDispatch,max-size=131072,requires-body=true,timeout=10,script-update-interval=7200,enable=true
淘宝比价 = type=http-response,script-path=https://raw.githubusercontent.com/yichahucha/surge/master/tb_price.js,pattern=^https?://trade-acs\.m\.taobao\.com/gw/mtop\.taobao\.detail\.getdetail,max-size=131072,requires-body=true,timeout=10,script-update-interval=7200,enable=true
京东比价 = type=http-response,requires-body=1,max-size=0,pattern=^https?://api\.m\.jd\.com/client\.action\?functionId=(wareBusiness|serverConfig|basicConfig),script-path=https://service.2ti.st/QuanX/Script/jd_tb_price/main.js
流利说·阅读VIP = type=http-response,script-path=https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/JavaScript/LiuLiShuo-YueDu.js,pattern=^https?:\/\/vira\.llsapp\.com\/api\/v\d\/\w+\/\w+$,max-size=131072,requires-body=true,timeout=10,enable=true
樊登读书 = type=http-response,script-path=https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Crack/fdds.js,pattern=https://api.dushu.io/Album/Info,max-size=131072,requires-body=true,timeout=10,enable=true
傲软抠图解锁会员 = type=http-response,script-path=https://raw.githubusercontent.com/yqc007/QuantumultX/master/BackgroundEraserProCrack.js,pattern=^https?:\/\/gw\.aoscdn\.com\/base\/vip\/client\/authorizations$,max-size=131072,requires-body=true,timeout=10,enable=true
Polaris Office解锁订阅 (支持新版9.6.3) = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/PolarisOfficeProCrack.js,pattern=^https?:\/\/api\.polarisoffice\.com\/api\/1\/account\/userinfo$,max-size=131072,requires-body=true,timeout=10,enable=true
Picsew解锁专业版(支持新版3.8.1) = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/PicsewProCrack.js,pattern=^https?:\/\/buy\.itunes\.apple\.com\/verifyReceipt$,max-size=131072,requires-body=true,timeout=10,enable=true
PlaneVPN解锁订阅 = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/PlaneVPNProCrack.js,pattern=^https?:\/\/buy\.itunes\.apple\.com\/verifyReceipt$,max-size=131072,requires-body=true,timeout=10,enable=true
新语听书解锁会员(支持新版4.2.9) = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/XinYuLibraryProCrack.js,pattern=^https?:\/\/i\.xinyulib\.com\.cn\/api\/querytoken.+,max-size=131072,requires-body=true,timeout=10,enable=true
1Blocker解锁(支持新版5.1.1) = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/1Blocker.js,pattern=^https:\/\/api\.revenuecat\.com\/v1\/receipts,max-size=131072,requires-body=true,timeout=10,enable=true
XMind解锁Pro = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/XMind.js,pattern=https:\/\/www\.xmind\.cn\/\_res\/devices,max-size=131072,requires-body=true,timeout=10,enable=true
趣制作2.1.1解锁Pro = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/qzz.js,pattern=^https://cm.szsszykj.com/interface/GetVip.php,max-size=131072,requires-body=true,timeout=10,enable=true
美颜相机 = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/Meiyanxiangji.js,pattern=^https:\/\/api\.meiyan\.com\/vip\/user_info,max-size=131072,requires-body=true,timeout=10,enable=true
美图秀秀 = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/mtxx.js,pattern=^https:\/\/api\.xiuxiu\.meitu\.com\/v1\/user\/show\.json,max-size=131072,requires-body=true,timeout=10,enable=true
嘀嗒清单 = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/DiDaQingDan.js,pattern=^https:\/\/(ticktick|dida365)\.com\/api\/v2\/user\/status,max-size=131072,requires-body=true,timeout=10,enable=true
解锁马卡龙 = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/MaKaLongWanTu.js,pattern=^https?:\/\/app\.api\.versa-ai\.com\/pay\/order\/iap\/check,max-size=131072,requires-body=true,timeout=10,enable=true
InShot解锁订阅 = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/InShot.js,pattern=^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt,max-size=131072,requires-body=true,timeout=10,enable=true
糖心VLog网页版解锁会员 = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/TXVWCrack.js,pattern=^https?:\/\/txv04\.com\/h5\/user\/findQrcode$,max-size=131072,requires-body=true,timeout=10,enable=true
酷我2496解锁会员 = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/KWLongPlayProCrack.js,pattern=^https?:\/\/api_2496\.kuwo\.cn\/front\/user\/vipstatus$,requires-body=true,timeout=10,enable=true
LaunchCenter解锁订阅 = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/LaunchCenterProCrack.js,pattern=^https?:\/\/buy\.itunes\.apple\.com\/verifyReceipt$,requires-body=true,timeout=10,enable=true
解锁酷我音乐会员?听书 = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/kwyy.js,pattern=^http://(.+).kuwo.cn(/v2/api/user/info|/a.p|/vip/v2/user/vip),max-size=131072,requires-body=true,timeout=10,enable=true
解锁酷我音乐会员下载 = type=http-request,pattern=^https?:\/\/musicpay\.kuwo\.cn\/music\.pay\?newver.+$,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/kwyyxz.js,requires-body=true,timeout=10,enable=true
微信去广告 = type=http-response,requires-body=1,max-size=-1,pattern=^https?:\/\/mp\.weixin\.qq\.com\/mp\/getappmsgad\?,script-path=https://raw.githubusercontent.com/yjqiang/surge_scripts/main/scripts/wechat/wechat_public_accounts.js
微信公众号去广告 = type=http-response,script-path=https://raw.githubusercontent.com/scomper/Surge/master/Scripts/WeChat.js,pattern=^https://mp\.weixin\.qq\.com/mp/getappmsgad,max-size=131072,requires-body=true,timeout=10,enable=true
解除微信链接限制 = type=http-response,pattern=^https\:\/\/(weixin110\.qq|security.wechat)\.com\/cgi-bin\/mmspamsupport-bin\/newredirectconfirmcgi\?,requires-body=1,max-size=0,script-path=https://raw.githubusercontent.com/zZPiglet/Task/master/asset/UnblockURLinWeChat.js
辣椒视频解锁会员(少年歌行pro製作，轉載請保留出處信息) = type=http-response,script-path=Script/sngxljsp.js,pattern=^http:\/\/jk\.5apk\.cn\/api(\/reg|\/play),max-size=131072,requires-body=true,timeout=10,enable=true
小小影视 unlock Vip&免广告感谢@GB-png，提供新方法 = type=http-response,script-path=https://raw.githubusercontent.com/photonmang/quantumultX/master/xxys.js,pattern=https:\/\/.*\.(xiaoxiaoapps|xiaoxiaoimg)\.com\/(ssp-svr\/ssp\/list3|ucp/index|getGlobalData),max-size=131072,requires-body=true,timeout=10,enable=true
Bibilivip会员 = type=http-response,script-path=Script/Bibilivip.js,pattern=https:\/\/app\.bilibili\.com\/(x\/vip\/web\/user\/combine|vip\/home|x\/v2\/account\/mine|x\/v2\/account\/myinfo),max-size=131072,requires-body=true,timeout=10,enable=true
Python Ai解锁会员 = type=http-response,script-path=Script/pyai.js,pattern=^http:\/\/ws\.60he\.com\/(book|user).+,max-size=131072,requires-body=true,timeout=10,enable=true
WPS (By eHpo) = type=http-response,script-path=Script/Wps.js,pattern=^https://account.wps.*/api/users/,max-size=131072,requires-body=true,timeout=10,enable=true
去微博应用内广告 (By yichahucha) = type=http-response,script-path=https://raw.githubusercontent.com/yichahucha/surge/master/wb_launch.js,pattern=^https?://(sdk|wb)app.uve.weibo.com(/interface/sdk/sdkad.php|/wbapplua/wbpullad.lua),max-size=131072,requires-body=true,timeout=10,enable=true
去微博应用内广告 (By yichahucha) = type=http-response,script-path=https://raw.githubusercontent.com/yichahucha/surge/master/wb_ad.js,pattern=^https?://m?api\.weibo\.c(n|om)/2/(statuses/(unread|extend|positives/get|(friends|video)(/|_)(mix)?timeline)|stories/(video_stream|home_list)|(groups|fangle)/timeline|profile/statuses|comments/build_comments|photo/recommend_list|service/picfeed|searchall|cardlist|page|!/photos/pic_recommend_status|video/tiny_stream_video_list|photo/info),max-size=131072,requires-body=true,timeout=10,enable=true
去微信公众号广告 (By Choler) = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/File/Wechat.js,pattern=^https?:\/\/mp\.weixin\.qq\.com\/mp\/getappmsgad,max-size=131072,requires-body=true,timeout=10,enable=true
哔哩哔哩番剧开启1080P+ = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/File/bilifj.js,pattern=^https:\/\/ap(p|i)\.bilibili\.com\/((pgc\/player\/api\/playurl)|(x\/v2\/account\/myinfo\?)|(x\/v2\/account/mine\?)),max-size=131072,requires-body=true,timeout=10,enable=true
抖音去广告去水印 (By Choler) = type=http-request,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/Aweme.js,pattern=^https?:\/\/.+?\.amemv\.com\/aweme\/v\d\/(feed|aweme\/post|follow\/feed|nearby\/feed|search\/item|general\/search\/single|hot\/search\/video\/list)\/,max-size=131072,timeout=10,enable=true
抖音去广告去水印 (By Choler) = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/Aweme.js,pattern=^https?:\/\/.+?\.amemv\.com\/aweme\/v\d\/(feed|aweme\/post|follow\/feed|nearby\/feed|search\/item|general\/search\/single|hot\/search\/video\/list)\/,max-size=131072,requires-body=true,timeout=10,enable=true
去广告 = type=http-response,script-path=https://raw.githubusercontent.com/Alex0510/Eric/master/surge/Script/xxysad.js,pattern=https:\/\/.*\..*\.com\/(vod\/reqplay\/|ucp/index|getGlobalData),max-size=131072,requires-body=true,timeout=10,enable=true
爱美剧VIP&ads = type=http-response,script-path=https://raw.githubusercontent.com/wf021325/qx/master/js/aimeiju.js,pattern=^http(s)://api.bjxkhc.com/index.php/app/ios/(vod/show|(user|vod|topic|type)/index),max-size=131072,requires-body=true,timeout=10,enable=true
网易蜗牛读书VIP (By yxiaocai and JO2EY) = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/File/wnyd.js,pattern=^https?:\/\/p\.du\.163\.com\/gain\/readtime\/info\.json,max-size=131072,requires-body=true,timeout=10,enable=true
看漫画极速版vip (By HoGer) = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/File/kmh.js,pattern=^https?:\/\/getuserinfo\.321mh\.com\/app_api\/v5\/getuserinfo\/,max-size=131072,requires-body=true,timeout=10,enable=true
知音漫客VIP (By mieqq) = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/File/Zymh.js,pattern=^https://getuserinfo-globalapi.zymk.cn/app_api/v5/(getuserinfo|coin_account|getuserinfo_ticket|getcomicinfo)/,max-size=131072,requires-body=true,timeout=10,enable=true
VSCO滤镜VIP = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/File/vsco.js,pattern=^https?:\/\/vsco\.co\/api\/subscriptions\/2.1\/user-subscriptions\/,max-size=131072,requires-body=true,timeout=10,enable=true
大片-视频编辑器 VIP = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/File/dapian.js,pattern=^https?:\/\/api\.vnision\.com\/v1\/(users\/|banners),max-size=131072,requires-body=true,timeout=10,enable=true
去广告 = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/File/xjsp.js,pattern=^https?:\/\/.*\.*apps\.com\/(ucp\/index|getGlobalData|.+\/reqplay\/),max-size=131072,requires-body=true,timeout=10,enable=true
用药助手解锁专业版 (By Primovist) = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/yyzs.js,pattern=^https?:\/\/(i|newdrugs)\.dxy\.cn\/(snsapi\/username\/|app\/user\/(pro\/stat\?|init\?timestamp=)),max-size=131072,requires-body=true,timeout=10,enable=true
陆琪讲故事 = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/luqi.js,pattern=^https:\/\/www\.luqijianggushi\.com\/api\/v2\/user\/get,max-size=131072,requires-body=true,timeout=10,enable=true
WPS (By eHpo) = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/Wps.js,pattern=^https://account.wps.*/api/users/,max-size=131072,requires-body=true,timeout=10,enable=true
Gyroscope 解锁 pro (By Maasea) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/NobyDa/Surge/JS/gyroscope.js,pattern=^https:\/\/api\.gyrosco\.pe\/v1\/account\/$,max-size=131072,requires-body=true,timeout=10,enable=true
水印精灵 vip (By Alex0510) = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/syjl.js,pattern=^https:\/\/api1\.dobenge\.cn\/api\/user\/getuserinfo,max-size=131072,requires-body=true,timeout=10,enable=true
大千视界 = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/dqsj.js,pattern=^https:\/\/api\.mvmtv\.com\/index\.php.*(c=user.*a=info|a=addr.*vid=.*),max-size=131072,requires-body=true,timeout=10,enable=true
JibJab解锁pro = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/jibjab.js,pattern=^https:\/\/origin-prod-phoenix\.jibjab\.com\/v1\/user,max-size=131072,requires-body=true,timeout=10,enable=true
Termius 解锁本地pro  (By Maasea) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/NobyDa/Surge/JS/Termius.js,pattern=https:\/\/api\.termius\.com\/api\/v3\/bulk\/account\/,max-size=131072,requires-body=true,timeout=10,enable=true
小影 解锁Vip (By @hiepkimcdtk55) = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/vivavideo.js,pattern=^https:\/\/viva\.v21xy\.com\/api\/rest\/u\/vip,max-size=131072,requires-body=true,timeout=10,enable=true
彩云天气 Vip = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/NobyDa/QuantumultX/File/ColorWeather.js,pattern=^https:\/\/biz\.caiyunapp\.com\/v2\/user\?app_name\=weather,max-size=131072,requires-body=true,timeout=10,enable=true
Keep 解锁私人课程和动作库 (QX存在bug 该脚本可能无法生效) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/NobyDa/Surge/JS/Keep.js,pattern=^https:\/\/api\.gotokeep\.com\/(.+\/subject|.+\/dynamic),max-size=131072,requires-body=true,timeout=10,enable=true
扫描全能王 pro = type=http-response,script-path=https://raw.githubusercontent.com/aa75017730/Quantumult-X/main/JS_failarmy/camscanner.js,pattern=^https:\/\/(api|api-cs)\.intsig\.net\/purchase\/cs\/query_property\?,max-size=131072,requires-body=true,timeout=10,enable=true
VUE pro = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/VUE.js,pattern=^https:\/\/api\.vuevideo\.net\/api\/v1\/(users\/.+\/profile|subtitle\/prepare),max-size=131072,requires-body=true,timeout=10,enable=true
NiChi 解锁素材 = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/NiChi.js,pattern=^https?:\/\/mp\.bybutter\.com\/mood\/(official-templates|privileges),max-size=131072,requires-body=true,timeout=10,enable=true
PicsArt美易 pro = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/PicsArt.js,pattern=^https:\/\/api\.(picsart|meiease)\.c(n|om)\/users\/show\/me\.json,max-size=131072,requires-body=true,timeout=10,enable=true
Splice 视频编辑器 pro = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/NobyDa/Surge/JS/Splice.js,pattern=^https:\/\/splice\.oracle\.\w+\.com\/devices\/me,max-size=131072,requires-body=true,timeout=10,enable=true
百度云倍速播放 = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/BaiduCloud.js,pattern=https:\/\/pan\.baidu\.com\/rest\/2\.0\/membership\/user,max-size=131072,requires-body=true,timeout=10,enable=true
皮皮虾 去广告去水印 = type=http-response,script-path=https://raw.githubusercontent.com/Liquor030/Sub_Ruleset/master/Script/Super.js,pattern=^https?://.*\.snssdk\.com/bds/(feed/stream|comment/cell_reply|cell/cell_comment|cell/detail|ward/list|user/favorite|user/cell_coment|user/cell_userfeed|user/publish_list),max-size=131072,requires-body=true,timeout=10,enable=true
vsco = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/vsco.js,pattern=^https?:\/\/vsco\.co\/api\/subscriptions\/2.1\/user-subscriptions\/,max-size=131072,requires-body=true,timeout=10,enable=true
gyroscope = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/Gyroscope.vip.js,pattern=^https:\/\/api\.gyrosco\.pe\/v1\/account\/$,max-size=131072,requires-body=true,timeout=10,enable=true
Termius = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/Terminus.js,pattern=https:\/\/api\.termius\.com\/api\/v3\/bulk\/account\/,max-size=131072,requires-body=true,timeout=10,enable=true
PicsArt = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/picsArt.vip.js,pattern=^https:\/\/api\.(picsart|meiease)\.c(n|om)\/users\/show\/me\.json,max-size=131072,requires-body=true,timeout=10,enable=true
Vivavideo = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/vivavideo.vip.js,pattern=^https:\/\/viva-asia1\.vvbrd\.com\/api\/rest\/u\/vip*,max-size=131072,requires-body=true,timeout=10,enable=true
Undfold = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/Unfold.vip.js,pattern=^https:\/\/api\.unfold\.app\/v1\/ios\/receipts$,max-size=131072,requires-body=true,timeout=10,enable=true
Nhaccuatui = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/nhaccuatui.js,pattern=^https:\/\/graph\.nhaccuatui\.com\/.*\/users\/info*,max-size=131072,requires-body=true,timeout=10,enable=true
Jibjab = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/jibjab.vip.js,pattern=^https:\/\/origin-prod-phoenix\.jibjab\.com\/v1\/user$,max-size=131072,requires-body=true,timeout=10,enable=true
buyhack = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/verify_receipt.js,pattern=^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt$,max-size=131072,requires-body=true,timeout=10,enable=true
sync = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/syn.me.js,pattern=^https:\/\/api\.sync\.me\/api\/purchases\/(report_purchases|get_purchases),max-size=131072,requires-body=true,timeout=10,enable=true
elsaresponse = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/elsa-response.js,pattern=^https:\/\/pool\.elsanow\.io\/user\/api\/v1\/purchase$,max-size=131072,requires-body=true,timeout=10,enable=true
drops = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/drops.js,pattern=^https:\/\/lambda\.us-east-1\.amazonaws\.com/.*/functions\/prod-4-syncPurchases\/invocations$,max-size=131072,requires-body=true,timeout=10,enable=true
mondly = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/mondly.vip.js,pattern=^https:\/\/api\.mondlylanguages\.com\/v1\/ios\/user\/sync$,max-size=131072,requires-body=true,timeout=10,enable=true
busuu = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/busuu.vip.js,pattern=^https:\/\/api\.busuu\.com\/users\/me*,max-size=131072,requires-body=true,timeout=10,enable=true
Videoshow = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/videoshow.vip.js,pattern=^https:\/\/owa\.videoshowiosglobalserver\.com\/.*\/iosPayClient,max-size=131072,requires-body=true,timeout=10,enable=true
elevate = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/elevate.vip.js,pattern=^https:\/\/accounts\.elevateapp\.net\/api\/users\?user%5Bauthentication_token*,max-size=131072,requires-body=true,timeout=10,enable=true
beautyplus = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/beautyplusvip.js,pattern=^https:\/\/api-intl\.mr\.meitu\.com/.*/subs_offer_elg$,max-size=131072,requires-body=true,timeout=10,enable=true
camera360 = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/camera360.vip.js,pattern=^https:\/\/bmall\.camera360\.com\/api\/(iap\/check-receipt$|mix\/getinfo$),max-size=131072,requires-body=true,timeout=10,enable=true
zingtv = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/zingtvvipv1.js,pattern=^https?:\/\/api\.tv\.zing\.vn\/.*/user*,max-size=131072,requires-body=true,timeout=10,enable=true
calm = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/calm.vip.js,pattern=^https:\/\/api\.calm\.com\/me$,max-size=131072,requires-body=true,timeout=10,enable=true
lightroom = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/Lightroom.js,pattern=^https:\/\/photos\.adobe\.io\/v2\/accounts*,max-size=131072,requires-body=true,timeout=10,enable=true
Pdfexpert = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/Pdfexpert.vip.js,pattern=^https:\/\/license\.pdfexpert\.com\/api\/1\.0\/pdfexpert6\/subscription\/(refresh$|check$),max-size=131072,requires-body=true,timeout=10,enable=true
productive&sleepzy&weather live = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/productive.js,pattern=^https:\/\/subs\.platforms\.team\/.+\/apple\/verify$,max-size=131072,requires-body=true,timeout=10,enable=true
Musixmatch = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/musixmatch.miao.js,pattern=^https:\/\/apic\.musixmatch\.com\/ws\/.*\/config\.get,max-size=131072,requires-body=true,timeout=10,enable=true
mimo = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/mimo.vip.js,pattern=^https:\/\/api\.getmimo\.com\/v1\/subscriptions$,max-size=131072,requires-body=true,timeout=10,enable=true
mojo&noto = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/revenuecat.js,pattern=^https:\/\/api\.revenuecat\.com\/.+\/(receipts$|subscribers\/[a-zA-Z0-9_-]*$),max-size=131072,requires-body=true,timeout=10,enable=true
Bright = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/Bright.rsp,pattern=^https:\/\/engbright\.com\/app-portal\/apple\/receipt$,max-size=131072,requires-body=true,timeout=10,enable=true
lingokids = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/lingokids.vip.js,pattern=^https:\/\/api\.lingokids\.com\/v1\/renovate_session$,max-size=131072,requires-body=true,timeout=10,enable=true
musicalm = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/musicalm.js,pattern=^https:\/\/www\.peacefulsoundsapp\.com\/api\/v1\/init$,max-size=131072,requires-body=true,timeout=10,enable=true
duolingo_test = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/duolingo.js,pattern=^https:\/\/duolingo-leaderboards-prod\.duolingo\.com\/leaderboards*,max-size=131072,requires-body=true,timeout=10,enable=true
ulike = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/ulike.js,pattern=^https:\/\/commerce-i18n-api\.faceu\.mobi\/commerce\/v1\/subscription\/user_info$,max-size=131072,requires-body=true,timeout=10,enable=true
zingmp3 = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/zingmp3.js,pattern=^https:\/\/api\.global\.mp3\.zing\.vn\/1\.0\/getUserInfo\?data=*,max-size=131072,requires-body=true,timeout=10,enable=true
Blinkist = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/blinkist.js,pattern=^https:\/\/api\.blinkist\.com\/v4\/(me$|me.json$|me\/access$),max-size=131072,requires-body=true,timeout=10,enable=true
sololearn = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/sololearn.js,pattern=^https:\/\/api\.sololearn\.com\/(Profile\/GetProfile$|authenticateDevice$),max-size=131072,requires-body=true,timeout=10,enable=true
kinemaster = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/kinemaster.js,pattern=^https:\/\/api-kinemaster-assetstore\.(nexstreaming|kinemasters)\.com\/.*\/product\/verifyReceipt$,max-size=131072,requires-body=true,timeout=10,enable=true
pushover = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/pushover.js,pattern=^https:\/\/api\.pushover\.net\/1\/messages\.json*,max-size=131072,requires-body=true,timeout=10,enable=true
CamScanner = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/CamScaner.js,pattern=^https:\/\/(api|api-cs)\.intsig\.net\/purchase\/cs\/query_property\?,max-size=131072,requires-body=true,timeout=10,enable=true
over = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/over.vip.js,pattern=^https:\/\/api\.overhq\.com\/(user\/token\/refresh$|subscription\/verifyReceipt$),max-size=131072,requires-body=true,timeout=10,enable=true
speak&translate = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/speak&translate.js,pattern=^https:\/\/receipt-validator\.herewetest\.com\/apple\/verifyTransaction$,max-size=131072,requires-body=true,timeout=10,enable=true
document = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/documents.js,pattern=^https:\/\/license\.pdfexpert\.com\/api\/.*\/documents\/subscription\/(refresh$|check$),max-size=131072,requires-body=true,timeout=10,enable=true
workingcopy = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/workingcopy.js,pattern=^https:\/\/education\.github\.com\/api\/user$,max-size=131072,requires-body=true,timeout=10,enable=true
phothop&PSexpress = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/photoshop.js,pattern=^https:\/\/lcs-mobile-cops\.adobe\.io\/mobile_profile,max-size=131072,requires-body=true,timeout=10,enable=true
dayone = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/dayone.js,pattern=^https:\/\/dayone\.me\/api\/(users|v2\/users\/account-status)$,max-size=131072,requires-body=true,timeout=10,enable=true
endel = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/endel.js,pattern=^https:\/\/api-production\.endel\.io\/.*\/user$,max-size=131072,requires-body=true,timeout=10,enable=true
shred = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/shred.js,pattern=^https:\/\/api\.shred\.app\/verifyReceipt$,max-size=131072,requires-body=true,timeout=10,enable=true
nichi = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/nichi.js,pattern=^https?:\/\/mp\.bybutter\.com\/mood\/(official-templates|privileges),max-size=131072,requires-body=true,timeout=10,enable=true
grammarly = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/grammarly.js,pattern=^https:\/\/subscription\.grammarly\.com\/api\/v1$,max-size=131072,requires-body=true,timeout=10,enable=true
splice = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/splice.js,pattern=^https:\/\/splice\.oracle\.\w+\.com\/devices\/me,max-size=131072,requires-body=true,timeout=10,enable=true
all apps monkey = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/monkey.js,pattern=^https:\/\/www\.api\.monkeyuni\.net\/api\/.+\/mobile\/account\/load-update,max-size=131072,requires-body=true,timeout=10,enable=true
textnow = type=http-response,script-path=https://raw.githubusercontent.com/langkhach270389/Scripting/master/Textnow.js,pattern=^https:\/\/api\.textnow\.me\/api2.0\/users\/.*,max-size=131072,requires-body=true,timeout=10,enable=true
驾校一点通 (by @superuv) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/jxydt.js,pattern=^https:\/\/vipapi\.jxedt\.com\/vip\/check,max-size=131072,requires-body=true,timeout=10,enable=true
彩云小译 (by @superuv) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/cyxy.js,pattern=^https:\/\/api\.interpreter\.caiyunai\.com\/v1\/user,max-size=131072,requires-body=true,timeout=10,enable=true
Bear熊掌记  内购解锁 = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/bear.js,pattern=^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt,max-size=131072,requires-body=true,timeout=10,enable=true
Pocket list (by @superuv) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/pock.js,pattern=^https:\/\/pocketlists\.com\/api\/v1\/pocketlists.me.get,max-size=131072,requires-body=true,timeout=10,enable=true
海豚记账 (by @superuv) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/HTJZ.js,pattern=https:\/\/book\.haitunwallet\.com\/app\/vip\/status,max-size=131072,requires-body=true,timeout=10,enable=true
幕布 (by @superuv) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/mb.js,pattern=https:\/\/mubu\.com\/api\/app\/user\/info,max-size=131072,requires-body=true,timeout=10,enable=true
智能证件照相机 (by @superuv) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/znzj.js,pattern=^https:\/\/app\.xunjiepdf\.com\/api\/v4\/virtualactregister,max-size=131072,requires-body=true,timeout=10,enable=true
猫咪翻译(by @superuv) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/mmfy.js,pattern=http:\/\/miaow\.yiyongcad\.com\/api\/v4\/memprofile,max-size=131072,requires-body=true,timeout=10,enable=true
微商助手(by @superuv) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/wszs.js,pattern=https:\/\/api\.lennou\.com\/user\/info,max-size=131072,requires-body=true,timeout=10,enable=true
gk扫描仪(by @superuv) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/smy.js,pattern=^https:\/\/api\.gkocr\.com\/api\/userlogin1.php,max-size=131072,requires-body=true,timeout=10,enable=true
流利说.阅读 (by@火羽&@singee) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/llyd.js,pattern=^https?:\/\/vira\.llsapp\.com\/api\/v2\/readings\/(accessible|limitation),max-size=131072,requires-body=true,timeout=10,enable=true
abaenglish (未测试) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/abaenglish.vip.js,pattern=^https:\/\/api\.revenuecat\.com\/v1\/(receipts|\d{1,})$,max-size=131072,requires-body=true,timeout=10,enable=true
轻颜相机 & ulike & 蒸汽波相机(vaporcam)三合一 解锁VIP(By @s y & Alex0510) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/qyxj.js,pattern=https://(commerce-.*api|pay).(faceu|wecut).(com|mobi)/(commerce|apple)/(iosAppVerifyReceipt.php|v1/subscription/user_info),max-size=131072,requires-body=true,timeout=10,enable=true
CPU Dasher破解(恢复购买后禁用掉 By @s y) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/cupdasher.js,pattern=^https:\/\/p.+-buy\.itunes\.apple\.com\/WebObjects\/MZFinance.woa\/wa\/inAppRegrantPurchaseHistory,max-size=131072,requires-body=true,timeout=10,enable=true
酷我换肤(已经有的皮肤需要先从本地皮肤删除再换 By@ s y) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/themekuwo.js,pattern=^https?:\/\/vip1\.kuwo\.cn\/(vip\/v2\/theme),max-size=131072,requires-body=true,timeout=10,enable=true
lake = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/lake.js,pattern=^https:\/\/api\.lakecoloring\.com\/v1\/receipt,max-size=131072,requires-body=true,timeout=10,enable=true
人人影视字幕组(商店版)去广告,保留轮播推荐影片(By @Kaya) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/YYeTs.js,pattern=^http://ctrl.playcvn.com/app/(init|ads),max-size=131072,requires-body=true,timeout=10,enable=true
每日英语阅读/每日外刊 解锁课程  (By chamberlen) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/mryy.js,pattern=^https:\/\/dict\.eudic\.net\/jingting\/GetThisChapterTaskStatus?,max-size=131072,requires-body=true,timeout=10,enable=true
联通营业厅 去轮播广告 (By Wangsc1) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/china_unicom.js,pattern=^https?://m.client.10010.com/uniAdmsInterface/getHomePageAd,max-size=131072,requires-body=true,timeout=10,enable=true
第一弹 去广告+原画 (By Miao Miao) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/Diyidan.js,pattern=^https:\/\/api\.diyidan\.net\/v0\.3\/(user\/personal_homepage|vip_user\/info|tv_series\/index\?appChanne),max-size=131072,requires-body=true,timeout=10,enable=true
Fantastical 内购解锁 (By @sunshy) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/fantastical.js,pattern=^https:\/\/api\.flexibits\.com\/v1\/(auth|account)\/(device|details|appstore-receipt)\/$,max-size=131072,requires-body=true,timeout=10,enable=true
菜谱大全解锁vip (By @photonmang) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/cpdq.js,pattern=https?:\/\/api\.jiaonizuocai\.com,max-size=131072,requires-body=true,timeout=10,enable=true
SoloLearn Unlock PRO & Platinum Moderator (By @sunshy) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/sololearn.js,pattern=https:\/\/api\.sololearn\.com\/(authenticateDevice|challenge\/GetContestFeed|Profile\/GetProfile)$,max-size=131072,requires-body=true,timeout=10,enable=true
头脑吃鸡 = type=http-response,script-path=https://raw.githubusercontent.com/chavyleung/scripts/master/tncj/tncj.min.js,pattern=^https://tncj.hortorgames.com/chicken/fight/(answer|findQuiz),max-size=131072,requires-body=true,timeout=10,enable=true
Pear 雪梨 = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/pear.js,pattern=^https:\/\/(www\.baidu.com2\.club|ayk\.tmdidi\.com|m\.pearkin\.com|souhu\.mett\.me|bkcd\.b-cdn\.net)\/(api\/movie\/WatchMovie|api\/Account\/CheckVip|api\/account\/IndexDetail),max-size=131072,requires-body=true,timeout=10,enable=true
克拉壁纸  解锁付费壁纸 (By @Dachaw) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/clarity.js,pattern=^https:\/\/claritywallpaper\.com\/clarity\/api\/(userInfo|special\/queryByCatalogAll),max-size=131072,requires-body=true,timeout=10,enable=true
洪恩双语绘本 (By 军哥哥) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/hnsyhb.js,pattern=https:\/\/bookapi\.ihuman\.com\/(v1\/get\_user\_info|v1\/get\_purchase\_list),max-size=131072,requires-body=true,timeout=10,enable=true
中国体育直播unlock (By 军哥哥) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/zgtyzb.js,pattern=http:\/\/rest\.zhibo\.tv\/room\/get\-room\-info\-v430,max-size=131072,requires-body=true,timeout=10,enable=true
有道云笔记VIP (ByAlex0510) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/ydybj.js,pattern=https://note.youdao.com/yws/(mapi/payment|api/self),max-size=131072,requires-body=true,timeout=10,enable=true
Peak 解锁Pro = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/peak.js,pattern=^https:\/\/billing\.peakcloud\.org\/billing\/2\/user\/me?,max-size=131072,requires-body=true,timeout=10,enable=true
IT之家 去新闻列表广告 = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/ITHome.js,pattern=^https?:\/\/api\.ithome\.com\/json\/(newslist|listpage)\/news,max-size=131072,requires-body=true,timeout=10,enable=true
IT之家 去新闻列表广告 = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/ITHome.js,pattern=^https?:\/\/api\.ithome\.com\/json\/slide\/index,max-size=131072,requires-body=true,timeout=10,enable=true
万里影视 （by LTribe） = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/Wanliyingshi.js,pattern=^http?:\/\/.*\.arten.cn/login/login,max-size=131072,requires-body=true,timeout=10,enable=true
奇热小说 解锁收费章节(By @@ios4521) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/qrxs.js,pattern=^https://api.weiqire.com/api3/(visitor/|user/unlockCharpter),max-size=131072,requires-body=true,timeout=10,enable=true
石墨文档 (By Alex0510) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/shimo.js,pattern=https://api.shimo.im/users/,max-size=131072,requires-body=true,timeout=10,enable=true
VideoStar Unlock（by LTribe） = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/VideoStar.js,pattern=^https?:\/\/.*\.videostarapp\.com\/scripts\/subsNew\.php,max-size=131072,requires-body=true,timeout=10,enable=true
Pillow (By @CheeryTodo) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/pillow.js,pattern=https:\/\/api\.revenuecat\.com\/v1\/(subscribers|receipts),max-size=131072,requires-body=true,timeout=10,enable=true
韩剧TV (By 凉意) 下载地址请看脚本内说明 = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/hanjuTV.js,pattern=^https\:\/\/hjapi\.bjxkhc\.com\/v2d2\/users\/.*\/member,max-size=131072,requires-body=true,timeout=10,enable=true
手机硬件管家 (By Alex0510) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/sjyjgj.js,pattern=http:\/\/api\.591master\.com\:8081\/(1.0|3.6.8)\/ui(forum|common)\/(downloadwallpaper|getuser),max-size=131072,requires-body=true,timeout=10,enable=true
筋斗云tv (By 凉意) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/jdyTV.js,pattern=^http\:\/\/jdytv\.cn\/login\/login\/veifys,max-size=131072,requires-body=true,timeout=10,enable=true
花椒视频 (By Alex0510) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/hjsp.js,pattern=http://user.shywck.com/user/userinfo,max-size=131072,requires-body=true,timeout=10,enable=true
迅捷应用6合1 （by LTribe） = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/xunjie.js,pattern=^https?:\/\/.*\.xunjie.*\.com\/api\/v\d\/*,max-size=131072,requires-body=true,timeout=10,enable=true
小睡眠（by 黑黑酱） = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/xiaoshuimian.js,pattern=^https:\/\/api\.psy-1\.com\/cosleep\/user\/info,max-size=131072,requires-body=true,timeout=10,enable=true
蜗牛睡眠会员（by黑黑酱） = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/wnsm.js,pattern=^https:\/\/snailsleep\.net\/snail\/v1\/profile\/get,max-size=131072,requires-body=true,timeout=10,enable=true
可可英语会员 = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/kkyy.js,pattern=^https:\/\/mob2015\.kekenet\.com\/keke\/mobile\/index\.php,max-size=131072,requires-body=true,timeout=10,enable=true
飒漫画 (By @u18888) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/Smh.js,pattern=^https:\/\/m\.samh\.xndm\.tech\/userapi\/info\/v1\/getuserinfo,max-size=131072,requires-body=true,timeout=10,enable=true
闪电下载vip (By 凉意) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/sdxz.js,pattern=^http\:\/\/app\.flashdown365\.com\/ios\/login,max-size=131072,requires-body=true,timeout=10,enable=true
西窗烛 （By 黑黑酱） = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/xcz.js,pattern=^https:\/\/avoscloud\.com\/1\.1\/users\/,max-size=131072,requires-body=true,timeout=10,enable=true
JAV101无限观看 (By 凉意) = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/JAV101.js,pattern=^https\:\/\/pwaapi\.gao1gps\.cn\/v1\/user\/info,max-size=131072,requires-body=true,timeout=10,enable=true
美颜相机一次性解锁内购（by黑黑酱） = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/myxj.js,pattern=^https:\/\/api\.meiyan\.com\/iap\/verify\.json,max-size=131072,requires-body=truetimeout=60,enable=true
Fit健身会员 （by黑黑酱） = type=http-response,script-path=https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Script/fit.js,pattern=^https:\/\/bea\.sportq\.com\/SFitWeb\/sfit\/getUserBaseInfo,max-size=131072,requires-body=truetimeout=60,enable=true
动画疯 去广告(by NobyDa) = type=http-response,script-path=https://raw.githubusercontent.com/NobyDa/Script/master/Surge/JS/Bahamut.js,pattern=https:\/\/api\.gamer\.com\.tw\/mobile_app\/anime\/v3\/token\.php,max-size=131072,requires-body=truetimeout=60,enable=true
Netflix获取评分(by yichahucha) = type=http-response,script-path=https://raw.githubusercontent.com/yichahucha/surge/master/nf_rating.js,pattern=^https?://ios\.prod\.ftl\.netflix\.com/iosui/user/.+path=%5B%22videos%22%2C%\d+%22%2C%22summary%22%5D,max-size=131072,requires-body=truetimeout=60,enable=true
单集评分 = type=http-response,script-path=https://raw.githubusercontent.com/yichahucha/surge/master/nf_rating_season.js,pattern=^https?://ios\.prod\.ftl\.netflix\.com/iosui/warmer/.+type=show-ath,max-size=131072,requires-body=truetimeout=60,enable=true
```
### [MITM]
```
[MITM]
hostname =api-cs.intsig.net,vira.llsapp.com,i.weread.qq.com,101*.*.*,116.*.*.*,117.*.*.*,120.*.*.*,121.*.*.*,140.*.*.*,183.*.*.*,203*.*.*,*.wtzw.com,api_2496.kuwo.cn， txv04.com,i.xinyulib.com.cn,api.polarisoffice.com,kd.youth.cn,ios.baertt.com,api.meiyan.com,*.tiktokv.com,*.byteoversea.com,*.tik-tokapi.com,trade-acs.m.taobao.com,api.m.jd.com,app.58.com,acs.m.taobao.com,m*.amap.com,api-new.app.acfun.cn,api.bjxkhc.com,*.amemv.com,*.snssdk.com,issuecdn.baidupcs.com,pan.baidu.com,newclient.map.baidu.com,mime.baidu.com,act.vip.iqiyi.com,app.bilibili.com,manga.bilibili.com,m.client.10010.com,cloud.189.cn,www.youtube.com,s.youtube.com,ios.wps.cn,api.jr.mi.com,appconf.mail.163.com,c.m.163.com,client.mail.163.com,interface*.music.163.com,support.you.163.com,p.du.163.com,*.uve.weibo.com,weibointl.api.weibo.cn,api.weibo.cn,mapi.weibo.com,tqt.weibo.cn,*.k.sohu.com,*.tv.sohu.com,ap*.smzdm.com,ssl.kohsocialapp.qq.com,4gimg.map.qq.com,r.inews.qq.com,news.ssp.qq.com,mp.weixin.qq.com,api.zhihu.com,*.googlevideo.com,*.musical.ly,vip1.kuwo.cn,jdjoy.jd.com,draw.jdfcloud.com,mobile01.91quzou.com,mk.immomo.com,huiyuan.163.com,geekhub.com,cxdng.cpic.com.cn,h5.youzan.com,api.infzm.com,api.xiaoheihe.cn,exp.angelalign.com,ngabbs.com,api.umer.com.cn,app*.jegotrip.com.cn,task.jegotrip.com.cn,my.ruanmei.com,www.mydigit.cn,wx-mini.pagoda.com.cn,m.weibo.cn,apapia-history.manmanbuy.com,weather-data.apple.com,mall.oclean.com,api.cashtoutiao.com,user-api-prd-mx.wandafilm.com,h5.bianlifeng.com,teacherapi.zmlearn.com,clientaccess.10086.cn,maicai.api.ddxq.mobi,vip.heytea.com,webapi.qmai.cn,proapi.115.com,proxy.vac.qq.com,*.xmcimg.com,as.xiaojukeji.com,note.youdao.com,music.163.com,c.tieba.baidu.com,weibo.com,iface?.iqiyi.com,*.smzdm.com,*.v2ex.com,www.52pojie.cn,*.bilibili.com,*.feng.com,*.video.qq.com,*.acfun.cn,*.rrys2019.com,mobwsa.ximalaya.com,*.rr.tv,www.flyertea.com,wapside.189.cn,sf-integral-sign-in.weixinjia.net,h5.ele.me,*.you.163.com,apk.tw,api.dongqiudi.com,*.m.163.com,user.qunar.com,yuba.douyu.com,ios.zmzapi.com,*.y.qq.com,*.csdn.net,m.ctrip.com,m.gdoil.cn,credits.bz.mgtv.com,api-takumi.mihoyo.com,act.10010.com,e.189.cn,www.maomicd.com,wx.10086.cn,mtrace.qq.com,www.lltxt.com,weclub.ccc.cmbchina.com,promotion.waimai.meituan.com,i.meituan.com,daojia.jd.com,api-hdcj.9w9.com,api.everphoto.cn,group.baicizhan.com,pm.m.fenqile.com,ms.jr.jd.com,nebula.kuaishou.com,api.dushu.io,node.kg.qq.com,app.nio.com,wxprdapplet.gac-nio.com,activity-1.m.duiba.com.cn,m-bean.kaola.com,110.43.90.61,zt.wps.cn,xiaoshuo.qm989.com,passport.suning.com,luckman.suning.com,sign.suning.com,gameapi.suning.com,m.ximalaya.com,iphone.myzaker.com,sapi.beingfine.cn,icbc1.wlphp.com,wx.17u.cn,frodo.douban.com,mcs-mimp-web.sf-express.com,gameapi.hellobike.com,mwegame.qq.com,api.1sapp.com,tieba.baidu.com,app.jf.360.cn,pay.sc.weibo.com,api.inews.qq.com,newsapi.sina.cn,*.youth.cn,apiwz.midukanshu.com,www.duokan.com,appv8.qukantianxia.com,appv7.qukantx.com,xwsh.javamall.cn,operation-api.jimistore.com,account.wps.cn,greasyfork.org,openuserjs.org,*.*apps.com,bea.sportq.com,*.gao1gps.cn,avoscloud.com,app.flashdown365.com,m.samh.xndm.tech,mob2015.kekenet.com,ios.prod.ftl.netflix.com,vipapi.jxedt.com,api.interpreter.caiyunai.com,pocketlists.com,book.haitunwallet.com,mubu.com,app.xunjiepdf.com,miaow.yiyongcad.com,api.lennou.com,api.gkocr.com,commerce-.*api.faceu.mobi,commerce-api.faceu.mobi,api.revenuecat.com,api.rr.tv,editorapi.115.com,dida365.com,ticktick.com,api.lakecoloring.com,ctrl.playcvn.com,dict.eudic.net,api.wakamoment.ga,*.bh3.com,api.diyidan.net,api.flexibits.com,api.jiaonizuocai.com,api.sololearn.com,tncj.hortorgames.com,bkcd.b-cdn.net,souhu.mett.me,ayk.tmdidi.com,m.pearkin.com,www.baidu.com2.club,claritywallpaper.com,bookapi.ihuman.com,rest.zhibo.tv,billing.peakcloud.org,api.ithome.com,www.xmind.cn,*.arten.cn,api.weiqire.com,api.shimo.im,pay.wecut.com,*.videostarapp.com,app.api.versa-ai.com,*.bjxkhc.com,api.591master.com,jdytv.cn,user.shywck.com,*.xunjie*.com,api.psy-1.com,snailsleep.net,api.bilibili.com,link.zhihu.com,aweme*.snssdk.com,*.kuwo.cn,*.xiao*.com,*.xiaoxiao*.com,getuserinfo.321mh.com,getuserinfo-globalapi.zymk.cn,ios.fuliapps.com,vsco.co,api.vnision.com,*.my10api.com,sp.kaola.com,apple.fuliapps.com,newdrugs.dxy.cn,app101.avictown.cc,api.hlo.xyz,api.ijo.xyz,www.luqijianggushi.com,account.wps.*,u.kanghuayun.com,api.gyrosco.pe,api1.dobenge.cn,api.mvmtv.com,mitaoapp.yeduapp.com,origin-prod-phoenix.jibjab.com,www.3ivf.com,pay.guoing.com,api.termius.com,viva.v21xy.com,biz.caiyunapp.com,api.gotokeep.com,ap*.intsig.net,api.vuevideo.net,api.picsart.c*,api.meiease.c*,api.gamer.com.tw,ios.xiangjiaoapps.com,apple.xiangjiaoapps.com,*.lagoapps.com,*.xiangxiangapps.com,avatar-nct.nixcdn.com,spclient.wg.spotify.com,oa.zalo.me,api.unfold.app,viva-asia1.vvbrd.com,graph.nhaccuatui.com,api.memrise.com,api.sync.me,pool.elsanow.io,lambda.us-east-1.amazonaws.com,api.mondlylanguages.com,api.busuu.com,owa.videoshowiosglobalserver.com:0,accounts.elevateapp.net,purchases.ws.pho.to,api-intl.mr.meitu.com,bmall.camera360.com,api.tv.zing.vn,api.calm.com,www.calm.com,api.global.mp3.zing.vn,apimboom2.globaldelight.net,photos.adobe.io,license.pdfexpert.com,subs.platforms.team,apic.musixmatch.com,api.getmimo.com,engbright.com,api.lingokids.com,www.peacefulsoundsapp.com,duolingo-leaderboards-prod.duolingo.com,mobile-api.adguard.com,api.blinkist.com,api-kinemaster-assetstore.*,api.pushover.net,api.overhq.com,receipt-validator.herewetest.com,lcs-mobile-cops.adobe.io,education.github.com,backend.getdrafts.com,ssl-api.itranslateapp.com,sk.ulysses.app,dayone.me,license.enpass.io,mp.bybutter.com,*.grammarly.com,splice.oracle.*.com,api.keepkeep.com,planner5d.com,secure.istreamer.com,www.api.monkeyuni.net,api.textnow.me,*.xxjjappss.com,*.huaerdadi.com,*.xiaoxiaoapps.com,*.xiaoxiaoimg.com,ws.60he.com,app.qdjdswkj.com,api.rcljx.com,api.qishangzs.com,damiyingshi.app.bucuo.online,.*.top,node.52tt.com,m.jingxi.com,wxavip-tp.ezrpro.cn,lginstaacademy.com,ranlv.lvfacn.com,jqb.iphonezhuan.com,testflight.apple.com,dkd-api.dysdk.com,%INSERT%mp.weixin.qq.com,bububao.duoshoutuan.com,api.yikeapp.com,mobile.app.autohome.com.cn,openapi.autohome.com.cn,meow-api.sxyj.net,gist.githubusercontent.com,raw.githubusercontent.com,img10.360buyimg.com,gd.10086.cn,pgdt.ugdtimg.com,api*.amemv.com,api*.musical.ly,api.xiuxiu.meitu.com,outcut.szsszykj.com,api.shayujizhang.com,wq.jd.com,mqqapi.reader.qq.com,mb3admin.com,www.maoke123.com,myiconisme.com,%APPEND%api.m.jd.com,minigame.ucpopo.com,duoting.tatatimes.com,cm.szsszykj.com,bbs.maibaapp.com,lkyl.dianpusoft.cn,www.baimaa.com,youtubei.googleapis.com,*.zhihu.com,api*.tiktokv.com,mjappaz.yefu365.com,api-163.biliapi.net,bd.4008109966.net,bdapp.4008109966.net,p.doras.api.vcinema.cn,api.meiease.c**,api.tophub.today,commerce-i18n-api.faceu.mobi,act.gaoqingdianshi.com,baimiao.uzero.cn,api4.bybutter.com,*-buy.itunes.apple.com,*.iqiyi.com,h5.m.jd.com,jk.5apk.cn,%APPEND%testflight.apple.com,gw.aoscdn.com,duckduckgo.com,sub.store,boxer.baidu.com,-*.weibo.com,security.wechat.com,weixin110.qq.com,%APPEND%sub.store,
enable = true
ca-passphrase = Shadowrocket
ca-p12 = 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
skip-server-cert-verify = true
```
