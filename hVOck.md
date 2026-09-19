百度蜘蛛是百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
汤士塘滩塘傥靶塘来看温砍吐湍逊路路露露炼
状态代码

成功
200 正常;请求已完成。
201 正常;紧接POST命令。
202 正常;已接受用于处理，但处理尚未完成。
203 正常;部分信息 — 返回的信息只是一部分。
204 正常;无响应 — 已接收请求，但不存在要回送的信息。
重定向
301 永久重定向 — 请求的数据具有新的位置且更改是永久的。
302 暂时重定向 — 请求的数据临时具有不同URI。
303 请参阅其它 — 可在另一URI下找到对请求的响应，且应使用 GET方法检索此响应。
304 未修改 — 未按预期修改文档。
305 使用代理 — 必须通过位置字段中提供的代理来访问请求的资源。
306 未使用 — 不再使用;保留此代码以便将来使用。
代码中的错误
400 错误请求 — 请求中有语法问题，或不能满足请求。
401 未授权 — 未授权客户机访问数据。
402 需要付款 — 表示计费系统已有效。
403 禁止— 即使有授权也不需要访问。
404 找不到—服务器找不到给予的资源;文档不存在。
406 不可接受 — 根据此请求中所发送的“接受”标题，此请求所标识的资源只能生成内容特征为“不可接受”的响应实体。
407 代理认证请求 — 客户机首先必须使用代理认证自身。
410 请求的网页不存在(永久);
415 介质类型不受支持 —服务器拒绝服务请求，因为不支持请求实体的格式。
500 内部错误 — 因为意外情况，服务器不能完成请求。
501 未执行 —服务器不支持请求的工具。
502 错误网关—服务器接收到来自上游服务器的无效响应。
503 无法获得服务 — 由于临时过载或维护，服务器无法处理请求。

问题解答

Baiduspider对一个网站服务器造成的访问压力如何？
答：Baiduspider会自动根据服务器的负载能力调节访问密度。在连续访问一段时间后，Baiduspider会暂停一会，以防止增大服务器的访问压力。所以在一般情况下，Baiduspider对您网站的服务器不会造成过大的压力。
为什么Baiduspider不停的抓取我的网站？
答：或许您的网站权重高或者对于您网站上新产生的或者持续、有规律更新的页面，Baiduspider会持续抓取。此外，您也可以检查网站访问日志中Baiduspider的访问是否正常，以防止有人恶意冒充Baiduspider来频繁抓取您的网站。 如果您发现Baiduspider非正常抓取您的网站，请反馈至，并请尽量给出Baiduspider对贵站的访问日志，以便于我们跟踪处理。
我不想我的网站被Baiduspider访问，我该怎么做？
答：Baiduspider遵守互联网robots协议。您可以利用robots.txt文件完全禁止Baiduspider访问您的网站，或者禁止Baiduspider访问您网站上的部分文件。 注意：禁止Baiduspider访问您的网站，将使您的网站上的网页，在百度搜索引擎以及所有百度提供搜索引擎服务的搜索引擎中无法被搜索到。
ps:关于robots.txt的写作方法，请参看我们的介绍：robots.txt写作方法
为什么我的网站已经加了robots.txt，还能在百度搜索出来？
答：因为搜索引擎索引数据库的更新需要时间。虽然Baiduspider已经停止访问您网站上的网页，但百度搜索引擎数据库中已经建立的网页索引信息，可能需要二至四周才会清除。 另外也请检查您的robots配置是否正确。
我希望我的网站内容被百度索引但不被保存快照，我该怎么做？
答：Baiduspider遵守互联网metarobots协议。您可以利用网页meta的设置，使百度显示只对该网页建索引，但并不在搜索结果中显示该网页的快照。
和robots的更新一样，因为搜索引擎索引数据库的更新需要时间，所以虽然您已经在网页中通过meta禁止了百度在搜索结果中显示该网页的快照，但百度搜索引擎数据库中如果已经建立了网页索引信息，可能需要二至四周才会在线上生效。
百度蜘蛛在robots.txt中的名字是什么？
答：“Baiduspider” 首字母B大写，其余为小写。
Baiduspider多长时间之后会重新抓取我的网页？
答：百度搜索引擎每周更新，网页视重要性有不同的更新率，频率在几天至一月之间，Baiduspider会重新访问和更新一个网页。
Baiduspider抓取造成的带宽堵塞？
答：Baiduspider的正常抓取并不会造成您网站的带宽堵塞，造成此现象可能是由于有人冒充baidu的spider恶意抓取。如果您发现有名为Baiduspider的agent抓取并且造成带宽堵塞，请尽快和我们联系。您可以将信息反馈至百度网页投诉中心，如果能够提供您网站该时段的访问日志将更加有利于我们的分析。

群发外链
对应名称
产品名称 对应user-agent
网页搜索 Baiduspider
无线搜索 Baiduspider
图片搜索 Baiduspider-image
视频搜索 Baiduspider-video
新闻搜索 Baiduspider-news
百度搜藏 Baiduspider-favo
百度联盟Baiduspider-cpro
竞价蜘蛛Baiduspider-sfkr

