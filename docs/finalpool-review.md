# Finalpool task collection

## Scope and requirements

- Reviewed all 14 developer branches and 30 previously untracked task entries in their latest named batches, using immutable branch heads.
- Required `docs/task.md` and `docs/agent_system_prompt.md`: present, nonempty, English-only. Optional `docs/user_system_prompt.md`: English-only when nonempty.
- `task_config.json`: required with nonempty `needed_mcp_servers` and nonempty `needed_local_tools` containing `claim_done`, per `tasks/examples/example-task/readme.txt`.
- `evaluation/main.py`, `preprocess/main.py`, `groundtruth_workspace`, and `initial_workspace` are optional. No additional implementation-content or runtime checks were imposed.

## Results

- New tasks: 30 implementing, 0 implemented. Every new task is missing `task_config.json`; four have an additional English-only violation.
- Existing Task Tracker statuses were preserved (54 implemented and 33 implementing).
- The pool contains all 54 tasks marked implemented in Notion after this review, copied without modifications from the recorded developer-branch commits. These older statuses were not revalidated as part of the requested latest-task review.
- The blank-name task in the yuxuan-dev commit was recorded in Notion as `Unnamed task (tasks/yuxuan)`; its files live directly under that developer directory.
- The latest lueyang-dev commit names territory-manager and client-portal, but only changes territory-manager files. Both untracked tasks already existed earlier; both were audited at the current branch head.

## New task status review

| Developer branch | Task | Status | Blockers |
| --- | --- | --- | --- |
| fan-dev | discount-calculator | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| fan-dev | loyalty-program | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| gyy | robots-handler | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| gyy | sitemap-generator | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| gyy | tag-manager | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| haoze | media-organizer | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| haoze | streaming-service | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| jl_dev | customer-feedback-processor | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| jl_dev | inventory-management | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| junteng_dev | customer-portal | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| junteng_dev | help-desk | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| junxian_dev | currency-converter | implementing | docs/task.md contains Chinese; English-only content required; Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| junxian_dev | social-connector | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| lueyang-dev | client-portal | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| lueyang-dev | territory-manager | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| lv | analytics-dashboard | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| lv | insights-engine | implementing | docs/agent_system_prompt.md contains Chinese; English-only content required; Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| lv | survey-builder | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| ruige | log-analyzer | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| ruige | web-crawler | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| wenshuo-dev | cache-optimizer | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| wenshuo-dev | scheduler | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| xiaochen_dev | health-monitor | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| xiaochen_dev | status-checker | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| yuxuan-dev | Unnamed task (tasks/yuxuan) | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| yuxuan-dev | sync-service | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| yuzhen-dev | audit-logger | implementing | docs/agent_system_prompt.md contains Chinese; English-only content required; Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| yuzhen-dev | resource-monitor | implementing | docs/agent_system_prompt.md contains Chinese; English-only content required; Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| zhaochen | certificate-manager | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |
| zhaochen | storage-manager | implementing | Missing task_config.json (needed_mcp_servers must be nonempty; needed_local_tools must be nonempty and include claim_done) |

## Included tasks

See `finalpool-manifest.json` for exact source commits, paths, source tree SHAs, file SHAs, and corresponding Notion entries.

