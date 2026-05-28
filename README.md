# Bassa Marea

`restaurant` · `V. Ludovico Fabiani, 20, 87023 Diamante CS, Italy` · ⭐4.4 (141 reviews)

## Файлы

- `brief.json` — структурированные данные для Claude Code (lead, social, reviews, menu, media, palette, stats)
- `info.md` — человекочитаемая сводка
- `media/google/` — 10 файл(ов)

- `index.html` — ещё не сгенерирован

## Media по ролям (AI vision)

  (нет AI-ролей)

## Ручная сборка сайта

1. Открыть Claude Code в этой папке:
   ```bash
   cd "/opt/viktoria-agency/output/bassa-marea"
   claude
   ```
2. Использовать дизайн-скилл:
   ```
   /html-demo "Bassa Marea"
   ```
   или прочитать `brief.json` и подобрать стиль вручную:
   ```
   read brief.json и собери одностраничный сайт с Tailwind CDN. Стиль: ...
   ```
3. Результат сохранить как `index.html` в этой же папке.
4. Записать в БД статус `built` и опубликовать:
   ```bash
   python cli.py publish -l "Bassa Marea"  # ещё не реализовано
   ```

## QA после сборки

```
/qa-demo /opt/viktoria-agency/output/bassa-marea/index.html
```
