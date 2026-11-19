# BioAIEvolu · DSH 插件索引（Format 1）

BioAIEvolu 发布的 DeepSeek Harness 插件官方索引源（[插件索引 Format 1](https://deepseek-harness.github.io/deepseek-harness/guide/plugin-market)）。

## 索引地址

在 DSH 中打开 **插件 → 发现 → 添加索引源**，粘贴：

```
https://raw.githubusercontent.com/BioAIEvolu/dsh-plugin-market/main/index.json
```

## 收录插件

| 插件 | 分类 | 说明 |
| --- | --- | --- |
| [dsh-token-tally](https://github.com/BioAIEvolu/dsh-token-tally) | 工具 | Token 用量与费用看板：五页签消耗视图 + 模型对比表 + 53 周热力图，本地聚合 |
| [dsh-md-studio](https://github.com/BioAIEvolu/dsh-md-studio) | 文档 | Markdown 渲染插件：Mermaid 图表、KaTeX 公式、代码高亮，完全离线 |

## 维护

- 新增插件：在 `index.json` 的 `plugins` 数组追加条目（`publishTimestamp` 取 npm 发布时间的 Unix 秒）；
- 新版本：追加 `versions[]` 条目；
- 校验：DSH 会在添加索引源时校验格式，违规条目会在「管理索引源…」中显示 JSON 路径。
