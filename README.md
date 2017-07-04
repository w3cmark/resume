resume
======

# 技能

---
### **介绍一下你自己**
包括：最强的技能、最深入研究的知识领域、个性中最积极的部分、做过的最成功的事、主要的成就等
对互联网比较感兴趣
对前端技术

### **最大的优缺点**
从自己的优点说起，中间加一些小缺点，最后再把问题转回到优点上，突出优点的部分
喜欢动手、思考、写总结、对工作难点比较执着；对自己的约束力还是不够

### **说说你的家庭**
希望听到的重点也在于家庭对求职者的积极影响。外企相信，和睦的家庭关系对一个人的成长有潜移默化的影响

### **对行业、技术发展趋势的看法**
对所面试的公司预先了解很多，包括公司各个部门，发展情况

### **就你申请的这个职位，你认为你还欠缺什么**
对于这个职位和我的能力来说，我相信自己是可以胜任的，只是缺乏经验，这个问题我想我可以进入公司以后以最短的时间来解决，我的学习能力很强，我相信可以很快融入公司的企业文化，进入工作状态。

### **你还有什么问题吗**
贵公司对新入公司的员工有没有什么培训项目，我可以参加吗？或者说贵公司的晋升机制是什么样的？

## **面试流程**
+ 做过最满意的项目是什么？
>时尚网wap版，移动的第一个完整的、独立完成前端的大型整站项目

+ 你处于什么样的角色，起到了什么方面的作用？
>处于整个项目前端的执行者

+ 在项目中遇到什么技术问题？具体是如何解决的？
>1、焦点图插件不满足滑动后继续滚动——改写插件
2、瀑布流的实现

+ 如果再做这个项目，你会在哪些方面进行改善？
>焦点图插件的改进，增加按需加载

+ 描述一个你遇到过的技术问题，你是如何解决的？
>Q:瀑布流在IOS的chrome下出现左右高度统计出错的问题，导致下面的加载会全部偏向一般。

A:原因是因为图片加载但没显示出来时计算高度，通过高度比较来决定该插入哪一边失效。

解决方法，先判断图片加载之后，按比例计算出图片的高度，赋值高度属性，确保图片没显示时高度是真实的

>Q:wp系统下position fixed抖动，pc上面IE9都没问题，wp系统是8.0，用的是ie10

A：导致抖动的原因是设置fixed的元素，加入了背景图片，解决办法是把背景图片分开，比如可以通过伪类after或者before来实现。

+ 最近在学什么？接下来半年你打算学习什么？

>学习js、nodejs、js模板、前端自动化工具、html5和css3动画、MVC框架



**JS**
（待完善）

**css3**

1. 新增的属性 `box-shadow`、`text-shadow`、`boder-image`、`background-clip`等
2. 动画属性 transform（变换）/transition（过度）/animation
    transform属性：旋转：rotate() / 倾斜：skew() / 缩放：scale() / translate()/matrix：矩阵，六个值
3. 新的选择器 比如子串匹配的属性选择符、结构性伪类、目标伪类、状态伪类

**HTML5**

1. meta声明
2. 新增的标签 (header/nav/video/audio/canvas/svg)
3. 表单新特性 (email/number/color/tel/x-webkit-speech 等)
4. 新增的js api (localstorage/seasionstorage/classList/DeviceMotionEvent/FileReader/Webworker/Drag & Drop)

+ 技术实现细节

+ 最值得自豪的，可以拿出来和朋友分享的事情

+ 除了日常工作，还会做哪些事情来为团队贡献

（1）分享项目中遇到的问题和解决方案（整理bug）

（2）分享自己留意的前端的新技术和工具

（3）参与工作新问题的讨论

+ 目前主流移动设备的分辨率

320 x 480

480 x 640 (安卓平板)

768 x 1024 (ipad 竖屏)

1536x2048(ipad mini2)

+ 看过有关前端开发的书籍

《web前端黑客技术揭秘》

《犀利开发 jQuery内核详解与实践》

《JavaScript高级程序设计》（邮电出版、曹力/张欣翻译）

《JavaScript权威指南》

《CSS权威指南》

## **知识点**

### **display有多少个属性**

``list-item``	此元素会作为列表显示。

``run-in``	此元素会根据上下文作为块级元素或内联元素显示。

``table``	此元素会作为块级表格来显示（类似``table``），表格前后带有换行符。

``inline-table``	此元素会作为内联表格来显示（类似`` <table>``），表格前后没有换行符。

``table-row-group``	此元素会作为一个或多个行的分组来显示（类似 ``<tbody>``）。

``table-header-group``	此元素会作为一个或多个行的分组来显示（类似 ``<thead>``）。

``table-footer-group``	此元素会作为一个或多个行的分组来显示（类似 ``<tfoot>``）。

``table-row``	此元素会作为一个表格行显示（类似 ``<tr>``）。

``table-column-group``	此元素会作为一个或多个列的分组来显示（类似 ``<colgroup>``）。

``table-column``	此元素会作为一个单元格列显示（类似 ``<col>``）

``table-cell``	此元素会作为一个表格单元格显示（类似 ``<td>`` 和 ``<th>``）

``table-caption``	此元素会作为一个表格标题显示（类似 ``<caption>``）

``inherit``	规定应该从父元素继承 ``display`` 属性的值。

### **inline-block兼容性**

IE 7和Firefox 2及以前的版本是不支持``inline-block``，可以通过设置hasLayout（加上zoom: 1，触发layout）;Firefox 2可以用``display: -moz-inline-box``、``display: -moz-inline-stack``

### **CSS兼容问题**

#### 属性hack
```
.sofish{
    padding:10px;
    -webkit-padding:10px; /*webkit内核*/
    -moz-padding:10px; /*火狐*/
    -o-padding:10px; /*opera*/
    -ms-padding:10px; /*IE*/
    padding:9px\9; /* all ie */
    padding:8px\0; /* ie8-9 */
    *padding:5px; /* ie6-7 */
    +padding:7px; /* ie7 */
    _padding:6px; /* ie6 */
}

```
#### IE 注释
```
<!--[if IE6]><body class="ie6"><![endif]-->
<!--[if IE7]><body class="ie7"><![endif]-->
<!--[if IE8]><body class="ie8"><![endif]-->
<!--[if IE9]><body class="ie9"><![endif]-->
<!--[if !IE]><body class="non-ie"><![endif]-->
```
#### 选择器hack
```
/* IE6 and below */
* html #uno  { color: red }  或  *html #uno  { color: red }
/* IE7 */
*+html #dieciocho {color: red }  或 *:first-child+html #dos { color: red }

/* IE7, FF, Saf, Opera  */
html>body #tres { color: red }

/* IE8, FF, Saf, Opera (Everything but IE 6,7) */
html>/**/body #cuatro { color: red }
```
#### JS兼容问题
+ 下一兄弟节点的兼容问题
（FF会将空白、换行等文本信息也当做childNodes中的一员，而IE则会忽略它们，只将DOM节点当做是childNodes的一员）
```
function getNextNode(node){
    node=typeof node=="string"?document.getElementById(node):node;
    var nextNode=node.nextSibling;
    if(!nextNode)return null;
    if(!document.all){  //FF不识别document.all
        while(true){
            if(nextNode.nodeType==1){
                break;
            }else{
                if(nextNode.nextSibling){
                    nextNode=nextNode.nextSibling;
                }else{
                    break;
                }
            }
        }
    }
    return nextNode;
}
```

