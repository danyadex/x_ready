# x_ready

Claude проходит по X-лентам ведущих людей в AI и выделяет главное.

- `authors.md` — кого читаем (редактируй как хочешь)
- `digests/` — готовые дайджесты по датам
- `.claude/commands/digest.md` — инструкция, как читать и что считать важным

## Как запустить

Нужны Claude Code и расширение Claude in Chrome, а в Chrome ты должен быть залогинен в X.

```bash
git clone https://github.com/danyadex/x_ready && cd x_ready
```

```bash
claude --chrome
```

Внутри сессии:

```
/digest
```

Можно указать период: `/digest за последние 3 дня`.
