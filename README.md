# CUMTB-Master-s-Thesis-Template-For-Word

中国矿业大学（北京）学硕学位论文Word智能大模板（非文科）

# 第一件事：

## 01前言

1. 本文档根据中国矿业大学（北京）截至2023年正在使用的学术型硕士学位论文要求制作https://yjs.cumtb.edu.cn/info/1041/1215.htm

2. *【此条已废弃，由于Word保存上的一些问题，文档已改为标准文档docx格式，对后续编辑没有影响可以照常使用】*！本文档格式为dotx，为Microsoft Word模板文件，当打开这个文件后，Word会按照模板创建一个新文档并且在保存的时候提示选择新文件位置，所以在此文件上的所有编辑均不会影响到原模板文件。

3. 本文档已经内嵌了论文编辑中所有需要的字体，理论上讲不需要再额外安装字体，如果出现意外，此处是楷体GB_2312的下载地址：https://downsc.chinaz.net/Files/DownLoad/font3/bb2510.rar

4. 本文档已经设置了每个大标题的自动奇数页，在导出PDF文件或者打印时，Word会自动添加白页把所有大标题放在奇数页，所以不需要手动加页（不然打印时会多打出几张白纸）

5. 在将文字内容粘贴进此模板时，请一律右键选择“只保留文本”，并使用文档样式清单中的样式，样式库中的样式不要轻易修改或更新（包括样式名，否则更新目录或页眉时可能会报错），论文编辑中的样式需求清单里应该都有，基本不需要新样式了
6. 还有其他问题可以在issue中讨论

## 02完整浏览样式清单

- 01正文文本
- 02_1正文编号
- 02文本固定19.5磅
- 03一级标题
- 04二级标题
- 05三级标题
- 06四级标题
- 07表抬头
- 08表中文字
- 09图片
- 10图抬头
- 11图注
- 12参考文献1-9
- 13参考文献10-99
- 14参考文献100-999
- 15参考文献标题
- 16参考文献正文引用
- 17页眉
- 18页脚
- 19_1扉页信息
- 19_2扉页题目
- 19_3封面信息
- 20标题声明摘要等
- 21_1目录一级标题
- 21_2目录二级标题
- 21_3目录三级标题
- 22摘要正文
- 23摘要关键词
- 24_1附录编号
- 24_2附录标题
- 25附录正文
- 26_1简介 作者姓名
- 26_2简介正文
- 26_3简介小标题
- 26_4简介列项
- 27图表清单
- MTDisplayEquation
- MTEquationSection

此样式清单基本涵盖了中国矿业大学（北京）硕士学位论文（非文科）Word编辑中所有需要用到的正文、图表、标题、摘要、页眉页脚、参考文献、信息、目录清单、附录等格式信息，在论文编辑中需要按照编辑内容自行选择文字样式，下方有详细使用说明。

## 03根据自身情况检查必须的地方

### 检查之前先打开显示编辑标记开关，检查完可以关闭：

<img src="https://i.postimg.cc/BZK0dWqt/image.png" style="zoom:200%;" />

### 章节检查：

文档预置了7个大章节，编辑之前先把大章节调整一致，如果你计划写六章，那就在删除第七章时连带删除章节对应的分节符

