## 前端问题的总结 (本仓库=>知识点定义的文字描述,不涉及编程)
## 编程篇总结会更新到另外一个仓库 [编程](https://github.com/Xieguoiang/Full-Stack-Programming)

- [FE-interview](#fe-interview)
  - [HTML， HTTP，web综合问题](#$html，-http，web综合问题)
    - [常见排序算法的时间复杂度,空间复杂度](#常见排序算法的时间复杂度空间复杂度)
    - [什么是Http协议无状态协议怎么解决Http协议无状态协议](#什么是Http协议无状态协议怎么解决Http协议无状态协议)
    - [前端需要注意哪些SEO](#前端需要注意哪些seo)
    - [web开发中会话跟踪的方法有哪些](#web开发中会话跟踪的方法有哪些)
    - [doctype是什么,举例常见doctype及特点](#doctype是什么举例常见doctype及特点)
    - [HTML全局属性(global attribute)有哪些](#html全局属性global-attribute有哪些)
    - [什么是web语义化,有什么好处](#什么是web语义化有什么好处)
    - [HTTP method](#http-method)
    - [从浏览器地址栏输入url到显示页面的步骤(以HTTP为例)](#从浏览器地址栏输入url到显示页面的步骤以http为例)
    - [HTTP request报文结构是怎样的](#http-request报文结构是怎样的)
    - [HTTP response报文结构是怎样的](#http-response报文结构是怎样的)
    - [如何进行网站性能优化](#如何进行网站性能优化)
    - [什么是渐进增强](#什么是渐进增强)
    - [HTTP状态码及其含义](#http状态码及其含义)
    - [HTTPS工作原理](#HTTPS工作原理)
  - [$CSS部分](#$css部分)
    - [CSS选择器有哪些](#css选择器有哪些)
    - [css sprite是什么,有什么优缺点](#css-sprite是什么有什么优缺点)
    - [`display: none;`与`visibility: hidden;`的区别](#display-none与visibility-hidden的区别)
    - [css hack原理及常用hack](#css-hack原理及常用hack)
    - [specified value,computed value,used value计算方法](#specified-valuecomputed-valueused-value计算方法)
    - [`link`与`@import`的区别](#link与@import的区别)
    - [``display: block;``和``display: inline;``的区别](#display-block和display-inline的区别)
    - [PNG,GIF,JPG的区别及如何选](#pnggifjpg的区别及如何选)
    - [CSS有哪些继承属性](#css有哪些继承属性)
    - [IE6浏览器有哪些常见的bug,缺陷或者与标准不一致的地方,如何解决](#ie6浏览器有哪些常见的bug缺陷或者与标准不一致的地方如何解决)
    - [容器包含若干浮动元素时如何清理(包含)浮动](#容器包含若干浮动元素时如何清理包含浮动)
    - [什么是FOUC?如何避免](#什么是fouc如何避免)
    - [如何创建块级格式化上下文(block formatting context),BFC有什么用](#如何创建块级格式化上下文block-formatting-contextbfc有什么用)
    - [display,float,position的关系](#displayfloatposition的关系)
    - [外边距折叠(collapsing margins)](#外边距折叠collapsing-margins)
    - [如何确定一个元素的包含块(containing block)](#如何确定一个元素的包含块containing-block)
    - [stacking context,布局规则](#stacking-context布局规则)
    - [如何水平居中一个元素](#如何水平居中一个元素)
    - [如何竖直居中一个元素](#如何竖直居中一个元素)
  - [$javascript概念部分](#$javascript概念部分)
    - [DOM元素e的e.getAttribute(propName)和e.propName有什么区别和联系](#dom元素e的egetattributepropname和epropname有什么区别和联系)
    - [offsetWidth/offsetHeight,clientWidth/clientHeight与scrollWidth/scrollHeight的区别](#offsetwidthoffsetheightclientwidthclientheight与scrollwidthscrollheight的区别)
    - [XMLHttpRequest通用属性和方法](#xmlhttprequest通用属性和方法)
    - [focus/blur与focusin/focusout的区别与联系](#focusblur与focusinfocusout的区别与联系)
    - [mouseover/mouseout与mouseenter/mouseleave的区别与联系](#mouseovermouseout与mouseentermouseleave的区别与联系)
    - [sessionStorage,localStorage,cookie区别](#sessionstoragelocalstoragecookie区别)
    - [javascript跨域通信](#javascript跨域通信)
    - [javascript有哪几种数据类型](#javascript有哪几种数据类型)
    - [什么闭包,闭包有什么用](#什么闭包闭包有什么用)
    - [javascript有哪几种方法定义函数](#javascript有哪几种方法定义函数)
    - [应用程序存储和离线web应用](#应用程序存储和离线web应用)
    - [客户端存储localStorage和sessionStorage](#客户端存储localstorage和sessionstorage)
    - [cookie及其操作](#cookie及其操作)
    - [javascript有哪些方法定义对象](#javascript有哪些方法定义对象)
    - [===运算符判断相等的流程是怎样的](#===运算符判断相等的流程是怎样的)
    - [==运算符判断相等的流程是怎样的](#==运算符判断相等的流程是怎样的)
    - [对象到字符串的转换步骤](#对象到字符串的转换步骤)
    - [对象到数字的转换步骤](#对象到数字的转换步骤)
    - [<,>,<=,>=的比较规则](#==的比较规则)
    - [+运算符工作流程](#运算符工作流程)
    - [函数内部arguments变量有哪些特性,有哪些属性,如何将它转换为数组](#函数内部arguments变量有哪些特性有哪些属性如何将它转换为数组)
    - [DOM事件模型是如何的,编写一个EventUtil工具类实现事件管理兼容](#dom事件模型是如何的编写一个eventutil工具类实现事件管理兼容)
    - [评价一下三种方法实现继承的优缺点,并改进](#评价一下三种方法实现继承的优缺点并改进)
  

<!-- END doctoc generated TOC please keep comment here to allow auto update -->
# FE-interview

个人收集的前端知识点、面试题和答案，参考答案仅代表个人观点，方便复习，目录如下:

## HTML， HTTP，web综合问题

### 常见排序算法的时间复杂度,空间复杂度

![排序算法比较](img/sort-compare.png)

### 什么是Http协议无状态协议怎么解决Http协议无状态协议

1. 无状态协议对于事务处理没有记忆能力。缺少状态意味着如果后续处理需要前面的信息,也就是说:当客户端一次HTTP请求完成以后, 客户端再发送一次HTTP请求, HTTP并不知道当前客户端是一个"老用户"。
2. 可以使用Cookie来解决无状态的问题，Cookie就相当于一个通行证，第一次访问的时候给客户端发送一个Cookie，当客户端再次来的时候，拿着Cookie通行证),那么服务器就知道这个是"老用户"


### 前端需要注意哪些SEO

1. 合理的title、description、keywords：搜索对着三项的权重逐个减小，title值强调重点即可，重要关键词出现不要超过2次，而且要靠前，不同页面title要有所不同；description把页面内容高度概括，长度合适，不可过分堆砌关键词，不同页面description有所不同；keywords列举出重要关键词即可
2. 语义化的HTML代码，符合W3C规范：语义化代码让搜索引擎容易理解网页
3. 重要内容HTML代码放在最前：搜索引擎抓取HTML顺序是从上到下，有的搜索引擎对抓取长度有限制，保证重要内容一定会被抓取
4. 重要内容不要用js输出：爬虫不会执行js获取内容
5. 少用iframe：搜索引擎不会抓取iframe中的内容
6. 非装饰性图片必须加alt
7. 提高网站速度：网站速度是搜索引擎排序的一个重要指标

### web开发中会话跟踪的方法有哪些

1. cookie
2. session
3. url重写
4. 隐藏input
5. ip地址

### doctype是什么,举例常见doctype及特点

1. `<!doctype>`声明必须处于HTML文档的头部，在`<html>`标签之前，HTML5中不区分大小写
2. `<!doctype>`声明不是一个HTML标签，是一个用于告诉浏览器当前HTMl版本的指令
3. 现代浏览器的html布局引擎通过检查doctype决定使用兼容模式还是标准模式对文档进行渲染，一些浏览器有一个接近标准模型。
3. 在HTML4.01中`<!doctype>`声明指向一个DTD，由于HTML4.01基于SGML，所以DTD指定了标记规则以保证浏览器正确渲染内容
4. HTML5不基于SGML，所以不用指定DTD

常见dotype：

1. **HTML4.01 strict**：不允许使用表现性、废弃元素（如font）以及frameset。声明：`<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">`
2. **HTML4.01 Transitional**:允许使用表现性、废弃元素（如font），不允许使用frameset。声明：`<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">`
3. **HTML4.01 Frameset**:允许表现性元素，废气元素以及frameset。声明：`<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">`
4. **XHTML1.0 Strict**:不使用允许表现性、废弃元素以及frameset。文档必须是结构良好的XML文档。声明：``<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">``
5. **XHTML1.0 Transitional**:允许使用表现性、废弃元素，不允许frameset，文档必须是结构良好的XMl文档。声明： ``<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">``
6. **XHTML 1.0 Frameset**:允许使用表现性、废弃元素以及frameset，文档必须是结构良好的XML文档。声明：``<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-frameset.dtd">``
7. **HTML 5**: `<!doctype html>`

### HTML全局属性(global attribute)有哪些

参考资料：[MDN: html global attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)或者[W3C HTML global-attributes](http://www.w3.org/TR/html-markup/global-attributes.html#common.attrs.core)

- `accesskey`:设置快捷键，提供快速访问元素如<a href="#" accesskey="a">aaa</a>在windows下的firefox中按``alt + shift + a``可激活元素
- `class`:为元素设置类标识，多个类名用空格分开，CSS和javascript可通过class属性获取元素
- `contenteditable`: 指定元素内容是否可编辑
- `contextmenu`: 自定义鼠标右键弹出菜单内容
- `data-*`: 为元素增加自定义属性
- `dir`: 设置元素文本方向
- `draggable`: 设置元素是否可拖拽
- `dropzone`: 设置元素拖放类型： copy, move, link
- `hidden`: 表示一个元素是否与文档。样式上会导致元素不显示，但是不能用这个属性实现样式效果
- `id`: 元素id，文档内唯一
- `lang`: 元素内容的的语言
- `spellcheck`: 是否启动拼写和语法检查
- `style`: 行内css样式
- `tabindex`: 设置元素可以获得焦点，通过tab可以导航
- `title`: 元素相关的建议信息
- `translate`: 元素和子孙节点内容是否需要本地化

### 什么是web语义化,有什么好处

web语义化是指通过HTML标记表示页面包含的信息，包含了HTML标签的语义化和css命名的语义化。
HTML标签的语义化是指：通过使用包含语义的标签（如h1-h6）恰当地表示文档结构
css命名的语义化是指：为html标签添加有意义的class，id补充未表达的语义，如[Microformat](http://en.wikipedia.org/wiki/Microformats)通过添加符合规则的class描述信息
为什么需要语义化：

- 去掉样式后页面呈现清晰的结构
- 盲人使用读屏器更好地阅读
- 搜索引擎更好地理解页面，有利于收录
- 便团队项目的可持续运作及维护

### HTTP method

1. 一台服务器要与HTTP1.1兼容，只要为资源实现**GET**和**HEAD**方法即可
2. **GET**是最常用的方法，通常用于**请求服务器发送某个资源**。
3. **HEAD**与GET类似，但**服务器在响应中值返回首部，不返回实体的主体部分**
4. **PUT**让服务器**用请求的主体部分来创建一个由所请求的URL命名的新文档，或者，如果那个URL已经存在的话，就用干这个主体替代它**
5. **POST**起初是用来向服务器输入数据的。实际上，通常会用它来支持HTML的表单。表单中填好的数据通常会被送给服务器，然后由服务器将其发送到要去的地方。
6. **TRACE**会在目的服务器端发起一个环回诊断，最后一站的服务器会弹回一个TRACE响应并在响应主体中携带它收到的原始请求报文。TRACE方法主要用于诊断，用于验证请求是否如愿穿过了请求/响应链。
7. **OPTIONS**方法请求web服务器告知其支持的各种功能。可以查询服务器支持哪些方法或者对某些特殊资源支持哪些方法。
8. **DELETE**请求服务器删除请求URL指定的资源

### 从浏览器地址栏输入url到显示页面的步骤(以HTTP为例)

1. 在浏览器地址栏输入URL
2. 浏览器查看**缓存**，如果请求资源在缓存中并且新鲜，跳转到转码步骤
    1. 如果资源未缓存，发起新请求
    2. 如果已缓存，检验是否足够新鲜，足够新鲜直接提供给客户端，否则与服务器进行验证。
    3. 检验新鲜通常有两个HTTP头进行控制`Expires`和`Cache-Control`：
        - HTTP1.0提供Expires，值为一个绝对时间表示缓存新鲜日期
        - HTTP1.1增加了Cache-Control: max-age=,值为以秒为单位的最大新鲜时间
3. 浏览器**解析URL**获取协议，主机，端口，path
4. 浏览器**组装一个HTTP（GET）请求报文**
5. 浏览器**获取主机ip地址**，过程如下：
    1. 浏览器缓存
    2. 本机缓存
    3. hosts文件
    4. 路由器缓存
    5. ISP DNS缓存
    6. DNS递归查询（可能存在负载均衡导致每次IP不一样）
6. **打开一个socket与目标IP地址，端口建立TCP链接**，三次握手如下：
    1. 客户端发送一个TCP的**SYN=1，Seq=X**的包到服务器端口
    2. 服务器发回**SYN=1， ACK=X+1， Seq=Y**的响应包
    3. 客户端发送**ACK=Y+1， Seq=Z**
7. TCP链接建立后**发送HTTP请求**
8. 服务器接受请求并解析，将请求转发到服务程序，如虚拟主机使用HTTP Host头部判断请求的服务程序
9. 服务器检查**HTTP请求头是否包含缓存验证信息**如果验证缓存新鲜，返回**304**等对应状态码
10. 处理程序读取完整请求并准备HTTP响应，可能需要查询数据库等操作
11. 服务器将**响应报文通过TCP连接发送回浏览器**
12. 浏览器接收HTTP响应，然后根据情况选择**关闭TCP连接或者保留重用，关闭TCP连接的四次握手如下**：
    1. 主动方发送**Fin=1， Ack=Z， Seq= X**报文
    2. 被动方发送**ACK=X+1， Seq=Z**报文
    3. 被动方发送**Fin=1， ACK=X， Seq=Y**报文
    4. 主动方发送**ACK=Y， Seq=X**报文
13. 浏览器检查响应状态吗：是否为1XX，3XX， 4XX， 5XX，这些情况处理与2XX不同
14. 如果资源可缓存，**进行缓存**
15. 对响应进行**解码**（例如gzip压缩）
16. 根据资源类型决定如何处理（假设资源为HTML文档）
17. **解析HTML文档，构件DOM树，下载资源，构造CSSOM树，执行js脚本**，这些操作没有严格的先后顺序，以下分别解释
18. **构建DOM树**：
    1. **Tokenizing**：根据HTML规范将字符流解析为标记
    2. **Lexing**：词法分析将标记转换为对象并定义属性和规则
    3. **DOM construction**：根据HTML标记关系将对象组成DOM树
19. 解析过程中遇到图片、样式表、js文件，**启动下载**
20. 构建**CSSOM树**：
    1. **Tokenizing**：字符流转换为标记流
    2. **Node**：根据标记创建节点
    3. **CSSOM**：节点创建CSSOM树
21. **[根据DOM树和CSSOM树构建渲染树](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-tree-construction)**:
    1. 从DOM树的根节点遍历所有**可见节点**，不可见节点包括：1）`script`,`meta`这样本身不可见的标签。2)被css隐藏的节点，如`display: none`
    2. 对每一个可见节点，找到恰当的CSSOM规则并应用
    3. 发布可视节点的内容和计算样式
22. **js解析如下**：
    1. 浏览器创建Document对象并解析HTML，将解析到的元素和文本节点添加到文档中，此时**document.readystate为loading**
    2. HTML解析器遇到**没有async和defer的script时**，将他们添加到文档中，然后执行行内或外部脚本。这些脚本会同步执行，并且在脚本下载和执行时解析器会暂停。这样就可以用document.write()把文本插入到输入流中。**同步脚本经常简单定义函数和注册事件处理程序，他们可以遍历和操作script和他们之前的文档内容**
    3. 当解析器遇到设置了**async**属性的script时，开始下载脚本并继续解析文档。脚本会在它**下载完成后尽快执行**，但是**解析器不会停下来等它下载**。异步脚本**禁止使用document.write()**，它们可以访问自己script和之前的文档元素
    4. 当文档完成解析，document.readState变成interactive
    5. 所有**defer**脚本会**按照在文档出现的顺序执行**，延迟脚本**能访问完整文档树**，禁止使用document.write()
    6. 浏览器**在Document对象上触发DOMContentLoaded事件**
    7. 此时文档完全解析完成，浏览器可能还在等待如图片等内容加载，等这些**内容完成载入并且所有异步脚本完成载入和执行**，document.readState变为complete,window触发load事件
23. **显示页面**（HTML解析过程中会逐步显示页面）

### HTTP request报文结构是怎样的
[rfc2616](http://www.w3.org/Protocols/rfc2616/rfc2616-sec5.html)中进行了定义：

1. 首行是**Request-Line**包括：**请求方法**，**请求URI**，**协议版本**，**CRLF**
2. 首行之后是若干行**请求头**，包括**general-header**，**request-header**或者**entity-header**，每个一行以CRLF结束
3. 请求头和消息实体之间有一个**CRLF分隔**
4. 根据实际请求需要可能包含一个**消息实体**
一个请求报文例子如下：

```
GET /Protocols/rfc2616/rfc2616-sec5.html HTTP/1.1
Host: www.w3.org
Connection: keep-alive
Cache-Control: max-age=0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8
User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.1916.153 Safari/537.36
Referer: https://www.google.com.hk/
Accept-Encoding: gzip,deflate,sdch
Accept-Language: zh-CN,zh;q=0.8,en;q=0.6
Cookie: authorstyle=yes
If-None-Match: "2cc8-3e3073913b100"
If-Modified-Since: Wed, 01 Sep 2004 13:24:52 GMT

name=qiu&age=25
```

### HTTP response报文结构是怎样的

[rfc2616](http://www.w3.org/Protocols/rfc2616/rfc2616-sec6.html)中进行了定义：

1. 首行是状态行包括：**HTTP版本，状态码，状态描述**，后面跟一个CRLF
2. 首行之后是**若干行响应头**，包括：**通用头部，响应头部，实体头部**
3. 响应头部和响应实体之间用**一个CRLF空行**分隔
4. 最后是一个可能的**消息实体**
响应报文例子如下：

```
HTTP/1.1 200 OK
Date: Tue, 08 Jul 2014 05:28:43 GMT
Server: Apache/2
Last-Modified: Wed, 01 Sep 2004 13:24:52 GMT
ETag: "40d7-3e3073913b100"
Accept-Ranges: bytes
Content-Length: 16599
Cache-Control: max-age=21600
Expires: Tue, 08 Jul 2014 11:28:43 GMT
P3P: policyref="http://www.w3.org/2001/05/P3P/p3p.xml"
Content-Type: text/html; charset=iso-8859-1

{"name": "qiu", "age": 25}
```

### 如何进行网站性能优化

[雅虎Best Practices for Speeding Up Your Web Site](https://developer.yahoo.com/performance/rules.html)：

- content方面
    1. 减少HTTP请求：合并文件、CSS精灵、inline Image
    2. 减少DNS查询：DNS查询完成之前浏览器不能从这个主机下载任何任何文件。方法：DNS缓存、将资源分布到恰当数量的主机名，平衡并行下载和DNS查询
    3. 避免重定向：多余的中间访问
    4. 使Ajax可缓存
    5. 非必须组件延迟加载
    6. 未来所需组件预加载
    7. 减少DOM元素数量
    8. 将资源放到不同的域下：浏览器同时从一个域下载资源的数目有限，增加域可以提高并行下载量
    9. 减少iframe数量
    10. 不要404

- Server方面
    1. 使用CDN
    2. 添加Expires或者Cache-Control响应头
    3. 对组件使用Gzip压缩
    4. 配置ETag
    5. Flush Buffer Early
    6. Ajax使用GET进行请求
    7. 避免空src的img标签
- Cookie方面
    1. 减小cookie大小
    2. 引入资源的域名不要包含cookie
- css方面
    1. 将样式表放到页面顶部
    2. 不使用CSS表达式
    3. 使用<link>不使用@import
    4. 不使用IE的Filter
- Javascript方面
    1. 将脚本放到页面底部
    2. 将javascript和css从外部引入
    3. 压缩javascript和css
    4. 删除不需要的脚本
    5. 减少DOM访问
    6. 合理设计事件监听器
- 图片方面
    1. 优化图片：根据实际颜色需要选择色深、压缩
    2. 优化css精灵
    3. 不要在HTML中拉伸图片
    4. 保证favicon.ico小并且可缓存
- 移动方面
    1. 保证组件小于25k
    2. Pack Components into a Multipart Document


### 什么是渐进增强

渐进增强是指在web设计时强调可访问性、语义化HTML标签、外部样式表和脚本。保证所有人都能访问页面的基本内容和功能同时为高级浏览器和高带宽用户提供更好的用户体验。核心原则如下:

- 所有浏览器都必须能访问基本内容
- 所有浏览器都必须能使用基本功能
- 所有内容都包含在语义化标签中
- 通过外部CSS提供增强的布局
- 通过非侵入式、外部javascript提供增强功能
- end-user web browser preferences are respected

### HTTP状态码及其含义

参考[RFC 2616](http://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html)

- 1XX：信息状态码
    - **100 Continue**：客户端应当继续发送请求。这个临时相应是用来通知客户端它的部分请求已经被服务器接收，且仍未被拒绝。客户端应当继续发送请求的剩余部分，或者如果请求已经完成，忽略这个响应。服务器必须在请求万仇向客户端发送一个最终响应
    - **101 Switching Protocols**：服务器已经理解力客户端的请求，并将通过Upgrade消息头通知客户端采用不同的协议来完成这个请求。在发送完这个响应最后的空行后，服务器将会切换到Upgrade消息头中定义的那些协议。
- 2XX：成功状态码
    - **200 OK**：请求成功，请求所希望的响应头或数据体将随此响应返回
    - **201 Created**：已创建
    - **202 Accepted**：已接受
    - **203 Non-Authoritative Information**：非授权信息 
    - **204 No Content**： 无内容
    - **205 Reset Content**：重置内容
    - **206 Partial Content**：部分内容
- 3XX：重定向
    - **300 Multiple Choices**：
    - **301 Moved Permanently**：已被永远移走
    - **302 Found**：对象已移动
    - **303 See Other**：
    - **304 Not Modified**：未发现修改
    - **305 Use Proxy**：
    - **306 （unused）**：
    - **307 Temporary Redirect**：临时重定向
- 4XX：客户端错误
    - **400 Bad Request**:  错误的请求。由于语法格式不正确，服务器无法理解该请求.
    - **401 Unauthorized**:  访问被拒绝
    - **402 Payment Required**:
    - **403 Forbidden**: 禁止访问
    - **404 Not Found**: 未找到路径
    - **405 Method Not Allowed**: 不允许的方法
    - **406 Not Acceptable**: 客户端浏览器不接受所请求页面的 MIME 类型
    - **407 Proxy Authentication Required**:
    - **408 Request Timeout**: 请求超时
    - **409 Conflict**:
    - **410 Gone**:
    - **411 Length Required**:
    - **412 Precondition Failed**: 前提条件失败
    - **413 Request Entity Too Large**:
    - **414 Request-URI Too Long**:
    - **415 Unsupported Media Type**:
    - **416 Requested Range Not Satisfiable**:
    - **417 Expectation Failed**:
- 5XX: 服务器错误
    - **500 Internal Server Error**:  服务器内部错误(服务端代码出现错误)
    - **501 Not Implemented**: 数据值指定了未实现的配置
    - **502 Bad Gateway**:  Web 服务器用作网关或代理服务器时收到了无效响应
    - **503 Service Unavailable**: 服务不可用
    - **504 Gateway Timeout**:  web 服务器网关超时
    - **505 HTTP Version Not Supported**: HTTP版本不支持

### HTTPS工作原理

1. 首先HTTP请求服务端生成证书,客户端对证书的有效期、合法性、域名是否与请求的域名一致、证书的公钥（RSA加密）等进行校验;
2. 客户端如果校验通过后，就根据证书的公钥的有效， 生成随机数，随机数使用公钥进行加密（RSA加密;
3. 消息体产生的后，对它的摘要进行MD5（或者SHA1）算法加密，此时就得到了RSA签名;
4. 发送给服务端，此时只有服务端（RSA私钥）能解密;
5. 解密得到的随机数,再用AES加密,作为密钥（此时的密钥只有客户端和服务端知道）。
![HTTPS工作原理](img/https-msg.png)

## $CSS部分

### CSS选择器有哪些

1. ***通用选择器**：选择所有元素，**不参与计算优先级**，兼容性IE6+
2. **#X id选择器**：选择id值为X的元素，兼容性：IE6+
3. **.X 类选择器**： 选择class包含X的元素，兼容性：IE6+
4. **X Y后代选择器**： 选择满足X选择器的后代节点中满足Y选择器的元素，兼容性：IE6+
5. **X 元素选择器**： 选择标所有签为X的元素，兼容性：IE6+
6. **:link，：visited，：focus，：hover，：active链接状态**： 选择特定状态的链接元素，顺序LoVe HAte，兼容性: IE4+
7. **X + Y直接兄弟选择器**：在**X之后第一个兄弟节点**中选择满足Y选择器的元素，兼容性： IE7+
8. **X > Y子选择器**： 选择X的子元素中满足Y选择器的元素，兼容性： IE7+
9. **X ~ Y兄弟**： 选择**X之后所有兄弟节点**中满足Y选择器的元素，兼容性： IE7+
10. **[attr]**：选择所有设置了attr属性的元素，兼容性IE7+
11. **[attr=value]**：选择属性值刚好为value的元素
12. **[attr~=value]**：选择属性值为空白符分隔，其中一个的值刚好是value的元素
13. **[attr|=value]**：选择属性值刚好为value或者value-开头的元素
14. **[attr^=value]**：选择属性值以value开头的元素
15. **[attr$=value]**：选择属性值以value结尾的元素
16. **[attr*=value]**：选择属性值中包含value的元素
17. **[:checked]**：选择单选框，复选框，下拉框中选中状态下的元素，兼容性：IE9+
18. **X:after, X::after**：after伪元素，选择元素虚拟子元素（元素的最后一个子元素），CSS3中::表示伪元素。兼容性:after为IE8+，::after为IE9+
18. **:hover**：鼠标移入状态的元素，兼容性a标签IE4+， 所有元素IE7+
19. **:not(selector)**：选择不符合selector的元素。**不参与计算优先级**，兼容性：IE9+
20. **::first-letter**：伪元素，选择块元素第一行的第一个字母，兼容性IE5.5+
21. **::first-line**：伪元素，选择块元素的第一行，兼容性IE5.5+
22. **:nth-child(an + b)**：伪类，选择前面有an + b - 1个兄弟节点的元素，其中n
&gt;= 0， 兼容性IE9+
23. **:nth-last-child(an + b)**：伪类，选择后面有an + b - 1个兄弟节点的元素
其中n &gt;= 0，兼容性IE9+
24. **X:nth-of-type(an+b)**：伪类，X为选择器，**解析得到元素标签**，选择**前面**有an + b - 1个**相同标签**兄弟节点的元素。兼容性IE9+
25. **X:nth-last-of-type(an+b)**：伪类，X为选择器，解析得到元素标签，选择**后面**有an+b-1个相同**标签**兄弟节点的元素。兼容性IE9+
26. **X:first-child**：伪类，选择满足X选择器的元素，且这个元素是其父节点的第一个子元素。兼容性IE7+
27. **X:last-child**：伪类，选择满足X选择器的元素，且这个元素是其父节点的最后一个子元素。兼容性IE9+
28. **X:only-child**：伪类，选择满足X选择器的元素，且这个元素是其父元素的唯一子元素。兼容性IE9+
29. **X:only-of-type**：伪类，选择X选择的元素，**解析得到元素标签**，如果该元素没有相同类型的兄弟节点时选中它。兼容性IE9+
30. **X:first-of-type**：伪类，选择X选择的元素，**解析得到元素标签**，如果该元素
是此此类型元素的第一个兄弟。选中它。兼容性IE9+


### css sprite是什么,有什么优缺点

概念：将多个小图片拼接到一个图片中。通过background-position和元素尺寸调节需要显示的背景图案。

优点：

1. 减少HTTP请求数，极大地提高页面加载速度
2. 增加图片信息重复度，提高压缩比，减少图片大小
3. 更换风格方便，只需在一张或几张图片上修改颜色或样式即可实现

缺点：

1. 图片合并麻烦
2. 维护麻烦，修改一个图片可能需要从新布局整个图片，样式


### `display: none;`与`visibility: hidden;`的区别
联系：它们都能让元素不可见

区别：

1. display:none;会让元素完全从渲染树中消失，渲染的时候不占据任何空间；visibility: hidden;不会让元素从渲染树消失，渲染师元素继续占据空间，只是内容不可见
2. display: none;是非继承属性，子孙节点消失由于元素从渲染树消失造成，通过修改子孙节点属性无法显示；visibility: hidden;是继承属性，子孙节点消失由于继承了hidden，通过设置visibility: visible;可以让子孙节点显式
3. 修改常规流中元素的display通常会造成文档重排。修改visibility属性只会造成本元素的重绘。
4. 读屏器不会读取display: none;元素内容；会读取visibility: hidden;元素内容

### css hack原理及常用hack

原理：利用**不同浏览器对CSS的支持和解析结果不一样**编写针对特定浏览器样式。常见的hack有1）属性hack。2）选择器hack。3）IE条件注释

- IE条件注释：适用于[IE5, IE9]常见格式如下

```
<!--[if IE 6]>
Special instructions for IE 6 here
<![endif]-->
```

- 选择器hack：不同浏览器对选择器的支持不一样

```
/***** Selector Hacks ******/

/* IE6 and below */
* html #uno  { color: red }

/* IE7 */
*:first-child+html #dos { color: red }

/* IE7, FF, Saf, Opera  */
html>body #tres { color: red }

/* IE8, FF, Saf, Opera (Everything but IE 6,7) */
html>/**/body #cuatro { color: red }

/* Opera 9.27 and below, safari 2 */
html:first-child #cinco { color: red }

/* Safari 2-3 */
html[xmlns*=""] body:last-child #seis { color: red }

/* safari 3+, chrome 1+, opera9+, ff 3.5+ */
body:nth-of-type(1) #siete { color: red }

/* safari 3+, chrome 1+, opera9+, ff 3.5+ */
body:first-of-type #ocho {  color: red }

/* saf3+, chrome1+ */
@media screen and (-webkit-min-device-pixel-ratio:0) {
 #diez  { color: red  }
}

/* iPhone / mobile webkit */
@media screen and (max-device-width: 480px) {
 #veintiseis { color: red  }
}

/* Safari 2 - 3.1 */
html[xmlns*=""]:root #trece  { color: red  }

/* Safari 2 - 3.1, Opera 9.25 */
*|html[xmlns*=""] #catorce { color: red  }

/* Everything but IE6-8 */
:root *> #quince { color: red  }

/* IE7 */
*+html #dieciocho {  color: red }

/* Firefox only. 1+ */
#veinticuatro,  x:-moz-any-link  { color: red }

/* Firefox 3.0+ */
#veinticinco,  x:-moz-any-link, x:default  { color: red  }
```

- 属性hack：不同浏览器解析bug或方法

```
/* IE6 */
#once { _color: blue }

/* IE6, IE7 */
#doce { *color: blue; /* or #color: blue */ }

/* Everything but IE6 */
#diecisiete { color/**/: blue }

/* IE6, IE7, IE8 */
#diecinueve { color: blue\9; }

/* IE7, IE8 */
#veinte { color/*\**/: blue\9; }

/* IE6, IE7 -- acts as an !important */
#veintesiete { color: blue !ie; } /* string after ! can be anything */
```

### specified value,computed value,used value计算方法

- specified value: 计算方法如下：
    1. 如果样式表设置了一个值，使用这个值
    2. 如果没有设置值，这个属性是继承属性，从父元素继承
    3. 如果没设置，并且不是继承属性，使用css规范指定的初始值

- computed value: 以specified value根据规范定义的行为进行计算，通常将相对值计算为绝对值，例如em根据font-size进行计算。一些使用百分数并且需要布局来决定最终值的属性，如width，margin。百分数就直接作为computed value。line-height的无单位值也直接作为computed value。这些值将在计算used value时得到绝对值。**computed value的主要作用是用于继承**

- used value：属性计算后的最终值，对于大多数属性可以通过window.getComputedStyle获得，尺寸值单位为像素。以下属性依赖于布局，
    - background-position
    - bottom, left, right, top
    - height, width
    - margin-bottom, margin-left, margin-right, margin-top
    - min-height, min-width
    - padding-bottom, padding-left, padding-right, padding-top
    - text-indent

### `link`与`@import`的区别

1. ``link``是HTML方式， ``@import``是CSS方式
2. ``link``最大限度支持并行下载，``@import``过多嵌套导致串行下载，出现[FOUC](http://www.bluerobot.com/web/css/fouc.asp/)
4. ``link``可以通过``rel="alternate stylesheet"``指定候选样式
5. 浏览器对``link``支持早于``@import``，可以使用``@import``对老浏览器隐藏样式
6. ``@import``必须在样式规则之前，可以在css文件中引用其他文件
6. 总体来说：**[link优于@import](http://www.stevesouders.com/blog/2009/04/09/dont-use-import/)**

### ``display: block;``和``display: inline;``的区别

``block``元素特点：

1.处于常规流中时，如果``width``没有设置，会自动填充满父容器
2.可以应用``margin/padding``
3.在没有设置高度的情况下会扩展高度以包含常规流中的子元素
4.处于常规流中时布局时在前后元素位置之间（独占一个水平空间）
5.忽略``vertical-align``

``inline``元素特点

1.水平方向上根据``direction``依次布局
2.不会在元素前后进行换行
3.受``white-space``控制
4.``margin/padding``在竖直方向上无效，水平方向上有效
5.``width/height``属性对非替换行内元素无效，宽度由元素内容决定
6.非替换行内元素的行框高由``line-height``确定，替换行内元素的行框高由``height``,``margin``,``padding``,``border``决定
6.浮动或绝对定位时会转换为``block``
7.``vertical-align``属性生效



### PNG,GIF,JPG的区别及如何选
参考资料： [选择正确的图片格式](http://www.yuiblog.com/blog/2008/11/04/imageopt-2/)
**GIF**:

1. 8位像素，256色
2. 无损压缩
3. 支持简单动画
4. 支持boolean透明
5. 适合简单动画

**JPEG**：

1. 颜色限于256
2. 有损压缩
3. 可控制压缩质量
4. 不支持透明
5. 适合照片

**PNG**：

1. 有PNG8和truecolor PNG
2. PNG8类似GIF颜色上限为256，文件小，支持alpha透明度，无动画
3. 适合图标、背景、按钮

### CSS有哪些继承属性

- 关于文字排版的属性如：
  +  [font](https://developer.mozilla.org/en-US/docs/Web/CSS/font)
  +  [word-break](https://developer.mozilla.org/en-US/docs/Web/CSS/word-break)
  +  [letter-spacing](https://developer.mozilla.org/en-US/docs/Web/CSS/letter-spacing)
  +  [text-align](https://developer.mozilla.org/en-US/docs/Web/CSS/text-align)
  +  [text-rendering](https://developer.mozilla.org/en-US/docs/Web/CSS/text-rendering)
  +  [word-spacing](https://developer.mozilla.org/en-US/docs/Web/CSS/word-spacing)
  +  [white-space](https://developer.mozilla.org/en-US/docs/Web/CSS/white-space)
  +  [text-indent](https://developer.mozilla.org/en-US/docs/Web/CSS/text-indent)
  +  [text-transform](https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform)
  +  [text-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow)
- [line-height](https://developer.mozilla.org/en-US/docs/Web/CSS/line-height)
- [color](https://developer.mozilla.org/en-US/docs/Web/CSS/color)
- [visibility](https://developer.mozilla.org/en-US/docs/Web/CSS/visibility)
- [cursor](https://developer.mozilla.org/en-US/docs/Web/CSS/cursor)



### IE6浏览器有哪些常见的bug,缺陷或者与标准不一致的地方,如何解决

- IE6不支持min-height，解决办法使用css hack：

```
.target {
    min-height: 100px;
    height: auto !important;
    height: 100px;   // IE6下内容高度超过会自动扩展高度
}
```

- ``ol``内``li``的序号全为1，不递增。解决方法：为li设置样式``display: list-item;``

- 未定位父元素``overflow: auto;``，包含``position: relative;``子元素，子元素高于父元素时会溢出。解决办法：1）子元素去掉``position: relative;``; 2）不能为子元素去掉定位时，父元素``position: relative;``

```
<style type="text/css">
.outer {
    width: 215px;
    height: 100px;
    border: 1px solid red;
    overflow: auto;
    position: relative;  /* 修复bug */
}
.inner {
    width: 100px;
    height: 200px;
    background-color: purple;
    position: relative;
}
</style>

<div class="outer">
    <div class="inner"></div>
</div>
```

- IE6只支持``a``标签的``:hover``伪类，解决方法：使用js为元素监听mouseenter，mouseleave事件，添加类实现效果：

```
<style type="text/css">
.p:hover,
.hover {
    background: purple;
}
</style>

<p class="p" id="target">aaaa bbbbb<span>DDDDDDDDDDDd</span> aaaa lkjlkjdf j</p>

<script type="text/javascript">
function addClass(elem, cls) {
    if (elem.className) {
        elem.className += ' ' + cls;
    } else {
        elem.className = cls;
    }
}
function removeClass(elem, cls) {
    var className = ' ' + elem.className + ' ';
    var reg = new RegExp(' +' + cls + ' +', 'g');
    elem.className = className.replace(reg, ' ').replace(/^ +| +$/, '');
}

var target = document.getElementById('target');
if (target.attachEvent) {
    target.attachEvent('onmouseenter', function () {
        addClass(target, 'hover');
    });
    target.attachEvent('onmouseleave', function () {
        removeClass(target, 'hover');
    })
}
</script>
```

- IE5-8不支持``opacity``，解决办法：

```
.opacity {
    opacity: 0.4
    filter: alpha(opacity=60); /* for IE5-7 */
    -ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=60)"; /* for IE 8*/
}
```

- IE6在设置``height``小于``font-size``时高度值为``font-size``，解决办法：``font-size: 0;``
- IE6不支持PNG透明背景，解决办法: **IE6下使用gif图片**
- IE6-7不支持``display: inline-block``解决办法：设置inline并触发hasLayout

```
    display: inline-block;
    *display: inline;
    *zoom: 1;
```

- IE6下浮动元素在浮动方向上与父元素边界接触元素的外边距会加倍。解决办法：
1）使用padding控制间距。
2）浮动元素``display: inline;``这样解决问题且无任何副作用：css标准规定浮动元素display:inline会自动调整为block
- 通过为块级元素设置宽度和左右margin为auto时，IE6不能实现水平居中，解决方法：为父元素设置``text-align: center;``

### 容器包含若干浮动元素时如何清理(包含)浮动

1. 容器元素闭合标签前添加额外元素并设置``clear: both``
2. 父元素触发块级格式化上下文(见块级可视化上下文部分)
3. 设置容器元素伪元素进行清理[推荐的清理浮动方法](http://nicolasgallagher.com/micro-clearfix-hack/)

```
/**
* 在标准浏览器下使用
* 1 content内容为空格用于修复opera下文档中出现
*   contenteditable属性时在清理浮动元素上下的空白
* 2 使用display使用table而不是block：可以防止容器和
*   子元素top-margin折叠,这样能使清理效果与BFC，IE6/7
*   zoom: 1;一致
**/

.clearfix:before,
.clearfix:after {
    content: " "; /* 1 */
    display: table; /* 2 */
}

.clearfix:after {
    clear: both;
}

/**
* IE 6/7下使用
* 通过触发hasLayout实现包含浮动
**/
.clearfix {
    *zoom: 1;
}
```

### 什么是FOUC?如何避免
Flash Of Unstyled Content：用户定义样式表加载之前浏览器使用默认样式显示文档，用户样式加载渲染之后再从新显示文档，造成页面闪烁。**解决方法**：把样式表放到文档的`head`

### 如何创建块级格式化上下文(block formatting context),BFC有什么用
创建规则：

1. 根元素
2. 浮动元素（``float``不是``none``）
3. 绝对定位元素（``position``取值为``absolute``或``fixed``）
4. ``display``取值为``inline-block``,``table-cell``, ``table-caption``,``flex``, ``inline-flex``之一的元素
5. ``overflow``不是``visible``的元素


作用：

1. 可以包含浮动元素
2. 不被浮动元素覆盖
3. 阻止父子元素的margin折叠

### display,float,position的关系

1. 如果``display``为none，那么position和float都不起作用，这种情况下元素不产生框
2. 否则，如果position值为absolute或者fixed，框就是绝对定位的，float的计算值为none，display根据下面的表格进行调整。
3. 否则，如果float不是none，框是浮动的，display根据下表进行调整
4. 否则，如果元素是根元素，display根据下表进行调整
5. 其他情况下display的值为指定值
总结起来：**绝对定位、浮动、根元素都需要调整``display``**
![display转换规则](img/display-adjust.png)

### 外边距折叠(collapsing margins)
毗邻的两个或多个``margin``会合并成一个margin，叫做外边距折叠。规则如下：

1. 两个或多个毗邻的普通流中的块元素垂直方向上的margin会折叠
2. 浮动元素/inline-block元素/绝对定位元素的margin不会和垂直方向上的其他元素的margin折叠
3. 创建了块级格式化上下文的元素，不会和它的子元素发生margin折叠
4. 元素自身的margin-bottom和margin-top相邻时也会折叠

### 如何确定一个元素的包含块(containing block)

1. 根元素的包含块叫做初始包含块，在连续媒体中他的尺寸与viewport相同并且anchored at the canvas origin；对于paged media，它的尺寸等于page area。初始包含块的direction属性与根元素相同。
2. ``position``为``relative``或者``static``的元素，它的包含块由最近的块级（``display``为``block``,``list-item``, ``table``）祖先元素的**内容框**组成
3. 如果元素``position``为``fixed``。对于连续媒体，它的包含块为viewport；对于paged media，包含块为page area
4. 如果元素``position``为``absolute``，它的包含块由祖先元素中最近一个``position``为``relative``,``absolute``或者``fixed``的元素产生，规则如下：
    - 如果祖先元素为行内元素，the containing block is the bounding box around the **padding boxes** of the first and the last inline boxes generated for that element.
    - 其他情况下包含块由祖先节点的**padding edge**组成

    如果找不到定位的祖先元素，包含块为**初始包含块**

### stacking context,布局规则
z轴上的默认层叠顺序如下（从下到上）：

1. 根元素的边界和背景
2. 常规流中的元素按照html中顺序
3. 浮动块
4. positioned元素按照html中出现顺序

如何创建stacking context：

1. 根元素
2. z-index不为auto的定位元素
3. a flex item with a z-index value other than 'auto'
4. opacity小于1的元素
5. 在移动端webkit和chrome22+，z-index为auto，position: fixed也将创建新的stacking context

### 如何水平居中一个元素
- 如果需要居中的元素为**常规流中inline元素**，为父元素设置`text-align: center;`即可实现
- 如果需要居中的元素为**常规流中block元素**，1）为元素设置宽度，2）设置左右margin为auto。3）IE6下需在父元素上设置`text-align: center;`,再给子元素恢复需要的值

```
<body>
    <div class="content">
    aaaaaa aaaaaa a a a a a a a a
    </div>
</body>

<style>
    body {
        background: #DDD;
        text-align: center; /* 3 */
    }
    .content {
        width: 500px;      /* 1 */
        text-align: left;  /* 3 */
        margin: 0 auto;    /* 2 */

        background: purple;
    }
</style>
```

- 如果需要居中的元素为**浮动元素**，1）为元素设置宽度，2）`position: relative;`，3）浮动方向偏移量（left或者right）设置为50%，4）浮动方向上的margin设置为元素宽度一半乘以-1

```
<body>
    <div class="content">
    aaaaaa aaaaaa a a a a a a a a
    </div>
</body>

<style>
    body {
        background: #DDD;
    }
    .content {
        width: 500px;         /* 1 */
        float: left;

        position: relative;   /* 2 */
        left: 50%;            /* 3 */
        margin-left: -250px;  /* 4 */

        background-color: purple;
    }
</style>
```

- 如果需要居中的元素为**绝对定位元素**，1）为元素设置宽度，2）偏移量设置为50%，3）偏移方向外边距设置为元素宽度一半乘以-1

```
<body>
    <div class="content">
    aaaaaa aaaaaa a a a a a a a a
    </div>
</body>

<style>
    body {
        background: #DDD;
        position: relative;
    }
    .content {
        width: 800px;

        position: absolute;
        left: 50%;
        margin-left: -400px;

        background-color: purple;
    }
</style>
```

- 如果需要居中的元素为**绝对定位元素**，1）为元素设置宽度，2）设置左右偏移量都为0,3）设置左右外边距都为auto

```
<body>
    <div class="content">
    aaaaaa aaaaaa a a a a a a a a
    </div>
</body>

<style>
    body {
        background: #DDD;
        position: relative;
    }
    .content {
        width: 800px;

        position: absolute;
        margin: 0 auto;
        left: 0;
        right: 0;

        background-color: purple;
    }
</style>
```

### 如何竖直居中一个元素
参考资料：[6 Methods For Vertical Centering With CSS](http://www.vanseodesign.com/css/vertical-centering/)。 [盘点8种CSS实现垂直居中](http://blog.csdn.net/freshlover/article/details/11579669)

- 需要居中元素为**单行文本**，为包含文本的元素设置大于`font-size`的`line-height`：

```
<p class="text">center text</p>

<style>
.text {
    line-height: 200px;
}
</style>
```


## $javascript概念部分

### DOM元素e的e.getAttribute(propName)和e.propName有什么区别和联系

- e.getAttribute()，是标准DOM操作文档元素属性的方法，具有通用性可在任意文档上使用，返回元素在源文件中**设置的属性**
- e.propName通常是在HTML文档中访问特定元素的**特性**，浏览器解析元素后生成对应对象（如a标签生成HTMLAnchorElement），这些对象的特性会根据特定规则结合属性设置得到，对于没有对应特性的属性，只能使用getAttribute进行访问
- e.getAttribute()返回值是源文件中设置的值，类型是字符串或者null（有的实现返回""）
- e.propName返回值可能是字符串、布尔值、对象、undefined等
- 大部分attribute与property是一一对应关系，修改其中一个会影响另一个，如id，title等属性
- 一些布尔属性`<input hidden/>`的检测设置需要hasAttribute和removeAttribute来完成，或者设置对应property
- 像`<a href="../index.html">link</a>`中href属性，转换成property的时候需要通过转换得到完整URL
- 一些attribute和property不是一一对应如：form控件中`<input value="hello"/>`对应的是defaultValue，修改或设置value property修改的是控件当前值，setAttribute修改value属性不会改变value property

### offsetWidth/offsetHeight,clientWidth/clientHeight与scrollWidth/scrollHeight的区别

- offsetWidth/offsetHeight返回值包含**content + padding + border**，效果与e.getBoundingClientRect()相同
- clientWidth/clientHeight返回值只包含**content + padding**，如果有滚动条，也**不包含滚动条**
- scrollWidth/scrollHeight返回值包含**content + padding + 溢出内容的尺寸**

[Measuring Element Dimension and Location with CSSOM in Windows Internet Explorer 9](http://msdn.microsoft.com/en-us/library/ie/hh781509(v=vs.85).aspx)

![元素尺寸](img/element-size.png)

### XMLHttpRequest通用属性和方法

1. `readyState`:表示请求状态的整数，取值：
  - UNSENT（0）：对象已创建
  - OPENED（1）：open()成功调用，在这个状态下，可以为xhr设置请求头，或者使用send()发送请求
  - HEADERS_RECEIVED(2)：所有重定向已经自动完成访问，并且最终响应的HTTP头已经收到
  - LOADING(3)：响应体正在接收
  - DONE(4)：数据传输完成或者传输产生错误
3. `onreadystatechange`：readyState改变时调用的函数
4. `status`：服务器返回的HTTP状态码（如，200， 404）
5. `statusText`:服务器返回的HTTP状态信息（如，OK，No Content）
6. `responseText`:作为字符串形式的来自服务器的完整响应
6. `responseXML`: Document对象，表示服务器的响应解析成的XML文档
7. `abort()`:取消异步HTTP请求
8. `getAllResponseHeaders()`: 返回一个字符串，包含响应中服务器发送的全部HTTP报头。每个报头都是一个用冒号分隔开的名/值对，并且使用一个回车/换行来分隔报头行
9. `getResponseHeader(headerName)`:返回headName对应的报头值
10. `open(method, url, asynchronous [, user, password])`:初始化准备发送到服务器上的请求。method是HTTP方法，不区分大小写；url是请求发送的相对或绝对URL；asynchronous表示请求是否异步；user和password提供身份验证
11. `setRequestHeader(name, value)`:设置HTTP报头
12. `send(body)`:对服务器请求进行初始化。参数body包含请求的主体部分，对于POST请求为键值对字符串；对于GET请求，为null

### focus/blur与focusin/focusout的区别与联系

1. focus/blur不冒泡，focusin/focusout冒泡
2. focus/blur兼容性好，focusin/focusout在除FireFox外的浏览器下都保持良好兼容性，如需使用事件托管，可考虑在FireFox下使用事件捕获elem.addEventListener('focus', handler, true)
3. 可获得焦点的元素：
    1. window
    2. 链接被点击或键盘操作
    3. 表单空间被点击或键盘操作
    4. 设置`tabindex`属性的元素被点击或键盘操作

### mouseover/mouseout与mouseenter/mouseleave的区别与联系

1. mouseover/mouseout是标准事件，**所有浏览器都支持**；mouseenter/mouseleave是IE5.5引入的特有事件后来被DOM3标准采纳，现代标准浏览器也支持
2. mouseover/mouseout是**冒泡**事件；mouseenter/mouseleave**不冒泡**。需要为**多个元素监听鼠标移入/出事件时，推荐mouseover/mouseout托管，提高性能**
3. 标准事件模型中event.target表示发生移入/出的元素,**vent.relatedTarget**对应移出/如元素；在老IE中event.srcElement表示发生移入/出的元素，**event.toElement**表示移出的目标元素，**event.fromElement**表示移入时的来源元素

例子：鼠标从div#target元素移出时进行处理，判断逻辑如下：

    <div id="target"><span>test</span></div>

    <script type="text/javascript">
    var target = document.getElementById('target');
    if (target.addEventListener) {
      target.addEventListener('mouseout', mouseoutHandler, false);
    } else if (target.attachEvent) {
      target.attachEvent('onmouseout', mouseoutHandler);
    }

    function mouseoutHandler(e) {
      e = e || window.event;
      var target = e.target || e.srcElement;

      // 判断移出鼠标的元素是否为目标元素
      if (target.id !== 'target') {
        return;
      }

      // 判断鼠标是移出元素还是移到子元素
      var relatedTarget = event.relatedTarget || e.toElement;
      while (relatedTarget !== target
        && relatedTarget.nodeName.toUpperCase() !== 'BODY') {
        relatedTarget = relatedTarget.parentNode;
      }

      // 如果相等，说明鼠标在元素内部移动
      if (relatedTarget === target) {
        return;
      }

      // 执行需要操作
      //alert('鼠标移出');

    }
    </script>

### sessionStorage,localStorage,cookie区别

1. 都会在浏览器端保存，有大小限制，同源限制
2. cookie会在请求时发送到服务器，作为会话标识，服务器可修改cookie；web storage不会发送到服务器
3. cookie有path概念，子路径可以访问父路径cookie，父路径不能访问子路径cookie
4. 有效期：cookie在设置的有效期内有效，默认为浏览器关闭；sessionStorage在窗口关闭前有效，localStorage长期有效，直到用户删除
5. 共享：sessionStorage不能共享，localStorage在同源文档之间共享，cookie在同源且符合path规则的文档之间共享
6. localStorage的修改会促发其他文档窗口的update事件
7. cookie有secure属性要求HTTPS传输
8. 浏览器不能保存超过300个cookie，单个服务器不能超过20个，每个cookie不能超过4k。web storage大小支持能达到5M

### javascript跨域通信
同源：两个文档同源需满足

1. 协议相同
2. 域名相同
3. 端口相同

跨域通信：js进行DOM操作、通信时如果目标与当前窗口不满足同源条件，浏览器为了安全会阻止跨域操作。跨域通信通常有以下方法

- 如果是log之类的简单**单项通信**，新建``<img>``,``<script>``,``<link>``,``<iframe>``元素，通过src，href属性设置为目标url。实现跨域请求
- 如果请求**json数据**，使用``<script>``进行jsonp请求
- 现代浏览器中**多窗口通信**使用HTML5规范的targetWindow.postMessage(data, origin);其中data是需要发送的对象，origin是目标窗口的origin。window.addEventListener('message', handler, false);handler的event.data是postMessage发送来的数据，event.origin是发送窗口的origin，event.source是发送消息的窗口引用
- 内部服务器代理请求跨域url，然后返回数据
- 跨域请求数据，现代浏览器可使用HTML5规范的CORS功能，只要目标服务器返回HTTP头部**``Access-Control-Allow-Origin: *``**即可像普通ajax一样访问跨域资源

### javascript有哪几种数据类型
六种基本数据类型

- undefined
- null
- string
- boolean
- number
- [symbol](https://developer.mozilla.org/en-US/docs/Glossary/Symbol)(ES6)

一种引用类型

- Object

### 什么闭包,闭包有什么用
**闭包是在某个作用域内定义的函数，它可以访问这个作用域内的所有变量**。闭包作用域链通常包括三个部分：

1. 函数本身作用域。
2. 闭包定义时的作用域。
3. 全局作用域。

闭包常见用途：

1. 创建特权方法用于访问控制
2. 事件处理程序及回调

### javascript有哪几种方法定义函数

1. [函数声明表达式](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function)
2. [function操作符](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/function)
3. [Function 构造函数](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function)
4. [ES6:arrow function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/arrow_functions)

重要参考资料：[MDN:Functions_and_function_scope](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions_and_function_scope)

### 应用程序存储和离线web应用
HTML5新增应用程序缓存，允许web应用将应用程序自身保存到用户浏览器中，用户离线状态也能访问。
1.为html元素设置manifest属性:``<html manifest="myapp.appcache">``，其中后缀名只是一个约定，真正识别方式是通过``text/cache-manifest``作为MIME类型。所以需要配置服务器保证设置正确
2.manifest文件首行为``CACHE MANIFEST``，其余就是要缓存的URL列表，每个一行，相对路径都相对于manifest文件的url。注释以#开头
3.url分为三种类型：``CACHE``:为默认类型。``NETWORK``：表示资源从不缓存。 ``FALLBACK``:每行包含两个url，第二个URL是指需要加载和存储在缓存中的资源， 第一个URL是一个前缀。任何匹配该前缀的URL都不会缓存，如果从网络中载入这样的URL失败的话，就会用第二个URL指定的缓存资源来替代。以下是一个文件例子：

```
CACHE MANIFEST

CACHE:
myapp.html
myapp.css
myapp.js

FALLBACK:
videos/ offline_help.html

NETWORK:
cgi/
```

### 客户端存储localStorage和sessionStorage

- localStorage有效期为永久，sessionStorage有效期为顶层窗口关闭前
- 同源文档可以读取并修改localStorage数据，sessionStorage只允许同一个窗口下的文档访问，如通过iframe引入的同源文档。
- Storage对象通常被当做普通javascript对象使用：**通过设置属性来存取字符串值**，也可以通过**setItem(key, value)设置**，**getItem(key)读取**，**removeItem(key)删除**，**clear()删除所有数据**，**length表示已存储的数据项数目**，**key(index)返回对应索引的key**

```
localStorage.setItem('x', 1); // storge x->1
localStorage.getItem('x); // return value of x

// 枚举所有存储的键值对
for (var i = 0, len = localStorage.length; i < len; ++i ) {
    var name = localStorage.key(i);
    var value = localStorage.getItem(name);
}

localStorage.removeItem('x'); // remove x
localStorage.clear();  // remove all data
```

### cookie及其操作

- cookie是web浏览器存储的少量数据，最早设计为服务器端使用，作为HTTP协议的扩展实现。cookie数据会自动在浏览器和服务器之间传输。
- 通过读写cookie检测是否支持
- cookie属性有**名**，**值**，**max-age**，**path**, **domain**，**secure**；
- cookie默认有效期为浏览器会话，一旦用户关闭浏览器，数据就丢失，通过设置**max-age=seconds**属性告诉浏览器cookie有效期
- cookie作用域通过**文档源**和**文档路径**来确定，通过**path**和**domain**进行配置，web页面同目录或子目录文档都可访问
- 通过cookie保存数据的方法为：为document.cookie设置一个符合目标的字符串如下
- 读取document.cookie获得'; '分隔的字符串，key=value,解析得到结果

```
document.cookie = 'name=qiu; max-age=9999; path=/; domain=domain; secure';

document.cookie = 'name=aaa; path=/; domain=domain; secure';
// 要改变cookie的值，需要使用相同的名字、路径和域，新的值
// 来设置cookie，同样的方法可以用来改变有效期

// 设置max-age为0可以删除指定cookie

//读取cookie，访问document.cookie返回键值对组成的字符串，
//不同键值对之间用'; '分隔。通过解析获得需要的值
```

[cookieUtil.js](https://github.com/qiu-deqing/google/blob/master/module/js/cookieUtil.js)：自己写的cookie操作工具

### javascript有哪些方法定义对象

1. 对象字面量： `var obj = {};`
2. 构造函数： `var obj = new Object();`
3. Object.create(): `var obj = Object.create(Object.prototype);`

### ===运算符判断相等的流程是怎样的

1. 如果两个值不是相同类型，它们不相等
2. 如果两个值都是null或者都是undefined，它们相等
3. 如果两个值都是布尔类型true或者都是false，它们相等
4. 如果其中有一个是**NaN**，它们不相等
5. 如果都是数值型并且数值相等，他们相等， -0等于0
6. 如果他们都是字符串并且在相同位置包含相同的16位值，他它们相等；如果在长度或者内容上不等，它们不相等；两个字符串显示结果相同但是编码不同==和===都认为他们不相等
7. 如果他们指向相同对象、数组、函数，它们相等；如果指向不同对象，他们不相等

### ==运算符判断相等的流程是怎样的

1. 如果两个值类型相同，按照===比较方法进行比较
2. 如果类型不同，使用如下规则进行比较
  1. 如果其中一个值是null，另一个是undefined，它们相等
  2. 如果一个值是**数字**另一个是**字符串**，将**字符串转换为数字**进行比较
  3. 如果有布尔类型，将**true转换为1，false转换为0**，然后用==规则继续比较
  4. 如果一个值是对象，另一个是数字或字符串，将对象转换为原始值然后用==规则继续比较
  5. **其他所有情况都认为不相等**

### 对象到字符串的转换步骤

1. 如果对象有toString()方法，javascript调用它。如果返回一个原始值（primitive value如：string number boolean）,将这个值转换为字符串作为结果
2. 如果对象没有toString()方法或者返回值不是原始值，javascript寻找对象的valueOf()方法，如果存在就调用它，返回结果是原始值则转为字符串作为结果
3. 否则，javascript不能从toString()或者valueOf()获得一个原始值，此时throws a TypeError


### 对象到数字的转换步骤

    1. 如果对象有valueOf()方法并且返回元素值，javascript将返回值转换为数字作为结果
    2. 否则，如果对象有toString()并且返回原始值，javascript将返回结果转换为数字作为结果
    3. 否则，throws a TypeError

### <,>,<=,>=的比较规则

所有比较运算符都支持任意类型，但是**比较只支持数字和字符串**，所以需要执行必要的转换然后进行比较，转换规则如下:
1. 如果操作数是对象，转换为原始值：如果valueOf方法返回原始值，则使用这个值，否则使用toString方法的结果，如果转换失败则报错
2. 经过必要的对象到原始值的转换后，如果两个操作数都是字符串，按照字母顺序进行比较（他们的16位unicode值的大小）
3. 否则，如果有一个操作数不是字符串，**将两个操作数转换为数字**进行比较

### +运算符工作流程
1. 如果有操作数是对象，转换为原始值
2. 此时如果有**一个操作数是字符串**，其他的操作数都转换为字符串并执行连接
3. 否则：**所有操作数都转换为数字并执行加法**

### 函数内部arguments变量有哪些特性,有哪些属性,如何将它转换为数组

- arguments所有函数中都包含的一个局部变量，是一个类数组对象，对应函数调用时的实参。如果函数定义同名参数会在调用时覆盖默认对象
- arguments[index]分别对应函数调用时的实参，并且通过arguments修改实参时会同时修改实参
- arguments.length为实参的个数（Function.length表示形参长度）
- arguments.callee为当前正在执行的函数本身，使用这个属性进行递归调用时需注意this的变化
- arguments.caller为调用当前函数的函数（已被遗弃）
- 转换为数组：<code>var args = Array.prototype.slice.call(arguments, 0);</code>

### DOM事件模型是如何的,编写一个EventUtil工具类实现事件管理兼容

- DOM事件包含捕获（capture）和冒泡（bubble）两个阶段：捕获阶段事件从window开始触发事件然后通过祖先节点一次传递到触发事件的DOM元素上；冒泡阶段事件从初始元素依次向祖先节点传递直到window
- 标准事件监听elem.addEventListener(type, handler, capture)/elem.removeEventListener(type, handler, capture)：handler接收保存事件信息的event对象作为参数，event.target为触发事件的对象，handler调用上下文this为绑定监听器的对象，event.preventDefault()取消事件默认行为，event.stopPropagation()/event.stopImmediatePropagation()取消事件传递
- 老版本IE事件监听elem.attachEvent('on'+type, handler)/elem.detachEvent('on'+type, handler)：handler不接收event作为参数，事件信息保存在window.event中，触发事件的对象为event.srcElement，handler执行上下文this为window使用闭包中调用handler.call(elem, event)可模仿标准模型，然后返回闭包，保证了监听器的移除。event.returnValue为false时取消事件默认行为，event.cancleBubble为true时取消时间传播
- 通常利用事件冒泡机制托管事件处理程序提高程序性能。

```
/**
 * 跨浏览器事件处理工具。只支持冒泡。不支持捕获
 * @author  (qiu_deqing@126.com)
 */

var EventUtil = {
    getEvent: function (event) {
        return event || window.event;
    },
    getTarget: function (event) {
        return event.target || event.srcElement;
    },
    // 返回注册成功的监听器，IE中需要使用返回值来移除监听器
    on: function (elem, type, handler) {
        if (elem.addEventListener) {
            elem.addEventListener(type, handler, false);
            return handler;
        } else if (elem.attachEvent) {
            var wrapper = function () {
              var event = window.event;
              event.target = event.srcElement;
              handler.call(elem, event);
            };
            elem.attachEvent('on' + type, wrapper);
            return wrapper;
        }
    },
    off: function (elem, type, handler) {
        if (elem.removeEventListener) {
            elem.removeEventListener(type, handler, false);
        } else if (elem.detachEvent) {
            elem.detachEvent('on' + type, handler);
        }
    },
    preventDefault: function (event) {
        if (event.preventDefault) {
            event.preventDefault();
        } else if ('returnValue' in event) {
            event.returnValue = false;
        }
    },
    stopPropagation: function (event) {
        if (event.stopPropagation) {
            event.stopPropagation();
        } else if ('cancelBubble' in event) {
            event.cancelBubble = true;
        }
    },
    /**
     * keypress事件跨浏览器获取输入字符
     * 某些浏览器在一些特殊键上也触发keypress，此时返回null
     **/
     getChar: function (event) {
        if (event.which == null) {
            return String.fromCharCode(event.keyCode);  // IE
        }
        else if (event.which != 0 && event.charCode != 0) {
            return String.fromCharCode(event.which);    // the rest
        }
        else {
            return null;    // special key
        }
     }
};
```

### 评价一下三种方法实现继承的优缺点,并改进

```
function Shape() {}

function Rect() {}

// 方法1
Rect.prototype = new Shape();

// 方法2
Rect.prototype = Shape.prototype;

// 方法3
Rect.prototype = Object.create(Shape.prototype);

Rect.prototype.area = function () {
  // do something
};
```

方法1：

1. 优点：正确设置原型链实现继承
2. 优点：父类实例属性得到继承，原型链查找效率提高，也能为一些属性提供合理的默认值
3. 缺点：父类实例属性为引用类型时，不恰当地修改会导致所有子类被修改
4. 缺点：创建父类实例作为子类原型时，可能无法确定构造函数需要的合理参数，这样提供的参数继承给子类没有实际意义，当子类需要这些参数时应该在构造函数中进行初始化和设置
5. 总结：继承应该是继承方法而不是属性，为子类设置父类实例属性应该是通过在子类构造函数中调用父类构造函数进行初始化

方法2：

1. 优点：正确设置原型链实现继承
2. 缺点：父类构造函数原型与子类相同。修改子类原型添加方法会修改父类

方法3：

1. 优点：正确设置原型链且避免方法1.2中的缺点
2. 缺点：ES5方法需要注意兼容性

改进：

1. 所有三种方法应该在子类构造函数中调用父类构造函数实现实例属性初始化

```
function Rect() {
    Shape.call(this);
}
```


2. 用新创建的对象替代子类默认原型，设置``Rect.prototype.constructor = Rect;``保证一致性
3. 第三种方法的polyfill：

```
function create(obj) {
    if (Object.create) {
        return Object.create(obj);
    }

    function f() {};
    f.prototype = obj;
    return new f();
}
```

