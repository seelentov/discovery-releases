# discovery — релизы

Скомпилированные бинарники `discovery-agent` — системы мониторинга сетевых устройств
для интернет-провайдеров. Этот репозиторий хранит только готовые сборки под разные
ОС/архитектуры и их контрольные суммы; исходный код закрытый, документация — в
[discovery-info](https://github.com/seelentov/discovery-info), удобная страница
скачивания с описанием — на [лендинге](https://seelentov.github.io/discovery-landing/download.html).

## Актуальная версия — 1.1.1

| Платформа | Файл | Размер |
|---|---|---|
| macOS (Apple Silicon) | [`v1.1.1/discovery-agent-1.1.1-macos-arm64.tar.gz`](v1.1.1/discovery-agent-1.1.1-macos-arm64.tar.gz) | 16 МБ |
| macOS (Intel) | [`v1.1.1/discovery-agent-1.1.1-macos-x86_64.tar.gz`](v1.1.1/discovery-agent-1.1.1-macos-x86_64.tar.gz) | 17 МБ |
| Windows (x86_64) | [`v1.1.1/discovery-agent-1.1.1-windows-x86_64.zip`](v1.1.1/discovery-agent-1.1.1-windows-x86_64.zip) | 24 МБ |
| Linux x86_64 (Debian/Ubuntu) | [`v1.1.1/discovery-agent-1.1.1-linux-x86_64.deb`](v1.1.1/discovery-agent-1.1.1-linux-x86_64.deb) | 9,8 МБ |
| Linux arm64 (Debian/Ubuntu) | [`v1.1.1/discovery-agent-1.1.1-linux-arm64.deb`](v1.1.1/discovery-agent-1.1.1-linux-arm64.deb) | 8,7 МБ |
| Linux x86_64 (Fedora/RHEL) | [`v1.1.1/discovery-agent-1.1.1-linux-x86_64.rpm`](v1.1.1/discovery-agent-1.1.1-linux-x86_64.rpm) | 11 МБ |
| Linux arm64 (Fedora/RHEL) | [`v1.1.1/discovery-agent-1.1.1-linux-arm64.rpm`](v1.1.1/discovery-agent-1.1.1-linux-arm64.rpm) | 10 МБ |

Контрольные суммы — [`v1.1.1/SHA256SUMS.txt`](v1.1.1/SHA256SUMS.txt). Условия
использования — [`v1.0.0/LICENSE.md`](v1.0.0/LICENSE.md) (тот же файл лежит и внутри
каждого архива).

Проверка после скачивания:
```bash
shasum -a 256 -c SHA256SUMS.txt --ignore-missing
```

## Прошлые версии

Каждая версия — отдельный каталог (`v1.0.0/`, `v0.1.0/`, ...), старые версии не
удаляются при выходе новой — если вам по какой-то причине нужна не самая свежая сборка,
она остаётся доступна.

`v0.1.0/` — внутренние тестовые сборки (только Linux `.deb`/`.rpm`, без контрольных сумм
и лицензии внутри каталога), предшествовавшие первому официальному релизу 1.0.0.
Оставлены для истории, для реального использования не рекомендуются — берите 1.0.0.

## Установка

Краткая инструкция — на [странице скачивания лендинга](https://seelentov.github.io/discovery-landing/download.html),
подробная (включая пробный период и лицензирование) — в
[discovery-info/docs/installation.md](https://github.com/seelentov/discovery-info/blob/main/docs/installation.md).

## Лицензия

Использование ПО регулируется `LICENSE.md` внутри каждой версии — пробный период до
отдельной коммерческой договорённости. Полный текст условий одинаков для всех платформ
и версий.
