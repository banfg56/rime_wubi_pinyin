# rime_wubi_pinyin
rime input method with wubi_pinyin

[Rime](https://rime.im/download/)
Useage：download this package and save it to your Rime installed path, the re-delpoy and enjoy it!

[五笔拼音数据来源](https://github.com/junxxx/rime_wubi_pinyin)

### Rime 安装
#### Mac
Mac ~/Library/Rime/

#### Windows
在用户文件夹以及程序文件夹中替换相关文件

#### Linux Ubuntu

> 注意: fcitx已进入维护模式，推荐使用fcitx5

使用 fcitx-rime, 因为wubi86需要 wubi 与 pinyin-simp 下两个输入方案的数据。安装命令如下：
```
apt-get install fcitx-rime
apt-get install librime-data-wubi librime-data-pinyin-simp
后续可拷贝自定义方案到 ~/.config/fcitx/rime(如果是使用fcitx5可能是在~/.local/share/fcitx5/rime/下) 下。然后再在输入法中选择重新部署即可
```

### default.customer.yaml
主要是以下配置:
* 设置输入法为 wubi_pinyin
* rime快捷键盘设置为 Control+F4
* 输入法切换键设置为 Right Shift