+  获取事件源
 (IE用srcElement获取事件源，而FF用target获取事件源)
```
function getEventTarget(e){
    e=window.event||e;
    return e.srcElement||e.target;
}
```

+ 添加事件响应函数
```
function addEventHandler(elm,eventType,handler){
    elm=typeof elm=="string"?document.getElementById(elm):elm;
    if(elm.attachEvent){
        elm.attachEvent("on"+eventType,handler);
    }else if(elm.addEventListener){
        elm.addEventListener(eventType,handler,false);
    }else
        return false;
}
```
+ 阻止事件冒泡stopPropagation
```
function stopPropagation(e){
    e=window.event||e;
    if(document.all){//只有ie识别
        e.cancelBubble=true;
    }else{
        e.stopPropagation();
    }
}
```

### **盒子模型有多少种**
IE6盒子模型中，盒子的尺寸包含了内容区，padding，border和margin这四个部分，而W3C的盒子模型中，盒子的尺寸只包含内容区，padding，border 和 margin 被排除在盒子尺寸之外。
>注：在 CSS3 中，增加了属性：``box-sizing``。box-sizing 有两个可选值，一个是默认的content-box一个是border-box，选用后者，盒子模型将按 IE6 的方式进行处理。

### **正确理解 Repaint 和 Reflow**
Repaint(重绘)就是在一个元素的外观被改变，但没有改变布局(宽高)的情况下发生，如改变visibility、outline、背景色等等。
Reflow(重排)就是DOM的变化影响到了元素的几何属性（宽和高），浏览器会重新计算元素的几何属性，会使渲染树中受到影响的部分失效，浏览器会验证DOM树上的所有其它结点的visibility属性，这也是Reflow低效的原因。如：改变窗囗大小、改变文字大小、内容的改变、浏览器窗口变化，style属性的改变等等。
通过设置style属性改变结点样式的话，每设置一次都会导致一次reflow，所以最好通过设置class的方式；　有动画效果的元素，它的position属性应当设为fixed或absolute，这样不会影响其它元素的布局；如果功能需求上不能设置position为fixed或absolute，那么就权衡速度的平滑性。

### **sass vs less**
为什么Sass比LESS要好
Sass有很多可用的方法和逻辑。例如：条件和循环语句。LESS也可以做到，但不是很高效且不直观。像LESS一样，Sass也内置了一些非常友好的函数，像颜色，数字，还有变量列表。
Sass用户可以使用功能强大的Compass库。这些库LESS用户也可以用，但并不完全一样，因为这是由一个庞大的社区来共同维护的。Compass有非常强大的特性，像自动生成图片切片（CSS Sprites)，传统浏览器支持，还有对CSS3的跨浏览器支持等。

用Sass和Compass时的问题

这些似乎是人们在使用Sass时遇到的最大问题：
建立Ruby的运行环境会产生的工作量；
对命令行的恐惧；
切换到另一个工具所产生的不便和额外的时间消耗；

### **Twitter Bootstrap**

Bootstrap是基于LESS的一套前端工具库，想以一个项目，整合Compass，Blueprint，h5bp的目标功能，成为web前端的一站式解决方案。

一套完整的基础css模块，但不如compass丰富和强大
一套预定义样式表，包括一个格子布局系统，和blueprint提供的差不多，只是设计风格不一样
一组基于Jquery的js交互插件，这是Bootstrap真正强大的地方，也是她严格意义上可以取代Blueprint的原因所在，这些非常不错的小插件，包括对话框，下拉导航等等，不但功能完善，而且十分精致，正在成为众多jquery项目的默认设计标准。
特别提一下，Bootstrap使用Normalize.css来进行Reset CSS，这一项目已经成为了事实标准(超过Compass的Eric meyer 2.0)，强烈推荐使用，另外前边说的h5bp也使用Normalize，因此，如果你在项目中同时使用了h5bp和Bootstrap， 请注意，没有必要再引入h5bp的初始样式表style.css

### **HTML5相关 Webworker、Drag & Drop**
+ Webworker
web worker 是运行在后台的 JavaScript，独立于其他脚本，不会影响页面的性能。您可以继续做任何愿意做的事情：点击、选取内容等等，而此时 web worker 在后台运行。
```
var w;
function startWorker(){
    if(typeof(Worker)!=="undefined"){
        if(typeof(w)=="undefined"){
            w=new Worker("/example/html5/demo_workers.js");
        }
        w.onmessage = function (event) {
            document.getElementById("result").innerHTML=event.data;
        };
    }else{
        document.getElementById("result").innerHTML="Sorry, your browser does not support Web Workers...";
    }
}

function stopWorker(){
    w.terminate();//终止监听
}
```
+ Drag & Drop
1、为了使元素可拖动，把 draggable 属性设置为 true
2、
``栗子``
```
<style type="text/css">
#div1 {width:488px;height:70px;padding:10px;border:1px solid #aaaaaa;}
</style>
<script type="text/javascript">
function allowDrop(ev)
{
ev.preventDefault();
}

function drag(ev)
{
ev.dataTransfer.setData("Text",ev.target.id);
}

function drop(ev)
{
ev.preventDefault();
var data=ev.dataTransfer.getData("Text");
ev.target.appendChild(document.getElementById(data));
}
</script>
</head>
<body>

<p>请把 W3School 的图片拖放到矩形中：</p>

<div id="div1" ondrop="drop(event)" ondragover="allowDrop(event)"></div>
<br />
<img id="drag1" src="/i/w3school_banner.gif" draggable="true" ondragstart="drag(event)" />
```
### **浏览器是怎样渲染一个页面**
由从服务器接收到的 HTML 形成DOM（文档对象模型）。
样式被加载和解析，形成 CSSOM（CSS 对象模型）。
紧接着 DOM 和 CSSOM 创建了一个渲染树，这个渲染树是一些被渲染对象的集合（ Webkit 分别叫它们”renderer”和”render object”，而在Gecko 引擎中叫”frame”）。除了不可见的元素（比如 head 标签和一些有 display:none 属性的元素），渲染树映射了 DOM 的结构。在渲染树中，每一个文本字符串都被当做一个独立的 renderer。每个渲染对象都包含了与之对应的计算过样式的DOM 对象（或者一个文本块）。换句话说，渲染树描述了 DOM 的直观的表现形式。
对每个渲染元素来说，它的坐标是经过计算的，这被叫做“布局(layout)”。浏览器使用一种只需要一次处理的“流方法”来布局所有元素（tables需要多次处理）。
最后，将布局显示在浏览器窗口中，这个过程叫做“绘制(painting)”。

