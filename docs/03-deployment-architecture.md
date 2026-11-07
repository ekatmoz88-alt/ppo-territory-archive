# ППО «Территория» — архитектура развёртывания

**Архитектурные схемы:** [интерактивный каталог EN/RU](https://ekatmoz88-alt.github.io/territory-descriptor-unified/materials/architecture/architecture.html) · [канонический Mermaid-источник](https://github.com/ekatmoz88-alt/territory-descriptor-unified/blob/main/materials/architecture/README.md#4-ppo-territory--deployment-architecture-evidence-status).

[Русский](#ru) | [English](#en)

<a id="ru"></a>

[Интерактивная схема архитектуры развёртывания](https://ekatmoz88-alt.github.io/territory-descriptor-unified/materials/architecture/architecture.html#deployment)


[Интерактивная схема архитектуры развёртывания](https://ekatmoz88-alt.github.io/territory-descriptor-unified/materials/architecture/architecture.html#deployment)


## Централизованное развёртывание

Централизованная модель описана как региональный или центральный экземпляр приложения, к которому пользовательские рабочие места подключаются по модели тонкого клиента. Сервисы приложения и базы данных размещаются централизованно относительно подключённых пользователей.

## Распределённое развёртывание

Распределённая модель предназначена для подразделений с нестабильным или ограниченным подключением. Для поддержки локальной работы на таких площадках используются локальные серверы приложений и баз данных.

## Размещение серверов и автономный обмен

Исходные материалы описывают два варианта размещения: сервер приложения и сервер базы данных могут быть раздельными либо совмещёнными. Отдельно приведён профиль выделенного сервера меньшей мощности.

Для площадок без постоянного соединения описан пакетный обмен или репликация с использованием съёмных носителей. Точный протокол, расписание передачи, политика разрешения конфликтов и механизмы защиты требуют подтверждения технической документацией и данными о реализации.

Документация также указывает два варианта размещения серверов приложения и БД: раздельное или совмещённое. Отдельно описан профиль выделенного сервера меньшей мощности. Фактическая конфигурация конкретного региона не установлена.

Это исторические модели развёртывания, а не рекомендации по построению современной инфраструктуры.

<a id="en"></a>

[Interactive deployment architecture diagram](https://ekatmoz88-alt.github.io/territory-descriptor-unified/materials/architecture/architecture.html#deployment)


[Interactive deployment architecture diagram](https://ekatmoz88-alt.github.io/territory-descriptor-unified/materials/architecture/architecture.html#deployment)


## Centralized deployment

The centralized model is described as a regional or central application instance accessed by user workstations using a thin-client approach. Application and database services are hosted centrally relative to connected users.

## Distributed deployment

The distributed model is described for offices with unreliable or limited connectivity. Local application and database servers support local work at those sites.

## Server placement and offline exchange

The source materials describe two server-placement alternatives: the application server and database server may be separate or combined. A distinct lower-capacity dedicated-server profile is also described.

For sites without continuous connectivity, the materials describe batch exchange or replication using removable media. The exact protocol, transfer schedule, conflict-resolution policy and safeguards require confirmation from technical documents and implementation evidence.

The documentation also specifies two application/database server-placement alternatives: separate servers or a combined server. A lower-capacity dedicated-server profile is described separately. The actual configuration of a particular region has not been established.

These are historical deployment models, not modern deployment recommendations.
