Markdown学习笔记
=====================

Markdown是什么我就不说明了，希望了解的同学请[Google](http://www.google.com.hk) 或者访问[Markdown官方网站](http://http://daringfireball.net/projects/markdown/)

Markdown基本可以分为 *Block Elements* 和 *Span Elements*

Block Elements
-----------------
###段落
在markdown里面的源文件，随便一行就是一个段落，每个回车markdown会自动转换成`<br/>`

###Headers
headers分为setext方式和atx方式
首先说*setext*方式，就是在文字下面另起一行，然后用=或者-，在下面划上一排就出现了哦~
atx方式是在行首用#，用几个#就表示几级标题

###引用Blackquotes
这个在国内的HTML里面其实没怎么出现，因为中国人不喜欢表示自己是引用的？反正论文也是这样^_^
就是用>打头啦

###列表
####无序列表
用*,+,-都可以表示列表，只需要用其中一个符号+一个空格，然后后面跟上列表文字就可以了
####有序列表
有序列表需要用数字序列和英文句号来表示，如：
1. First
2. Second
3. Third

###代码块
代码用``包裹起代码片段就可以，**&<>**这些符号Markdown会自动转义为相应的HTML
对于多行代码，并且自己调整缩进的那么需要在代码前用1个tab或者4个空格起头

###水平分割线
三个以上*,-,_就是水平分割线了

Span Elements
---------------
###链接
Markdown的链接分为2中类型，inline-style和reference-style。突然响起Gangnam Style~
inline-style就像这样 \[example site\]\(http://www.example.org\),中括号里面是链接文本，后面是链接地址。
什么？你要加上title，没问题！ \[example site\]\(http://www.example.org "Example Title"\)
*Reference-style*就稍稍复杂一点，既然是reference，那么必须是引用另外一个地方，这个地址就需要在其他地方定义了
\[example site\]\[1\]

\[1\]: http://www.example.org "Optional Tilte"

三部分分别是[id]: url "Title",其中tilte是可选的
什么？你说你记不清id，Markdown作者已经为我们考虑到了，id是可以用E文滴，不过是忽略大小写的
\[example site\]\[exsite\]

\[exsite\]: http://www.example.org "Optional Title"

###强调
强调分为大强调和小强调，小强调用*或者_,大强调用啥？2个*或_, 哈哈哈，就像这样\*\*Emphasis\*\*

###代码
代码上面也讲过了，不过上面是代码块，这里是inline的代码，很`包裹起来就行

###图片
图片的语法和链接很像，只是前面加了!,想这样 \!\[alt text\]\(/path/to/img.jpg\)

其他你需要知道的
-------------
###反斜杠
Markdown里面用反斜杠\\作为转义字符

###简写链接
如果超链接的文本和地址是一样的，可以直接这么写\<http://www.example.org\>
生成的超链接就是`<a href="http://www.example.org">http://www.example.org</a>`