``重绘``
当在页面上修改了一些不需要改变定位的样式的时候（比如background-color,border-color,visibility)，浏览器只会将新的样式重新绘制给元素（这就叫一次“重绘”或者“重新定义样式”）


``重排``
当页面上的改变影响了文档内容、结构或者元素定位时，就会发生重排（或称“重新布局”）。重排通常由以下改变触发：

DOM 操作（如元素增、删、改或者改变元素顺序）。
内容的改变，包括 Form 表单中文字的变化。
计算或改变 CSS 属性。
增加或删除一个样式表。
改变”class”属性。
浏览器窗口的操作（改变大小、滚动窗口）。
激活伪类（如:hover状态）。

### **加载和渲染过程**
页面加载和渲染的过程（涉及内核间的差异以及并发处理）
从浏览器地址栏的请求链接开始，浏览器通过DNS解析查到域名映射的IP地址，成功之后浏览器端向此IP地址取得连接，成功连接之后，浏览器端将请 求头信息 通过HTTP协议向此IP地址所在服务器发起请求，服务器接受到请求之后等待处理，最后向浏览器端发回响应，此时在HTTP协议下，浏览器从服务器接收到 text/html类型的代码，浏览器开始显示此html，并获取其中内嵌资源地址，然后浏览器再发起请求来获取这些资源，并在浏览器的html中显示。

其实浏览器加载显示html的顺序是按下面的顺序进行的：

1、IE下载的顺序是从上到下，渲染的顺序也是从上到下，下载和渲染是同时进行的。

2、在渲染到页面的某一部分时，其上面的所有部分都已经下载完成（并不是说所有相关联的元素都已经下载完）。

3、如果遇到语义解释性的标签嵌入文件（JS脚本，CSS 脚本）在IE的下载过程会启用单独连接进行下载。

4、并且在下载后进行解析，解析过程中，停止页面所有往下元素的下载。

5、样式表在下载完成后，将和以前下载的所有样式表一起进行解析，解析完成后，将对此前所有元素（含以前已经渲染的）重新进行渲染。

6、JS、CSS中如有重定义，后定义函数将覆盖前定义函数。

Firefox处理下载和渲染顺序大体相同，只是在细微之处有些差别，例如：iframe的渲染
>样式文件和JS文件一样是下载完一个解析一个的

### **运算符**
 i++和 ++i的区别，i++单独使用时候和++i一模一样，i++是等i这个表达式运算结束后再运算i+1，然后改变i的值,
而++i是先运算i+1,然后改变i的值，然后再和外面的表达式结合，进行整体运算。

### **字符串处理**
toFixed(num)（ps：num为保留小数点后几位）
Math.ceil(num) //返回大于等于其数值参数的最大整数
Math.floor(num) //返回小于等于其数值参数的最大整数
Math.round(num) //四舍五入取整
concat 将两个或多个字符的文本组合起来，返回一个新的字符串。
indexOf 返回字符串中一个子串第一处出现的索引（从左到右搜索）。如果没有匹配项，返回 -1 。
charAt 返回指定位置的字符。
lastIndexOf 返回字符串中一个子串最后一处出现的索引（从右到左搜索），如果没有匹配项，返回 -1 。
match 检查一个字符串匹配一个正则表达式内容，如果么有匹配返回 null。
substring 返回字符串的一个子串，传入参数是起始位置和结束位置。
substr 返回字符串的一个子串，传入参数是起始位置和长度
replace 用来查找匹配一个正则表达式的字符串，然后使用新字符串代替匹配的字符串。
search 执行一个正则表达式匹配查找。如果查找成功，返回字符串中匹配的索引值。否则返回 -1 。
slice 提取字符串的一部分，并返回一个新字符串（与 substring 相同）。
split 通过将字符串划分成子串，将一个字符串做成一个字符串数组。
length 返回字符串的长度，所谓字符串的长度是指其包含的字符的个数。
toLowerCase 将整个字符串转成小写字母。
toUpperCase 将整个字符串转成大写字母。

字符串连接操作非常消耗资源,解决方法是用 Array 对象存储字符串，然后用 join() 方法（参数是空字符串）创建最后的字符串

### **js里面的基础对象和基础数据类型**
JS基础数据类型:number数字(NaN)、string字符串、boolean布尔值、null、undefined
typeof 用来判断数据类型
显示/强制类型转换（ Number()、parseInt()、parseFloat() ）
基础对象：Document、Window、Navigator、Screen、History、Location

基础对象
JS Array、JS Boolean、JS Date、JS Math、JS Number、JS String、JS RegExp、JS Functions、JS Events
Browser 对象 Window、Navigator、Screen、History、Location

### **DOM年份，DOM好处和坏处，怎么禁用DOM**
Document Object Model (DOM)是HTML和XML文档的编程接口。
DOM标准主要要为：微软DOM与W3C DOM，一般IE实现的是微软DOM，而其它浏览器则不同程度的实际了W3C DOM
DOM Level Zero ,事实上从来不存在DOM 0版本，只是人们的戏称。只是在W3C DOM出现之前，不同浏览器（主要是IE与NN）实现的DOM相互排斥，1996年的浏览器大战所产生的DHTML就是所谓的DOM 0，它是脚本程序员的恶梦
DOM Level 1 包括DOM Core和DOM HTML。前者提供了基于XML的文档结构图。后者添加了一些HTML专用的对象和方法，从而扩展了DOM Core.目前IE在内的大部分桌面浏览器都通过不同方式实现了DOM 1
DOM Level 2 引入几个新模块：DOM视图，事件，样式，遍历和范围。IE只实现了一部分，火狐浏览器几乎全部实现，除IE之外的浏览器也实现了大部分
DOM Level 3 引入了以统一的方式载入和保存文档的方法。DOM Core被扩展支持所有的XML1.0的特性。火狐浏览器之类实现了少部分

好处：js调用dom的属性和方法就可以编程控制网页中的各种元素
坏处：DOM操作很耗性能

### **BOM浏览器信息**
BOM是Browser Object Model的缩写，简称浏览器对象模型
window对象、History对象、Location 对象、Navigator对象

### **http的几种状态**

主要的就是4种大情况：200+（Success）表示 响应成功的HTTP状态码；
+ 300+ (Redirction)表示需进行重定向的HTTP状态码；
+ 400+(Client Error)表示客户端发生的消息中存在错误的HTTP状态码；
+ 500+(Server Error)表示服务器出错的HTTP状态码。

+ 301，302 都是HTTP状态的编码，都代表着某个URL发生了转移，不同之处在于：
    301 代表永久性转移(Permanently Moved)
    302 代表暂时性转移(Temporarily Moved )
    304 客户的缓存资源是最新的， 要客户端使用缓存

+ 400告诉客户端，它发送了一个错误的请求
401	需要客户端对自己认证
403	请求被服务器拒绝了
404	未找到资源

+ 500 服务器遇到一个错误，使其无法为请求提供服务
501	客户端发起的请求超出服务器的能力范围(比如，使用了服务器不支持的请求方法)时，使用此状态码。
502	代理使用的服务器遇到了上游的无效响应
503	服务器目前无法为请求提供服务，但过一段时间就可以恢复服务
504	与状态吗408类似， 但是响应来自网关或代理，此网关或代理在等待另一台服务器的响应时出现了超时
505	服务器收到的请求使用了它不支持的HTTP协议版本。

