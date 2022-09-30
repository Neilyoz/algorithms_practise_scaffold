# 算法练习架子

最近入手了《算法（第四版）》，为了省去环境搭建快速进行上手，搭建了这个架子。

## 前置要求
- 确保已经安装好maven工具

```bash
git clone https://github.com/Neilyoz/algorithms_practise_scaffold.git
cd algorithms_practise_scaffold
mvn install:install-file -Dfile="lib/algs4.jar" -DgroupId="edu.princeton.cs" -DartifactId=algs4 -Dversion="1.0.0" -Dpackaging=jar
```

执行完成，在idea中即可进行`mvn complie`了，enjoy it~
