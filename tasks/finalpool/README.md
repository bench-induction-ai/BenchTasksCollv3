# Final task pool

This pool contains all 54 tasks marked **implemented** in the Task Tracker at the time of collection.

Task Tracker: https://app.notion.com/p/Task-Tracker-1-3ee7ed3946dc818db9d6d76138183651

Each task directory is an unchanged copy from its implementor's developer branch. `manifest.json` records source commits and source paths.

## Review scope

The latest task work on all 14 developer branches was reviewed: 30 task additions, including one unnamed task under `tasks/yuxuan`. All were marked **implementing** because `task_config.json` is absent. The example requires non-empty `needed_mcp_servers` and non-empty `needed_local_tools` including `claim_done`. Four latest tasks also contain Chinese in documentation required to be English-only.

The example explicitly makes user_system_prompt.md, evaluation/main.py, preprocess/main.py, initial_workspace, and groundtruth_workspace optional. Missing optional files do not block a task. No implementation quality, functionality, or additional content requirements were imposed.

Existing implemented tracker entries were preserved, not reclassified: the request is to include all tasks marked implemented in Notion, not to re-audit earlier tasks. No missing configuration was fabricated.

## Included tasks

| Task | Developer branch | Original path | Files |
| --- | --- | --- | ---: |
| activity-logger | lueyang-dev | `tasks/lueyang/activity-logger` | 5 |
| alert-system | yuzhen-dev | `tasks/yuzhen/alert-system` | 5 |
| asset-optimizer | yuxuan-dev | `tasks/yuxuan/asset-optimizer` | 5 |
| backup-utility | xiaochen_dev | `tasks/xiaochen/backup-utility` | 4 |
| blog-engine | gyy | `tasks/gyy/blog-engine` | 6 |
| booking-system | junteng_dev | `tasks/junteng/booking-system` | 7 |
| calendar-sync | junteng_dev | `tasks/junteng/calendar-sync` | 6 |
| canvas-automation | ruige | `tasks/ruige/canvas-automation` | 5 |
| canvas-grade-automation | jl_dev | `tasks/jl/canvas-grade-automation` | 4 |
| chat-bot | lv | `tasks/lv/chat-bot` | 6 |
| cms-builder | gyy | `tasks/gyy/cms-builder` | 7 |
| contact-manager | junteng_dev | `tasks/junteng/contact-manager` | 6 |
| content-manager | yuxuan-dev | `tasks/yuxuan/content-manager` | 7 |
| content-scheduler | gyy | `tasks/gyy/content-scheduler` | 5 |
| coupon-manager | fan-dev | `tasks/fan/coupon-manager` | 4 |
| crm-system | lueyang-dev | `tasks/lueyang/crm-system` | 7 |
| data-analytics | ruige | `tasks/ruige/data-analytics` | 5 |
| data-validator | yuzhen-dev | `tasks/yuzhen/data-validator` | 5 |
| deal-manager | lueyang-dev | `tasks/lueyang/deal-manager` | 5 |
| deployment-tool | xiaochen_dev | `tasks/xiaochen/deployment-tool` | 6 |
| email-campaign | lueyang-dev | `tasks/lueyang/email-campaign` | 6 |
| email-classification-system | jl_dev | `tasks/jl/email-classification-system` | 6 |
| error-tracker | xiaochen_dev | `tasks/xiaochen/error-tracker` | 5 |
| expense-tracker | ruige | `tasks/ruige/expense-tracker` | 5 |
| feedback-collector | lv | `tasks/lv/feedback-collector` | 5 |
| file-manager | ruige | `tasks/ruige/file-manager` | 4 |
| follow-up-reminder | lueyang-dev | `tasks/lueyang/follow-up-reminder` | 5 |
| form-builder | yuzhen-dev | `tasks/yuzhen/form-builder` | 3 |
| image-processor | wenshuo-dev | `tasks/wenshuo/image-processor` | 6 |
| invoice-generator | yuzhen-dev | `tasks/yuzhen/invoice-generator` | 4 |
| load-balancer | zhaochen | `tasks/zhaochen/load-balancer` | 4 |
| monitoring-agent | xiaochen_dev | `tasks/xiaochen/monitoring-agent` | 5 |
| network-analyzer | yuxuan-dev | `tasks/yuxuan/network-analyzer` | 3 |
| order-processor | junteng_dev | `tasks/junteng/order-processor` | 4 |
| payment-processor | yuzhen-dev | `tasks/yuzhen/payment-processor` | 5 |
| pdf-report-generator | jl_dev | `tasks/jl/pdf-report-generator` | 6 |
| permission-manager | yuzhen-dev | `tasks/yuzhen/permission-manager` | 5 |
| personalization-service | lv | `tasks/lv/personalization-service` | 4 |
| price-tracker | fan-dev | `tasks/fan/price-tracker` | 4 |
| product-catalog | junteng_dev | `tasks/junteng/product-catalog` | 6 |
| qr-generator | junxian_dev | `tasks/junxian/qr-generator` | 6 |
| reminder-service | junteng_dev | `tasks/junteng/reminder-service` | 4 |
| sales-pipeline | lueyang-dev | `tasks/lueyang/sales-pipeline` | 3 |
| search-engine | wenshuo-dev | `tasks/wenshuo/search-engine` | 7 |
| security-scanner | xiaochen_dev | `tasks/xiaochen/security-scanner` | 5 |
| sentiment-analyzer | lv | `tasks/lv/sentiment-analyzer` | 4 |
| shipment-tracker | junteng_dev | `tasks/junteng/shipment-tracker` | 3 |
| social-publisher | gyy | `tasks/gyy/social-publisher` | 5 |
| subtitle-generator | haoze | `tasks/haoze/subtitle-generator` | 6 |
| task-scheduler | yuxuan-dev | `tasks/yuxuan/task-scheduler` | 3 |
| template-engine | zhaochen | `tasks/zhaochen/template-engine` | 3 |
| translation-api | junxian_dev | `tasks/junxian/translation-api` | 5 |
| video-trimmer | haoze | `tasks/haoze/video-trimmer` | 4 |
| voice-processor | lv | `tasks/lv/voice-processor` | 5 |
