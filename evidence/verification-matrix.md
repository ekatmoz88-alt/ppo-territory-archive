# Матрица проверки источников

[Русский](#ru) | [English](#en)

<a id="ru"></a>

| Уровень доказательности | Что подтверждает | Ограничение |
|---|---|---|
| Документ технического проекта | Планируемый объём, архитектуру и требования | Не доказывает факт развёртывания |
| Спецификация интерфейса | Описанный контракт и формат обмена | Не доказывает наличие работающей интеграции |
| Скриншот | Видимый интерфейс и последовательность действий | Не подтверждает серверную логику |
| Исходный код | Реализованное поведение в исследованной версии | Не доказывает эксплуатацию в production |
| Протокол / журнал испытаний | Поведение в зафиксированных условиях испытаний | Не подтверждает все эксплуатационные условия |
| Документ о приёмке | Формальный факт приёмки и указанный объём | Необходимо сверить с оригиналом подписанного документа |

## Что ещё необходимо проверить по первичным источникам

- Полный перечень всех 17 функциональных модулей.
- Полные спецификации интерфейсов и детали протоколов внешних интеграций.
- Точные конфигурации платформ для каждой модели развёртывания.
- Исходный календарный план, акты приёмки и протоколы испытаний.
- Расшифровки сокращений, если исходный документ не даёт однозначного определения.

<a id="en"></a>

| Evidence level | What it supports | Limitation |
|---|---|---|
| Technical-project document | Intended scope, architecture and requirements | Does not prove deployment |
| Interface specification | Contract and exchange format as specified | Does not prove a live integration |
| Screenshot | Visible interface and workflow | Does not prove backend logic |
| Source code | Implemented behavior in the examined revision | Does not prove production operation |
| Test report / log | Behavior under recorded test conditions | Does not prove all operational conditions |
| Acceptance document | Formal acceptance event and stated scope | Must be checked against the original signed record |

## Outstanding source verification

- Complete list of all 17 functional modules.
- Full interface specifications and protocol details for external integrations.
- Exact platform configurations by deployment model.
- Original lifecycle schedule, acceptance acts and test reports.
- Definitions of abbreviations where the source is not unambiguous.
