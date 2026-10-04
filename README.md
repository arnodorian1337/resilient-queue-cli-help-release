# Resilient queue compatibility fixture

This small repository contains a deterministic queue worker and the compatibility
utility used by the Windows release jobs.

The worker has no third-party dependencies. The checked-in compatibility utility
lets release jobs validate their cached runtime data without installing a build
toolchain.
