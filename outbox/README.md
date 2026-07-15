# host-to-vm outbox

Only `HostCoordinator` may append canonical Fast Lane envelopes here. `VmTester`
reads and validates them fail closed before taking any allow-listed diagnostic
action. Credentials are never stored in this repository.
