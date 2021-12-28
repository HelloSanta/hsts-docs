# Markdown
Markdown 語法：https://markdown.tw/
<br />
Markdown 即時編譯：https://markdownlivepreview.com/

## 強調內容
适合显示重要的提示信息，语法为 !> 内容。
```md
!> 一段重要的内容，可以和其他 **Markdown** 语法混用。
```
!> 内容
## 普通提示
普通的提示信息，比如写 TODO 或者参考内容等。
```md
?> _TODO_ 完善示例
```
?> _TODO_ 完善示例

## 忽略副標題
如果你想忽略特定的標題，可以给它添加 <!-- {docsify-ignore} --> 。

```md
# Getting Started

## Header <!-- {docsify-ignore} -->

該標題不會出現在側邊欄的目錄中。
```

## 設置連結的 target 屬性
```md
[link](/demo ':target=_blank')
[link](/demo2 ':target=_self')
```
## 圖片處理
#### 縮放
```md
![logo](https://docsify.js.org/_media/icon.svg ':size=WIDTHxHEIGHT')
![logo](https://docsify.js.org/_media/icon.svg ':size=50x100')
![logo](https://docsify.js.org/_media/icon.svg ':size=100')

<!-- 支持按百分比缩放 -->

![logo](https://docsify.js.org/_media/icon.svg ':size=10%')
```
#### 設置圖片的 Class
```md
![logo](https://docsify.js.org/_media/icon.svg ':class=someCssClass')
```
#### 設置圖片的 ID
```md
![logo](https://docsify.js.org/_media/icon.svg ':id=someCssId')
```