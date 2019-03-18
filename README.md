# git-maven
Maven仓库
## 部署
mvn clean deploy -Dmaven.test.skip  -DaltDeploymentRepository=self-mvn-repo::default::file:F:\MavenRepository\git-maven
## 使用
```
<repositories>
    <repository>
        <id>git-maven</id>
        <url>https://raw.githubusercontent.com/liuzihaoboy/git-maven/master/repository</url>
    </repository>
</repositories>
```
