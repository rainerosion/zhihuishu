# 知到智慧树刷网课油猴脚本
最近选了多门课，不想慢慢一个课程播放几分钟停留一小时的局面，又把以前写的js脚本改了下，适用于新版的智慧树刷课。不过这一次不是一天能刷完的所以写成了油猴脚本，打开智慧树自动生效。
这一次我提供了2个版本。一个使用tampermonkey运行，一个使用浏览器console控制台运行。

- 自动答题

- 1.25倍速率

- 自动换下一视频

自动答题就是走一个形式，智慧树并不会用来算分数，本脚本多选题大概率会选错，请悉知。

# 方法一：Tampermonkey脚本使用方法

- 打开浏览器

- 安装tampermonkey插件

- 找到Tampermonkey点击

- 选择添加新脚本

- 复制[zhihuishui-tampermonkey.js](zhihuishu-tampermonkey.js)中的内容到输入框

- CTRL+S保存代码

- 进入智慧树课程播放界面自动开始刷课

# 使用方法二：浏览器console运行方法

- 打开智慧树播放网课的界面

- F12 选择console选项卡

- 复制[zhihuishu-console.js](zhihuishu-console.js)中的内容

- 粘贴脚本内容到控制台console输入框后回车。

- 关闭开发者工具弹框（页面重新刷新后需要重复以上步骤）
