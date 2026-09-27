# AniBaka compatibility branch

This branch starts at upstream tag `2.1.7`. The `screen_brightness` package
omits the Windows dependency and federated plugin registration to avoid Windows
HDR brightness side effects in AniBaka. Its Dart API and other platforms are
unchanged. Windows brightness calls have no platform implementation.

AniBaka consumes the `screen_brightness` subdirectory as a pub Git dependency
pinned to a commit. Keep the upstream fork relationship when syncing updates.
