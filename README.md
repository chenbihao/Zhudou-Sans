# Fork

本仓库Fork自 [Zhudou Sans](https://github.com/Buernia/Zhudou-Sans)，

额外替换了一版 [ss02](ss02/ZhudouSans-Normal.sfd) 的版本（使用 FontForge ），相当于默认就应用了ss02特性的字体，方便使用。


## 煮豆黑体 Zhudou Sans


煮豆黑体是衍生自 [Noto Sans](https://github.com/googlefonts/noto-fonts) 和[思源黑体](https://github.com/adobe-fonts/source-han-sans)的标点符号字体家族，支持中日韩标点、全角字母、全角数字及一些特殊符号。标点造型主要来源于 Noto Sans，可以为类似风格的西文字体带来更加协调的中外文混排效果。

本字体为可变字体，支持字重无级变化，同时提供对应思源黑体7个字重的静态版本。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./images/Title.dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./images/Title.light.svg">
  <img src="./Title.light.svg">
</picture>

> 样张文本选自马王堆汉墓帛书《老子》甲本、[《请颁行新式标点符号议案（修正案）》](https://zh.wikisource.org/wiki/%E8%AB%8B%E9%A0%92%E8%A1%8C%E6%96%B0%E5%BC%8F%E6%A8%99%E9%BB%9E%E7%AC%A6%E8%99%9F%E8%AD%B0%E6%A1%88%EF%BC%88%E4%BF%AE%E6%AD%A3%E6%A1%88%EF%BC%89)、1951年[《标点符号用法》](https://zh.wikisource.org/wiki/%E6%A8%99%E9%BB%9E%E7%AC%A6%E8%99%9F%E7%94%A8%E6%B3%95_(1951%E5%B9%B4))和日文维基百科条目[《約物》](https://ja.wikipedia.org/w/index.php?title=%E7%B4%84%E7%89%A9&oldid=86255058)
>
> 样张使用的中日文字体为思源黑体

## 字符支持

* 现代中日韩标点符号
* 古汉语钩识号（𖿢，`U+16FE2`）和重文号（𖿣，`U+16FE3`）
* 全角字母、数字
* 7个知识共享（Creative Commons）许可图标（⊜🄍🄎🄏🅭🅮🅯，`U+229C`、`U+1F10D`—`U+1F10F`、`U+1F16D`—`U+1F16F`）
* 6个中国传统吉祥图案（🉠🉡🉢🉣🉤🉥，`U+1F260`—`U+1F265`）

⚠**注意：本字体不包含汉字、假名、谚文、一般西文和数字，请和其他字体搭配使用。**

## 排版功能

本字体支持以下 OpenType 排版特性：

* **替代半角宽度**（`halt`、`vhal`）

  将所有标点符号的宽度设置为半角。

* **自选连字**（`dlig`）

  将 “？？” “？！” “！？” “！！” 组合成 “⁇” “⁈” “⁉” “‼” 合字。可在软件 OpenType 功能菜单中选择 “自由连字”（Adobe）或 “历史和任意连字”（Word）以开启该功能。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./images/dlig.dark.svg">
  <img src="./images/dlig.light.svg">
</picture>

* **全角、半角与比例宽度字形**（`fwid`、`hwid`、`pwid`）

  弯引号有全角、半角、比例（Adobe 误译为 “等比宽度”）3种宽度的字形，连接号和间隔号有全角、半角2种宽度的字形。Adobe 软件可在 “字形” 面板中选择相应字形。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./images/fwid-hwid-pwid.dark.svg">
  <img src="./images/fwid-hwid-pwid.light.svg">
</picture>

* **破折号连字**（`ccmp`）

  将2个 “—”（`U+2014`）组成一个完整的破折号，将3个 “—” 组成一个占3字宽的长横。默认开启。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./images/ccmp.dark.svg">
  <img src="./images/ccmp.light.svg">
</picture>

* **标点挤压**（`kern`、`vkrn`）

  压缩连续出现的标点符号所占空间。默认开启，可在软件字距微调菜单中关闭。在 InDesign 等专业排版软件中建议关闭（选择 “原始设定-仅罗马字”，确保西文字母间距微调不受影响），改用软件内的标点挤压功能。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./images/kern.dark.svg">
  <img src="./images/kern.light.svg">
</picture>

  > 文本选自《请颁行新式标点符号议案（修正案）》

* **地区字形**（`locl`）

  本字体默认采用中国内地标点规范，可在软件（如 Word 和 InDesign）或网页中将文本标记为相应语言以采用港澳台、日本或韩国规范。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./images/locl.dark.svg">
  <img src="./images/locl.light.svg">
</picture>

  > 文本选自1951年《标点符号用法》

* **斜杠0**（`zero`）

  将全角数字０更改为斜杠０︀（Adobe 称 “斜线零”）字形。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./images/zero.dark.svg">
  <img src="./images/zero.light.svg">
</picture>

* **竖排字形**（`vert`）

  在竖排文本中使用相应的标点形式，默认开启。

* **居中标点**（`cpct`、`ss01`）

  将顿号、句号、叹号、逗号、句点、冒号、分号、问号居中。可在软件 OpenType 功能菜单中选择 “居中中日韩标点” 风格组合（Adobe）或 “样式集1”（Word）以开启该功能。
  
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./images/cpct.dark.svg">
  <img src="./images/cpct.light.svg">
</picture>

* **蝌蚪形逗号**（`ss02`）**（新特性！）**

  将逗号、分号和引号的字形改为蝌蚪形。可在软件 OpenType 功能菜单中选择 “蝌蚪逗号” 风格组合（Adobe）或 “样式集2”（Word）以开启该功能。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./images/ss02.dark.svg">
  <img src="./images/ss02.light.svg">
</picture>

此外，本字体亦支持变体选择符（Variation Selector，VS）功能，在相应字符后输入变体选择符 VS01（`U+FE00`）或 VS02（`U+FE01`）即可强制将该字符显示为规定的变体字形。本字体支持以下 Unicode 定义的标点符号和数字变体字形：

| 字符          | 顿号`U+3001` | 句号`U+3002` | 叹号`U+FF01` | 逗号`U+FF0C` | 句点`U+FF0E` | 全角数字0 `U+FF10` | 冒号`U+FF1A` | 分号`U+FF1B` | 问号`U+FF1F` |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ----------- | ---------- | ---------- | ---------- |
| VS01 `U+FE00` | 、︀（偏靠） | 。︀（偏靠） | ！︀（偏靠） | ，︀（偏靠） | ．︀（偏靠） | ０︀（斜杠0） | ：︀（偏靠） | ；︀（偏靠） | ？︀（偏靠） |
| VS02 `U+FE01` | 、︁（居中） | 。︁（居中） | ！︁（居中） | ，︁（居中） | ．︁（居中） | 不适用 | ：︁（居中） | ；︁（居中） | ？︁（居中） |

上表中的符号可直接复制粘贴使用。

## 授权信息

本字体以《SIL 开源字体许可证》1.1版（SIL Open Font License 1.1，OFL）授权，可以自由使用（包括商用）、传播、修改，但不能单独出售字体文件。此外，修改版本不可使用本字体的保留名称 “Zhudou” 和 “煮豆”，且必须同样以《OFL》授权。详细信息请参见 https://scripts.sil.org/OFL 。

## 致谢

感谢[绵云饴里](https://github.com/MY1L)优化传统吉祥图案的轮廓。

## 联系作者

* **Twitter**：[@Buernia](https://twitter.com/Buernia)
* **新浪微博**：[@奈白不弍](https://weibo.com/p/1005055835431520)
* **Email**：buernia在foxmail.com（在→@）

关于本字体的意见或问题，建议在本项目的 [Issues 页面](https://github.com/Buernia/Zhudou-Sans/issues)提出。

## 其他项目

* [铁蒺藜体 Tiejili](https://github.com/Buernia/Tiejili)

