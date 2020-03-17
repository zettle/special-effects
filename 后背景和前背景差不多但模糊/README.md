# 实现后背景跟前图一致，但是放大模糊效果
![效果图](./result.png)

实现原理

1、后背景实际上是用img，并且`width=100%,height=100%`，通过`z-index`设置在后面

2、在后背景img的父级div中，设置css样式
```css
filter: blur(50px);
opacity: .6;
```

