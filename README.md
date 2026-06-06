# 数学建模 Codex Skills

这套 Skills 将数学建模竞赛或课题拆成 7 个可复用子流程：文献、数据、建模、代码、绘图、写作、排版。

codex使用方式(放置方式)：

```bash
mkdir -p ~/.codex/skills
cp -r math-modeling-* ~/.codex/skills/
```

也可以把本目录复制到项目仓库的 `.codex/skills/` 或团队约定的 skills 目录中。

建议在项目根目录额外放一个 `AGENTS.md`，告诉 Codex：

```md
# 数学建模项目约定

当任务涉及数学建模竞赛、建模课题、论文、数据分析、模型求解、可视化或排版时，优先调用对应的 math-modeling-* skill。
中文输出，代码可复现，真实数据优先，所有外部数据和文献必须记录来源。
```
