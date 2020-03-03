spec.alpha
========================================

spec is a Clojure library to describe the structure of data and functions. Specs can be used to validate data, conform (destructure) data, explain invalid data, generate examples that conform to the specs, and automatically use generative testing to test functions.

Clojure 1.9 depends on this library and provides it to users of Clojure. Thus, the recommended way to use this library is to add a dependency on the latest version of Clojure 1.9, rather than including it directly. In some cases, this library may release more frequently than Clojure. In those cases, you can explictly include the latest version of this library with the dependency info below.

NOTE: This library is alpha and subject to breaking changes. At a future point, there will be a non-alpha stable version of this library.

For more information:

* Rationale - https://clojure.org/about/spec
* Guide - https://clojure.org/guides/spec
* Spec split notice - https://groups.google.com/forum/#!msg/clojure/10dbF7w2IQo/ec37TzP5AQAJ

Releases and Dependency Information
========================================

Latest stable release: 0.2.187

* [All Released Versions](https://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22org.clojure%22%20AND%20a%3A%22spec.alpha%22)
* [Development Snapshot Versions](https://oss.sonatype.org/index.html#nexus-search;gav~org.clojure~spec.alpha~~~)

[deps.edn](https://clojure.org/guides/deps_and_cli) dependency information:

    org.clojure/spec.alpha {:mvn/version "0.2.187"}

[Leiningen](https://github.com/technomancy/leiningen) dependency information:

    [org.clojure/spec.alpha "0.2.187"]

[Maven](https://maven.apache.org/) dependency information:

    <dependency>
      <groupId>org.clojure</groupId>
      <artifactId>spec.alpha</artifactId>
      <version>0.2.187</version>
    </dependency>

Developer Information
========================================

* [API docs](https://clojure.github.io/spec.alpha/)
* [GitHub project](https://github.com/clojure/spec.alpha)
* [Changelog](https://github.com/clojure/spec.alpha/blob/master/CHANGES.md)
* [Bug Tracker](https://clojure.atlassian.net/browse/CLJ)
* [Continuous Integration](https://build.clojure.org/job/spec.alpha/)
* [Compatibility Test Matrix](https://build.clojure.org/job/spec.alpha-test-matrix/)

Copyright and License
========================================

Copyright (c) Rich Hickey, and contributors, 2018-2020. All rights reserved.  The use and distribution terms for this software are covered by the Eclipse Public License 1.0 (https://opensource.org/licenses/eclipse-1.0.php) which can be found in the file epl-v10.html at the root of this distribution. By using this software in any fashion, you are agreeing to be bound bythe terms of this license.  You must not remove this notice, or any other, from this software.
