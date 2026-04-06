# content-polisher-skill

把草稿润色成更清晰、有力度、适合继续编排或发布的文章。

## Installation

This skill is intended to run in the local Codex/Gemini skill workspace.

If you are working in this repository, use the skill directly from:

```bash
~/.agents/skills/content-polisher-skill
```

## Documentation

# Content Polisher

## Codex Compatibility
- 不依赖 `write_file`。
- 默认由上层流水线负责把润色结果保存到目标文件。
- 保留原始 Markdown 结构，不把润色误做成摘要。
