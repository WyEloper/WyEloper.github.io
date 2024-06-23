### Markdown 是一种轻量级的「标记语法」，它允许人们使用易读易写的纯文本格式编写文档，并可以转换为有效的 HTML。

### 官方文档：

#### 基本语法：<https://markdown.com.cn/basic-syntax/>

#### 扩展语法：<https://markdown.com.cn/extended-syntax/>

------

### 以下是一些基本的 Markdown 语法：

1. 标题：使用 # 号来标示，一个#是一级标题，两个#是二级标题，以此类推，支持六级标题。

   > # 这是一级标题
   > ## 这是二级标题
   > ### 这是三级标题
   > #### 这是四级标题
   > ##### 这是五级标题
   > ###### 这是六级标题

2. 段落：段落没有特殊的格式，直接编写文字就好，***段落的换行是使用两个以上空格加上回车***。

3. 列表：无序列表使用星号(*)、加号(+)或是减号(-)作为列表标记，有序列表则使用数字加上 . 号来表示。

   > - 无序列表项 1
   > - 无序列表项 2
   > - 无序列表项 3
   >
   > 1. 有序列表项 1
   > 2. 有序列表项 2
   > 3. 有序列表项 3

4. 引用：在引用的文字前加 >即可。引用也可以嵌套，如加两个 >> 。

   > 这是一段引用
   >> 这是二级嵌套的引用

5. 链接和图片：使用 [] 来插入链接，使用 ![] 来插入图片。

   > 这是一个链接[-我的github](https://github.com/WyEloper)   
   > 这是一个图片![-我的头像](https://avatars.githubusercontent.com/u/10302484?s=96&v=4)   
   > 网址: <https://github.com/WyEloper>   
   > email: <923275116@qq.com>
6. 代码：可以用反引号 ` 包裹一小段代码，或者用 ``` 包裹一段代码。

   > `console.log('Hello World')`

   围栏代码块：在代码块之前和之后的行上使用三个反引号（```）或三个波浪号（~~~）
   ~~~
   public class MyClass {
       public static void main(String[] args) {
            System.out.println('Hello, world!');
       }
   }   
   ~~~

   ```java
   public class MyClass {
       public static void main(String[] args) {
            System.out.println('Hello, world!');
       }
   }   
   ```
   语法高亮：添加语法突出显示，请在受防护的代码块之前的反引号旁边指定一种语言
   ```json
   {
   "firstName": "John",
   "lastName": "Smith",
   "age": 25
   }
   ```

7. 强调：Markdown 使用星号（*）和下划线（_）作为标记强调字词的符号, *或_的前后都要有一个空格。

   > **这些文字会被加粗**  
   > ***这些文字会加粗倾斜***  
   > *这些文字也会倾斜*  
   > _这些文字会被倾斜_   
   > ~~这是删除线~~   **在单词前后使用两个波浪号~~**

------

### 这些是 Markdown 的基本语法，但不同的 Markdown 解析器可能会支持一些额外的功能，例如表格、脚注等等。