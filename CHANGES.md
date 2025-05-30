# Change Log for spec.alpha

## Version 0.5.238 on May 10, 2024

* Update dependency to Clojure 1.11.3

## Version 0.4.233 on Feb 19, 2024

* Fix typo in docstring
* Remove duplicated lazy combinator
* Update parent pom and dependency to Clojure 1.11.1

## Version 0.3.218 on Nov 26, 2021

* Update Clojure dependency to Clojure 1.10.3
* Remove locking workaround
* Add multi-spec tests

## Version 0.3.214 on Nov 23, 2021

* [CLJ-2606](https://clojure.atlassian.net/browse/CLJ-2606) Add support to transform trailing maps on instrumented functions into kvs

## Version 0.2.194 on Jan 5, 2021

* Type hint return value of s/explain-str
* Update Clojure dependency to Clojure 1.10.1

## Version 0.2.187 on Mar 3, 2020

* [CLJ-1472](https://clojure.atlassian.net/browse/CLJ-1472) Fix use of locking to be more amenable to Graal analyzer

## Version 0.2.176 on Sept 4, 2018

* [CLJ-2373](https://clojure.atlassian.net/browse/CLJ-2373) Don't print ex-info into spec errors
* [CLJ-2391](https://clojure.atlassian.net/browse/CLJ-2391) Change spec problem line print order
* [CLJ-2392](https://clojure.atlassian.net/browse/CLJ-2392) Stop prepending :args to spec problem paths
* [CLJ-2393](https://clojure.atlassian.net/browse/CLJ-2393) Sort on descending "in" length before "at" length

## Version 0.2.168 on June 26, 2018

* [CLJ-2182](https://clojure.atlassian.net/browse/CLJ-2182) Always check preds for s/& on nil input
* [CLJ-2178](https://clojure.atlassian.net/browse/CLJ-2178) Return resolved pred for s/& explain-data
* [CLJ-2177](https://clojure.atlassian.net/browse/CLJ-2177) Return valid resolved pred in s/keys explain-data
* [CLJ-2167](https://clojure.atlassian.net/browse/CLJ-2176) Properly check for int? in int-in-range?
* [CLJ-2166](https://clojure.atlassian.net/browse/CLJ-2166) added function name to instrument exception map
* [CLJ-2111](https://clojure.atlassian.net/browse/CLJ-2111) Clarify docstring for :kind in s/every
* [CLJ-2068](https://clojure.atlassian.net/browse/CLJ-2068) Capture form of set and function instances in spec
* [CLJ-2060](https://clojure.atlassian.net/browse/CLJ-2060) Remove a spec by s/def of nil
* [CLJ-2046](https://clojure.atlassian.net/browse/CLJ-2046) gen random subsets of or'd req keys in map specs
* [CLJ-2026](https://clojure.atlassian.net/browse/CLJ-2026) Prevent concurrent loads in dynaload
* [CLJ-2176](https://clojure.atlassian.net/browse/CLJ-2176) s/tuple explain-data :pred problem

## Version 0.1.143 on Oct 30, 2017

* [CLJ-2259](https://clojure.atlassian.net/browse/CLJ-2259) - map decimal? to big decimal generator (instead of bigdec?)

## Version 0.1.134 on Oct 6, 2017

* [CLJ-2103](https://clojure.atlassian.net/browse/CLJ-2103) - s/coll-of and s/every gen is very slow if :kind specified without :into
* [CLJ-2171](https://clojure.atlassian.net/browse/CLJ-2171) - Default explain printer shouldn't print root val and spec
* Mark Clojure dependency as a provided dep so it's not transitively included

## Version 0.1.123 on May 26, 2017

* No changes, just a rebuild

## Version 0.1.109 on May 26, 2017

* [CLJ-2153](https://clojure.atlassian.net/browse/CLJ-2153) - Docstring for int-in-range? and int-in now mention fixed precision constraint
* [CLJ-2085](https://clojure.atlassian.net/browse/CLJ-2085) - Add the top level spec and value to explain-data
* [CLJ-2076](https://clojure.atlassian.net/browse/CLJ-2076) - coll-of and map-of should unform their elements
* [CLJ-2063](https://clojure.atlassian.net/browse/CLJ-2063) - report explain errors in order from longest to shortest path
* [CLJ-2061](https://clojure.atlassian.net/browse/CLJ-2061) - Better error message when exercise-fn called on fn without :args spec
* [CLJ-2059](https://clojure.atlassian.net/browse/CLJ-2059) - explain-data should return resolved preds
* [CLJ-2057](https://clojure.atlassian.net/browse/CLJ-2057) - If :ret spec is not supplied, use any?

## Version 0.1.108 on May 2, 2017

* AOT compile the spec namespaces

## Version 0.1.94 on Apr 26, 2017

* Moved spec namespaces from Clojure
* Renamed spec namespaces to append ".alpha"

