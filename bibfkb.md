百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
只怨共牙诹恢怨费嫉虏灼攘诶涸趁

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

https://github.com/ryukaura/kityhe/commit/15f93baeee2e6016667995c5c8b56930d452eabf
https://github.com/ryukaura/kityhe/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C-%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86.md
https://github.com/schowffer/nmghjj/commit/6262f401e6fe431fd064dba19248968896d4a32e
https://github.com/schowffer/nmghjj/blob/main/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/de5b53d4cf88b282d9c1ad1cbf1157838e0d9dd7
https://github.com/e44nf/nkliyn/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/f4ef4db89a9f8ed029abe7458b0daa0f5d24f75d
https://github.com/constiang-s/xzjjce/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/mustakuritsar07/rkngzy/commit/65172217e206b38487c0d7e735eb850eb1e5d736
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA%3Apg%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md
https://github.com/enognagu/lpvade/commit/a996447feef113fc2d312206597a65dd0c03c6cc
https://github.com/enognagu/lpvade/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/danielfachka/zyfplc/commit/a1d39f190b7702d119f839098afc117dab977131
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/kulkaye/xiinuu/commit/d7b115d2a794588c72c92f5bc48ca1df29b0db5d
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/ptushub/nohkiu/commit/006f1dee81d409dcb6a82978b3d1e99451350ed9
https://github.com/ptushub/nohkiu/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BA%BF%E4%B8%8728%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/sourux23/eufvji/commit/946ebbf8399e43e5a67f9500362279426a98c0d7
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95.md
https://github.com/ryukaura/kityhe/commit/df2a40a8628a411433d201f40accd22ebc359bdd
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/e44nf/nkliyn/commit/2916986193b3599144834d7adb1532d8bb956c96
https://github.com/e44nf/nkliyn/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md
https://github.com/constiang-s/xzjjce/commit/f2bdda8bbdc7594d21c5651bbafe866d0e198393
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/ed4e7ad709304e15a935a3b835facb178e9dda88
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E4%BA%BF%E4%B8%8728%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/93cdca34acb8f95b7b9fcb9c2f68dcf4ddd93e0e
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E5%A4%9A%E5%A4%9A28%E5%A4%A7%E8%88%9E%E5%8F%B0-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md
https://github.com/enognagu/lpvade/commit/bcd5e67780a2e5e6a7a18f3884b95fc95a7ea0b5
https://github.com/enognagu/lpvade/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3Apg%E5%A4%9A%E5%A4%9A28%E5%A4%A7%E8%88%9E%E5%8F%B0-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/781a786394c252040b648da1109995c890dbdc3d
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3Apg%E5%A4%9A%E5%A4%9A28%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/kulkaye/xiinuu/commit/53b734731a162f7d62ac2daf740c90aeb281b107
https://github.com/kulkaye/xiinuu/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3Apg%E5%A4%9A%E5%A4%9A28%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/ptushub/nohkiu/commit/f0a224224ebb038ffc784938e17a9429593211ea
https://github.com/ptushub/nohkiu/blob/main/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97%3Apg%E5%A4%9A%E5%A4%9A28%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/ryukaura/kityhe/commit/0eb17f9abbe561fa448ec4589201b6eec2804a2a
https://github.com/ryukaura/kityhe/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3Apg%E5%A4%9A%E5%A4%9A28%E5%B9%B3%E5%8F%B0-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/747c651660a42e6a2dcdff7b12375e1789bc22ff
https://github.com/sourux23/eufvji/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3Apg%E5%A4%9A%E5%A4%9A28%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3%E9%93%BE%E6%8E%A5-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md
https://github.com/constiang-s/xzjjce/commit/24f48ae5a92c30892c5bdee23ba8d1eaceddcd61
https://github.com/constiang-s/xzjjce/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3Apg%E5%A4%9A%E5%A4%9A28%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/fa60890c1ec3436415352d99e36ab5fab91c1efd
https://github.com/e44nf/nkliyn/blob/main/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA%3Apg%E5%A4%9A%E5%A4%9A28%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/schowffer/nmghjj/commit/210db52b451695d4a46ef8210e715e7aa97c1b77
https://github.com/schowffer/nmghjj/blob/main/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8%3Apg%E5%A4%9A%E5%A4%9A28%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88.md
https://github.com/mustakuritsar07/rkngzy/commit/1572cb47fdd3c03f677962bea97b174de445f3e6
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E5%A4%9A%E5%A4%9A28%E5%B9%B3%E5%8F%B0-%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8.md
https://github.com/enognagu/lpvade/commit/a9f42787f0e8e730a150a3c1a6f59c0c073e93f4
https://github.com/enognagu/lpvade/blob/main/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF%3A%E5%A4%9A%E5%A4%9A28%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E6%90%9C%E7%8B%90%E6%91%84%E5%BD%B1.md
https://github.com/danielfachka/zyfplc/commit/046523b2ff8ef050d9ce26f49f59091fa98da7d9
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E5%A4%9A%E5%A4%9A28%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90.md
https://github.com/kulkaye/xiinuu/commit/f6a198718e88e788d97e3b62a73f4648bf0ee47d
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%20-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF.md
https://github.com/ptushub/nohkiu/commit/e377b0fed350bdca248b8e6e0d9a33ff1863f43e
https://github.com/ptushub/nohkiu/blob/main/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/ryukaura/kityhe/commit/70a158044cf39adc842041c3fccc60552d131327
https://github.com/ryukaura/kityhe/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/94cba40179fffc59360e6c6bab0de94441228884
https://github.com/sourux23/eufvji/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95.md
https://github.com/schowffer/nmghjj/commit/30ce0ccd0fde73f33b3ad6256e368b38061acaa2
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md
https://github.com/constiang-s/xzjjce/commit/7c40c1e4a7f04833b15a2d09347ca75983ed7d68
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/mustakuritsar07/rkngzy/commit/bdfe6edd8f9fb0aae6e619a022eac63f8850f172
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/e44nf/nkliyn/commit/72493de87eb06b2426820f8cd995e5a8cf9aa886
https://github.com/e44nf/nkliyn/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/enognagu/lpvade/commit/7376657b0b96e05d9a4378b0be83117e766f8821
https://github.com/enognagu/lpvade/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md
https://github.com/danielfachka/zyfplc/commit/31314ac681db06c5efc616ccb17e6e52cb380c23
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/kulkaye/xiinuu/commit/34564cfcc76c21db5f5e05c889ed109964bbeeba
https://github.com/kulkaye/xiinuu/blob/main/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md
https://github.com/sourux23/eufvji/commit/b2afb01f299dc5a70f18617f3c50d69332b89c5d
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3Apg%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app%20-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/ptushub/nohkiu/commit/c30c878f62a82781214fd25f4098e9f1a613a82c
https://github.com/ptushub/nohkiu/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3Apg%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%20-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/ryukaura/kityhe/commit/8fecb86780ed3dd134a4180960855588c4530c86
https://github.com/ryukaura/kityhe/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3Apg%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/constiang-s/xzjjce/commit/01e38f09dda08e0988f324c5d7d67d17780d9895
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3Apg%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/23f5077c293a69a275ecce03074bf433e4b59b4e
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA.md
https://github.com/schowffer/nmghjj/commit/f68a4f118e39fec6838970f8bf2dcdce0b2cf307
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3Apg%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86.md
https://github.com/enognagu/lpvade/commit/e844c3ed51b13c2534315fa899e0f43317743035
https://github.com/enognagu/lpvade/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3Apg%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/e44nf/nkliyn/commit/5181fedab9e9a9c3e898e3ad43cd95d1acceefc8
https://github.com/e44nf/nkliyn/blob/main/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99%3Apg%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/danielfachka/zyfplc/commit/3ee41df423cc336774d02dac34304b384307fcf1
https://github.com/danielfachka/zyfplc/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3Apg%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md
https://github.com/kulkaye/xiinuu/commit/0ccc1eb913f3d802c9f6ba8977d2ec70e88c428e
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3Apg%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/sourux23/eufvji/commit/145c088f5a3ac65af95e1387fa8bc262a8ddbc97
https://github.com/sourux23/eufvji/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3Apg%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/ryukaura/kityhe/commit/174c4c0c177d2d403f4705ee0e52e28e0534425f
https://github.com/ryukaura/kityhe/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95.md
https://github.com/ptushub/nohkiu/commit/d26369dd088d9256b2e34a01064b410d84fd77fd
https://github.com/ptushub/nohkiu/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%20-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/43fd3cfcce29e88c5ed60f1d7a88526bcdc7a6c6
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md
https://github.com/e44nf/nkliyn/commit/b7486276738180b8ca2a3cee20be04575ee510d3
https://github.com/e44nf/nkliyn/blob/main/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/bf8d42b21cb8799d54d5713ba234d8974a09d137
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/constiang-s/xzjjce/commit/5493d21a01d59065ab79b26b4a7dbfded6ab72f7
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/enognagu/lpvade/commit/61ff35f23d5c320106e91bda6e5c573060f80ee4
https://github.com/enognagu/lpvade/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/danielfachka/zyfplc/commit/24b04d08788343fc949b53494ffb9471fe9c10aa
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/kulkaye/xiinuu/commit/f80ff31d358f12b0e4a8aacae2fedc4e102a28a6
https://github.com/kulkaye/xiinuu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0.md
https://github.com/sourux23/eufvji/commit/a86adeee18f7628a5f74d197174fa3020e0f5755
https://github.com/sourux23/eufvji/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/ryukaura/kityhe/commit/2feef4e651e8bc8dbc17fc39b3275c79c32eed0b
https://github.com/ryukaura/kityhe/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/ptushub/nohkiu/commit/248014be0c2a3f16de7bd133c453b90001fb8277
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3Apg%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%20-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/f26bdb39e091aa8168621d68785824e70b731fdf
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E9%A6%96%E8%A6%81%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/727d87562358b9d0e24e78614df27a373bc56186
https://github.com/e44nf/nkliyn/blob/main/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/d6e25c62ebb723f0233906cf180198eca5ea7ea3
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/constiang-s/xzjjce/commit/f20a9840193659d9c8136ae6df9599fbc15cac5a
https://github.com/constiang-s/xzjjce/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/e86113523d857766e1cfa6aeb9f544160cc86b01
https://github.com/enognagu/lpvade/blob/main/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/9907209ecffd66a05a08c3a5909b8c31a61274e3
https://github.com/schowffer/nmghjj/blob/main/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89%3A%E5%A4%9A%E5%A4%9A28%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E6%90%9C%E7%8B%90%E6%91%84%E5%BD%B1.md
https://github.com/kulkaye/xiinuu/commit/7b3c3292c21b78c95995968b5486a4ece23c9123
https://github.com/kulkaye/xiinuu/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E5%BF%85%E5%BA%94.md
https://github.com/sourux23/eufvji/commit/868b41b81f523a0d370209ae22447a10b76d8a99
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/76473a94134c96bbd9e9da0b7829d3abb5b0a687
https://github.com/ryukaura/kityhe/blob/main/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/ptushub/nohkiu/commit/3aeb4049e91fd8decef1a953c0904d59593d3866
https://github.com/ptushub/nohkiu/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E5%A4%9A%E5%A4%9A28%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/mustakuritsar07/rkngzy/commit/a9cfbc96f5f494c67fbf04914db6c792b635654c
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3A%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90%20-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/50581d1734604f0c0accba237a69f7663e0be058
https://github.com/e44nf/nkliyn/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/danielfachka/zyfplc/commit/9bc4c94c73ba81105a93f539158d32235e2ecbc9
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90app%20-%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4.md
https://github.com/constiang-s/xzjjce/commit/66845501cfb282f08b07e9b50ec9306628c8b8f4
https://github.com/constiang-s/xzjjce/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF.md
https://github.com/kulkaye/xiinuu/commit/b87aba858e91009abf9c93dd1641fdf2ca0d4201
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/4d9896a303a5abcdef55ef7101a5a41dfedd810e
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md
https://github.com/sourux23/eufvji/commit/c59717e0cc4acf781baa3ff6e06758cf2d513fd6
https://github.com/sourux23/eufvji/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/enognagu/lpvade/commit/c8f7948d98fdd70104931f199aa334b96a6e9854
https://github.com/enognagu/lpvade/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/ec6789bb7c5e4ba989e74a5b7303928e44c40663
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/9cc1386ba729e53ee4c11c015495e9bfaee89caf
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/mustakuritsar07/rkngzy/commit/6b1ab10a48232446900e5bc9d81c8e9d5e76228f
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E4%BC%98%E6%8D%B7%E6%95%B0%E7%A0%81.md
https://github.com/e44nf/nkliyn/commit/8d087f8c6331b9f4c4e50066e7e1d417bcec6322
https://github.com/e44nf/nkliyn/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90%20-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md
https://github.com/constiang-s/xzjjce/commit/f7158fd8b546b399de833997535d80a69b0799b9
https://github.com/constiang-s/xzjjce/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3Apg%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90app%20-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/danielfachka/zyfplc/commit/e2182eb733a14e0c49f24da4575a6684fa2e255f
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF%3Apg%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/ryukaura/kityhe/commit/d0ef38606ebe176bc8afd440591ed1e9021359f1
https://github.com/ryukaura/kityhe/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/kulkaye/xiinuu/commit/515c8697a6f437e7079ab94c5b51826b55260e33
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/sourux23/eufvji/commit/78ca0480047fdf46d5e485887fd155ca4cae9145
https://github.com/sourux23/eufvji/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E5%BE%81%E9%80%94%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md
https://github.com/enognagu/lpvade/commit/fdd8fbd4b0bd8113b6a63365a78c5027b44700e3
https://github.com/enognagu/lpvade/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/schowffer/nmghjj/commit/bee378c475f8bacd3591e1b049f0ca8fbfb6e6d1
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9%3Apg%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/ptushub/nohkiu/commit/08ca70351d7523a8c79fd27552193b565e598471
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F%3Apg%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF.md
https://github.com/e44nf/nkliyn/commit/da9628cdc1fd9417b70df9c6b399ce0568294c69
https://github.com/e44nf/nkliyn/blob/main/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4%3Apg%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/56652ccbc21fb5857a339f947e9802585d8e2719
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99%3Apg%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md
https://github.com/constiang-s/xzjjce/commit/81fb4fb6ec528b576f1cd48d13f7b157e8fbcba4
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md
https://github.com/danielfachka/zyfplc/commit/8cf87c00cf1c98f249d619bc3c722b4bc685c79c
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A%3Apg%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/38004fe3e84487fe14b3baa4731c00a6f180f231
https://github.com/ryukaura/kityhe/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3Apg%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/sourux23/eufvji/commit/b460b12fc92398e1828292605c3698d339a399d7
https://github.com/sourux23/eufvji/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88.md
https://github.com/enognagu/lpvade/commit/9e38275e779d4b94fb5a7bad8cbde73a205f2dee
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3Apg%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3%E9%93%BE%E6%8E%A5-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md
https://github.com/kulkaye/xiinuu/commit/afd7e9da9333b1b97aeb45d0753a70bae7d2ab6e
https://github.com/kulkaye/xiinuu/blob/main/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/8c6f674d26723d5cfac14237dbb4a6012f4deae3
https://github.com/schowffer/nmghjj/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3Apg%E5%BE%81%E9%80%94%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F.md
