# Markdown写法

## 标题
    # 标题1
    ## 标题2
    ### 标题3 
    #### 标题4 
    ##### 标题5
    ###### 标题6

## 引用
    在引用部分前加上>
>这是一段引用 

引用还可以嵌套使用
>比如
>>这样
>>>还可以加
>>>>无限套娃 :D

## 列表

### 有序列表
    1. 2. 3.
    把大象放进冰箱
1. 打开冰箱
2. 把大象塞进去
3. 关上冰箱

### 无序列表
    - 或者 * 或者 +
    把大象放进冰箱
 - 打开冰箱
 - 把大象放进去
 - 关上冰箱

* 打开冰箱
* 放入大象
* 关上冰箱

+ 打开冰箱
+ 放入大象
+ 关上冰箱

### 任务列表
    把大象放进冰箱
- [x] 打开冰箱 
- [ ] 把大象放进去
- [ ] 关上冰箱

## 代码块
    将代码放在```中 

```c
#include<stdio.h>
void main()
{
    printf("叫你把大象放冰箱，你干啥呢");
    return 0;
}
```

    如果代码中带有`可以用两个`
``我是丁真`test your code` ``



## 强调

### 加粗  
    在需要强调部分的前后加上**或__  

比如 **把大象放进去！**  
以及 __关上冰箱！__  
  
### 斜体
    在需要改成斜体的部分前后加上*或_


比如 *叫你塞大象你在干啥呢*  
以及 _关冰箱，不然你出电费啊_    
  
    加粗和斜体也可以混合使用  

比如
***关冰箱！！！不然我把你塞进去***  

## 分隔线
三个或者多个`*`、`-`、`_`  

***
___
---

## 链接
    [链接文本](链接地址 "链接提示") 

[还没把大象放进去？](https://www.bing.com/search?q=%E5%A6%82%E4%BD%95%E6%8A%8A%E5%A4%A7%E8%B1%A1%E6%94%BE%E8%BF%91%E5%86%B0%E7%AE%B1&form=QBLH&sp=-1&pq=%E5%A6%82%E4%BD%95%E6%8A%8A%E5%A4%A7%E8%B1%A1%E6%94%BE%E8%BF%91%E5%86%B0%E7%AE%B1&sc=0-9&qs=n&sk=&cvid=097785CD4FC844DDB9E036184C596B1E&ghsh=0&ghacc=0&ghpl= "如何把大象放近冰箱")
  
网页之类的也可以直接用`<>`  

比如您可以到<https://www.google.com.hk/>如何将大象放进冰箱

也可以使用链接来实现页面内跳转`[提示信息](#标题名称)`

[例如这里跳转到了分隔线](#分隔线)

[这里跳转到了斜体](#斜体)


## 图片

    ![图片alt](图片链接 "图片title")

### 链接图片
    给图片增加链接，请将图像的Markdown 括在方括号中，然后将链接添加在圆括号中

