# openwrt-package
Jerry's openwrt-package

建议使用Lean源进行编译。这个Branch的argon不适合官方版本。
包含了 如下应用
- Argon 主题
- Argon 主题配置应用
- vssr(Helloworld)上网冲浪应用
- jd-dailybonus 京豆签到插件
- go-aliyundrive-webdav 阿里云盘webdav的golang实现
- lua-maxminddb lua版本的maxminddb ip库解析器

## 使用方法

添加 src-git jerryk https://github.com/jerrykuku/openwrt-package 到 OpenWRT源码根目录feeds.conf.default文件

然后执行

```bash
./scripts/feeds clean
./scripts/feeds update -a
./scripts/feeds install -a
```
