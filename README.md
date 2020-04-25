# chui

<!-- badges -->
[![CircleCI](https://circleci.com/gh/lambdaisland/chui.svg?style=svg)](https://circleci.com/gh/lambdaisland/chui) [![cljdoc badge](https://cljdoc.org/badge/lambdaisland/chui)](https://cljdoc.org/d/lambdaisland/chui) [![Clojars Project](https://img.shields.io/clojars/v/lambdaisland/chui.svg)](https://clojars.org/lambdaisland/chui)
<!-- /badges -->

Modern ClojureScript test runner

## 錘 (锤) [chuí]

(rhymes with "hey")

- hammer
- to hammer into shape
- weight (e.g. of a steelyard or balance)

See the [Line Dict entry](https://dict.naver.com/linedict/zhendict/dict.html#/cnen/entry/cf6a566ba4a64496b8d8610525f3d9e8) for an audio sample.

<!-- opencollective -->
### Support Lambda Island Open Source

Chui is part of a growing collection of quality Clojure libraries and
tools released on the Lambda Island label. If you find value in our work please
consider [becoming a backer on Open Collective](http://opencollective.com/lambda-island#section-contribute)
<!--/opencollective -->

## Motivation

The testing library that comes with ClojureScript, `cljs.test`, consists of two
parts: an API for expressing tests and assertions, and a test runner for
executing tests. Chui re-implements the test runner part in a way that allows
more dynamic and fine-grained control, so that it forms a better base for
tooling. It also offers an attractive browser-based UI for running tests and
inspecting results.

See the [Architecture Decision Log](doc/architecture_decision_log.org) for
technical background.

## License

Copyright &copy; 2020 Arne Brasseur and Contributors

Licensed under the term of the Eclipse Public License 1.0, see LICENSE.
