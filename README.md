# wukong-itchat

用于微信控制 [wukong-robot](http://github.com/wzpan/wukong-robot.git) 。

## 安装

1.先安装wukong-robot并运行，确保wukong-robot的版本> = 1.5；

2.克隆仓库：

git clone https://github.com/wzpan/wukong-itchat.git

3.安装依赖：

``` bash
cd wukong-itchat

pip3 install -r requirements.txt
```

## 运行

``` bash
python3 bot.py
```

## 配置

详见 config.yml 。尤其注意如果 itchat 和 wukong-robot 并不在同一台服务器上运行，务必修改 `host` 配置。

## 使用

与文件传输助手聊天，文本或者语音都将会作为指令转发给 wukong-robot 的后台管理端。

