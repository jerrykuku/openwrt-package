# openwrt-package
Jerry's openwrt-package

建议使用Lean源进行编译。这个Branch的argon不适合官方版本。

## 使用方法

添加 src-git jerryk https://github.com/jerrykuku/openwrt-package 到 OpenWRT源码根目录feeds.conf.default文件

然后执行

```bash
./scripts/feeds clean
./scripts/feeds update -a
./scripts/feeds install -a
```
