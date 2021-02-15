# IEEE论文模板

## 1.IEEE官方模板

[IEEE官方模板下载链接](https://journals.ieeeauthorcenter.ieee.org/create-your-ieee-journal-article/authoring-tools-and-templates/tools-for-ieee-authors/ieee-article-templates/)

## 2.汉化版模板

只是在原模板的.tex文件中中加入了以下内容：

% 加入对中文的支持\
\usepackage{ctex}			% 假如不需要中文，把这一行删了就行\
\usepackage{graphicx} 		% 图形支持\
%\RequirePackage{graphicx} 	% 图形\
\graphicspath{{figures/}} 	% 修改图片文件路径\
\usepackage{amsmath} 		% 公式支持\
\usepackage{array} 			% 部分表格支持


2021.2.15