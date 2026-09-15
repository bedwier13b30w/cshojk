百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
慷胀蔷铀蕴啄啥壬煤延邻吵敦费映

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

https://github.com/e44nf/nkliyn/commit/673e9747abcc6719f6b6bb18c6e1a17658692880
https://github.com/e44nf/nkliyn/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/1bd3f58c1024ae86b2022275e29d7ed3522448fc
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/schowffer/nmghjj/commit/d5c78787d21e6f41c27a03b0d0f5723498f019df
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88.md
https://github.com/ptushub/nohkiu/commit/eadabc8fd8be2bf9caa5c79be7461557b9c6a0ef
https://github.com/ptushub/nohkiu/blob/main/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/e44nf/nkliyn/commit/dfc9c784d5d887d3674c34ccb2d707ef98b78283
https://github.com/e44nf/nkliyn/blob/main/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md
https://github.com/danielfachka/zyfplc/commit/2ffddf36b9f1561477da249098f39e96400b1125
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8.md
https://github.com/ptushub/nohkiu/commit/4baf427e15773116d57db377744a47f6bafc6de1
https://github.com/ptushub/nohkiu/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/1371d5795810382cc85dc412aba8dbe53cfaed94
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/e44nf/nkliyn/commit/828a1c891271707abde23aa44da448dc8d016afd
https://github.com/e44nf/nkliyn/blob/main/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md
https://github.com/danielfachka/zyfplc/commit/6271ea0c6db9d1b8d78c6b9735b434c409a5ca18
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/b904b2674841f0ed6cedf004e1a235def5bc0187
https://github.com/ptushub/nohkiu/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md
https://github.com/schowffer/nmghjj/commit/5c973c3bd5fe68f6f31ef5169f199f7b541a3753
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%BC%80%E6%88%B7-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/e44nf/nkliyn/commit/577a39f200694c13af3ae9a0c651165942321b7a
https://github.com/e44nf/nkliyn/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/danielfachka/zyfplc/commit/e0a56d2b105b39059f031c642ea87cc8f264044b
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/schowffer/nmghjj/commit/b3edc5e0bbccae6a97cf0b00d5104daa4290443e
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E4%B8%BB%E7%AE%A1-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/ptushub/nohkiu/commit/529b336c7a92dbda3e2d976034b77cbabc4c1414
https://github.com/ptushub/nohkiu/blob/main/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/d388f36bfe9fd8ae1e26c54f97f1650d70277fbf
https://github.com/e44nf/nkliyn/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/84d24a89eb6f40ec837b4d118f81734f0123019c
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/schowffer/nmghjj/commit/3388136f6e71fe083d73620146d70b5a6927e083
https://github.com/schowffer/nmghjj/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md
https://github.com/e44nf/nkliyn/commit/6b1cf3b833237237c47a0bc55b1c9f07bc50788a
https://github.com/e44nf/nkliyn/blob/main/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/ptushub/nohkiu/commit/8c5cf9c6337872c49b326e008287b7480f98e0c9
https://github.com/ptushub/nohkiu/blob/main/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1-%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86.md
https://github.com/danielfachka/zyfplc/commit/da4b7758f91d6a0e3135169b5afb51997fc6299e
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/e44nf/nkliyn/commit/da83c61fbd53d891abdab1c47ed5d1babea600f7
https://github.com/e44nf/nkliyn/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-360%E9%80%9A%E4%BF%A1.md
https://github.com/danielfachka/zyfplc/commit/72cd76b2e9246f77c3795e49a21955ea4a14a09f
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3%E7%90%86-360%E8%A7%86%E9%A2%91.md
https://github.com/schowffer/nmghjj/commit/bcdd0969d0409e565975c53e3a703338be3e1890
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md
https://github.com/ptushub/nohkiu/commit/a907ed9d84a2ca3043dd98c0500ae31129ffcb11
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md
https://github.com/danielfachka/zyfplc/commit/c06b9b6c97d2b27122483da3cc2c37cd64dcace2
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/e44nf/nkliyn/commit/2858bc46e4af404d233d11f0a4591d5b753a203f
https://github.com/e44nf/nkliyn/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB.md
https://github.com/schowffer/nmghjj/commit/d2ad20487e212f0795721b5f85a21f1ac63296fc
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96.md
https://github.com/ptushub/nohkiu/commit/065f9c40af22ce1ed42b05d62708ec9a644696b4
https://github.com/ptushub/nohkiu/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/e44nf/nkliyn/commit/d473ccdb2124e33f5cdb8444f5a298a0740c6d30
https://github.com/e44nf/nkliyn/blob/main/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md
https://github.com/danielfachka/zyfplc/commit/f3d71f33ef9ad263f1ce712b0e13341eb3f47739
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/7a76d488c17f8d27c3d47afae108ec741fb54a99
https://github.com/schowffer/nmghjj/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/479129252e518abf63f96bc764eab8857044e4bc
https://github.com/ptushub/nohkiu/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E7%99%BB%E9%99%86-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/danielfachka/zyfplc/commit/5b2aa28a9e082596c9504d13d769e96c9827d4a6
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86%E4%B8%BB%E7%AE%A1-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/bec979e16176f1db077363f0ffe7bdbbe07ea75d
https://github.com/e44nf/nkliyn/blob/main/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/schowffer/nmghjj/commit/f4633f77c29625baa3c97ed5378bc7a38faf88d4
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/e44nf/nkliyn/commit/9f0c056b3b32233677fb2b6713b7c721328a40a5
https://github.com/e44nf/nkliyn/blob/main/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/danielfachka/zyfplc/commit/080e8690f8d1f27af35c5a04a19a7515284ad024
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95.md
https://github.com/ptushub/nohkiu/commit/a0c0c8c513af70ed63805f37fb98e830a4a3770c
https://github.com/ptushub/nohkiu/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md
https://github.com/schowffer/nmghjj/commit/6591db34be97e09841cf9d44146d05e739b4b18f
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/e44nf/nkliyn/commit/94f1f5c63af5ca22743bd58d75c48349cdb9ac6e
https://github.com/e44nf/nkliyn/blob/main/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/danielfachka/zyfplc/commit/581583a3d67affdfc129ec53a3d4b62d065ba1cd
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/ptushub/nohkiu/commit/71e4494ab3c9ca2ec6ec719e30437c0c9df41ed0
https://github.com/ptushub/nohkiu/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/schowffer/nmghjj/commit/21f9c07125e345e10509fd65de9dfda1b832897c
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB.md
https://github.com/e44nf/nkliyn/commit/25e49bd42e87dcb299eb20c59eded52cd6fa27b7
https://github.com/e44nf/nkliyn/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/4bcdb34f8fe1c0ed3c378a0e3ab1306d453312dd
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/ptushub/nohkiu/commit/39b6e7a57ea46b2f975a2c7c09b2adc877cacfe6
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/a6ce61e8397a31bfed92a625e1178ffea267f2c0
https://github.com/e44nf/nkliyn/blob/main/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/schowffer/nmghjj/commit/21f6e2f658d30ce2d881457f93f8fd74fcf4f43b
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md
https://github.com/danielfachka/zyfplc/commit/76e09416e5daecb81fad0cfd1441f696bebade14
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md
https://github.com/e44nf/nkliyn/commit/77f869ba30780961efccc5dc80f1c9ede36e8854
https://github.com/e44nf/nkliyn/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md
https://github.com/ptushub/nohkiu/commit/4cf8ad4675636c095e909683cadfa1c44919db1a
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%BF%85%E5%BA%94.md
https://github.com/danielfachka/zyfplc/commit/aefa16d638210dd5c1ad45a306c4c8c80ac4cd3b
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB.md
https://github.com/schowffer/nmghjj/commit/7bcaf1b12997fa77663fce85709a6f9183c92087
https://github.com/schowffer/nmghjj/blob/main/2026%E9%A6%96%E8%A6%81%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/e44nf/nkliyn/commit/b7705d8a26c277422f360154b18b34c2b6a99fe2
https://github.com/e44nf/nkliyn/blob/main/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/ptushub/nohkiu/commit/b483d524428dbc140311368d2a82c27eaadaf48a
https://github.com/ptushub/nohkiu/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/danielfachka/zyfplc/commit/e12c2dee20f2031c7f7199a32eb9b6310ea70b1a
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md
https://github.com/schowffer/nmghjj/commit/0988b63416ffd069fde0dbf4986f0384e8288246
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5.md
https://github.com/e44nf/nkliyn/commit/c7665ee6b40bc6863511089145a5e9ed46e75a5c
https://github.com/e44nf/nkliyn/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md
https://github.com/ptushub/nohkiu/commit/e7ce13b4ee954904b66c4cb598456d9019630099
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/77f5e5069eaabf1a7e3b09517c326be3dbd7ce8a
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%BC%80%E6%88%B7-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md
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
