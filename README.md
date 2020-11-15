# Markdown基本语法

GitHub 全站支持 “GitHub 风格的 Markdown 语法”（简称 GFM），你可以用它来书写 issue、pull request（以下简称 “PR”）和各种评论。它和标准 Markdown 语法（SM）相比，存在一些值得注意的差异，并且增加了一些额外功能。

在 issue、评论和 pull request（以下简称 “PR”）的描述中，我们可以用 GitHub 风格的 Markdown 语法 来编写富文本；此外，GitHub 还提供了一些额外的功能，让我们的书写更加方便。
github中的书写方式：https://github.com/baixing/FE-Blog/issues/5

## 1、标题写法

**Markdown的标题有两种写法:**
- **类 Setext** : 用#号标记，一共分为六级标题，其中一级标题字体最大，六级标题字体最小。



```
 # 一级标题
 ## 二级标题
 ### 二级标题
 #### 二级标题
 #### 二级标题
 ##### 二级标题
```
- **类 atx 形式**：分别用=和-标记
```
一级标题
=================

二级标题
-----------
```
> 建议简单的文章用类atx风格，更加清晰。


## 2、斜体与加粗

在字符串首尾各加一个 * 号，代表斜体，各加两个星号代表加粗，三个星号代表斜体并加粗。  
**注意： 星号必须与字符串的首位两个字符紧贴，不能有空格**
```
*我是斜体* 
**我是加粗**  
***我又粗又斜***
~~哈哈哈这是删除~~
```
*我是斜体*  
**我是加粗**  
***我又粗又斜***  
~~哈哈哈这是删除~~

## 3、代码块

在代码块的首尾两行分别加上 **三个反引号（键盘左上方）**，首行的反引号后边可以写上语言类型，如python，java等，这样代码块会支持语法高亮。
```
、、、python  
def main():  
    # 这是python代码的注释
    pirnt(hello world!)  
    pass  
、、、
```

```python  
def main():  
    # 这是python代码的注释
    pirnt(hello world!)  
    pass  
```
## 

## 3、图片引用
因为markdown支持部分html语法，这里我更习惯于用**img标签引用图片**，其中src属性表示图片的路径（这里可以首先将需要使用的图片上传至图床，然后获得图片的url），heigth代表图片高度，宽度会自适应。  

```html
<img src="http://123.57.105.167/ni.png " height="200px">
```
<img src="http://123.57.105.167/ni.png " height="200px">


## 3、生成表格

列与列之间用``` | ```分隔，正文与表头用``` ----- ```分开，```------```两端各加一个冒号变成 ```:----: ```代表本列居中对齐。

```
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
```
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
