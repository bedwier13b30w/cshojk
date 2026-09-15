百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
收诤痹持盏锥锥照淳岩踪犯团嘎菩

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

https://github.com/danielfachka/zyfplc/commit/5fdc2e2f594a5169fd6928bec55c3b2292281647
https://github.com/danielfachka/zyfplc/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88.md
https://github.com/kulkaye/xiinuu/commit/591c28e5a302f4b949b1c9a68f79a002147550a3
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/enognagu/lpvade/commit/fc55f49d5a8b58926a68100908839f709459d14b
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/04e9b70857ca3b9baa2ac1c0812910538a430e3f
https://github.com/ptushub/nohkiu/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/5f9b9da38fce957bda0d538256634b479f984f21
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/25730392d8a3a905bcdd239f56c324e06492f041
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/0c724daaf704f520d25e9f956b7888abdc916cc8
https://github.com/constiang-s/xzjjce/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md
https://github.com/e44nf/nkliyn/commit/02b0b0c9f7e04615bf66caaf69db17177270f3d1
https://github.com/e44nf/nkliyn/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/sourux23/eufvji/commit/ce0c72ffc74db223ac891705b09cebb50cdd6ef3
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88.md
https://github.com/danielfachka/zyfplc/commit/9e2ce599de5e94db9613f5e0b27fdbc9d0db8215
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/d8b53a8855c6e1762f728b5cdffc7fe145e700d8
https://github.com/ryukaura/kityhe/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3Apg%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%20-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/enognagu/lpvade/commit/165ff1e06bdddee4c974fb310b446af92a5111e7
https://github.com/enognagu/lpvade/blob/main/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86.md
https://github.com/kulkaye/xiinuu/commit/71fc6f765fd322243699144989aa062be81935d5
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/616938dfb78b35e7fae6af312b929c12f97e42e3
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md
https://github.com/mustakuritsar07/rkngzy/commit/c71d5aafcd65fb609034b632f9accd1affd1db9a
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/1cfa9f6d0ce45b686967222d1d77cc594204e05d
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md
https://github.com/ptushub/nohkiu/commit/06b5cb5986bd25567ef3be79ca643ee47a21e724
https://github.com/ptushub/nohkiu/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E8%B6%85%E5%87%A1%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE.md
https://github.com/e44nf/nkliyn/commit/04d6bb5f88cedb9fb45cea3d2cafe0411dce7a56
https://github.com/e44nf/nkliyn/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md
https://github.com/sourux23/eufvji/commit/d498436f73b10838aae83d989841df3bbab60f47
https://github.com/sourux23/eufvji/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/danielfachka/zyfplc/commit/6fc621ac53d34ff942a70d3b8666d618f45538b2
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97%3A%E8%B6%85%E5%87%A1%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md
https://github.com/ryukaura/kityhe/commit/373ee7af18d56412393af185a5f3b07efb04027c
https://github.com/ryukaura/kityhe/blob/main/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF.md
https://github.com/enognagu/lpvade/commit/a064518a11dd74b54db10b7332ea23fc28795012
https://github.com/enognagu/lpvade/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/a66daa264dadfae8a98a73ab5e5359eae14157b0
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md
https://github.com/kulkaye/xiinuu/commit/e35ae5b5358250837e2749b061d630f1db1a7f6c
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md
https://github.com/mustakuritsar07/rkngzy/commit/2bc468feb05f96d2d1aacdf40664edd272a5852f
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/constiang-s/xzjjce/commit/55c17e092d62fe18ea942bfe08dadb539958f050
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3%E9%93%BE%E6%8E%A5-360%E9%80%9A%E4%BF%A1.md
https://github.com/ptushub/nohkiu/commit/223a50cf9982ca561431075f0fb97e79bda7582d
https://github.com/ptushub/nohkiu/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/d1c4cff88404dd5d74953d1f8b165444bc09a9fd
https://github.com/e44nf/nkliyn/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/3751086460b04618b199275a57a19bd22218ea41
https://github.com/sourux23/eufvji/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md
https://github.com/danielfachka/zyfplc/commit/050ebaf08d7fea6d7ac5ba2f70213293ef533c50
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/ryukaura/kityhe/commit/f09c34533271bb4ce4834ea5de01dd7c98735a62
https://github.com/ryukaura/kityhe/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md
https://github.com/enognagu/lpvade/commit/bb5971d44ccf273474326938967a98cf5d1b3a01
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/5117eeda80e36a8e4f032640f6ca500f2ac812f6
https://github.com/schowffer/nmghjj/blob/main/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F.md
https://github.com/mustakuritsar07/rkngzy/commit/6abf346e036ad0eff0542786a9f3d2ca457cafa8
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88.md
https://github.com/constiang-s/xzjjce/commit/a0778b2ca3bcc9e9a184f9305ce2d03f288d447a
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C%3A28%E5%9C%88%E5%A8%B1%E4%B9%90app%20-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md
https://github.com/ptushub/nohkiu/commit/59be8427624a8b127a1c159793424f9d041a9d0e
https://github.com/ptushub/nohkiu/blob/main/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA%3A28%E5%9C%88%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md
https://github.com/kulkaye/xiinuu/commit/b239d60ee8e8a434411482885e2ab59d4ebded70
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%20-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB.md
https://github.com/e44nf/nkliyn/commit/2fe78b8d266bcc9cb785bed7d42eb7837147d66b
https://github.com/e44nf/nkliyn/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A28%E5%9C%88%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/69bef42c39124877f3062d7b282cab7b1d873c8b
https://github.com/sourux23/eufvji/blob/main/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA%3A28%E5%9C%88%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/1c08bf50590a300ceed8c262395d96c3ff7b65c7
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/eb302a5dea2e2ea5e9a18582e3511b22ee70f306
https://github.com/ryukaura/kityhe/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/10e83a3b8c410ba8befcaf3a85d5db7bbb7844cd
https://github.com/enognagu/lpvade/blob/main/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-360%E9%80%9A%E4%BF%A1.md
https://github.com/schowffer/nmghjj/commit/217e402aca2de7d184e6a40d1a4dd09d24ff0031
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md
https://github.com/mustakuritsar07/rkngzy/commit/b7ca12f4eed5248a086bc54fe43c5efbf14b9d21
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md
https://github.com/constiang-s/xzjjce/commit/e80da424b971b60382a1455a5fbd213dc55ee513
https://github.com/constiang-s/xzjjce/blob/main/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92%3Apg28%E5%9C%88%E5%A8%B1%E4%B9%90%20-36%E6%B0%AA%E6%B1%BD%E8%BD%A6.md
https://github.com/ptushub/nohkiu/commit/7f83e315729d2b2c35a64e73a3b74b1e6fd340a5
https://github.com/ptushub/nohkiu/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3Apg28%E5%9C%88%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE.md
https://github.com/kulkaye/xiinuu/commit/b660eb434a365fde9b6a8d0a4e95524c8e31fd70
https://github.com/kulkaye/xiinuu/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg28%E5%9C%88%E5%A8%B1%E4%B9%90app%20-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md
https://github.com/e44nf/nkliyn/commit/be3fdd3dde62e859846e7a6827043087cb6db103
https://github.com/e44nf/nkliyn/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3Apg28%E5%9C%88%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md
https://github.com/sourux23/eufvji/commit/26f71dfca937b0b6655f558a2a01ea6ae2fe2dec
https://github.com/sourux23/eufvji/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg28%E5%9C%88%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md
https://github.com/danielfachka/zyfplc/commit/a33240d77f3cb72ac6f29e5126cb5274248c1149
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3Apg28%E5%9C%88%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86.md
https://github.com/enognagu/lpvade/commit/fa6d22d233a52e1f44b6ecd6d9115570324f7cfb
https://github.com/enognagu/lpvade/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/e2275f9ef2a448923aba9f311f7c3e533fc1876c
https://github.com/ryukaura/kityhe/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md
https://github.com/mustakuritsar07/rkngzy/commit/1778c8dc7c61f302519110084d2ada8d11c9f01e
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88.md
https://github.com/schowffer/nmghjj/commit/4661dafc1e2b0b6479c1da0518efa9af8e56f860
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/constiang-s/xzjjce/commit/72aaa7aa811df6fd0bf86979a7c6eff0146bf7e0
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3Apg28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9.md
https://github.com/ptushub/nohkiu/commit/dc1c5039c99e8a6cb650f48518800262b0c95c70
https://github.com/ptushub/nohkiu/blob/main/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%20-360%E9%80%9A%E4%BF%A1.md
https://github.com/kulkaye/xiinuu/commit/381910f16cc59d2253a531e9decfb74a90f128d8
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md
https://github.com/e44nf/nkliyn/commit/49c03d36a31185664cdf123c8a1fc999654fcd22
https://github.com/e44nf/nkliyn/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/sourux23/eufvji/commit/c2db34a6c29c126867af8e4a797574619a51c7d3
https://github.com/sourux23/eufvji/blob/main/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/b2ac4c5c05f35e8ac5a71347ae1a1fc524878f4b
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/enognagu/lpvade/commit/37e58d89bb1b6f60a7d00a88e349522c1ddf81d4
https://github.com/enognagu/lpvade/blob/main/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md
https://github.com/ryukaura/kityhe/commit/574fc80e0828d5f01a453617442bb8b5cae0f14f
https://github.com/ryukaura/kityhe/blob/main/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/7b028ea02523381499d7413ee648573f428ad3ee
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/schowffer/nmghjj/commit/4ad88d4813d9a969e264054ec02aa4e5e0318b89
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/d9751c4025c71fdfe52c36a75d44ac49dc419da9
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/ptushub/nohkiu/commit/cce68efe9353232df1b958f37d6f8bb678b924a5
https://github.com/ptushub/nohkiu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95.md
https://github.com/e44nf/nkliyn/commit/7252247459e5f052aa766ddbc8786f314a3fa9c4
https://github.com/e44nf/nkliyn/blob/main/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-36%E6%B0%AA%E6%B1%BD%E8%BD%A6.md
https://github.com/kulkaye/xiinuu/commit/dcc3db635c465a4b3ecf88279a0515d20efe75cc
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93%3Apg28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%20-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/sourux23/eufvji/commit/2e29b50e734de4c7aa568c67e148c432b5022e08
https://github.com/sourux23/eufvji/blob/main/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md
https://github.com/danielfachka/zyfplc/commit/e984ad7b84769bbf9f619080f9e0bf530eed3af7
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95.md
https://github.com/enognagu/lpvade/commit/2129c49283aca8921691cc0d62146473e9545dcf
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/ryukaura/kityhe/commit/20b3616db3518d546a6f7dc405e0f23adeaaecd2
https://github.com/ryukaura/kityhe/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A28%E5%9C%88%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md
https://github.com/mustakuritsar07/rkngzy/commit/ac7d6e7fc351f177a2b0cbccfe8de5966ccad0a5
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md
https://github.com/constiang-s/xzjjce/commit/074de2b9df20e5c0b80621bcd527c98bf0248490
https://github.com/constiang-s/xzjjce/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md
https://github.com/schowffer/nmghjj/commit/cda48937f97fd7a571270cc34358a5509e98048b
https://github.com/schowffer/nmghjj/blob/main/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/8665eaa9ac82fe751307b8343a53c8ccd3310898
https://github.com/e44nf/nkliyn/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/ptushub/nohkiu/commit/841a0d9c93c63e75d4058309bab6dbfa1eacdf8e
https://github.com/ptushub/nohkiu/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A28%E5%9C%88%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md
https://github.com/kulkaye/xiinuu/commit/9a9ac1d6ac4c03f9f75ede7eaea6774ee0e5a73a
https://github.com/kulkaye/xiinuu/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/sourux23/eufvji/commit/ded9ec9f7f55f536eef544e3fcf5a5e3db02e5b3
https://github.com/sourux23/eufvji/blob/main/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA%3Apg%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0-%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/3f4e83d7e919ac4c3f146a66892849afe69d1553
https://github.com/enognagu/lpvade/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3Apg%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-360%E5%8E%86%E5%8F%B2.md
https://github.com/ryukaura/kityhe/commit/80db8de363b14e717f5d15a27767908090dd0940
https://github.com/ryukaura/kityhe/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3Apg%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4.md
https://github.com/danielfachka/zyfplc/commit/98f93a90d1a81e84a94f1c50676c04732e7e268f
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3Apg%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/c1ed54749345c2a647a3f558ad058d0333b18dc1
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3Apg%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3%E9%93%BE%E6%8E%A5-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/constiang-s/xzjjce/commit/73d6c41d446afdd5bad2cb194dac39be783e4019
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3Apg%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/schowffer/nmghjj/commit/5de4940d99e3f1afdd403b0c9911e8180d22a61a
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3Apg%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md
https://github.com/e44nf/nkliyn/commit/1e3c17f7aa76fe66e03814b041886541fe6a3b34
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89%3Apg%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md
https://github.com/ptushub/nohkiu/commit/14c0ef48845ab88d2f155f431aa2f28fe34ae80b
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3Apg%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md
https://github.com/kulkaye/xiinuu/commit/60c0507d700267115a15c332ccdbbf756b0ab2e2
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/sourux23/eufvji/commit/9fd045a8578ad727f8512ec82e175f65279a29ed
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99%3A%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/ryukaura/kityhe/commit/88de188efd352b442178d9513657bf1334f176fe
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90%20-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md
https://github.com/danielfachka/zyfplc/commit/79a8721799efec042e94fe4955f450f0026822c4
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92%3A%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md
https://github.com/enognagu/lpvade/commit/c9838d4a987b2787453e102f7baf3d1b5f736eea
https://github.com/enognagu/lpvade/blob/main/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md
https://github.com/mustakuritsar07/rkngzy/commit/f0c10f8a46b0cccf3861881d65839573a5842e1d
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90app%20-%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90.md
https://github.com/constiang-s/xzjjce/commit/0cedddc2706b61b2a27f4849ab6d58fd06f0f74b
https://github.com/constiang-s/xzjjce/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/schowffer/nmghjj/commit/c2829e38f710ed1e82cfeb61dd7fb194b6d081f7
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-36%E6%B0%AA%E6%B1%BD%E8%BD%A6.md
https://github.com/e44nf/nkliyn/commit/c20f772fd4450b59bca0851083b03c5369726c55
https://github.com/e44nf/nkliyn/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md
https://github.com/kulkaye/xiinuu/commit/e2351de9cd6f4b20fd14bd854dab2088e7c5e8ba
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md
https://github.com/ptushub/nohkiu/commit/35087b362e59ccb7fcac1fc0bc9f243ea71d1f91
https://github.com/ptushub/nohkiu/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/e52d89551fbea0abf35acbec125e28ab8213d79a
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/danielfachka/zyfplc/commit/4d57eadfcdaefd663b3365f0695b2d381daf6ac0
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF%3A%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md
https://github.com/ryukaura/kityhe/commit/09522d8b0ca0946299cc5adcc23fbe34f863086c
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/enognagu/lpvade/commit/3e5cb8ebec0b6154676528572591d1a717a06fdd
https://github.com/enognagu/lpvade/blob/main/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92%3Apg%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90%20-%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/e0bfaa755a42151171b5432ea60edbabaacce280
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/constiang-s/xzjjce/commit/a9716e3ecc9babb4a3f73835c22410f9cca5658b
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3Apg%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90app%20-%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88.md
https://github.com/schowffer/nmghjj/commit/c6ea716a06a903e82867bc605d0dd3a4878da244
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0%3Apg%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/kulkaye/xiinuu/commit/d8db6220335852acfd3a4ed1f96f0bc84ed6a325
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99%3Apg%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E6%90%9C%E7%8B%90%E6%91%84%E5%BD%B1.md
https://github.com/e44nf/nkliyn/commit/ed35502e5c5191be7da34fa720e025cd9b138299
https://github.com/e44nf/nkliyn/blob/main/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BC%98%E6%8D%B7%E6%95%B0%E7%A0%81.md
https://github.com/ptushub/nohkiu/commit/125409fb5dac86728f67443ee98343d77f2ce549
https://github.com/ptushub/nohkiu/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/891ac1bb7fd90c24268334a437e7bf01906ad68e
https://github.com/sourux23/eufvji/blob/main/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8%3Apg%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md
https://github.com/enognagu/lpvade/commit/9eef87ba14a7b935e50724b7d6128be0bf6ec700
https://github.com/enognagu/lpvade/blob/main/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91%3Apg%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md
https://github.com/danielfachka/zyfplc/commit/5bd8364855b8dcdda00dec57f36cdafe8719c312
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3Apg%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md
https://github.com/ryukaura/kityhe/commit/01eae1d67b68c8b620ff8669d98d5588cafe5b36
https://github.com/ryukaura/kityhe/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3Apg%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md
https://github.com/mustakuritsar07/rkngzy/commit/1776e51198ae858f699691c2e489ee0b01e40f8a
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%20-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/a7647c97385d51fe014d6577dfe77286f98d0378
https://github.com/constiang-s/xzjjce/blob/main/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB%3A%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/313abff4ea7e71fe1a3cea80069e6843b72cf6d3
https://github.com/schowffer/nmghjj/blob/main/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5%3A%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE.md
https://github.com/kulkaye/xiinuu/commit/70a2010a3f6a57056d4d9259cd02a02ddc6af222
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/d8616effaad3062bf499fe464aaa0b3e31be155c
https://github.com/e44nf/nkliyn/blob/main/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8%3A%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/7cb1536c5667ca02352386ddff7298312999e1d0
https://github.com/sourux23/eufvji/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/ptushub/nohkiu/commit/a8aa57bb8a2c368b5c60d9aa857df67336bce8ac
https://github.com/ptushub/nohkiu/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-360%E8%A7%86%E9%A2%91.md
https://github.com/ryukaura/kityhe/commit/b16190aa5462333d44d27095f7eebf63cd33243f
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99%3A%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88.md
https://github.com/danielfachka/zyfplc/commit/3165546ab54891dda66f74ffd2a58ecff72e2f51
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/mustakuritsar07/rkngzy/commit/1580ec49f4f38b34116563294bb37b862ecf168f
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/constiang-s/xzjjce/commit/d336c7cc101fc3397a1aef058119e0b78e64ec9b
https://github.com/constiang-s/xzjjce/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3Apg%E9%A2%86%E8%88%AA%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%20-%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86.md
https://github.com/enognagu/lpvade/commit/d0d57f51b08a5fe92fa9004c931cf84ee75a377c
https://github.com/enognagu/lpvade/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E9%A2%86%E8%88%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
