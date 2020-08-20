# 俄罗斯轮盘
适用于hoshinobotv2的俄罗斯轮盘小游戏。<br>
 <br>
项目源码来源于https://github.com/QingWen45/Russian-roulette ，并由 https://github.com/pcrbot/russian 进行了优化和支持多群的修改。<br>
 <br>
添加了允许自定义禁言时间，并对流程表述做了一些优化。记得用之前给bot管理员权限<br>
 <br>
*代码垃圾，欢迎有能人士帮忙抽抽。*<br>
## 安装方法
1. git clone或打包下载代码
2. 将`russian-roulette`文件夹放到`.\HoshinoBot\hoshino\modules`文件夹中
3. 在`.\HoshinoBot\hoshino\config`文件夹中找到`_bot_.py`并在其中的`MODULES ON`部分中增加`'russian-roulette'`
4. 重启bot
## 游戏功能
- [x] 自定义子弹数目及禁言时间
- [x] 无需加入，直接开枪
- [x] 赛后进行胜负总结
- [x] 多群使用
- [ ] 群内分房间
- [ ] 输入错误报错提示
- [ ] 随机击倒表述
- [ ] 强制结束
## 食用方法
群内发送`“俄罗斯轮盘”`或`“开枪”`或`“rs”`开始使用。
