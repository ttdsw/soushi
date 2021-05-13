{
	"targetVersion":5,
	"version4Link":"",
	"name":"天幽绝清君诺",
	"author":"天幽绝清君诺",
	"contact":"自用",
	"message":"勿传播，不更新",
	"searchConfig":[
		{
			"configName":"九四四",
			"configType":"WebPage",
			"itemNameRegex":"<li><a title=\"(.*?)\" href=\".*\" target=\"_self\">.*</a></li>",
			"itemUrlRegex":"<li><a title=\".*\" href=\"(.*?)\" target=\"_self\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\"> <",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\"> <",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchTypeRegex":"类型：</span>(.*?)<span class=\"split-line\"></span><span class=\"text-muted\">地区：</span>",
			"searchUrl":"http://www.944tv.com/search.php?searchword={SearchWord}&amp",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\"> <",
			"usable":true
		},
		{
			"configName":"Auete影视",
			"configType":"WebPage",
			"itemNameRegex":"<a class=\"btn btn-orange\" title=\"(.*)\" href=\".* target=\"_self\"",
			"itemUrlRegex":"<a class=\"btn btn-orange\" title=\".*\" href=\"(.*)\" target=\"_self\"",
			"searchNameRegex":"<a href=\".*\"><span class=\"text-danger\">(.*)</span></a>",
			"searchPictureRegex":"",
			"searchStateRegex":"<span class=\"date text-grey\">(.*)</span>",
			"searchUrl":"https://auete.com/search.php?searchword={SearchWord}",
			"searchUrlRegex":"<a href=\"(.*)\"><span class=\"text-danger\">.*</span></a>",
			"usable":true
		},
		{
			"configName":"干饭",
			"configType":"WebPage",
			"itemNameRegex":"><a href=\".*play/\\d*-1-\\d*\\.html\">(.*?)</a></li>",
			"itemSkipRegex":"<a href=\"(.*?)\">立即播放</a>",
			"itemUrlRegex":"><a href=\"(.*play/\\d*-1-\\d*\\.html)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchTypeRegex":"",
			"searchUrl":"https://www.ganfantv.com/search/-------------.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"searchYearRegex":"",
			"sniffExcludeRegex":".*la/.*",
			"usable":true
		},
		{
			"configName":"骚火",
			"configType":"WebPage",
			"itemNameRegex":"<a title=\".*?\" href=\"/play/\\d*-0-\\d*\\.html\" target=\"_self\">(.*?)</a>",
			"itemUrl":"{SearchUrlOrId}&Header={\"User-Agent\":\"Mozilla/5.0 (Linux; Android 10; M2007J17C Build/QKQ1.200628.002; wv)\"}",
			"itemUrlRegex":"<a title=\".*?\" href=\"(/play/\\d*-0-\\d*\\.html)\" target=\"_self\">.*?</a>",
			"searchNameRegex":"<a href=\".*\" title=\"(.*?)\"><img class=\"lazyload\" data-original=\".*\"></a>",
			"searchPictureRegex":"<a href=\".*\" title=\".*\"><img class=\"lazyload\" data-original=\"(.*?)\"></a>",
			"searchStateRegex":"<div class=\"v_note\">\n     (.*?)\n    </div>",
			"searchUrl":"http://saohuotv.com/search.php?searchword={SearchWord}&Header={\"User-Agent\":\"Mozilla/5.0 (Linux; Android 10; M2007J17C Build/QKQ1.200628.002; wv)\"}",
			"searchUrlRegex":"<a href=\"(.*?)\" title=\".*\"><img class=\"lazyload\" data-original=\".*\"></a>",
			"usable":true
		},
		{
			"configName":"夜夜迷",
			"configType":"WebPage",
			"itemNameRegex":"<li><a href=\".*/vod/play/id.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li><a href=\"(.*/vod/play/id.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchTypeRegex":"类型：</span>(.*?)<span class=\"split-line\"></span><span class=\"text-muted\">地区",
			"searchUrl":"http://yeyemi.com/index.php/vod/search.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"searchYearRegex":"年份：</span>(.*?)</span></p>",
			"sniffExcludeRegex":".*la/.*",
			"usable":true
		},
		{
			"configName":"快看",
			"configType":"WebPage2",
			"itemNameRegex":"<li><a href=\".*.html\" target=\"_self\" title=\".*\" alt=\".*\">(.*?)</a></li>",
			"itemUrlRegex":"<li><a href=\"(.*.html)\" target=\"_self\" title=\".*\" alt=\".*\">.*</a></li>",
			"searchNameRegex":"<li><a href=\".*\" title=\"(.*?)\" target=",
			"searchPictureRegex":"data-original=\"(.*?)\"",
			"searchStateRegex":"<p> 状态：<label class=\"status\"></label><label class=\"title\">(.*?)</label></p>",
			"searchTypeRegex":"分类：<a href=\".*\" title=\"(.*?)\" target=\"_self\" style=",
			"searchUrl":"http://m.kuaikan33.com/search/{SearchWord}-1.html",
			"searchUrlRegex":"<li><a href=\"(.*?)\" title=\".*\" target=",
			"searchYearRegex":"<p> 时间：(.*?)</p>",
			"usable":true
		},
		{
			"configName":"555电影",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a href=\".*/id/.*/sid/1/nid/\\d*\\.html.*\">(.*)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a href=\"(.*/id/.*/sid/1/nid/\\d*\\.html).*\">.*</a></li>",
			"searchNameRegex":"<a class=\"hl-item-thumb hl-lazy\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"<a class=\"hl-item-thumb hl-lazy\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"hl-lc-1 remarks\">(.*)</span>",
			"searchTypeRegex":"<p class=\"hl-item-sub hl-lc-1\"> <em>(.*?)</em>",
			"searchUrl":"https://www.555dy4.com/index.php/vod/search.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"<a class=\"hl-item-thumb hl-lazy\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"searchYearRegex":"&nbsp;&middot;&nbsp;(.*?)&nbsp;&middot;&nbsp;",
			"usable":true
		},
		{
			"configName":"饭团",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*-1-.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*-1-.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchTypeRegex":"分类：</span>(.*?)<span class=\"split-line\"></span><span class=\"text-muted hidden-xs\">地区",
			"searchUrl":"https://fantuan.tv/vodsearch.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"searchYearRegex":"年份：</span>(.*?)</p>",
			"usable":true
		},
		{
			"configName":"嘀嗒电影",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*/sid/1/nid/.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*/sid/1/nid/.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchTypeRegex":"分类：</span>(.*?)<span class=\"split-line\"></span>",
			"searchUrl":"https://www.didady.cn/index.php/vod/search.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"searchYearRegex":"年份：</span>(.*?)</p>",
			"usable":true
		},
		{
			"configName":"剧好看",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*vodplay/.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*vodplay/.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"tag\" style=\"background-color.*\">(.*?)</span></span><span class=\"pic-text text-right\">.*</span></a>",
			"searchTypeRegex":"分类：</span>(.*?)<span class=\"split-line\"></span><span class=\"text-muted hidden-xs\">地区",
			"searchUrl":"https://www.juhaokan.cc/vodsearch/-------------.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"searchYearRegex":"<span class=\"tag\" style=\"background-color.*\">.*</span></span><span class=\"pic-text text-right\">(.*?)</span></a>",
			"usable":true
		},
		{
			"configName":"去看备用",
			"configType":"WebPage",
			"itemNameRegex":"<li><a target=\"_blank\" href=\".*1-.*\">(.*?)<",
			"itemUrlRegex":"<li><a target=\"_blank\" href=\"(.*1-.*)\">.*<",
			"searchNameRegex":"loading\" href=\".*\" title=\"(.*?)\" data-original=\".*\" style=",
			"searchPictureRegex":"loading\" href=\".*\" title=\".*\" data-original=\"(.*?)\" style=",
			"searchStateRegex":"状态：</span>(.*?)</li>",
			"searchTypeRegex":"类型：</span><a href=\".*\" target=\"_blank\">(.*?)</a>",
			"searchUrl":"https://wmsp.cc/search/{SearchWord}-1.html",
			"searchUrlRegex":"loading\" href=\"(.*?)\" title=\".*\" data-original=\".*\" style=",
			"searchYearRegex":"更新时间：</span>(.*?)</li>",
			"sniffExcludeRegex":"https://ia.51.la.*",
			"usable":true
		},
		{
			"configName":"AGE动漫",
			"configType":"WebPage",
			"itemNameRegex":"<a href=\".*play/.*\" target=\"_self\" title=\"(.*?)\">.*</a>",
			"itemUrlRegex":"<a href=\"(.*play/.*)\" target=\"_self\" title=\".*\">.*</a>",
			"searchNameRegex":"<a href=\".*\" class=\"cell_imform_name\">(.*?)</a>",
			"searchPictureRegex":"width=\"150px\" height=\"208px\" src=\"(.*?)\" alt=\".*\">",
			"searchStateRegex":"<span class=\"newname\">(.*?)</span></a>",
			"searchUrl":"https://www.agefans.net/search?query={SearchWord}&page=1",
			"searchUrlRegex":"<a href=\"(.*?)\" class=\"cell_imform_name\">.*</a>",
			"usable":true
		},
		{
			"configName":"BD电影首发",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\"col-lg-10 col-md-8 col-sm-6 col-xs-4\"><a class=\"btn btn-default\" href=\".*-1-.*\">(.*)</a></li>",
			"itemUrlRegex":"<li class=\"col-lg-10 col-md-8 col-sm-6 col-xs-4\"><a class=\"btn btn-default\" href=\"(.*-1-.*)\">.*</a></li>",
			"searchNameRegex":"<h4 class=\"title\"><a class=\"searchkey\" href=\".*\">(.*)</a></h4>",
			"searchUrl":"https://www.bddysf.com/vodsearch.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"<h4 class=\"title\"><a class=\"searchkey\" href=\"(.*)\">.*</a></h4>",
			"sniffExcludeRegex":"https://ia.51.la.*",
			"usable":true
		},
		{
			"configName":"麻花",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*play/.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*play/.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchUrl":"https://www.mahua110.com/search/-------------.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"sniffExcludeRegex":".*static/player/.*",
			"usable":true
		},
		{
			"configName":"迪迪影视",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*/vod/play/.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*/vod/play/.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\"><span class=\"play hidden-xs\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\"><span class=\"play hidden-xs\"></span>",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span></a>",
			"searchTypeRegex":"分类：</span>(.*?)<span class=\"split-line\"></span><span class=\"text-muted hidden-xs\">地区：</span>",
			"searchUrl":"https://tv758.com/index.php/vod/search.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\"><span class=\"play hidden-xs\">",
			"usable":true
		},
		{
			"configName":"LIBVIO电影",
			"configType":"WebPage",
			"itemNameRegex":"<a href=\".*play/\\d*-1-\\d*\\.html\">(.*?)</a>",
			"itemUrlRegex":"<a href=\"(.*play/\\d*-1-\\d*\\.html)\">.*</a>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchUrl":"https://www.libvio.com/vodsearch/wd/{SearchWord}.html",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"usable":true
		},
		{
			"configName":"南柯W",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*-1-.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*-1-.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchUrl":"https://nkdyw.cn/nk/{SearchWord}----------1---/",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"sniffExcludeRegex":".*pstatp.*",
			"sniffTargetExtensions":"m3u8",
			"sniffTargetRegex":"",
			"usable":true
		},
		{
			"configName":"乐看W",
			"configType":"WebPage2",
			"itemNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*-1-.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*-1-.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchUrl":"https://lekkan.com/vodsearch/-------------/?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"sniffExcludeRegex":".*la/.*",
			"sniffTargetExtensions":"",
			"sniffTargetRegex":"http://cache.lekan4k.com.*",
			"usable":true
		},
		{
			"configName":"片库W",
			"configType":"WebPage",
			"itemNameRegex":"<li><a href=\".*-1-\\d*\\.html.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li><a href=\"(.*-1-\\d*\\.html).*\">.*</a></li>",
			"searchNameRegex":"<p>名称：<strong><a href=\".*\">(.*)\\(.*\\)</a></strong><span class=\"ss1\">\\s*\\[.*\\]\\[.*\\]</span></p>",
			"searchPictureRegex":"<a href=\".*\"><img src=\"(.*)\" referrerpolicy=\"no-referrer\"></a>",
			"searchStateRegex":"<p>名称：<strong><a href=\".*\">.*\\(.*\\)</a></strong><span class=\"ss1\">\\s*\\[.*\\]\\[(.*)\\]</span></p>",
			"searchTypeRegex":"<p>名称：<strong><a href=\".*\">.*\\(.*\\)</a></strong><span class=\"ss1\">\\s*\\[(.*)\\]\\[.*\\]</span></p>",
			"searchUrl":"http://pianku.cf/Moviesearch/-------------.html?wd={SearchWord}",
			"searchUrlRegex":"<p>名称：<strong><a href=\"(.*)\">.*\\(.*\\)</a></strong><span class=\"ss1\">\\s*\\[.*\\]\\[.*\\]</span></p>",
			"searchYearRegex":"<p>名称：<strong><a href=\".*\">.*\\((.*)\\)</a></strong><span class=\"ss1\">\\s*\\[.*\\]\\[.*\\]</span></p>",
			"sniffExcludeRegex":".*ts3.xar.*",
			"usable":true
		},
		{
			"configName":"看一看",
			"configType":"WebPage",
			"itemNameRegex":"<li><a title=\".*\" href=\".*-src-1-num-.*\" target=\"_self\">(.*?)</a></li>",
			"itemUrlRegex":"<li><a title=\".*\" href=\"(.*-src-1-num-.*)\" target=\"_self\">.*</a></li>",
			"searchNameRegex":"<a class=\"link-hover\" href=\".*\" title=\"(.*?)\"><img class=\"lazy\" data-original=\".*\" src=\".*\" alt=",
			"searchPictureRegex":"<a class=\"link-hover\" href=\".*\" title=\".*\"><img class=\"lazy\" data-original=\"(.*?)\" src=\".*\" alt=",
			"searchStateRegex":"</p></span><p class=\"other\"><i>(.*?)</i></p></a></li>",
			"searchUrl":"https://v.kyikan.com/index.php?m=vod-search-pg-1-wd-{SearchWord}.html",
			"searchUrlRegex":"<a class=\"link-hover\" href=\"(.*?)\" title=\".*\"><img class=\"lazy\" data-original=\".*\" src=\".*\" alt=",
			"sniffExcludeRegex":".*kyikan.*",
			"sniffTargetExtensions":"",
			"sniffTargetRegex":"",
			"usable":true
		},
		{
			"configName":"ADC文",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*info fed-part-eone\" href=\".*play/\\d*-\\d*-\\d*\\.html\">(.*?)</a></li>",
			"itemRangeRegex":"<ul class=\"fed-part-rows\">(.*?)</ul>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*info fed-part-eone\" href=\"(.*play/\\d*-\\d*-\\d*\\.html)\">.*</a></li>",
			"searchNameRegex":"<h1 class=\".*\"><a href=\".*\"><span class=\".*\">(.*?)</span></a></h1>",
			"searchPictureRegex":"data-original=\"(.*?)\"><span class=",
			"searchStateRegex":"<span class=\"fed-list-remarks fed-font-xii fed-text-white fed-text-center\">(.*?)</span>",
			"searchUrl":"https://www.adcmove.com/search/-------------.html?wd={SearchWord}",
			"searchUrlRegex":"<h1 class=\".*\"><a href=\"(.*?)\"><span class=\".*\">.*</span></a></h1>",
			"sniffExcludeRegex":".*adcmove.*",
			"sniffTargetExtensions":"m3u8",
			"sniffTargetRegex":"",
			"usable":true
		},
		{
			"configName":"枫林",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*play/.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*play/.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-center\">(.*?)</span></a>",
			"searchUrl":"https://imaple.co/search.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"usable":true
		},
		{
			"configName":"九八五",
			"configType":"WebPage",
			"itemNameRegex":"<li><a href=\".*play/.*\" target=\"_blank\" title=\".*\">(.*?)</a></li>",
			"itemUrlRegex":"<li><a href=\"(.*play/.*)\" target=\"_blank\" title=\".*\">.*</a></li>",
			"searchNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*\" title=\"(.*?)\" target=\"_blank\"><img class=\"lazy\" src=\".*\" data-original=\".*\" alt=",
			"searchPictureRegex":"<li class=\".*\"><a class=\".*\" href=\".*\" title=\".*\" target=\"_blank\"><img class=\"lazy\" src=\".*\" data-original=\"(.*?)\" alt=",
			"searchStateRegex":"<p class=\"other\"><i>(.*?)</i></p></a></li>",
			"searchUrl":"https://m.985ys.com/search/{SearchWord}----------1---.html",
			"searchUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*?)\" title=\".*\" target=\"_blank\"><img class=\"lazy\" src=\".*\" data-original=\".*\" alt=",
			"usable":true
		},
		{
			"configName":"万影网",
			"configType":"WebPage",
			"itemNameRegex":"<a href=\".*/play-1-.*\" target=\"_self\" title=\".*\">(.*?)</a></li>",
			"itemUrlRegex":"<a href=\"(.*/play-1-.*)\" target=\"_self\" title=\".*\">.*</a></li>",
			"searchNameRegex":"<h2><a href=\".*\" title=\".*\" target=\"_self\">(.*?)</a></h2>",
			"searchPictureRegex":"src=\"(.*?)\" alt=\".*\">",
			"searchStateRegex":"<p>状态：(.*?)</p>",
			"searchUrl":"http://m.wydy8.com/vod-search-pg-1-wd-{SearchWord}.html",
			"searchUrlRegex":"<h2><a href=\"(.*?)\" title=\".*\" target=\"_self\">.*</a></h2>",
			"usable":true
		},
		{
			"configName":"二哈",
			"configType":"WebPage",
			"itemNameRegex":"<li><a href=\".*play/.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li><a href=\"(.*play/.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchUrl":"https://www.2hys.com/vodsearch/page/1/wd/{SearchWord}.html",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"usable":true
		},
		{
			"configName":"播王",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*-9-.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*-9-.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-center\">(.*?)</span>",
			"searchTypeRegex":"",
			"searchUrl":"https://bowang.tv/search/wd/{SearchWord}.html",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"searchYearRegex":"年份：</span>(.*?)</p>",
			"usable":true
		},
		{
			"configName":"樱花",
			"configType":"WebPage2",
			"itemNameRegex":"><a title=\".*\" href=\".*player/.*\" target=\"_blank\">(.*?)</a></li>",
			"itemUrlRegex":"><a title=\".*\" href=\"(.*player/.*)\" target=\"_blank\">.*</a></li>",
			"searchNameRegex":"<a href=\".*\" class=\"\"> <img class=\"lazy\" data-original=\".*\" alt=\"(.*?)\" src=",
			"searchPictureRegex":"<a href=\".*\" class=\"\"> <img class=\"lazy\" data-original=\"(.*?)\" alt=\".*\" src=",
			"searchStateRegex":"",
			"searchTypeRegex":"",
			"searchUrl":"POST:http://m.imomoe.ai/search.asp?searchword={SearchWordGBK}",
			"searchUrlRegex":"<a href=\"(.*?)\" class=\"\"> <img class=\"lazy\" data-original=\".*\" alt=\".*\" src=",
			"searchYearRegex":"",
			"usable":true
		},
		{
			"configName":"妮可",
			"configType":"WebPage2",
			"itemNameRegex":"<a href=\".*/\\d*-1-\\d*\\.html\" class=\".*\">(.*?)</a></li>",
			"itemUrlRegex":"<a (href=\".*/\\d*-1-\\d*\\.html\") class=\".*\">(.*)</a></li>",
			"searchNameRegex":" <a href=\".*\"> <img class=\"img-responsive img-thumbnail ff-img\" data-original=\".*\" alt=\"(.*?)\" src=",
			"searchPictureRegex":"data-original=\"(.*?)\"",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*)</span></a>",
			"searchTypeRegex":"",
			"searchUrl":"http://www.nicotv.biz/video/search/{SearchWord}.html",
			"searchUrlRegex":"<a (href=\".*\")> <img class=\"img-responsive img-thumbnail ff-img\" data-original=\".*\" alt=\".*\" src=",
			"searchYearRegex":"<span class=\"continu\">(.*)</span>",
			"usable":true
		},
		{
			"configName":"迪迪",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*/vod/play/.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*/vod/play/.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\"><span class=\"play hidden-xs\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\"><span class=\"play hidden-xs\"></span>",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span></a>",
			"searchTypeRegex":"分类：</span>(.*?)<span class=\"split-line\"></span><span class=\"text-muted hidden-xs\">地区：</span>",
			"searchUrl":"https://tv547.com/index.php/vod/search.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\"><span class=\"play hidden-xs\">",
			"usable":true
		},
		{
			"configName":"爱迪",
			"configType":"WebPage",
			"itemNameRegex":"<li><a href=\".*-1-.*\" target=\"_blank\">(.*?)</a></li>",
			"itemUrlRegex":"<li><a href=\"(.*-1-.*)\" target=\"_blank\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic_text text_right\">(.*?)</span>",
			"searchUrl":"https://aidi.tv/vsearch/-------------.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"sniffTargetExtensions":"m3u8",
			"sniffTargetRegex":"",
			"usable":true
		},
		{
			"configName":"八八看",
			"configType":"WebPage",
			"itemNameRegex":"<a href=\".*-src-1-num-.*\" title=\".*\">(.*?)</a></li>",
			"itemUrlRegex":"<a href=\"(.*-src-1-num-.*)\" title=\".*\">.*</a></li>",
			"searchNameRegex":"<a href=\".*\" title=\"(.*?)\" target=\"_blank\"><img class=\"lazy\" data-src=\".*\" src=",
			"searchPictureRegex":"<a href=\".*\" title=\".*\" target=\"_blank\"><img class=\"lazy\" data-src=\"(.*?)\" src=",
			"searchStateRegex":"<em class=\"emScore\">(.*?)</em>",
			"searchUrl":"https://m.88kan.com/vod-search-pg-1-wd-{SearchWord}.html",
			"searchUrlRegex":"<a href=\"(.*?)\" title=\".*\" target=\"_blank\"><img class=\"lazy\" data-src=\".*\" src=",
			"sniffExcludeRegex":".*m.88kan.*",
			"sniffTargetExtensions":"",
			"sniffTargetRegex":"",
			"usable":true
		},
		{
			"configName":"蓝影",
			"configType":"WebPage",
			"itemNameRegex":"<a class=\".*\" href=\"/vodplay/.*.html\">(.*)</a></li>",
			"itemUrlRegex":"<a class=\".*\" href=\"(/vodplay/.*.html)\">.*</a></li>",
			"searchNameRegex":"<h4 class=\"title\"><a class=\"searchkey\" href=\"/voddetail/.*.html\">(.*)</a></h4>",
			"searchPictureRegex":"data-original=\"(.*)\"><span class=",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*)</span></a>",
			"searchUrl":"https://www.888kktv.com/vod/search.html?wd={SearchWord}",
			"searchUrlRegex":"<h4 class=\"title\"><a class=\"searchkey\" href=\"(/voddetail/.*.html)\">.*</a></h4>",
			"usable":true
		},
		{
			"configName":"AGE",
			"configType":"WebPage",
			"itemNameRegex":"<a href=\".*play/.*\" target=\"_self\" title=\"(.*?)\">.*</a>",
			"itemUrlRegex":"<a href=\"(.*play/.*)\" target=\"_self\" title=\".*\">.*</a>",
			"searchNameRegex":"<a href=\".*\" class=\"cell_imform_name\">(.*?)</a>",
			"searchPictureRegex":"width=\"150px\" height=\"208px\" src=\"(.*?)\" alt=\".*\">",
			"searchStateRegex":"<span class=\"newname\">(.*?)</span></a>",
			"searchUrl":"https://www.agefans.net/search?query={SearchWord}&page=1",
			"searchUrlRegex":"<a href=\"(.*?)\" class=\"cell_imform_name\">.*</a>",
			"usable":true
		},
		{
			"configName":"虎看",
			"configType":"WebPage",
			"itemNameRegex":"<a href=\".*vodplayhtml/\\d*-1-\\d*\\.html\">(.*?)</a></li>",
			"itemUrlRegex":"<a href=\"(.*vodplayhtml/\\d*-1-\\d*\\.html)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchTypeRegex":"类型：</span>(.*?)<span class=\"split-line\"></span><span class=\"text-muted\">地区",
			"searchUrl":"https://www.hukanyy.com/index.php?m=vod-search-pg-1-wd-{SearchWord}.html",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"searchYearRegex":"年份：</span>(.*?)</span></p>",
			"usable":true
		},
		{
			"configName":"小兵",
			"configType":"WebPage",
			"itemNameRegex":"<li><a href=\".*-2-.*\" title=\"(.*?)\">.*<p>.*</p></a></li>",
			"itemUrlRegex":"<li><a href=\"(.*-2-.*)\" title=\".*\">.*<p>.*</p></a></li>",
			"searchNameRegex":"<h3><a href=\".*\" style=\".*558bd9\" title=\".*\">(.*?)</a>",
			"searchPictureRegex":"<a href=\".*\" title=\".*\"><img src=\"(.*?)\" alt=",
			"searchStateRegex":"",
			"searchUrl":"https://www.xbplay.cc/query/{SearchWord}",
			"searchUrlRegex":"<h3><a href=\"(.*?)\" style=\".*558bd9\" title=\".*\">.*</a>",
			"usable":true
		},
		{
			"configName":"我的",
			"configType":"WebPage",
			"itemNameRegex":"<li><a href=\".*/sid/1/nid/.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li><a href=\"(.*/sid/1/nid/.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic_text text_right\">(.*?)</span></a>",
			"searchTypeRegex":"<span class=\"info_right\">(.*?)</span>.*</a></h4>",
			"searchUrl":"http://www.wsba.com.cn/index.php/vod/search.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"searchYearRegex":"",
			"sniffExcludeRegex":".*.la/.*",
			"usable":true
		},
		{
			"configName":"捏它",
			"configType":"WebPage",
			"itemNameRegex":"<li><a title=\"(.*)\" href=\".*\">",
			"itemUrlRegex":"<li><a title=\".*\" href=\"(.*)\">",
			"searchNameRegex":"<a title=\"(.*)\" href=\"/voddetail/.*.html\" target=\"_blank\"",
			"searchPictureRegex":"data-echo=\"(.*)\" alt=",
			"searchStateRegex":"<span class=\"so-imgTag_rb\">(.*)</span>",
			"searchUrl":"http://www.nieta.co/vodsearch.html?wd={SearchWord}",
			"searchUrlRegex":"<a title=\".*\" href=\"(/voddetail/.*.html)\" target=\"_blank\"",
			"usable":true
		},
		{
			"configName":"A蓝",
			"configType":"WebPage",
			"itemNameRegex":"<a class=\"btn btn-orange\" title=\"(.*)\" href=\".* target=\"_self\"",
			"itemUrlRegex":"<a class=\"btn btn-orange\" title=\".*\" href=\"(.*)\" target=\"_self\"",
			"searchNameRegex":"<a href=\".*\"><span class=\"text-danger\">(.*)</span></a>",
			"searchPictureRegex":"",
			"searchStateRegex":"<span class=\"date text-grey\">(.*)</span>",
			"searchUrl":"https://auete.com/search.php?searchword={SearchWord}",
			"searchUrlRegex":"<a href=\"(.*)\"><span class=\"text-danger\">.*</span></a>",
			"usable":true
		},
		{
			"configName":"哈哩",
			"configType":"WebPage",
			"itemNameRegex":"<li><a href=\"/play/.*.html\">(.*)</a></li>",
			"itemUrlRegex":"<li><a href=\"(/play/.*.html)\">.*</a></li>",
			"searchNameRegex":"<a href=\".*\" title=\"(.*)\"><h1 class=\".*\">",
			"searchPictureRegex":"data-echo=\"(.*)\"></div>",
			"searchStateRegex":"<li class=\"ellipsis-1\">状态：(.*)</li>",
			"searchUrl":"https://m.halitv.com/search/?c=so&module=video&wd={SearchWord}",
			"searchUrlRegex":"<a href=\"(.*)\" title=\".*\"><h1 class=\".*\">",
			"usable":true
		},
		{
			"configName":"视觉",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*vodplay/.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*vodplay/.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchTypeRegex":"分类：</span>(.*?)<span class=\"split-line\"></span><span class=\"text-muted hidden-xs\">地区",
			"searchUrl":"https://www.xinshipai.vip/vodsearch/-------------.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"searchYearRegex":"年份：</span>(.*?)</p>",
			"usable":true,
			"waitTime":500
		},
		{
			"configName":"电影先生",
			"configType":"WebPage",
			"itemNameRegex":"<a href=\".*paly-.*\" title=\".*\"><span>(.*?)</span></a>",
			"itemUrlRegex":"<a href=\"(.*paly-.*)\" title=\".*\"><span>.*</span></a>",
			"searchNameRegex":"<a class=\"video-serial\" href=\".*\" title=\"(.*?)\">.*</a>",
			"searchPictureRegex":"<img class=\"lazyload\" data-src=\"(.*?)\" src=",
			"searchStateRegex":"<a class=\"video-serial\" href=\".*\" title=\".*\">(.*?)</a>",
			"searchTypeRegex":"<a href=\".*\" title=\"(.*?)\" class=\"tag-link\">",
			"searchUrl":"http://dianying.in/search-{SearchWord}-------------/",
			"searchUrlRegex":"<a class=\"video-serial\" href=\"(.*?)\" title=\".*\">.*</a>",
			"searchYearRegex":"<a href=\".*\" title=\".*\" class=\"tag-link\">(.*?)</a>",
			"usable":true
		},
		{
			"configName":"微博兔",
			"configType":"WebPage",
			"itemNameRegex":"<a href=\".*-src-1-num-.*\" target=\"_self\" title=\".*\" alt=\".*\">(.*?)</a></li>",
			"itemUrlRegex":"<a href=\"(.*-src-1-num-.*)\" target=\"_self\" title=\".*\" alt=\".*\">.*</a></li>",
			"searchNameRegex":"<span class=\"sTit\"><a href=\".*\" target=\"_self\">(.*?)</a></span>",
			"searchPictureRegex":"<img data-src=\"(.*?)\" src=\".*\" onerror=",
			"searchStateRegex":"<span class=\"sDes\">(.*?)</span>",
			"searchUrl":"https://m.weibotu.cc/vod-search-pg-1-wd-{SearchWord}.html",
			"searchUrlRegex":"<span class=\"sTit\"><a href=\"(.*?)\" target=\"_self\">.*</a></span>",
			"usable":true
		},
		{
			"configName":"美剧虫",
			"configType":"WebPage",
			"itemNameRegex":"<a href=\".*index.php/vodplay/.*\">(.*?)</a></li>",
			"itemSkipRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\"><span class=\"play hidden_xs\"></span>",
			"itemUrlRegex":"<a href=\"(.*index.php/vodplay/.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic_text text_right\">(.*?)</span>",
			"searchUrl":"https://meijuchong.com/index.php/vodsearch/-------------.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"usable":true
		},
		{
			"configName":"比米",
			"configType":"WebPage",
			"itemNameRegex":"<li><a href=\".*play/1/.*\">(.*?)</a>",
			"itemUrlRegex":"<li><a href=\"(.*play/1/.*)\">.*</a>",
			"searchNameRegex":"<li class=\"item\"><a href=\".*\" title=\"(.*?)\" target=\"_blank\" class=\"img\"><img class=\"lazy\" src=\".*\" referrerpolicy=",
			"searchPictureRegex":"<li class=\"item\"><a href=\".*\" title=\".*\" target=\"_blank\" class=\"img\"><img class=\"lazy\" src=\"(.*?)\" referrerpolicy=",
			"searchStateRegex":"<p title=\".*\"><span class=\"fl\">(.*?)</span></p>",
			"searchUrl":"http://bimiacg.com/vod/search/wd/{SearchWord}/page/1/",
			"searchUrlRegex":"<li class=\"item\"><a href=\"(.*?)\" title=\".*\" target=\"_blank\" class=\"img\"><img class=\"lazy\" src=\".*\" referrerpolicy=",
			"usable":true
		},
		{
			"configName":"97看",
			"configType":"WebPage",
			"itemNameRegex":"<li><a title=\"(.*)\" href=\".*\" target=\"_self\">",
			"itemUrlRegex":"<li><a title=\".*\" href=\"(.*)\" target=\"_self\">",
			"searchNameRegex":"<a class=\"link-hover\" href=\".*\" title=\"(.*)\"><img class=\"lazy\"",
			"searchPictureRegex":"data-original=\"(.*)\" src=",
			"searchStateRegex":"<p class=\"other\"><i>(.*)</i></p>",
			"searchUrl":"http://www.97qbb.com/search.php?searchword={SearchWord}",
			"searchUrlRegex":"<a class=\"link-hover\" href=\"(.*)\" title=\".*\"><img class=\"lazy\"",
			"usable":true
		},
		{
			"configName":"极品",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\"col-lg-\\d* col-md-\\d* col-sm-\\d* col-xs-\\d*\"><a class=\"btn btn-default\" href=\"/vodplay/\\d*-1-\\d*\\.html\">(.*)</a></li>",
			"itemUrlRegex":"<li class=\"col-lg-\\d* col-md-\\d* col-sm-\\d* col-xs-\\d*\"><a class=\"btn btn-default\" href=\"(/vodplay/\\d*-1-\\d*\\.html)\">.*</a></li>",
			"searchNameRegex":"<h4 class=\"title\"><a class=\"searchkey\" href=\".*\">(.*)</a></h4>",
			"searchPictureRegex":"data-original=\"(.*)\"><span class=\"play hidden-xs\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*)</span></a>",
			"searchUrl":"https://www.jpysvip.net/vodsearch/-------------.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"<h4 class=\"title\"><a class=\"searchkey\" href=\"(.*)\">.*</a></h4>",
			"sniffExcludeRegex":"https://ia\\.51\\.la.*",
			"usable":true
		},
		{
			"configName":"迪迪迪",
			"configType":"WebPage",
			"itemNameRegex":"<a class=\"btn btn-default\" href=\".*\">(.*)</a></li>",
			"itemUrlRegex":"<a class=\"btn btn-default\" href=\"(.*)\">.*</a></li>",
			"searchNameRegex":"href=\".*\" title=\"(.*)\" data-original=",
			"searchPictureRegex":"data-original=\"(.*)\"><span",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*)</span>",
			"searchUrl":"http://tv758.com/index.php/vod/search.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"href=\"(.*)\" title=\".*\" data-original=",
			"usable":true
		},
		{
			"configName":"肖先生",
			"configType":"WebPage",
			"itemNameRegex":"<a href=\".*/sid/\\d*/nid/\\d*.html\">(.*)</a>",
			"itemUrlRegex":"<a href=\"(.*/sid/\\d*/nid/\\d*.html)\">.*</a>",
			"searchNameRegex":"href=\"/index.php/vod/detail/id/\\d*.html\" title=\"(.*)\" data-original=",
			"searchPictureRegex":"title=\".*\" data-original=\"(.*)\">",
			"searchStateRegex":"<span class=\"hl-lc-1 remarks\">(.*)</span>",
			"searchUrl":"http://cs.syg520.cn/index.php/vod/search/wd/{SearchWord}.html",
			"searchUrlRegex":"href=\"(/index.php/vod/detail/id/\\d*.html)\" title=\".*\" data-original=",
			"usable":true
		},
		{
			"configName":"神鸡",
			"configType":"WebPage",
			"itemNameRegex":"<li> <a title=\"(.*)\" href=\".*\" target=\"_self\">",
			"itemUrlRegex":"<li> <a title=\".*\" href=\"(.*)\" target=\"_self\">.*</a> </li>",
			"searchNameRegex":"<a class=\"v-thumb stui-vodlist__thumb lazyload\" href=\".*\" title=\"(.*)\" data-original=",
			"searchPictureRegex":"data-original=\"(.*)\"> <span class=\"play hidden-xs\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*)</span></a>",
			"searchUrl":"http://www.sjj279.com/search?searchword={SearchWord}",
			"searchUrlRegex":"<a class=\"v-thumb stui-vodlist__thumb lazyload\" href=\"(.*)\" title=\".*\" data-original=",
			"usable":true
		},
		{
			"configName":"七零",
			"configType":"WebPage",
			"itemNameRegex":"<a class=\".*\" href=\"/vodplay.*\">(.*)</a></li>",
			"itemUrlRegex":"<a class=\".*\" href=\"(/vodplay/\\d*-1-\\d*\\.html)\">.*</a></li>",
			"searchNameRegex":"<h4 class=\"title\"><a class=\"searchkey\" href=\".*\">(.*)</a></h4>",
			"searchPictureRegex":"data-original=\"(.*)\"><span class=\"play hidden-xs\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*)</span></a>",
			"searchUrl":"https://www.70ys.cc/vodsearch/-------.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"<h4 class=\"title\"><a class=\"searchkey\" href=\"(.*)\">.*</a></h4>",
			"sniffExcludeRegex":"https://ia\\.51\\.la.*",
			"usable":true
		},
		{
			"configName":"高清B",
			"configType":"Kuyun77",
			"searchUrl":"aHR0cDovL2FwaS5rdW55dTc3LmNvbQ==",
			"usable":true
		},
		{
			"configName":"嘀哩",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*-1-.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*-1-.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchUrl":"http://www.diliktv.com/vodsearch/-------------.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"sniffExcludeRegex":".*diliktv.com.*",
			"sniffTargetExtensions":"m3u8",
			"usable":true
		},
		{
			"configName":"九八",
			"configType":"WebPage",
			"itemNameRegex":"<li><a title=\"(.*?)\" href=\".*\" target=\"_self\">.*</a></li>",
			"itemUrlRegex":"<li><a title=\".*\" href=\"(.*?)\" target=\"_self\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text\">(.*?)</span></a>",
			"searchTypeRegex":"",
			"searchUrl":"http://www.980kp.com/search.php?page=1&searchword={SearchWord}&searchtype=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"usable":true
		},
		{
			"configName":"JPY",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*vodplay/.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*vodplay/.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\"><",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\"><",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span></a>",
			"searchTypeRegex":"分类：</span>(.*?)<span class=\"split-line\"></span><span class=\"text-muted hidden-xs\">地区：</span>",
			"searchUrl":"https://www.jpysvip.net/vodsearch/-------------.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\"><",
			"sniffExcludeRegex":"https://ia\\.51\\.la.*",
			"usable":true
		},
		{
			"configName":"海绵",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*/sid/1/nid/.*\" target=\"_self\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*/sid/1/nid/.*)\" target=\"_self\">.*</a></li>",
			"searchNameRegex":"<h1 class=\"mo-wrap-arow mo-fsxs-16px mo-fssm-18px\"><a href=\".*\">(.*?)</a></h1>",
			"searchPictureRegex":"data-original=\"(.*?)\"><span class=\"mo-situ-play\"></span>",
			"searchStateRegex":"<span class=\"mo-situ-rema mo-part-ramp mo-fsxs-12px mo-text-white mo-coxs-center\">(.*?)</span></a>",
			"searchTypeRegex":"分类:&nbsp;</span><a href=\".*\" target=\"_blank\">(.*?)</a></li>",
			"searchUrl":"https://www.yuzhouys.com/index.php/vod/search.html?wd={SearchWord}",
			"searchUrlRegex":"<h1 class=\"mo-wrap-arow mo-fsxs-16px mo-fssm-18px\"><a href=\"(.*?)\">.*</a></h1>",
			"searchYearRegex":"年份:&nbsp;</span><a href=\".*\" target=\"_blank\">(.*?)</a>&nbsp;</li>",
			"usable":true
		},
		{
			"configName":"回响",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a href=\".*-1-.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a href=\"(.*-1-.*)\">.*</a></li>",
			"searchNameRegex":"hl-lazy\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"hl-lazy\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"hl-lc-1 remarks\">(.*?)</span>",
			"searchTypeRegex":"",
			"searchUrl":"https://hxys.tv/vodsearch/-------------.html?wd={SearchWord}",
			"searchUrlRegex":"hl-lazy\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"searchYearRegex":"",
			"usable":true
		},
		{
			"configName":"神马",
			"configType":"WebPage",
			"itemNameRegex":"<li><a href=\"/play/\\d*-1-\\d*/\">(.*?)</a></li>",
			"itemUrlRegex":"<li><a (href=\"/play/\\d*-1-\\d*/\")>.*</a></li>",
			"searchNameRegex":"<a class=\"stui-vodlist__thumb lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\"> <span",
			"searchPictureRegex":"<a class=\"stui-vodlist__thumb lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\"> <span",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchUrl":"POST:https://www.shenma4480.com/search/-------------/?PostBody={\"wd\":\"{SearchWord}\",\"submit\":\"\"}",
			"searchUrlRegex":"<a class=\"stui-vodlist__thumb lazyload\" (href=\".*?\") title=\".*\" data-original=\".*\"> <span",
			"usable":true
		},
		{
			"configName":"阿里云",
			"configType":"WebPage",
			"extensions":"unknown",
			"itemNameRegex":"<li><a href=\".*\\d*/sid/\\d*/nid/\\d*\\.html\">(.*)</a></li>",
			"itemRangeRegex":"<ul class=\"content_playlist.*?\">([\\w\\W]+?)</ul>",
			"itemUrlRegex":"<li><a href=\"(.*\\d*/sid/\\d*/nid/\\d*\\.html)\">.*</a></li>",
			"searchNameRegex":"<h4 class=\"vodlist_title\"><a href=\".*\" title=\"(.*)\"><span class=\"info_right\">.*</span>.*</a></h4>",
			"searchPictureRegex":"<a class=\"vodlist_thumb lazyload\" href=\".*\" title=\".*\" data-original=\"(.*)\"><span class=\"play hidden_xs\"></span><span class=\"pic_text text_right\">.*</span></a>",
			"searchStateRegex":"<a class=\"vodlist_thumb lazyload\" href=\".*\" title=\".*\" data-original=\".*\"><span class=\"play hidden_xs\"></span><span class=\"pic_text text_right\">(.*)</span></a>",
			"searchTypeRegex":"<h4 class=\"vodlist_title\"><a href=\".*\" title=\".*\"><span class=\"info_right\">(.*)</span>.*</a></h4>",
			"searchUrl":"http://www.wsba.com.cn/index.php/vod/search.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"<h4 class=\"vodlist_title\"><a href=\"(.*)\" title=\".*\"><span class=\"info_right\">.*</span>.*</a></h4>",
			"sniffExcludeRegex":"http://collect-v6.51.la/v6/collect",
			"usable":true
		},
		{
			"configName":"南瓜五",
			"configType":"WebPage",
			"itemNameRegex":"<li.*><a target=\"_blank\" href=\".*\\d*-1-\\d*\\.html\">(.*?)<",
			"itemUrl":"{SearchUrlOrId}&Header={\"User-Agent\":\"{WebViewUserAgent}\"}",
			"itemUrlRegex":"<li.*><a target=\"_blank\" href=\"(.*\\d*-1-\\d*\\.html)\">.*<",
			"searchNameRegex":"<a class=\"video-pic loading\" href=\".*\" title=\"(.*?)\" data-original=\".*\" style=\"padding-top:150%;\"><span class=\"note text-bg-c\">.*</span></a>",
			"searchPictureRegex":"<a class=\"video-pic loading\" href=\".*\" title=\".*\" data-original=\"(.*?)\" style=\"padding-top:150%;\"><span class=\"note text-bg-c\">.*</span></a>",
			"searchStateRegex":"<li class=\".*hidden-xs\"><span>状态：</span>(.*)</li>",
			"searchUrl":"POST:http://www.nangua55.com/search/?PostBody={\"wd\":\"{SearchWord}\"}&Header={\"User-Agent\":\"{WebViewUserAgent}\"}",
			"searchUrlRegex":"<a class=\"video-pic loading\" href=\"(.*?)\" title=\".*\" data-original=\".*\" style=\"padding-top:150%;\"><span class=\"note text-bg-c\">.*</span></a>",
			"searchYearRegex":"<span class=\".*hidden-xs\">年代：</span>(\\d{4})",
			"sniffTargetRegex":"https?://api.longdidi.top/parse/hls.php.*",
			"usable":true
		},
		{
			"configName":"美美",
			"configType":"MeiMei",
			"searchUrl":"https://www.58wk.com",
			"usable":true
		},
		{
			"configName":"鲱鱼",
			"configType":"FeiYu",
			"searchUrl":"aHR0cDovL3d3dy5mZXl1LnZpcA==",
			"usable":true
		},
		{
			"configName":"夜迷",
			"configType":"WebPage",
			"itemNameRegex":"<li><a href=\".*/vod/play/id.*\">(.*?)</a></li>",
			"itemUrlRegex":"<li><a href=\"(.*/vod/play/id.*)\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchTypeRegex":"类型：</span>(.*?)<span class=\"split-line\"></span><span class=\"text-muted\">地区",
			"searchUrl":"http://yeyemi.com/index.php/vod/search.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"searchYearRegex":"年份：</span>(.*?)</span></p>",
			"sniffExcludeRegex":".*la/.*",
			"usable":true
		},
		{
			"configName":"流年",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"> <a class=\".*\" href=\".*/sid/1/nid/.*\">(.*?)</a> ",
			"itemUrlRegex":"<li class=\".*\"> <a class=\".*\" href=\"(.*/sid/1/nid/.*)\">.*</a> ",
			"searchNameRegex":"<h1 class=\".*\"><a href=\".*\"><span class=\".*\">(.*?)</span></a></h1>",
			"searchPictureRegex":"<a class=\".*\" href=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"fed-list-remarks fed-font-xii fed-text-white fed-text-center\">(.*?)</span>",
			"searchTypeRegex":"分类：</span><a href=\".*\" target=\"_blank\">(.*?)</a></li>",
			"searchUrl":"http://www.liunianys.cn/index.php/vod/search.html?wd={SearchWord}",
			"searchUrlRegex":"<h1 class=\".*\"><a href=\"(.*?)\"><span class=\".*\">.*</span></a></h1>",
			"searchYearRegex":"年份：</span><a href=\".*\" target=\"_blank\">(.*?)</a>&nbsp;</li>",
			"usable":true
		},
		{
			"configName":"九七",
			"configType":"WebPage",
			"itemNameRegex":"<li><a title=\".*\" href=\".*/play.*\" target=\"_self\">(.*?)</a></li>",
			"itemUrlRegex":"<li><a title=\".*\" href=\"(.*/play.*)\" target=\"_self\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchUrl":"http://www.97kpz.com/search.php?page=1&searchword={SearchWord}&searchtype=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"usable":true
		},
		{
			"configName":"四K",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*\" href=\".*play/.*\" target=\"_blank\">(.*?)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*\" href=\"(.*play/.*)\" target=\"_blank\">.*</a></li>",
			"searchNameRegex":"lazyload\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"lazyload\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"pic-text text-right\">(.*?)</span>",
			"searchUrl":"http://www.4kvod.com/search/-------------/?wd={SearchWord}&submit=",
			"searchUrlRegex":"lazyload\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"usable":true
		},
		{
			"configName":"4K奈飞鸭",
			"configType":"WebPage",
			"extensions":"unknown",
			"itemNameRegex":"<li><a class=\"t-u\" href=\".*\">(.*)</a></li>",
			"itemUrlRegex":"<li><a class=\"t-u\" href=\"(.*)\">.*</a></li>",
			"searchNameRegex":"<a class=\"title cor1\" href=\".*\">(.*)<span class=\"cor2\">.*</span></a>",
			"searchPictureRegex":"<div class=\"bj eclazy\" data-original=\"(.*)\" style=\".*;\"></div>",
			"searchStateRegex":"<span class=\"pack-prb\">(.*)</span>",
			"searchTypeRegex":"<span class=\"pack-prt\">(.*?)</span>",
			"searchUrl":"https://www.yanetflix.com/index.php/vod/search.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"<a class=\"title cor1\" href=\"(.*)\">.*<span class=\"cor2\">.*</span></a>",
			"searchYearRegex":"",
			"usable":true
		},
		{
			"configName":"ADC",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a class=\".*info fed-part-eone\" href=\".*play/\\d*-\\d*-\\d*\\.html\">([^(线)]*?)</a></li>",
			"itemRangeRegex":"<ul class=\"fed-part-rows\">(.*?)</ul>",
			"itemUrlRegex":"<li class=\".*\"><a class=\".*info fed-part-eone\" href=\"(.*play/\\d*-\\d*-\\d*\\.html)\">[^(线)]*?</a></li>",
			"searchNameRegex":"<h1 class=\".*\"><a href=\".*\"><span class=\".*\">(.*?)</span></a></h1>",
			"searchPictureRegex":"data-original=\"(.*?)\"><span class=",
			"searchStateRegex":"<span class=\"fed-list-remarks fed-font-xii fed-text-white fed-text-center\">(.*?)</span>",
			"searchUrl":"https://www.adcmove.com/search/-------------.html?wd={SearchWord}",
			"searchUrlRegex":"<h1 class=\".*\"><a href=\"(.*?)\"><span class=\".*\">.*</span></a></h1>",
			"sniffExcludeRegex":".*adcmove.*",
			"sniffTargetExtensions":"m3u8",
			"sniffTargetRegex":"(https?://){1}[^(https?://)]/index.*",
			"usable":true
		},
		{
			"configName":"酷客",
			"configType":"WebPage",
			"extensions":"unknown",
			"itemNameRegex":"<li><a href=\".*\\d*-0-\\d*\\.html\" target=\"_self\" title=\"(.*)\">.*</a></li>",
			"itemUrlRegex":"<li><a href=\"(.*\\d*-0-\\d*\\.html)\" target=\"_self\" title=\".*\">.*</a></li>",
			"searchNameRegex":"<h3 class=\"title\"><a href=\".*\">(.*)</a></h3>",
			"searchPictureRegex":"<a class=\".*\" data-original=\"(.*)\" href=\".*\" title=\".*\"><span class=\"play hidden-xs\"></span> <span class=\"pic-text text-right\">.*</span></a>",
			"searchStateRegex":"<a class=\".*\" data-original=\".*\" href=\".*\" title=\".*\"><span class=\"play hidden-xs\"></span> <span class=\"pic-text text-right\">(.*)</span></a>",
			"searchTypeRegex":"类型：</span>(.*?)<",
			"searchUrl":"POST:http://www.anluyg.net/search.php?PostBody={\"searchword\":\"{SearchWordNoEncryption}\"}",
			"searchUrlRegex":"<h3 class=\"title\"><a href=\"(.*)\">.*</a></h3>",
			"searchYearRegex":"年份：</span>(.*?)<",
			"usable":true
		},
		{
			"configName":"六度",
			"configType":"WebPage",
			"extensions":"unknown",
			"itemNameRegex":"<li><a title=\".*\" href=\".*\\d*/0/\\d*\\.html\" target=\"_self\">(.*)</a></li>",
			"itemUrlRegex":"<li><a title=\".*\" href=\"(.*\\d*/0/\\d*\\.html)\" target=\"_self\">.*</a></li>",
			"searchNameRegex":"<h3 class=\"title\"><a href=\".*\">(.*)</a></h3>",
			"searchPictureRegex":"<a class=\".*\" href=\".*\" title=\".*\" alt=\".*\" data-original=&\"(.*?)\">",
			"searchTypeRegex":"类型：</span>(.*?)<",
			"searchUrl":"POST:http://6d.43miko.cn/?c=search&PostBody={\"wd\":\"{SearchWord}\"}",
			"searchUrlRegex":"<h3 class=\"title\"><a href=\"(.*)\">.*</a></h3>",
			"searchYearRegex":"年份：</span>(.*?)<",
			"usable":true
		},
		{
			"configName":"落尘",
			"configType":"WebPage2",
			"itemNameRegex":"<li.*><a href=\".*/\\d*/0/\\d*\\.html\">(.*?)</a></li>",
			"itemUrl":"{SearchUrlOrId}&Header={\"User-Agent\":\"{WebViewUserAgent}\"}",
			"itemUrlRegex":"<li.*><a href=\"(.*/\\d*/0/\\d*\\.html)\">.*</a></li>",
			"searchNameRegex":"<span class=\"sTit\">([^<>]*)</span>",
			"searchPictureRegex":"<img src=\"(.*)\" onerror=\"nofind\\(\\);\" style=\"width: 0px; height: 0px;\">",
			"searchTypeRegex":"<span class=\"sStyle\"><em class=\"styleBlue\">(.*)</em></span>",
			"searchUrl":"POST:https://v.20s.wang/?c=search&PostBody={\"wd\":\"{SearchWord}\"}&Header={\"User-Agent\":\"{WebViewUserAgent}\"}",
			"searchUrlRegex":"</div> <a href=\"(.*)\" target=\"_self\" class=\"aMask\" style=\"width: 0px; height: 0px;\"></a> </li>",
			"searchYearRegex":"<span class=\"sDes\">&nbsp;&nbsp;/&nbsp;&nbsp;(.*)</span>",
			"usable":true
		},
		{
			"configName":"欧巴",
			"configType":"WebPage",
			"itemNameRegex":"<li class=\".*\"><a href=\".*/id/.*/sid/1/nid/\\d*\\.html.*\">(.*)</a></li>",
			"itemUrlRegex":"<li class=\".*\"><a href=\"(.*/id/.*/sid/1/nid/\\d*\\.html).*\">.*</a></li>",
			"searchNameRegex":"<a class=\"hl-item-thumb hl-lazy\" href=\".*\" title=\"(.*?)\" data-original=\".*\">",
			"searchPictureRegex":"<a class=\"hl-item-thumb hl-lazy\" href=\".*\" title=\".*\" data-original=\"(.*?)\">",
			"searchStateRegex":"<span class=\"hl-lc-1 remarks\">(.*)</span>",
			"searchTypeRegex":"<p class=\"hl-item-sub hl-lc-1\"> <em>(.*?)</em>",
			"searchUrl":"https://www.o8tv.com/index.php/vod/search.html?wd={SearchWord}&submit=",
			"searchUrlRegex":"<a class=\"hl-item-thumb hl-lazy\" href=\"(.*?)\" title=\".*\" data-original=\".*\">",
			"searchYearRegex":"&nbsp;&middot;&nbsp;(.*?)&nbsp;&middot;&nbsp;",
			"usable":true
		}
	],
	"searchManager":{},
	"analysisApi":{
		"147":{
			"api":"https://man.ledboke.com/147/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"1717":{
			"api":"https://www.1717yun.com/jx/ty.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"17云":{
			"api":"http://17kyun.com/api.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"256":{
			"api":"https://pay.520yk.cn/256/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"2AA":{
			"api":"http://www.2ajx.com/vip.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"2AB":{
			"api":"http://www.2ajx.com/vip.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"3jx":{
			"api":"https://api.3jx.top/vip/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"4080":{
			"api":"https://jx.urlkj.com/4080/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"555解析":{
			"api":"https://titan.mgtv.com.o8tv.com/jiexi/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"618G":{
			"api":"https://jx.618g.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"8090":{
			"api":"https://www.8090g.cn/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"91全网":{
			"api":"https://www.91jxs.com/jiexi/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"920":{
			"api":"https://api.tv920.com/jx/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"973":{
			"api":"https://jx.973973.xyz/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"BL":{
			"api":"https://vip.bljiex.com/?v=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"CHok":{
			"api":"https://www.gai4.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"CK":{
			"api":"https://www.ckplayer.vip/jiexi/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"CKMOV":{
			"api":"https://ckmov.ccyjjd.com/ckmov/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"CKMOV解析":{
			"api":"https://www.ckmov.vip/api.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"H8":{
			"api":"https://www.h8jx.com/jiexi.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"IK":{
			"api":"https://vip.ikjiexi.top/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"LLQPlayer":{
			"api":"https://jiexi.jiexizhuanyong.com/wapjx/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"M1907":{
			"api":"https://z1.m1907.cn/?jx=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"M3U":{
			"api":"https://jiexi.janan.net/jiexi/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"M3U8.TV":{
			"api":"https://jx.m3u8.tv/jiexi/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"MPOS":{
			"api":"https://vip.mpos.ren/v/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"OK1":{
			"api":"https://api.okjx.cc:666/jx.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"OK2":{
			"api":"https://okjx.cc/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"PAR":{
			"api":"https://vip.parwix.com:4433/player/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"Playm3u8":{
			"api":"https://www.playm3u8.cn/jiexi.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"SSAMAO":{
			"api":"https://www.ssamao.com/jx/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"YJ":{
			"api":"https://cdn.yangju.vip/k/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"七夕":{
			"api":"https://api.80tvs.cn/m3u8.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"七年":{
			"api":"http://42.192.47.132/jx/mao/index.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"七彩":{
			"api":"https://www.xymav.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"久播":{
			"api":"https://vip.jiubojx.com/vip/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true,
			"vip":"&referer="
		},
		"乐喵":{
			"api":"https://jx.hao-zsj.cn/vip/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"乐多":{
			"api":"https://api.leduotv.com/wp-api/ifr.php?vid=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"乐看至":{
			"api":"https://lekan.4v0r.cn/m3u8.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"九八看":{
			"api":"https://jx.youyitv.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"云析":{
			"api":"https://jx.mw0.cc/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"云端":{
			"api":"https://jx.ergan.top/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"云网":{
			"api":"https://www.41478.net/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"冰豆":{
			"api":"https://api.qianqi.net/vip/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"加速":{
			"api":"https://www.cuan.la/m3u8.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"南柯":{
			"api":"https://www.nkdyw.cn/jx.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"夜空":{
			"api":"https://pay.520yk.cn/256/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"大亨":{
			"api":"http://api.13tv.top/jiexi/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"大侠":{
			"api":"https://api.10dy.net/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"大师":{
			"api":"https://jx.ergan.top/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"大白":{
			"api":"http://api.myzch.cn/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"小蒋极":{
			"api":"https://www.kpezp.cn/jlexi.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"思云":{
			"api":"https://jx.ap2p.cn/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"思古A":{
			"api":"https://api.bbbbbb.me/jx/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"思古B":{
			"api":"https://api.sigujx.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"思古C":{
			"api":"https://jsap.attakids.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"思古D":{
			"api":"https://t.siguyy.com/player/analysis.php?v=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"思念":{
			"api":"https://jsap.attakids.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"恶灵":{
			"api":"https://jx.elwtc.com/vip/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"放开云":{
			"api":"http://api.iopenyun.com:88/vip/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"无名":{
			"api":"https://www.administratorw.com/index.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"时光":{
			"api":"https://jiexi.janan.net/jiexi/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"明日":{
			"api":"https://www.qianyicp.com/jiexi/index.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"星影":{
			"api":"https://www.2kxy.com/jb/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"星驰":{
			"api":"https://vip.cjys.top/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"智能":{
			"api":"https://go.yh0523.cn/y.cy?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"暮光":{
			"api":"https://muguang.mgtv.com.muguangys.com/jiexi.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"月亮":{
			"api":"https://api.yueliangjx.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"月亮云A":{
			"api":"http://api.yueliangjx.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"月亮云B":{
			"api":"https://api.yueliangjx.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"枫林":{
			"api":"https://api.fenglinys.net/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"核对":{
			"api":"https://api.hdworking.top/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"求生人":{
			"api":"https://api.yananweidao.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"淘影":{
			"api":"https://jx.vodjx.top/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"爱跟":{
			"api":"https://vip.2ktvb.com/player/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"爱酷看看":{
			"api":"http://www.ikukk.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"狂奔":{
			"api":"http://k8aa.com/jx/index.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"狼云":{
			"api":"https://jx.yaohuaxuan.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"玩嗨":{
			"api":"https://www.yaosou.cc/jiexi/?v=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"电影盒子":{
			"api":"http://jx5.178du.com/p1/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"盖斯":{
			"api":"https://www.gai4.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"盘古A":{
			"api":"https://api.jx.yh0523.cn/test/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"盘古B":{
			"api":"https://www.pangujiexi.com/jiexi/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"看剧猫":{
			"api":"http://jx.kanjumao.cn/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"神马":{
			"api":"https://jxx.smys8.cn/index.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"福星":{
			"api":"https://jx.popo520.cn/jiexi/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"简傲云":{
			"api":"https://vip.mcyanyu.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"老斑":{
			"api":"https://vip.laobandq.com/jiexi.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"蓝光高清资源站":{
			"api":"https://j.languang.wfss100.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"蘑菇":{
			"api":"https://jx.wzslw.cn/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"蝴蝶":{
			"api":"https://api.hdworking.top/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"解析啦":{
			"api":"https://api.jiexi.la/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"诺讯":{
			"api":"https://www.ckmov.com/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"迪耿蓝光":{
			"api":"https://api.1dior.cn/analysis/123/index.php?uid=1428&my=afkruDFIYZ&url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"酷博":{
			"api":"http://jx.x-99.cn/api.php?id=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"酷点":{
			"api":"http://bf.kudian6.com/jiexi.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"金桥A":{
			"api":"https://5.nmgbq.com/2/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"金桥B":{
			"api":"https://jqaaa.com/jx.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"零视":{
			"api":"https://video.eeeol.cn/jx.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"音萌":{
			"api":"https://api.v6.chat/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"饭团":{
			"api":"https://qian.wkfile.com/m3u8.php?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		},
		"麻瓜":{
			"api":"http://jx.maguays.cc/?url=",
			"support":[
				"iqiyi",
				"qq",
				"youku",
				"mgtv",
				"sohu",
				"bilibili",
				"pptv",
				"1905",
				"miguvideo",
				"ixigua"
			],
			"usable":true
		}
	},
	"sniffUrlSkip":{},
	"televisionList":[
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.168.91/PLTV/1/224/3221225594/index.m3u8",
					"tvUrlTips":"HD"
				},
				{
					"sniff":true,
					"tvUrl":"http://39.135.33.12/PLTV/77777777/224/3221226666/index.m3u8#mp4",
					"tvUrlTips":"1080P"
				}
			],
			"tvLogo":"",
			"tvName":"天津卫视-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.168.91/PLTV/1/224/3221225528/index.m3u8",
					"tvUrlTips":"HD"
				},
				{
					"sniff":true,
					"tvUrl":"http://39.135.33.12/PLTV/77777777/224/3221226654/index.m3u8#mp4",
					"tvUrlTips":"1080P"
				}
			],
			"tvLogo":"",
			"tvName":"广东卫视-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.115.163:8080/PLTV/88888910/224/3221225639/index.m3u8#mp4",
					"tvUrlTips":"HD"
				},
				{
					"sniff":true,
					"tvUrl":"http://39.135.33.12/PLTV/77777777/224/3221226715/index.m3u8#mp4",
					"tvUrlTips":"1080P"
				}
			],
			"tvLogo":"",
			"tvName":"CCTV14少儿-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.115.163:8080/PLTV/88888910/224/3221225628/index.m3u8#mp4",
					"tvUrlTips":"HD"
				},
				{
					"sniff":true,
					"tvUrl":"http://39.135.33.12/PLTV/77777777/224/3221226816/index.m3u8#mp4",
					"tvUrlTips":"1080P"
				}
			],
			"tvLogo":"",
			"tvName":"CCTV11戏曲-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.115.163:8080/PLTV/88888910/224/3221225627/index.m3u8",
					"tvUrlTips":"HD"
				},
				{
					"sniff":true,
					"tvUrl":"http://39.135.33.12/PLTV/77777777/224/3221226640/index.m3u8#mp4",
					"tvUrlTips":"1080P"
				}
			],
			"tvLogo":"",
			"tvName":"CCTV10科教-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.115.163:8080/PLTV/88888910/224/3221225626/index.m3u8#mp4",
					"tvUrlTips":"HD"
				},
				{
					"sniff":true,
					"tvUrl":"http://39.135.33.12/PLTV/77777777/224/3221226648/index.m3u8#mp4",
					"tvUrlTips":"1080P"
				}
			],
			"tvLogo":"",
			"tvName":"CCTV9纪录-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.115.163:8080/PLTV/88888910/224/3221225624/index.m3u8#mp4",
					"tvUrlTips":"HD"
				},
				{
					"sniff":true,
					"tvUrl":"http://39.135.33.12/PLTV/77777777/224/3221226646/index.m3u8#mp4",
					"tvUrlTips":"1080P"
				}
			],
			"tvLogo":"",
			"tvName":"CCTV7国防军事-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.115.163:8080/PLTV/88888910/224/3221225621/index.m3u8#mp4",
					"tvUrlTips":"HD"
				},
				{
					"sniff":true,
					"tvUrl":"http://39.135.33.12/PLTV/77777777/224/3221226817/index.m3u8#mp4",
					"tvUrlTips":"1080P"
				}
			],
			"tvLogo":"",
			"tvName":"CCTV4中文国际-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.115.163:8080/PLTV/88888910/224/3221225647/index.m3u8#mp4",
					"tvUrlTips":"HD"
				},
				{
					"sniff":true,
					"tvUrl":"http://39.135.33.12/PLTV/77777777/224/3221226717/index.m3u8#mp4",
					"tvUrlTips":"1080P"
				}
			],
			"tvLogo":"",
			"tvName":"CCTV3综艺-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.115.163:8080/PLTV/88888910/224/3221225641/index.m3u8#mp4",
					"tvUrlTips":"HD"
				},
				{
					"sniff":true,
					"tvUrl":"http://39.135.33.12/PLTV/77777777/224/3221226818/index.m3u8#mp4",
					"tvUrlTips":"1080P"
				}
			],
			"tvLogo":"",
			"tvName":"CCTV15音乐-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://m.douyu.com/8805?type=ip",
					"tvUrlTips":"HD斗鱼"
				}
			],
			"tvName":"罗翔刑法",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.115.163:8080/PLTV/88888910/224/3221225741/index.m3u8#mp4",
					"tvUrlTips":"HD"
				}
			],
			"tvLogo":"",
			"tvName":"深圳卫视-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.168.91/PLTV/1/224/3221225590/index.m3u8",
					"tvUrlTips":"HD"
				}
			],
			"tvLogo":"",
			"tvName":"辽宁卫视-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.168.91/PLTV/1/224/3221225504/index.m3u8",
					"tvUrlTips":"HD"
				}
			],
			"tvLogo":"",
			"tvName":"东方卫视-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.115.163:8080/PLTV/88888910/224/3221225736/index.m3u8#mp4",
					"tvUrlTips":"HD"
				}
			],
			"tvLogo":"",
			"tvName":"黑龙江卫视-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.115.163:8080/PLTV/88888910/224/3221225734/index.m3u8#mp4",
					"tvUrlTips":"HD"
				}
			],
			"tvLogo":"",
			"tvName":"重庆卫视-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.115.163:8080/PLTV/88888910/224/3221225740/index.m3u8#mp4",
					"tvUrlTips":"HD"
				}
			],
			"tvLogo":"",
			"tvName":"湖北卫视-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.115.163:8080/PLTV/88888910/224/3221225746/index.m3u8#mp4",
					"tvUrlTips":"HD"
				}
			],
			"tvLogo":"",
			"tvName":"江西卫视-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.115.163:8080/PLTV/88888910/224/3221225738/index.m3u8#mp4",
					"tvUrlTips":"HD"
				},
				{
					"sniff":true,
					"tvUrl":"http://39.135.33.12/PLTV/77777777/224/3221226662/index.m3u8#mp4",
					"tvUrlTips":"1080P"
				}
			],
			"tvLogo":"",
			"tvName":"山东卫视-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"",
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://39.134.115.163:8080/PLTV/88888910/224/3221225657/index.m3u8#mp4",
					"tvUrlTips":"HD"
				}
			],
			"tvLogo":"",
			"tvName":"东南卫视-HD",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"anhui",
			"tvList":[
				{
					"tvUrl":"http://39.134.168.91/PLTV/1/224/3221225548/index.m3u8",
					"tvUrlTips":"HD"
				}
			],
			"tvLogo":"https://s1.ax1x.com/2020/05/06/Ykxq2T.png",
			"tvName":"安徽卫视",
			"uiType":"Normal",
			"usable":true
		},
		{
			"epgIndex":"jiangsu",
			"tvList":[
				{
					"tvUrl":"http://39.134.168.91/PLTV/1/224/3221225512/index.m3u8",
					"tvUrlTips":"HD"
				}
			],
			"tvLogo":"https://s1.ax1x.com/2020/05/06/Ykztds.png",
			"tvName":"江苏卫视",
			"uiType":"Normal",
			"usable":true
		},
		{
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"https://m.douyu.com/2132902",
					"tvUrlTips":"HD斗鱼"
				}
			],
			"tvName":"陈翔六点半",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://m.douyu.com/3637765?type=ip",
					"tvUrlTips":"HD斗鱼"
				}
			],
			"tvName":"经典功夫港片",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://m.douyu.com/8449367?type=ip",
					"tvUrlTips":"HD斗鱼"
				}
			],
			"tvName":"足球西看台",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://m.douyu.com/3637726?type=ip",
					"tvUrlTips":"HD斗鱼"
				}
			],
			"tvName":"经典港式恐怖",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"tvList":[
				{
					"sniff":false,
					"tvUrl":"http://107.148.254.201:13164/play.m3u8?token=BWAiAK2GR%2Fd%2FL9K5eYRV5LZG&tid=migu&id=81",
					"tvUrlTips":"HD"
				}
			],
			"tvName":"周星驰影院",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"tvList":[
				{
					"tvUrl":"http://183.207.249.14/PLTV/3/224/3221225567/index.m3u8",
					"tvUrlTips":"HD"
				}
			],
			"tvName":"黑莓电影",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"tvList":[
				{
					"sniff":true,
					"tvUrl":"http://m.douyu.com/436240?type=wh",
					"tvUrlTips":"斗鱼HD"
				}
			],
			"tvName":"深夜奇谈",
			"uiType":"NotEPG",
			"usable":true
		},
		{
			"epgIndex":"hunan",
			"tvList":[
				{
					"tvUrl":"http://39.134.168.91/PLTV/1/224/3221225518/index.m3u8",
					"tvUrlTips":"HD"
				}
			],
			"tvLogo":"https://s1.ax1x.com/2020/05/06/YkzGLQ.png",
			"tvName":"湖南卫视",
			"uiType":"Normal",
			"usable":true
		},
		{
			"epgIndex":"cctv10",
			"tvList":[
				{
					"tvUrl":"http://mgsp.live.miguvideo.com:8088/wd_r2/2018/ocn/cctv10hd/2000/index.m3u8?msisdn=202104270837558af52d5160eb422a96bc2c876463fae8&mdspid=&spid=699004&netType=0&sid=5500212874&pid=2028597139&timestamp=20210427083755&Channel_ID=0116_25000000-99000-100300010010001&ProgramID=624878405&ParentNodeID=-99&assertID=5500212874&client_ip=118.123.7.220&SecurityKey=20210427083755&mvid=5100001696&mcid=500020&mpid=&playurlVersion=SJ-A1-4.3.4&userid=&jmhm=&videocodec=h264&encrypt=b5e54f112570f79909e2d7923814cdc7",
					"tvUrlTips":"HD"
				}
			],
			"tvLogo":"https://p.pstatp.com/origin/pgc-image/096fd196271b4ab7bbeb92dd8e39150f",
			"tvName":"CCTV-10 科教",
			"uiType":"Normal",
			"usable":true
		},
		{
			"epgIndex":"cctv8",
			"tvList":[
				{
					"tvUrl":"http://39.134.168.91/PLTV/1/224/3221225562/index.m3u8",
					"tvUrlTips":"FHD"
				},
				{
					"tvUrl":"http://cctv5alih5ca.v.myalicdn.com/live/cctv8_2/index.m3u8",
					"tvUrlTips":"流畅"
				}
			],
			"tvLogo":"https://s1.ax1x.com/2020/05/06/YkxzZ9.png",
			"tvName":"CCTV-8 电视剧",
			"uiType":"Normal",
			"usable":true
		},
		{
			"epgIndex":"cctv5plus",
			"tvList":[
				{
					"tvUrl":"http://117.136.156.107/PLTV/88888888/224/3221225512/index.m3u8",
					"tvUrlTips":"标清"
				},
				{
					"tvUrl":"http://cctv5alih5ca.v.myalicdn.com/live/cctv5plus_2/index.m3u8",
					"tvUrlTips":"流畅"
				}
			],
			"tvLogo":"https://s1.ax1x.com/2020/05/06/YkzpI1.png",
			"tvName":"CCTV-5+ 体育赛事",
			"uiType":"Normal",
			"usable":true
		},
		{
			"epgIndex":"cctv5",
			"tvList":[
				{
					"tvUrl":"http://39.135.138.58:18890/PLTV/88888910/224/3221225752/index.m3u8",
					"tvUrlTips":"高清"
				},
				{
					"tvUrl":"http://cctv5alih5ca.v.myalicdn.com/live/cctv5_2/index.m3u8",
					"tvUrlTips":"流畅"
				}
			],
			"tvLogo":"https://s1.ax1x.com/2020/05/06/YkxXMF.png",
			"tvName":"CCTV-5 体育",
			"uiType":"Normal",
			"usable":true
		},
		{
			"epgIndex":"cctv2",
			"tvList":[
				{
					"tvUrl":"http://39.134.216.5/live.hcs.cmvideo.cn:8088/wd_r2/cctv/cctv2hd/3000/index.m3u8?ProgramID=&encrypt=1",
					"tvUrlTips":"高清"
				},
				{
					"tvUrl":"http://112.17.40.145/PLTV/88888888/224/3221226138/index.m3u8",
					"tvUrlTips":"HD"
				},
				{
					"tvUrl":"https://cctvcnch5ca.v.wscdns.com/live/cctv2_2/index.m3u8",
					"tvUrlTips":"流畅"
				}
			],
			"tvLogo":"https://s1.ax1x.com/2020/05/06/YkxT5q.png",
			"tvName":"CCTV-2 财经",
			"uiType":"Normal",
			"usable":true
		},
		{
			"epgIndex":"cctv1",
			"tvList":[
				{
					"tvUrl":"http://39.134.216.5/live.hcs.cmvideo.cn:8088/wd_r2/cctv/cctv1hd/2500/index.m3u8?ProgramID=&encrypt=1",
					"tvUrlTips":"高清"
				},
				{
					"tvUrl":"https://cctvcnch5ca.v.wscdns.com/live/cctv1_2/index.m3u8",
					"tvUrlTips":"流畅"
				}
			],
			"tvLogo":"https://s1.ax1x.com/2020/05/06/YkxHP0.png",
			"tvName":"CCTV-1 综合",
			"uiType":"Normal",
			"usable":true
		},
		{
			"epgIndex":"dongfang",
			"tvList":[
				{
					"tvUrl":"http://39.134.168.91/PLTV/1/224/3221225504/index.m3u8",
					"tvUrlTips":"HD"
				}
			],
			"tvLogo":"https://s1.ax1x.com/2020/05/06/YkzeZd.png",
			"tvName":"东方卫视",
			"uiType":"Normal",
			"usable":true
		},
		{
			"epgIndex":"zhejiang",
			"tvList":[
				{
					"tvUrl":"http://39.134.168.91/PLTV/1/224/3221225520/index.m3u8",
					"tvUrlTips":"HD2"
				}
			],
			"tvLogo":"https://s1.ax1x.com/2020/05/06/Ykz6eJ.png",
			"tvName":"浙江卫视",
			"uiType":"Normal",
			"usable":true
		},
		{
			"epgIndex":"btv1",
			"tvList":[
				{
					"tvUrl":"http://39.134.168.91/PLTV/1/224/3221225524/index.m3u8",
					"tvUrlTips":"HD"
				}
			],
			"tvLogo":"https://s1.ax1x.com/2020/05/06/YkxbGV.png",
			"tvName":"北京卫视",
			"uiType":"Normal",
			"usable":true
		},
		{
			"epgIndex":"cctv6",
			"tvList":[
				{
					"tvUrl":"http://39.134.216.5/live.hcs.cmvideo.cn:8088/migu/kailu/cctv6hd265/55/20200407/index.m3u8?ProgramID=&encrypt=1",
					"tvUrlTips":"FHD"
				},
				{
					"tvUrl":"http://cctv5alih5ca.v.myalicdn.com/live/cctv6_2/index.m3u8",
					"tvUrlTips":"流畅"
				}
			],
			"tvLogo":"https://s1.ax1x.com/2020/05/06/Ykxjr4.png",
			"tvName":"CCTV-6 电影",
			"uiType":"Normal",
			"usable":true
		},
		{
			"epgIndex":"cctvchild",
			"tvList":[
				{
					"tvUrl":"http://39.134.216.5/mgsp.live.miguvideo.com:8088/wd_r2/ocn/cctv14hd/3000/index.m3u8?&encrypt=1",
					"tvUrlTips":"HD"
				}
			],
			"tvLogo":"https://p.pstatp.com/origin/pgc-image/9f55a90fdb7c4a259ad2194595e3c1fc",
			"tvName":"CCTV-14 少儿",
			"uiType":"Normal",
			"usable":true
		},
		{
			"epgIndex":"cctv13",
			"tvList":[
				{
					"tvUrl":"http://39.135.138.60:18890/PLTV/88888910/224/3221225638/index.m3u8",
					"tvUrlTips":"FHD"
				},
				{
					"tvUrl":"https://cctvcnch5ca.v.wscdns.com/live/cctv13_2/index.m3u8",
					"tvUrlTips":"流畅"
				}
			],
			"tvLogo":"https://s1.ax1x.com/2020/05/06/YkzFxO.png",
			"tvName":"CCTV-13 新闻",
			"uiType":"Normal",
			"usable":true
		},
		{
			"epgIndex":"cctv12",
			"tvList":[
				{
					"tvUrl":"http://39.134.216.5/live.hcs.cmvideo.cn:8088/migu/kailu/20200324/cctv12hd/57/index.m3u8?ProgramID=&encrypt=1",
					"tvUrlTips":"FHD"
				},
				{
					"tvUrl":"http://cctv5alih5ca.v.myalicdn.com/live/cctv12_2/index.m3u8",
					"tvUrlTips":"流畅"
				}
			],
			"tvLogo":"https://s1.ax1x.com/2020/05/06/YkziRK.png",
			"tvName":"CCTV-12 社会与法",
			"uiType":"Normal",
			"usable":true
		}
	],
	"fastVideoList":[
		{
			"extensions":"unknown",
			"fvName":"蓝雀爆笑解说",
			"fvUrl":"https://m.douyu.com/8656759?type=ip",
			"isLive":true,
			"usable":true
		},
		{
			"extensions":"unknown",
			"fvName":"小乔讲电影",
			"fvUrl":"https://m.douyu.com/8413908?type=ip",
			"isLive":true,
			"usable":true
		},
		{
			"extensions":"unknown",
			"fvName":"牛叔说电影",
			"fvUrl":"https://m.douyu.com/2758565?type=ip",
			"isLive":true,
			"usable":true
		},
		{
			"extensions":"unknown",
			"fvName":"科幻Fans布玛",
			"fvUrl":"https://m.douyu.com/3508304?type=ip",
			"isLive":true,
			"usable":true
		},
		{
			"extensions":"unknown",
			"fvName":"小片片说大片",
			"fvUrl":"https://m.douyu.com/4258555?type=ip",
			"isLive":true,
			"usable":true
		},
		{
			"extensions":"unknown",
			"fvName":"哇妹综解",
			"fvUrl":"https://m.douyu.com/8657920?type=ip",
			"isLive":true,
			"usable":true
		},
		{
			"extensions":"unknown",
			"fvName":"HD影视",
			"fvUrl":"http://hpull.kktv8.com/livekktv/111536805/playlist.m3u8",
			"isLive":true,
			"usable":true
		}
	]
}
