# NUDT本科论文Latex模版

provided by nonsense。

本项目基于学长学姐给出的硕博论文模版进行修改。编译方式如下：

```
xelatex + bibtex + xelatex*2
```

# 依赖的字体

使用此模板需要下载安装配套字体：

+ [ttf字体下载(Windows字体，与Word一致)](https://github.com/TomHeaven/nudt_thesis/releases/download/v1.1/ttf.zip)
使用ttf需要修改入口thesis.tex / thesis_blind.tex，确保documentclass的字体参数为

```
\documentclass[doctor,ttf]{nudtpaper}   % ttf字体
```
注意Windows 10系统安装字体`不要双击字体安装`，这样只会为当前用户安装字体，latex可能还是无法找到字体。要右击字体文件，选`为所有用户安装字体`。


# 用法
论文不包括封面，封面做好拼接进来即可。



# 参考文献类别
refs.bib中可用的参考文献类别有：
+ article: Article from a magazine or journal 【学术文章】
+ book: A published book   【书】
+ inbook: A part of a book (section, chapter and so on)  【书的一部分，无单独标题】
+ incollection: A part of a book having its own title        【书的一部分，有单独标题】
+ booklet: A work that is printed but have no publisher or sponsoring institution 【未出版的书】
+ conference: An article in a conference proceedings    【会议论文】
+ inproceedings: An article in a conference proceedings【会议论文集中的论文】
+ manual: Technical documentation                             【手册】
+ masterthesis: A Master’s thesis                                【硕士论文】
+ phdthesis: A PhD thesis                                           【博士论文】
+ proceedings: The same as conference                       【会议论文】
+ techreport: Report published by an institution             【技术报告】
+ unpublished: Document not formally published, with author and title  【未发表的文献】
+ misc: Something that doesn’t fit in any other type       【其他类别】

# 致谢

本模版修改自这些前辈们的工作：

+ LiuBenYuan <liubenyuan@gmail.com>：Github项目[https://github.com/liubenyuan/nudtpaper](https://github.com/liubenyuan/nudtpaper)
+ Ruini <xueruini@gmail.com> 
+ sofoot

在此表示感谢！

# 免责声明

本模板只适用于2018级NUDT本科学员毕业论文。使用本模板产生的任何问题作者不承担任何直接或者间接责任。但作者会尽力帮助有需要的同学解决问题。

