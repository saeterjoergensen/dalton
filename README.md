> [!NOTE]
> This project is decommissioned and intentionally non-operational

# dalton
## Discord Membership Bot

> "All you have to do is follow three simple rules. One, never underestimate your opponent. Expect the unexpected. Two, take it outside. Never start anything inside the bar unless it's absolutely necessary. And three, be nice."<br>
—Dalton, *Road House* (1989)

Dalton is a Discord bot that verifies users against an external membership API.

### Status

- Runtime logic has been removed.
- The entrypoint exits immediately with a decommission message.
- No credential loading remains in repository code.

### Security posture

- No active secret files are tracked in the repository.
- Legacy token and password values must still be treated as compromised if they were ever exposed.
- Historical leak risk is handled by credential rotation and decommissioning, not by current code state.

### Repository intent

This repository is kept only as an archival record. It is not intended for deployment.
