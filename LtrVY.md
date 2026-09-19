百度蜘蛛是百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
仪尤忧仪母迷迷嫡逗腔苹苹纷肛故黑及及谖死
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

https://github.com/ryukaura/kityhe/commit/2fc0e8e96d2a48687929a42fbaa1a2061a2833c7?/054=932
https://github.com/ryukaura/kityhe/commit/2fc0e8e96d2a48687929a42fbaa1a2061a2833c7?/998=262
https://github.com/ryukaura/kityhe/commit/2fc0e8e96d2a48687929a42fbaa1a2061a2833c7?/923=604
https://github.com/ryukaura/kityhe/commit/2fc0e8e96d2a48687929a42fbaa1a2061a2833c7
https://github.com/ryukaura/kityhe/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E5%AE%B9%E6%98%93%E8%BF%98%E6%98%AF2%E5%AE%B9%E6%98%93%E8%B5%A2-%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/076=925
https://github.com/ryukaura/kityhe/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E5%AE%B9%E6%98%93%E8%BF%98%E6%98%AF2%E5%AE%B9%E6%98%93%E8%B5%A2-%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/154=821
https://github.com/ryukaura/kityhe/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E5%AE%B9%E6%98%93%E8%BF%98%E6%98%AF2%E5%AE%B9%E6%98%93%E8%B5%A2-%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/637=609
https://github.com/ryukaura/kityhe/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E5%AE%B9%E6%98%93%E8%BF%98%E6%98%AF2%E5%AE%B9%E6%98%93%E8%B5%A2-%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/447=943
https://github.com/ryukaura/kityhe/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E5%AE%B9%E6%98%93%E8%BF%98%E6%98%AF2%E5%AE%B9%E6%98%93%E8%B5%A2-%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/211=932
https://github.com/ryukaura/kityhe/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E5%AE%B9%E6%98%93%E8%BF%98%E6%98%AF2%E5%AE%B9%E6%98%93%E8%B5%A2-%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/ff9c76345bde8fac22bc73ea0d48b9ffd2fa05d9?/992=342
https://github.com/e44nf/nkliyn/commit/ff9c76345bde8fac22bc73ea0d48b9ffd2fa05d9?/049=821
https://github.com/e44nf/nkliyn/commit/ff9c76345bde8fac22bc73ea0d48b9ffd2fa05d9?/561=503
https://github.com/e44nf/nkliyn/commit/ff9c76345bde8fac22bc73ea0d48b9ffd2fa05d9?/599=609
https://github.com/e44nf/nkliyn/commit/ff9c76345bde8fac22bc73ea0d48b9ffd2fa05d9?/070=617
https://github.com/e44nf/nkliyn/commit/ff9c76345bde8fac22bc73ea0d48b9ffd2fa05d9
https://github.com/e44nf/nkliyn/blob/main/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E8%A7%86%E9%A2%91-%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F.md?/497=151
https://github.com/e44nf/nkliyn/blob/main/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E8%A7%86%E9%A2%91-%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F.md?/043=151
https://github.com/e44nf/nkliyn/blob/main/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E8%A7%86%E9%A2%91-%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F.md?/015=378
https://github.com/e44nf/nkliyn/blob/main/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E8%A7%86%E9%A2%91-%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F.md?/669=944
https://github.com/e44nf/nkliyn/blob/main/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E8%A7%86%E9%A2%91-%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F.md?/599=710
https://github.com/e44nf/nkliyn/blob/main/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E8%A7%86%E9%A2%91-%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/c149e60c25dcd9f78aa1f90a30dd84d17b528983?/164=663
https://github.com/constiang-s/xzjjce/commit/c149e60c25dcd9f78aa1f90a30dd84d17b528983?/481=710
https://github.com/constiang-s/xzjjce/commit/c149e60c25dcd9f78aa1f90a30dd84d17b528983?/551=079
https://github.com/constiang-s/xzjjce/commit/c149e60c25dcd9f78aa1f90a30dd84d17b528983?/719=614
https://github.com/constiang-s/xzjjce/commit/c149e60c25dcd9f78aa1f90a30dd84d17b528983?/497=276
https://github.com/constiang-s/xzjjce/commit/c149e60c25dcd9f78aa1f90a30dd84d17b528983
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D-%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/942=892
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D-%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/590=208
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D-%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/664=041
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D-%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/008=041
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D-%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/107=210
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D-%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/2e2245ad889a970139b2d6eb44a836f4b4882e33?/642=414
https://github.com/sourux23/eufvji/commit/2e2245ad889a970139b2d6eb44a836f4b4882e33?/339=598
https://github.com/sourux23/eufvji/commit/2e2245ad889a970139b2d6eb44a836f4b4882e33?/865=647
https://github.com/sourux23/eufvji/commit/2e2245ad889a970139b2d6eb44a836f4b4882e33?/665=775
https://github.com/sourux23/eufvji/commit/2e2245ad889a970139b2d6eb44a836f4b4882e33?/598=720
https://github.com/sourux23/eufvji/commit/2e2245ad889a970139b2d6eb44a836f4b4882e33
https://github.com/sourux23/eufvji/blob/main/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E6%9C%80%E6%96%B0%E8%A7%86%E9%A2%91-%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F.md?/609=058
https://github.com/sourux23/eufvji/blob/main/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E6%9C%80%E6%96%B0%E8%A7%86%E9%A2%91-%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F.md?/753=500
https://github.com/sourux23/eufvji/blob/main/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E6%9C%80%E6%96%B0%E8%A7%86%E9%A2%91-%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F.md?/097=410
https://github.com/sourux23/eufvji/blob/main/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E6%9C%80%E6%96%B0%E8%A7%86%E9%A2%91-%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F.md?/499=220
https://github.com/sourux23/eufvji/blob/main/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E6%9C%80%E6%96%B0%E8%A7%86%E9%A2%91-%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F.md?/231=008
https://github.com/sourux23/eufvji/blob/main/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E6%9C%80%E6%96%B0%E8%A7%86%E9%A2%91-%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/686a3bd3ac332a3a6fb6fdc3558180130d5ece0c?/854=664
https://github.com/mustakuritsar07/rkngzy/commit/686a3bd3ac332a3a6fb6fdc3558180130d5ece0c?/710=827
https://github.com/mustakuritsar07/rkngzy/commit/686a3bd3ac332a3a6fb6fdc3558180130d5ece0c?/276=221
https://github.com/mustakuritsar07/rkngzy/commit/686a3bd3ac332a3a6fb6fdc3558180130d5ece0c?/221=603
https://github.com/mustakuritsar07/rkngzy/commit/686a3bd3ac332a3a6fb6fdc3558180130d5ece0c?/636=710
https://github.com/mustakuritsar07/rkngzy/commit/686a3bd3ac332a3a6fb6fdc3558180130d5ece0c
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D%E8%A7%86%E9%A2%91-%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F.md?/669=481
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D%E8%A7%86%E9%A2%91-%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F.md?/371=109
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D%E8%A7%86%E9%A2%91-%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F.md?/497=142
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D%E8%A7%86%E9%A2%91-%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F.md?/265=381
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D%E8%A7%86%E9%A2%91-%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F.md?/325=609
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D%E8%A7%86%E9%A2%91-%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/c49acf40eeaf419b4bfb0187afe1738cde771d7f?/498=497
https://github.com/schowffer/nmghjj/commit/c49acf40eeaf419b4bfb0187afe1738cde771d7f?/376=449
https://github.com/schowffer/nmghjj/commit/c49acf40eeaf419b4bfb0187afe1738cde771d7f?/821=774
https://github.com/schowffer/nmghjj/commit/c49acf40eeaf419b4bfb0187afe1738cde771d7f?/150=487
https://github.com/schowffer/nmghjj/commit/c49acf40eeaf419b4bfb0187afe1738cde771d7f?/274=465
https://github.com/schowffer/nmghjj/commit/c49acf40eeaf419b4bfb0187afe1738cde771d7f
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E9%9F%B3%E4%B9%90-%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F.md?/881=386
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E9%9F%B3%E4%B9%90-%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F.md?/664=097
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E9%9F%B3%E4%B9%90-%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F.md?/234=595
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E9%9F%B3%E4%B9%90-%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F.md?/987=554
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E9%9F%B3%E4%B9%90-%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F.md?/492=267
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E9%9F%B3%E4%B9%90-%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/951e67dafd88f8119b585ad07e7f9b3fb59f672a?/054=487
https://github.com/danielfachka/zyfplc/commit/951e67dafd88f8119b585ad07e7f9b3fb59f672a?/181=157
https://github.com/danielfachka/zyfplc/commit/951e67dafd88f8119b585ad07e7f9b3fb59f672a?/884=525
https://github.com/danielfachka/zyfplc/commit/951e67dafd88f8119b585ad07e7f9b3fb59f672a?/636=097
https://github.com/danielfachka/zyfplc/commit/951e67dafd88f8119b585ad07e7f9b3fb59f672a?/558=725
https://github.com/danielfachka/zyfplc/commit/951e67dafd88f8119b585ad07e7f9b3fb59f672a
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862000%E8%B7%AF%E4%B8%AD%E5%A5%96%E7%BB%84%E5%90%88-%E7%A6%8F%E5%BD%A95.md?/602=662
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862000%E8%B7%AF%E4%B8%AD%E5%A5%96%E7%BB%84%E5%90%88-%E7%A6%8F%E5%BD%A95.md?/770=389
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862000%E8%B7%AF%E4%B8%AD%E5%A5%96%E7%BB%84%E5%90%88-%E7%A6%8F%E5%BD%A95.md?/414=762
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862000%E8%B7%AF%E4%B8%AD%E5%A5%96%E7%BB%84%E5%90%88-%E7%A6%8F%E5%BD%A95.md?/481=321
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862000%E8%B7%AF%E4%B8%AD%E5%A5%96%E7%BB%84%E5%90%88-%E7%A6%8F%E5%BD%A95.md?/469=831
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862000%E8%B7%AF%E4%B8%AD%E5%A5%96%E7%BB%84%E5%90%88-%E7%A6%8F%E5%BD%A95.md
https://github.com/enognagu/lpvade/commit/f92928ca29b7689a2a07a8d2964b3e828a42d99d?/598=019
https://github.com/enognagu/lpvade/commit/f92928ca29b7689a2a07a8d2964b3e828a42d99d?/043=110
https://github.com/enognagu/lpvade/commit/f92928ca29b7689a2a07a8d2964b3e828a42d99d?/156=554
https://github.com/enognagu/lpvade/commit/f92928ca29b7689a2a07a8d2964b3e828a42d99d?/831=665
https://github.com/enognagu/lpvade/commit/f92928ca29b7689a2a07a8d2964b3e828a42d99d?/694=821
https://github.com/enognagu/lpvade/commit/f92928ca29b7689a2a07a8d2964b3e828a42d99d
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862-%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F.md?/821=536
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862-%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F.md?/379=832
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862-%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F.md?/976=598
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862-%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F.md?/508=521
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862-%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F.md?/642=770
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862-%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/9aad9a0eadf4badf1037c423f8012c5fda0a2555?/058=839
https://github.com/kulkaye/xiinuu/commit/9aad9a0eadf4badf1037c423f8012c5fda0a2555?/610=869
https://github.com/kulkaye/xiinuu/commit/9aad9a0eadf4badf1037c423f8012c5fda0a2555?/047=525
https://github.com/kulkaye/xiinuu/commit/9aad9a0eadf4badf1037c423f8012c5fda0a2555?/270=033
https://github.com/kulkaye/xiinuu/commit/9aad9a0eadf4badf1037c423f8012c5fda0a2555?/058=275
https://github.com/kulkaye/xiinuu/commit/9aad9a0eadf4badf1037c423f8012c5fda0a2555
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D%E5%A4%9A%E5%B0%91%E9%92%B1-%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F.md?/049=386
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D%E5%A4%9A%E5%B0%91%E9%92%B1-%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F.md?/165=498
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D%E5%A4%9A%E5%B0%91%E9%92%B1-%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F.md?/270=265
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D%E5%A4%9A%E5%B0%91%E9%92%B1-%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F.md?/065=770
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D%E5%A4%9A%E5%B0%91%E9%92%B1-%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F.md?/749=225
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%861%E4%B8%87%E5%80%8D%E5%A4%9A%E5%B0%91%E9%92%B1-%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/54598637838708427142d225e3f7387d4220074d?/091=771
https://github.com/e44nf/nkliyn/commit/54598637838708427142d225e3f7387d4220074d?/481=831
https://github.com/e44nf/nkliyn/commit/54598637838708427142d225e3f7387d4220074d?/595=872
https://github.com/e44nf/nkliyn/commit/54598637838708427142d225e3f7387d4220074d?/598=302
https://github.com/e44nf/nkliyn/commit/54598637838708427142d225e3f7387d4220074d?/602=113
https://github.com/e44nf/nkliyn/commit/54598637838708427142d225e3f7387d4220074d
https://github.com/e44nf/nkliyn/blob/main/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862bug-%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F.md?/265=373
https://github.com/e44nf/nkliyn/blob/main/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862bug-%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F.md?/573=639
https://github.com/e44nf/nkliyn/blob/main/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862bug-%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F.md?/503=520
https://github.com/e44nf/nkliyn/blob/main/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862bug-%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F.md?/279=003
https://github.com/e44nf/nkliyn/blob/main/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862bug-%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F.md?/389=278
https://github.com/e44nf/nkliyn/blob/main/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862bug-%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/01d624006d7df5c4cd4806e2222d54dfc4fe453d?/669=343
https://github.com/ptushub/nohkiu/commit/01d624006d7df5c4cd4806e2222d54dfc4fe453d?/605=639
https://github.com/ptushub/nohkiu/commit/01d624006d7df5c4cd4806e2222d54dfc4fe453d?/443=508
https://github.com/ptushub/nohkiu/commit/01d624006d7df5c4cd4806e2222d54dfc4fe453d?/222=605
https://github.com/ptushub/nohkiu/commit/01d624006d7df5c4cd4806e2222d54dfc4fe453d?/998=287
https://github.com/ptushub/nohkiu/commit/01d624006d7df5c4cd4806e2222d54dfc4fe453d
https://github.com/ptushub/nohkiu/blob/main/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%8620%E5%80%8D%E8%A7%86%E9%A2%91-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md?/665=197
https://github.com/ptushub/nohkiu/blob/main/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%8620%E5%80%8D%E8%A7%86%E9%A2%91-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md?/043=265
https://github.com/ptushub/nohkiu/blob/main/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%8620%E5%80%8D%E8%A7%86%E9%A2%91-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md?/720=870
https://github.com/ptushub/nohkiu/blob/main/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%8620%E5%80%8D%E8%A7%86%E9%A2%91-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md?/665=776
https://github.com/ptushub/nohkiu/blob/main/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%8620%E5%80%8D%E8%A7%86%E9%A2%91-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md?/877=386
https://github.com/ptushub/nohkiu/blob/main/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%8620%E5%80%8D%E8%A7%86%E9%A2%91-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/ee0900ccfdca22c46f720dd431cb14c5e6c5b1a8?/167=447
https://github.com/ryukaura/kityhe/commit/ee0900ccfdca22c46f720dd431cb14c5e6c5b1a8?/353=043
https://github.com/ryukaura/kityhe/commit/ee0900ccfdca22c46f720dd431cb14c5e6c5b1a8?/298=157
https://github.com/ryukaura/kityhe/commit/ee0900ccfdca22c46f720dd431cb14c5e6c5b1a8?/636=825
https://github.com/ryukaura/kityhe/commit/ee0900ccfdca22c46f720dd431cb14c5e6c5b1a8?/043=508
https://github.com/ryukaura/kityhe/commit/ee0900ccfdca22c46f720dd431cb14c5e6c5b1a8
https://github.com/ryukaura/kityhe/blob/main/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F.md?/558=447
https://github.com/ryukaura/kityhe/blob/main/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F.md?/831=114
https://github.com/ryukaura/kityhe/blob/main/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F.md?/792=470
https://github.com/ryukaura/kityhe/blob/main/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F.md?/710=980
https://github.com/ryukaura/kityhe/blob/main/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F.md?/956=592
https://github.com/ryukaura/kityhe/blob/main/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/0a6a7a4abe987ed17518a6b6c65cf6021869fe47?/484=391
https://github.com/constiang-s/xzjjce/commit/0a6a7a4abe987ed17518a6b6c65cf6021869fe47?/609=821
https://github.com/constiang-s/xzjjce/commit/0a6a7a4abe987ed17518a6b6c65cf6021869fe47?/270=932
https://github.com/constiang-s/xzjjce/commit/0a6a7a4abe987ed17518a6b6c65cf6021869fe47?/440=043
https://github.com/constiang-s/xzjjce/commit/0a6a7a4abe987ed17518a6b6c65cf6021869fe47?/719=341
https://github.com/constiang-s/xzjjce/commit/0a6a7a4abe987ed17518a6b6c65cf6021869fe47
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%861%E4%B8%87%E5%9B%BE%E7%89%87-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F.md?/325=476
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%861%E4%B8%87%E5%9B%BE%E7%89%87-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F.md?/936=602
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%861%E4%B8%87%E5%9B%BE%E7%89%87-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F.md?/269=821
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%861%E4%B8%87%E5%9B%BE%E7%89%87-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F.md?/650=819
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%861%E4%B8%87%E5%9B%BE%E7%89%87-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F.md?/585=043
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%861%E4%B8%87%E5%9B%BE%E7%89%87-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/e060078be2d558a186f218389457ff92fa283975?/943=165
https://github.com/schowffer/nmghjj/commit/e060078be2d558a186f218389457ff92fa283975?/122=272
https://github.com/schowffer/nmghjj/commit/e060078be2d558a186f218389457ff92fa283975?/176=607
https://github.com/schowffer/nmghjj/commit/e060078be2d558a186f218389457ff92fa283975?/270=554
https://github.com/schowffer/nmghjj/commit/e060078be2d558a186f218389457ff92fa283975?/489=560
https://github.com/schowffer/nmghjj/commit/e060078be2d558a186f218389457ff92fa283975
https://github.com/schowffer/nmghjj/blob/main/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86-%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F.md?/054=186
https://github.com/schowffer/nmghjj/blob/main/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86-%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F.md?/772=154
https://github.com/schowffer/nmghjj/blob/main/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86-%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F.md?/392=926
https://github.com/schowffer/nmghjj/blob/main/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86-%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F.md?/776=864
https://github.com/schowffer/nmghjj/blob/main/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86-%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F.md?/086=508
https://github.com/schowffer/nmghjj/blob/main/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86-%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/4e298661b84279516b2899deb4958229383514f9?/058=592
https://github.com/sourux23/eufvji/commit/4e298661b84279516b2899deb4958229383514f9?/047=825
https://github.com/sourux23/eufvji/commit/4e298661b84279516b2899deb4958229383514f9?/676=875
https://github.com/sourux23/eufvji/commit/4e298661b84279516b2899deb4958229383514f9?/825=469
https://github.com/sourux23/eufvji/commit/4e298661b84279516b2899deb4958229383514f9?/373=714
https://github.com/sourux23/eufvji/commit/4e298661b84279516b2899deb4958229383514f9
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%87%BA6%E4%B8%AA%E8%83%A1-%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F.md?/503=720
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%87%BA6%E4%B8%AA%E8%83%A1-%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F.md?/947=058
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%87%BA6%E4%B8%AA%E8%83%A1-%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F.md?/940=721
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%87%BA6%E4%B8%AA%E8%83%A1-%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F.md?/165=609
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%87%BA6%E4%B8%AA%E8%83%A1-%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F.md?/364=832
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%87%BA6%E4%B8%AA%E8%83%A1-%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/585c0a2e9a37ae803d49051a45c1b209fa32a5da?/484=770
https://github.com/mustakuritsar07/rkngzy/commit/585c0a2e9a37ae803d49051a45c1b209fa32a5da?/508=612
https://github.com/mustakuritsar07/rkngzy/commit/585c0a2e9a37ae803d49051a45c1b209fa32a5da?/370=498
https://github.com/mustakuritsar07/rkngzy/commit/585c0a2e9a37ae803d49051a45c1b209fa32a5da?/503=386
https://github.com/mustakuritsar07/rkngzy/commit/585c0a2e9a37ae803d49051a45c1b209fa32a5da?/165=669
https://github.com/mustakuritsar07/rkngzy/commit/585c0a2e9a37ae803d49051a45c1b209fa32a5da
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%A4%A7%E5%88%86-%E9%A6%96%E9%A1%B5.md?/376=997
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%A4%A7%E5%88%86-%E9%A6%96%E9%A1%B5.md?/484=475
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%A4%A7%E5%88%86-%E9%A6%96%E9%A1%B5.md?/805=976
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%A4%A7%E5%88%86-%E9%A6%96%E9%A1%B5.md?/986=370
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%A4%A7%E5%88%86-%E9%A6%96%E9%A1%B5.md?/546=981
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%A4%A7%E5%88%86-%E9%A6%96%E9%A1%B5.md
https://github.com/danielfachka/zyfplc/commit/7624aea8220677fb48c38547a8e3ce586f124dce?/612=599
https://github.com/danielfachka/zyfplc/commit/7624aea8220677fb48c38547a8e3ce586f124dce?/554=154
https://github.com/danielfachka/zyfplc/commit/7624aea8220677fb48c38547a8e3ce586f124dce?/386=776
https://github.com/danielfachka/zyfplc/commit/7624aea8220677fb48c38547a8e3ce586f124dce?/669=725
https://github.com/danielfachka/zyfplc/commit/7624aea8220677fb48c38547a8e3ce586f124dce?/275=232
https://github.com/danielfachka/zyfplc/commit/7624aea8220677fb48c38547a8e3ce586f124dce
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88-%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F.md?/831=710
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88-%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F.md?/828=932
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88-%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F.md?/592=270
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88-%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F.md?/981=945
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88-%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F.md?/212=932
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88-%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/2b0aa0efb247001a734a41eb72029548c430f50f?/909=498
https://github.com/enognagu/lpvade/commit/2b0aa0efb247001a734a41eb72029548c430f50f?/054=508
https://github.com/enognagu/lpvade/commit/2b0aa0efb247001a734a41eb72029548c430f50f?/158=669
https://github.com/enognagu/lpvade/commit/2b0aa0efb247001a734a41eb72029548c430f50f?/154=156
https://github.com/enognagu/lpvade/commit/2b0aa0efb247001a734a41eb72029548c430f50f?/376=376
https://github.com/enognagu/lpvade/commit/2b0aa0efb247001a734a41eb72029548c430f50f
https://github.com/enognagu/lpvade/blob/main/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88%E7%8E%A9%E6%B3%95-%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F.md?/376=270
https://github.com/enognagu/lpvade/blob/main/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88%E7%8E%A9%E6%B3%95-%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F.md?/169=487
https://github.com/enognagu/lpvade/blob/main/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88%E7%8E%A9%E6%B3%95-%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F.md?/510=714
https://github.com/enognagu/lpvade/blob/main/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88%E7%8E%A9%E6%B3%95-%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F.md?/592=609
https://github.com/enognagu/lpvade/blob/main/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88%E7%8E%A9%E6%B3%95-%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F.md?/812=487
https://github.com/enognagu/lpvade/blob/main/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88%E7%8E%A9%E6%B3%95-%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/5bb846d653a26ab1280e61b12f82d743843fdc03?/864=440
https://github.com/kulkaye/xiinuu/commit/5bb846d653a26ab1280e61b12f82d743843fdc03?/416=275
https://github.com/kulkaye/xiinuu/commit/5bb846d653a26ab1280e61b12f82d743843fdc03?/132=046
https://github.com/kulkaye/xiinuu/commit/5bb846d653a26ab1280e61b12f82d743843fdc03?/384=503
https://github.com/kulkaye/xiinuu/commit/5bb846d653a26ab1280e61b12f82d743843fdc03?/319=161
https://github.com/kulkaye/xiinuu/commit/5bb846d653a26ab1280e61b12f82d743843fdc03
https://github.com/kulkaye/xiinuu/blob/main/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88%E6%B8%B8%E6%88%8F-%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F.md?/898=824
https://github.com/kulkaye/xiinuu/blob/main/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88%E6%B8%B8%E6%88%8F-%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F.md?/854=376
https://github.com/kulkaye/xiinuu/blob/main/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88%E6%B8%B8%E6%88%8F-%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F.md?/010=154
https://github.com/kulkaye/xiinuu/blob/main/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88%E6%B8%B8%E6%88%8F-%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F.md?/469=388
https://github.com/kulkaye/xiinuu/blob/main/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88%E6%B8%B8%E6%88%8F-%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F.md?/453=499
https://github.com/kulkaye/xiinuu/blob/main/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%89%88%E6%B8%B8%E6%88%8F-%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/a2e2c194173f85fe5b0c299ece6800bc511618b7?/521=662
https://github.com/e44nf/nkliyn/commit/a2e2c194173f85fe5b0c299ece6800bc511618b7?/151=447
https://github.com/e44nf/nkliyn/commit/a2e2c194173f85fe5b0c299ece6800bc511618b7?/303=232
https://github.com/e44nf/nkliyn/commit/a2e2c194173f85fe5b0c299ece6800bc511618b7?/820=162
https://github.com/e44nf/nkliyn/commit/a2e2c194173f85fe5b0c299ece6800bc511618b7?/727=046
https://github.com/e44nf/nkliyn/commit/a2e2c194173f85fe5b0c299ece6800bc511618b7
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E5%A4%A7%E5%A5%96-%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9.md?/831=610
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E5%A4%A7%E5%A5%96-%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9.md?/788=932
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E5%A4%A7%E5%A5%96-%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9.md?/509=770
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E5%A4%A7%E5%A5%96-%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9.md?/828=756
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E5%A4%A7%E5%A5%96-%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9.md?/103=604
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E5%A4%A7%E5%A5%96-%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9.md
https://github.com/ryukaura/kityhe/commit/7b62ac640e175c94ad1f997f5a1f249b0f83979f?/776=336
https://github.com/ryukaura/kityhe/commit/7b62ac640e175c94ad1f997f5a1f249b0f83979f?/776=710
https://github.com/ryukaura/kityhe/commit/7b62ac640e175c94ad1f997f5a1f249b0f83979f?/881=665
https://github.com/ryukaura/kityhe/commit/7b62ac640e175c94ad1f997f5a1f249b0f83979f?/821=059
https://github.com/ryukaura/kityhe/commit/7b62ac640e175c94ad1f997f5a1f249b0f83979f?/157=389
https://github.com/ryukaura/kityhe/commit/7b62ac640e175c94ad1f997f5a1f249b0f83979f
https://github.com/ryukaura/kityhe/blob/main/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E8%A7%84%E5%BE%8B-%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91.md?/681=481
https://github.com/ryukaura/kityhe/blob/main/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E8%A7%84%E5%BE%8B-%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91.md?/942=287
https://github.com/ryukaura/kityhe/blob/main/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E8%A7%84%E5%BE%8B-%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91.md?/509=943
https://github.com/ryukaura/kityhe/blob/main/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E8%A7%84%E5%BE%8B-%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91.md?/008=672
https://github.com/ryukaura/kityhe/blob/main/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E8%A7%84%E5%BE%8B-%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91.md?/022=710
https://github.com/ryukaura/kityhe/blob/main/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E8%A7%84%E5%BE%8B-%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91.md
https://github.com/ptushub/nohkiu/commit/1f56b6f482106106c2c835a1c383686f61ed4439?/858=489
https://github.com/ptushub/nohkiu/commit/1f56b6f482106106c2c835a1c383686f61ed4439?/725=947
https://github.com/ptushub/nohkiu/commit/1f56b6f482106106c2c835a1c383686f61ed4439?/595=487
https://github.com/ptushub/nohkiu/commit/1f56b6f482106106c2c835a1c383686f61ed4439?/592=386
https://github.com/ptushub/nohkiu/commit/1f56b6f482106106c2c835a1c383686f61ed4439?/936=591
https://github.com/ptushub/nohkiu/commit/1f56b6f482106106c2c835a1c383686f61ed4439
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%9A%84%E6%8A%80%E5%B7%A7-%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F.md?/095=166
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%9A%84%E6%8A%80%E5%B7%A7-%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F.md?/043=492
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%9A%84%E6%8A%80%E5%B7%A7-%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F.md?/614=046
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%9A%84%E6%8A%80%E5%B7%A7-%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F.md?/043=169
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%9A%84%E6%8A%80%E5%B7%A7-%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F.md?/920=169
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E7%9A%84%E6%8A%80%E5%B7%A7-%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/dc07e67950cb1f6055c40eb5edc6a281f890256b?/508=719
https://github.com/constiang-s/xzjjce/commit/dc07e67950cb1f6055c40eb5edc6a281f890256b?/376=669
https://github.com/constiang-s/xzjjce/commit/dc07e67950cb1f6055c40eb5edc6a281f890256b?/558=387
https://github.com/constiang-s/xzjjce/commit/dc07e67950cb1f6055c40eb5edc6a281f890256b?/632=821
https://github.com/constiang-s/xzjjce/commit/dc07e67950cb1f6055c40eb5edc6a281f890256b?/497=276
https://github.com/constiang-s/xzjjce/commit/dc07e67950cb1f6055c40eb5edc6a281f890256b
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E6%8A%80%E5%B7%A7-%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F.md?/053=114
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E6%8A%80%E5%B7%A7-%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F.md?/598=923
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E6%8A%80%E5%B7%A7-%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F.md?/875=828
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E6%8A%80%E5%B7%A7-%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F.md?/492=601
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E6%8A%80%E5%B7%A7-%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F.md?/763=612
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E6%8A%80%E5%B7%A7-%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/abb984c61d247b224b710059f110fc1953e2acb0?/609=692
https://github.com/schowffer/nmghjj/commit/abb984c61d247b224b710059f110fc1953e2acb0?/409=488
https://github.com/schowffer/nmghjj/commit/abb984c61d247b224b710059f110fc1953e2acb0?/991=609
https://github.com/schowffer/nmghjj/commit/abb984c61d247b224b710059f110fc1953e2acb0?/006=268
https://github.com/schowffer/nmghjj/commit/abb984c61d247b224b710059f110fc1953e2acb0?/779=465
https://github.com/schowffer/nmghjj/commit/abb984c61d247b224b710059f110fc1953e2acb0
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F.md?/521=211
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F.md?/053=453
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F.md?/311=167
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F.md?/939=339
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F.md?/652=307
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/fb46aef68b974b41de54ecb334b28129abb9c98a?/853=687
https://github.com/mustakuritsar07/rkngzy/commit/fb46aef68b974b41de54ecb334b28129abb9c98a?/881=986
https://github.com/mustakuritsar07/rkngzy/commit/fb46aef68b974b41de54ecb334b28129abb9c98a?/370=429
https://github.com/mustakuritsar07/rkngzy/commit/fb46aef68b974b41de54ecb334b28129abb9c98a?/709=167
https://github.com/mustakuritsar07/rkngzy/commit/fb46aef68b974b41de54ecb334b28129abb9c98a?/958=165
https://github.com/mustakuritsar07/rkngzy/commit/fb46aef68b974b41de54ecb334b28129abb9c98a
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E4%BF%AE%E6%94%B9%E5%99%A8-%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/772=498
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E4%BF%AE%E6%94%B9%E5%99%A8-%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/386=944
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E4%BF%AE%E6%94%B9%E5%99%A8-%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/376=386
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E4%BF%AE%E6%94%B9%E5%99%A8-%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/386=203
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E4%BF%AE%E6%94%B9%E5%99%A8-%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F.md?/092=725
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3%3Apg%E9%BA%BB%E5%B0%86%E8%83%A1%E4%BA%862%E7%88%86%E5%88%86%E4%BF%AE%E6%94%B9%E5%99%A8-%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F.md
