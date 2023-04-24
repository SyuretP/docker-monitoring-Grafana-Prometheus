# docker-monitoring-stack-GPNC
Cadvisor monitoring and collecting containers' metrics, Node_exporter monitoring host machine.
Prometheus is ingesting the metrics scrapped by both and then we use Grafana to query the data from the datasource and visualise it in form of dashboards and configure alerts based on different conditions.

Cadvisor:
![image](https://user-images.githubusercontent.com/124918294/234123288-21f3e8ef-dac2-42b6-af33-ef754baea52b.png)

Node_exporter:
![image](https://user-images.githubusercontent.com/124918294/234123402-a367c8c4-212f-418c-aa9c-963b5d780db7.png)

alert:
![image](https://user-images.githubusercontent.com/124918294/234126214-7d0cc377-68c7-40f1-b13b-f81a496118ed.png)
![image](https://user-images.githubusercontent.com/124918294/234126280-c046647d-a423-40ba-befe-203400960a72.png)
