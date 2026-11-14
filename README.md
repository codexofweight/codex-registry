# codex-registry

**Part of the Codex of Weights project** by Artem A. Arzamastsev (Артем Андреевич Арзамасцев). Official repositories are listed in [codex-registry](https://github.com/codexofweight/codex-registry); anything not listed there is not an official part of the project.

| Part | What it is |
|---|---|
| [codexofweights](https://github.com/codexofweight/codexofweights) · [site](https://codexofweight.github.io/codexofweights/) | the Codex text (Russian canonical, English translation), Edition 1.0, DOI [10.5281/zenodo.23545813](https://doi.org/10.5281/zenodo.23545813), [Wikidata Q141881012](https://www.wikidata.org/wiki/Q141881012) |
| [codex-protocols-schema](https://github.com/codexofweight/codex-protocols-schema) | the Protocols as machine-readable JSON, checked against the canonical text |
| [codexofweights_agent](https://github.com/codexofweight/codexofweights_agent) · [site](https://codexofweight.github.io/codexofweights_agent/) | an AI agent that follows the Protocols; code, charter, public action log |
| [codexofweights-core](https://github.com/codexofweight/codexofweights-core) | shared safety core (hash pin, limits, sandbox) for agents and workers |
| [codex-compliance-eval](https://github.com/codexofweight/codex-compliance-eval) | preregistered open tests of how models follow the Codex, with null results |
| [codex-registry](https://github.com/codexofweight/codex-registry) | the list of official repositories and canonical hashes |

Everything is published openly; only personal data is withheld.


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

## Хэши канонических файлов (сверка подлинности)

Источник: `MANIFEST.txt` в репозитории `codexofweights`.

| Файл | SHA-256 |
|---|---|
| `CODEX.en.md` | `a9e5a3edc37d99045bbdaa915157eb1c78d6ee5a2d31f5f0ba71b5b315239542` |
| `CODEX.ru.md` | `19dfb8098286d1e59babf09d157d53ae9d3217bd6b2970e41582b708f2583363` |

## Заметки о хэшах

Репозиторий агента коммитит состояние и журнал каждые ~20 минут, поэтому его `HEAD` устаревает почти сразу. Для проверки подлинности ориентируйтесь на хэши канонических файлов выше и на релизы (теги), а не на `HEAD` агента.

## Как пользоваться

Если встретили репозиторий или сайт, называющий себя частью Codex of
Weights, но отсутствующий в таблице выше - это не официальная часть
проекта, независимо от того, что на нём написано.

## Статус

Зачаток, снэпшот от 2026-11-14. Автоматическое обновление хэшей через
GitHub Actions - следующий шаг.

## Licence

MIT (`LICENSE`).
