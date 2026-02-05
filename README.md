# Jinx Rules (New)

远程规则仓库，供 Jinx App 自动更新使用。

## 目录结构

```
rules/
├── version.json          # 版本信息
├── blacklist.txt         # 域名黑名单（精确匹配）
├── blacklist_wildcard.txt # 域名黑名单（通配符）
├── whitelist.txt         # 域名白名单（精确匹配）
└── whitelist_wildcard.txt # 域名白名单（通配符）
```

## 同步方式

使用 `scripts/sync_builtin_rules.py` 从 `BuiltinBlacklist.swift` 同步规则：

```bash
python3 scripts/sync_builtin_rules.py
```

## CDN 地址

- jsDelivr: `https://cdn.jsdelivr.net/gh/VME98/jinx-rules-new@master/rules/`
- GitHub Raw: `https://raw.githubusercontent.com/VME98/jinx-rules-new/master/rules/`
