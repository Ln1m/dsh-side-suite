# dsh-extensions-panel

> 本分支是 **零 vk 版**：只注册官方槽，代码不引用任何 vk 槽，装不装 dsh-vk-suite 都一样。vk 版见 [main 分支](https://github.com/Ln1m/dsh-extensions-panel/tree/main)。

> 本分支是 **官方挂载版**（零 vk 依赖）：位置 = 官方 `sidebar.panellist` 槽（左栏图标）配 `main` 槽（中央面板）。vk 版见 [main 分支](https://github.com/Ln1m/dsh-extensions-panel/tree/main)，需先装 [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite)。
> 冲突：一个槽位只渲染优先级最高的一条，同优先级重复注册会直接抛错；与占同一位置的插件互斥（详见 [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite) 的「推荐怎么用 / 会跟谁冲突」）。

[English](README.en.md) · 中文

![功能栏虚拟显示器卡片界面实拍](assets/dsh-extensions-panel.png)

*界面实拍：截自本机运行中的 DSH 实例，示例内容已脱敏。*

在左栏「功能」Tab（`vk.sidebar.extensions` 槽）里注册一张虚拟显示器开关卡片。

## 装

```sh
dsh plugin --profile web add file:<本仓库>
```

装完重启 web 实例。
