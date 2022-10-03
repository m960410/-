# > 交管12123
^https:\/\/gab\.122\.gov\.cn\/eapp\/m\/sysquery\/adver$ url reject
^https:\/\/gab\.122\.gov\.cn\/eapp\/m\/sysquery url reject
# > 高德地图
^https?+:\/\/m\d\.amap\.com\/ws\/valueadded\/alimama\/splash_screen\/ url reject-200
^https?:\/\/m5\.amap\.com\/ws\/valueadded\/ url reject
^https?:\/\/optimus-ads\.amap\.com\/uploadimg\/ url reject
# > 优酷
^https?:\/\/vali\.cp31\.ott\.cibntv\.net\/youku url reject
^https?:\/\/.+?\.ott\.cibntv\.net\/[\w\/-]+.mp4\?sid= url reject
^https?:\/\/[\w-.]+\.ott\.cibntv\.net\/[\w\/-]+.mp4\?ccode=02010101 url reject
^https?:\/\/[\w-.]+\.ott\.cibntv\.net\/[\w\/-]+.mp4\?sid= url reject
^https?:\/\/ups\.youku\.com\/.*?needad=1& url reject
^https?:\/\/r\.l\.youku\.com\/rec_at_click url reject-img
^https?:\/\/m\.youku\.com\/video\/libs\/iwt\.js url reject-img
^https?:\/\/api\.mobile\.youku\.com\/layout\/search\/hot\/word url reject-img
^https?:\/\/ad\.api\.3g\.youku\.com url reject-img
^https?:\/\/.+?\.atm\.youku\.com url reject
^https?:\/\/(iyes|(api|hd)\.mobile)\.youku\.com\/(adv|common\/v3\/hudong\/new) url reject-img
^https?:\/\/[\s\S]*\/youku\/.*?\.mp4 url reject-img
^http:\/\/ems\.youku\.com\/imp\? url reject
# > 芒果TV
^https?:\/\/pcvideoyd\.titan\.mgtv\.com\/pb\/ url reject-img
# > 知乎开屏页广告,首页右下角悬浮框,推荐列表广告,问题回答列表广告,具体回答下广告
^https:\/\/(appcloud2\.zhihu\.com\/v3\/config$|www\.zhihu\.com\/api\/v4\/answers\/\d+\/recommendations|api\.zhihu\.com\/(topstory\/recommend|commercial_api\/(real_time_launch_v2|app_float_layer$)|questions\/\d+\/feeds\?|v4\/questions\/\d+\/answers\?)) url script-response-body https://raw.githubusercontent.com/app2smile/rules/master/js/zhihu.js
# > BiliBili_哔哩哔哩_屏蔽IP请求
^https?:\/\/app\.bilibili\.com\/x\/resource\/ip url reject
# > BiliBili_哔哩哔哩_屏蔽
^https?:\/\/app\.bilibili\.com\/bilibili\.app\.interface\.v1\.Search\/Default url reject
# > BiliBili_哔哩哔哩_屏蔽首页右上活动[卸载重装]
^https?:\/\/app\.bilibili\.com\/x\/resource\/top\/activity url reject-dict
# > BiliBili_哔哩哔哩_启动时开启直连模式
^https?:\/\/api\.bilibili\.com\/x\/offline\/version url script-response-body https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Script/bilibili_startup_direct.js
# > BiliBili_哔哩哔哩_繁体CC字幕转中文简体[自行启用]
;^https?:\/\/i.\.hdslb\.com\/bfs\/subtitle\/.+\.json$ url script-response-body https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Script/bilibili_cc.js
# > BiliBili_哔哩哔哩_观影页面去广告
^https?:\/\/api\.(bilibili|biliapi)\.(com|net)\/pgc\/page\/cinema\/tab\? url script-response-body https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Script/bilibili_json.js
# > BiliBili_哔哩哔哩_应用开屏去广告
^https://app.bilibili.com/x/v2/splash/show url reject-dict
# > BiliBili_哔哩哔哩_应用开屏广告预加载
^https:\/\/app\.bilibili\.com\/x\/v2\/splash\/list url script-response-body https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Script/bilibili_json.js
# > BiliBili_哔哩哔哩_去除统一设置的皮肤
^https?:\/\/app\.bilibili\.com\/x\/resource\/show\/skin\? url script-response-body https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Script/bilibili_json.js
# > BiliBili_哔哩哔哩_1080P高码率+4K画质(番剧和影视除外)
^https?:\/\/app\.bilibili\.com\/x\/v2\/account\/myinfo\? url script-response-body https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Script/bilibili_json.js
# > BiliBili_哔哩哔哩_热搜发现
^https://app.bilibili.com/x/v2/search/square url script-response-body https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Script/bilibili_json.js
# > BiliBili_哔哩哔哩_Defaultword
^https://app.bilibili.com/x/v2/search/defaultwords url reject-dict
# > BiliBili_哔哩哔哩_Material_Ad
^https?:\/\/api\.bilibili\.com\/x\/vip\/ads\/material\/report url reject-dict
# > BiliBili_哔哩哔哩_小卡片广告
^https://api.bilibili.com/pgc/season/player/cards url reject-dict
# > BiliBili_哔哩哔哩_解除SIM卡地区限制
;(^https?:\/\/app\.biliintl.com\/intl\/.+)(&sim_code=\d+)(.+) url 302 $1$3
# > BiliBili_哔哩哔哩_去除搜索中的大家都在搜
^https?:\/\/api\.vc\.bilibili\.com\/search_svr\/v\d\/Search\/recommend_words url reject
# > BiliBili_哔哩哔哩_去除动态中的话题
^https?:\/\/api\.vc\.bilibili\.com\/topic_svr\/v1\/topic_svr url reject-dict
# > BiliBili_哔哩哔哩_可能的一些推广(beta)
^https?:\/\/api\.bilibili\.com\/pgc\/season\/app\/related\/recommend\? url reject-dict
# > BiliBili_哔哩哔哩_漫画去广告
^https?:\/\/manga\.bilibili\.com\/twirp\/comic\.v\d\.Comic\/(Flash|ListFlash) url reject-dict
# > BiliBili_哔哩哔哩_推荐去广告
^https?:\/\/app\.bilibili\.com\/x\/v2\/feed\/index url script-response-body https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Script/bilibili_json.js
# > BiliBili_哔哩哔哩_追番去广告
^https?:\/\/api\.(bilibili|biliapi)\.(com|net)\/pgc\/page\/bangumi url script-response-body https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Script/bilibili_json.js
# > BiliBili_哔哩哔哩_直播去广告
^https?:\/\/api\.live\.bilibili\.com\/xlive\/app-room\/v1\/index\/getInfoByRoom url script-response-body https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Script/bilibili_json.js
# > BiliBili_哔哩哔哩_动态去广告
^https?:\/\/api\.vc\.bilibili\.com\/dynamic_svr\/v1\/dynamic_svr\/dynamic_(history|new)\? url script-response-body https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Script/bilibili_json.js
# > BiliBili_哔哩哔哩_标籤页处理
^https?:\/\/app\.bilibili\.com\/x\/resource\/show\/tab url script-response-body https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Script/bilibili_json.js
# > BiliBili_哔哩哔哩_我的页面处理
^https?:\/\/app\.bilibili\.com\/x\/v2\/account\/mine url script-response-body https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Script/bilibili_json.js
# > BiliBili_哔哩哔哩_Proto去广告
^https:\/\/app\.bilibili\.com\/bilibili\.app\.(view\.v1\.View\/View|dynamic\.v2\.Dynamic\/DynAll)$ url script-response-body https://raw.githubusercontent.com/app2smile/rules/master/js/bilibili-proto.js
# > BiliBili_哔哩哔哩_动态广告
;^https://app\.bilibili\.com/bilibili\.app\.dynamic\.v2\.Dynamic/DynAll$ url script-response-body https://raw.githubusercontent.com/yjqiang/surge_scripts/main/scripts/bilibili/bilibili_dynamic.js
# > 腾讯广告
^https?:\/\/btrace\.qq\.com url reject-200
^https?:\/\/api2\.helper\.qq\.com\/game\/buttons url reject-img
^https?:\/\/\w+\.beacon\.qq\.com url reject
^https?:\/\/mi\.gdt\.qq\.com\/gdt_mview\.fcg url reject
^https?:\/\/lives\.l\.qq\.com\/livemsg\?sdtfrom= url reject-img
^https?:\/\/imgcache\.qq\.com\/qqlive\/ url reject-img
^https?:\/\/mtteve\.beacon\.qq\.com\/analytics url reject-img
^https?+:\/\/vv\.video\.qq\.com\/getvmind\? url reject-200
^https?+:\/\/ssl\.kohsocialapp\.qq\.com:10001\/game\/buttons url reject-200
^https?+:\/\/qt\.qq\.com\/lua\/mengyou\/get_splash_screen_info url reject-200
^https?+:\/\/3gimg\.qq\.com\/tencentMapTouch\/app\/activity\/ url reject-200
^https?+:\/\/3gimg\.qq\.com\/tencentMapTouch\/splash\/ url reject-200
^https?:\/\/.+?\.l\.qq\.com url reject
^https?:\/\/\w+\.gdt\.qq\.com url reject
^https?:\/\/y\.gtimg\.cn\/music\/.*?_Ad/\d+\.png url reject-img
^https?:\/\/splashqqlive\.gtimg\.com\/website\/\d{6} url reject-img
^https?:\/\/qzonestyle\.gtimg\.cn\/qzone\/biz\/gdt\/mob\/sdk\/ios\/v2\/ url reject-img
^https?:\/\/discuz\.gtimg\.cn\/cloud\/scripts\/discuz_tips\.js url reject-img
^https?:\/\/bla\.gtimg\.com\/qqlive\/\d{6}.+?\.png url reject-img
^https?:\/\/mmgr\.gtimg\.com\/gjsmall\/qiantu\/upload\/ url reject-img
^https?:\/\/mmgr\.gtimg\.com\/gjsmall\/qqpim\/public\/ios\/splash\/.+?\/\d{4}_\d{4} url reject-img
# > 爱奇艺
^https?:\/\/iface\.iqiyi\.com\/api\/getNewAdInfo url reject
^https?:\/\/intl\.iqiyi\.com\/ad_external\/ url reject
^https?:\/\/intl\.iqiyi\.com\/video\/advertise url reject
^https?:\/\/u\d\.iqiyipic\.com\/image\/[\w\/]+\/oad_ url reject
^https?+:\/\/act\.vip\.iqiyi\.com\/interact\/api\/show\.do url reject-200
^https?+:\/\/act\.vip\.iqiyi\.com\/interact\/api\/v2\/show url reject-200
^https?+:\/\/iface\.iqiyi\.com\/api\/getNewAdInfo url reject-200
^https?:\/\/iface2\.iqiyi\.com\/fusion\/3\.0\/fusion_switch url reject-img
^http:\/\/.+\.iqiyipic\.com\/image\/.+\/ad\/.+\.jpg url reject
^http:\/\/static-s\.iqiyi\.com\/common\/.+\/Small_video\/a2\/af\/.+\.png url reject
^http:\/\/msga/.cupid/.iqiyi/.com\/scp2\.gif url reject
https?:\/\/ssports\.iqiyi\.com/app\/ url reject
https?:\/\/ssports\.iqiyi\.com/json\/shop\/shopInfo  url reject
https?:\/\/.+\.iqiyi\.com\/videos\/other\/20$ url reject
https?:\/\/.+\.iqiyipic\.com\/image\/20*_100000 url reject
https?:\/\/static\.iqiyi\.com\/js\/common\/.+\.js url reject
https?:\/\/t7z\.cupid\.iqiyi\.com\/show url reject
# > 腾讯视频
^https://news.l.qq.com\/app\? url reject
^https?:\/\/btrace.qq.com url reject-200
^https?:\/\/vv\.video\.qq\.com\/getvmind\? url reject-200
^http:\/\/.+/\?tk=9901afb195dcf9a34db6088a4a221dba38b3d980e4db86009f8a08be4d4099ee323f6e7f03b881db21133b1bf2ae5bc5 url reject
^http:\/\/video\.dispatch\.tc\.qq\.com\/.+\.mp4 url reject
^http:\/\/.+\/vmind\.qqvideo\.tc\.qq\.com\/.+\.mp4 url reject
^http:\/\/wa\.gtimg\.com\/adxcdn\/.+\.jpg url reject
^https?:\/\/.+?\/omts.tc.qq.com\/ url reject
^https?:\/\/.+?\/variety.tc.qq.com\/ url reject
^https?:\/\/.+?\.tc\.qq\.com\/.+?_p20\d_ url reject
^https?+:\/\/(?:(?:25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(?:25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/.+?\.tc\.qq\.com\/.+?p201\.1\.mp4\? url reject-200
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/.+\.tc\.qq\.com\/.+p201\.1\.mp4\? url reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/[a-z.]+\.tc\.qq\.com\/[\w\W]+=v3004 url reject
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/[a-z.]+\.tc\.qq\.com\/[\w\W]+_p20\d url reject
^https?:\/\/[\s\S]*\/.+?\.tc\.qq\.com/.*?p201.1\.mp4 url reject-img
^https?:\/\/video\.dispatch\.tc\.qq\.com\/\w+\.p20\d\.1\.mp4 url reject
# > 京东
^https?:\/\/m15\.360buyimg\.com\/mobilecms\/jfs\/t1\/202220\/24\/21575\/134711\/625b821bE5d642d73\/77636692989bd2be\.jpg url reject
^https?:\/\/m\.360buyimg\.com\/mobilecms\/s1125x2436_jfs\/t1\/96405\/17\/28473\/168578\/625cd144E7997a990\/8233ce8a10c4e463\.jpg url reject
^https?:\/\/m\.360buyimg\.com\/mobilecms\/s1125x2436_jfs\/t1\/182114\/23\/23904\/121433\/62593c9cEd77c4519\/2e3f4c518b771094\.jpg url reject
^https?:\/\/m\.360buyimg\.com\/mobilecms\/s1125x2436_jfs\/t1\/202971\/34\/26906\/282671\/6319c862E1818d3fa\/0597464cf6bc8e2f\.jpg url reject
^https?:\/\/m\.360buyimg\.com\/mobilecms\/s1125x2436_jfs\/t1\/143222\/27\/29233\/141967\/631b1f8cE3a112e54\/d3fe0b2f9f0a9f30\.jpg url reject
^https?:\/\/m\.360buyimg\.com\/mobilecms\/s1125x2436_jfs url reject
^https?:\/\/m15\.360buyimg\.com\/mobilecms\/jfs\/t1\/197429\/22/22400\/119193\/62562ef0Eff59b4d4 url reject
^https?:\/\/api\.m\.jd\.com\/client\.action\?functionId=start$ url reject-array
^https?://union.click.jd.com/jda? url request-header ^(.+?\s).+?(\s[\s\S]+?Host:).+?(\r\n) request-header $1/jda?adblock=$2union.click.jd.com$3
^https?://union.click.jd.com/sem.php? url request-header ^(.+?\s).+?(\s[\s\S]+?Host:).+?(\r\n) request-header $1/sem.php?adblock=$2union.click.jd.com$3
^https?:\/\/ms\.jr\.jd\.com\/gw\/generic\/(aladdin\/na\/m\/getLoadingPicture|aladdin\/na\/m\/getLoadingPicture) url reject
^https?:\/\/ms\.jr\.jd\.com\/gw\/generic\/aladdin\/na\/m\/getLoadingPicture url reject
^https?:\/\/ms\.jr\.jd\.com\/gw\/generic\/base\/(new)?na\/m\/adInfo url reject
^https?:\/\/ms\.jr\.jd\.com\/gw\/generic\/base\/na\/m\/adInfo url reject
^https?:\/\/bdsp-x\.jd\.com\/adx\/ url reject
^https?:\/\/api\.m\.jd.com\/client\.action\?functionId=(start|queryMaterialAdverts) url reject
^https?:\/\/(bdsp-x|dsp-x)\.jd\.com\/adx\/ url reject
^https?:\/\/api\.m\.jd\.com\/client\.action\?functionId=start url script-response-body https://raw.githubusercontent.com/28413761/QX/main/JS/startup.js
^https?+:\/\/api\.m\.jd\.com\/client\.action\?functionId=start$ url reject-200
^https?:\/\/img\d+\.360buyimg\.com\/jddjadvertise\/ url reject
^https?:\/\/m15\.360buyimg\.com\/mobilecms\/jfs\/t1\/197429\/22\/22400\/119193\/62562ef0Eff59b4d4 url reject
^https?:\/\/m15\.360buyimg\.com\/mobilecms\/jfs\/t1\/220846\/5\/16214\/41327 url reject
^https?:\/\/m15\.360buyimg\.com\/mobilecms\/jfs\/t1\/202818 url reject
^https?:\/\/storage\.360buyimg\.com\/kepler-app url reject-img
^https?:\/\/m\.360buyimg\.com\/mobilecms\/s640x1136_jfs\/ url reject-img
# > 淘宝
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.taobao\.idle\.home\.welcome\/ url reject-200
^https?+:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.tmall\.wireless url reject-200
^https?+:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alibaba\.advertisementservice\.getadv url reject-200
^https?+:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alimama\.etao\.config\.query\/ url response-body "ems_etao_advertise" response-body ""
^https?+:\/\/acs\.m\.taobao\.com\/gw\/mtop\.film\.mtopadvertiseapi\.queryadvertise\/ url reject-200
^https?+:\/\/acs\.m\.taobao\.com\/gw\/mtop\.o2o\.ad\.gateway\.get\/ url reject-200
^https?+:\/\/acs\.m\.taobao\.com\/gw\/mtop\.trip\.activity\.querytmsresources\/ url reject-200
# > 什么值得买去广告
# > 什么值得买好价详情页
^https?:\/\/haojia\.m\.smzdm\.com\/detail_modul\/other_modul url reject
# > 什么值得买好价详情页红包小助手
^https?:\/\/haojia\.m\.smzdm\.com\/detail_modul\/user_related_modul url reject
# > 什么值得买Wiki(618晒物活动推广，将来可能不是广告)
^https?:\/\/haojia\.m\.smzdm\.com\/detail_modul\/wiki_related_modul url reject
# > 什么值得买开屏广告
^https?:\/\/app-api\.smzdm\.com\/util\/loading url script-response-body https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/smzdm/smzdm_remove_ads.js
# > 什么值得买首页广告
^https?:\/\/homepage-api\.smzdm\.com\/v3\/home url script-response-body https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/smzdm/smzdm_remove_ads.js
# > 什么值得买好价广告
^https?:\/\/haojia-api\.smzdm\.com\/home\/list url script-response-body https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/smzdm/smzdm_remove_ads.js
# > 什么值得买好价详情页广告
^https?:\/\/haojia\.m\.smzdm\.com\/detail_modul\/article_releated_modul url script-response-body https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/smzdm/smzdm_remove_ads.js
# > 什么值得买百科广告
^https?:\/\/baike-api\.smzdm\.com\/home_v3\/list url script-response-body https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/smzdm/smzdm_remove_ads.js
# > 什么值得买搜索结果广告
^https?:\/\/s-api\.smzdm\.com\/sou\/list_v10 url script-response-body https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/smzdm/smzdm_remove_ads.js
# > 什么值得买搜索标签广告
^https?:\/\/s-api\.smzdm\.com\/sou\/filter\/tags\/hot_tags url script-response-body https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/smzdm/smzdm_remove_ads.js
# > 什么值得买值会员权益中心banner广告
^https?:\/\/zhiyou\.m\.smzdm\.com\/user\/vip\/ajax_get_banner url script-response-body https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/smzdm/smzdm_remove_ads.js
# > 美团
^https?+:\/\/img\.meituan\.net\/(?>adunion|display|midas)\/.+?\.(gif|jpg|jpg\.webp)$ url reject-200
^https?+:\/\/p\d\.meituan\.net\/wmbanner\/[A-Za-z0-9]+?\.jpg url reject-200
^https?+:\/\/p\d\.meituan\.net\/movie\/[A-Za-z0-9]+?\.jpg\?may_covertWebp url reject-200
^https?:\/\/s3plus\.meituan\.net\/.+?\/linglong\/ url reject
^https?:\/\/s3plus\.meituan\.net\/v1\/mss_a002 url reject-img
^https?:\/\/www\.meituan\.com\/api\/v\d\/appstatus\? url reject
^https?:\/\/wmapi\.meituan\.com\/api\/v\d+\/loadInfo\? url reject
^https?:\/\/wmapi\.meituan\.com\/api\/v\d\/startpicture url reject
^https?:\/\/flowplus\.meituan\.net\/v\d\/\w+\/linglong\/\d+\.(gif|jpg|mp4) url reject
^https?:\/\/(s3plus|flowplus)\.meituan\.net\/v\d\/\w+\/linglong\/\w+\.(gif|jpg|mp4) url reject
^https?:\/\/apimobile\.meituan\.com\/appupdate\/mach\/checkUpdate? url reject
^https?:\/\/img\.meituan\.net\/(adunion|display|midas)\/\w+\.(gif|jpg|jpg\.webp)$ url reject
^https?:\/\/p\d.meituan.net\/movie\/.*?\?may_covertWebp url reject-img
^https?:\/\/p\d{1}\.meituan\.net\/(adunion|display|linglong|mmc|wmbanner)\/ url reject
