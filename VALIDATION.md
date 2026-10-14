# 验证记录

## 2026-10-15 同步与复验

2026-10-15，在本源码副本重新运行：

```sh
node --test tests/services.test.mjs tests/adventure.test.mjs tests/economy.test.mjs
```

结果：31 tests，31 passed，0 failed / cancelled / skipped。覆盖状态持久化、稳定回执、钱包迁移、失败保存和重复结算等确定性逻辑。本次检查不依赖完整画面素材。

核对当前主工作目录的 812 个发布范围文件，内容一致；未从历史备份或安装包覆盖当前源码。版本字段 1.27.0 是源码标记，不能代替完整发行包版本或真实联机 / 手机验收。

源码文件及发布字节哈希见 [SOURCE_INVENTORY.json](SOURCE_INVENTORY.json)，同步范围见 [同步摘要](validation/source-sync-20261015.json)。

## 历史记录（原日期保留）

2026-10-14，在本源码副本运行：

```sh
node --test tests/services.test.mjs tests/adventure.test.mjs tests/economy.test.mjs
```

结果：31 tests，31 passed，0 failed。覆盖进度持久化、冒险状态、奖励、钱包与重复结算等确定性逻辑。

本仓库是源码审阅版。授权尚未核实的运行美术、音频和魔塔地图未收录，因此不等同完整可安装发行包。合作地图保留GPL许可与可编辑源文件；其余第三方文件保留各自许可。
