# ППО «Территория» — архитектура развёртывания

[Русский](#ru) | [English](#en)

<a id="ru"></a>

## Централизованное развёртывание

Централизованная модель описана как региональный или центральный экземпляр приложения, к которому пользовательские рабочие места подключаются по модели тонкого клиента. Сервисы приложения и базы данных размещаются централизованно относительно подключённых пользователей.

## Распределённое развёртывание

Распределённая модель предназначена для подразделений с нестабильным или ограниченным подключением. Для поддержки локальной работы на таких площадках используются локальные серверы приложений и баз данных.

## Автономная работа и пакетный обмен

Материалы описывают пакетную синхронизацию или репликацию с использованием съёмных носителей в условиях отсутствия постоянного соединения. Точный протокол, политика разрешения конфликтов и механизмы защиты требуют подтверждения технической документацией и данными о реализации.

Это исторические модели развёртывания, а не рекомендации по построению современной инфраструктуры.

<a id="en"></a>

## Centralized deployment

The centralized model is described as a regional or central application instance accessed by user workstations using a thin-client approach. Application and database services are hosted centrally relative to connected users.

## Distributed deployment

The distributed model is described for offices with unreliable or limited connectivity. Local application and database servers support local work at those sites.

## Offline and batch exchange

The materials describe batch synchronization or replication using removable media where continuous connectivity is unavailable. The exact protocol, conflict-resolution policy and safeguards require confirmation from technical documents and implementation evidence.

These are historical deployment models, not modern deployment recommendations.
