## Домашняя работа к занятию “Мониторинг”

### Перечислите алерты, которые настроены в Prometheus alerts:

1. jenkins_down 
2. jenkins_high_cpu 
3. jenkins_high_memory 
4. high_cpu_load 
5. high_memory_load
6. high_storage_load
7. monitor_service_down

### Перечислите количество dashboards в Grafana, для какого ПО они?

В Grafana 4 dasboards:
1. Docker Containers
2. Docker Host
3. Monitoring Services
4. Ngnix

### Сделайте скриншот работающего dashboards docker containers grafana, перечислите метрики, которые там есть:
![Screenshot](https://github.com/OxLezh/DE_Monitoring/blob/main/Снимок%20экрана%202024-02-10%20144728.png)
* CPU load, 
* CPU cores,
  Rrunning containers,
* Memory load,
* Used memory,
* System load,
* Used storage,
* Storage load,
* I/O usage,
* Container cpu usage,
* Conainer memory usage,
* Container cached memory usage,
* Container network input,
* Container network output.
