百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
氖裂毡型蚁现园匝倏导妇怨哺献督

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

https://github.com/kulkaye/xiinuu/commit/9e39bd87aea3285e8d538342f76ca641a76cf832
https://github.com/kulkaye/xiinuu/blob/main/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/6dc4986c7bd2c91bba1d12991a5045d337bf849c
https://github.com/schowffer/nmghjj/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3%E7%90%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5.md
https://github.com/ptushub/nohkiu/commit/0cd3433630039d1c5e2514412391e269bcbebcc2
https://github.com/ptushub/nohkiu/blob/main/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md
https://github.com/danielfachka/zyfplc/commit/6510354ee5a2df39a0ba18321ae9c71c7e48e94d
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/kulkaye/xiinuu/commit/9c066451d5c318e4daebebc977ea2fff83883747
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/6abbd7ce25167ce0278436c9f904c341a14c7f16
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/012d77cff680407da2fbf695765f022e6933f752
https://github.com/ptushub/nohkiu/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96.md
https://github.com/kulkaye/xiinuu/commit/e2d921054bb1eb01de11fcdd98e3fd7f0d558459
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/danielfachka/zyfplc/commit/fb131cf17daa0c2a303573dae9ed6e20982bb128
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/schowffer/nmghjj/commit/d9c18dc6d3052c6db85e613fcae689f75f5d554f
https://github.com/schowffer/nmghjj/blob/main/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/kulkaye/xiinuu/commit/c3861711f0f3e4f19ac7070369f83f0d20ee4b57
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/5f650cc3335363643247eb8c0b9c273eefb073f6
https://github.com/ptushub/nohkiu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E7%99%BB%E9%99%86-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/34879e2c3055d9b9783d68a5c9d028b8b8b45cd7
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/0c6d53cbf597bc723438a3ae8b7e20bb82326cf9
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86%E4%B8%BB%E7%AE%A1-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md
https://github.com/kulkaye/xiinuu/commit/427a9633444ba1f561c48cc2b4972863ca79fa4b
https://github.com/kulkaye/xiinuu/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/schowffer/nmghjj/commit/86831dc50e22769eedc4a4fde1c7b7b71b14c4da
https://github.com/schowffer/nmghjj/blob/main/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0.md
https://github.com/danielfachka/zyfplc/commit/3b32483bc44f77faccd7eacd2cb10c613b36f7f2
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-360%E9%80%9A%E4%BF%A1.md
https://github.com/ptushub/nohkiu/commit/91f25c50ec1091cd7a3b2a9907c88b18805a4ca4
https://github.com/ptushub/nohkiu/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E6%8A%A5.md
https://github.com/kulkaye/xiinuu/commit/171ee24682652660d4761f9c6165730f61583c80
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/3cb1c179dbe53398d0586deba400c526a7336d38
https://github.com/schowffer/nmghjj/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/502cb2edecea57e8504d766571788b301a03112a
https://github.com/ptushub/nohkiu/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/danielfachka/zyfplc/commit/f528f433e44f8fa0a4079de6545363f57bb81bad
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md
https://github.com/kulkaye/xiinuu/commit/8606ea0b50c39b50639af39c3174bae1b4c0627b
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md
https://github.com/schowffer/nmghjj/commit/8051d57b8374d9152deb7e44bde44b5cb675d7bc
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/d6f552aaff9abd4e4574fce3c37526aecc241354
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/ptushub/nohkiu/commit/d7e6401fd1cd103b83d2985b4dbd515e80b8a9e8
https://github.com/ptushub/nohkiu/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4.md
https://github.com/danielfachka/zyfplc/commit/96c650f4d1c4b838758c9628f63f28138c6da4e8
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md
https://github.com/schowffer/nmghjj/commit/953a006293aa8a0b91e34a4e3b3e67b20f589148
https://github.com/schowffer/nmghjj/blob/main/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-360%E5%8E%86%E5%8F%B2.md
https://github.com/ptushub/nohkiu/commit/a64d27eabf97632e38183323b788de79c1814ff2
https://github.com/ptushub/nohkiu/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB.md
https://github.com/kulkaye/xiinuu/commit/ec8402c7d551fd697e627d50766871b1c27ee68b
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/danielfachka/zyfplc/commit/4bd8bc259812592db7166c3fe94fb92f26b4c228
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md
https://github.com/schowffer/nmghjj/commit/96450c28de936a665bf7bdffc9ff1c4ad910ac27
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8.md
https://github.com/kulkaye/xiinuu/commit/59ad87a19bebd01320378482980280e525f921eb
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA.md
https://github.com/ptushub/nohkiu/commit/4024f7a5760155a1ffa89137dd95cc87fec2adfc
https://github.com/ptushub/nohkiu/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E9%97%AE%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E8%99%8E%E5%97%85%E6%97%85%E6%B8%B8.md
https://github.com/danielfachka/zyfplc/commit/c279887bd3aba708c944657bbd5064aaf6b46fc7
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/schowffer/nmghjj/commit/407f2bfc806f02ceb426a4dd5a534e0af4d734ef
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C-%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/a0a295e2b46ac24603c9f3f19502dfe4fb74fa46
https://github.com/kulkaye/xiinuu/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/f5bceb4516c1907a4ec9f2831ab6cfa4f732018a
https://github.com/ptushub/nohkiu/blob/main/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%BC%80%E6%88%B7-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md
https://github.com/danielfachka/zyfplc/commit/a68a43dd8ea524ddefa759bfe3daad03503fefcf
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md
https://github.com/kulkaye/xiinuu/commit/2e286d4ce99aaf7aeaef2e35c81cd39f3568fdec
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md
https://github.com/schowffer/nmghjj/commit/b4a8ef6c1ae58bc1555d5691f120e21524d5ccfb
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88.md
https://github.com/ptushub/nohkiu/commit/0affa1b610c24f46e0d53931d674402aca8afa03
https://github.com/ptushub/nohkiu/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E4%B8%BB%E7%AE%A1-%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81.md
https://github.com/danielfachka/zyfplc/commit/b2f09f9df85508815c468056f175e00971e43b33
https://github.com/danielfachka/zyfplc/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/f4f39f4333072fc86f12af1ddb23cca14e43d82e
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md
https://github.com/schowffer/nmghjj/commit/bcf2ff156c90cc3365857dd2c201b0e70c4dd734
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md
https://github.com/ptushub/nohkiu/commit/fc8a2fd86a7dd3c71f32cc5e7553e86d2acc05f7
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/1d65be9a9d9675a8af7e8f4b0fe7dbc0e7044204
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7.md
https://github.com/kulkaye/xiinuu/commit/4e1bd9b3ba06c0cf0277793df1abb16e7105a426
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md
https://github.com/schowffer/nmghjj/commit/9152085d6f91fbc6e19a5349db3d161bff9dc4a9
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/ptushub/nohkiu/commit/60b8a38240f69f89502ba1ddb292460610291442
https://github.com/ptushub/nohkiu/blob/main/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/kulkaye/xiinuu/commit/2e9249dff4d5af98126a6aacc6762fe01fe194d0
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3%E7%90%86-%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/6aef61fce00641dfaeb76ca984b495f3e2a56056
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/ptushub/nohkiu/commit/70ddb005dd66f2bd15c7a18344eb34905816ad18
https://github.com/ptushub/nohkiu/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/danielfachka/zyfplc/commit/75e424b26ed1468b23877d4123ea699048daacde
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/c5e5c4ca3b8f1acfe4d176cf60494003c677ec59
https://github.com/kulkaye/xiinuu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-360%E9%80%9A%E4%BF%A1.md
https://github.com/schowffer/nmghjj/commit/2d1bf9a0ae4757ea134074183bfa6302f0498976
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E4%BC%98%E6%8D%B7%E6%95%B0%E7%A0%81.md
https://github.com/kulkaye/xiinuu/commit/05642200824cfbd607048424a9e47566a023593d
https://github.com/kulkaye/xiinuu/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E6%90%9C%E7%8B%90%E6%91%84%E5%BD%B1.md
https://github.com/ptushub/nohkiu/commit/028d6bec07f07b4e4931c41af2aa634126733cc7
https://github.com/ptushub/nohkiu/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md
https://github.com/danielfachka/zyfplc/commit/21a4a73f1716f471debb16009b345532fb73961c
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/schowffer/nmghjj/commit/b8b8de49b45f6a724724bc6590c04624069a5e90
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E7%99%BB%E9%99%86-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/f08494bbba34e4e521c575268018e85b2949efce
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1-%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81.md
https://github.com/danielfachka/zyfplc/commit/1b6a32bc7548df91a9c01904af466edb7184e89b
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/ptushub/nohkiu/commit/3294c00e7de590000037734db62ee35351c35877
https://github.com/ptushub/nohkiu/blob/main/2026%E9%A6%96%E8%A6%81%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86%E4%B8%BB%E7%AE%A1-%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86.md
https://github.com/schowffer/nmghjj/commit/b112f2a35dd768b0086bf88beb152d04f75621e2
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/danielfachka/zyfplc/commit/41e14f9af92e17939a3c9873a829e677c2c8181b
https://github.com/danielfachka/zyfplc/blob/main/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/d759886b876fcd4e460e6b8678362b4ac946899f
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8.md
https://github.com/schowffer/nmghjj/commit/f97200502c5960e75e829eb4ac2e5ab53a20888b
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1-%E5%BF%85%E5%BA%94.md
https://github.com/ptushub/nohkiu/commit/18064409b7915924d9629db32226d27f107e3156
https://github.com/ptushub/nohkiu/blob/main/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96.md
https://github.com/danielfachka/zyfplc/commit/e98d1e20850369aa3526b7e4d45401b4c6e574e2
https://github.com/danielfachka/zyfplc/blob/main/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7.md
https://github.com/kulkaye/xiinuu/commit/32f17c644816e701d785bc40f49835b2a8a0e801
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9.md
https://github.com/ptushub/nohkiu/commit/7b79dabbf13636942ddf2ce4140f3e05e5ae66c0
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md
https://github.com/schowffer/nmghjj/commit/27c09aef6a8d3bc6d229c4349e46181b8f309b10
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-36%E6%B0%AA%E6%B1%BD%E8%BD%A6.md
https://github.com/danielfachka/zyfplc/commit/eab6486b8a042bbfe790d3840ce820f75ff6ff0b
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86%E6%94%BF%E7%AD%96-360%E9%80%9A%E4%BF%A1.md
https://github.com/kulkaye/xiinuu/commit/7e868540a72ca3c5f28e0b6397a4e9986c1766fa
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/ptushub/nohkiu/commit/b2db7728bd750b0443b0f4e07f0696e096cbd6a2
https://github.com/ptushub/nohkiu/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88.md
https://github.com/schowffer/nmghjj/commit/395ab490e11667364e613a71f829655fbbaccc81
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/ce978393de840c9cbec30d56907a4fbacb4b7f52
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%BB%E4%BB%A3-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md
https://github.com/kulkaye/xiinuu/commit/189a4ce0519737af7baf2df248fd0dd5378823bd
https://github.com/kulkaye/xiinuu/blob/main/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/ptushub/nohkiu/commit/235174f56b41bcd7a41d31046d8fb37789c37663
https://github.com/ptushub/nohkiu/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md
https://github.com/danielfachka/zyfplc/commit/7bfdfd01ecc29aa613e1114c5fa5e5f888231000
https://github.com/danielfachka/zyfplc/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md
https://github.com/schowffer/nmghjj/commit/1eaa92c3717ada117b03207c363f0a58951f0d88
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81.md
https://github.com/kulkaye/xiinuu/commit/74c8d7cb9d9697d5d9f32354227fdd8b940c9d2f
https://github.com/kulkaye/xiinuu/blob/main/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3A%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85%E5%BE%85%E9%81%87-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/78486376452b62f6f8f0a557515058bb8e4c9eb6
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C-360%E9%80%9A%E4%BF%A1.md
https://github.com/ptushub/nohkiu/commit/e766775fc0e67c3ef1bb96b36eaa8e6c70a3f916
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md
https://github.com/schowffer/nmghjj/commit/4f403c64be38b1982912c62c81f7d536c86fceeb
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%93%BE%E6%8E%A5-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md
https://github.com/kulkaye/xiinuu/commit/dd7f6ee014d37d6e66b03d2e8c4e3f8837115f64
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md
https://github.com/danielfachka/zyfplc/commit/9c3852dc6b0c3d2ff5ea10ce93bd4a51044de6ae
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95-%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9.md
https://github.com/schowffer/nmghjj/commit/82a823d6a8e0bc74be023bb7976d5c1174ca010c
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/ptushub/nohkiu/commit/920030f578932e1c09951bc9b4f28985c90c30c6
https://github.com/ptushub/nohkiu/blob/main/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%BC%80%E6%88%B7-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95.md
https://github.com/danielfachka/zyfplc/commit/645ac2ecde511b7d9640eb6fb1b6fa5b95d318a3
https://github.com/danielfachka/zyfplc/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md
https://github.com/kulkaye/xiinuu/commit/b72e0e87f70091c2ddc087dddd6db3b266575a19
https://github.com/kulkaye/xiinuu/blob/main/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86.md
https://github.com/schowffer/nmghjj/commit/60235949505e196b4b53280eafde32d9be761018
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E4%B8%BB%E7%AE%A1-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/636068abfe8ae92d3589d95cf644bbd49a174fe2
https://github.com/ptushub/nohkiu/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/8b2dada69de2bd2368939f274d61691ec8584af9
https://github.com/danielfachka/zyfplc/blob/main/2026%E9%A6%96%E8%A6%81%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/schowffer/nmghjj/commit/6b5edce93cea6cea5afec6650374563fd9274a02
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1-%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81.md
https://github.com/ptushub/nohkiu/commit/6732312fc3713a4b5cf99b31f011dcde65459fc8
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/kulkaye/xiinuu/commit/c23b5f179a574dafdd9bac8518936439aed23469
https://github.com/kulkaye/xiinuu/blob/main/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/da5e08aa5f36058d29b747fed11258e8e760c263
https://github.com/danielfachka/zyfplc/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95.md
https://github.com/schowffer/nmghjj/commit/2f5f46052b4b6e058695b1b507d467996c83411b
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7.md
https://github.com/kulkaye/xiinuu/commit/f9a50651dede206975957526fcb631edf1f38f1b
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md
