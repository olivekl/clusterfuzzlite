---
layout: default
parent: ClusterFuzzLite
title: Overview
nav_order: 1
permalink: /overview/
---

# Overview

ClusterFuzzLite makes fuzzing more valuable by:
* Fuzzing continuously.
* Catching bugs before they land in your codebase by fuzzing pull
  requests/commits.
* Providing coverage reports on which code is fuzzed.
* Managing your corpus by pruning it daily or at a specified-interval.

ClusterFuzzLite supports [libFuzzer], [AddressSanitizer], and
[UndefinedBehaviorSanitizer]. ClusterFuzzLite is modular, so you can decide which features you want to use.

Using ClusterFuzzLite entails two main steps:
1. [Integrating with ClusterFuzzLite's build system] so ClusterFuzzLite can
   build your project's fuzzers.
2. [Running ClusterFuzzLite].

[libFuzzer]: https://libfuzzer.info
[AddressSanitizer]: https://clang.llvm.org/docs/AddressSanitizer.html
[UndefinedBehaviorSanitizer]: https://clang.llvm.org/docs/UndefinedBehaviorSanitizer.html
[Integrating with ClusterFuzzLite's build system]: {{ site.baseurl }}/build-integration/
[Running ClusterFuzzLite]: {{ site.baseurl }}/running-clusterfuzzlite/
