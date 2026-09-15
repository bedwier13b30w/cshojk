百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
墩悄下焙善净躺戮呛残坎链来侥及

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

https://github.com/danielfachka/zyfplc/commit/2a9829ab438e3fc98e02594efe29e951f5de9f87
https://github.com/danielfachka/zyfplc/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3Apg%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%20-%E4%BC%98%E6%8D%B7%E6%95%B0%E7%A0%81.md
https://github.com/ptushub/nohkiu/commit/2873673cdd40341edb3d918b8c8c77b716d5a692
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90app%20-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF.md
https://github.com/sourux23/eufvji/commit/6337d38ff07396de105fddf525fe41138a8f4eb9
https://github.com/sourux23/eufvji/blob/main/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C%3Apg%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md
https://github.com/kulkaye/xiinuu/commit/1ae339770575aeda0f01324e6d6daefbac58b97a
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3Apg%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/1b365bc969a03bd3c1cd5dbee0c9fb6736b2f418
https://github.com/ryukaura/kityhe/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3Apg%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-36%E6%B0%AA%E6%B1%BD%E8%BD%A6.md
https://github.com/constiang-s/xzjjce/commit/ad80cba5f9500b5c7f19199e545fd0747933a540
https://github.com/constiang-s/xzjjce/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3Apg%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5.md
https://github.com/mustakuritsar07/rkngzy/commit/8ed146df40458b94e2061940d086117cafde47c1
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3Apg%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/e44nf/nkliyn/commit/03582d710b8cec1741af8d65b49b8db9af1ca41b
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3Apg%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/19ffa12e04925e430cd86ddd9179a54d978e92f9
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C%3Apg%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/enognagu/lpvade/commit/bd831bfbe088c4287eaa93149203204e284b18b1
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3Apg%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/ptushub/nohkiu/commit/bd8cd3fb9b24ac504cb5f02aa5ed01c39cf65b6e
https://github.com/ptushub/nohkiu/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E4%BC%98%E6%8D%B7%E6%95%B0%E7%A0%81.md
https://github.com/danielfachka/zyfplc/commit/6ec7cd556d0db081c153deb1adeb4a609210c54d
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%20-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md
https://github.com/sourux23/eufvji/commit/08e128ec7fcacbc016374a061d8093223653fba4
https://github.com/sourux23/eufvji/blob/main/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/kulkaye/xiinuu/commit/e8a4a322ed298a7ea59701622f0daf71f5e2bf0b
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md
https://github.com/ryukaura/kityhe/commit/a5e6484660374f790cc1a76affa5c79772922dfb
https://github.com/ryukaura/kityhe/blob/main/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/constiang-s/xzjjce/commit/dc19e2a222b5465c60f280e4c9fd2524f61186d0
https://github.com/constiang-s/xzjjce/blob/main/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md
https://github.com/e44nf/nkliyn/commit/d1d6bb28ec6e09c6ef7ae35d51b1383514e93668
https://github.com/e44nf/nkliyn/blob/main/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-36%E6%B0%AA%E6%B1%BD%E8%BD%A6.md
https://github.com/schowffer/nmghjj/commit/0b4979db1f3538bfbc52173e0093779e94c72922
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/ptushub/nohkiu/commit/fe6b89506b0b351529d05d064966e452e68dbe26
https://github.com/ptushub/nohkiu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/a099f07a2da1961706d9680d4900f6ccf6008496
https://github.com/enognagu/lpvade/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/sourux23/eufvji/commit/c76c62c3e06109168946df719a23ca68358c7da1
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md
https://github.com/mustakuritsar07/rkngzy/commit/64e27f8632a6ef6390886af7d9debdffcf079171
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-36%E6%B0%AA%E6%B1%BD%E8%BD%A6.md
https://github.com/kulkaye/xiinuu/commit/c46763c1d9de419e04455f8477bffd7f71e27544
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88.md
https://github.com/ryukaura/kityhe/commit/035500bfd4cb932ccf104521ee456fa2dd6fc834
https://github.com/ryukaura/kityhe/blob/main/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/e44nf/nkliyn/commit/2c6e80b36ec881a08932fe076510e10e915ec02c
https://github.com/e44nf/nkliyn/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88.md
https://github.com/constiang-s/xzjjce/commit/b8444fba8c2cfd5ae1a5a0705ce0bdccfff6c731
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95.md
https://github.com/danielfachka/zyfplc/commit/eaffb8bf7da5394370424e472eafc7b31e8b3836
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3Apg%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%20-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/ptushub/nohkiu/commit/8f67863d986e2b4de3f18406839698c161e35d43
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md
https://github.com/sourux23/eufvji/commit/eca8c002ed293e042944a9e32e7390846e3f3ccf
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-36%E6%B0%AA%E6%B1%BD%E8%BD%A6.md
https://github.com/schowffer/nmghjj/commit/3460f58743dfb4fd367d11a497475578379539fb
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md
https://github.com/mustakuritsar07/rkngzy/commit/cf9e84ab654503fc26d26a0c4f22c01da803bd18
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/kulkaye/xiinuu/commit/94745ff47458294d30ab2ed8021642fef32f7538
https://github.com/kulkaye/xiinuu/blob/main/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92%3ANG28%E5%A8%B1%E4%B9%90%20-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md
https://github.com/e44nf/nkliyn/commit/374eae6a9ae60eec2ef88434daed34716fcfce6e
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3ANG28%E5%A8%B1%E4%B9%90app%20-%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8.md
https://github.com/enognagu/lpvade/commit/82a453be55ce92bacad1173c2a9f40cdc9b6820a
https://github.com/enognagu/lpvade/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E5%8D%97%E5%AE%AB%E9%9B%86%E5%9B%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/mustakuritsar07/rkngzy/commit/e24e986ba9510563d3bf430d7537fdea03d9735d
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3ANG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/schowffer/nmghjj/commit/5c209da0a167dc6dd146c7c2388b6bf7e66f083d
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4%3ANG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5.md
https://github.com/ptushub/nohkiu/commit/a9b655a02fb33dd6189f60d4ebf0b6e4dfdfadc0
https://github.com/ptushub/nohkiu/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3ANG28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/a5c57e1642268730fe12db6982198af989d2e549
https://github.com/kulkaye/xiinuu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3ANG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/danielfachka/zyfplc/commit/ac944ae58a844e2e57773077eafd929903ccad1b
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF%3ANG28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/constiang-s/xzjjce/commit/102e15e02018ab2c94bf1a29cccc00bba9e8eb8e
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3ANG28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-360%E9%80%9A%E4%BF%A1.md
https://github.com/enognagu/lpvade/commit/4053cd223f996e04319d94a75aa5ab73dc6bf82f
https://github.com/enognagu/lpvade/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3ApgNG28%E5%A8%B1%E4%B9%90%20-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md
https://github.com/e44nf/nkliyn/commit/54f29edb7e62fefc0b4fca0557a33a64e69b6063
https://github.com/e44nf/nkliyn/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F%3ANG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/ryukaura/kityhe/commit/d41b4779c583582a50775d1c9b69bfd0ee89f0af
https://github.com/ryukaura/kityhe/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3ANG28%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95.md
https://github.com/mustakuritsar07/rkngzy/commit/394109b734c71948fad69669e6e6ead2098e30f0
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3ApgNG28%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md
https://github.com/ptushub/nohkiu/commit/61e878e7ed9487faf5dc8db71b7d2f350a62750f
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3ApgNG28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88.md
https://github.com/sourux23/eufvji/commit/d23994f9fc68ec59185fb6778abc42e4ea47a757
https://github.com/sourux23/eufvji/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3ANG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-360%E8%A7%86%E9%A2%91.md
https://github.com/schowffer/nmghjj/commit/a29060a6eae66bc39f29a1fc3253c3f532c36890
https://github.com/schowffer/nmghjj/blob/main/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3ApgNG28%E5%A8%B1%E4%B9%90app%20-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md
https://github.com/kulkaye/xiinuu/commit/15eea9f3cea293eb405976901f84786b705f6c3f
https://github.com/kulkaye/xiinuu/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3ApgNG28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/constiang-s/xzjjce/commit/f617d2804ede99728f143dac7d1316eb16bbceac
https://github.com/constiang-s/xzjjce/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3ApgNG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/enognagu/lpvade/commit/a1efbeb57102ff21dab81aa7cf07c63507c6e6c2
https://github.com/enognagu/lpvade/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3ApgNG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/290da75709103cfaf2054ea976ba6d83451aed72
https://github.com/e44nf/nkliyn/blob/main/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C%3ApgNG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md
https://github.com/danielfachka/zyfplc/commit/bc21817a5936e310d49b54a70c857ee74c879c4d
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3ApgNG28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md
https://github.com/schowffer/nmghjj/commit/bfd15328ab60c9137a1b8f0ad279b4f664d994aa
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9%3ANG28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/93f58b24bb184da5cfd5d390bbb9d19a0d1641ab
https://github.com/sourux23/eufvji/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3ANG28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/3f803405c8e525b129ab2d7ea0411e9afc429c1a
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC%3ApgNG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md
https://github.com/ryukaura/kityhe/commit/dc4644c72a39946305a684317a3cdba813aad066
https://github.com/ryukaura/kityhe/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3ApgNG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md
https://github.com/ptushub/nohkiu/commit/d6370128478467845be51dbab0058bc6ad6c93d2
https://github.com/ptushub/nohkiu/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3ANG28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%20-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md
https://github.com/constiang-s/xzjjce/commit/46dbc08f3e881f81a9063d2e719c79c070bb6e79
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3ANG28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/91cd486d480795868005315e72ba76caea802856
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3ANG28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md
https://github.com/enognagu/lpvade/commit/b838467bb851a4106d780c20eae25ba2a5b899d5
https://github.com/enognagu/lpvade/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3ANG28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/e44nf/nkliyn/commit/9d5511603db827cd5ee2717096a8060e91769820
https://github.com/e44nf/nkliyn/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3ANG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md
https://github.com/danielfachka/zyfplc/commit/e599b54eebeadfc41906dd452b6bc73f8936833c
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3ANG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/3e455c9fd191b5d67eda98eb73d4021dcb4879b4
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3ANG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB.md
https://github.com/mustakuritsar07/rkngzy/commit/a2acfce0ddbb0c51194f9717ced8a4b8d689e499
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3ANG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/847ff016e3134ee663a0c2190b4cff50788294be
https://github.com/sourux23/eufvji/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3ANG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/ryukaura/kityhe/commit/44c3db0b4caef3c2674e6e167e5fce8622ab5631
https://github.com/ryukaura/kityhe/blob/main/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0%3ApgNG28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md
https://github.com/kulkaye/xiinuu/commit/01de0198ddc8fa1a5d01428cc8f3e0216300d34b
https://github.com/kulkaye/xiinuu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3ANG28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96.md
https://github.com/ptushub/nohkiu/commit/d67d7f4365cae49c0010e09e48bcc42b652ee1d0
https://github.com/ptushub/nohkiu/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3ANG28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/constiang-s/xzjjce/commit/396357f551efd74a9b9393d5c505d9b1ac8cba7c
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3ANG28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-360%E5%8E%86%E5%8F%B2.md
https://github.com/enognagu/lpvade/commit/217613d0822af7fac3d58430550d3f7d0bd41904
https://github.com/enognagu/lpvade/blob/main/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3ANG28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/fa36c63689cfea003b298228b46310e360b3b722
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3ANG28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md
https://github.com/schowffer/nmghjj/commit/2c13fe18f04d9916266aec9fb9c2336f4c58e0c0
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3ANG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/kulkaye/xiinuu/commit/aa5ad710766e400a45d43b2585ffc79e758d9f3c
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E9%97%AE%E9%BC%8E%E5%A8%B1%E4%B9%90-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/danielfachka/zyfplc/commit/bbabd8950974545b90222dca39fb1be5e97e1880
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3ANG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md
https://github.com/mustakuritsar07/rkngzy/commit/dae3e4a9dfb3196f8bfd3195df326dd7da21d55e
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3ANG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-36%E6%B0%AA%E6%B1%BD%E8%BD%A6.md
https://github.com/sourux23/eufvji/commit/ff81e33991967899ed6086aaba2f0d0221c2e77f
https://github.com/sourux23/eufvji/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3ANG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/ryukaura/kityhe/commit/e428f0ad2184f65f7d30e6ef0ade4f414b38d553
https://github.com/ryukaura/kityhe/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3ANG28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/ptushub/nohkiu/commit/650cdabc4a6adbf087c5c806b3a123e4f43e5aea
https://github.com/ptushub/nohkiu/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85-%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/72999fc3d7768354b5203a42f894c321d9de94ab
https://github.com/enognagu/lpvade/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E5%8D%97%E5%AE%AB%E5%9B%BD%E9%99%85-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/07810a0a2a4d4f57b432c27d423c89df2753c0be
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E5%8D%97%E5%AE%AB%E5%A8%B1%E4%B9%90-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md
https://github.com/e44nf/nkliyn/commit/0eb54483d4d6d3c5acbdf9bea939a125c1f8dbab
https://github.com/e44nf/nkliyn/blob/main/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C%3Ac7%E5%A8%B1%E4%B9%90-%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F.md
https://github.com/schowffer/nmghjj/commit/53c675c45de4cf0960c24bc9ecc7c22c338968cf
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A%3Ac7%E5%9B%BD%E9%99%85-360%E9%80%9A%E4%BF%A1.md
https://github.com/kulkaye/xiinuu/commit/17e34c044e4082b4b68b040d5cd23a01b0449016
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E5%A3%B9%E5%8F%B7%E5%A8%B1%E4%B9%90-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/enognagu/lpvade/commit/3b24cb325d929c2e0791eb4f605d8100460277f3
https://github.com/enognagu/lpvade/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/sourux23/eufvji/commit/011ca18be9a93e07658e6942edfe783f105b3a54
https://github.com/sourux23/eufvji/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%20-360%E9%80%9A%E4%BF%A1.md
https://github.com/ptushub/nohkiu/commit/8026586f40ad21f1a05607aa01f8fb152dad0b6c
https://github.com/ptushub/nohkiu/blob/main/2026%E9%A6%96%E8%A6%81%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E5%A4%9A%E5%A4%9A28-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/mustakuritsar07/rkngzy/commit/868aeb10af3a2e43d5ced079ef5466399e9515e5
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E4%BA%BF%E4%B8%8728-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md
https://github.com/constiang-s/xzjjce/commit/50300e32e527c74619128179ad3fb648359e23c0
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md
https://github.com/danielfachka/zyfplc/commit/b4875aa16bee2286e14f8a1c6c3c7dfb26bfd5fa
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E5%A3%B9%E5%8F%B7%E5%9B%BD%E9%99%85-%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE.md
https://github.com/e44nf/nkliyn/commit/7a7d1037e2bde4d000a1c734da93230b2314bd44
https://github.com/e44nf/nkliyn/blob/main/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA.md
https://github.com/schowffer/nmghjj/commit/6700a77c9cd4f440d4febc185f40a95208a3b274
https://github.com/schowffer/nmghjj/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md
https://github.com/ryukaura/kityhe/commit/636da11e38e97da1173c17e3da21f5c54a9f1d16
https://github.com/ryukaura/kityhe/blob/main/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/27cc63d9d973093498821d248b839810ba151a11
https://github.com/enognagu/lpvade/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/92e1f480eb6aab7f96816937855160260c2da3af
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/ptushub/nohkiu/commit/060f0d06b95d2f6491460e264cd5a09697077880
https://github.com/ptushub/nohkiu/blob/main/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A28%E5%9C%88%E5%9B%BD%E9%99%85-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/89ed4e8a0259992cb9bd51b1a243d27495535440
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0%3A%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md
https://github.com/e44nf/nkliyn/commit/b2d1941fd006ad10e73d8800e63230cae3042219
https://github.com/e44nf/nkliyn/blob/main/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90-%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/4c65806c12022a7ada3e6b90f9b44dfc26cb0f7d
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F%3A%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/f1799dc4b6e4ebdab9570d36d22feeebf196b17b
https://github.com/danielfachka/zyfplc/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/ryukaura/kityhe/commit/90dacfc7685279e8e63cf44450e9bdbfbf6c9804
https://github.com/ryukaura/kityhe/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/4f3814dad90f3abcd6bbf152192785d9ea1d3ba7
https://github.com/enognagu/lpvade/blob/main/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/1f711ab3895a9a6cbaf5b02ec0a8be77c19553ed
https://github.com/sourux23/eufvji/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A28%E5%9C%88%E5%9B%BD%E9%99%85-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/constiang-s/xzjjce/commit/7b105df6b0529ae32f462b019a222c2e8c82bff8
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E7%BA%B5%E6%A8%AA%E5%A8%B1%E4%B9%90-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md
https://github.com/kulkaye/xiinuu/commit/7de55c65eb78cce5cbfa311db82bd86eb18d6171
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md
https://github.com/schowffer/nmghjj/commit/2256647c53aac9b5d641c1bd6b8945756ceeb7d3
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA%3A%E9%BE%99%E8%85%BE%E5%A8%B1%E4%B9%90-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/82ca72c66eadf0fe17514e6af0161bb35c62b5a3
https://github.com/ptushub/nohkiu/blob/main/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86.md
https://github.com/mustakuritsar07/rkngzy/commit/18b0802e3f231555dfc1b32facce1da60f48d620
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E9%9D%9E%E5%87%A1%E5%9B%BD%E9%99%85-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/7de644d2f47445946c06b185320bbc8e9419bbde
https://github.com/e44nf/nkliyn/blob/main/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5%3A%E9%9D%9E%E5%87%A1%E5%A8%B1%E4%B9%90-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/danielfachka/zyfplc/commit/52e511c07531b9b41bfc3dbfedc4915e71ca9d87
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB.md
https://github.com/ryukaura/kityhe/commit/2e4a92eb9f5d4353b700754c716370481dbfa1f0
https://github.com/ryukaura/kityhe/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%A8%B1%E4%B9%90-%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96.md
https://github.com/enognagu/lpvade/commit/abaa9798ef43a63cce7b9e0f7cc4c2ccba0ad3d9
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E9%97%AE%E9%BC%8E%E5%A4%A7%E8%88%9E%E5%8F%B0-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md
https://github.com/sourux23/eufvji/commit/3f66f26aa5ae5dc57c6b16669e57abb178916b69
https://github.com/sourux23/eufvji/blob/main/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5%3A%E8%BF%99%E4%B8%8A%E9%9D%A2%E9%83%BD%E6%98%AF%E4%B8%BB%E5%85%B3%E9%94%AE%E8%AF%8D%E8%87%B3%E5%B0%91%E5%8F%91300%E6%9D%A1-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md
https://github.com/schowffer/nmghjj/commit/8c99e81fb630629b3194e77a08f622475b47892f
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3Apg%E9%97%AE%E9%BC%8E%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md
https://github.com/kulkaye/xiinuu/commit/df2754cbb5bfa7d6adf982460349dd92d3aa063f
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0%3Apg%E9%97%AE%E9%BC%8E%E5%A4%A7%E8%88%9E%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA.md
https://github.com/ptushub/nohkiu/commit/245276a279526fa674a8d23a4ba9943105187642
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3Apg%E9%97%AE%E9%BC%8E%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/ba66e640d53a6fe8cdfc76eebd45b75f5079cf05
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3Apg%E9%97%AE%E9%BC%8E%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88.md
https://github.com/constiang-s/xzjjce/commit/c529f1f96fe36b8df9ae1a12cdd8e0d75a667636
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E4%B8%8B%E9%9D%A2%E6%98%AF%E6%89%80%E6%9C%89%E5%89%AF%E8%AF%8D%E5%8F%91700%E6%9D%A1%20%20-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md
https://github.com/ryukaura/kityhe/commit/15628c06cd453714c3659df8278db413811709a7
https://github.com/ryukaura/kityhe/blob/main/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F%3Apg%E9%97%AE%E9%BC%8E%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md
https://github.com/sourux23/eufvji/commit/3921f474835e3bff6860a60a049bf202b78519e8
https://github.com/sourux23/eufvji/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3Apg%E9%97%AE%E9%BC%8E%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md
https://github.com/danielfachka/zyfplc/commit/2f925702b75efb3386d185e12e7d678f2b36687b
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3Apg%E9%97%AE%E9%BC%8E%E5%B9%B3%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/e44nf/nkliyn/commit/d662cf16b2970d0685833a6423d4426971e75d4d
https://github.com/e44nf/nkliyn/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3Apg%E9%97%AE%E9%BC%8E%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3%E9%93%BE%E6%8E%A5-360%E9%80%9A%E4%BF%A1.md
https://github.com/enognagu/lpvade/commit/67be8724cd50e9581292cd1dc0286bc3f2144df3
https://github.com/enognagu/lpvade/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3Apg%E9%97%AE%E9%BC%8E%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md
https://github.com/constiang-s/xzjjce/commit/4adfb8b774968678c2f81338fa279b663e5f93b3
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E9%97%AE%E9%BC%8Eapp%E6%B3%A8%E5%86%8C-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/81ca4831c476771ce4e04cd65b2caefbc446dfed
https://github.com/kulkaye/xiinuu/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E9%97%AE%E9%BC%8E%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md
