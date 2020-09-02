# otus-lab-3
Настройка хранения метрик Prometheus
В прошлом домашнем задании вы развернули prometheus и экспортеры.

Теперь вам предстоит развернуть хранилище метрик для prometheus.

В данном дз предлагается использовать Vikotoria metrics.

Для успешного выполнения дз вам достаточно развернуть один инстанс Viktoria metrics. При это вам нельзя использовать docker образ. Viktoria metrics должна управляться при помощи Systemd.

Далее вам предстоит настроить remote write самого prometheus и подключить новый data source для Grafana.

В качестве результата дз вам нужно приложить часть конфига prometheus с описанием remote write и Systemd unit file для Viktoria metrics в примечание для преподавателя. Так же приложите скриншот дашборда любого экспортера использующий в качестве datasource Viktoria metrics.
