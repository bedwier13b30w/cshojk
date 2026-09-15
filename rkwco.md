百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
讯敢勇禄缓袄诳蓉涸轿磊共系矩烈

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

https://github.com/constiang-s/xzjjce/commit/74424a33fa58d9589eea21a148e1727ac920cadb
https://github.com/constiang-s/xzjjce/blob/main/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3A%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BC%98%E6%8D%B7%E6%95%B0%E7%A0%81.md
https://github.com/sourux23/eufvji/commit/61ac135f45464560ca613075231be97895b1da13
https://github.com/sourux23/eufvji/blob/main/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99%3A%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/e44nf/nkliyn/commit/0bceb1fd67d5a35f6f5fa10d37af9ab6efa1a717
https://github.com/e44nf/nkliyn/blob/main/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/enognagu/lpvade/commit/8492b2c910ccc189f06aafac075f6f453c51064d
https://github.com/enognagu/lpvade/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/mustakuritsar07/rkngzy/commit/6e6abfeab7da959eb16319d2058a5cb564be05c3
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5.md
https://github.com/ryukaura/kityhe/commit/d918d89538510db9df687b2444232884484188f5
https://github.com/ryukaura/kityhe/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/ptushub/nohkiu/commit/36d8e1b64e2fb0a58aeb6cc6553be899915cf579
https://github.com/ptushub/nohkiu/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81.md
https://github.com/kulkaye/xiinuu/commit/0493273c54453b0c63aae28c52683eb0cf87d487
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/schowffer/nmghjj/commit/1d6bcc3713ed6b22931cf1de401a6181eb4fc522
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3Apg%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%20-%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86.md
https://github.com/sourux23/eufvji/commit/35182d8301b3745b708e5d106ab7c25991c021c7
https://github.com/sourux23/eufvji/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/constiang-s/xzjjce/commit/83c1e6e2d22ac59cdb74731391f8c0e19c16623b
https://github.com/constiang-s/xzjjce/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/danielfachka/zyfplc/commit/8ffa8b139fa15a013dd07996c5cb2d08d7ade1e7
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/e44nf/nkliyn/commit/4a65ba53d897f445e6d34eba82fcd39828fc3de1
https://github.com/e44nf/nkliyn/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81.md
https://github.com/enognagu/lpvade/commit/1e74baae24bf1f04f7695716565ee3dea04423d1
https://github.com/enognagu/lpvade/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/ptushub/nohkiu/commit/abd0c908eb9291ee3c4e86c4f62155f4d6fc733f
https://github.com/ptushub/nohkiu/blob/main/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md
https://github.com/kulkaye/xiinuu/commit/c15a8b3362630c0c07d6a4800828d0e3ed74206d
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-360%E8%A7%86%E9%A2%91.md
https://github.com/mustakuritsar07/rkngzy/commit/06fff3260c69982b8f48d822ec6ec0e0c1e9694f
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/ryukaura/kityhe/commit/c8cda1d0ad285ebdec39183a3362643224b4021f
https://github.com/ryukaura/kityhe/blob/main/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md
https://github.com/schowffer/nmghjj/commit/2a1379251f905d2da98e7ebe254732a77a3245c4
https://github.com/schowffer/nmghjj/blob/main/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0-%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4.md
https://github.com/sourux23/eufvji/commit/43bddc9c52a5434bcc6e295316ed4061bec8b039
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3Apg%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/constiang-s/xzjjce/commit/040203ba589574cc80f72bfbfc70f3617126bee5
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3Apg%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA.md
https://github.com/danielfachka/zyfplc/commit/5c9a6eea508648cbd7d7eac7327a6894ba25fdfe
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/a3d3b70f0daeba5e8a64b3d98de7805ee9073d75
https://github.com/e44nf/nkliyn/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3Apg%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-36%E6%B0%AA%E6%B1%BD%E8%BD%A6.md
https://github.com/enognagu/lpvade/commit/af2252dbd18f2756653762c7b2c6e82f266cf884
https://github.com/enognagu/lpvade/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3Apg%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3%E9%93%BE%E6%8E%A5-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md
https://github.com/kulkaye/xiinuu/commit/38d2c0cf9e2cc94aa65a1b02c09d74735541bb99
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3Apg%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4.md
https://github.com/ptushub/nohkiu/commit/ceedeff521e99428ebc695c62356892e3aff4e54
https://github.com/ptushub/nohkiu/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3Apg%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/1394de0cd9eb14724a319145eaa0a4a1d9d64ea8
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E6%90%9C%E7%8B%90%E6%91%84%E5%BD%B1.md
https://github.com/ryukaura/kityhe/commit/5dda5fc245949edf711bd4448b81ed47d296c1e4
https://github.com/ryukaura/kityhe/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3Apg%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md
https://github.com/sourux23/eufvji/commit/1bafaf675b8833dd34497357fc169969856f2bb9
https://github.com/sourux23/eufvji/blob/main/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/schowffer/nmghjj/commit/991dcafd4c71b0c3834e22543926e65330538dd0
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/constiang-s/xzjjce/commit/9a08a7025ea51c658ef58f62063baad2dcbabec3
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/37c59afb61445a4d930a7d8851b8b34081961fab
https://github.com/enognagu/lpvade/blob/main/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90app%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md
https://github.com/e44nf/nkliyn/commit/544f7cd85852ffa5c63dcf217e27d6bc20658993
https://github.com/e44nf/nkliyn/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/bfcf9ed6b4f92e792fc3ba56b3d47d9908ebb153
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md
https://github.com/danielfachka/zyfplc/commit/4f6084cd696dd33a6f069262fd3643edbd2884b5
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%20-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/2078b0ce1507b8054a0b1cf770b9fce10c9897fb
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/99104ed37c7c20c84dbd79029b6269ff8b613448
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/ryukaura/kityhe/commit/7d2b35200aa82e7f71a2bf790b173dd79ddc22ef
https://github.com/ryukaura/kityhe/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/e00ed357a3f0c2075009209c2433b882571464a2
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/651ce511e864cdb33e76371d6a50a9bf433be3f7
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3Apg%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/sourux23/eufvji/commit/bb4cbf1c8cece48b141483830bafdb802ce6088d
https://github.com/sourux23/eufvji/blob/main/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/constiang-s/xzjjce/commit/9d09d91841ab58fa900811fdf655565e05c66625
https://github.com/constiang-s/xzjjce/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/8f914b0013eba09ff85242f8de526965917ff056
https://github.com/e44nf/nkliyn/blob/main/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8%3Apg%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%20-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md
https://github.com/enognagu/lpvade/commit/717a37003b684fa1fff77fb0566b630512c98383
https://github.com/enognagu/lpvade/blob/main/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96.md
https://github.com/ptushub/nohkiu/commit/f73fbf66cd792f3645a10cba338900dd542e58f5
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F%3Apg%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/danielfachka/zyfplc/commit/d818c18b9623d953aa5cc870c8891aae508f6af9
https://github.com/danielfachka/zyfplc/blob/main/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3Apg%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90app%20-%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/bc0ffedd80c64e5acf06a822f419a690af4932eb
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3Apg%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/ryukaura/kityhe/commit/f4554236a018b23aed7a1f683af47a72954bcc03
https://github.com/ryukaura/kityhe/blob/main/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92%3Apg%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/kulkaye/xiinuu/commit/a64c4775e761bf68bd3806d7622ccfe27057ffa3
https://github.com/kulkaye/xiinuu/blob/main/2026%E9%A6%96%E8%A6%81%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md
https://github.com/schowffer/nmghjj/commit/d96e93d0852c1927a04318562533d5e7ba4aed16
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3Apg%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/b7c828c8deaaf6a9659f41c817d39a5dcc3545eb
https://github.com/sourux23/eufvji/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3Apg%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/5ef6175a3d215740c1abe5ec08b89119f705f324
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9.md
https://github.com/enognagu/lpvade/commit/2610cbd7619258662affed1b075a3c2856a82318
https://github.com/enognagu/lpvade/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%20-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/4fbd66fa8b6e3332521e7b3b410da3ab797836ea
https://github.com/e44nf/nkliyn/blob/main/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99%3Apg%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96.md
https://github.com/ptushub/nohkiu/commit/002ab913d00671ac71ad4e44f9ac1ea9d4c4a4a0
https://github.com/ptushub/nohkiu/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB.md
https://github.com/kulkaye/xiinuu/commit/33d80f14ec85c184d2410c86dc7259d14d931909
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88.md
https://github.com/danielfachka/zyfplc/commit/aa7e05f08a3c716aa0e2c53ec6e0bd42a7ca2806
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/mustakuritsar07/rkngzy/commit/a7acf727c6ef90345b4e38bbf9153f2e6a20762b
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/9089540ad7862cf89614c5832839797835fe3bb5
https://github.com/ryukaura/kityhe/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md
https://github.com/schowffer/nmghjj/commit/ead21b66405d4339f3f9c5277fff23279e44b201
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/sourux23/eufvji/commit/d807c9aa80257ca7495b8cbaba25c7195093d64c
https://github.com/sourux23/eufvji/blob/main/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/9a705126d3662e5fb863b6bb30bb7fae9ffcfa1a
https://github.com/constiang-s/xzjjce/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E5%BF%85%E5%BA%94.md
https://github.com/e44nf/nkliyn/commit/53670e7070bffe23d73058b1ed4aef04ec9989e9
https://github.com/e44nf/nkliyn/blob/main/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md
https://github.com/enognagu/lpvade/commit/2851dbbc612b602db09c5b3099658b1d77327b67
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md
https://github.com/ptushub/nohkiu/commit/cf7a1409a343ea3b9edfd2ec1557b51904b563d5
https://github.com/ptushub/nohkiu/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3Apg%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%20-%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81.md
https://github.com/kulkaye/xiinuu/commit/38170c328f2bc010c2aa4eabcd7cc7966699aff5
https://github.com/kulkaye/xiinuu/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md
https://github.com/danielfachka/zyfplc/commit/a593e481cfee14f2187aec18fedaf3f64361fb2f
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA.md
https://github.com/ryukaura/kityhe/commit/dcf78fc74a1b79645013a04c2fe77bf4f32b10c8
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/mustakuritsar07/rkngzy/commit/0d72bc1ec9c35efb31fbebc782fc152bd90a2c66
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E4%BC%98%E6%8D%B7%E6%95%B0%E7%A0%81.md
https://github.com/schowffer/nmghjj/commit/cc07e039cc7e759b710ae129dd05aeb2e76d71d5
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/sourux23/eufvji/commit/1c87887584cfbb74765a8a9c2217bc0cdaa69ae2
https://github.com/sourux23/eufvji/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/b6387b36111bd5cbc47b8b0c795fd7b903fe14cd
https://github.com/constiang-s/xzjjce/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-36%E6%B0%AA%E6%B1%BD%E8%BD%A6.md
https://github.com/e44nf/nkliyn/commit/f07ed750375c3bb2d39ccce0cc00fa2bc06d149c
https://github.com/e44nf/nkliyn/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md
https://github.com/enognagu/lpvade/commit/fcb327c8bf9906cf752d8129e90cc51e28cae2be
https://github.com/enognagu/lpvade/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md
https://github.com/ptushub/nohkiu/commit/0fc5233c1eb7ff9bc6908239c5b4a285e10a241c
https://github.com/ptushub/nohkiu/blob/main/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E4%BC%98%E6%8D%B7%E6%95%B0%E7%A0%81.md
https://github.com/kulkaye/xiinuu/commit/ed57fa39a30e9d525caeafb9821daac73cbf4ddf
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md
https://github.com/ryukaura/kityhe/commit/925d09298bda258f6a874e645989a2e11a70f2bb
https://github.com/ryukaura/kityhe/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86.md
https://github.com/danielfachka/zyfplc/commit/d11e0068894d52b07a9d6255597c070494aa5b37
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md
https://github.com/schowffer/nmghjj/commit/32e5974ee36857ea2ca87e5377ec7cd7165abd0b
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/c6614da0bfd6c0ccdd80f8d64b608df64442d0e1
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95.md
https://github.com/sourux23/eufvji/commit/6fe7afe0c466080ff19c8b0c79390448df4593e2
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3%E9%93%BE%E6%8E%A5-%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/fe8733057f9440515ed36a74283a860b54103b41
https://github.com/e44nf/nkliyn/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md
https://github.com/constiang-s/xzjjce/commit/ba4481ff6c99b754dd6de1fac6ac6ca32d4a1df6
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-360%E8%A7%86%E9%A2%91.md
https://github.com/enognagu/lpvade/commit/b724c2c2e098dcade0b76204eed1043639d79cdb
https://github.com/enognagu/lpvade/blob/main/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/kulkaye/xiinuu/commit/206c271d7240f3e625614af152444ed306f9e580
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md
https://github.com/ptushub/nohkiu/commit/04487bdb6c0d598c703764ab8d3296189e63bc37
https://github.com/ptushub/nohkiu/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86.md
https://github.com/ryukaura/kityhe/commit/02e2c501f6f5864c69c199ee9e6b08d909e9049a
https://github.com/ryukaura/kityhe/blob/main/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/danielfachka/zyfplc/commit/c203f0652136490f1e0453c3931f49a1e1519389
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/schowffer/nmghjj/commit/8f4dca9756e320d9b3c4db860a87318876a84561
https://github.com/schowffer/nmghjj/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%20-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/mustakuritsar07/rkngzy/commit/735cae4d36f71e83cd3796d75184666820b2176f
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86.md
https://github.com/sourux23/eufvji/commit/c4b837de1ba93c80da2281720b6167b5470415c7
https://github.com/sourux23/eufvji/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A28%E5%9C%88%E5%A8%B1%E4%B9%90app%20-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md
https://github.com/constiang-s/xzjjce/commit/10c430f889a172c802bd0e62f5f3c2d4ab9d8305
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A28%E5%9C%88%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/73b2f9f538016a3dbdc67a12a89de6e79d77489e
https://github.com/e44nf/nkliyn/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A28%E5%9C%88%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E6%90%9C%E7%8B%90%E6%91%84%E5%BD%B1.md
https://github.com/enognagu/lpvade/commit/cb82fcf075937d05de33919a7af39e01272666ae
https://github.com/enognagu/lpvade/blob/main/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A28%E5%9C%88%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md
https://github.com/kulkaye/xiinuu/commit/0d6af5234445feb2c7317ba80cb1baac6073cd47
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/ptushub/nohkiu/commit/fa9402385f1b1b4e9ed4ea7f59497f0476981bf1
https://github.com/ptushub/nohkiu/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/ryukaura/kityhe/commit/36434fdb81be6acbde4de10238b1f87f89a24078
https://github.com/ryukaura/kityhe/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/4117cdca5c2744e0dbe35c4970f045dc28f9f4c5
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95.md
https://github.com/schowffer/nmghjj/commit/5841ecf898762811e3c1e89521686afa5061f732
https://github.com/schowffer/nmghjj/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md
https://github.com/sourux23/eufvji/commit/aa766aceaf37f0aa360b44408e6828bc11bdbba2
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3Apg28%E5%9C%88%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/4927b2699c77fa5ccaa81ffdf5bd2abbec332eee
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0%3Apg28%E5%9C%88%E5%A8%B1%E4%B9%90%20-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md
https://github.com/kulkaye/xiinuu/commit/25ffc56a45de58727704ba7eb570ccea49755584
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8%3Apg28%E5%9C%88%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/e44nf/nkliyn/commit/809b4b438ac52612decb17e3cc1e5e417e8f5cc1
https://github.com/e44nf/nkliyn/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3Apg28%E5%9C%88%E5%A8%B1%E4%B9%90app%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5.md
https://github.com/enognagu/lpvade/commit/067a7fede841a763567b929d07af425d7ca16c60
https://github.com/enognagu/lpvade/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3Apg28%E5%9C%88%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md
https://github.com/constiang-s/xzjjce/commit/81616f211cadb17e4f50d01707f40dd67c04f913
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3Apg28%E5%9C%88%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/7e097ed45f28cd5a33bc6505b7d09d96f79fa6bf
https://github.com/ptushub/nohkiu/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF.md
https://github.com/ryukaura/kityhe/commit/40f95be9bfc3fd987f28c174cd26daf6b1de8e0c
https://github.com/ryukaura/kityhe/blob/main/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-360%E5%8E%86%E5%8F%B2.md
https://github.com/danielfachka/zyfplc/commit/f156d2f92b9ccf4e9141b25e9bbb79573f7eec69
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/79e51820731e378e115faba92350c554d17f324b
https://github.com/sourux23/eufvji/blob/main/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/e3f8933ae07fd0092ace96d3e7adc6fcbd27c457
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/mustakuritsar07/rkngzy/commit/7c002f4782249f07156a4a2c3dc465bb3b7dedae
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%20-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/1a7598f285bc1d93bf3386e19909851c82003f65
https://github.com/e44nf/nkliyn/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md
https://github.com/kulkaye/xiinuu/commit/52b8b22ffeee1fa67fe4bcfe8933ba8938fd9dbc
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md
https://github.com/enognagu/lpvade/commit/2b829b9c156d869251f805ffe368484401663712
https://github.com/enognagu/lpvade/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/constiang-s/xzjjce/commit/350736f315375644a8e0f22b155669c68a09d928
https://github.com/constiang-s/xzjjce/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/b7dbd5152411331cc1175c3ff91bcbc5c4fe45e5
https://github.com/ptushub/nohkiu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8.md
https://github.com/danielfachka/zyfplc/commit/07a9149ab5c1513d8032e202955aa9fd3dae327f
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/deb74b92809e8e222e9db600eda27ff29d2881f0
https://github.com/sourux23/eufvji/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md
https://github.com/ryukaura/kityhe/commit/e965280e3454ca3985dd3c13b573ad551351428a
https://github.com/ryukaura/kityhe/blob/main/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md
https://github.com/schowffer/nmghjj/commit/584bc9fece084f5684d2ab662ede6f0770bb5a96
https://github.com/schowffer/nmghjj/blob/main/2026%E9%A6%96%E8%A6%81%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md
https://github.com/kulkaye/xiinuu/commit/b09b74a8241a4f8c75570382f88853e932cbea24
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/mustakuritsar07/rkngzy/commit/c6964370483e5098d011b760792e6eaf4c16bab0
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/e44nf/nkliyn/commit/9a9b7dcae77991c03097a791109a190990d253b8
https://github.com/e44nf/nkliyn/blob/main/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3Apg28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%20-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF.md
https://github.com/enognagu/lpvade/commit/09b17fafc8ff7527e9099955545c06e42012e63a
https://github.com/enognagu/lpvade/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F.md
