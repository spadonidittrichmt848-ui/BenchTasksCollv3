# Final pool

All tasks marked `implemented` in the Notion **Task Tracker → Task Status Table**, collected from the developer branches of `BenchTasksCollv3`.

Each task directory is copied verbatim from its source branch. Tasks still `implementing` are excluded.

## Provenance

| Task | Source branch |
| --- | --- |
| activity-logger | `lueyang-dev` |
| alert-system | `yuzhen-dev` |
| analytics-dashboard | `lv` |
| asset-optimizer | `yuxuan-dev` |
| backup-utility | `xiaochen_dev` |
| blog-engine | `gyy` |
| booking-system | `junteng_dev` |
| cache-optimizer | `wenshuo-dev` |
| calendar-sync | `junteng_dev` |
| canvas-automation | `ruige` |
| canvas-grade-automation | `jl_dev` |
| certificate-manager | `zhaochen` |
| chat-bot | `lv` |
| client-portal | `lueyang-dev` |
| cms-builder | `gyy` |
| contact-manager | `junteng_dev` |
| content-manager | `yuxuan-dev` |
| content-scheduler | `gyy` |
| coupon-manager | `fan-dev` |
| crm-system | `lueyang-dev` |
| customer-feedback-processor | `jl_dev` |
| customer-portal | `junteng_dev` |
| data-analytics | `ruige` |
| data-validator | `yuzhen-dev` |
| deal-manager | `lueyang-dev` |
| deployment-tool | `xiaochen_dev` |
| discount-calculator | `fan-dev` |
| email-campaign | `lueyang-dev` |
| email-classification-system | `jl_dev` |
| error-tracker | `xiaochen_dev` |
| expense-tracker | `ruige` |
| feedback-collector | `lv` |
| file-manager | `ruige` |
| follow-up-reminder | `lueyang-dev` |
| form-builder | `yuzhen-dev` |
| health-monitor | `xiaochen_dev` |
| help-desk | `junteng_dev` |
| image-processor | `wenshuo-dev` |
| inventory-management | `jl_dev` |
| invoice-generator | `yuzhen-dev` |
| load-balancer | `zhaochen` |
| log-analyzer | `ruige` |
| loyalty-program | `fan-dev` |
| media-organizer | `haoze` |
| monitoring-agent | `xiaochen_dev` |
| network-analyzer | `yuxuan-dev` |
| order-processor | `junteng_dev` |
| payment-processor | `yuzhen-dev` |
| pdf-report-generator | `jl_dev` |
| permission-manager | `yuzhen-dev` |
| personalization-service | `lv` |
| price-tracker | `fan-dev` |
| product-catalog | `junteng_dev` |
| qr-generator | `junxian_dev` |
| reminder-service | `junteng_dev` |
| robots-handler | `gyy` |
| sales-pipeline | `lueyang-dev` |
| scheduler | `wenshuo-dev` |
| search-engine | `wenshuo-dev` |
| security-scanner | `xiaochen_dev` |
| sentiment-analyzer | `lv` |
| shipment-tracker | `junteng_dev` |
| sitemap-generator | `gyy` |
| social-connector | `junxian_dev` |
| social-publisher | `gyy` |
| status-checker | `xiaochen_dev` |
| storage-manager | `zhaochen` |
| streaming-service | `haoze` |
| subtitle-generator | `haoze` |
| survey-builder | `lv` |
| sync-service | `yuxuan-dev` |
| tag-manager | `gyy` |
| task-scheduler | `yuxuan-dev` |
| template-engine | `zhaochen` |
| territory-manager | `lueyang-dev` |
| translation-api | `junxian_dev` |
| video-trimmer | `haoze` |
| voice-processor | `lv` |
| web-crawler | `ruige` |

## Newly reviewed tasks (latest commit on each developer branch)

- Implemented: 25
- Implementing: 4 — `currency-converter` (junxian_dev), `insights-engine` (lv), `audit-logger` and `resource-monitor` (yuzhen-dev)

The four implementing tasks contain Chinese text in `docs/task.md` or `docs/agent_system_prompt.md`, which violates the English-only requirement in `tasks/examples/example-task/docs`.

`yuxuan-dev` also contains an unnamed/malformed task submission at `tasks/yuxuan/{docs,evaluation,groundtruth_workspace}` (no task directory name); it is not a valid task and is excluded from the pool.
