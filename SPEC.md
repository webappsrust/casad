# Project-Specific Overrides

- The Casad server binary runs and is built/released only for BSD and Linux platforms. The companion CLI and runtime agent follow AI.md Part 33's supported cross-platform build targets; macOS and Windows CLI/agent artifacts are in scope. Domain authentication is performed by each operating system's native platform flow (including SSSD/PAM/NSS where configured), never by the Casad CLI or telemetry agent.

## Optional parts

- PART 34: REQUIRED
