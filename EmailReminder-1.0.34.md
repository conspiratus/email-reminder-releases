## 1.0.34

- Kept Reminder tasks in Incoming until their status changes, while acknowledging their queue delivery after local persistence so it cannot repeat every lease cycle.
- Made scheduled NHI task notifications one-shot across inbox refreshes and app restarts.
- Added supported NHI Bridge fields for listing and updating existing tasks, including their due date.

