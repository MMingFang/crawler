# crawler

初步系统学习python爬虫crawler

Task01：html等有关知识，api使用，request-get使用 拔高部分：js

网页是由 HTML 、 CSS 、JavaScript 组成的。
HTML 是用来搭建整个网页的骨架，而 CSS 是为了让整个页面更好看，包括我们看到的颜色，每个模块的大小、位置等都是由 CSS 来控制的， JavaScript 是用来让整个网页“动起来”，这个动起来有两层意思，一层是网页的数据动态交互，还有一层是真正的动，比如我们都见过一些网页上的动画，一般都是由 JavaScript 配合 CSS 来完成的。
在选项 Elements 中可以看到网页的源代码，这里展示的就是 HTML 代码。

Elements：允许用户从浏览器的角度来观察网页，用户可以借此看到Chrome渲染页面所需要的HTML、CSS和DOM（Document Object Model）对象。
Network：可以看到网页向服务气请求了哪些资源、资源的大小以及加载资源的相关信息。此外，还可以查看HTTP的请求头、返回内容等。
Source：即源代码面板，主要用来调试JavaScript。
Console：即控制台面板，可以显示各种警告与错误信息。在开发期间，可以使用控制台面板记录诊断信息，或者使用它作为shell在页面上与JavaScript交互。
Performance：使用这个模块可以记录和查看网站生命周期内发生的各种事情来提高页面运行时的性能。
Memory：这个面板可以提供比Performance更多的信息，比如跟踪内存泄漏。
Application：检查加载的所有资源。
Security：即安全面板，可以用来处理证书问题等。

api（Application Programming Iterface）的用处：API为开发者提供了方便友好的接口，不同的开发者用不同的语言都能获取相同的数据。

不同于PHP或者ASP.NET，JavaScript不是为“网站服务器”提供的语言，而是为“用户浏览器”提供的语言。


JavaScript语言的特点
动态语言

动态语言是指程序在运行时可以改变其结构：新的函数可以被引进，已有的函数可以被删除等在结构上的变化。JavaScript便是一个动态语言。除此之外如Ruby、Python等也都属于动态语言，而C、C++等语言则不属于动态语言。比如在JavaScript中可以在对象定义之后动态的为其添加属性和方法

脚本语言

脚本语言是为了缩短传统的编写-编译-链接-运行（edit-compile-link-run）过程而创建的计算机编程语言，只在被调用时进行解释或编译，然后执行。它的命名起源于一个脚本“screenplay”，每次运行都会使对话框逐字重复。早期的脚本语言经常被称为批量处理语言或工作控制语言。

弱类型

弱/强类型指的是语言类型系统的类型检查的严格程度，弱类型的语言在声明变量的时候不必进行变量类型的确定，语言的运行时会隐式做数据类型转换，对于弱类型语言来说，不同类型的变量可以进行直接运算，而强类型的则不可以。

JavaScript的基本语法
JavaScript的执行顺序：按照HTML文件中出现的顺序依次执行
大小写敏感：JavaScript严格区分大小写
忽略空白符和换行符
语句分隔符：使用；结束语句，可以把多个语句写在一行，最后一个语句的分号可以省略，但尽量不要省略。可以使用{}括成一个语句组，形成一个block
通过\对代码进行折行操作：document.write(‘hello\world’);
//单行注释  多行注释/注释内容/
JavaScript中的保留字：abstract，else，instanceof，super，boolean，enum，int，switch，break，export，interface，synchronized，byte，extends，let，this，case，false，long，throw，catch，final，native，throws，char，finally，new，transient，class，float，null，true，const，for，package，try，continue，function，private，typeof，debugger，goto，protected，var，defaut，if，public，void，delete，inplements，return，volatile，do，import，short，while，doble，in，static，width
通过document.write()向文档书写内容
通过console.log()向控制台写入内容
语法错误：通过控制台进行调试
逻辑错误：通过alert() 进行调试