https://github.com/NeutronCloudBastion/wqitqd/commit/ef38d5f47fbda941282f9a8d9b02dadb75a240a3?/487=236
https://github.com/NeutronCloudBastion/wqitqd/commit/ef38d5f47fbda941282f9a8d9b02dadb75a240a3?/992=609
https://github.com/NeutronCloudBastion/wqitqd/commit/ef38d5f47fbda941282f9a8d9b02dadb75a240a3?/525=425
https://github.com/NeutronCloudBastion/wqitqd/commit/ef38d5f47fbda941282f9a8d9b02dadb75a240a3
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E7%88%86%E5%88%86-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F.md?/843=043
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E7%88%86%E5%88%86-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F.md?/758=536
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E7%88%86%E5%88%86-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F.md?/781=751
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E7%88%86%E5%88%86-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F.md?/388=011
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E7%88%86%E5%88%86-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F.md?/810=381
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E7%88%86%E5%88%86-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F.md
https://github.com/ornatepenguin/repo-bupvwfjm/commit/c01cff8aecfb7eaa993cd684e9d7218dd08a4998?/308=376
https://github.com/ornatepenguin/repo-bupvwfjm/commit/c01cff8aecfb7eaa993cd684e9d7218dd08a4998?/154=836
https://github.com/ornatepenguin/repo-bupvwfjm/commit/c01cff8aecfb7eaa993cd684e9d7218dd08a4998?/710=425
https://github.com/ornatepenguin/repo-bupvwfjm/commit/c01cff8aecfb7eaa993cd684e9d7218dd08a4998?/187=932
https://github.com/ornatepenguin/repo-bupvwfjm/commit/c01cff8aecfb7eaa993cd684e9d7218dd08a4998?/156=609
https://github.com/ornatepenguin/repo-bupvwfjm/commit/c01cff8aecfb7eaa993cd684e9d7218dd08a4998
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96-%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/618=854
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96-%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/887=243
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96-%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/669=998
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96-%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/221=114
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96-%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/090=937
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96-%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F.md
https://github.com/illcello/repo-rv2f6rr6/commit/62d79f16c320037088e80b19b678a9f7e6bb5edf?/725=558
https://github.com/illcello/repo-rv2f6rr6/commit/62d79f16c320037088e80b19b678a9f7e6bb5edf?/492=275
https://github.com/illcello/repo-rv2f6rr6/commit/62d79f16c320037088e80b19b678a9f7e6bb5edf?/409=825
https://github.com/illcello/repo-rv2f6rr6/commit/62d79f16c320037088e80b19b678a9f7e6bb5edf?/164=590
https://github.com/illcello/repo-rv2f6rr6/commit/62d79f16c320037088e80b19b678a9f7e6bb5edf?/270=598
https://github.com/illcello/repo-rv2f6rr6/commit/62d79f16c320037088e80b19b678a9f7e6bb5edf
https://github.com/illcello/repo-rv2f6rr6/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E8%A7%86%E9%A2%91-%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F.md?/592=169
https://github.com/illcello/repo-rv2f6rr6/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E8%A7%86%E9%A2%91-%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F.md?/770=932
https://github.com/illcello/repo-rv2f6rr6/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E8%A7%86%E9%A2%91-%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F.md?/332=821
https://github.com/illcello/repo-rv2f6rr6/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E8%A7%86%E9%A2%91-%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F.md?/114=831
https://github.com/illcello/repo-rv2f6rr6/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E8%A7%86%E9%A2%91-%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F.md?/347=481
https://github.com/illcello/repo-rv2f6rr6/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E8%A7%86%E9%A2%91-%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F.md
https://github.com/sugarydisast/repo-uvvof0zo/commit/9402db932f621381ded0f5b136513abd5602da95?/500=043
https://github.com/sugarydisast/repo-uvvof0zo/commit/9402db932f621381ded0f5b136513abd5602da95?/370=386
https://github.com/sugarydisast/repo-uvvof0zo/commit/9402db932f621381ded0f5b136513abd5602da95?/379=565
https://github.com/sugarydisast/repo-uvvof0zo/commit/9402db932f621381ded0f5b136513abd5602da95?/743=158
https://github.com/sugarydisast/repo-uvvof0zo/commit/9402db932f621381ded0f5b136513abd5602da95?/168=758
https://github.com/sugarydisast/repo-uvvof0zo/commit/9402db932f621381ded0f5b136513abd5602da95
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E5%A4%9A%E5%B0%91-%E8%B4%A2%E5%AF%8C%E7%84%A6%E7%82%B9.md?/403=603
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E5%A4%9A%E5%B0%91-%E8%B4%A2%E5%AF%8C%E7%84%A6%E7%82%B9.md?/043=947
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E5%A4%9A%E5%B0%91-%E8%B4%A2%E5%AF%8C%E7%84%A6%E7%82%B9.md?/501=070
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E5%A4%9A%E5%B0%91-%E8%B4%A2%E5%AF%8C%E7%84%A6%E7%82%B9.md?/823=153
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E5%A4%9A%E5%B0%91-%E8%B4%A2%E5%AF%8C%E7%84%A6%E7%82%B9.md?/482=164
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E5%A4%9A%E5%B0%91-%E8%B4%A2%E5%AF%8C%E7%84%A6%E7%82%B9.md
https://github.com/alarmingrat/repo-fbt55cvf/commit/f015708be8d34f597069c48388d6c6f1ec436e95?/619=004
https://github.com/alarmingrat/repo-fbt55cvf/commit/f015708be8d34f597069c48388d6c6f1ec436e95?/619=558
https://github.com/alarmingrat/repo-fbt55cvf/commit/f015708be8d34f597069c48388d6c6f1ec436e95?/225=265
https://github.com/alarmingrat/repo-fbt55cvf/commit/f015708be8d34f597069c48388d6c6f1ec436e95?/654=150
https://github.com/alarmingrat/repo-fbt55cvf/commit/f015708be8d34f597069c48388d6c6f1ec436e95?/754=496
https://github.com/alarmingrat/repo-fbt55cvf/commit/f015708be8d34f597069c48388d6c6f1ec436e95
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E6%98%AF%E4%BB%80%E4%B9%88-%E6%8A%95%E8%B5%84%E7%83%AD%E7%82%B9.md?/432=047
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E6%98%AF%E4%BB%80%E4%B9%88-%E6%8A%95%E8%B5%84%E7%83%AD%E7%82%B9.md?/549=443
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E6%98%AF%E4%BB%80%E4%B9%88-%E6%8A%95%E8%B5%84%E7%83%AD%E7%82%B9.md?/369=110
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E6%98%AF%E4%BB%80%E4%B9%88-%E6%8A%95%E8%B5%84%E7%83%AD%E7%82%B9.md?/489=586
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E6%98%AF%E4%BB%80%E4%B9%88-%E6%8A%95%E8%B5%84%E7%83%AD%E7%82%B9.md?/970=665
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E6%98%AF%E4%BB%80%E4%B9%88-%E6%8A%95%E8%B5%84%E7%83%AD%E7%82%B9.md
https://github.com/ChipAmbassadorPliers/dkngum/commit/ef7ab6d1f386a3d41053800914d2aef7a21bad89?/603=046
https://github.com/ChipAmbassadorPliers/dkngum/commit/ef7ab6d1f386a3d41053800914d2aef7a21bad89?/710=821
https://github.com/ChipAmbassadorPliers/dkngum/commit/ef7ab6d1f386a3d41053800914d2aef7a21bad89?/821=817
https://github.com/ChipAmbassadorPliers/dkngum/commit/ef7ab6d1f386a3d41053800914d2aef7a21bad89?/181=710
https://github.com/ChipAmbassadorPliers/dkngum/commit/ef7ab6d1f386a3d41053800914d2aef7a21bad89?/716=040
https://github.com/ChipAmbassadorPliers/dkngum/commit/ef7ab6d1f386a3d41053800914d2aef7a21bad89
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E5%9B%BE%E7%89%87-%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F.md?/940=506
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E5%9B%BE%E7%89%87-%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F.md?/977=886
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E5%9B%BE%E7%89%87-%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F.md?/685=322
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E5%9B%BE%E7%89%87-%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F.md?/292=043
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E5%9B%BE%E7%89%87-%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F.md?/091=169
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E5%9B%BE%E7%89%87-%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F.md
https://github.com/prestigiouswi/repo-dnd41ifi/commit/3a0854f373f78606cf95de62ab0cf0a33c7f931b?/607=932
https://github.com/prestigiouswi/repo-dnd41ifi/commit/3a0854f373f78606cf95de62ab0cf0a33c7f931b?/008=565
https://github.com/prestigiouswi/repo-dnd41ifi/commit/3a0854f373f78606cf95de62ab0cf0a33c7f931b?/153=743
https://github.com/prestigiouswi/repo-dnd41ifi/commit/3a0854f373f78606cf95de62ab0cf0a33c7f931b?/558=647
https://github.com/prestigiouswi/repo-dnd41ifi/commit/3a0854f373f78606cf95de62ab0cf0a33c7f931b?/962=275
https://github.com/prestigiouswi/repo-dnd41ifi/commit/3a0854f373f78606cf95de62ab0cf0a33c7f931b
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E7%85%A7%E7%89%87-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/592=609
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E7%85%A7%E7%89%87-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/364=114
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E7%85%A7%E7%89%87-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/800=181
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E7%85%A7%E7%89%87-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/370=370
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E7%85%A7%E7%89%87-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F.md?/981=276
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E5%A5%96%E7%85%A7%E7%89%87-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F.md
https://github.com/CoordinatePond/cgkpim/commit/cc92b51e43d85fdee02da4c49ac4d989643c5dc3?/754=497
https://github.com/CoordinatePond/cgkpim/commit/cc92b51e43d85fdee02da4c49ac4d989643c5dc3?/338=609
https://github.com/CoordinatePond/cgkpim/commit/cc92b51e43d85fdee02da4c49ac4d989643c5dc3?/776=154
https://github.com/CoordinatePond/cgkpim/commit/cc92b51e43d85fdee02da4c49ac4d989643c5dc3?/728=503
https://github.com/CoordinatePond/cgkpim/commit/cc92b51e43d85fdee02da4c49ac4d989643c5dc3?/881=053
https://github.com/CoordinatePond/cgkpim/commit/cc92b51e43d85fdee02da4c49ac4d989643c5dc3
https://github.com/CoordinatePond/cgkpim/blob/main/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88-%E7%9B%B4%E6%92%AD%E5%90%A7.md?/670=829
https://github.com/CoordinatePond/cgkpim/blob/main/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88-%E7%9B%B4%E6%92%AD%E5%90%A7.md?/592=043
https://github.com/CoordinatePond/cgkpim/blob/main/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88-%E7%9B%B4%E6%92%AD%E5%90%A7.md?/265=747
https://github.com/CoordinatePond/cgkpim/blob/main/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88-%E7%9B%B4%E6%92%AD%E5%90%A7.md?/158=005
https://github.com/CoordinatePond/cgkpim/blob/main/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88-%E7%9B%B4%E6%92%AD%E5%90%A7.md?/652=603
https://github.com/CoordinatePond/cgkpim/blob/main/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88-%E7%9B%B4%E6%92%AD%E5%90%A7.md
https://github.com/illcello/repo-rv2f6rr6/commit/6cdc6d9c6bc71b81f6530e21bb6b93f8898f89d1?/697=347
https://github.com/illcello/repo-rv2f6rr6/commit/6cdc6d9c6bc71b81f6530e21bb6b93f8898f89d1?/776=713
https://github.com/illcello/repo-rv2f6rr6/commit/6cdc6d9c6bc71b81f6530e21bb6b93f8898f89d1?/508=490
https://github.com/illcello/repo-rv2f6rr6/commit/6cdc6d9c6bc71b81f6530e21bb6b93f8898f89d1?/284=425
https://github.com/illcello/repo-rv2f6rr6/commit/6cdc6d9c6bc71b81f6530e21bb6b93f8898f89d1?/052=156
https://github.com/illcello/repo-rv2f6rr6/commit/6cdc6d9c6bc71b81f6530e21bb6b93f8898f89d1
https://github.com/illcello/repo-rv2f6rr6/blob/main/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%9C%B0%E5%9B%BE%E5%A4%9A%E5%B0%91%E5%80%8D-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md?/827=723
https://github.com/illcello/repo-rv2f6rr6/blob/main/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%9C%B0%E5%9B%BE%E5%A4%9A%E5%B0%91%E5%80%8D-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md?/489=354
https://github.com/illcello/repo-rv2f6rr6/blob/main/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%9C%B0%E5%9B%BE%E5%A4%9A%E5%B0%91%E5%80%8D-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md?/265=276
https://github.com/illcello/repo-rv2f6rr6/blob/main/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%9C%B0%E5%9B%BE%E5%A4%9A%E5%B0%91%E5%80%8D-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md?/503=669
https://github.com/illcello/repo-rv2f6rr6/blob/main/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%9C%B0%E5%9B%BE%E5%A4%9A%E5%B0%91%E5%80%8D-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md?/698=936
https://github.com/illcello/repo-rv2f6rr6/blob/main/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%9C%B0%E5%9B%BE%E5%A4%9A%E5%B0%91%E5%80%8D-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md
https://github.com/NeutronCloudBastion/wqitqd/commit/40bfc3afedbb061ec47d102ec5c7e5625bc52f58?/386=710
https://github.com/NeutronCloudBastion/wqitqd/commit/40bfc3afedbb061ec47d102ec5c7e5625bc52f58?/334=113
https://github.com/NeutronCloudBastion/wqitqd/commit/40bfc3afedbb061ec47d102ec5c7e5625bc52f58?/487=117
https://github.com/NeutronCloudBastion/wqitqd/commit/40bfc3afedbb061ec47d102ec5c7e5625bc52f58?/507=598
https://github.com/NeutronCloudBastion/wqitqd/commit/40bfc3afedbb061ec47d102ec5c7e5625bc52f58?/602=881
https://github.com/NeutronCloudBastion/wqitqd/commit/40bfc3afedbb061ec47d102ec5c7e5625bc52f58
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88%E8%AF%95%E7%8E%A9-%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F.md?/563=041
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88%E8%AF%95%E7%8E%A9-%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F.md?/487=591
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88%E8%AF%95%E7%8E%A9-%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F.md?/376=610
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88%E8%AF%95%E7%8E%A9-%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F.md?/606=820
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88%E8%AF%95%E7%8E%A9-%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F.md?/636=820
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88%E8%AF%95%E7%8E%A9-%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F.md
https://github.com/ornatepenguin/repo-bupvwfjm/commit/ce598fee5346acdfc791eff843048a99e9f4151a?/342=501
https://github.com/ornatepenguin/repo-bupvwfjm/commit/ce598fee5346acdfc791eff843048a99e9f4151a?/774=675
https://github.com/ornatepenguin/repo-bupvwfjm/commit/ce598fee5346acdfc791eff843048a99e9f4151a?/576=992
https://github.com/ornatepenguin/repo-bupvwfjm/commit/ce598fee5346acdfc791eff843048a99e9f4151a?/372=558
https://github.com/ornatepenguin/repo-bupvwfjm/commit/ce598fee5346acdfc791eff843048a99e9f4151a?/160=268
https://github.com/ornatepenguin/repo-bupvwfjm/commit/ce598fee5346acdfc791eff843048a99e9f4151a
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E6%8B%9B%E8%81%98.md?/834=334
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E6%8B%9B%E8%81%98.md?/111=225
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E6%8B%9B%E8%81%98.md?/883=336
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E6%8B%9B%E8%81%98.md?/276=165
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E6%8B%9B%E8%81%98.md?/903=532
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%8D%95%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E6%8B%9B%E8%81%98.md
https://github.com/sugarydisast/repo-uvvof0zo/commit/c4772474c4172876a966946c28f3aaa4c6dafdc3?/656=746
https://github.com/sugarydisast/repo-uvvof0zo/commit/c4772474c4172876a966946c28f3aaa4c6dafdc3?/291=268
https://github.com/sugarydisast/repo-uvvof0zo/commit/c4772474c4172876a966946c28f3aaa4c6dafdc3?/524=523
https://github.com/sugarydisast/repo-uvvof0zo/commit/c4772474c4172876a966946c28f3aaa4c6dafdc3?/480=190
https://github.com/sugarydisast/repo-uvvof0zo/commit/c4772474c4172876a966946c28f3aaa4c6dafdc3?/440=079
https://github.com/sugarydisast/repo-uvvof0zo/commit/c4772474c4172876a966946c28f3aaa4c6dafdc3
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%9A%E5%B0%91%E9%92%B1-%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F.md?/756=270
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%9A%E5%B0%91%E9%92%B1-%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F.md?/603=222
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%9A%E5%B0%91%E9%92%B1-%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F.md?/884=589
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%9A%E5%B0%91%E9%92%B1-%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F.md?/717=989
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%9A%E5%B0%91%E9%92%B1-%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F.md?/511=355
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%9A%E5%B0%91%E9%92%B1-%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F.md
https://github.com/alarmingrat/repo-fbt55cvf/commit/f301231f0c8decdcedb686af87ef86e5221b4fbd?/631=269
https://github.com/alarmingrat/repo-fbt55cvf/commit/f301231f0c8decdcedb686af87ef86e5221b4fbd?/897=943
https://github.com/alarmingrat/repo-fbt55cvf/commit/f301231f0c8decdcedb686af87ef86e5221b4fbd?/342=543
https://github.com/alarmingrat/repo-fbt55cvf/commit/f301231f0c8decdcedb686af87ef86e5221b4fbd?/265=665
https://github.com/alarmingrat/repo-fbt55cvf/commit/f301231f0c8decdcedb686af87ef86e5221b4fbd?/009=881
https://github.com/alarmingrat/repo-fbt55cvf/commit/f301231f0c8decdcedb686af87ef86e5221b4fbd
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%9A%E5%B0%91%E9%92%B1%E4%B8%80%E5%A5%97-%E4%B8%AD%E8%B4%A2%E8%B5%84%E8%AE%AF.md?/710=059
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%9A%E5%B0%91%E9%92%B1%E4%B8%80%E5%A5%97-%E4%B8%AD%E8%B4%A2%E8%B5%84%E8%AE%AF.md?/786=164
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%9A%E5%B0%91%E9%92%B1%E4%B8%80%E5%A5%97-%E4%B8%AD%E8%B4%A2%E8%B5%84%E8%AE%AF.md?/609=520
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%9A%E5%B0%91%E9%92%B1%E4%B8%80%E5%A5%97-%E4%B8%AD%E8%B4%A2%E8%B5%84%E8%AE%AF.md?/936=556
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%9A%E5%B0%91%E9%92%B1%E4%B8%80%E5%A5%97-%E4%B8%AD%E8%B4%A2%E8%B5%84%E8%AE%AF.md?/096=505
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%9A%E5%B0%91%E9%92%B1%E4%B8%80%E5%A5%97-%E4%B8%AD%E8%B4%A2%E8%B5%84%E8%AE%AF.md
https://github.com/prestigiouswi/repo-dnd41ifi/commit/ed215a2a646a27269a23cdffd494107970d2bc88?/725=389
https://github.com/prestigiouswi/repo-dnd41ifi/commit/ed215a2a646a27269a23cdffd494107970d2bc88?/225=710
https://github.com/prestigiouswi/repo-dnd41ifi/commit/ed215a2a646a27269a23cdffd494107970d2bc88?/332=934
https://github.com/prestigiouswi/repo-dnd41ifi/commit/ed215a2a646a27269a23cdffd494107970d2bc88?/031=376
https://github.com/prestigiouswi/repo-dnd41ifi/commit/ed215a2a646a27269a23cdffd494107970d2bc88?/942=657
https://github.com/prestigiouswi/repo-dnd41ifi/commit/ed215a2a646a27269a23cdffd494107970d2bc88
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%94%BB%E7%95%A5-%E8%B4%A2%E5%AF%8C%E5%9C%A8%E7%BA%BF.md?/262=614
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%94%BB%E7%95%A5-%E8%B4%A2%E5%AF%8C%E5%9C%A8%E7%BA%BF.md?/270=881
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%94%BB%E7%95%A5-%E8%B4%A2%E5%AF%8C%E5%9C%A8%E7%BA%BF.md?/727=747
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%94%BB%E7%95%A5-%E8%B4%A2%E5%AF%8C%E5%9C%A8%E7%BA%BF.md?/164=597
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%94%BB%E7%95%A5-%E8%B4%A2%E5%AF%8C%E5%9C%A8%E7%BA%BF.md?/970=992
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%94%BB%E7%95%A5-%E8%B4%A2%E5%AF%8C%E5%9C%A8%E7%BA%BF.md
https://github.com/CoordinatePond/cgkpim/commit/d9cddfed0dce8643dc0fe6341ebb09b7921c8b01?/221=775
https://github.com/CoordinatePond/cgkpim/commit/d9cddfed0dce8643dc0fe6341ebb09b7921c8b01?/114=003
https://github.com/CoordinatePond/cgkpim/commit/d9cddfed0dce8643dc0fe6341ebb09b7921c8b01?/503=025
https://github.com/CoordinatePond/cgkpim/commit/d9cddfed0dce8643dc0fe6341ebb09b7921c8b01?/484=504
https://github.com/CoordinatePond/cgkpim/commit/d9cddfed0dce8643dc0fe6341ebb09b7921c8b01?/332=076
https://github.com/CoordinatePond/cgkpim/commit/d9cddfed0dce8643dc0fe6341ebb09b7921c8b01
https://github.com/CoordinatePond/cgkpim/blob/main/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%AE%98%E7%BD%91%E7%89%88-%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F.md?/667=376
https://github.com/CoordinatePond/cgkpim/blob/main/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%AE%98%E7%BD%91%E7%89%88-%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F.md?/164=208
https://github.com/CoordinatePond/cgkpim/blob/main/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%AE%98%E7%BD%91%E7%89%88-%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F.md?/276=903
https://github.com/CoordinatePond/cgkpim/blob/main/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%AE%98%E7%BD%91%E7%89%88-%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F.md?/881=554
https://github.com/CoordinatePond/cgkpim/blob/main/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%AE%98%E7%BD%91%E7%89%88-%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F.md?/218=717
https://github.com/CoordinatePond/cgkpim/blob/main/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%AE%98%E7%BD%91%E7%89%88-%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F.md
https://github.com/ChipAmbassadorPliers/dkngum/commit/c7198aad0180efd38bde56c899f6a21331a5ff62?/889=158
https://github.com/ChipAmbassadorPliers/dkngum/commit/c7198aad0180efd38bde56c899f6a21331a5ff62?/265=603
https://github.com/ChipAmbassadorPliers/dkngum/commit/c7198aad0180efd38bde56c899f6a21331a5ff62?/921=550
https://github.com/ChipAmbassadorPliers/dkngum/commit/c7198aad0180efd38bde56c899f6a21331a5ff62?/609=047
https://github.com/ChipAmbassadorPliers/dkngum/commit/c7198aad0180efd38bde56c899f6a21331a5ff62?/899=592
https://github.com/ChipAmbassadorPliers/dkngum/commit/c7198aad0180efd38bde56c899f6a21331a5ff62
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%94%BE%E6%B0%B4%E6%97%B6%E9%97%B4-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md?/714=558
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%94%BE%E6%B0%B4%E6%97%B6%E9%97%B4-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md?/054=053
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%94%BE%E6%B0%B4%E6%97%B6%E9%97%B4-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md?/342=050
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%94%BE%E6%B0%B4%E6%97%B6%E9%97%B4-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md?/347=727
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%94%BE%E6%B0%B4%E6%97%B6%E9%97%B4-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md?/753=452
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%94%BE%E6%B0%B4%E6%97%B6%E9%97%B4-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md
https://github.com/illcello/repo-rv2f6rr6/commit/ae5fdd2b3499f3f083cd0d6da039d921ce99e0d3?/661=508
https://github.com/illcello/repo-rv2f6rr6/commit/ae5fdd2b3499f3f083cd0d6da039d921ce99e0d3?/375=523
https://github.com/illcello/repo-rv2f6rr6/commit/ae5fdd2b3499f3f083cd0d6da039d921ce99e0d3?/025=476
https://github.com/illcello/repo-rv2f6rr6/commit/ae5fdd2b3499f3f083cd0d6da039d921ce99e0d3?/821=492
https://github.com/illcello/repo-rv2f6rr6/commit/ae5fdd2b3499f3f083cd0d6da039d921ce99e0d3?/441=501
https://github.com/illcello/repo-rv2f6rr6/commit/ae5fdd2b3499f3f083cd0d6da039d921ce99e0d3
https://github.com/illcello/repo-rv2f6rr6/blob/main/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%8E%B7%E5%A5%96%E8%A7%86%E9%A2%91-%E6%B2%99%E7%89%B9%E8%B4%A2%E7%BB%8F.md?/487=821
https://github.com/illcello/repo-rv2f6rr6/blob/main/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%8E%B7%E5%A5%96%E8%A7%86%E9%A2%91-%E6%B2%99%E7%89%B9%E8%B4%A2%E7%BB%8F.md?/058=558
https://github.com/illcello/repo-rv2f6rr6/blob/main/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%8E%B7%E5%A5%96%E8%A7%86%E9%A2%91-%E6%B2%99%E7%89%B9%E8%B4%A2%E7%BB%8F.md?/163=770
https://github.com/illcello/repo-rv2f6rr6/blob/main/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%8E%B7%E5%A5%96%E8%A7%86%E9%A2%91-%E6%B2%99%E7%89%B9%E8%B4%A2%E7%BB%8F.md?/821=936
https://github.com/illcello/repo-rv2f6rr6/blob/main/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%8E%B7%E5%A5%96%E8%A7%86%E9%A2%91-%E6%B2%99%E7%89%B9%E8%B4%A2%E7%BB%8F.md?/985=052
https://github.com/illcello/repo-rv2f6rr6/blob/main/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%8E%B7%E5%A5%96%E8%A7%86%E9%A2%91-%E6%B2%99%E7%89%B9%E8%B4%A2%E7%BB%8F.md
https://github.com/NeutronCloudBastion/wqitqd/commit/c59a7380b03f9ebf2a3ffbb6d41c898814f3de5f?/967=821
https://github.com/NeutronCloudBastion/wqitqd/commit/c59a7380b03f9ebf2a3ffbb6d41c898814f3de5f?/058=111
https://github.com/NeutronCloudBastion/wqitqd/commit/c59a7380b03f9ebf2a3ffbb6d41c898814f3de5f?/181=000
https://github.com/NeutronCloudBastion/wqitqd/commit/c59a7380b03f9ebf2a3ffbb6d41c898814f3de5f?/525=492
https://github.com/NeutronCloudBastion/wqitqd/commit/c59a7380b03f9ebf2a3ffbb6d41c898814f3de5f?/170=070
https://github.com/NeutronCloudBastion/wqitqd/commit/c59a7380b03f9ebf2a3ffbb6d41c898814f3de5f
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%8A%80%E5%B7%A7-%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/592=636
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%8A%80%E5%B7%A7-%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/010=181
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%8A%80%E5%B7%A7-%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/298=103
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%8A%80%E5%B7%A7-%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/370=176
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%8A%80%E5%B7%A7-%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/056=345
https://github.com/NeutronCloudBastion/wqitqd/blob/main/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E6%8A%80%E5%B7%A7-%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md
https://github.com/RestBoatwright/pnbunq/commit/4f6f65686173081020819845cf29a1b776c4ad48?/776=386
https://github.com/RestBoatwright/pnbunq/commit/4f6f65686173081020819845cf29a1b776c4ad48?/054=865
https://github.com/RestBoatwright/pnbunq/commit/4f6f65686173081020819845cf29a1b776c4ad48?/009=508
https://github.com/RestBoatwright/pnbunq/commit/4f6f65686173081020819845cf29a1b776c4ad48?/332=497
https://github.com/RestBoatwright/pnbunq/commit/4f6f65686173081020819845cf29a1b776c4ad48?/263=419
https://github.com/RestBoatwright/pnbunq/commit/4f6f65686173081020819845cf29a1b776c4ad48
https://github.com/RestBoatwright/pnbunq/blob/main/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E7%88%86%E5%A5%96%E7%85%A7%E7%89%87-%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F.md?/254=610
https://github.com/RestBoatwright/pnbunq/blob/main/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E7%88%86%E5%A5%96%E7%85%A7%E7%89%87-%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F.md?/932=247
https://github.com/RestBoatwright/pnbunq/blob/main/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E7%88%86%E5%A5%96%E7%85%A7%E7%89%87-%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F.md?/001=821
https://github.com/RestBoatwright/pnbunq/blob/main/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E7%88%86%E5%A5%96%E7%85%A7%E7%89%87-%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F.md?/992=721
https://github.com/RestBoatwright/pnbunq/blob/main/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E7%88%86%E5%A5%96%E7%85%A7%E7%89%87-%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F.md?/971=376
https://github.com/RestBoatwright/pnbunq/blob/main/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E5%A4%A7%E7%88%86%E5%A5%96%E7%85%A7%E7%89%87-%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F.md
https://github.com/alarmingrat/repo-fbt55cvf/commit/a93e48319ae86d0b342dee07bc521ffe203f251c?/606=596
https://github.com/alarmingrat/repo-fbt55cvf/commit/a93e48319ae86d0b342dee07bc521ffe203f251c?/598=949
https://github.com/alarmingrat/repo-fbt55cvf/commit/a93e48319ae86d0b342dee07bc521ffe203f251c?/941=508
https://github.com/alarmingrat/repo-fbt55cvf/commit/a93e48319ae86d0b342dee07bc521ffe203f251c?/773=602
https://github.com/alarmingrat/repo-fbt55cvf/commit/a93e48319ae86d0b342dee07bc521ffe203f251c?/452=839
https://github.com/alarmingrat/repo-fbt55cvf/commit/a93e48319ae86d0b342dee07bc521ffe203f251c
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9-%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/370=831
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9-%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/500=598
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9-%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/720=164
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9-%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/875=823
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9-%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/947=825
https://github.com/alarmingrat/repo-fbt55cvf/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9-%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F.md
https://github.com/ornatepenguin/repo-bupvwfjm/commit/9c945400d1ce0aaf21eb32d4a886072da6b397de?/710=312
https://github.com/ornatepenguin/repo-bupvwfjm/commit/9c945400d1ce0aaf21eb32d4a886072da6b397de?/506=554
https://github.com/ornatepenguin/repo-bupvwfjm/commit/9c945400d1ce0aaf21eb32d4a886072da6b397de?/642=720
https://github.com/ornatepenguin/repo-bupvwfjm/commit/9c945400d1ce0aaf21eb32d4a886072da6b397de?/114=540
https://github.com/ornatepenguin/repo-bupvwfjm/commit/9c945400d1ce0aaf21eb32d4a886072da6b397de?/854=665
https://github.com/ornatepenguin/repo-bupvwfjm/commit/9c945400d1ce0aaf21eb32d4a886072da6b397de
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BD%AF%E4%BB%B6%E6%98%AF%E4%BB%80%E4%B9%88-%E7%BA%A2%E8%A2%96.md?/187=275
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BD%AF%E4%BB%B6%E6%98%AF%E4%BB%80%E4%B9%88-%E7%BA%A2%E8%A2%96.md?/998=821
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BD%AF%E4%BB%B6%E6%98%AF%E4%BB%80%E4%B9%88-%E7%BA%A2%E8%A2%96.md?/934=309
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BD%AF%E4%BB%B6%E6%98%AF%E4%BB%80%E4%B9%88-%E7%BA%A2%E8%A2%96.md?/111=919
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BD%AF%E4%BB%B6%E6%98%AF%E4%BB%80%E4%B9%88-%E7%BA%A2%E8%A2%96.md?/191=854
https://github.com/ornatepenguin/repo-bupvwfjm/blob/main/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BD%AF%E4%BB%B6%E6%98%AF%E4%BB%80%E4%B9%88-%E7%BA%A2%E8%A2%96.md
https://github.com/sugarydisast/repo-uvvof0zo/commit/d0bb25024a1c8fc4cdc4db7761c87f28c08efc7f?/487=976
https://github.com/sugarydisast/repo-uvvof0zo/commit/d0bb25024a1c8fc4cdc4db7761c87f28c08efc7f?/492=542
https://github.com/sugarydisast/repo-uvvof0zo/commit/d0bb25024a1c8fc4cdc4db7761c87f28c08efc7f?/542=483
https://github.com/sugarydisast/repo-uvvof0zo/commit/d0bb25024a1c8fc4cdc4db7761c87f28c08efc7f?/726=665
https://github.com/sugarydisast/repo-uvvof0zo/commit/d0bb25024a1c8fc4cdc4db7761c87f28c08efc7f?/158=386
https://github.com/sugarydisast/repo-uvvof0zo/commit/d0bb25024a1c8fc4cdc4db7761c87f28c08efc7f
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E6%A0%B7-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F.md?/265=309
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E6%A0%B7-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F.md?/214=043
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E6%A0%B7-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F.md?/225=167
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E6%A0%B7-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F.md?/015=998
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E6%A0%B7-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F.md?/214=609
https://github.com/sugarydisast/repo-uvvof0zo/blob/main/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E6%A0%B7-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F.md
https://github.com/prestigiouswi/repo-dnd41ifi/commit/abb3924d89ad76c6360cc300ab59eebbb4c3f581?/265=619
https://github.com/prestigiouswi/repo-dnd41ifi/commit/abb3924d89ad76c6360cc300ab59eebbb4c3f581?/837=465
https://github.com/prestigiouswi/repo-dnd41ifi/commit/abb3924d89ad76c6360cc300ab59eebbb4c3f581?/943=370
https://github.com/prestigiouswi/repo-dnd41ifi/commit/abb3924d89ad76c6360cc300ab59eebbb4c3f581?/047=932
https://github.com/prestigiouswi/repo-dnd41ifi/commit/abb3924d89ad76c6360cc300ab59eebbb4c3f581?/009=508
https://github.com/prestigiouswi/repo-dnd41ifi/commit/abb3924d89ad76c6360cc300ab59eebbb4c3f581
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9%E7%89%88-%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F.md?/834=609
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9%E7%89%88-%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F.md?/885=209
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9%E7%89%88-%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F.md?/112=110
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9%E7%89%88-%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F.md?/439=332
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9%E7%89%88-%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F.md?/535=835
https://github.com/prestigiouswi/repo-dnd41ifi/blob/main/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9%E7%89%88-%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F.md
https://github.com/ChipAmbassadorPliers/dkngum/commit/9f5218278de6ccc2a05875fe2d210f8aff43a01f?/624=940
https://github.com/ChipAmbassadorPliers/dkngum/commit/9f5218278de6ccc2a05875fe2d210f8aff43a01f?/154=187
https://github.com/ChipAmbassadorPliers/dkngum/commit/9f5218278de6ccc2a05875fe2d210f8aff43a01f?/598=058
https://github.com/ChipAmbassadorPliers/dkngum/commit/9f5218278de6ccc2a05875fe2d210f8aff43a01f?/151=143
https://github.com/ChipAmbassadorPliers/dkngum/commit/9f5218278de6ccc2a05875fe2d210f8aff43a01f?/487=436
https://github.com/ChipAmbassadorPliers/dkngum/commit/9f5218278de6ccc2a05875fe2d210f8aff43a01f
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BE%93%E4%BA%86-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/381=636
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BE%93%E4%BA%86-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/420=114
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BE%93%E4%BA%86-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/711=864
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BE%93%E4%BA%86-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/558=487
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BE%93%E4%BA%86-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/379=903
https://github.com/ChipAmbassadorPliers/dkngum/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%BE%93%E4%BA%86-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F.md
https://github.com/CoordinatePond/cgkpim/commit/bea0749c204532a012516df99a905ce656489a64?/047=665
https://github.com/CoordinatePond/cgkpim/commit/bea0749c204532a012516df99a905ce656489a64?/523=270
https://github.com/CoordinatePond/cgkpim/commit/bea0749c204532a012516df99a905ce656489a64?/492=854
https://github.com/CoordinatePond/cgkpim/commit/bea0749c204532a012516df99a905ce656489a64?/507=831
https://github.com/CoordinatePond/cgkpim/commit/bea0749c204532a012516df99a905ce656489a64?/619=592
https://github.com/CoordinatePond/cgkpim/commit/bea0749c204532a012516df99a905ce656489a64
https://github.com/CoordinatePond/cgkpim/blob/main/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9%E9%93%BE%E6%8E%A5-%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F.md?/720=936
https://github.com/CoordinatePond/cgkpim/blob/main/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9%E9%93%BE%E6%8E%A5-%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F.md?/710=169
https://github.com/CoordinatePond/cgkpim/blob/main/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9%E9%93%BE%E6%8E%A5-%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F.md?/628=509
https://github.com/CoordinatePond/cgkpim/blob/main/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9%E9%93%BE%E6%8E%A5-%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F.md?/274=370
https://github.com/CoordinatePond/cgkpim/blob/main/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9%E9%93%BE%E6%8E%A5-%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F.md?/826=718
https://github.com/CoordinatePond/cgkpim/blob/main/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5%3Apg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E8%AF%95%E7%8E%A9%E9%93%BE%E6%8E%A5-%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F.md
