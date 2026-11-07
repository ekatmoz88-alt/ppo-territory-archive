# ППО «Территория» — функциональные модули

**Архитектурная документация:** [интерактивный каталог EN/RU — 10 схем Mermaid](https://ekatmoz88-alt.github.io/territory-descriptor-unified/materials/architecture/architecture.html) · [канонический Mermaid-источник](https://github.com/ekatmoz88-alt/territory-descriptor-unified/blob/main/materials/architecture/README.md).

[Русский](#ru) | [English](#en)

<a id="ru"></a>





## Функциональные области, выявленные в доступных материалах

- Регистрационный учёт граждан Российской Федерации.
- Процессы оформления разрешения на временное проживание (РВП).
- Процессы оформления паспорта гражданина Российской Федерации.
- Процессы, связанные с вопросами гражданства.

В исходных материалах всего упоминаются 17 функциональных модулей. Полный авторитетный перечень пока не восстановлен по первичной технической документации.

В архитектурном каталоге отдельно показана инвентаризация БД: 401 таблица с группами CORE_*, DICT_*, RP_*, FP_*, REG_*, MIG_* и другими предметными областями. Префиксы таблиц не являются подтверждённым перечнем функциональных модулей и не доказывают соответствие один к одному. Не следует выводить названия или обязанности остальных модулей только из перечисленных бизнес-областей. Идентификаторы, входные и выходные данные, а также зависимости следует добавлять только при наличии подтверждения в исходных документах или исследованной реализации.

<a id="en"></a>





## Business domains identified in available materials

- Registration records for citizens of the Russian Federation.
- Temporary residence permit (РВП) workflows.
- Russian passport workflows.
- Citizenship-related workflows.

The source materials refer to 17 functional modules in total. A complete authoritative inventory has not yet been reconstructed from primary technical documentation.

The architecture catalogue separately reports a database inventory of 401 tables grouped under CORE_*, DICT_*, RP_*, FP_*, REG_*, MIG_* and other subject areas. Table prefixes are not a verified list of functional modules and do not establish a one-to-one mapping. Do not infer names or responsibilities of the remaining modules from the business domains above. Add identifiers, inputs, outputs and dependencies only when supported by source documents or inspected implementation evidence.
