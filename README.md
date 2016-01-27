# SimpleNotes
一款类似iOS自带备忘录的app
我把名字叫做“去记”，**强调随时随地都能记录身边的事**
___
主要功能
===
- 以自定义的listview的形式显示已经存在的笔记
- 可以在列表中向左滑动删除，也可以在笔记内容页面删除
- 可以动态搜索笔记内容
- 可以在笔记内容界面改变界面背景颜色
- 可以将笔记分享出去
- 可以在笔记内容界面添加新的笔记
___
主要特点
===
-做这个app的初衷是之前做过但是做的很粗糙xian（虽然现在仍然粗糙，摊手。。。）

主要目的是 **在应用中使用各种动画库**
用到的库有：

1. [翻书效果的动画android-flip](https://github.com/openaphid/android-flip)

    它主要用在应用第一次启动时的引导界面
    
2. [Material Design](https://github.com/MichiganLabs/MaterialDesignLibrary)

    在很多地方用到这个效果，组件虽然不多，但是用起来感觉特别棒
    
3. [类似path的菜单](https://github.com/siyamed/android-satellite-menu)

    这个菜单效果很棒，下图会给出
4. [滑动删除](https://github.com/yydcdut/SlideAndDragListView)
  用在listview中，类似于微信的删除效果
  
___
其他
===
- 使用viewflipper实现不同的页面的滑动效果，本来想用viewpager的，但是太麻烦了。。。
- 按键都是遵循Material Design的设计规范

___
截图
===
第一次启用的过渡界面
![image](https://github.com/tanyanghzsd/SimpleNotes/tree/master/raw/1.png)
![image](https://github.com/tanyanghzsd/SimpleNotes/tree/master/raw/5.png)

主界面列表
![image](https://github.com/tanyanghzsd/SimpleNotes/tree/master/raw/11.png)

笔记详细内容界面
![image](https://github.com/tanyanghzsd/SimpleNotes/tree/master/raw/6.png)

调节rgb控制板可以控制界面背景颜色
![image](https://github.com/tanyanghzsd/SimpleNotes/tree/master/raw/7.png)

分享功能
![image](https://github.com/tanyanghzsd/SimpleNotes/tree/master/raw/8.png)

滑动删除
![image](https://github.com/tanyanghzsd/SimpleNotes/tree/master/raw/9.png)

搜索功能
![image](https://github.com/tanyanghzsd/SimpleNotes/tree/master/raw/10.png)
