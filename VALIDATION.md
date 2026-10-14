# 验证记录

2026-10-14，在本源码副本运行：

```sh
node --test tests/services.test.mjs tests/adventure.test.mjs tests/economy.test.mjs
```

结果：31 tests，31 passed，0 failed。覆盖进度持久化、冒险状态、奖励、钱包与重复结算等确定性逻辑。

本仓库是源码审阅版。授权尚未核实的运行美术、音频和魔塔地图未收录，因此不等同完整可安装发行包。合作地图保留GPL许可与可编辑源文件；其余第三方文件保留各自许可。
