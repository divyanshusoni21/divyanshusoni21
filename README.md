- Backend Engineer experienced building and maintaining `Python/Django` systems end-to-end. Tech Stacks : `PostgreSQL`, `Celery`, `Docker`.

- Have Worked on `Whatsapp Cloud APIs` to build a fully functional Whatsapp BSP enabling Live Chat (using Meta `Webhooks` for receiving incoming message events and `SSE` to stream real-time updates directly to the agent dashboard without page refreshes) and Campaign creation (sending up to `5,000` messages in a single broadcast, supporting dynamic template variable mapping and automated retry logic for failed deliveries).
  
- Architected an automated news ingestion cron pipeline running every 5min. Scrapes the feed url, does `deduplication`, filtering and tag assignment, fires an `OpenAI API` call for sentiment analysis. Uses `ThreadPoolExecutor` for concurrency. ([https://dailystockhunt.com](https://dailystockhunt.com))
  
- Created a portfolio project to be able to clip a youtube video with its url and desired time-range ([https://yt-vidclipper-fe.vercel.app](https://yt-vidclipper-fe.vercel.app)). Uses celery queues `video`(video clipping, video speed manipulation) and `default`(email, cleanup old files), Containerized with Docker, Hosted on DigitalOcean, `CI/CD` with GitHub Actions.
  
- Well-versed in production Celery resilience and performance tuning (`task_acks_late`, `worker_prefetch_multiplier=1`, `soft/hard time limits`, `task_reject_on_worker_lost`, and handling poison pill tasks).
