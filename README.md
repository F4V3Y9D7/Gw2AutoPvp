# Gw2AutoPvp ~ Guild Wars 2 Automatic Pvp Bot
# 一款激战2自动竞技场机器人脚本bot
---
## 警告⚠
- 切勿倒卖，仅作于技术学习交流用途，下载后请于24小时内删除。切勿破坏游戏平衡。

## 说明
- 20240403：由于Aibot框架变相收费，故换成开源得op框架。（打着非商用免费的名义来限制时长是真的恶心，避坑）
- 有bug提交Issues，并说明bug情况，随缘修复

## 支持功能
- [x] 自动寻路占点
- [x] ~~自动释放技能~~
- [x] ~~支持多开(未测试,推荐在虚拟机多开)~~(20240601已禁止此功能)
- [x] 组排队长/队员模式
- [x] 5V5模式
- [x] 排位模式(自动识别)
- [x] 匹配模式(自动识别)
- [x] 自定义房(仅支持天空地图)
- [x] 3V3/2V2模式
- [ ] ~~交互界面GUI~~(计划取消)

### 1.下载
- 下载页面右侧`Release`发布的编译版本👉
- 解压到**非中文路径**下，**以管理员身份**运行`Gw2AutoPvp.exe`

### 2.环境设置
- windows**系统桌面缩放尽量为100%** （不会的自行百度，貌似支持其他缩放，自己尝试）
- 游戏必须窗口化，带标题栏的那种，否则游戏会崩溃
- **务必卸载神油、dps、滤镜等插件**，否则会带来很多bug

### 3.游戏设置
- 系统设置中启用：`使用自由视角`
- 系统设置中**必须关闭**：`双击方向键闪避`
- 快捷键**必须设置**：`W前进`、`S后退`、`A左平移`、`D右平移`、`J左转`、`K右转`、`P pvp面板快捷键`
- **强调**：`J左转`、`K右转`**必须设置**！否则寻路时不能自动转动视角
- 系统设置-图像选项中的**界面大小**必须设置为**普通**
- DPI缩放关闭，全屏伽马值为1
- 画质全部最低

### 4.启动脚本
- 运行`Gw2AutoPvp.exe`
- **注意**：必须进入pvp地图-迷雾之心后，开启本脚本

### 5.其他注意事项
- 强烈推荐使用死灵自杀流挂机！！！[bd配置点这里](https://www.bilibili.com/video/BV1JL4y1G78D/?spm_id_from=333.337.search-card.all.click&vd_source=0940bf29b38efba56ccfc6a3cef8182d)，如果不能自杀，可能会出现寻路失效！！！同时注意修改`suicide.txt`中的自动按键
- 右键系统桌面-显示设置，其中的`缩放`必须设置为100%！否则无法识别游戏图像
- 支持自动释放技能，需要更改`config`文件夹下的`suicide.txt`文件！默认快捷键为0、9、8、7四个技能
- **注意**：必须进入pvp地图-迷雾之心后，开启本脚本
- 游戏设置中的`界面大小`需要设置为`普通`，关闭DPI缩放，全屏伽马值为 1
- 如果你不够20级无法进行排位模式，那么使用脚本之前必须在pvp界面的`非排位偏好`里勾选`征服`模式。不能选择所有模式！否则会排到`末日英雄之战`这张图，效率极低，容易被举报

## 最后
- 无任何QQ群、交流群，不提供安装一条龙服务，自己动手，丰衣足食
