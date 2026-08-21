# Sukka Mihomo Rules

SukkaW Clash / Mihomo 规则自动镜像。

## Short Path

Sukka 原始目录：

```
Clash/domainset
Clash/non_ip
Clash/ip
```

自动转换：

```
rules/domain
rules/non_ip
rules/ip
```

## Rule Count

| Type | Count |
|---|---:|
| domain | 11 |
| non_ip | 38 |
| ip | 20 |
| Total | 69 |

## Current Version

```
e4d320cf1cc04006921cc1763d68e07cd5a3f8d856c7345adb3fa6be42bad83b
```

## Raw URL

```
https://raw.githubusercontent.com/locksherneo/mihomo-sukka-rules/main/rules/
```

Example:

```
https://raw.githubusercontent.com/locksherneo/mihomo-sukka-rules/main/rules/domain/game-download.txt
```

## Sync

- 每 24 小时检查一次
- 自动发现 Sukka 新规则
- 无变化不 Commit
- 下载失败保留旧版本
- 规则数量异常保护
- SHA256 完整性检查
- 更新前自动备份
- 最近 5 个版本
- 支持手动回滚

---

Automatically maintained by GitHub Actions.
