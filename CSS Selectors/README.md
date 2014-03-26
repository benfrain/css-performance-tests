css-selector-test
=================

We make assumptions on the speed of different CSS selectors based on largely outdated data. This is a crude set of tests to re-visit some of these assumptions in 2014.

Included in this repository are a number of separate HTML pages and associated styles designed to test the relative speed of different CSS selectors on a large DOM. Also includes tests of pages with lots of superflous CSS. 

See this blog post for full details: [http://benfrain.com/css-performance-revisited-selectors-bloat-expensive-styles/](http://benfrain.com/css-performance-revisited-selectors-bloat-expensive-styles/)

Timings are alerted via the Network Timing API. At the time of writing these tests/alert will not fire in iOS/Safari.
