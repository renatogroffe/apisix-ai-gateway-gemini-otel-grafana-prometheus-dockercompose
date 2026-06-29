# apisix-ai-gateway-gemini-otel-grafana-prometheus-dockercompose
Scripts do Docker Compose para subida de um ambiente do APISIX com capacidade de AI Gateway. Inclui monitoramento com Grafana + OpenTelemetry + Prometheus, com geração de traces de requisições direcionadas ao APISIX e coleta de métricas. IA testada: Google Gemini.

Testes realizados no Visual Studio Code:

![Testes no VS Code](img/vscode-01.png)

Trace no Grafana Tempo:

![Trace gerado](img/tempo-01.png)

Dashboard Grafana para APISIX: **https://grafana.com/grafana/dashboards/11719-apache-apisix/**

Monitorando a instância do APISIX via dashboard Grafana:

![Dashboard APISIX](img/grafana-apisix-01.png)