| Developer branch | Source task | Destination |
| --- | --- | --- |
| fan-dev | `tasks/fan/coupon-manager` | `tasks/finalpool/coupon-manager` |
| fan-dev | `tasks/fan/price-tracker` | `tasks/finalpool/price-tracker` |
| gyy | `tasks/gyy/blog-engine` | `tasks/finalpool/blog-engine` |
| gyy | `tasks/gyy/cms-builder` | `tasks/finalpool/cms-builder` |
| gyy | `tasks/gyy/content-scheduler` | `tasks/finalpool/content-scheduler` |
| gyy | `tasks/gyy/social-publisher` | `tasks/finalpool/social-publisher` |
| haoze | `tasks/haoze/subtitle-generator` | `tasks/finalpool/subtitle-generator` |
| haoze | `tasks/haoze/video-trimmer` | `tasks/finalpool/video-trimmer` |
| jl_dev | `tasks/jl/canvas-grade-automation` | `tasks/finalpool/canvas-grade-automation` |
| jl_dev | `tasks/jl/email-classification-system` | `tasks/finalpool/email-classification-system` |
| jl_dev | `tasks/jl/pdf-report-generator` | `tasks/finalpool/pdf-report-generator` |
| junteng_dev | `tasks/junteng/booking-system` | `tasks/finalpool/booking-system` |
| junteng_dev | `tasks/junteng/calendar-sync` | `tasks/finalpool/calendar-sync` |
| junteng_dev | `tasks/junteng/contact-manager` | `tasks/finalpool/contact-manager` |
| junteng_dev | `tasks/junteng/order-processor` | `tasks/finalpool/order-processor` |
| junteng_dev | `tasks/junteng/product-catalog` | `tasks/finalpool/product-catalog` |
| junteng_dev | `tasks/junteng/reminder-service` | `tasks/finalpool/reminder-service` |
| junteng_dev | `tasks/junteng/shipment-tracker` | `tasks/finalpool/shipment-tracker` |
| junxian_dev | `tasks/junxian/qr-generator` | `tasks/finalpool/qr-generator` |
| junxian_dev | `tasks/junxian/translation-api` | `tasks/finalpool/translation-api` |
| lueyang-dev | `tasks/lueyang/activity-logger` | `tasks/finalpool/activity-logger` |
| lueyang-dev | `tasks/lueyang/crm-system` | `tasks/finalpool/crm-system` |
| lueyang-dev | `tasks/lueyang/deal-manager` | `tasks/finalpool/deal-manager` |
| lueyang-dev | `tasks/lueyang/email-campaign` | `tasks/finalpool/email-campaign` |
| lueyang-dev | `tasks/lueyang/follow-up-reminder` | `tasks/finalpool/follow-up-reminder` |
| lueyang-dev | `tasks/lueyang/sales-pipeline` | `tasks/finalpool/sales-pipeline` |
| lv | `tasks/lv/chat-bot` | `tasks/finalpool/chat-bot` |
| lv | `tasks/lv/feedback-collector` | `tasks/finalpool/feedback-collector` |
| lv | `tasks/lv/personalization-service` | `tasks/finalpool/personalization-service` |
| lv | `tasks/lv/sentiment-analyzer` | `tasks/finalpool/sentiment-analyzer` |
| lv | `tasks/lv/voice-processor` | `tasks/finalpool/voice-processor` |
| ruige | `tasks/ruige/canvas-automation` | `tasks/finalpool/canvas-automation` |
| ruige | `tasks/ruige/data-analytics` | `tasks/finalpool/data-analytics` |
| ruige | `tasks/ruige/expense-tracker` | `tasks/finalpool/expense-tracker` |
| ruige | `tasks/ruige/file-manager` | `tasks/finalpool/file-manager` |
| wenshuo-dev | `tasks/wenshuo/image-processor` | `tasks/finalpool/image-processor` |
| wenshuo-dev | `tasks/wenshuo/search-engine` | `tasks/finalpool/search-engine` |
| xiaochen_dev | `tasks/xiaochen/backup-utility` | `tasks/finalpool/backup-utility` |
| xiaochen_dev | `tasks/xiaochen/deployment-tool` | `tasks/finalpool/deployment-tool` |
| xiaochen_dev | `tasks/xiaochen/error-tracker` | `tasks/finalpool/error-tracker` |
| xiaochen_dev | `tasks/xiaochen/monitoring-agent` | `tasks/finalpool/monitoring-agent` |
| xiaochen_dev | `tasks/xiaochen/security-scanner` | `tasks/finalpool/security-scanner` |
| yuxuan-dev | `tasks/yuxuan/asset-optimizer` | `tasks/finalpool/asset-optimizer` |
| yuxuan-dev | `tasks/yuxuan/content-manager` | `tasks/finalpool/content-manager` |
| yuxuan-dev | `tasks/yuxuan/network-analyzer` | `tasks/finalpool/network-analyzer` |
| yuxuan-dev | `tasks/yuxuan/task-scheduler` | `tasks/finalpool/task-scheduler` |
| yuzhen-dev | `tasks/yuzhen/alert-system` | `tasks/finalpool/alert-system` |
| yuzhen-dev | `tasks/yuzhen/data-validator` | `tasks/finalpool/data-validator` |
| yuzhen-dev | `tasks/yuzhen/form-builder` | `tasks/finalpool/form-builder` |
| yuzhen-dev | `tasks/yuzhen/invoice-generator` | `tasks/finalpool/invoice-generator` |
| yuzhen-dev | `tasks/yuzhen/payment-processor` | `tasks/finalpool/payment-processor` |
| yuzhen-dev | `tasks/yuzhen/permission-manager` | `tasks/finalpool/permission-manager` |
| zhaochen | `tasks/zhaochen/load-balancer` | `tasks/finalpool/load-balancer` |
| zhaochen | `tasks/zhaochen/template-engine` | `tasks/finalpool/template-engine` |
