# bluetooth printer demo

演示运行 echo 插件的例子，后期 printer 的 demo 一样的道理

## 前提环境

需先安装 cordova

```bash
npm install -g cordova
```

添加 android

```bash
cordova platform add android
```

## 插件

更新插件，需先删除，再添加

### 删除 echo 插件

```bash
cordova plugin remove com.plugin.echo
```

### 添加 echo  插件

```bash
cordova plugin add https://github.com/lynzz/cordova-plugin-echo.git --save

```

## 运行

```bash
cordova run android
```

## 调试

用 android studio 打开  platforms/android 目录即可