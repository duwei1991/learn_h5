
# html5介绍及学习
### 一、HTML5现状介绍
#### 1.1 url
![](http://pic002.cnblogs.com/images/2011/134090/2011110911172557.png)
##### url是互联网的门牌号，互联网资源通过url进行访问，图上protocol常见的有http、https、ftp等等，port默认为80，所以很少见到80端口
#### 1.2 http 请求
#####在客户机和服务器之间进行请求-响应时，两种最常被用到的方法是：GET 和 POST。
* GET - 从指定的资源请求数据。
* POST - 向指定的资源提交要被处理的数据
* POST raw方式使用的是纯字符串的数据上传方式，所以在POST之前，可能需要手工的把一些JSON格式的数据转换成字符串的(加两单引号)
* POST form-data的方式就是key-value的提交，数据其实是分割的
#### HTML、CSS、JAVASCRIPT
##### HTML
* 当前并存的HTML版本是HTML4和HTML5,HTML4主要是为了兼容IE9以下浏览器，HTML5包含有新的标签和特性
##### CSS
* 当前并存的CSS版本是CSS2和CSS3,其中CSS2因为浏览器的历史发展原因，不同浏览器实现相同的样式需要不同的语法，IE9以下浏览器样式兼容是一个比较头痛的事情，所以一般会采用一些样式框架来处理兼容问题，比如bootstrap的2.x版本
* `http://v2.bootcss.com/`
* CSS2对动画支持不是很好，所以之前很多动画都是由javascript来实现，而在CSS3中，原生的CSS动画比javascript实现的动画更加流畅，所以现在移动端动画更多的是采用CSS3的方案，有一个CSS3动画库可以参考
*    `https://daneden.github.io/animate.css/`
##### JAVASCRIPT
* javascript 是 ECMAScript（后简称ES)的具体实现，当前所有浏览器基本都兼容ES4的语法规则，现代浏览器和移动端浏览器基本都支持ES5的语法，而最新的ES6语法规则已经推出，但是浏览器并非完全支持，所以出现了`babel`这种将ES6语法的代码编译成ES5语法代码的工具出现
* ES4时代，基本是jQuery一统天下，因为不同浏览器的语法各异，没有特别标准的规范，jQuery的出现，大大降低了开发人员的开发难度，后面ES5和ES6的一些语法规则，也是参考了jQuery的语法，而jQuery也不是止步不前，jQuery在版本规划上，1.x是兼容所有浏览器的版本，2.x是只兼容ES5语法的版本，所以在选择jQuery的时候，也需要区分使用场景
* ES5时代，随着前端逻辑越来越复杂，jQuery的手工操作DOM方式越来越低效且容易出错，包括谷歌、Facebook等大型互联网公司都推出了自己的新一代JS框架，比如谷歌的angularjs和Facebook的reactjs，他们的核心思想都是数据与UI的自动绑定，无需手工操作DOM，angularjs和reactjs都可以理解为骨架，基于这两款js框架，发展出了ionic和ant.design这两款前端整体解决方案，由于react的入门及使用成本相对较高，适合大型互联网公司使用，所以我们以后会把精力放在基于angular1.x的js体系
* `http://ionicframework.com`
* `http://ant.design`
* ES6时代，由于当前浏览器还不能完全支持ES6语法，所以出现了TypeScript这种需要编译的语言，和babel这种编译工具，都是为了帮助前端能够实现复杂项目的模块管理,而前端编译大多依赖于nodejs
* `http://www.typescriptlang.org/`
* `http://babeljs.io/`
* `https://nodejs.org/en/`

#### 浏览器
##### PC端浏览器
* PC端浏览器，特别是企业用户，仍然大量在使用IE老版本浏览器，其他现代浏览器主要包含Chrome、Firefox、Safira、Opera等，类似360浏览器等国产浏览器一般都是基于Chrome内核
* 一般需要兼容HTML4、CSS2
##### 移动端浏览器
* 移动端浏览器主要包含iOS的Safira浏览器、安卓的Chrome浏览器，以及腾讯的微信、QQ等内置浏览器
* 一般只需要兼容HTML5、CSS3

### 二、HTML5技术栈

### 三、JS专题

### 四、CSS专题

### 五、NODE.JS专题

### 六、hybird app  
- 6.1 微信小程序
- 6.2 ionic
