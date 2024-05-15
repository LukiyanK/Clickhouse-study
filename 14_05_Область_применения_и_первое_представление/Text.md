##### Задачи: 
- Привести 2 - 3 практических примера использования БД ClickHouse в компаниях
- Уточнить специфику проекта
- Подготовить отчет со ссылками на ресурсы

#### Ответ:
- CloudFlare:
  - [Сайт компании](https://cloudflare.com)
  - [Статья компании о использовании clickhouse для анализа логов](https://blog.cloudflare.com/log-analytics-using-clickhouse)

- Kozhindev:
  - [Сайт компании](https://kozhindev.com)
  - [Статья компании о использовании clickhouse](https://tproger.ru/articles/clickhouse-kak-obrabatyvat-big-data-v-800-raz-bystree)

- Kaspersky:
  - [Сайт компании](https://kaspersky.ru)
  - [Используют как часть продукта KUMA в качестве хранилища данных](https://www.anti-malware.ru/reviews/Kaspersky-Unified-Monitoring-and-Analysis-Platform#part3)

- Yandex.cloud, SberCloud etc
  - У всех облачных провацйдров есть SaaS :)


##### Дополнительные задания

1. К каким классам систем относится ClickHouse?
2. Какую проблему вы бы решили использовать ClickHouse, а какую не стали бы им решать?
3. Где можно получить помощь по ClickHouse и куда сообщить о багах?

#### Ответ

1. Колоночная аналитическая система управления базами данных (СУБД) с открытым исходным кодом;
2. Использовать для сбора, хранения и анализа данных, например логи. Не стал бы решать задачу, когда требуется вставка большого количества мелких данных при этом доступ к этим данным должен быть без задержки, например для  межбанковских транзакций.
3.  - [Git](https://github.com/ClickHouse)
    - [Сообщество](https://t.me/clickhouse_ru)
    - [Документация](https://clickhouse.com/docs)
