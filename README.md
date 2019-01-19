逆向工程
==

项目环境：
--

* 工具: idea2018.1

* jdk：1.8 x64 

* maven：3.5.4

***

`**使用步骤：**`

下载导入idea后

**在主程序入口类GeneratorSqlmap.java中运行main方法，即可自动生成**

```Java
public static void main(String[] args){
    try {
        GeneratorSqlmap generatorSqlmap = new GeneratorSqlmap();
        generatorSqlmap.generator();
    } catch (Exception e) {
        e.printStackTrace();
    }
}
```
<p></p>
<br><br>

**运行展示：**<br>

![](https://img-blog.csdnimg.cn/20190119150123284.png"主程序入口")
