# elk_hw
### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

### Решение 1. Elasticsearch 

![img](https://github.com/valery-dubinin/elk_hw/blob/main/img/1.png)
---

### Задание 2. Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.

### Решение 2. Kibana

![img](https://github.com/valery-dubinin/elk_hw/blob/main/img/3.png)
---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

### Решение 3. Logstash

Сделал через Filebeat который отправляет в logstash

![img](https://github.com/valery-dubinin/elk_hw/blob/main/img/6.png)

---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*

### Htitybt 4. Filebeat. 

Kibana:

![img](https://github.com/valery-dubinin/elk_hw/blob/main/img/4.png)

Индексы:

![img](https://github.com/valery-dubinin/elk_hw/blob/main/img/2.png)

Место с логами в бите:

![img](https://github.com/valery-dubinin/elk_hw/blob/main/img/5.png)
