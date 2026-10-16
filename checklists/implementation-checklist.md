# Implementation checklist

- [ ] The workflow scope and data class are explicit.
- [ ] Retention is a timestamp and a versioned policy, not an undocumented default.
- [ ] Only a named authority can change retention.
- [ ] Write and read boundaries are enforced by the system, not only described in prompts.
- [ ] Expiry is tested with a negative test.
- [ ] Evidence links write, read, policy-change, and expiry events.
- [ ] Cost reporting separates ingestion, retrieval, and storage.
