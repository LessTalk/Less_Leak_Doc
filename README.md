# 内存泄漏调试

#### 生成Hprof
```
adb shell am dumpheap package /data/local/tmp/less.hprof
```

#### 拷贝文件到 电脑
```
adb pull /data/local/tmp/less.hprof
```

#### 转换格式
```
hprof-conv less.hprof ok.hprof
```

#### [下载Mat](https://www.eclipse.org/mat/downloads.php)
