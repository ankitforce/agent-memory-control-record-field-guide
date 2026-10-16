# Operating model

A memory control record is a portable policy object for an agent memory scope. It binds a data class and scope to a retention policy, named change authority, and evidence references.

The model selection policy is separate. Model routing decides who performs a task; the memory control record decides what state may survive the task.

Required enforcement points:

- Reject writes whose class is not permitted for the scope.
- Reject reads outside the scope.
- Require named authority for retention changes.
- Make expiry observable and testable.
- Persist evidence for writes, reads, policy changes, and expiry.
