##第一章 CSS与HTML
##### 元素
- 块元素：能够包含子元素 ：block
- 行内元素： 不能包含子元素 :inline
- 替换元素： 本来不显示内容 比如 \<image/>
- 非替换元素: 自己显示元素 比如 \<h1>
    
##### css关联
- \<link>标签引入 
    - href:支持url/相对路径引入
    - rel: 关系 stylesheet
    - type: 引入类型： text/css
    - media: css应用的媒体类型 
- \<style>标签
- 内联样式 \<h1 style="color:red;"><h1>     

> 当三种样式共存时后面的会覆盖前面的
## 第二章 选择器

- 组成:选择器(h1):{属性(color):值(red)}
- 类别:
    - 元素选择器: h1{color:red},作用于所有元素
    - 通配选择器: *{color:red}
    - 类选择器: .h1{color:red},作用于class 引用的组件,一个元素可以引用多个类选择器
    - id选择器: #h1{color:red},作用于id引用的组件,一个元素只可以引用一个id选择器
    - 属性选择器: 元素[属性值]{color:red}
    - 后代选择器: 元素1 元素2 {color:red} 仅作用与元素1下的所有元素2的样式,>作用于直系子类，+作用于同类子类
    - 伪类选择器: 元素:关键字 {color:red}
        - 静态伪类: link:未点击的超链接 ,visited: 点击过得超链接
        - 动态伪类: focus: 获取焦点时起作用,hover: 鼠标悬停时起作用, active: 激活元素时起作用
    - 伪元素选择器: 1.first-letter 2.first-line
     ```
        <h2><h2:first-letter>T</h2:first-letter>his is an h2 element</h2>
    ```  
    

