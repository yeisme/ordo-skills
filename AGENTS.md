# Ordo Skills 工作区说明

本仓库只维护 Ordo 任务分解、工作区编排和 runtime canary 的 Agent Skills。

- 保持 Skill 名称稳定。
- 不保存 Ordo runtime 源码、数据库、运行 receipt 或凭据。
- 每个 Skill 必须包含 `SKILL.md` 和 `agents/openai.yaml`。
- 验证命令：`python3 scripts/validate_skills.py`。
