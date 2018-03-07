# GitHub版maven仓库

在`pom`文件中新增`repositories`节点，声明远程仓库地址：

```xml
<repositories>
    <repository>
        <id>github-maven-repo</id>
        <url>https://raw.githubusercontent.com/nihaorz/maven-repo/master/repository</url>
    </repository>
</repositories>
```

然后声明`dependency`即可从GitHub仓库下载jar包啦。