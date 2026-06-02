---
title: v3.0.0 of cupertino_http
url: https://pub.dev/packages/cupertino_http
date: '2026-05-26'
author: dart.dev
feed_url: https://pub.dev/feed.atom
---
A macOS/iOS Flutter plugin that provides access to the Foundation URL Loading System.

Changelog excerpt:
- **BREAKING CHANGE:**Remove `shouldUseExtendedBackgroundIdleMode`from `URLSessionConfiguration`.
- Support usage in Dart SDK projects.
- Fix a bug where close reasons not containing valid UTF-8 would cause an uncatchable exception to be thrown.
- Exclude unnecessary generated code. Slightly reduces disk space requirements.
- Add `URLSessionTask.taskDelegate`setter and `URLSessionTask.delegate`builder to enable use of task-level delegates.
- **BREAKING:**Update minimum supported versions to iOS [...]
