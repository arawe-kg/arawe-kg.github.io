# Общий процесс разработки

## Требования

- Разработка должна вестись согласно установленным правилам.
- Програмный код должен быть написан строго в соответствии со стилевыми стандартами.


## [Git](https://git-scm.com)

Работа с Git должна придерживаться следующих стандартов:

- [GitHub Flow](https://docs.github.com/en/get-started/using-github/github-flow)
- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0)
- [Semantic Versioning](https://semver.org)
- [Semantic Release](https://github.com/semantic-release/semantic-release)

### Ветки

- `main`: релизная ветка
- `dev`: ветка разработки
    - `fix/<название>`: ветки исправлений
    - `feat/<название>`: ветки реализации нового функционала

#### Примеры веток

- `fix/server-response`
- `feat/websockets`


### Коммиты

Сообщения коммитов должны быть следующего формата:

`<тип>(<область>): <описание>`

- Использовать только ASCII символы
- Наличие `области` опционально
- Описание должно начинаться с глагола в императивной форме

#### Типы коммитов:

- `fix` - исправление бага или недочёта
- `feat` - добавление нового функционала
- `perf` - изменения, нарушающие обратную совместимость

#### Примеры коммитов

- `fix(core): stop loop breaking when count is bigger than 21`
- `feat: add new database model`
- `perf(api): remove filtering option`


## [Asana](https://asana.com)

Раздел в разработке.
