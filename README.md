# CPO Skills · 首席产品官技能库

给 Claude Code / Codex / Cursor 等 AI agent 用的中文产品技能。每个 skill 只做一件事，做到不用再找第二个。

## 收录

| skill | 一句话 |
|---|---|
| [crossing-the-chasm](skills/crossing-the-chasm/SKILL.md) | 跨越鸿沟产品官。判断产品卡在哪一段，选滩头细分，整体产品、定位陈述、渠道定价、鸿沟后组织切换。 |
| [skill-forge](skills/skill-forge/SKILL.md) | Skill工厂。三问选题闸口、书/纪要/聊天记录/开源skill四种进料、标准化与非标准化两条评估线、好skill七条标准。 |

## 安装

Claude Code：
```bash
git clone https://github.com/markdao86-design/cpo-skills
cp -r cpo-skills/skills/* ~/.claude/skills/
```
其他 agent：把 `skills/<name>/` 整个目录复制到对应的 skills 路径。

## 每个 skill 的结构

```
<name>/
  SKILL.md       触发描述 + 固定流程 + 硬规则 + 常见误用 + 输出规范
  references/    按需加载的方法论
  templates/     输出骨架
```

## 选题原则

不做模型，不做通用 agent。找人人必用的细分小需求，挑模型现在做得不专业的，打包成 skill 做到最牛。

## 许可证

MIT。方法论来源在各 skill 内注明，均为自行表述，不含原书文本。
