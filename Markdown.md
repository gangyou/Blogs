Markdownѧϰ�ʼ�
=====================

Markdown��ʲô�ҾͲ�˵���ˣ�ϣ���˽��ͬѧ��[Google](http://www.google.com.hk) ���߷���[Markdown�ٷ���վ](http://http://daringfireball.net/projects/markdown/)

Markdown�������Է�Ϊ *Block Elements* �� *Span Elements*

Block Elements
-----------------
###����
��markdown�����Դ�ļ������һ�о���һ�����䣬ÿ���س�markdown���Զ�ת����`<br/>`

###Headers
headers��Ϊsetext��ʽ��atx��ʽ
����˵*setext*��ʽ��������������������һ�У�Ȼ����=����-�������滮��һ�žͳ�����Ŷ~
atx��ʽ����������#���ü���#�ͱ�ʾ��������

###����Blackquotes
����ڹ��ڵ�HTML������ʵû��ô���֣���Ϊ�й��˲�ϲ����ʾ�Լ������õģ���������Ҳ������^_^
������>��ͷ��

###�б�
####�����б�
��*,+,-�����Ա�ʾ�б�ֻ��Ҫ������һ������+һ���ո�Ȼ���������б����־Ϳ�����
####�����б�
�����б���Ҫ���������к�Ӣ�ľ������ʾ���磺
1. First
2. Second
3. Third

###�����
������``���������Ƭ�ξͿ��ԣ�**&<>**��Щ����Markdown���Զ�ת��Ϊ��Ӧ��HTML
���ڶ��д��룬�����Լ�������������ô��Ҫ�ڴ���ǰ��1��tab����4���ո���ͷ

###ˮƽ�ָ���
��������*,-,_����ˮƽ�ָ�����

Span Elements
---------------
###����
Markdown�����ӷ�Ϊ2�����ͣ�inline-style��reference-style��ͻȻ����Gangnam Style~
inline-style�������� \[example site\]\(http://www.example.org\),�����������������ı������������ӵ�ַ��
ʲô����Ҫ����title��û���⣡ \[example site\]\(http://www.example.org "Example Title"\)
*Reference-style*�����Ը���һ�㣬��Ȼ��reference����ô��������������һ���ط��������ַ����Ҫ�������ط�������
\[example site\]\[1\]

\[1\]: http://www.example.org "Optional Tilte"

�����ֱַ���[id]: url "Title",����tilte�ǿ�ѡ��
ʲô����˵��ǲ���id��Markdown�����Ѿ�Ϊ���ǿ��ǵ��ˣ�id�ǿ�����E�ĵΣ������Ǻ��Դ�Сд��
\[example site\]\[exsite\]

\[exsite\]: http://www.example.org "Optional Title"

###ǿ��
ǿ����Ϊ��ǿ����Сǿ����Сǿ����*����_,��ǿ����ɶ��2��*��_, ����������������\*\*Emphasis\*\*

###����
��������Ҳ�����ˣ����������Ǵ���飬������inline�Ĵ��룬��`������������

###ͼƬ
ͼƬ���﷨�����Ӻ���ֻ��ǰ�����!,������ \!\[alt text\]\(/path/to/img.jpg\)

��������Ҫ֪����
-------------
###��б��
Markdown�����÷�б��\\��Ϊת���ַ�

###��д����
��������ӵ��ı��͵�ַ��һ���ģ�����ֱ����ôд\<http://www.example.org\>
���ɵĳ����Ӿ���`<a href="http://www.example.org">http://www.example.org</a>`