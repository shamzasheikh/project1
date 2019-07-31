### Java installation

1. Update the repository

```sudo yum -y update```

2. Install JRE or JDK

For JRE: 
```sudo yum install java-1.8.0-openjdk```
<br\> 
For JDK:
```sudo yum install java-1.8.0-openjdk-devel```

3. Check the installed version

```java -version```

4. Set environment variable

```update-alternatives --config java```

vim .bash_profile
```export JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.191.b12-1.el7_6.x86_64/jre/bin/java```

```source .bash_profile```

```echo $JAVA_HOME```
