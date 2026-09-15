百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
缮衫挠勇堂傩乘敦酱紫孔刺庇乘焚

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

https://github.com/danielfachka/zyfplc/commit/6fe6f44e2f7cb9f26360392f5f9f2323f9c36aaa
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4.md
https://github.com/ptushub/nohkiu/commit/2c01559f2b31b27dee7a9a872efd5937d9df6556
https://github.com/ptushub/nohkiu/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-360%E9%80%9A%E4%BF%A1.md
https://github.com/danielfachka/zyfplc/commit/50e5f79bbc1133c9e365f728fce5f6fcb10a46b1
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/ptushub/nohkiu/commit/8fbbe721518c533ccb0b65e4584a3a7b12db541d
https://github.com/ptushub/nohkiu/blob/main/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/a47a2febcf20b255e32699a236f33ccd84d20fcd
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/ptushub/nohkiu/commit/d6245ba8a3c1f51b916b9576a3a8da14a4cf0d9f
https://github.com/ptushub/nohkiu/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/kulkaye/xiinuu/commit/cdab1926ee37408ff9196669159ba94eab294880
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-360%E8%A7%86%E9%A2%91.md
https://github.com/danielfachka/zyfplc/commit/daf142d51bc49f386092f9bd5f6768c8469fbc00
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/ptushub/nohkiu/commit/a28548b92dc0b94d81b3220b70e9bcd4d06138bb
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86.md
https://github.com/danielfachka/zyfplc/commit/a5ab305b0c77df428da04e5b304a2fe153f17a03
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md
https://github.com/ptushub/nohkiu/commit/874b067e604a79db6d7b1e6cdba5fb7cbaf8d551
https://github.com/ptushub/nohkiu/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/danielfachka/zyfplc/commit/97eba73243ed6b73e8d27504f98e39d1d05fdf2c
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md
https://github.com/ptushub/nohkiu/commit/678779069ec1939a553c45141bb4136109697951
https://github.com/ptushub/nohkiu/blob/main/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%BC%80%E6%88%B7-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/danielfachka/zyfplc/commit/e884e6fca88a484658b6053f31d06282e0d4fb69
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/ptushub/nohkiu/commit/8041a5cd1b4e12914de5e73dd9a25498fd017932
https://github.com/ptushub/nohkiu/blob/main/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md
https://github.com/danielfachka/zyfplc/commit/3bdd879cc775d3e188e2b90e9ca189f13a7f1b11
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C-360%E8%A7%86%E9%A2%91.md
https://github.com/kulkaye/xiinuu/commit/3c86bebb33e276ed0fdccb77c81109498eaa3e58
https://github.com/kulkaye/xiinuu/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5.md
https://github.com/danielfachka/zyfplc/commit/508e1a85bfec5d6b88908d0ccadabd8489561ed0
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95.md
https://github.com/ptushub/nohkiu/commit/cd9a85181a1aef5f307c0c0a4029ff4e5c35f22d
https://github.com/ptushub/nohkiu/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E4%B8%BB%E7%AE%A1-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md
https://github.com/danielfachka/zyfplc/commit/d9ac3ec14e5785b8d76ca4ea8e1adee7d36c373c
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md
https://github.com/ptushub/nohkiu/commit/a0c231403a158d3640f84f915ab5c376fa8c66b7
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1-360%E8%A7%86%E9%A2%91.md
https://github.com/danielfachka/zyfplc/commit/eb81a93518fd203e54df0c32dfe77a9f4e12e55f
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB.md
https://github.com/ptushub/nohkiu/commit/cf099074936935d6885b08674f35b98ba0bfc6ef
https://github.com/ptushub/nohkiu/blob/main/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/d57d2902a7cce9f5beaaada213cf8da66fd1ebdb
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/danielfachka/zyfplc/commit/a283d58481d81b912cedc9293eb139c800e373d9
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8.md
https://github.com/ptushub/nohkiu/commit/7e78c56f1cfc2888012ecfb994169d4d0d367c79
https://github.com/ptushub/nohkiu/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/6da6ece6cf3c3ee688444f63f2775978c9095529
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3%E7%90%86-%E4%BC%98%E6%8D%B7%E6%95%B0%E7%A0%81.md
https://github.com/ptushub/nohkiu/commit/443e5d52f2fc29ae520e1ca8932990c1b4d062c5
https://github.com/ptushub/nohkiu/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9.md
https://github.com/danielfachka/zyfplc/commit/86b96f89aef6c73975d7fa634c6d7ce8bb2da9a7
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/kulkaye/xiinuu/commit/c50dcef34b99f5b4851ae37b0ec3b9cb3879dc13
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md
https://github.com/ptushub/nohkiu/commit/7be8e5f7ca84c86edb89a4c467792d7e8e3bb1d8
https://github.com/ptushub/nohkiu/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/danielfachka/zyfplc/commit/19b1bb0db5ff78445214714d03b5a6b0d6b743c4
https://github.com/danielfachka/zyfplc/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/ptushub/nohkiu/commit/558de66dacfeafae869127688494cedb7222f577
https://github.com/ptushub/nohkiu/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/danielfachka/zyfplc/commit/24e92a05b16fcd74ecf6e3eaf5fdb8a4416d7a0b
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/ptushub/nohkiu/commit/0f0714e96b2205febca5f31a4eaddb50a3594ce8
https://github.com/ptushub/nohkiu/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E7%99%BB%E9%99%86-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/a010a09dee4f5ea0f2e423a384f14229cfff4a77
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/danielfachka/zyfplc/commit/0ecfc1f938ca6b025993038e66ec1545d1e4c5c0
https://github.com/danielfachka/zyfplc/blob/main/2026%E9%A6%96%E8%A6%81%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/c3c5f1c0429771f54bf4312d0a5096c33351ff81
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90.md
https://github.com/danielfachka/zyfplc/commit/5c07a61cdb284b31f659e52187ad879bde3b6924
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/94056e9be7910a91387fcecae1364cbc98048749
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md
https://github.com/danielfachka/zyfplc/commit/9f8ed7ef7a684c5fd50003d613dd588105fd8e6b
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1-%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9.md
https://github.com/danielfachka/zyfplc/commit/66027b421882583916d34e5dc31e453c9e1ca30d
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86.md
https://github.com/danielfachka/zyfplc/commit/0bffc52ab76b8f0bbeddd9412319c4daf2a4d92a
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/danielfachka/zyfplc/commit/19e86e028fea19634f30e295c8d95dc5e73e93bb
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF.md
https://github.com/danielfachka/zyfplc/commit/433cbca02ed20339401028509902e0c105340789
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/danielfachka/zyfplc/commit/c116b378bd05640f2022ad9135451f26df6fe1c0
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/danielfachka/zyfplc/commit/deda3c24c501aa6eed2b10dee3ac51db0f68498d
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md
https://github.com/danielfachka/zyfplc/commit/1dcf02a39836090b69a211249c66c517ac630f32
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md
https://github.com/danielfachka/zyfplc/commit/e142b585aa4acf943fd26229473a768172c88fc9
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/danielfachka/zyfplc/commit/ab3398232f591a609e6348768145ef8671c2e9cf
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md
https://github.com/danielfachka/zyfplc/commit/a3ace19c4f1091379c5d9b58e8c821bf7a47d19a
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/e88b2b154331d87609a336d802f637bdabe6b816
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/e7c70016cf5fe4c6940396a2bf180f4e03e72c3e
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/0e5d46f99981afa50697eecc66a1ce4453f902c8
https://github.com/kulkaye/xiinuu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md
https://github.com/kulkaye/xiinuu/commit/394f26f8744b210f234c83c93b5fb66809b37740
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/kulkaye/xiinuu/commit/e23cade5fab7a2cd9627ef8e7ffecc38b5c3fbea
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md
https://github.com/kulkaye/xiinuu/commit/1ec21fc113c6143817dbd912e76c4ccd5fac1b05
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md
https://github.com/kulkaye/xiinuu/commit/f932b03f86dfb2b0d90da8dd100e0d5b786b64a5
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/dbdbddb831d3d31f0a2e0a97d4f019c87a0f103e
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E4%B8%BB%E7%AE%A1-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/95a62b0f487d212b53a8068d91cea0ccd214da8c
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md
https://github.com/kulkaye/xiinuu/commit/83c3eae764b661496814de83dad572113555247e
https://github.com/kulkaye/xiinuu/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8.md
https://github.com/kulkaye/xiinuu/commit/bd641dc62b35e15d9dd39e5403c389fb157f45bb
https://github.com/kulkaye/xiinuu/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/kulkaye/xiinuu/commit/c0c63a983eaa944d8c88aad27c2a7f5220dc24df
https://github.com/kulkaye/xiinuu/blob/main/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1-%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81.md
https://github.com/kulkaye/xiinuu/commit/02635e12ea86fc89212443ba506c7a68fa9e0758
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-360%E5%8E%86%E5%8F%B2.md
https://github.com/kulkaye/xiinuu/commit/d12c05eca17c8eaa67d5b856e62527450bbcf156
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-360%E8%A7%86%E9%A2%91.md
https://github.com/kulkaye/xiinuu/commit/c7009a01ba84c984bc6023f909549b9213f6be02
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/kulkaye/xiinuu/commit/ff78ee7e3ae9b7237caec81b80fdc00899308642
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md
https://github.com/kulkaye/xiinuu/commit/8c3d652e7c7aae15fbdd7aba8ff401adfe55bf39
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/kulkaye/xiinuu/commit/628cd2f6f4fb280eceb7b26874becf26628a0748
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3%E7%90%86-%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86.md
https://github.com/kulkaye/xiinuu/commit/9b8f3c00dceea947693081d9ea28380d3ae1fd1b
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/kulkaye/xiinuu/commit/90df573604743712c3f68f1699fb10ade0969cbf
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md
https://github.com/kulkaye/xiinuu/commit/2a43aa96bbeb90e6bbc877f87933f38eb2b86485
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/kulkaye/xiinuu/commit/c4acf3b5d30e35ddf2c7ba944b7cbf8253ad91f2
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md
https://github.com/kulkaye/xiinuu/commit/a6a01ea0c01a56916642f771232e3935e1c6e46d
https://github.com/kulkaye/xiinuu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C-360%E8%A7%86%E9%A2%91.md
https://github.com/kulkaye/xiinuu/commit/20410516bab8c4d6bdaffea8927efcf8519412e7
https://github.com/kulkaye/xiinuu/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA.md
https://github.com/kulkaye/xiinuu/commit/8fd3ffa370aa778a78b50c0cf0c9f5d1236573ff
https://github.com/kulkaye/xiinuu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/e3375aee81e9bca1e8434d787393b8e3b2f1e64e
https://github.com/kulkaye/xiinuu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E7%99%BB%E9%99%86-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md
https://github.com/kulkaye/xiinuu/commit/2ddbb4ad3f8cb5c862c0e4e7ab998cb4e940322c
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md
https://github.com/kulkaye/xiinuu/commit/bd90776aa35b2fa902096ccb1a9d0f7e49bdabb6
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86%E4%B8%BB%E7%AE%A1-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md
https://github.com/kulkaye/xiinuu/commit/bcf01d61e609904fc12985a8cbfa29e7aecfb4e7
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/kulkaye/xiinuu/commit/a8a3b7eef6ba7f9139ff990c8ebf8e2e1eca9c4c
https://github.com/kulkaye/xiinuu/blob/main/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/kulkaye/xiinuu/commit/5137e1bd0db40a10d11e9c66831a7cc3d8adde41
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/kulkaye/xiinuu/commit/bab347683069bf64e11455ab160ac7f822ec71bc
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/kulkaye/xiinuu/commit/08e89e55b217956afa7313ae359a695cda532266
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/abfd39f6894d6c6294b05ac7e1c66be78a81866d
https://github.com/kulkaye/xiinuu/blob/main/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1-%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81.md
https://github.com/kulkaye/xiinuu/commit/8d1108adae1cd8322eaeed90d85617c2426035ae
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md
https://github.com/kulkaye/xiinuu/commit/1555a1c93ce623566794e659267a6ebfac610204
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/kulkaye/xiinuu/commit/a14e1886e78b7a90d3e27dfba51da9c668918912
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4.md
https://github.com/kulkaye/xiinuu/commit/76368446124468f79217221de027f4bc08313ee5
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/kulkaye/xiinuu/commit/c286e90777bd9268a30466e4127cd1c926feb321
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/kulkaye/xiinuu/commit/fd890b243c5aa557d0e5dd85d07a317497c99bf3
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/79ce8a114a1e99d4999a7c23af02294a415d6f6c
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md
https://github.com/kulkaye/xiinuu/commit/e27df16e996f8bb0bce710b87e617539ac0c9b5c
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md
https://github.com/kulkaye/xiinuu/commit/769618f3ae49d349e537b76cdb99eb7c092807f5
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95.md
https://github.com/kulkaye/xiinuu/commit/5640f2a7f3f6293b09c8f7db7d6fc51b8769980b
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/aea115dc2fad0bf0eee1f9ca02a018a06e61e5ea
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9.md
https://github.com/kulkaye/xiinuu/commit/54659bca0deb603735ef8b47172b3aeed8a34aff
https://github.com/kulkaye/xiinuu/blob/main/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86.md
https://github.com/kulkaye/xiinuu/commit/f494856827b319f49973ee19f5197f58e0698a44
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/kulkaye/xiinuu/commit/13283b7588d35b04c2d02eec1aebc1913b8d3fc7
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/kulkaye/xiinuu/commit/ffff05117a00a44dde315653a6b55e467d6a3389
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
