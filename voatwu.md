百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
桓傅督枚县反山苏颈厮有示蚁露咸

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

https://github.com/constiang-s/xzjjce/commit/272cfe0fb6fe73c3fefa74466e6642a6d455b66e
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99%3Apg%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/ptushub/nohkiu/commit/0aeaef9a1bd40be005add302d911431964847165
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A%3Apg%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/danielfachka/zyfplc/commit/aaa5c0abb4e845a207397b0c6437c6fe1027bbc8
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93%3Apg%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/9b487e98e0d2dd262040dbbd43b0f1c4d275bcc0
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0-%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96.md
https://github.com/sourux23/eufvji/commit/cde720108f01b9dff7707582af8efbec29a69a1e
https://github.com/sourux23/eufvji/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3Apg%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3%E9%93%BE%E6%8E%A5-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/9971ccf32360c78392c2180d259cbeedc5d43346
https://github.com/e44nf/nkliyn/blob/main/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3Apg%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/3bb0ca4d9f6c692be7f4bb121a318272a4f53996
https://github.com/enognagu/lpvade/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3Apg%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E5%BF%85%E5%BA%94.md
https://github.com/ryukaura/kityhe/commit/0884e2f60abe924b3e41818c1998431a72738225
https://github.com/ryukaura/kityhe/blob/main/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99%3Apg%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md
https://github.com/mustakuritsar07/rkngzy/commit/7e6368e900db86c39da57ebff944b382d99b45f2
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Apg%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md
https://github.com/kulkaye/xiinuu/commit/194176f63c7565db0ab1802da7259bca66f2d924
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md
https://github.com/constiang-s/xzjjce/commit/ae9a51f4c79e6f0730af1b91a3d2a77a29c6d5cd
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF.md
https://github.com/ptushub/nohkiu/commit/9d1d12b97837b5cb480decafa013355a533c8fc0
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0.md
https://github.com/schowffer/nmghjj/commit/ba54c836147fdcc25ae7f24e15954e1b4aa8543a
https://github.com/schowffer/nmghjj/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/e44nf/nkliyn/commit/ff8a12fe78e92a562c6dd78ad45eba5ffaa4f352
https://github.com/e44nf/nkliyn/blob/main/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md
https://github.com/enognagu/lpvade/commit/8ab138ea81ecc02a8144ec05bd89eb2f68f1701f
https://github.com/enognagu/lpvade/blob/main/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/d5a3f9f36d8f5c4e66572f6b8e37df47a2d029db
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%20-%E4%BC%98%E6%8D%B7%E6%95%B0%E7%A0%81.md
https://github.com/sourux23/eufvji/commit/1fb093b707fad78bd816cf2f0fc1c8f01cb13de1
https://github.com/sourux23/eufvji/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90app%20-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/ryukaura/kityhe/commit/a8f2f9e5746053fefa9c48fead71d1f0bcee41c7
https://github.com/ryukaura/kityhe/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/mustakuritsar07/rkngzy/commit/7b38a88271493aabb398b438d853242b04b972b8
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/8119ddcf9ca4b67c8752be8b65c7c44a724aa8f6
https://github.com/kulkaye/xiinuu/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/constiang-s/xzjjce/commit/fab8c15b36d330d6db26fa03537a9b8be94af71d
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md
https://github.com/ptushub/nohkiu/commit/68e173dce6b06ac0b3da612467f4c02313a1f031
https://github.com/ptushub/nohkiu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md
https://github.com/e44nf/nkliyn/commit/69b73b791a13888d32122920c1edd753234bbbfa
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3Apg%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA.md
https://github.com/enognagu/lpvade/commit/7a5bf98c731417f1a94a43881d5b84ea78cb6607
https://github.com/enognagu/lpvade/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-360%E8%A7%86%E9%A2%91.md
https://github.com/schowffer/nmghjj/commit/48473008b35c4ea2aef2f8d9481162cb5c908974
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md
https://github.com/danielfachka/zyfplc/commit/6004556fd3523e3abbacbbdc6f494e9096ee39e5
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90app%20-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/kulkaye/xiinuu/commit/3dee9978b49260bd35ece32e5d2c5da326c35a45
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3Apg%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81.md
https://github.com/ryukaura/kityhe/commit/6f0b768819030687fa6f8bf2f7cd4e19537e0805
https://github.com/ryukaura/kityhe/blob/main/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C%3Apg%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB.md
https://github.com/mustakuritsar07/rkngzy/commit/7532f00ce97a086379311cc0b033185376c5cbbb
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3Apg%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/ec5313285b30af907923d1f41d48de5db690715e
https://github.com/ptushub/nohkiu/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3Apg%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/constiang-s/xzjjce/commit/bffacbebc3b1608671eeaee8c0c1679870d18904
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3Apg%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/e44nf/nkliyn/commit/c0b839f4abe7f15345c04e765cc3bede943dc96c
https://github.com/e44nf/nkliyn/blob/main/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89%3Apg%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-360%E8%A7%86%E9%A2%91.md
https://github.com/sourux23/eufvji/commit/b78ca2a37fc6ba7c39177f54de086485d664dd64
https://github.com/sourux23/eufvji/blob/main/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F%3Apg%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/9ea4a25eb221328aee54273c596dc7db645fe10c
https://github.com/enognagu/lpvade/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3Apg%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%BF%85%E5%BA%94.md
https://github.com/danielfachka/zyfplc/commit/729a2be19085e5e058ce86f4ae644f92557a434d
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/a6e0bc14a662cf83ec6ea49dc5f7156f32d94538
https://github.com/kulkaye/xiinuu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96.md
https://github.com/schowffer/nmghjj/commit/8106605e03a624aacab7d223e7d3e2636802b7c1
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%20-%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86.md
https://github.com/ptushub/nohkiu/commit/8ec0eb1e89bc83f044a07026cf2c4fc55b1ca2e9
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86.md
https://github.com/ryukaura/kityhe/commit/83604b2b4fd4c873e06b616e19eb1148301dedb9
https://github.com/ryukaura/kityhe/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/85bceb95bb4817f47a5702f69ac03610dfd61e4b
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81.md
https://github.com/constiang-s/xzjjce/commit/123c1618430938610e12fec934771d9b7b469340
https://github.com/constiang-s/xzjjce/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81.md
https://github.com/e44nf/nkliyn/commit/36b75ed2dbb3db0edca3ade26382009ffdfb51fd
https://github.com/e44nf/nkliyn/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/enognagu/lpvade/commit/abd978b77dfc804245e9d4ab377ecef11ac32ec2
https://github.com/enognagu/lpvade/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/ade108f364830fc65748c270c2731f421bbcbbca
https://github.com/sourux23/eufvji/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-36%E6%B0%AA%E6%B1%BD%E8%BD%A6.md
https://github.com/danielfachka/zyfplc/commit/c89e45a79a54db570ae3b7c3ee9aa2f261617eaf
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90.md
https://github.com/kulkaye/xiinuu/commit/1e05eb55f008640f5e384fcdd85fa227e60371eb
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C%3Apg%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%20-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/ptushub/nohkiu/commit/f1b0ddf7be68d5e599aa19ba8addc88f023f3241
https://github.com/ptushub/nohkiu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82.md
https://github.com/mustakuritsar07/rkngzy/commit/b7733d224e38e4f9b337f3cca5e2862121a2ba36
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/constiang-s/xzjjce/commit/d501328b6f6dbb677789e3aa9ad8d637f53b941e
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/0e829fdea7045d051baec54fa0b6997fb50cbc3d
https://github.com/ryukaura/kityhe/blob/main/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md
https://github.com/e44nf/nkliyn/commit/4a2ac44ed71cdace0326d5357f2d4c6b2ef7ce80
https://github.com/e44nf/nkliyn/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E8%8A%92%E6%9E%9C%E5%88%9B%E6%8A%95.md
https://github.com/schowffer/nmghjj/commit/6b2355dbcad367aa800003a042e8f31c9a78811c
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E5%90%9B%E4%B8%B4%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AA%E6%B3%A8%E5%86%8C%20-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/enognagu/lpvade/commit/009abb19fe6f2e1da0512294d8c3fe6c628c2eec
https://github.com/enognagu/lpvade/blob/main/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%20-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md
https://github.com/danielfachka/zyfplc/commit/0da9cb7b194491ec7e0682102eb816ac1b647aec
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md
https://github.com/kulkaye/xiinuu/commit/984a372a454e5a9a8daf8325c2a2cbebdbd2a81a
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md
https://github.com/sourux23/eufvji/commit/852ff4eb7dab52b865427a31742ff4ed558b8801
https://github.com/sourux23/eufvji/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E5%90%9B%E4%B8%B4%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%AF%BC%E8%88%AAapp%E6%B3%A8%E5%86%8C%20-%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86.md
https://github.com/ptushub/nohkiu/commit/b098df914ffa7ca3cd5bef76009634a417499431
https://github.com/ptushub/nohkiu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0-36%E6%B0%AA%E6%B1%BD%E8%BD%A6.md
https://github.com/constiang-s/xzjjce/commit/bf472acf02e373266f827c3b4506af1df397339d
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3Apg%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81.md
https://github.com/mustakuritsar07/rkngzy/commit/4442d1dcef4adc556279a9eeacf13f1c9ddd8dc0
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3Apg%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0-%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86.md
https://github.com/ryukaura/kityhe/commit/6b138bfced93b4eddf4c4545d00d1113c62f7c32
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3Apg%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md
https://github.com/e44nf/nkliyn/commit/f207917a6e0f0758419c30c5ec9c11f5c9125cf9
https://github.com/e44nf/nkliyn/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3Apg%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88.md
https://github.com/enognagu/lpvade/commit/6ca4af14d728f38ad4650b1da8404d21a82ef2a2
https://github.com/enognagu/lpvade/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3Apg%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/danielfachka/zyfplc/commit/3ad0a9babd7b3e6165f70f5e201977fbfb07a4e2
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3Apg%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/kulkaye/xiinuu/commit/47944332ecb5fab4b0ddd7b97478de3407af4d85
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3Apg%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/schowffer/nmghjj/commit/59b3f18e4a66315a967f03e6ecd5087f94bbed85
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA%3Apg%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A4%A7%E8%88%9E%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3%E9%93%BE%E6%8E%A5-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/e59f229411945396cee8559caefd11889e9bc7bc
https://github.com/sourux23/eufvji/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3-%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE.md
https://github.com/constiang-s/xzjjce/commit/1236559888f639e737e6619aa0dc1c91a7dedd8d
https://github.com/constiang-s/xzjjce/blob/main/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5%3A%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/04ed654225e53e14f59fd082a932e1676ccb45d3
https://github.com/e44nf/nkliyn/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/ac8671f6e57ee893b9423cb398160a88482ae902
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md
https://github.com/ryukaura/kityhe/commit/393c7b254b55ac30577f1d25517e89f2d9d498b3
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90%20-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md
https://github.com/ptushub/nohkiu/commit/b49e6d632cdc733a61c271712a9e2be6ed3c779f
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/6c80ed1854cc4c64ca5ba368acfb5e372330d326
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF.md
https://github.com/kulkaye/xiinuu/commit/15086d6df873cc976eec021d26a350a1f726aa9c
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/1efae0cccaff831408ef45163f3aac44e8f2c75c
https://github.com/enognagu/lpvade/blob/main/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90app%20-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/32889589df13e5e418209aa7be785d344e813f48
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/schowffer/nmghjj/commit/04c4d8b2413958ae4f90d6de80797be1d932f6e2
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8.md
https://github.com/e44nf/nkliyn/commit/6de9b2186a4424b3df7c62a05451b943d2272da7
https://github.com/e44nf/nkliyn/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md
https://github.com/mustakuritsar07/rkngzy/commit/960393f5527ceeb2462ad291556a1ee0c5d4d3b7
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3A%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/dc8fe9206c930d46d6a61864b4c4332e4acf6ebf
https://github.com/ryukaura/kityhe/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE.md
https://github.com/sourux23/eufvji/commit/325c6e0c23c6820e49e3a1fa2a722875c777424a
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md
https://github.com/danielfachka/zyfplc/commit/85ffacb23b5068bd5dc19157194f948f35ed6450
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC%3Apg%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md
https://github.com/ptushub/nohkiu/commit/7a2ba4bd7bda784fcef2d5bb66c52897ac814f10
https://github.com/ptushub/nohkiu/blob/main/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99%3Apg%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90%20-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/kulkaye/xiinuu/commit/b385f60423c648511b12edff40490b0864baeb00
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3Apg%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90app%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md
https://github.com/enognagu/lpvade/commit/24e4922d7d5289c1cea7215a1cc93c084aafe1de
https://github.com/enognagu/lpvade/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3Apg%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/9bacd61fd6784687c2768f0d7f008a36cc1a0d2f
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99%3Apg%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/e44nf/nkliyn/commit/350be85c70102e8aed3a0d83e73b77b4998d0408
https://github.com/e44nf/nkliyn/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3Apg%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%20-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md
https://github.com/mustakuritsar07/rkngzy/commit/c5059068395834f969c792b69359a7b1479cde73
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3Apg%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%20-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md
https://github.com/schowffer/nmghjj/commit/6a087e874649778bf4ef200292e710db30bdcb88
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Apg%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/danielfachka/zyfplc/commit/2dc301db3b02c96bdd6aee2854ad415e6fb044f4
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3Apg%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md
https://github.com/kulkaye/xiinuu/commit/2e9a348be988cd0a022b46aed26c205a97572a2f
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%20-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md
https://github.com/ryukaura/kityhe/commit/67bb50fc93249524c832c9c6f63650e2d16866e5
https://github.com/ryukaura/kityhe/blob/main/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C%3Apg%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%20-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md
https://github.com/ptushub/nohkiu/commit/aa034fe3e77addd5a68d8464112f3732ee42c4a0
https://github.com/ptushub/nohkiu/blob/main/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB%3A%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%20-%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95.md
https://github.com/enognagu/lpvade/commit/27a278c77de511a996ac3055fa40f115a83f63b8
https://github.com/enognagu/lpvade/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/b8b2ebf2b69e51f77543241aa68c5e9ea4bec819
https://github.com/sourux23/eufvji/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3Apg%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md
https://github.com/constiang-s/xzjjce/commit/8111cd00549946df4a860a4eb589e295fda458cd
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93%3A%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E4%BA%AC%E4%B8%9C%E9%80%9A%E6%8A%A5.md
https://github.com/e44nf/nkliyn/commit/0c8e6af424bc8d89c74041a1927973a2a686c35c
https://github.com/e44nf/nkliyn/blob/main/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5%3A%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%20-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md
https://github.com/mustakuritsar07/rkngzy/commit/d340d30ade61d9f4592462dd373bd9505a11b61b
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E6%97%BA%E8%B4%A2%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/kulkaye/xiinuu/commit/2300f20b66d8bf9844e1eb66b89a5db2eb66fedb
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%20-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/danielfachka/zyfplc/commit/459d8dbf90b4d43f0c6052b4162a4fbd1b4b08b0
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F%3A%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%20-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md
https://github.com/ptushub/nohkiu/commit/29f234effdf67c8a29d4f51849975c37d331be9c
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3A%E6%97%BA%E8%B4%A2%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91app%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5%E5%85%A5%E5%8F%A3%20-%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88.md