[<img src="https://i.postimg.cc/2SQ2D4Cp/2023-03-22-230220.png" style="zoom:200%;" />](https://postimg.cc/5Xtw5QHp)

### 基础格式检查：

文档预置了一些用于测试的内容，供检查目录、图表清单、页眉页脚自动检测功能是否正常，正常情况下全部能正常显示，如果初始便有识别“错误！”报出，就是域代码出了问题，可以在issue中提出。

# 编辑细则：

文档中从摘要开始，全部使用上述样式清单中的样式进行编辑，使用方法为：

- 选择要更改设置格式的文字、图片或表格内容（对于段落或链接样式，鼠标点一下对应的自然段也可以）

- 点击对应的样式

  ![](https://i.postimg.cc/7hHK5kBm/image.png)

## 01编写正文

- 所有论文正文在正常情况下，全部选择 01正文文本格式，带编号的内容选择 02_1正文编号格式
- 其中 02文本固定19.5磅在特殊情况下使用，通常情况它和01格式一样，但是使用Mathtype在正文里输入符号时可能会导致行间距变宽，此时使用02格式来强制修正，Mathtype格式MTDisplayEquation与MTEquationSection已内置
- 正文所有大章节标题一律使用 03一级标题、二级标题一律使用 04二级标题，以此类推

## 02图、图抬头与图注

- 论文插入图片一律使用“嵌入型”，插入后对图片应用样式 09图片

- 图抬头为：插入图片后右键->插入题注，标签选择“图”或者“Fig.”（分别对应中英文图抬头），位置为“所选题目下方”，插入标题后格式一律选择 10图抬头**【对于没有“图”或者“Fig.”的情况，请看下文“其他说明”】**

  <img src="https://i.postimg.cc/xdsdfsnh/image.png" alt="image.png" style="zoom:150%;" />

- 如果图片有说明性注解，格式一律选择 11图注

## 03表、表抬头与表文字

- 文档中以内置好三线表格式并默认，所以直接插入表格就是标准三线表，如果不是，在表设计中选择01三线表，左的表格样式中只勾选“标题行”

  <img src="https://i.postimg.cc/ZnBQ35vd/image.png" alt="image.png" style="zoom:200%;" />

- 表抬头为：插入表格后右键->插入题注，标签选择“表”或者“Table”（分别对应中英文表抬头），位置为“所选题目上方”，插入标题后格式一律选择 07表抬头**【对于没有“表”或者“Table”的情况，请看下文“其他说明”】**

- 对于表格中文字居中，选择使用的单元格，选用 08表中文字格式，这个格式并不是必须使用的

- 文档中只有“图”“Fig.”“表”“Table”四个题注标签是使用的，其余的不要使用

## 04参考文献

- 参考文献内容使用12、13、14三种格式
- 正文中的参考文献上角标一律使用 16参考文献正文引用

## 05目录与图表清单

- 三个目录的格式以已经内置并配置域，但是由于Word限制并不会实时更新，编辑之后要手动点击一下更新

- 更新目录：点击目录中的任意位置或选择目录，Word中点击引用->更新目录->更新整个目录，Word就自动识别了

  <img src="https://i.postimg.cc/cHcv6MZb/image.png" alt="image.png" style="zoom:200%;" />

- 更新图表清单：点击清单中的任意位置或选择目录，Word中点击引用->（题注选项卡）更新表格->更新整个目录，Word就自动识别了

  <img src="https://i.postimg.cc/Y0htk1Sg/image.png" alt="image.png" style="zoom:200%;" />

## 06摘要、附录简介与致谢

- 无论中英文，摘要正文格式一律为 22摘要正文，关键词一律为 23摘要关键词，“关键词”这几个字按一下加粗
- 24_1附录编号 为“附录A”这几个字，24_2附录标题 为下方标题，附录标题不参与目录更新，正文为 25附录正文
- 简介和致谢跟随模板安排走就行
- 封面与扉页中的信息我已经由原来的普通文本格式变成表格，格式安排完成，直接输入内容就行，不用考虑下划线缩进

## 07域更新，页眉、页码与时间戳

- 所有页眉页码格式已按照学校要求格式安排完毕
- 正文的奇数页眉内容会随着章标题而自动变化，偶数页全部为“中国矿业大学（北京）硕士学位论文”，但是由于Word限制并不会实时更新，编辑之后要手动点击一下更新（见下边）
- 论文封面的年月为时间戳，什么时候的打开的文档就显示为当前年月，可以删掉自己改
- 域更新快捷键为F11，如果Ctrl+A全选，在按下F11后，全部的页眉页脚、交叉引用、公式编号、图表抬头、时间戳都会刷新一下

# 其它说明：

## 01有关图、表题注标签的说明：

1. 由于Word将题注标签存储在公用模板中，所以你在打开该模板插入图、表抬头的时候可能发现没有“图”，“表”，“Fig.”，“Table”这几个标签，此时手动添加一下即可，非常简单，并且图表清单会自动对名为“图”和“表”的标签进行识别，所以仍能正常更新无需多余改动，下面说明如何插入新题注标签：

2. 右键任意一张图片，点击“插入题注”->“新建标签”，填入标签名，例如“图”

   ![](https://i.postimg.cc/GhJTnCy4/image.png)

3. 点击确定，选择刚刚创建的标签，点击“编号”，并按照图示设置，点击确定，新标签即插入完毕：

   ![](https://i.postimg.cc/BnjgSbch/image.png)

# 后记：

这个模板前后做了蛮长时间，不过总归是可以极大减少论文排版的时间，避免因为格式挨批对吧。本Word模板计划免费提供给将要毕业的 中国矿业大学（北京） 的硕士同学们，祝我们毕业顺利！

附有捐赠打赏二维码，如果真能收到感谢的话我会很高兴~
