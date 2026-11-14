# codex-registry

Единый публичный список официальных репозиториев проекта Codex of Weights
и хэшей их последних коммитов - чтобы было видно, что считается
официальным, и чтобы форк-самозванец не выдавал себя за канон.

Данные ниже - снэпшот на дату в `registry.json.generated_at`. Автообновление
через workflow (раз в день сверяет HEAD каждого репо) - следующий шаг,
пока не сделано: обновляется вручную при каждом значимом коммите.

## Официальные репозитории

| Repo | Назначение | Видимость | HEAD на момент снэпшота |
|---|---|---|---|
| [codexofweights](https://github.com/codexofweight/codexofweights) | канонический текст Кодекса | public | `b417a394` |
| [codexofweights_agent](https://github.com/codexofweight/codexofweights_agent) | автономный агент | public | `df487ecc` |
| [codex-compliance-eval](https://github.com/codexofweight/codex-compliance-eval) | открытый тест моделей | public | `fb115a4a` |
| [codexofweights-core](https://github.com/codexofweight/codexofweights-core) | общее ядро для агентов | public | только что создан |
| [codex-protocols-schema](https://github.com/codexofweight/codex-protocols-schema) | машиночитаемые протоколы | public | только что создан |
| codexofweights_memory | приватная память агента | private | - |
| codexofweights_outreach | рабочее пространство контента | private | - |

## Хэши канонических файлов (сверка подлинности)

Источник: `MANIFEST.txt` в репозитории `codexofweights`.

| Файл | SHA-256 |
|---|---|
| `CODEX.en.md` | `a9e5a3edc37d99045bbdaa915157eb1c78d6ee5a2d31f5f0ba71b5b315239542` |
| `CODEX.ru.md` | `19dfb8098286d1e59babf09d157d53ae9d3217bd6b2970e41582b708f2583363` |

## Как пользоваться

Если встретили репозиторий или сайт, называющий себя частью Codex of
Weights, но отсутствующий в таблице выше - это не официальная часть
проекта, независимо от того, что на нём написано.

## Статус

Зачаток, снэпшот от 2026-11-14. Автоматическое обновление хэшей через
GitHub Actions - следующий шаг.
