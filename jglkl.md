百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
伎盗扑抵短景赡廖肝优乐群毓送车

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

https://github.com/schowffer/nmghjj/commit/d4f96ab93ac5b1b915ad1a57d6ee083e3151864f
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3Apg%E5%A3%B9%E5%8F%B7%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/143ec13c52e6a572001c6a1d97a48cdfd05cf38c
https://github.com/enognagu/lpvade/blob/main/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E5%A3%B9%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%20-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/0bc5267fa19a3ebd780e9f2baf74b0cc8a5fc524
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E5%A3%B9%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88.md
https://github.com/danielfachka/zyfplc/commit/c1aca695853022bd9203c07e2c98832a91cf0a28
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F%3Apg%E5%A3%B9%E5%8F%B7%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/mustakuritsar07/rkngzy/commit/ca2b959e26b5f3015d709243d0bf4585c05af2d4
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E5%A3%B9%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/sourux23/eufvji/commit/0c3813472c2a5ad89b2a5b10e91c27da2c25aca2
https://github.com/sourux23/eufvji/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3Apg%E5%A3%B9%E5%8F%B7%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/constiang-s/xzjjce/commit/f0213e5ddbb6e85113260c51774f83a382945277
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C%3A%E5%A3%B9%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/3d768b8eccb61bf02fdcc590f9fff7423518d0b3
https://github.com/e44nf/nkliyn/blob/main/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92%3A%E5%A3%B9%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/ryukaura/kityhe/commit/85175a359d82a0ff46c1265be19e5be495b0fd62
https://github.com/ryukaura/kityhe/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E5%A3%B9%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/kulkaye/xiinuu/commit/4d716ad5593589772e578742baa5c8a88aa9ae39
https://github.com/kulkaye/xiinuu/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E5%A3%B9%E5%8F%B7%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md
https://github.com/ptushub/nohkiu/commit/cd06c60a9c4720308a6daf770539dfba8ed0c78a
https://github.com/ptushub/nohkiu/blob/main/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC%3A%E5%A3%B9%E5%8F%B7%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md
https://github.com/enognagu/lpvade/commit/816733a5a693baab6c4904a79832401ac803411b
https://github.com/enognagu/lpvade/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E5%A3%B9%E5%8F%B7%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/e17b9cd32b3d1bce2515dd9ec74f285f0ef3eb9a
https://github.com/schowffer/nmghjj/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3A%E5%A3%B9%E5%8F%B7%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/8501e8af5e7b95a88fa15434eea01ee7340acf30
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3Apg%E5%A3%B9%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%20-%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96.md
https://github.com/sourux23/eufvji/commit/12e9c5510deffae00adb2980b699b1cd74854aaa
https://github.com/sourux23/eufvji/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A%E5%A3%B9%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/b7ce53724072937004e987435a6aa067677c4a13
https://github.com/danielfachka/zyfplc/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E5%A3%B9%E5%8F%B7%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md
https://github.com/constiang-s/xzjjce/commit/d2a7f86853a31da55500c0cb5beb4c617b44a463
https://github.com/constiang-s/xzjjce/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E5%A3%B9%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E5%BF%85%E5%BA%94.md
https://github.com/e44nf/nkliyn/commit/26cb270cef12a49bbe97acefae42b439c4b2ed8c
https://github.com/e44nf/nkliyn/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E5%A3%B9%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md
https://github.com/ryukaura/kityhe/commit/a48fd6bd915b2b5376323c88818ec0b2459ff5d5
https://github.com/ryukaura/kityhe/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E5%A3%B9%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/enognagu/lpvade/commit/8294588564881921598ae0bd907b9de3e7588e62
https://github.com/enognagu/lpvade/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A%3A%E5%A3%B9%E5%8F%B7%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/a645f31f7e8fefcd48321c875a076b898a0e237e
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E5%A3%B9%E5%8F%B7%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E6%90%9C%E7%8B%90%E6%91%84%E5%BD%B1.md
https://github.com/kulkaye/xiinuu/commit/a31df2ff76c228569bfec3dbf7178f2f3c6ac168
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E5%A3%B9%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/schowffer/nmghjj/commit/75c6738e9baf6619c8a9a5a1d867bb95771c75cf
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E5%A3%B9%E5%8F%B7%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md
https://github.com/sourux23/eufvji/commit/73850e0e360b056509d4cb25c5128a255fada588
https://github.com/sourux23/eufvji/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E5%A3%B9%E5%8F%B7%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/mustakuritsar07/rkngzy/commit/b16a2d2b3ebe63bcad2ec7ec473b3647d858de31
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E5%A3%B9%E5%8F%B7%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA.md
https://github.com/constiang-s/xzjjce/commit/98ec7c64ed1046ae296209fc5fc80c8407e3fc94
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3Apg%E4%BA%BF%E4%B8%8728%E5%A4%A7%E8%88%9E%E5%8F%B0-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md
https://github.com/danielfachka/zyfplc/commit/0205463c5199aeedccf56d5a0d568a9d4827acf7
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97%3A%E4%BA%BF%E4%B8%8728%E5%A4%A7%E8%88%9E%E5%8F%B0-%E5%BF%85%E5%BA%94.md
https://github.com/e44nf/nkliyn/commit/89a18851e94a797d690837b5182f5ff9571cb3da
https://github.com/e44nf/nkliyn/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3Apg%E4%BA%BF%E4%B8%8728%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96.md
https://github.com/enognagu/lpvade/commit/fc1a87402f6c0a73f868436dabfb3992e602eaaf
https://github.com/enognagu/lpvade/blob/main/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB%3Apg%E4%BA%BF%E4%B8%8728%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF.md
https://github.com/ryukaura/kityhe/commit/3fd36ce9c4e718ef3e961d6ae43f26a7e42fdd65
https://github.com/ryukaura/kityhe/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3Apg%E4%BA%BF%E4%B8%8728%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/e519b0a440fcd72185d65219375addea0388b450
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3Apg%E4%BA%BF%E4%B8%8728%E5%B9%B3%E5%8F%B0-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/schowffer/nmghjj/commit/92be1660ff32d5d75be558809b4df3abc02d492c
https://github.com/schowffer/nmghjj/blob/main/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93%3Apg%E4%BA%BF%E4%B8%8728%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95.md
https://github.com/ptushub/nohkiu/commit/430e3441e759993afb0acc728c71772f9ee6e979
https://github.com/ptushub/nohkiu/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F%3Apg%E4%BA%BF%E4%B8%8728%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3%E9%93%BE%E6%8E%A5-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/4f82e829dd570fdf16ce3115ce264ba14608b0de
https://github.com/sourux23/eufvji/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3Apg%E4%BA%BF%E4%B8%8728%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/cd446d92c1f410ba6504ccf5fad1f4cd806b5cbc
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3Apg%E4%BA%BF%E4%B8%8728%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86.md
https://github.com/constiang-s/xzjjce/commit/834ba11f7ec36c568f0ca2fa18f1fa6b62596b20
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA%3A%E4%BA%BF%E4%B8%8728%E5%B9%B3%E5%8F%B0-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/danielfachka/zyfplc/commit/e78c23b6b17839f70dbe649a49dd187d9263e1e5
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3A%E4%BA%BF%E4%B8%8728%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9.md
https://github.com/enognagu/lpvade/commit/36b30dcfee6c1795ad5a644f947e7de7b69f1e81
https://github.com/enognagu/lpvade/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E4%BA%BF%E4%B8%87%E5%A8%B1%E4%B9%90-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/e44nf/nkliyn/commit/b1eac0e38507de4d08d5e03f8152cdd78b4d9210
https://github.com/e44nf/nkliyn/blob/main/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB%3A%E4%BA%BF%E4%B8%8728%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/b78d36391207037cafc84bbffc91d4a200e46962
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%20%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/kulkaye/xiinuu/commit/394760cce944cf1f792d36f9c057ae8225825ebd
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90app-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/sourux23/eufvji/commit/60d2b838e457f53a7c1956a5ae893e1589b7bade
https://github.com/sourux23/eufvji/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE.md
https://github.com/ptushub/nohkiu/commit/3461bc2a3ae41afdcb72bab092a9c5a909b7283f
https://github.com/ptushub/nohkiu/blob/main/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/mustakuritsar07/rkngzy/commit/f8593885c9851f26d0aefac2cc2416336fd27dbb
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/f29eee3356f5867ccd5badf584ce12077e25e564
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md
https://github.com/enognagu/lpvade/commit/e65e9b9a4a681726123276852181b315c9ca05bc
https://github.com/enognagu/lpvade/blob/main/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4.md
https://github.com/constiang-s/xzjjce/commit/5959a9a9188c79c1d21dca0b6026e4632878cc6e
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/007b601938abf4e3aaaff87b5a742f7a28c738a7
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md
https://github.com/e44nf/nkliyn/commit/8650e8f24855903e7d18b9b9825e6b7973ea5bfa
https://github.com/e44nf/nkliyn/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/f677a475f13b30c375bac01226aadf5c34a5aea1
https://github.com/kulkaye/xiinuu/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3Apg%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md
https://github.com/ryukaura/kityhe/commit/a0a5fee5ecb9f5fd63cd2580249bc3fd504a52c9
https://github.com/ryukaura/kityhe/blob/main/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90-%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95.md
https://github.com/sourux23/eufvji/commit/1334c032a74a17999fd96a5f3481ca8bc2ce3e1b
https://github.com/sourux23/eufvji/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3Apg%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90app-360%E9%80%9A%E4%BF%A1.md
https://github.com/ptushub/nohkiu/commit/bb135a823ac8e139fae700d52b7d83deac7218ad
https://github.com/ptushub/nohkiu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C-360%E9%80%9A%E4%BF%A1.md
https://github.com/mustakuritsar07/rkngzy/commit/1e8d4ae373c5a482f19bfdba09e913fa8cf73e55
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3Apg%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0.md
https://github.com/schowffer/nmghjj/commit/cca40d3fa66844daa02315405533f93b82afb3fd
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3Apg%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/enognagu/lpvade/commit/e0113e488eca38915acc6fc04180ec2c36ad9655
https://github.com/enognagu/lpvade/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3Apg%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/kulkaye/xiinuu/commit/7f2056efe4b1a7749a210e313d709a8b0a0c2096
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF%3Apg%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/constiang-s/xzjjce/commit/475a4bb68d0cf03ec684ea3a0e0723bab784b1d9
https://github.com/constiang-s/xzjjce/blob/main/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3Apg%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md
https://github.com/e44nf/nkliyn/commit/6ea52e39c2bce90b12655c280d4be17475a8a4fd
https://github.com/e44nf/nkliyn/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3Apg%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/danielfachka/zyfplc/commit/257b34deb1a4212a974f3ddd2e8b6ee528b02336
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3Apg%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C-%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/ba8cccbbaa6b1470aa3f183f5453e80522108dd2
https://github.com/ryukaura/kityhe/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/sourux23/eufvji/commit/7455334c024b5a8306192885314db65570f23f82
https://github.com/sourux23/eufvji/blob/main/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C-%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88.md
https://github.com/ptushub/nohkiu/commit/c9bf2236b03e6bbd7f11584bc1fc2540418f7d3f
https://github.com/ptushub/nohkiu/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/mustakuritsar07/rkngzy/commit/438fe61cf29a807e50652ec722ef601cd1fdb762
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md
https://github.com/kulkaye/xiinuu/commit/a9305ecac927af42a87b3417e317f7c555ab9bd6
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/453ae50db9495e254a35aef6c802f0bd879cdb87
https://github.com/enognagu/lpvade/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/48111cd2210700c40c261a6a94260788029d47ee
https://github.com/schowffer/nmghjj/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/d62887c3c9a6f7c1dd684dd16ad0eea580f6e194
https://github.com/e44nf/nkliyn/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/constiang-s/xzjjce/commit/a9aac790b34c84dd8af4fff1b83bca3759bd3183
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md
https://github.com/danielfachka/zyfplc/commit/e9856f9b6d4f80ff771c2cb9858ff481cd5ab8b0
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/492e33d1160e886392b39b74a1d4ee93a7b92312
https://github.com/sourux23/eufvji/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3Apg%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA-%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90.md
https://github.com/ryukaura/kityhe/commit/29088233ce47a5781df613a6dcd84f10c3eebbaa
https://github.com/ryukaura/kityhe/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md
https://github.com/ptushub/nohkiu/commit/fdc8021387d266b7e9c351abfa8cc94ed9952ff9
https://github.com/ptushub/nohkiu/blob/main/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C-%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96.md
https://github.com/mustakuritsar07/rkngzy/commit/cd885e760137ce36c7d058e47642a0c25051848a
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md
https://github.com/enognagu/lpvade/commit/1257f046885e92d101504f3e9ea6b1094e1810eb
https://github.com/enognagu/lpvade/blob/main/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/kulkaye/xiinuu/commit/74fe1a75a788e43e6349917999f1b43fe67d44aa
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/ba6a4857c7ff192d57b6d67663563e2d9564cb34
https://github.com/schowffer/nmghjj/blob/main/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md
https://github.com/constiang-s/xzjjce/commit/1a32c29bd535435ccb6a10bbe5f31a869aae993e
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/064df7e65e684d57513876cd9ebb4c0e43bef85d
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C-%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F.md
https://github.com/danielfachka/zyfplc/commit/4e9eaab0b94b0b31182259fb8c455de6acd25394
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/ryukaura/kityhe/commit/2fbf6f932f00782aa7367727b6e37970f9501576
https://github.com/ryukaura/kityhe/blob/main/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF.md
https://github.com/sourux23/eufvji/commit/1c81a3508cd15a17e7bf5c158a69fc7489ea3aea
https://github.com/sourux23/eufvji/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/dd9edd2cd28f15f6e5489a6eed816ab69aa6c12a
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5%3Apg%E5%A4%9A%E5%A4%9A28%E5%A4%A7%E8%88%9E%E5%8F%B0-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md
https://github.com/enognagu/lpvade/commit/49a7aace0a0ef48b5db4c622331ebd8c45b95439
https://github.com/enognagu/lpvade/blob/main/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5%3Apg%E5%A4%9A%E5%A4%9A28%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md
https://github.com/ptushub/nohkiu/commit/6cd3ab1469e756d1d5fdbb805da5fea26489054c
https://github.com/ptushub/nohkiu/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E5%A4%9A%E5%A4%9A28%E5%A4%A7%E8%88%9E%E5%8F%B0-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/kulkaye/xiinuu/commit/526689445aa3020face2749b4e229c068d2dfd0f
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3Apg%E5%A4%9A%E5%A4%9A28%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/constiang-s/xzjjce/commit/ad2b3e12e1375ceef4fc4abf354101e79b7b03b1
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4%3Apg%E5%A4%9A%E5%A4%9A28%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3%E9%93%BE%E6%8E%A5-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md
https://github.com/schowffer/nmghjj/commit/bba61df4af6a3399f1999dd65d12375ba7184f76
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3Apg%E5%A4%9A%E5%A4%9A28%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/e44nf/nkliyn/commit/a1c0825aba27f83965432b8834954968496cacf3
https://github.com/e44nf/nkliyn/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3Apg%E5%A4%9A%E5%A4%9A28%E5%B9%B3%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88.md
https://github.com/sourux23/eufvji/commit/d5c47b4f3730986bea362c8943e7831de1bbe3d3
https://github.com/sourux23/eufvji/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E5%A4%9A%E5%A4%9A28%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/518126895f506aabc625ba10afca29d5809f30da
https://github.com/danielfachka/zyfplc/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3Apg%E5%A4%9A%E5%A4%9A28%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F.md
https://github.com/mustakuritsar07/rkngzy/commit/ca204ea7bb4d9626271c558cbb773e129b568554
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E5%A4%9A%E5%A4%9A28%E5%B9%B3%E5%8F%B0-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/kulkaye/xiinuu/commit/7e4f9ecb8329922d4969188de76afafeb076cdd8
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%20-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/7ec6e04608593db7b37a974191df8b5243a4bf90
https://github.com/enognagu/lpvade/blob/main/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E5%A4%9A%E5%A4%9A28%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/ryukaura/kityhe/commit/630ee4a05c694a3cc3a1d85013ac8af4295f9645
https://github.com/ryukaura/kityhe/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3Apg%E5%A4%9A%E5%A4%9A28%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md
https://github.com/ptushub/nohkiu/commit/70a026ac4548bef5f12978d31ac2c1a989aa23ac
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E5%A4%9A%E5%A4%9A28%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/7e1a575cb1d678e6c4cd14d944bc438f23a05f14
https://github.com/constiang-s/xzjjce/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-360%E8%A7%86%E9%A2%91.md
https://github.com/kulkaye/xiinuu/commit/77ae880561542142f0b7078739e7258674c4b6e9
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB.md
https://github.com/schowffer/nmghjj/commit/5520d8cb63d7e9a0df89feea48ebad75b0b5f3b9
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md
https://github.com/sourux23/eufvji/commit/d15f835f90a9c22e4e4e77fa952faab39b875e84
https://github.com/sourux23/eufvji/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md
https://github.com/e44nf/nkliyn/commit/fad4d9c7c51c81007a7b54876d453cb9df96345e
https://github.com/e44nf/nkliyn/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md
https://github.com/mustakuritsar07/rkngzy/commit/882ad2d47352f6c476831bb626308635c10f6095
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95.md
https://github.com/ryukaura/kityhe/commit/15aaf929918814b1727d835e40a0d8771bd83017
https://github.com/ryukaura/kityhe/blob/main/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/5ea6e0c8081338d16343a2ce1c3aadcc1739398b
https://github.com/enognagu/lpvade/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md
https://github.com/danielfachka/zyfplc/commit/3271dbe04691e2f465d1a3891cda22df4a65ce7b
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/ptushub/nohkiu/commit/e98276cc221e4a05b187eb196749ae4dd823a54a
https://github.com/ptushub/nohkiu/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/constiang-s/xzjjce/commit/03ec094db84216bf101bd0163fdc493785ad89f2
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3Apg%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%20-%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81.md
https://github.com/sourux23/eufvji/commit/58dc57ee040f1566a2bd2fcf636518204c415fcb
https://github.com/sourux23/eufvji/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3Apg%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4.md
https://github.com/kulkaye/xiinuu/commit/1feea45c83e9b95af98fe86d63ef74f85f113bc4
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3Apg%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/e44nf/nkliyn/commit/3e792bbe0251ee7334f5018f0116076c64fab93b
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89%3Apg%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md
https://github.com/schowffer/nmghjj/commit/bb2073f476ac2fa5b0a197777c559e108815054c
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app%20-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/mustakuritsar07/rkngzy/commit/f251cd545bccfbcc47da74d1f0ae70cbf5d00026
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3Apg%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E6%90%9C%E7%8B%90%E6%91%84%E5%BD%B1.md
https://github.com/ryukaura/kityhe/commit/a5db538d70eba7a0b8caf1b88e6e220b0957295e
https://github.com/ryukaura/kityhe/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3Apg%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/b92395c9ec5f808331993bc9566e6606081c661c
https://github.com/enognagu/lpvade/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/d79817549656508ca5ce82d28175d6caa1dd8883
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92%3Apg%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/ptushub/nohkiu/commit/068dc9735614793941a3da821078f28f73ffbb04
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3Apg%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md
https://github.com/sourux23/eufvji/commit/b278290e7db51699e0f327b0c4964eeec4d7f058
https://github.com/sourux23/eufvji/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%20-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/kulkaye/xiinuu/commit/35b88f6bbbe01fb502d1d167559d11ed4c040ef6
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/94f9475f8b2fb6ac5f10d7d7074cecb1c4700960
https://github.com/constiang-s/xzjjce/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/e44nf/nkliyn/commit/e02a37372d6623f67daf9a57431957dd1c4ab1c0
https://github.com/e44nf/nkliyn/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/5abe550a720d17ac8dbdbfa5ae668506d543d1d2
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/47f2a9a4db7d0493d032006b6cbfd7e33de4d662
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md
https://github.com/enognagu/lpvade/commit/980d140646593d4eeeab5ed54430a3a1bf161011
https://github.com/enognagu/lpvade/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/ryukaura/kityhe/commit/d79e2f06737c487e8c5af8ef8f5ffd2752d5ab75
https://github.com/ryukaura/kityhe/blob/main/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95.md
