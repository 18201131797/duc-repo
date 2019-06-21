duc maven 仓库
=========================

### 使用方式 
1.pom.xml 文件中增远程仓库配置
```
    <repositories>
        <repository>
            <id>duc-repo</id>
            <url>https://raw.github.com/18201131797/duc-repo/master/</url>
        </repository>
    </repositories>
```
2.pom.xml 文件增加引用jar包
```
    <dependency>
          <groupId>xxx.xxx</groupId>
          <artifactId>xxx-xxx</artifactId>
          <version>x.x.x</version>
     </dependency>
```
--------------------------------

### 可用jar包

1. core

```
    <dependency>
          <groupId>com.core</groupId>
          <artifactId>duc-core</artifactId>
          <version>1.0.0</version>
    </dependency>
```

2.tkmybatis

```
    <dependency>
        <groupId>com.tkmybatis</groupId>
        <artifactId>duc-tkmybatis</artifactId>
        <version>1.0.0</version>
    </dependency>
```

3.web

```
    <dependency>
        <groupId>com.web</groupId>
        <artifactId>duc-web</artifactId>
        <version>1.0.0</version>
    </dependency>
```

4.redis

```
    <dependency>
        <groupId>com.redis</groupId>
        <artifactId>duc-redis</artifactId>
        <version>1.0.0</version>
    </dependency>
```

5.swagger

```
    <dependency>
        <groupId>com.swagger</groupId>
        <artifactId>duc-swagger</artifactId>
        <version>1.0.0</version>
    </dependency>
```

5.rocketmq

```
    <dependency>
        <groupId>com.rocketmq</groupId>
        <artifactId>duc-rocketmq</artifactId>
        <version>1.0.0</version>
    </dependency>
```

--------------------------------

注意：如果jar包下载不下来请检查 maven 的 setting.xml 文件 镜像仓库mirror的mirrorOf是否设置成了*需要改成central
