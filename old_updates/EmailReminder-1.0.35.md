## 1.0.35

- Cancel a scheduled NHI reminder alert immediately when its task is completed or cancelled.
- Ignore delayed `task.ready` queue messages whose task has already been closed, preventing stale smoke-test and cancelled-task alerts.

