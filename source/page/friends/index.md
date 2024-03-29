---
layout: friends     # 必须
seo_title: 友链   # 可选，这是友链页的标题
sidebar: []
meta:
  header: []
  footer: []
twikoo:
  placeholder: 这里是友链，虽然我一直不怎么处理友链的啊喂...
sitemap: false
---

{% p center logo gray large, 今夕复何夕，共此灯烛光。 %}

<!-- more -->

{% tabs tab-id %}

<!-- tab <i class="fad fa-galaxy"></i><i style="font-weight: normal;font-style: normal;">&nbsp;举个栗子</i> -->

{% codeblock lang:yml mark:1-3 友链格式，除高亮行，其余均可选~ line_number:false %}
- title: # 网站名称
  url: # 访问地址
  avatar: # 头像地址
  description: # 描述/一句话概述/格言
  screenshot: # 网站截图/展示图
  backgroundColor: # 头像背景颜色
  textColor: # 文本颜色
  keywords:
    - 标签一
    - 标签二
{% endcodeblock %}

<!-- endtab -->

<!-- tab <i class="fad fa-greater-than-equal"></i><i style="font-weight: normal;font-style: normal;">&nbsp;前置要求 </i> -->

{% checkbox green checked, Https 站点（大势所趋） %}
{% checkbox green checked, 网站加载速度正常（待定...） %}
{% checkbox minus blue checked, 免费类域名站点请略过（潜在的不可靠性） %}
{% checkbox minus blue checked, 新创站点请略过（建议拥有一定的原创内容） %}
{% checkbox times red checked, 不接受一切商业性或强烈侵入类广告之站点 %}
{% checkbox times red checked, 不接受违反中华人民共和国法律法规之站点 %}

<!-- endtab -->

<!-- tab <i class="fad fa-cannabis logoColor"></i><i style="font-weight: normal;font-style: normal;">&nbsp;本站信息 </i>  -->

<p>
<span class='not-select'>访问地址：</span><code>https://inkss.cn</code><br>
<span class='not-select'>站点名称：</span><code>枋柚梓的猫会发光</code><br>
<span class='not-select'>头像地址：</span><code>https://cdn.jsdelivr.net/gh/inkss/common@1/static/avatar.jpg</code><br>
<span class='not-select'>描述信息：</span><code>繁星永存，记忆更古不变。</code>
</p>

<!-- endtab -->

<!-- tab <i class="fad fa-bug logoColor"></i><i style="font-weight: normal;font-style: normal;">&nbsp;失效链接 </i>  -->

> 记录严重失效类型

| 名称         | 地址                      | 描述/标签                      | 备注              |
| ------------ | ------------------------- | ------------------------------ | ----------------- |
| BooLo        | https://www.boolo.top     | 记录成长，向未来奔跑           | 无 DNS 相应       |
| nomar        | https://www.nomar.cn      | 技术记录分享                   | 内容异常/描述不符 |
| 饿龙不是龙哩 | https://liuyifei.club     | INFP/菲迷/颜控/夜猫子/无头怪   | 域名注销          |
| Flexiston    | https://www.flexiston.com | 长风破浪会有时，直挂云帆济沧海 | 域名注销          |

以上内容的最后更新日期：2021年12月17日

<!-- endtab -->

{% endtabs %}
