学习 vim 并且其会成为你最后一个使用的文本编辑器。没有比这个更好的文本编辑器了，非常地难学，但是却不可思议地好用。

* 我建议下面这四个步骤：1.存活；2.感觉良好；3.觉得更好，更强，更快；4.使用VIM的超能力。
* vim的学习曲线相当的大，所以，如果你一开始看到的是一大堆VIM的命令分类，你一定会对这个编辑器失去兴趣的。
* vi\(vim\)是上Linux非常常用的编辑器，很多Linux发行版都默认安装了vi\(vim\)。vi\(vim\)命令繁多但是如果使用灵活之后将会大大提高效率。vi是“visual interface”的缩写，vim是vi IMproved\(增强版的vi\)。

| 分类 |
| :--- |


|  | 命令 |
| :--- | :--- |
| 一、打开文件、保存、关闭文件 | vim filename //打开filename文件 |
|  | :w //保存文件 |
|  | :w atool.org //保存至atool.org文件 |
|  | :q //退出编辑器，如果文件已修改请使用下面的命令 |
|  | :q! //退出编辑器，且不保存 |
|  | :wq //退出编辑器，且保存文件 |
| 二、插入文本或行\(按ESC键可退出插入模式\) | a //在当前光标位置的右边添加文本 |
|  | i //在当前光标位置的左边添加文本 |
|  | A //在当前行的末尾位置添加文本 |
|  | I //在当前行的开始处添加文本\(非空字符的行首\) |
|  | O //在当前行的上面新建一行 |
|  | o //在当前行的下面新建一行 |
|  | R //替换\(覆盖\)当前光标位置及后面的若干文本 |
|  | J //合并光标所在行及下一行为一行\(依然在命令模式\) |
| 三、移动光标 | 使用上下左右方向键 |
|  | 命令模式下：h 向左、j 向下 、k 向上、l 向右。 |
|  | 空格键 向右、Backspace 向左、Enter 移动到下一行首、- 移动到上一行首。 |
| 四、删除、恢复字符或行 | x //删除当前字符 |
|  | nx //删除从光标开始的n个字符 |
|  | dd //删除当前行 |
|  | ndd //向下删除当前行在内的n行 |
|  | u //撤销上一步操作 |
|  | U //撤销对当前行的所有操作 |
| 五、搜索 | /atool //向光标下搜索atool字符串 |
|  | ?atool //向光标上搜索atool字符串 |
|  | n //向下搜索前一个搜素动作 |
|  | N //向上搜索前一个搜索动作 |
| 六、跳至指定行 | n+ //向下跳n行 |
|  | n- //向上跳n行 |
|  | nG //跳到行号为n的行 |
|  | G //跳至文件的底部 |
| 七、设置行号 | :set nu //显示行号 |
|  | :set nonu //取消显示行号 |
| 八、复制、粘贴 | yy //将当前行复制到缓存区，也可以用 "ayy 复制，"a 为缓冲区，a也可以替换为a到z的任意字母，可以完成多个复制任务。 |
|  | nyy //将当前行向下n行复制到缓冲区，也可以用 "anyy 复制，"a 为缓冲区，a也可以替换为a到z的任意字母，可以完成多个复制任务。 |
|  | yw //复制从光标开始到词尾的字符。 |
|  | nyw //复制从光标开始的n个单词。 |
|  | y^ //复制从光标到行首的内容。 |
|  | y$ //复制从光标到行尾的内容。 |
|  | p //粘贴剪切板里的内容在光标后，如果使用了前面的自定义缓冲区，建议使用"ap 进行粘贴。 |
|  | P //粘贴剪切板里的内容在光标前，如果使用了前面的自定义缓冲区，建议使用"aP 进行粘贴。 |
| 九、替换 | :s/old/new //用new替换行中首次出现的old |
|  | :s/old/new/g //用new替换行中所有的old |
|  | :n,m s/old/new/g //用new替换从n到m行里所有的old |
|  | :%s/old/new/g //用new替换当前文件里所有的old |
| 十、编辑其他文件 | :e otherfilename //编辑文件名为otherfilename的文件。 |
| 十一、修改文件格式 | set fileformat=unix //将文件修改为unix格式，如win下面的文本文件在linux下会出现^M。 |



