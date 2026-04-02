# Скиллы для загрузки

Приоритет расставлен под задачу: сайт-портфолио художника, тёмный стиль, золото, галерея работ.

---

## Приоритет 1 — Обязательные

| Скилл | Репо | Зачем |
|---|---|---|
| `frontend-design` | https://github.com/anthropics/skills | Официальный Anthropic: HTML/CSS/React/Tailwind, избегает generic AI-эстетики |
| `web-design-guidelines` | https://github.com/vercel-labs/agent-skills | Официальный Vercel: принципы качественного веб-дизайна |
| `elite-web-design` | https://github.com/RSHVR/elite-web-design | GSAP анимации, CSS паттерны, оптимизация — для элегантного сайта |

## Приоритет 2 — Желательные

| Скилл | Репо | Зачем |
|---|---|---|
| `web-design-workflow` | https://github.com/deserteaglemjAEC/web-design-workflow | 11 скиллов: от идеи до запуска, полный lifecycle |
| `web-artifacts-builder` | https://github.com/anthropics/skills | Официальный Anthropic: HTML с React + Tailwind + shadcn/ui |
| `ui-ux-pro-max` | https://github.com/nextlevelbuilder/ui-ux-pro-max-skill | Профессиональный UI/UX, несколько платформ |

## Приоритет 3 — SEO (после запуска)

| Скилл | Репо | Зачем |
|---|---|---|
| `claude-seo` | https://github.com/AgriciDaniel/claude-seo | 19 суб-скиллов: техническое SEO, schema, локальное SEO |

## Большие паки (если нужно много сразу)

| Пак | Репо | Содержит |
|---|---|---|
| antigravity-awesome-skills | https://github.com/sickn33/antigravity-awesome-skills | 1340+ скиллов, npm-инсталлер |
| awesome-claude-skills | https://github.com/travisvn/awesome-claude-skills | Каталог с разделом web/design |

---

## Конструкторы с MCP

Для сайта-визитки с конструктором и поддержкой MCP:

| Конструктор | MCP | Примечание |
|---|---|---|
| **Webflow** | ✅ Официальный MCP-сервер | Лучший вариант: дизайн + код + MCP |
| **Framer** | ⚠️ Unofficially через API | React-based, красивые анимации |
| **Tilda** | ❌ Нет MCP | Популярен в РФ, нет интеграции |

**Рекомендация:** Webflow — единственный конструктор уровня "мечты" с официальным MCP.
Но есть порог входа (английский интерфейс, платный для публикации).

---

## Как устанавливать скиллы

```bash
# Через claude CLI (если поддерживается):
claude skill install <repo-url>

# Или вручную: скачать файл скилла → положить в ~/.claude/skills/<name>/
```
