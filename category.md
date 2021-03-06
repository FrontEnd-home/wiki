#分类列表

###category

暂时以此列表分类（前为路径名path，后为显示名称name，每个分类及tag是要有一个描述的）

```js
- html                  //HTML
    - html5             //HTML5
        - canvas        //Canvas
        - svg           //SVG
        - webworker     //WebWorker [alias: worker]
        - blob          //Blob
- css                   //CSS
    - css3              //CSS3
    - sass              //Sass
    - less              //Less
- javascript            //JavaScript [alias: js]
- markdown              //Markdown
- framework             //框架
    - nodejs            //Node.js
        - express       //Express
        - socketio      //Socket.IO
        - phantomjs     //PhantomJS
    - backbone          //Backbane.js
    - angular           //Angular.js
    - extjs             //ExtJS
- lib                   //类库
    - jquery            //jQuery
    - underscore        //Underscore.js
    - zepto             //Zepto.js
    - modernizr         //Modernizr
- devtools              //开发工具
    - requirejs         //RequireJS   (tags: 加载器)
    - seajs             //SeaJS       (tags: 加载器)
    - git               //Git
    - svn               //SVN
    - jsdoc             //jsDoc
    - jslint            //JSLint
    - jshint            //JSHint
    - bower             //Bower
    - grunt             //Grunt
    - gulp              //Gulp
- editor                //编辑器
    - sublime           //Sublime
- debug                 //调试工具
    - fiddle            //Fiddler
    - firebug           //Firebug
- analyzer              //性能分析
    - yslow             //YSlow
    - httpwatch         //HttpWatch
    - dynatrace         //dynaTrace Ajax
- testing               //测试工具
    - karam             //Karma
    - mocha             //Mocha
    - chai              //Chai
- books                 //书籍
- wheel                 //造好的轮子
- resources             //资源整理
- other                 //其他
- *specification        //业内标准
- *open                 //开放服务
```

## 构建多种分类方式

实际用途中，分类是个不定的元素，所以不能够通过一种形式的划分就达到优良分类的目的，分类存在多种分类方式

比如可以按照编程语言分类，当然这种分类并不会覆盖所有的类目，也可以按知识点分类，各种分类各有优势，但都要有个子类，划分文章时，划分的是子类，而不是父类，然后通过隶属关系，进行分类聚合

如此就可以推荐某种形式的聚合来展示分类，随时可以优化展示，而新增文字只是提交到子分类里，而不是聚合里

这个作为后续方案展开实施

举例：

### 1、按编程/语言聚合，如下分类：

```js
HTML            3C 17P
CSS
JavaScript      3C 8P
    各种框架
        Backbane.js
        Angular.js
        ExtJS
    各种库
        jQuery
        Underscore.js
        Zepto.js
    其他...
PHP
Python
Go
C/C++
Ruby
```
实际应该有更多的按编程语言的子聚合，各种语言下的框架/类的聚合，工具的类型集合，还有比如算法，机器学习等很多的聚合

下一期的分类调整，理论上只做子类的分类，其他都作为聚合（新增文章可以自动补全提醒分类），但考虑到JavaScript可以作为子类也可以作为聚合，这个问题还需要继续探究下，子类与聚合如何共存以及划分各自的职能

