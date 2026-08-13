# Ordo Skills

Ordo 任务分解、Git workspace admission、writer lease、运行时 canary 和验证证据的开源 Skills 集合。

## Skills

- `ordo-dag-task-decomposition`：把 OpenSpec/Goal 任务变成可执行 DAG、owner path 与验收边界。
- `ordo-agent-cli-worktree-orchestration`：管理 current/isolated workspace、writer lease、heartbeat、集成与安全清理。
- `ordo-runtime-canary-evaluation`：对 Codex、Claude Code、OMP、Pi 等 runtime 做受保护 canary、评分与 promotion。

## 验证

```bash
git clone https://github.com/yeisme/ordo-skills.git
cd ordo-skills
python3 scripts/validate_skills.py
```

本仓库不实现 Ordo runtime。实现、协议和持久化由 Ordo 产品仓库拥有。

## License

[MIT](LICENSE)
