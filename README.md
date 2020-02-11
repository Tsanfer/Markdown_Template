# Markdown_Template
 Markdown 模板

>**<u>参考[菜鸟教程 > Markdown教程](https://www.runoob.com/markdown/md-tutorial.html)部分内容</u>**
>印象笔记中Markdown的**脚注**、**高级链接**功能不可用
[TOC]

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
段落正常字体
*段落斜体*
**段落粗体**
***段落粗斜体***
***
~~删除线~~
<u>下划线</u>

* 无序项
1. 有序项1
2. 有序项2
3. 有序项3
    1. 嵌套项
    * 嵌套项
    
>区块引用
>>一层嵌套引用
>>>二层嵌套引用
>>>
>>>>>>>>>>>十层嵌套引用.....

`printf("这是一个代码片段"); //代码片段`

```C
printf("这是一个代码块");
//代码块
```

[简单链接格式](https://www.runoob.com/markdown/md-tutorial.html)

![图片替代文字](https://www.runoob.com/wp-content/uploads/2019/03/iconfinder_markdown_298823.png "图片属性")

| 左对齐         |      居中      |         右对齐 |
| :------------- | :------------: | -------------: |
| 这是一个单元格 | 这是一个单元格 | 这是一个单元格 |
| 这是一个单元格 | 这是一个单元格 | 这是一个单元格 |

\*\*使用转义字符\*\*

```chart
,数值一,数值二,数值三
类型1,5000,8000,4000
类型2,3000,1000,4000
类型3,5000,7000,6000
类型4,7000,2000,3000

type: column
title: 柱状图
x.title: 类型
x.suffix: 单位x
y.title: 数值
y.suffix: 单位y
```

```math
e^{i\pi} + 1 = 0 //(Just English Allow Here)
```

```mermaid
graph TD
A[开始A] --> B(过程B)
B --> C{判断条件C}
C -->|条件C1| D[结束D]
C -->|条件C2| E[结束E]
C -->|条件C3| F[结束F]
```

```mermaid
sequenceDiagram
A->>B: 是否已收到消息？
B-->>A: 已收到消息
```

```mermaid
gantt
title 甘特图
dateFormat  YYYY-MM-DD
section 项目A
任务1: duty1, 2018-01-01, 30d
任务2: 20d
section 项目B
任务3: 2018-01-01, 10d
任务4: after duty1, 20d
```
