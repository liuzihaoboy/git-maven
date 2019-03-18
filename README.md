# git-maven
## 介绍
maven个人仓库
## 部署
部署到本地
```
mvn clean deploy -Dmaven.test.skip  -DaltDeploymentRepository=self-mvn-repo::default::file:F:\MavenRepository\git-maven
```
## 发布
```
git add .
git commit -m ""
git push origin master
```
## 使用
在pom文件引入
```
<repositories>
    <repository>
        <id>git-maven</id>
        <url>https://raw.githubusercontent.com/liuzihaoboy/git-maven/master/repository</url>
    </repository>
</repositories>
```
maven方式使用
