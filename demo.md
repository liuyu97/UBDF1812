#笔记
##我的笔记05.16
- css
- html
- git **cu**
###Git
```
git init
git add .
git commit -m ""
git push

git clone
```
###不想让边框影响大小
```
box-sizing:border-box
```
###h1 h2 h3  h4 h5 h6
放重要的东西，而不是用它的样式
###ul li
清除默认布局
````
h1,h2,h3,h4,h5.h6{
    
    
    list-style:none;
}
````
###鼠标放上显示手的形状
````
cursor:pointer
````
###CSS3变换 过渡
```
div{
变换
transform:  移动 translate(x,y) 
            缩放 scale(x,y)
                 基准点transform-origin: 10px 10px;
            旋转 rotate(10deg)
            斜切 skew(x,y)
过渡
transition：all 1s linear 2s;
}
```
###CSS3 动画
````
    @keyframes animate{
        0%{
            transform:rotate(0deg);
        }
        100%{
            transform:rotate(30deg);    
        }
    }
 ````
```
div{
    box-shadow:0px 0px 20px #000 inset;
}

```
###a链接不刷新
```
<a href="javascript:;">链接</a>
```
###display改变元素的显示状态
```
display:block;
    inline;
    inline-block;
    none;
```
###CSS里的bug
当给父元素里面的第一个子元素设置margin-top
给父元素设置一个边框或者用padding-top