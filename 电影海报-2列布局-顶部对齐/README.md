# 电影海报-效果

用`display:inline-block`实现2列布局，标题不固定，有些标题很长超过1行，就会变成下面的效果
![before](./before.png)

解决方法，在父类加`vertical-align: top;`就可以实现对其顶部
![after](./after.png)
