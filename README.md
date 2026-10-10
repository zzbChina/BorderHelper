# 率土之滨模拟助手

一个基于 **Vue 3 + JavaScript** 实现的率土之滨战斗模拟工具，支持武将/战法/宝物配置、队伍模拟、战斗过程可视化与战报回放。

项目源于对 SLG 战斗系统的兴趣，通过逆向拆解战斗底层逻辑，实现了**效果系统、数值建模、状态机、冲突裁决**等核心模块，可模拟不同阵容与策略的对战胜负。

## 🛠️技术栈

**前端**：Vue 3 + SCSS
**构建**：Vite
**部署**：本地服务器（serve）
**数据**：JSON 配置化驱动（武将 / 战法 / 宝物 / 配队数据 / 阵容 / 账号）

## 📸内容展示

### 武将模块

<img src=".\demonstration\warrior1.jpeg" alt="5_0版本 (7)" style="width: 200px; height: auto;">  <img src=".\demonstration\warrior2.jpeg" alt="5_0版本 (7)" style="width: 200px; height: auto;">  <img src=".\demonstration\warrior3.jpeg" alt="5_0版本 (10)" style="width: 200px; height: auto;" />

可**切换画像选择**，符合自己的风格喜好

### 配队模块

<img src=".\demonstration\demo (14).png" alt="5_0版本 (24)" style="width: 200px; height: auto;" />  <img src=".\demonstration\demo (11).png" alt="5_0版本 (25)" style="width: 200px; height: auto;" /> <img src=".\demonstration\demo (12).png" alt="5_0版本 (25)" style="width: 200px; height: auto;" />

自由搭配属于自己账号的队伍数据，配合导入模拟对局功能，队伍强度更加直观

### 模拟对局模块

完善了**16个高级兵种的特性**加成和宝物系统，**30多种不同宝物**的所有锻造效果均已实现

<img src=".\demonstration\demo (2).png" alt="5_2版本 (2)" style="width: 200px; height: auto;" />  <img src=".\demonstration\demo (5).png" alt="5_4版本 (5)" style="width: 200px; height: auto;" />  <img src=".\demonstration\demo (4).png" alt="demon" style="width: 200px; height: auto;" />

可保存队伍配置，保存其加点，兵种特性选择，和宝物选择，后续模拟对局直接导入更加高效

<img src=".\demonstration\5_4版本 (4).jpeg" alt="5_4版本 (4)" style="width: 200px; height: auto;" /> <img src=".\demonstration\5_4版本 (6).jpeg" alt="5_4版本 (6)" style="width: 200px; height: auto;" /> <img src=".\demonstration\demo (6).png" alt="5_4版本 (6)" style="width: 200px; height: auto;" />

分组保存，**灵活配置**阵容进行对抗演习

<img src=".\demonstration\demo (9).png" alt="5_0版本 (31)" style="width: 200px; height: auto;" /> <img src=".\demonstration\demo (10).png" alt="5_0版本 (33)" style="width: 200px; height: auto;" /> <img src=".\demonstration\demo (13).png" alt="5_0版本 (33)" style="width: 200px; height: auto;" />

战报主页，可连续对战，底部**可选显示特性战报**，优化显示体验，节约阅读时间

<img src=".\demonstration\demo (8).png" alt="iPhone 14 Pro Max" style="width: 200px; height: auto;" /> <img src=".\demonstration\demo.png" alt="iPhone 14 Pro Max" style="width: 200px; height: auto;" /> <img src=".\demonstration\demo (7).png" alt="5_0版本 (38)" style="width: 200px; height: auto;" />

数字部分特殊处理，使得**治疗效果和伤害效果一目了然**，高额伤害显示更为突出，点击伤害处可查看增减伤详情

## 🤝贡献指南

如果你在使用中遇到以下问题，欢迎提交 Issue：
- 🐛 **Bug 报告**：显示异常、战斗流程卡死、战法出现bug等
- 📱 **兼容性问题**：不同浏览器、机型、分辨率下的表现异常
- ⚔️ **游戏数据错误**：武将 / 战法 / 宝物数值与官方版本不一致
- 💡 **功能建议**：体验优化、新功能想法
- 📄 **文档问题**：README 描述不清、安装步骤有误

**后续在完成代码结构整理与资源版权确认后，会考虑开放源码。**



## 📝更新日志

在下一次率土大版本更新后调整（例如年中和年末的平衡性调整）

| 版本 | 时间     | 更新内容                                        |
| ---- | -------- | ----------------------------------------------- |
| 5.11 | 2026/7/7 | 1.同步6月武将平衡性调整；                       |
|      |          | 2.新增对局战法新增**北伐副将、赛季战法**等内容; |
|      |          | 3.修复【审视定计】判定时机问题；                |



## 🚀本地快速部署

通过**serve**运行在本地服务器，通过网络可在多端访问（如果是直接点开html文件使用，下载到本地都会有跨域问题，其余功能也可正常使用）

`serve` 是 Node.js 的第三方工具，需先安装 Node.js（自带 npm 包管理器）：

```
node -v  # 查看Node.js版本
npm -v   # 查看npm版本
```

在 CMD 中执行以下指令，全局安装 `serve`：

```
npm install -g serve
```

使用serve：

```
cd /d "你的文件夹路径"
serve //启动服务器：
//serve -p 8080  # -p = --port，指定端口8080
```

启动成功后，CMD 会显示访问地址（默认：`http://localhost:3000` 或 `http://你的IP:3000`）

## 📮 联系方式

邮箱：zzb3886290@163.com

绿泡泡号：Fenggezzb

欢迎技术交流和问题反馈（一直活着🙂）
