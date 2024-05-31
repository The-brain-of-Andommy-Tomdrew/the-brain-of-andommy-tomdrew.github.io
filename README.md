# 關於我在XX成為IT vendor的這檔事
## 背景
本人是一個做左十年有多而又乜都唔識的又無得升職揼石仔的Software Engineer，而又中意守水堂嗰D人，是咁的，我係係一間都唔知係咪叫做Vendor既嘅公司做Senior Consultant(下稱SC)，原本都9 fing fing，hea下hea下又一日，你都咪話都真係幾爽下。
有一日，地公司有個Manager R姐，想搵我落去個Project 幫手啦，咁公司D人就叫我做T啦。

## Hardware Integration 記

R姐:喂，啊T，得唔得閒幫手，有D Integration 嘅野想你幫手睇睇。
ME:心諗乜料呢，又搞9 ME。
R姐:有乜野方法可以係個Web base嘅Application(即係Website) 駁到落去個Hardware度，而又可踢得著部機而又可以communicate到，將D Data比返個Web App 食返。

聽完R姐講，咁都應該唔好難姐，以為你地要整架飛機出黎。點解我會咁講，係因為佢比左份Deck出黎，講左個Solution，由個Web App 做Trigger Point，用一條async API Call localhost嘅IIS 既 NodeJs寫既一個APP 仔去Call 個SDK(DLL) 同個Card Reader communicate 啦，之後再係個local嘅IIS 寫個Data 落去kafka度，即EDA(Event Driven Architecture)，咁個Frontend 即係個Web App啊，會不停咁問個Server 拎返個Card Reader Read左嘅Data。
ME:嘩。你地搞乜撚野，要搞到咁複雜，你地識唔識嫁?
R姐:個Solution 係由條TEAM 入面嘅Architect(下稱R哥又名匡仔) 同 Application Team Lead(下稱Tracy，咁聽個名以為係女黎啦，點知係個男人黎。刁) 加上一班GDC(即大陸嘅揼石仔)，研究左二個月既Solution黎，原本果個Solution係叫個客做個API 出黎我地CALL 佢地API 叫佢地個API 同個Hardware做Integration。
ME:你比哂D SDK 啊，requirement 我，我做埋個Demo比你，你拎個Solution去Present 啦。
咁啊R姐就比哂我要嘅野比我啦。我原本係嗰啲唔會做Deck同埋唔做Presentation嘅人黎，我就砌左份Deck同埋挾左兩條Demo嘅片入去，咁所有野都係Point Form，叫佢地拎去Present啦，跟住R姐又叫我做埋個Presentation，話佢地個Architect 同App team lead唔識講喎，咁都算啦，你話做咪做囉。
到左要Present嗰日啦，臨Present前半個鐘，R姐打左個電話過黎，心諗你都知我唔係好聽電話嫁啦，打過黎乜事啊，一聽個電話，
ME: 喂，乜事?
R姐:我地個Architect 匡仔 有D 野想係個Present 前夾一夾。
匡仔: 啊T 呀，我睇完你份野，我驚個客會唔接受個Solution喎。
ME: 咁點啊，你有冇Soltion啊。一係你講，一係我講，一係取消個會。又未撚講你又話驚個客乜乜柒柒。
匡仔: 咁啊。個會照去囉。
ME: 無野啦嘛? 無就 bye 啦
咁夠鐘Present啦，我就Join個zoom。9 UP 完一輪。講完成個Deck，播完條Demo片，再講係用WebSocket 嘅 方法去做。咁都無問題啦。咁最多都人地Infra Security team既人問左D 無聊嘅Secuirty 既問題，咁我答左佢，只有Localhost可以駁到個local WebSocket Server，咁都無問題啦。 當時我都仲係WFH，咁開完個會啦，就梗係第一時間quit會之後繼續係度HEA啦。無咩事就梗係繼續休息啦。

## 被正式拉落水
咁佢地係會有份Team Chart 去同人地公司Present啦，咁我就好自然地成為左個Chart上面嘅一條Work stream 既其中一人，咁嗰條Work Stream 個名就係叫做S.W.A.T，只有一個人，咁都係我要求嫁啦，原因係我本人向來都係one man band，唔係咁想比人煩同埋煩到人

## Scanner 記
## Aduit Log 記
## DaaS 記
## OO記
