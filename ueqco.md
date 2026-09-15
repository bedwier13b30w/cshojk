百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
谑瘴褂谓霸衣仓四吻副敖仓又拾尉

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

https://github.com/e44nf/nkliyn/commit/817f376776c796eec31278164629ce2f50a0c1d6
https://github.com/e44nf/nkliyn/blob/main/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E4%BC%98%E6%8D%B7%E6%95%B0%E7%A0%81.md
https://github.com/schowffer/nmghjj/commit/ebca9d4253695b414f71ef6924b8a6bfce382a7a
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md
https://github.com/ptushub/nohkiu/commit/73eb39e1d6aca8c83ffe20dfe8107e8dd14be112
https://github.com/ptushub/nohkiu/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C-%E6%90%9C%E7%8B%90%E6%91%84%E5%BD%B1.md
https://github.com/danielfachka/zyfplc/commit/02ee833ded7505f102088c505fce1e85a5f9ed80
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E4%B8%BB%E7%AE%A1-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/schowffer/nmghjj/commit/9b8df884b2f282647f4254c83c6d587c8ff22419
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9.md
https://github.com/ptushub/nohkiu/commit/593508675ea28dda1435b60485e29c8739323ecc
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md
https://github.com/danielfachka/zyfplc/commit/9c31a4740d35fd6cdc1ec671999513ba8acedecf
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1-360%E8%A7%86%E9%A2%91.md
https://github.com/e44nf/nkliyn/commit/9892e035848283121e4e573e3bad7924817e2622
https://github.com/e44nf/nkliyn/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md
https://github.com/schowffer/nmghjj/commit/a7224569471623e220bb939a746e93428ad268b7
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/ptushub/nohkiu/commit/9e40e2e0d825850f8cf1d5076b86beb0b25efbc2
https://github.com/ptushub/nohkiu/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/danielfachka/zyfplc/commit/d2664db39edde671f4bbafc61e972bd38b97623e
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5.md
https://github.com/schowffer/nmghjj/commit/af444a8335377c77fade9d09f2b18ba0e2ab6275
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/282f34aa3cd59e26e35c1146ef71219f9643e126
https://github.com/ptushub/nohkiu/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3%E7%90%86-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/990d7acfa59c56f5ea62e13339fe5a34e182d4f4
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA.md
https://github.com/e44nf/nkliyn/commit/ee0e408d92961db05c3d788b753d71a202571b98
https://github.com/e44nf/nkliyn/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md
https://github.com/schowffer/nmghjj/commit/8a1b580b0ab438ab848604ea311a5bcec463fdea
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5.md
https://github.com/danielfachka/zyfplc/commit/ae37cc3724baa1b6985b04982ac6089ae9e00d43
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/ptushub/nohkiu/commit/5a947c751b0ff24443c97a8f13d31af73227bb60
https://github.com/ptushub/nohkiu/blob/main/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/73da9e056f6d7d42f480500077df005f2c8a4821
https://github.com/e44nf/nkliyn/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md
https://github.com/schowffer/nmghjj/commit/827b1a25726a9fc21c705bdce827b285ed9bca15
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF.md
https://github.com/e44nf/nkliyn/commit/1aef24d64fa879d84ae9c1b927c4b29aea635dc9
https://github.com/e44nf/nkliyn/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/037b214688fcfd203a62a494c7803844acb6e2c2
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96.md
https://github.com/ptushub/nohkiu/commit/8924b1bd65bdb85e70e76fc726812912efd8b11c
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E7%99%BB%E9%99%86-36%E6%B0%AA%E6%B1%BD%E8%BD%A6.md
https://github.com/e44nf/nkliyn/commit/83953d238a7a77a6441757b02f082abee57f8f67
https://github.com/e44nf/nkliyn/blob/main/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md
https://github.com/schowffer/nmghjj/commit/63664757cee73b24fcbfe486120307f0f048725e
https://github.com/schowffer/nmghjj/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86%E4%B8%BB%E7%AE%A1-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/eea86d5d962da35c1c7957a39b787a29929c99eb
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/ptushub/nohkiu/commit/9df0bc7b5a92889537d476d666d40de5bf96a4de
https://github.com/ptushub/nohkiu/blob/main/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/bf047e56ef4369213a13fef410e08c4fdbdcafb3
https://github.com/e44nf/nkliyn/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md
https://github.com/danielfachka/zyfplc/commit/3d084cdd54ed615c894ad66446cda1df2120ca0c
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md
https://github.com/schowffer/nmghjj/commit/f5a66fc35e413cf6df95b811d04b7b3c845c65a7
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/ptushub/nohkiu/commit/839fc040a0e226491c8abc09e01783df700ea0e5
https://github.com/ptushub/nohkiu/blob/main/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md
https://github.com/danielfachka/zyfplc/commit/78839019fce363cc6488b3e1b5da9f421f009264
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md
https://github.com/e44nf/nkliyn/commit/cf53b033fa85de7cbdbd05dfca32e6d41350b14d
https://github.com/e44nf/nkliyn/blob/main/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/8724911f3f57df326fd7aa9bd6d599a1cf95715e
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4.md
https://github.com/ptushub/nohkiu/commit/ebfef1599d06deae12df6548be5618ce70b9c240
https://github.com/ptushub/nohkiu/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md
https://github.com/e44nf/nkliyn/commit/e64c11d0f4f0599adc82f75473325fe7feb8b27e
https://github.com/e44nf/nkliyn/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/1dc9f2714829afe493414d1df10d113476b11fe9
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/schowffer/nmghjj/commit/dc6caa4237341b5117017eb9ea79321a83598a4a
https://github.com/schowffer/nmghjj/blob/main/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/ptushub/nohkiu/commit/80be41b1393b75e4b4e576128175a59fe0286df5
https://github.com/ptushub/nohkiu/blob/main/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/e44nf/nkliyn/commit/1cd66c669e387bf15fda675ec385c05145cb9e21
https://github.com/e44nf/nkliyn/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB.md
https://github.com/danielfachka/zyfplc/commit/8536868e6b56833726f369a45957bec5936cb450
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/43830d8c481fb4e613f1caaf232aa31100f34de0
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/c6b244540bdf3d3e20ba52588e93252f34747eec
https://github.com/e44nf/nkliyn/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/ptushub/nohkiu/commit/b88c06494869f7641a3f05db0d891c1c4d63fa08
https://github.com/ptushub/nohkiu/blob/main/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5.md
https://github.com/danielfachka/zyfplc/commit/b47696b37e28ec18e82648df59d5772571be47aa
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88.md
https://github.com/schowffer/nmghjj/commit/3360f1ddc29e33a381c8e5e812814d8d7311b6fd
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C-%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88.md
https://github.com/e44nf/nkliyn/commit/76229e5559fd9abe946e70de47123d9bfab9dcf9
https://github.com/e44nf/nkliyn/blob/main/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB.md
https://github.com/danielfachka/zyfplc/commit/4e49e26ea1774d58e330e9e6f1a3e7225830a889
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/31f9bc44e59075e6fd875f6bc08fe97197c7a2a5
https://github.com/ptushub/nohkiu/blob/main/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C-%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/6260c4ecca1703863dc6b3ce53fc0bba5512f64f
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%BC%80%E6%88%B7-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/810fbefbdc075bfd8477e244e103c6e1a6a8b8bf
https://github.com/e44nf/nkliyn/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5.md
https://github.com/danielfachka/zyfplc/commit/8c6ff89bd8c80f2be92dfbc714ebd4f6683ebaf5
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/ptushub/nohkiu/commit/4129c6f4a30001f458d4e4fe412fff98afdd6286
https://github.com/ptushub/nohkiu/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E4%B8%BB%E7%AE%A1-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/e44nf/nkliyn/commit/61d1279b89cb5e8175ca4e5704cf61ffbda6f6b5
https://github.com/e44nf/nkliyn/blob/main/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3%E7%90%86-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/schowffer/nmghjj/commit/516fb385fb5080599c932ce0dc99821c5159645d
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md
https://github.com/danielfachka/zyfplc/commit/3628af8982fe5cf4a0e64b4191846cf387425d5f
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md
https://github.com/ptushub/nohkiu/commit/5746f13edcd38dd1c64ca60dc4fac434262fae5e
https://github.com/ptushub/nohkiu/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E7%99%BB%E9%99%86-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md
https://github.com/schowffer/nmghjj/commit/92305ebc0eec26e186c7984b1f4c70675eddc24f
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86%E4%B8%BB%E7%AE%A1-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/e44nf/nkliyn/commit/419a62c4fcee3bdbe7f282d98b65238c25255a7e
https://github.com/e44nf/nkliyn/blob/main/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/bc9313be4ea97401dce40f96933b4c458d2d6b2a
https://github.com/ptushub/nohkiu/blob/main/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md
https://github.com/danielfachka/zyfplc/commit/39ed24b502ed247053febc482258d26ca5dd7a54
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/c64d476492e0eed7d1599e25e6c612c9d26cc813
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md
https://github.com/e44nf/nkliyn/commit/a499e933bdbcef96395a374531b4bbbbcdb62843
https://github.com/e44nf/nkliyn/blob/main/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md
https://github.com/kulkaye/xiinuu/commit/052e9c955aadab49daad5549ade29d29131b7959
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/ptushub/nohkiu/commit/875b7d7db22fce8f4415d58aa27c9e6e7a352e45
https://github.com/ptushub/nohkiu/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md
https://github.com/danielfachka/zyfplc/commit/2d96ce162188f888490bf7078a304d4d648187af
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8.md
https://github.com/schowffer/nmghjj/commit/930779a9cd779b891268ea87f903cc311e3a38b3
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8.md
https://github.com/danielfachka/zyfplc/commit/fae2c769d310fb118c0c6f1f511fb32551b311bb
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md
https://github.com/schowffer/nmghjj/commit/8d66424b650d1f9855ee6ebdcb507d98ca683f72
https://github.com/schowffer/nmghjj/blob/main/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C-%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86.md
https://github.com/ptushub/nohkiu/commit/7ce6beadf405e7d81dc0f93c592988ff18aef1ab
https://github.com/ptushub/nohkiu/blob/main/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C-%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0.md
https://github.com/danielfachka/zyfplc/commit/329df11a6c5663d4fc392ea1f35b6ada05b42bb5
https://github.com/danielfachka/zyfplc/blob/main/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%BC%80%E6%88%B7-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/ptushub/nohkiu/commit/3daef2a4715da36393d570cf53b880f83a9d0788
https://github.com/ptushub/nohkiu/blob/main/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/schowffer/nmghjj/commit/28c3aa2f93c7d7abc5cfd9c293592a488b023caa
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/69d013cae7fd8ef16cf9bb382e769f4116b21cce
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md
https://github.com/danielfachka/zyfplc/commit/b626f975632a60e0b4a260deefdf9d52a8359d31
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E4%B8%BB%E7%AE%A1-%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95.md
https://github.com/schowffer/nmghjj/commit/c6e41b18de30e44ffa6b8bb60a831b6d63961aca
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3%E7%90%86-360%E5%8E%86%E5%8F%B2.md
https://github.com/ptushub/nohkiu/commit/07b969b4c52e6991aa5543e884aedd6ea3686f89
https://github.com/ptushub/nohkiu/blob/main/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1-%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4.md
https://github.com/danielfachka/zyfplc/commit/c81728f37e191feb845b2d1c570dfc90724c503d
https://github.com/danielfachka/zyfplc/blob/main/2026%E9%A6%96%E8%A6%81%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md
https://github.com/schowffer/nmghjj/commit/e7076d8dff218e46dfa4f2035fa3b0df0bbe1a7e
https://github.com/schowffer/nmghjj/blob/main/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E7%99%BB%E9%99%86-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/ptushub/nohkiu/commit/5f0628584b488cd41d73809dc0f4a1df6629e486
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/danielfachka/zyfplc/commit/b356cd4c304ec505b506106ffaa91a3815694235
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86%E4%B8%BB%E7%AE%A1-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/ptushub/nohkiu/commit/5c819bb1c56ba225032dc7c1db6f6439b577db76
https://github.com/ptushub/nohkiu/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/29e83eb311b6620cd63eb8de0cdc62b7ac011cfe
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md
https://github.com/ptushub/nohkiu/commit/adf9d19d02c4d34f107b71cd496b63751997fde8
https://github.com/ptushub/nohkiu/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/81b20249be7dba7407afe67b5d1f90ba1ea4eb1c
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/danielfachka/zyfplc/commit/55b1b2af1827855e5e7b3ed60e04d9075accf9fb
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/9eca698cecbabe5398cb2fe5007c821ec21e9084
https://github.com/ptushub/nohkiu/blob/main/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90.md
https://github.com/danielfachka/zyfplc/commit/89b9b0cd702cb7af4de600dd5ce30af25eca95ed
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85-360%E8%A7%86%E9%A2%91.md
https://github.com/ptushub/nohkiu/commit/80487372d8b986670c859004eecb5416b6fb89e0
https://github.com/ptushub/nohkiu/blob/main/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/731bcfafe0104fc3e4a4df8717ac57bc5db88318
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85-%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90.md
https://github.com/ptushub/nohkiu/commit/901df4543594f280a2d262c85c59ca73ea4923b4
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md
https://github.com/danielfachka/zyfplc/commit/1c8fd4826c902c8bb350728d951b8508c061e992
https://github.com/danielfachka/zyfplc/blob/main/2026%E9%A6%96%E8%A6%81%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/057cad75f31e7a01eb0f3525f5532e47598bf3df
https://github.com/ptushub/nohkiu/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C-%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88.md
https://github.com/danielfachka/zyfplc/commit/bd5a5a48696287bd544fde54b54dcf07440bb45e
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95-%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4.md
https://github.com/danielfachka/zyfplc/commit/4284d28e83ef8f42e09ea5e99aba8b22e84041c3
https://github.com/danielfachka/zyfplc/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB.md
https://github.com/ptushub/nohkiu/commit/499ef548bc652759e4983280cdccee5ee35d71a3
https://github.com/ptushub/nohkiu/blob/main/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%BC%80%E6%88%B7-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/danielfachka/zyfplc/commit/c27e6154de11972a800daffd1e02cffa89e033fc
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/6160d0c0ee1ea7e40a83d8838d57a9e9be933f15
https://github.com/ptushub/nohkiu/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/66139bd60eeac4e38aa8187337b7bc413f6280df
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C-%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88.md
https://github.com/danielfachka/zyfplc/commit/0d3547f73b0a5ae1b3b26e218f2d273b8da989d7
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E4%B8%BB%E7%AE%A1-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
