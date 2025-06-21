# HSE Coursework: Redis в Kubernetes

Этот репозиторий содержит манифесты и скрипты для деплоя Redis в Kubernetes-кластере.

## Структура
- `deployment/deployment.yaml` — манифест Deployment для Redis
- `deployment/service.yaml` — манифест Service для Redis
- `deploy.sh` — автоматический деплой Redis
- `stop.sh` — удаление всех ресурсов Redis из кластера

## Быстрый старт
1. Запустите деплой:
   ```bash
   ./deploy.sh
   ```
2. Для удаления:
   ```bash
   ./stop.sh
   ```