+ 200 标示没有任何问题发生
    如果我们把一个地址采用301跳转方式跳转的话，搜索引擎会把老地址的PageRank等信息带到新地址，同时在搜索引擎索引库中彻底废弃掉原先的老地址。

### **canvas程序**
```
canvas = document.querySelector('canvas');
ctx = canvas.getContext('2d');
getContext（返回一个对象）
```

### **XMLHttpRequest**
``Xmlhttprequest``是ajax中的一个最为重要的对象，可以说没有xmlhttprequst的支持就没有ajax技术
```
xmlRequest = new XMLHttpRequest(); //IE7 & Mozilla
xmlRequest = new ActiveXObject("Microsoft.XMLHTTP"); //IE6,IE5
```

``xmlhttprequest`` 具有六个常用的方法,分别是:

(1)abort---------停止当前的请求.

(2)getAllResponseHeader-----------把当前的所有HTTP请求的响应头部作为键值对返回.

(3)getResponseHeader(“header”)----------返回指定的首部串值.

(4)open(“method”,”url”,”Boolean”,”username”,”password”)------建立对服务器的请求,其中method方法为get,put,post等.

(5)send(content)-------------------------具休向服务器提出请求.

(6)setRequestHeader(“header”,”value”)-----------为指定的首部设置值,注在设置之前,必须先调用OPEN()方法.

``xmlhttprequest``还提供了六个常用的属性.

(1)onreadystatechange--------------------当状态改变时就调用由此指定的函数.

(2)readystate----------------------------获得当前状态.通常有5个可取值(0-4)对我们真真正用用的就是4代表完成.
.
(3)responseText--------------------------通常由服务器返回一个字符串.

(4)responseXML---------------------------表示返回一个XML对象.

(5)status--------------------------------返回服务器状态.(200代表OK,404代表没有找到)

(6)statuse-------------------------------http状态码的相应文本.(ok或未找到).

``readystate``

0 － （未初始化）还没有调用send()方法

1 － （载入）已调用send()方法，正在发送请求

2 － （载入完成）send()方法执行完成，已经接收到全部响应内容

3 － （交互）正在解析响应内容

4 － （完成）响应内容解析完成，可以在客户端调用了

### **Ajax过程**
```
var xmlHttp;
function createXMLHttpRequest(){
    if (window.ActiveXObject) {
        xmlHttp = new ActiveXObject("Microsoft.XMLHTTP");
    }
    else
        if (window.XMLHttpRequest) {
            xmlHttp = new XMLHttpRequest();
        }
}

function startRequest(){
    createXMLHttpRequest();//第一步: 创建异步调用对象
    xmlHttp.onreadystatechange = handleStateChange;//第二步: 将对象状态与事件相关联
    xmlHttp.open("GET", "simpleResponse.txt", true);///第三步: 加载数据所在的服务器页
    xmlHttp.send(null);//第三步: 发送请求
}

function handleStateChange(){
    if (xmlHttp.readyState == 4) {
        if (xmlHttp.status == 200) {
            document.getElementById("test").innerHTML = xmlHttp.responseText;//返回simpleRespose.txt中的内容
        }
    }
}
```

### **如何解决跨域问题**
1、使用 window.name 解决跨域问题
window.name 的美妙之处：name 值在不同的页面（甚至不同域名）加载后依旧存在，并且可以支持非常长的 name 值（2MB）

为了让 Web 服务器实现 window.name，服务器应该只寻找请求中是否包含 windowname 参数。如果包含了 windowname参数，服务器应该返回一个设置了 window.name 字符串值的 HTML 文档，回应此请求并传送到客户端。

2、服务器代理
在你的web服务器上安装一个代理.你可以通过调用自己的web服务代理来代替直接调用web服务的XMLHttpRequest对请求.然后代理传递请求到web服务,并且返回客户端应用程序所需要的数据

3、JSONP解决跨域请求问题。
主要是利用了 <script/> 标签对 javascript 文档的动态解析来实现。

### **正则**

两种声明方式
```
var reg1 = /'\w+'/g;
var reg2 = new RegExp('\'\\w+\'','g');
```

``/d`` 任意一个数字，0~9 中的任意一个

``/w`` 任意一个字母或数字或下划线，也就是 A~Z,a~z,0~9,_ 中任意一个

``/s`` 包括空格、制表符、换页符等空白字符的其中任意一个

``.`` 小数点可以匹配除了换行符（/n）以外的任意一个字符

``[ab5@]`` 匹配 "a" 或 "b" 或 "5" 或 "@"

``[^abc]`` 匹配 "a","b","c" 之外的任意一个字符

``[f-k]`` 匹配 "f"~"k" 之间的任意一个字母

``[^A-F0-3]`` 匹配 "A"~"F","0"~"3" 之外的任意一个字符

``{n}`` 表达式重复n次，比如："/w{2}" 相当于 "/w/w"；"a{5}" 相当于 "aaaaa"

``{m,n}`` 表达式至少重复m次，最多重复n次，比如："ba{1,3}"可以匹配 "ba"或"baa"或"baaa"

``{m,}`` 表达式至少重复m次，比如："/w/d{2,}"可以匹配 "a12","_456","M12344"...

``?`` 匹配表达式0次或者1次，相当于 {0,1}，比如："a[cd]?"可以匹配 "a","ac","ad"

``+`` 表达式至少出现1次，相当于 {1,}，比如："a+b"可以匹配 "ab","aab","aaab"...

``*`` 表达式不出现或出现任意次，相当于 {0,}，比如："/^*b"可以匹配 "b","^^^b"...

``^`` 以字符串开始的地方匹配，不匹配任何字符

``$`` 以字符串结束的地方匹配，不匹配任何字符

``/b`` 匹配一个单词边界，也就是单词和空格之间的位置，不匹配任何字符


### **JS原型链**
原型链就是把原型连接在一起组成的链，那么为什么要把原型连接在一起呢？这就是继承啦，当你new一个对象，然后把另一个对象赋值给他的原型对象
```
function Person(){};
function Niko(){};
Niko.prototype = new Person();
```
这样，Niko就具有了Person的所有属性和方法，

### **Jsonp接口的原理**
+ JSONP的优点是：它不像XMLHttpRequest对象实现的Ajax请求那样受到同源策略的限制；它的兼容性更好，在更加古老的浏览器中都可以运行，不需要XMLHttpRequest或ActiveX的支持；并且在请求完毕后可以通过调用callback的方式回传结果。

+ JSONP的缺点则是：它只支持GET请求而不支持POST等其它类型的HTTP请求；它只支持跨域HTTP请求这种情况，不能解决不同域的两个页面之间如何进行JavaScript调用的问题。

### **js模板引擎**
模板引擎是为了使用户界面与业务数据（内容）分离而产生的，它可以生成特定格式的文档，用于网站的模板引擎就会生成一个标准的HTML文档。

js模板引擎包括如下：

