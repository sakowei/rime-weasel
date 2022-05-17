# rime-weasel

```
       _____                                                         ______
__________(_)______ ________       ___      ____________ _______________  /
__  ___/_  /__  __ `__ \  _ \________ | /| / /  _ \  __ `/_  ___/  _ \_  / 
_  /   _  / _  / / / / /  __//_____/_ |/ |/ //  __/ /_/ /_(__  )/  __/  /  
/_/    /_/  /_/ /_/ /_/\___/       ____/|__/ \___/\__,_/ /____/ \___//_/   
```

## 我的小狼毫基础配置

[toc]

主要设置的不多，下表可以查看具体有那些设置，供各位用家查阅：

### 自设主题 一黑／One Dark

![onedark](https://github.com/weirick/rime-weasel/blob/main/color_scheme_onedark.png)

主题配置：在 `程序文件夹\data\weasel.yaml` 最后一行，加空格添加 `onedark.shceme.yaml` 里的内容.

如果想要在 **输入法设定** 显示主题图，可以把`color_scheme_onedark.png`放到 `程序文件夹\data\preview` 里.

### `default.custom.yaml`

| 配置                   | 值          |
| ---------------------- | ----------- |
|												|							|
| good_old_caps_lock     | true        |
| 大小写键绑定           | noop        |
| 左右Shift 切换中英文   | commit_mode |
| 方案选单热键（Ctrl+`） | Shift + F4  |

### `weasel.custom.yaml`

| 配置         | 值                  |
| ------------ | ------------------- |
| color_shceme | onedark（自设主题） |
| 字体家族     | 宋体                |
| 字体大小     | 10                  |
| 横向输入框   | true                |

### `double_pinyin.schema.yaml`

| 配置       | 值   |
| ---------- | ---- |
| 中文, 西文 | 1（默认西文）  |
| 漢字, 汉字   | 1（默认简体字） |
| 左右方括号绑定 | 当出现输入框时，翻页 |
