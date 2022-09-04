# string_template
## english doc

[Click here to view the schematic diagram](https://wurenzhi.com/resource/pic.png)

Instructions:

1. Introduce dependencies (if the third-party warehouse fails, please use the central warehouse)
````
<dependency>
     <groupId>com.wurenzhi</groupId>
     <artifactId>string_template</artifactId>
     <version>2.0.0</version>
</dependency>
````

2. Set compile options
idea:
Settings --> Build, Execution, Deployment --> Compiler --> Shared build process VM options:
````
-Djps.track.ap.dependencies=false
````

3. Add annotations to class files that need to use string templates
````
@StringTemplate
public class Test {
     //some code
}
````

4. Recompile the project (it only needs to be recompiled once after the introduction, and it will be automatically compiled later)


## 中文文档

[点此查看示意图](https://wurenzhi.com/resource/pic.png)

使用方法:

1. 引入依赖(第三方仓库如果失败,请使用中央仓库)
```
<dependency>
    <groupId>com.wurenzhi</groupId>
    <artifactId>string_template</artifactId>
    <version>2.0.0</version>
</dependency>
```

2. 设置编译选项
idea:
Settings --> Build, Execution, Deployment --> Compiler --> Shared build process VM options: 
```
-Djps.track.ap.dependencies=false
```

3. 在需要使用字符串模板的class文件上添加注解
```
@StringTemplate
public class Test {
    //some code
}
```

4. 重新编译项目(仅在引入后需要重新编译一次,后续会自动编译)