``template``

官方参考：http://aui.github.io/artTemplate

``BaiduTemplate``

官方参考：http://baidufe.github.io/BaiduTemplate

``juicer``

官方参考：http://juicer.name

``doT``

官方参考：http://olado.github.io/doT

``kissy``

官方参考：http://docs.kissyui.com和https://github.com/kissyteam/kissy

``mustache``

官方参考：https://github.com/janl/mustache.js

### **对象**
如何判断一个对象是方法


**JS的加载**
不能并行下载和解析（阻塞下载）
当 引用了JS的时候，浏览器发送1个jsrequest就会一直等待该request的返回。因为浏览器需要1个稳定的DOM树结构，而JS中很有可能有代 码直接改变了DOM树结构，比如使用 document.write 或 appendChild,甚至是直接使用的location.href进行跳转，浏览器为了防止出现JS修改DOM树，需要重新构建DOM树的情况，所以就会阻塞其他的下载和呈现。

###**冒泡与捕获**
它们的定义，它们的区别，如何阻止冒泡
**捕获型事件**

+ 当你使用捕获型事件时
```

               | |
---------------| |-----------------
| element1     | |                |
|   -----------| |-----------     |
|   |element2  \ /          |     |
|   -------------------------     |
|        Event CAPTURING          |
-----------------------------------
```
：元素1的事件处理函数首先被触发，元素2的事件处理函数最后被触发

**冒泡型事件**

+ 当你使用冒泡型事件时
```

               / \
---------------| |-----------------
| element1     | |                |
|   -----------| |-----------     |
|   |element2  | |          |     |
|   -------------------------     |
|        Event BUBBLING           |
-----------------------------------
```
元素2 的处理函数首先被触发，元素1其次
JavaScript所有事件的两个阶段：捕获和冒泡
事实上，捕获阶段是一个和冒泡阶段完全相反的过程，即事件由祖先元素向子元素传播，和一个石子儿从水面向水底下沉一样，要说明的是在IE，opera浏览器中，是不存在这个阶段的。从各浏览器提供的注册事件监听的方法中可见一斑，例如适用于ie,opera的attachEvent，有两个参数，attachEvent(”on”+type,fn)，而适用于所谓标准浏览器的addEventListener则有三个参数，addEventListener(type,fn,boolean)，前面两个参数不用解释，第三个参数boolean，就是决定注册事件发生在捕获阶段还是冒泡阶段，具体参考如下：

+ true : 捕获阶段
+ false : 冒泡阶段

事件的传播是可以阻止的：

- 在W3c中，使用stopPropagation（）方法
- 在IE下设置cancelBubble = true；
不是所有的事件都能冒泡，例如：blur、focus、load、unload

阻止事件的默认行为，例如click <a>后的跳转~
+ 在W3c中，使用preventDefault（）方法；
+ 在IE下设置window.event.returnValue = false;

### **闭包**

了解什么是闭包、如何使用闭包、闭包的原理、闭包的真正原理

+ 定义
>闭包是有权访问另一个函数作用域中的变量的函数

+ 作用域链
>作用域链就是函数在定义的时候创建的,用于寻找使用到的变量的值的一个索引,而他内部的规则是,把函数自身的本地变量放在最前面,把自身的父级函数中的变量放在其次,把再高一级函数中的变量放在更后面,以此类推直至全局对象为止。

+ 内存回收机制
>如果这个函数内部又嵌套了另一个函数,而这个函数是有可能在外部被调用到的.并且这个内部函数又使用了外部函数的某些变量的话.这种内存回收机制就会出现问题.

闭包作用：一个是可以读取函数内部的变量，另一个就是让这些变量的值始终保持在内存中。

### **事件绑定**

**为什么用bind来进行事件绑定，live方法的实现原理**
Jquery中绑定事件有三种方法：以click事件为例

   （1）target.click(function(){});

   （2）target.bind("click",function(){});

   （3）target.live("click",function(){});

第一种方法很好理解，其实就和普通JS的用法差不多，只是少了一个on而已

第二、三种方法都是绑定事件，但是二者又有很大的不同，下面着重讲解一下，因为这个如果用到Jquery的框架的话是用的挺多的，尤其要注意二者的区别。

【bind和live的区别】
>live方法其实是bind方法的变种，其基本功能就同bind方法的功能是一样的，都是为一个元素绑定某个事件，但是bind方法只能给当前存在的元素绑定事件，对于事后采用JS等方式新生成的元素无效，而live方法则正好弥补了bind方法的这个缺陷，它可以对后生成的元素也可以绑定相应的事件。

live方法之所以能对后生成的元素也绑定相应的事件的原因归结在“事件委托”上面，所谓“事件委托”就是指绑定在祖先元素上的事件可以在其后代元素上进行使用。live方法的处理机制就是把事件绑定在DOM树的根节点上，而不是直接绑定在某个元素上。

由于只有在事件发生的时候，live方法才会去检测绑定事件的对象是否存在，所以live方法可以实现后来新增的元素也可实现事件的绑定。相比之下，bind会在事件在绑定阶段就会判断绑定事件的元素是否存在，而且只针对当前元素进行绑定，而不是绑定到父节点上。

那么为什么还要使用bind方法呢？bind和live主要的不同如下：

（1）bind方法可以绑定任何JavaScript的事件，而live方法在jQuery1.3的时候只支持click, dblclick, keydown, keypress,keyup,mousedown, mousemove, mouseout, mouseover, 和 mouseup.在jQuery 1.4.1中，甚至也支持 focus 和 blue事件了（映射到更合适，并且可以冒泡的focusin和focusout上）。另外，在jQuery 1.4.1中，也能支持hover（映射到"mouseenter mouseleave"）。

（2）live() 并不完全支持通过DOM遍历的方法找到的元素。取而代之的是，应当总是在一个选择器后面直接使用 .live()方法。

（3）当一个元素采用live方法进行事件的绑定的时候，如果想阻止事件的传递或冒泡，就要在函数中return false,仅仅调用stopPropagation()是无法实现阻止事件的传递或者冒泡的

### **mouseover和mouseenter的区别**

+ 不论鼠标指针穿过被选元素或其子元素，都会触发 mouseover 事件。对应mouseout
+ 只有在鼠标指针穿过被选元素时，才会触发 mouseenter 事件。对应mouseleave

### **JS获取鼠标坐标**

（1）相对于屏幕
```
function getMousePos(event) {
    var e = event || window.event;
    return {'x':e.screenX,'y':screenY}
}
```
（2）相对浏览器窗口
```
function getMousePos(event) {
    var e = event || window.event;
    return {'x':e.clientX,'y':clientY}
}
```
（3）相对文档
```
function getMousePos(event) {
    var e = event || window.event;
    var scrollX = document.documentElement.scrollLeft || document.body.scrollLeft;
    var scrollY = document.documentElement.scrollTop || document.body.scrollTop;
    var x = e.pageX || e.clientX + scrollX;
    var y = e.pageY || e.clientY + scrollY;
    //alert('x: ' + x + '\ny: ' + y);
    return { 'x': x, 'y': y };
}
//pageX for ff
//document.documentElement.scrollLeft for ie
//document.body.scrollLeft for chrome
```
### **ready方法的实现机制**

