# sqlla-pool-c3p0

[![](https://jitpack.io/v/PathogenABC/sqlla.svg)](https://jitpack.io/#PathogenABC/sqlla)

基于 c3p0 连接池的 Sqlla.ConnectionPool 数据源的实现

### 引入

在 root build.gradle 中添加下面代码

```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

在 module build.gradle 中添加依赖

```
dependencies {
    compile 'com.github.PathogenABC:sqlla-pool-c3p0:1.0.1'
}
```

[Sqlla项目主页](https://github.com/PathogenABC/sqlla)