ready方法是在dom加载完后就可以做相应的操作
在jquery脚本加载的时候,会设置一个isReady的标记,监听DOMContentLoaded事件(这个不是什么浏览器都有的,不同浏览器,jquery运作方式不一样).当然遇到调用ready函数的时候,如果isReady未被设置,那就是说页面未加载完,就会把要执行的函数用一个数组缓存起来,当页面加载完后,再把缓存的函数一一执行
[参考详细](http://blog.csdn.net/lk188/article/details/4359346)

### **工具库**
extJS、YUI、Prototype：这些工具库或框架都有各自的特点

+ extJS

最新版本：Ext JS5

优点： 强大的UI，而且性能不错，这是其最大的优点。 速度快，不管是UI还是其它模块。 100%面向对象和组件化的思想，一致的语法，全局的命名空间。 文档的完整，规范，方便。 核心的开发团队，Jack Slocum等。 活跃的社区，迅速增加的用户量。 模块化实现，可扩展性强。 所有的组件（widgets）都可直接使用，而无需进行设置

缺点： 稍复杂。 为重量级的框架（包含大量UI），体积大。如果导入ext-all.js，压缩后也有近500k。

2.ExtJs的特点

(1)纯Html/CSS+JS技术,重新定义表示层的耦合；

(2)基于纯Html/CSS+JS技术，提供丰富的跨浏览器UI组件，灵活采用JSON/XML数据源开发，使得服务端表示层的负荷真正减轻，从而达到客户端的MVC应用；

(3)集成多种JS底层库， 满足开发者不同需求；

(4)Ext初期仅是对YUI的对话框扩展，后来逐渐有了自己的特色，深受网友的喜爱。发展至今，Ext除YUI外还支持Jquery Prototype等的JS库，让大家自由地选择；

(5)多浏览器支持、支持多平台下的主流浏览器。

3.ExtJs的优缺点

(1).ExtJs的优点

<1>.UI组件丰富，外观漂亮。

Ext JS库有着丰富且漂亮的UI组件，大大缩短了我们的开发周期，而且组件拥有漂亮的布局，经过简单的调用与配置就可以实现不错的界面布局。ExtJS提供的各种组件可以用更加标准的方式展示数据降低了开发难度。

<2>.浏览器兼容性好。

使用ExtJS对浏览器没有任何要求。可以说是一种绿色的富客户端实现方式，ExtJs基本可以运行于现在主流的浏览器。

<3>有很多动画效果做得很不错，提高了用户的感知度。

<4>和后台代码无关。

不管后台用什么语言开发的都不会受影响，不管你是用C#也好 JAVA也好 还是PHP都和它没关系。

<5>将Web程序向桌面系统转化。

ExtJS最大的优势在于它将Web应用程序的操作方式向传统桌面应用程序的操作方式进行转化甚至消除了这种差异，从根本上提高了用户的使用体验，这是ExtJS应用前景广阔的主要原因。

<6>.相对丰富的文档和示例。

毫无疑问，刚刚接触到ExtJS的人多数都是被它附带的例子和开发文档吸引过去的，它的文档做的确实不错。

(2) ExtJs的缺点

<1>.体积较大，速度稍慢。

由于使用了大量的UI组件，所以体积较大，导致页面加载速度比较慢。　

<2>.收费,好像不免费。

因为它太优秀了，所以从Ext JS 2.0以后的版本都是收费的。也许这一点不能算是它的缺点，但这确实阻碍了它的推广与应用。

<3>没有合适的开发利器。

毫无疑问，一个好的开发工具可以大大的提高编码的速度，但是对于ExtJS，始终没有一个完美的开发工具，可以推荐的有Aptana Studio， Spket IDE，和Spket 提供的提示文件，但是都是各有优缺点，都不完美，只能一边看SDK一边写代码。

<4>没有界面设计工具。

虽然有人提供了一个在线的界面设计工具，但是和Visual Studio提供的ASP.Net设计工具来说，真的可以说是天壤之别。因此，只能一边预览，一边写代码。

<5>文档不全。

虽然ExtJS提供的文档很丰富，但是还是跟不上源代码的更新速度，所以，经常要通过看源代码，调试才能真正解决问题。

<6>不能编译。

这一点可以说是JavaScript的缺点（如果能编译，就不叫JavaScript了），在实际的开发中，经常会敲错一些代码，比如大小写错误等，不能通过编译得到反馈，只能在运行时排错，导致开发的效率比较低下。

+ YUI
如果你想作门户、如果你想作SNS、如果你想作大型电子商务和电子政务网站，你大概只有一个选择，那就是Yui，Yui抽象出了比其他框架更复杂的层次结构、把模块按照不同的层次划分，并定义层次之间模块依赖关系，这种设计使得Yui对万行级代码的管理游刃有余，这种重设计轻开发的思想是Yui的核心之一，此外，Yui不仅仅是JS框架，他是JS＋CSS＋规范的集合，必要的约束在团队协作项目中可以降低成本。其实Yui本身也是团队合作的产物。在扩展性方面，我觉得Yui是所有前端框架作的最好的，Ext就是选择基于Yui进行扩展。相对来讲，ProtoType和jQuery显然太小了。

+ Prototype

优点：基本底层，易学易用，甚至是其他一些js特效开发包的底层，体积算是最小的了。

缺点：如果说缺点，可能就是功能是他的弱项

+ jQuery

有人说jQuery是被设计用来改变你写JavaScript的方法的。在这一方面jQuery的确作的很好，20行的Dom javascript语句在jQuery里只需要2－3行就可以完成，语言的简洁简直太吸引人了，尤其对于前端开发工程师这群多少有些代码洁癖的人来说，简直美妙绝伦，甚至忽视了其粗糙的面向对象的结构这一致命的缺点。当我们过多的沉浸在代码简洁的乐趣中无法自拔的时候，对更高级抽象的忽视往往阻挡住了我们的视野。因此，jQuery本身无法承担庞大的网站架构任务，也只能在中小网站中搞一搞动画特效而已。但这仍然无法阻止wd们对jQuery的偏爱，只要你有洁癖，那么你一定会喜欢jQuery的。

+ MooTools

在面向对象的方面，MooTools的确作的不错，软件设计模式中的高内聚和低耦合在MooTools中有良好的体现。文档也很完整，但MooTools的占有率一直不高是一个很尴尬的现象，作底端太多余，无法和jQuery竞争，作高端又有点吃力，无法和Yui竞争，给人鸡肋的感觉，就这样。

+ fiddler工具

它能记录所有客户端和服务器的http和https请求，允许你监视，设置断点，甚至修改输入输出数据
原理：Fiddler 是以代理web服务器的形式工作的,它使用代理地址:127.0.0.1, 端口:8888. 当Fiddler会自动设置代理， 退出的时候它会自动注销代理，这样就不会影响别的程序。

+ BackboneJS

Backbone 为复杂Javascript应用程序提供模型(models)、集合(collections)、视图(views)的结构。其中模型用于绑定键值数据和自定义事件；集合附有可枚举函数的丰富API； 视图可以声明事件处理函数，并通过RESRful JSON接口连接到应用程序。
http://www.csser.com/tools/backbone/backbone.js.html

+ AngularJS

    AngularJS 是一款开源 JavaScript 函式库，由Google 维护，用来协助单一页面应用程式运行的。它的目标是透过MVC模式 (MVC) 功能增强基于浏览器的应用，使开发和测试变得更加容易。

    函式库读取包含附加自定义（标签属性）的HTML， 遵从这些自定义属性中的指令，并将页面中的输入或输出与由JavaScript变量表示的模型绑定起来。这些JavaScript变量的值可以手工设置，或者从静态或动态JSON资源中获取。

``优点``
    模板功能强大丰富，并且是声明式的，自带了丰富的Angular指令是一个比较完善的前端MV*框架，包含模板，数据双向绑定，路由，模块化，服务，依赖注入等所有功能
自定义Directive，比jQuery插件还灵活，但是需要深入了解Directive的一些特性，简单的封装容易，复杂一点官方没有提供详细的介绍文档，我们可以通过阅读源代码来找到某些我们需要的东西，如：在directive使用 $parse
ng模块化比较大胆的引入了Java的一些东西（依赖注入），能够很容易的写出可复用的代码，对于敏捷开发的团队来说非常有帮助，我们的项目从上线到目前，UI变化很大，在摸索中迭代产品，但是js的代码基本上很少改动
补充：Angular支持单元测试和e2e-testing

``缺点``

验证功能错误信息显示比较薄弱，需要写很多模板标签，没有JQuery Validate方便，所以我们自己封装了验证的错误信息提示，详细参考 why520crazy/w5c-validator-angular · GitHub
ngView只能有一个，不能嵌套多个视图，虽然有 angular-ui/ui-router · GitHub 解决，但是貌似ui-router 对于URL的控制不是很灵活，必须是嵌套式的（也许我没有深入了解或者新版本有改进）
对于特别复杂的应用场景，貌似性能有点问题，特别是在Windows下使用chrome浏览器，不知道是内存泄漏了还是什么其他问题，没有找到好的解决方案，奇怪的是在IE10下反而很快，对此还在观察中
这次从1.0.X升级到1.2.X，貌似有比较大的调整，没有完美兼容低版本，升级之后可能会导致一个兼容性的BUG，具体详细信息参考官方文档 AngularJS ，对应的中文版本：Angular 1.0到1.2 迁移指南
ng提倡在控制器里面不要有操作DOM的代码，对于一些JQuery 插件的使用，如果想不破坏代码的整洁性，需要写一些directive去封装一下JQ插件，但是现在有很多插件的版本已经支持Angular了，如：jQuery File Upload Demo

Angular 太笨重了，没有让用户选择一个轻量级的版本，当然1.2.X后，Angular也在做一些更改，比如把route，animate等模块独立出去，让用户自己去选择

+ Seajs

SeaJS是由支付宝前端高级技术专家王保平（玉伯）开发的一个遵循CMD规范的模块加载框架，可用来轻松愉悦地加载任意JavaScript模块和CSS模块。 SeaJS非常小巧，小巧在于其压缩后体积只有4KB，而且接口和方法也非常少。SeaJS有两个核心：模块的定义和模块的加载。SeaJS可以加载任意 JavaScript模块和CSS模块，能保证你在使用一个模块时，已将所依赖的其他模块载入脚本运行环境中。SeaJS可以让你享受写代码的乐趣，不用 去管那些加载的问题。毕竟现在网页的可维护性和性能问题一样严峻，体现在：文件太多，不利于维护，前端后端都一样；HTTP请求过多，当然这个可以通过合 并解决，但如果没有后端直接合并，那么人工成本会非常大。用SeaJS就能非常好地解决这些问题。SeaJS遵循CMD规范，因此可以很方便地书写模块。 目前已经有越来越多的人采用CMD规范来开发项目了。

`官网`：http://seajs.org/docs/

+ CommonJS 

CommonJS API定义很多普通应用程序（主要指非浏览器的应用）使用的API，从而填补了这个空白。它的终极目标是提供一个类似Python，Ruby和Java标准库。这样的话，开发者可以使用CommonJS API编写应用程序，然后这些应用可以运行在不同的JavaScript解释器和不同的主机环境中。在兼容CommonJS的系统中，你可以实用JavaScript程序开发：

服务器端JavaScript应用程序
命令行工具
图形界面应用程序
混合应用程序（如，Titanium或Adobe AIR）

---

### **jq源码分析**

最新版本：jquery 1.11.1(1.x) jquery2.1.1(2.x)

>2.x版本不支持IE的6、7、8.性能上有所提高

自由的HTML解析、增强的模块性、修复IE9 焦点死亡问题、修复Cordova

官网：http://jquery.com/

+ jQuery的无new构建
jQuery没有使用new运行符将jQuery显示的实例化，还是直接调用其函数
```
$().ready()
$().noConflict()
```
那么如何返回一个正确的实例？
可以把jQuery类当作一个工厂方法来创建实例，把这个方法放到jQuery.prototye原型中
```
var aQuery = function(selector, context) {
       return  aQuery.prototype.init();
}
aQuery.prototype = {
    init:function(){
        return this;
    }
    name:function(){},
    age:function(){}
}
```
+ 链式调用
通过简单扩展原型方法并通过return this的形式来实现跨浏览器的链式调用。
```
aQuery().init().name()

aQuery.prototype = {
    init: function() {
        return this;
    },
    name: function() {
        return this
    }
}
```
>Javascript是无阻塞语言，所以他不是没阻塞，而是不能阻塞，所以他需要通过事件来驱动，异步来完成一些本需要阻塞进程的操作，这样处理只是同步链式，异步链式jquery从1.5开始就引入了Promise

+ 插件接口
jQuery支持自己扩展属性，这个对外提供了一个接口，jQuery.fn.extend()来对对象增加方法
从jQuery的源码中可以看到，jQuery.extend和jQuery.fn.extend其实是同指向同一方法的不同引用
>jQuery.extend 对jQuery本身的属性和方法进行了扩展
jQuery.fn.extend 对jQuery.fn的属性和方法进行了扩展

**总结：**
通过new jQuery.fn.init() 构建一个新的对象，拥有init构造器的prototype原型对象的方法

通过改变prorotype指针的指向，让这个新的对象也指向了jQuery类的原型prototype

所以这样构建出来的对象就继续了jQuery.fn原型定义的所有方法了

---

### **lazyloader**

1、获取需要做按需加载的图片在页面的位置

``getClientRects``常用于获取鼠标的位置

``getBoundingClientRect``获取元素位置

2、预加载的位置为：上下一屏的图片

---

### **Mask，Flexible Box**

了解Mask，甚至能够知道Flexible Box的使用方法和原理

``Flexible Box`` 弹性布局

---

### **viewport 的参数和作用**

viewport用来把渲染限制在屏幕的一部分

参数：
```
height = [pixel_value | device-height] //控制 viewport 的高度
width = [pixel_value | device-width ] //控制 viewport 的大小
initial-scale = float_value //初始缩放比例，也即是当页面第一次 load 的时候缩放比例
minimum-scale = float_value //允许用户缩放到的最小比例
maximum-scale = float_value //允许用户缩放到的最大比例
user-scalable = [yes | no] //用户是否可以手动缩放
target-densitydpi = [dpi_value | device-dpi | high-dpi | medium-dpi | low-dpi]

//telephone & email
<meta name="format-detection" content="telphone=no, email=no" />

//是否启动webapp功能，会删除默认的苹果工具栏和菜单栏。
<meta name="apple-mobile-web-app-capable" content="yes" />

//当启动webapp功能时，显示手机信号、时间、电池的顶部导航栏的颜色。默认值为default（白色），可以定为black（黑色）和black-translucent（灰色半透明）
<meta name="apple-mobile-web-app-status-bar-style" content="black" />

<!-- 启用360浏览器的极速模式(webkit) -->
<meta name="renderer" content="webkit">
<!-- 避免IE使用兼容模式 -->
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<!-- 针对手持设备优化，主要是针对一些老的不识别viewport的浏览器，比如黑莓 -->
<meta name="HandheldFriendly" content="true">
<!-- 微软的老式浏览器 -->
<meta name="MobileOptimized" content="320">
<!-- uc强制竖屏 -->
<meta name="screen-orientation" content="portrait">
<!-- QQ强制竖屏 -->
<meta name="x5-orientation" content="portrait">
<!-- UC强制全屏 -->
<meta name="full-screen" content="yes">
<!-- QQ强制全屏 -->
<meta name="x5-fullscreen" content="true">
<!-- UC应用模式 -->
<meta name="browsermode" content="application">
<!-- QQ应用模式 -->
<meta name="x5-page-mode" content="app">
<!-- windows phone 点击无高光 -->
<meta name="msapplication-tap-highlight" content="no">
```

---

### **cookie(值不能为中文，要经过编码处理)**

大多数浏览器规定Cookie大小不超过4K，每个站点能保存的Cookie不超过20个，所有站点保存的Cookie总和不超过300个
当没有指明cookie时间时，所创建的cookie有效期默认到用户浏览器关闭止，故被称为会话cookie
document.cookie="userId=828; userName=hulk";

---

### **Dir**

### **Express**

### **Fork**

### **Grunt**

### **Haslayout**

### **kissy**

### **Media query**

### **Npm**

### **Opacity**

### **Querystring**

### **Referer**

### **Trim**

### **Underscore**

### **Vim**

### **Worker**

### **Xss**

### **Yslow**

页面性能检测工具

### **Zepto**

最新版本： 1.1.4

官网：http://zeptojs.com/

jq的移动版本，去掉了老版本浏览器的兼容支持

``zepto = {};``

这个变量贯穿始终，也是zepto与jQuery很不一样的地方，jQuery是一个类，会创建一个个实例，而zepto本身就只是一个对象......

### **Sizzler**

官网：http://sizzlejs.com/

jQuery的御用选择器，可独立使用

### **网速性能优化的方法(雅虎35条优化建议)**

规范代码，提高js的性能（正确理解 Repaint 和 Reflow、减少对DOM的操作），对js和css进行压缩处理；

高效使用HTML标签和CSS样式；

请减少HTTP请求；

压缩图片和使用图片Sprite技术;

使用JSON格式来进行数据交换；

使用CDN加速（内容分发网络）

动态删除节点，在浏览器内只保存两到三屏的节点，这样可以大大减轻浏览器压力

### **描述一下渐进增强和优雅降级之间的不同**
两者区别的关键在于它们各自关注的焦点，以及这种关注对工作流程的影响。

**优雅降级的视角**

优雅降级关注于在最先进/最全能的浏览器上构建网站。在被认为`老的`或能力不足的浏览器中的测试，经常要等到开发周期的最后一个环节才进行，并且通常限制在主流浏览器（如IE、Mozzila等）的前一个发布版本中。

在这种模式下，老的浏览器只可能提供差强人意（poor, but passable）的体验。或许会做些小补丁来适应某个特定浏览器，但这些浏览器毕竟不是关注的焦点，除了修正重大的错误，也不会再费多大的神了。

**渐进增强的视角**

渐进增强关注于内容。请注意区别：我甚至都没提及浏览器。

内容是我们最初创建网站的原因。有些网站传播内容，有些收集内容，有些请求内容，有些操作内容，有些网站以上所有功能都有，然而而他们都需要内容。这就是渐进增加成为一种更适合的模式的关键所在。这也是Yahoo!迅速采纳这种模式并用它创建了分级浏览器支持（Graded Browser Support）策略的原因。

### **览器并发请求数**

1. IE6和IE7————————2

2. IE8—————————— 6

3. Opera—————————8

4. Firefox———————— 6

5. Chrome————————6

6. Safari—————————6

通常的优化网站加载速度的方法是采用多个域名增加浏 览器对同一网页的请求并发连接数。

静态资源多域名的另外一个原因是，通过不同的域名携带不同的cookie。


### **LocalStorage兼容**
根据浏览器自动选择使用 localStorage、globalStorage 或者 userData 来实现本地存储功能

https://github.com/marcuswestin/store.js/blob/master/store.js


### **setTimeout的时间定义为0有什么用**
JavaScript 引擎是单线程处理任务的。它把任务放到队列中，不会同步去执行，必须在完成一个任务后才开始另外一个任务。

由于setTimeout可以把任务从某个队列中跳脱成为新队列，因而能够得到期望的结果

### **如何无刷新图片上传并且兼容**
1、用iframe上传
在页面动态创建 form 表单和 ifram ，设定 form 表单提交的目标为 ifram ，将文件域和要 post 的参数动态写入 form 表单中，然后提交 from 表单

2、借助于flash，例如swfupload.js

### **前端自动化工具的区别**
比如百度的fix工具和grunt工具

Grunt 是一个基于 task 的构建工具，依赖众多的插件进行配置组织，可以解决基本的前端自动化问题。FIS 是基于工具、开发框架、本地开发环境为一体的前端解决方案，不但拥有各类工具插件，同时还针对 PC、Mobile、I18n 等业务、场景总结了很多最佳实践。

Grunt的缺点

1、相对的低效：grunt各插件之间尽可能地保持独立，于是频繁的文件读写有时候就成了无奈的选择

2、缺乏有效的串联：插件A、插件B之间彼此独立，有的时候需要将插件A的输出，作为插件B的输入（如将sass编译后再内联到html里），有的时候就不得不使用临时目录来曲折地实现这个目的

接触fis是在grunt之后，有两点比较吸引的，当然就是相对于grunt来说：

1、更加高效：管道操作，避免了频繁的文件IO

2、更加灵活的配置：强大到令人发指的部署配置（当然也让人晕晕的，glob、正则混搭的规则～）

### **PNG8和PNG24有什么不同**

PNG8不支持半透明、PNG24支持半透明
